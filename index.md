# pages

[まーくあっぷの例](https://docs.kkgithub.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists)

## 2024-09-06
GitHubの勉強をちょっとやりなおした。といってもGitHub - VSCode 間の連携くらいなんだけど。

### Nuxtの勉強
app.vueがある → &lt;NuxtPage&gt;がURLに対応する/page以下のコンポーネントになる。
なので、app.vueの中にNuxtPageがある状態で/indexを開くと、app.vueの中に/page/index.vueを読み込んだかたちで出てくる……でいい？

というかNuxt4使ってみたかったんだけどまだリリースされてないという。
Nuxt3からNuxt4に移行しようとするとディレクトリ構成が変わるらしく、やだなー。

ふつうにやるときはbuild、静的ホスティングをやりたいときはgenerateする。
nuxt.config.tsでssr:falseしてgenerateするとnode.js使えないところでも置けるっぽい？
よくわからん。

generateしたサイトをVSCodeのLiveServerで開いてみたらMIMEタイプエラーが起きてあきらめかけたんですが、LiveServerのルートディレクトリを指定することでなんとかなりました。


