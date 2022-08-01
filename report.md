---
title: "ソフトウェア工学特論Ⅲレポート"
author: "FM22109 田中 湧大"
date: "2022年08月01日"
subject: "Markdown"
fontsize: 10.5pt
listingTitle: "コード"
figPrefix: "図"
tblPrefix: "表"
eqnPrefix: "式"
lstPrefix: "コード"
header-includes:
  - \usepackage{longtable}
  - \usepackage{booktabs}
---

\renewcommand{\figurename}{図}
\renewcommand{\tablename}{表}

# ユースケース図

![ユースケース図](out/usecase/図書貸出システム_ユースケース図.png){#fig:usecase}

# クラス図

![クラス図](out/class/図書貸出システム_クラス図.png){#fig:class}

# シーケンス図

## 利用者登録

![利用者登録](out/sequence/利用者登録.png){#fig:riyou}

## ログインする

![ログインする](out/sequence/ログインする.png){#fig:login}

## 貸出手続

![貸出手続](out/sequence/貸出手続.png){#fig:lend}

## 返却手続

![返却手続](out/sequence/返却手続.png){#fig:return}

## AV室予約

![AV室予約](out/sequence/AV室予約.png){#fig:av}

## 登録ユーザ一覧表示

![登録ユーザ一覧表示](out/sequence/登録ユーザ一覧表示.png){#fig:usershow}

## 貸出中ユーザ一覧表示

![貸出中ユーザ一覧表示](out/sequence/貸出中ユーザ一覧表示.png){#fig:lendshow}

## 本の貸出を予約する

![本の貸出を予約する](out/sequence/本の貸出を予約する.png){#fig:book}
