# KanadeSisido
🖊️Tokyo Metropolitan University<br/>
⌨️Faculty of Systems Design<br/>

# Websites
|Name|URL|
|----|----|
|Home Page |[kanade.sisido.dev](https://kanade.sisido.dev)|
|Portfolio Site|[Notion](https://daisy-share-4d5.notion.site/About-Me-3035d17ec90b80c2ac28f89021787e48)|
|Robocon-Club TEXNITIS|[robocon.texnitis-official.workers.dev](https://robocon.texnitis-official.workers.dev/)|
|HTML+CSS Tutorial|https://kanadesisido.github.io/welcome-gdgoc-2025/site/01/index.html|
|GDGoC TMU Unity Support Site|https://gdsc-tmu.github.io/event5-unity/|
|TMU Creators EXPO Official|https://gdsc-tmu.github.io/tmu-creators-expo/|


# Skills
[![My Skills](https://skillicons.dev/icons?i=ts,vue,vite,vim,tailwind,react,php,nextjs,materialui,firebase,aws,go,express,mysql&perline=7)](https://skillicons.dev)


## Backend

- **Go**
    - **Gin，Gorm，wire，gomock**
    - **Clean Archtecture, Dependency Injection，Table-Driven Test，Golden Test**
- **Node.js**
    - **Express.js**，Prisma
- PHP
    - Laravel
    - フレームワークを使わないAPI作成
- **Python**
    - FastAPI，Flask
- Google Apps Script

## Frontend

- Next.js
    - React, tailwindCSS, Shadcn/ui, MatirialUI
- TypeScript
- Vue
    - Vuetify

## Infra / Middleware

- MySQL / mariaDB
- PostgreSQL
- Redis
- Firebase
    - Firebase Auth
    - Firebase Realtime Database
    - Firebase Studio
    - Firebase Firestore
- Azure
- AWS
    - EC2
    - S3
    - Cloudfront
- Cloudflare
    - Workers
    - Tunnel
    - R2
- Docker
    - Docker Compose
- Nginx

# DevOpsなど
以下の取組みを行っています。（一部サービスが対象）

1. 自動テスト
    1. 一部のプロダクトでは、システムの可用性を保つため、Gomockを用いたTable-Driven Testを実施しております。
    2. 本番環境へのデプロイ時にはGitHubActionsを用いた自動テストを実施し、ユーザ体験に支障が出ないことを確認しています。
2. 自動デプロイ
    1. 一部のプロダクトではGitHubActionsを用いた自動デプロイを行っています。
3. 省コスト化
    1. 本番環境ではVMのコストを軽減するため、ビルド済コンテナをGHCRにアップし、それをVM上で展開する手法を採用しています。
4. セキュリティ
    1. 基本的なセキュリティ水準を担保するため、自動テスト段階で不正な入力を行い、問題がないことを確認しています。
    2. VMのポートを閉鎖し、セキュリティのリスクを移転しています。

<!---
KanadeSisido/KanadeSisido is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
