# Node.js
JavaScriptで記述されたコードを実行する環境を提供するプログラムです。
Google ChromeのJavaScriptエンジン V8 が使用されています。

# JavaScript
Netscapeが開発しMozillaがメンテナンスをしているスクリプティング言語です。
現在はECMAにて標準化されECMAScriptのサブセットという位置づけになりました。

# ECMAScript
JavaScriptは標準化されていなかったため各ブラウザー間で互換性がなかったり実装が違うなどの問題がありました。
現在はECMAにて管理されており、活発な開発がなされています。
現在の最新バージョンはES2016です。この夏にはES2017の策定の完了が予定されています。

# ECMA
元々はEuropean Computer Manufacturers Associationとして設立されました。
（ヨーロッパ計算機製造協会とでも訳すのでしょうか？）
コンピュータシステムの標準化団体です。
色々な規格を標準化しており、C#やCLI(.Net)も標準化されています。

# Babel
JavaScriptにはブラウザー間、及びブラウザーバージョンにより互換性の問題が発生します。
この互換性を吸収してくれるのがBabelです。
.babelrc設定ファイルにソースコードで使用される機能、対象環境を記述し、変換処理を行うことで
対象の環境で実行可能なJavaScriptに変換してくれます。
この変換をトランスパイルと呼びます。

# Node.jsでのプログラミング
プロジェクトフォルダを作成します。今回はpracticeフォルダを作成します。

```sh
mkdir practice
cd practice
```

プロジェクトフォルダを初期化するため、npmコマンドを使用します。
npm(Node Package Manager)はプロジェクトを管理するコマンドです。
今回は対話モードを使用しないため"-y"オプションを付与しています。

```sh
npm init -y
```

npm initコマンドを実行するとpackage.jsonファイルが生成されます。
このファイルにはプロジェクトの情報や、使用するライブラリや簡易なタスク実行が記述されます。

```json
{
  "name": "practice",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
```

# Link
- [Node.js](https://nodejs.org)
- [Electron](https://electron.atom.io/)
- [Babel](http://babeljs.io/)
- [Webの進化](http://www.evolutionoftheweb.com/)


