## 漢字書けな～い。 Web アプリ

![スクリーンショット](/kanji.jpg)

「漢字書けな～い。」は大きく表示する事で、漢字を見やすくするツールです。<br />
Web アプリにした事で、多くの OS・環境でいろんな表示が可能になっています。<br />
「漢字書けな～い！」シリーズは Windows・Mac OS 8/9 を原作に、様々なアプリで公開されています。

## 使用方法
「漢字書けな～い。」の Web サイトも参照して下さい。

- <a href="https://kanji-kakenai.jimdo.com/" target="_blank">漢字書けな～い。 https://kanji-kakenai.jimdo.com/</a>

フォントのポイント別に HTML を分けています。Netlify で公開しています。

- <a href="https://kanji.netlify.com/64.html" target="_blank">フォント 64 ポイント https://kanji.netlify.com/64.html</a>
- <a href="https://kanji.netlify.com/96.html" target="_blank">フォント 96 ポイント https://kanji.netlify.com/96.html</a>
- <a href="https://kanji.netlify.com/128.html" target="_blank">フォント 128 ポイント https://kanji.netlify.com/128.html</a>
- <a href="https://kanji.netlify.com/160.html" target="_blank">フォント 160 ポイント https://kanji.netlify.com/160.html</a>
- <a href="https://kanji.netlify.com/192.html" target="_blank">フォント 192 ポイント https://kanji.netlify.com/192.html</a>
- <a href="https://kanji.netlify.com/224.html" target="_blank">フォント 224 ポイント https://kanji.netlify.com/224.html</a>
- <a href="https://kanji.netlify.com/256.html" target="_blank">フォント 256 ポイント https://kanji.netlify.com/256.html</a>

表示先は真っ白になりますが、これで正常です。画面全体が入力枠になっていて、<br />
入力する事で大きく表示されます。

## 応用例

実際の動作例は次のページにあります。

- <a href="https://kanji-kakenai.jimdo.com/web-%E3%82%A2%E3%83%97%E3%83%AA/" target="_blank">Web アプリ | 漢字書けな～い。 https://kanji-kakenai.jimdo.com/web-アプリ/</a>


### リンクをクリックして、パソコン版アプリサイズで表示

```
<div><a onclick="window.open('https://kanji.netlify.com/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes'); return false;" href="javascript:void window.open('https://kanji.netlify.com/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes')">漢字書けな〜い。を起動</a></div>
```

### ブックマークレット

```
javascript:window.open('https://kanji.netlify.com/96.html', 'kanji', 'width=600,height=400,menubar=no,toolbar=no,scrollbars=yes,location=no,resizable=yes')
```

### iframe （Web サイト貼り付け・ブログパーツ等に）

```
<iframe src="https://kanji.netlify.com/96.html" width="100%" height="300" frameborder="0"></iframe>
```

## 公開元・原作

漢字書けな～い。は 中仙道 太郎 氏製作「漢字書けな〜い！」シリーズ作品です。<br />
原作者 中仙道 太郎 氏より許可をいただいています。

- <a href="https://kanji-kakenai.jimdo.com/" target="_blank">漢字書けな～い。 https://kanji-kakenai.jimdo.com/</a>
- **原作 漢字書けな～い！** <a href="http://nakasendo.com/isoft.html" target="_blank">iSoftware</a> | <a href="http://nakasendo.com/" target="_blank">最愛のiMacを創る会</a>
