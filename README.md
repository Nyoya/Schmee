# Schmee
php自作

## 概要
学校と保護者をつなぐSNSを作成しました。  
ユーザーは4種あります。
- アプリケーション管理ユーザー
- 会員(学校代表者、学校関係者、保護者)

## 使い方
### アプリケーション管理ユーザー
テストアカウント  
メールアドレス：admin@gmail.com  
パスワード：admin
#### 詳細
登録されている学校の一覧、詳細、学校通信投稿の一覧、学校ごとのユーザー一覧が見れます。  
学校新規登録も可能です。その後代表者の登録、詳細の登録をします。  
学校の編集も可能です。
学校の削除、ユーザーの削除ができます。  

### 会員(学校代表者、学校関係者)
学校代表者テストアカウント  
メールアドレス：higuchi@example.com  
パスワード：password  
#### 詳細
学校通信の一覧、詳細、保護者一覧、保護者詳細が見れます。  
投稿したのが自身の投稿のみ削除できます。  
学校通信とユーザーの検索も可能です。  
学校通信の投稿が可能です。  
学年やクラスを指定することで指定先にしか表示されないようにできます。  
全体を選択すると学校全体に表示できます。  
email送信を選択すると指定した先に送信できます。  
学校通信にコメント、既読ができます。  
コメントしたのが自身の場合のみ削除できます。  
ダイレクトメッセージができます。  
ルーム作成はダイレクトメッセージをしたいユーザーの詳細ページに行き、右にあるメールのアイコンを押すことでできます。  
ログアウトはマイページ右上から可能です。  

### 会員(保護者)
アカウント  
メール送信を確認する場合は新規登録をお願いします。  
学校コード：B114221820072  
メールアドレス：ご自身の使用できるメールアドレスで新規登録を行なってください。  
パスワード：ご自身で登録してください。  

テストアカウント  
メール送信を確認しない場合はこちらを使用してください。  
学校コード：B114221820072  
メールアドレス：hanako.kanou@example.net  
パスワード：password  
#### 詳細
学校通信の一覧、詳細、学校関係者一覧、学校関係者詳細が見れます。  
学校通信とユーザーの検索も可能です。  
学校通信にコメント、既読ができます。  
コメントしたのが自身の場合のみ削除できます。  
ダイレクトメッセージができます。  
ルーム作成はダイレクトメッセージをしたいユーザーの詳細ページに行き、右にあるメールのアイコンを押すことでできます。  
ログアウトはマイページ右上から可能です。  

## 環境
MAMP/MySQL/PHP

## データベース
データベース名：Schmee  
テーブル：お使いのphpMyAdminに上のデータベースを作り、入っているSchmee.sqlをインポートしていただければお使いいただけるようになると思います。