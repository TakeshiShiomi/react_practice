# react_practice
## エレメントの作成
React.createElement(タグ名 ,属性 ,中に組み込まれるもの )
React.createElementというのは、「エレメント」を作成するためのもの。
エレメントというのは、HTMLの タグとして組み込まれているものをJavaScriptの中でオブジェクトとして扱うようにしたもの。
このエレメントを作成し組み込むことで、 HTMLのタグによる表示が作成される。

## 各種コマンド
npm init react-app プロジェクト名 (rails newみたいなもの)
npm start (rails sみたいなもの)
npm run build (プロジェクトのビルドを行う。ビルドで生成されたフォルダをサーバにアップすればアプリケーションを公開できる)

### developerツールについて
ソースコードに書かれている内容がそのまま表示されるのではなく実行時に全く別の表示に変わってしまう。
Googleクロムの拡張機能からreact developer toolsはreactの動作状況に応じて表示などを解析するツール
インストールしたらクロムの検証ツールからcomponentsに切り替える