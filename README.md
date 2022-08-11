# React × Firebase で 簡単にチャットアプリを作成する

## アーキテクチャ

フロントエンド : React, Typescript, Chakra-UI, Formik
バックエンド : GoogleCloud(Firebase)

- Reactの`create-react-app`を、template typescript を指定してプロジェクト作成します。
- ChakraUIを用いてUIを作成します。
- Formikは、React/ChakraUIと親和性の高いフォーム用ライブラリで、入力フォームにこれを使います。
- バックエンドはすべてFirebaseにお任せします。DBはFirebsaeのRealtimeDatabaseを使います。

