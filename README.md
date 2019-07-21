## Overview

Ridhwan Healthpassはすべてのあなたの健康記録のための安全なクラウドストアです.これは、世界中のすべての医療機関の健康データを保存して表示するための場所を1か所に提供することで、患者に役立ちます。 それは健康記録がブロックチェーンを介して安全に保存されていることを保証することによってプロバイダーに役立ち、彼らが患者の以前の健康歴を容易に見ることを可能にします。 このアプリを構築するために、Node.js、Firebase、Bitcoinのブロックチェーン、Paypal、Stripe、Tesserect.js、BioBERT、およびhFiguresという健康データ視覚化ライブラリを使用しました。 私がこのアプリを作成した理由は、「bitcoin」スタートアップが実際に、プログラム的に、そして視覚的にどのように見えるかについてのアイデアをあなたに与えることです。

## Dependencies
- Node.js
- Firebase
- Stripe
- Paypal 
- Proof of Existence API
- Tesserect.js
- BioBERT
- hFigures Visualization
- Nodemailer

## Usage

#### Install the dependencies using npm (replace npm with 'yarn' if npm doesn't work)
npm install

#### And start the development server
npm start

## TODOs - Make a PR if you fix any. 

- Finish integrating Proof of Existence API and the Stripe/Paypal paywall. 
- Create a proper database schema for the health data
- Add Keyword Recognition via BioBERT, use the recognized keyword categories as columns in the database
- Replace the dummy health visualization with real health data
- Add in NodeMailer

## Credits

[tesserect.js team](https://github.com/naptha/tesseract.js?ref=devawesome.i) and society for helping me live and thrive. 

