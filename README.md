## 漢字書けな～い。 Web アプリ

![スクリーンショット](/screenshot.jpg)

「漢字書けな～い。」は大きく表示する事で、漢字を見やすくするツールです。\
Web アプリにした事で、多くの OS・環境でいろんな表示が可能になっています。\
「漢字書けな～い！」シリーズは Windows・Mac OS 8/9 を原作に、様々なアプリで公開されています。

「漢字書けな～い。」は 中仙道 太郎 氏製作「漢字書けな〜い！」シリーズ作品です。\
原作者 中仙道 太郎 氏より許可をいただいています。

- [**漢字書けな～い。** https://kanji-kakenai.jimdofree.com/](https://kanji-kakenai.jimdofree.com/)
- **原作 漢字書けな～い！** [iSoftware](http://nakasendo.com/isoft.html) | [最愛のiMacを創る会](http://nakasendo.com/) 

## 使用方法

サーバは [Netlify](https://www.netlify.com/) を用いて公開しています。

JavaScript を用いて右下 ＋ ・ － ボタンでフォントサイズを可変できるバージョンです。\
フォントサイズは Cookie に保存します。（使用から約 1 年有効）

- [**フォントサイズ可変版** https://kanji.balloon.net.eu.org/](https://kanji.balloon.net.eu.org/)

※ 2020年3月25日より kanji.balloon.net.eu.org へ変更しました。

またはフォントのポイント別に HTML を分けています。\
使用するフォントサイズが決まっている場合、\
JavaScript・Cookie の使用に問題がある場合はこちらを使用できます。

- [**フォント 64 ポイント** https://kanji.balloon.net.eu.org/64.html](https://kanji.balloon.net.eu.org/64.html)
- [**フォント 96 ポイント** https://kanji.balloon.net.eu.org/96.html](https://kanji.balloon.net.eu.org/96.html)
- [**フォント 128 ポイント** https://kanji.balloon.net.eu.org/128.html](https://kanji.balloon.net.eu.org/128.html)
- [**フォント 160 ポイント** https://kanji.balloon.net.eu.org/160.html](https://kanji.balloon.net.eu.org/160.html)
- [**フォント 192 ポイント** https://kanji.balloon.net.eu.org/192.html](https://kanji.balloon.net.eu.org/192.html)
- [**フォント 224 ポイント** https://kanji.balloon.net.eu.org/224.html](https://kanji.balloon.net.eu.org/224.html)
- [**フォント 256 ポイント** https://kanji.balloon.net.eu.org/256.html](https://kanji.balloon.net.eu.org/256.html)

※ 2020年4月14日より kanji.netlify.com → kanji.netlify.app へ変更されます。

表示先は真っ白になりますが、これで正常です。画面全体が入力枠になっていて、\
入力する事で大きく表示されます。

## 応用例

実際の動作例は次のページにあります。

- [**Web アプリ | 漢字書けな～い。** https://kanji-kakenai.jimdofree.com/web-アプリ/](https://kanji-kakenai.jimdofree.com/web-%E3%82%A2%E3%83%97%E3%83%AA/)


### リンクをクリックして、パソコン版アプリサイズで表示（画像の表示）

```
<div><a onclick="window.open('https://kanji.balloon.net.eu.org/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes'); return false;" href="javascript:void window.open('https://kanji.balloon.net.eu.org/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes')">漢字書けな〜い。を起動</a></div>
```

### ブックマークレット（ブックマークに入れて起動）

```
javascript:window.open('https://kanji.balloon.net.eu.org/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes')
```

### iframe （Web サイト貼り付け・ブログパーツ等に）

```
<iframe src="https://kanji.balloon.net.eu.org/96.html" width="100%" height="300" frameborder="0"></iframe>
```

## ライセンス

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />
「漢字書けな～い。Web アプリ」は <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">クリエイティブ・コモンズ 表示 4.0 国際 ライセンス</a> の下に提供されています。
