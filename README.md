# アプリケーション名

Support Talk  


# アプリケーション概要

医療介護の分野に特化した写真・メッセージの投稿アプリケーション  
主な対象： 医療介護を提供する人、それを受ける人  


# URL

Herokuによるデプロイ  
https://supporttalk.herokuapp.com/  

Basic認証  
ID： admin  
PW： 1111  


# テスト用アカウント

_____今後ユーザー機能実装予定  


# 利用方法

## 気持ちや出来事などの投稿、情報の発信

1. トップページのヘッダーからユーザー新規登録を行う_____今後実装予定  
2. 「投稿する」ボタンから、投稿内容（ニックネーム、画像、メッセージ）を入力し投稿する  


## 人気情報や流行の情報の取得
1. 気に入った投稿に「お気に入り」ボタンを押すことができる_____今後実装予定  
2. 投稿一覧を「人気順（お気に入り数の多い順）」に並べ替える_____今後実装予定  


# アプリケーションを作成した背景

様々なものが電子化してきており、それを扱いきれない高齢者や身体障害者は孤立してしまう傾向にある。  
また、介護が必要になったことで、その先の人生を諦めてしまう方も少なくない。  
介護において新しい情報を知ることで介護の負担を減らすことが可能となり、生活の質を向上させることに繋がる。  
そこで私は、医療介護に関連する情報の発信や、ポジティブネガティブ関係なくその気持ちを共有できる場を作りたいと考えた。  
このアプリケーションは、介護をする人だけでなく、介護される人にもぜひ使ってほしいと考えている。  


# 洗い出した要件

https://docs.google.com/spreadsheets/d/1Scl7ahtOjDz8CmmDENFtuyRRt272ub8N1BZwYlaVjZI/edit#gid=278226023  


# 実装した機能についての画像やGIF及びその説明

_____今後実装予定  


# 実装予定の機能

1. 画像投稿を画像アドレス入力ではなく、Active Storageに変更  
2. S3の導入  
3. お気に入り機能  
4. 投稿を人気順に並べ替える機能  
5. ハッシュタグなど、カテゴリーごとに投稿を検索できる機能  


# データベース設計

supporttalk.png  


# 画面遷移図

_____今後作成予定  


# 開発環境

・フロントエンド（HTML,CSS,JavaScript）  
・バックエンド（Ruby on Rails）  
・テキストエディタ  
・テスト_____今後実装予定  


# ローカルでの動作方法

% git clone https://github.com/43piyopiyo/supporttalk1  
% cd supporttalk  
% bundle install  
% rails db:create  
% rails db:migrate  
% yarn install  


# 工夫したポイント

ページ全体のイメージは“温かい”、“カフェ”、若者も好みそうなデザインを心がけた。  
投稿ボタンはカフェらしく「ビスケット」をイメージしている。  
高齢者や身体障害者が利用することを想定しているため、なるべくシンプルなデザインと必要最低限の機能にとどめている。  
一覧表示は、チェキのようなデザインにし、カーソルを合わせると分かりやすく大きく表示されるようにした。  

