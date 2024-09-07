# Pagesによる日記だ
[まーくあっぷの例](https://docs.kkgithub.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists)

## 2024-09-07
Rogalia、料理が99.60を超えている。クロワッサンづくりは終わっていいかな……。
農業ステータスはニンジンだったかリンゴだったか、どちらにせよ小麦の生地と合わせて焼くだけ。
料理が100になったら剣術/陶器/釣りをあげられるんだっけ？
陶器やろうとすると採掘もあがっちゃうんで注意しとかないとね。

### Nuxtの勉強
ブログっぽいもの作るぞ！ということで[やっている](https://nuxt-blog-beta-woad.vercel.app/)。
今日はcssとtemplateだけのコンポーネント作ってみたぞ。importが自動でなされるの、ありがたいねえ。


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


