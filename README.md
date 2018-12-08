## 漢字書けな～い。 Web アプリ

![スクリーンショット](/screenshot.jpg)

「漢字書けな～い。」は大きく表示する事で、漢字を見やすくするツールです。<br />
Web アプリにした事で、多くの OS・環境でいろんな表示が可能になっています。<br />
「漢字書けな～い！」シリーズは Windows・Mac OS 8/9 を原作に、様々なアプリで公開されています。

## 使用方法

「漢字書けな～い。」の Web サイトも参照して下さい。

- [漢字書けな～い。 https://kanji-kakenai.jimdo.com/](https://kanji-kakenai.jimdo.com/)

サーバは [Netlify](https://www.netlify.com/) を用いて公開しています。

JavaScript を用いて右下 ＋ ・ － ボタンでフォントサイズを可変できるバージョンです。

- [フォント可変版 https://kanji.netlify.com/](https://kanji.netlify.com/)

またはフォントのポイント別に HTML を分けています。

- [フォント 64 ポイント https://kanji.netlify.com/64.html](https://kanji.netlify.com/64.html)
- [フォント 96 ポイント https://kanji.netlify.com/96.html](https://kanji.netlify.com/96.html)
- [フォント 128 ポイント https://kanji.netlify.com/128.html](https://kanji.netlify.com/128.html)
- [フォント 160 ポイント https://kanji.netlify.com/160.html](https://kanji.netlify.com/160.html)
- [フォント 192 ポイント https://kanji.netlify.com/192.html](https://kanji.netlify.com/192.html)
- [フォント 224 ポイント https://kanji.netlify.com/224.html](https://kanji.netlify.com/224.html)
- [フォント 256 ポイント https://kanji.netlify.com/256.html](https://kanji.netlify.com/256.html)

表示先は真っ白になりますが、これで正常です。画面全体が入力枠になっていて、<br />
入力する事で大きく表示されます。

## 応用例

実際の動作例は次のページにあります。

- [Web アプリ | 漢字書けな～い。 https://kanji-kakenai.jimdo.com/web-アプリ/](https://kanji-kakenai.jimdo.com/web-%E3%82%A2%E3%83%97%E3%83%AA/)


### リンクをクリックして、パソコン版アプリサイズで表示（画像の表示）

```
<div><a onclick="window.open('https://kanji.netlify.com/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes'); return false;" href="javascript:void window.open('https://kanji.netlify.com/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes')">漢字書けな〜い。を起動</a></div>
```

### ブックマークレット（ブックマークに入れて起動）

```
javascript:window.open('https://kanji.netlify.com/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes')
```

### iframe （Web サイト貼り付け・ブログパーツ等に）

```
<iframe src="https://kanji.netlify.com/96.html" width="100%" height="300" frameborder="0"></iframe>
```

## 公開元・原作

「漢字書けな～い。」は 中仙道 太郎 氏製作「漢字書けな〜い！」シリーズ作品です。<br />
原作者 中仙道 太郎 氏より許可をいただいています。

- [漢字書けな～い。 https://kanji-kakenai.jimdo.com/](https://kanji-kakenai.jimdo.com/)
- **原作 漢字書けな～い！** [iSoftware](http://nakasendo.com/isoft.html) | [最愛のiMacを創る会](http://nakasendo.com/) 
