---
title: "社内の部活動でEC2を使いexpress.jsサーバーを立ててデプロイまでしてみた"
emoji: "🍒"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["aws", "ec2"]
# publication_name: sun_asterisk
published: false
---

## はじめに

社内には部活動制度があるのですが、その中にクラウド部（club_cloud）というクラウドに触れる部活動があります。
なんと部活動には活動費が下りるため、会社からの補助を使ってクラウドを触ることができます！！

今回その部活動として、EC2を触ってみようというハンズオン会があったため参加しました（各方面に大感謝）。


## ハンズオン会の内容

:::message
**ゴール：EC2にexpress.jsのサーバーサイドアプリケーションをデプロイする**
:::

### Step

- EC2を立てる
- SSMでEC2に接続
- デプロイ作業の準備
- 動作確認
- 後片付け（重要！）

### 使用したサービス

- EC2
- AWS Systems Manager

## 最後に
