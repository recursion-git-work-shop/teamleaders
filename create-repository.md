# チーム開発で使うリポジトリの作成方法

## 概要

1. Organizationの作成とメンバーの招待
2. チーム開発用リポジトリの作り方
3. ブランチの作成方法(developブランチの作成)
4. デフォルトブランチの設定方法(developブランチをデフォルトブランチに設定する)



## 1.　Organizationの作成とメンバーの招待
## Organizationの説明
Organizationとは、複数のリポジトリをさまざまなユーザーで管理、および共同作業するための機能です。

参考図
<img width="1438" alt="スクリーンショット 2023-03-13 16 56 44" src="https://user-images.githubusercontent.com/91725975/224640628-a627741b-3bd4-414b-963f-fb037cf79bcb.png">

### 作成手順
### ①アイコンマークをクリック
<img width="1074" alt="スクリーンショット 2023-03-13 16 20 06" src="https://user-images.githubusercontent.com/91725975/224633436-d5d97be1-89a2-4194-86d1-25189486a040.png">

### ②settingsをクリック
<img width="310" alt="スクリーンショット 2023-03-13 15 58 18" src="https://user-images.githubusercontent.com/91725975/224633587-3a762b9d-642e-48a7-ad51-be4072f62647.png">

### ③Oraganizationsをクリック
<img width="1074" alt="スクリーンショット 2023-03-13 16 23 05" src="https://user-images.githubusercontent.com/91725975/224633890-466fdbd5-5270-440b-a227-24ef7e5a7467.png">

### ④New oraganizationをクリック
<img width="1074" alt="スクリーンショット 2023-03-13 16 24 32" src="https://user-images.githubusercontent.com/91725975/224634127-29f7fc1d-fe24-4d0e-89cd-75a523fe7d4f.png">

### ⑤free planを選択

<img width="1440" alt="スクリーンショット 2023-03-13 15 59 15" src="https://user-images.githubusercontent.com/91725975/224647076-ec31907b-2160-4bde-9f9a-bb6ae0a26b8d.png">

### ⑥oraganizationを作成

※名前はチームがわかるように色を入れてください（teamdev-Red等）

<img width="1440" alt="スクリーンショット 2023-03-13 16 01 28" src="https://user-images.githubusercontent.com/91725975/224647151-198147d5-373b-4f3b-be3f-9fda917a2e31.png">

### ⑦invite memberをクリックし、チームメンバーを検索、owner権限で招待する
<img width="1440" alt="スクリーンショット 2023-03-13 16 02 47" src="https://user-images.githubusercontent.com/91725975/224635577-56211599-cde8-4989-a5c2-3e276e179d31.png">

<img width="1440" alt="スクリーンショット 2023-03-13 16 15 21" src="https://user-images.githubusercontent.com/91725975/224636047-5f369c56-ca1e-44ff-b3c5-de104288a1c2.png">


## 2.　チーム開発用リポジトリの作り方
チームリーダーには、task1という課題用のリポジトリとwork-spaceという開発用のリポジトリ、これら少なくとも２つのpublicリポジトリを作っていただきます。

完成図としてはこのようになります。

<img width="1438" alt="スクリーンショット 2023-03-13 16 56 44" src="https://user-images.githubusercontent.com/91725975/224640628-a627741b-3bd4-414b-963f-fb037cf79bcb.png">

### リポジトリの作成方法

①new repositoryをクリック
<img width="1438" alt="スクリーンショット 2023-03-13 16 50 23" src="https://user-images.githubusercontent.com/91725975/224907155-1ceb82f1-809c-4beb-977b-224b6157c7bc.png">

②publicを選択
<img width="1438" alt="スクリーンショット 2023-03-13 16 51 12" src="https://user-images.githubusercontent.com/91725975/224907177-d4d2dcbb-2453-4728-bf2d-6836716f5324.png">

③２つ目のリポジトリからは画面右のnew repositoryをクリック
<img width="1438" alt="スクリーンショット 2023-03-13 16 51 34" src="https://user-images.githubusercontent.com/91725975/224907255-d32b4ad1-3ec8-47d2-9e59-54c3c776f113.png">


### task1リポジトリについて
task1リポジトリはコチラで用意した[task1リポジトリ](https://github.com/recursion-git-work-shop/task1)を参考にファイル構成や中身も全く同じように作成してください。

このリポジトリを使用してチームメンバーと課題に取り組んでいただきます。

<img width="1438" alt="スクリーンショット 2023-03-13 17 16 46" src="https://user-images.githubusercontent.com/91725975/224644407-d8516238-64e9-438a-b5a3-db4d0b9d16f7.png">

## 3.　ブランチの作成方法
### ①branchをクリック
<img width="1070" alt="スクリーンショット 2023-03-13 17 22 00" src="https://user-images.githubusercontent.com/91725975/224645625-526141f8-8358-4364-b896-1de5056b979d.png">

### ②画面右、new branchをクリック
<img width="1438" alt="スクリーンショット 2023-03-13 17 18 12" src="https://user-images.githubusercontent.com/91725975/224646043-4467aef9-cd8d-45a5-a925-9ef780256bbe.png">

### ③ブランチ名はdevelopで作成（今回の開発では全リポジトリに以下の設定を適用してください）

<img width="1438" alt="スクリーンショット 2023-03-13 17 18 34" src="https://user-images.githubusercontent.com/91725975/224646456-d9ae1aa7-2ae2-40c1-8e54-00e335210a0c.png">

## 4.　デフォルトブランチの設定方法（今回の開発では全リポジトリに以下の設定を適用してください）

### ①settingsをクリック後、branchesをクリック

<img width="1070" alt="スクリーンショット 2023-03-13 17 35 28" src="https://user-images.githubusercontent.com/91725975/224648592-291ccd47-8a67-496b-818d-36fca52dd9a2.png">

### ②矢印マークをクリック後、ブランチをmainからdevelopに変更

<img width="1070" alt="スクリーンショット 2023-03-13 17 40 22" src="https://user-images.githubusercontent.com/91725975/224649599-79236f85-867c-4ba2-923d-89a164be23fa.png">

