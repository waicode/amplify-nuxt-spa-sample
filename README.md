# amplify-nuxt-spa-sample

![amplify-nuxt-spa-sample](https://main.d2elhmbkojzkli.amplifyapp.com/amplify-nuxt-spa-sample.png "amplify-nuxt-spa-sample")

<https://main.d2elhmbkojzkli.amplifyapp.com/>

* Nuxtアプリケーション（SPAモード）をAWSの`Amplify Console`（以下、Amplify）でデプロイするためのサンプルです

* `amplify.yml`を追加しbuildコマンドを`yarn run generate`に変更しています
  * Amplifyの自動デプロイ設定では`yarn run build`が実行され正常にデプロイされません

* 上記以外の設定は`create-nuxt-app`コマンドのデフォルト生成ファイルから大きな変更はしていません

```Shell
? Programming language: TypeScript
? Package manager: Yarn
? UI framework: None
? Nuxt.js modules: 利用しない
? Linting tools: ESLint, Prettier, StyleLint
? Testing framework: Jest
? Rendering mode: Single Page App
? Deployment target: Static (Static/Jamstack hosting)
? Development tools: 利用しない
? Continuous integration: GitHub Actions (GitHub only)
? What is your GitHub username? waicode
? Version control system: Git
```
