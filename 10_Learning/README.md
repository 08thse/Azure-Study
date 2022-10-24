# はじめの一歩

Azureのスキルアップにあたり、とっつきやすい＆覚えておきたい情報源などを紹介しています。  
基本的には、入門向けのコンテンツから順に紹介しているイメージです。

## Microsoft Learn

[Microsoft Learn](https://docs.microsoft.com/ja-jp/learn/)

言わずと知れた学習サイト。まずはここで勉強するのが良いかと。

### コレクション機能

Web 上にて様々なコレクションが公開されていることがありますので、それらのラーニングパスを参考にしてみるのも良いと思います。

* [Microsoft Learn Advent Calendar 2021 \- Adventar](https://adventar.org/calendars/6891)
* [Microsoft Learn Advent Calendar 2020 \- Adventar](https://adventar.org/calendars/5090)

## Azure Skills Navigator

「System Administrators」と「Solution Architects」へのスキルアップのロードマップ資料

[New Azure Skilling Guides\! \- Microsoft Tech Community](https://techcommunity.microsoft.com/t5/azure-infrastructure-blog/new-azure-skilling-guides/ba-p/3423689)

## Microsoft Virtual Training Days

[Virtual Training Days](https://www.microsoft.com/ja-jp/events/top/training-days)

無償で開催されるトレーニングイベントのスケジュール。一部のコースは資格試験の受験バウチャも配布される。

### Azure Fundamentals (AZ-900)

[試験 AZ\-900: Microsoft Azure Fundamentals \- Certifications \| Microsoft Learn](https://learn.microsoft.com/ja-jp/certifications/exams/az-900)

一番入門向けなAzure資格。まずはここから取得してみましょう。

## Azure Developer College

[Azure Developer Colleges](https://azuredevcollege.com/)

英語ではあるものの [Github 上にあるコンテンツ](https://github.com/azuredevcollege/trainingdays) が充実した内容で、Azure におけるシステム開発に必要な知識について、その周辺知識とともにレクチャーしています。

周辺の技術知識も含めてガッツリ学びたい方は、時間を見つけて一通り流してみることをオススメします。

## Azure の開発者ガイド (The Developer's Guide to Azure)

[Azure の開発者ガイド \- アプリの開発 \| Microsoft Azure](https://azure.microsoft.com/ja-jp/campaigns/developer-guide/)

アプリ開発に関わる Azure の各種サービスの概要・使いどころやクラウドネイティブ構成などをざっと説明。日本語 (2022年2月更新) 版も提供されているが上記ページからは DL できないみたい。下記から入手可能。

[開発者向け Azure へのガイド](https://clouddamcdnprodep.azureedge.net/gdc/gdcuKUFQc/original)

## @msdevjp (Twitter)

[Microsoft Tech Twitter (@msdevjp)](https://twitter.com/msdevjp)

日本マイクロソフトの公式Twitterアカウント。セミナ情報や記事情報など、かなり良い情報をまとめて発信してくれています。

## Microsoft Base コンテンツ ポータル

[Microsoft Base コンテンツ ポータル](https://www.microsoft.com/ja-jp/events/azurebase/contents/)

技術営業向けくらいのドキュメントが多め。ただ、この中の FGCF (Financial-grade Cloud Fundamentals) は技術的にも濃い資料。

## Microsoft Documents

[Azure のドキュメント](https://docs.microsoft.com/ja-jp/azure/)

公式マニュアル。意外とチュートリアルやベストプラクティスが充実しているので、設計前には熟読しておきましょう。

### Azure Advisor

[Azure Advisor のドキュメント - Azure Advisor](https://docs.microsoft.com/ja-jp/azure/advisor/)

「操作方法ガイド」配下のページはベストプラクティスとして確認しておくと良いと思います。

## Azure Update (RSS)

[Azure の更新情報](https://azure.microsoft.com/ja-jp/updates/)

最新情報はここでキャッチ。イベント後は100件を超えるアップデートが流れるので追いつくのが大変！

## 日本マイクロソフト サポート情報

[日本マイクロソフト サポート情報](https://cssjpn.github.io/)

日本の公式サポートブログの一覧が確認できて便利。各ブログでは様々な TIPS が発信されているので RSS 購読しておくと良いと思います。

## Azure アーキテクチャ センター

とにかく様々な領域のアーキテクチャに関するドキュメントがもりだくさん。全部読むのは辛いかもしれませんが、興味のあるページから読み進めると良いと思います。

[Azure アーキテクチャ センター - Azure Architecture Center](https://docs.microsoft.com/ja-jp/azure/architecture/)

### 更新情報

[What's new in Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/changelog)

更新情報は RSS で受け取ることが可能。英語版について、数日後には日本語の翻訳コンテンツが公開されることが多い印象。日本語版の更新情報は[こちら](https://docs.microsoft.com/ja-jp/azure/architecture/changelog)。

### Azure アプリケーション アーキテクチャ ガイド

[Azure アプリケーション アーキテクチャ ガイド](https://docs.microsoft.com/ja-jp/azure/architecture/guide/)

アーキテクチャ設計を俯瞰して捉えるのに良いです。Azure Well-Architected Framework 等を見ながら、適宜立ち返るのが良いでしょう。

[一部の OSS を利用する時の考慮事項](https://docs.microsoft.com/ja-jp/azure/architecture/guide/open-source-scenarios) や [一部サードパーティソフトウェアを利用する際の考慮事項](https://docs.microsoft.com/ja-jp/azure/architecture/guide/partner-scenarios) などもあります。

### .NET アプリのアーキテクチャ ガイド

[.NET アプリケーション アーキテクチャのドキュメント](https://docs.microsoft.com/ja-jp/dotnet/architecture/)

「電子書籍」に様々なアーキテクチャガイドがあります。

### Azure Well-Architected Framework

[Microsoft Azure Well-Architected Framework](https://docs.microsoft.com/ja-jp/azure/architecture/framework/)  
[Microsoft Azure Well-Architected Framework を使用して優れたソリューションを構築する](https://docs.microsoft.com/ja-jp/learn/paths/azure-well-architected-framework/)

VM や Storage Account などにおける可用性やコストの面での推奨事項がまとめられ始めており、設計時には是非見ておきたいポイントです。

* [Virtual Machines and reliability](https://docs.microsoft.com/azure/architecture/framework/services/compute/virtual-machines/reliability)
* [Virtual Machines and cost optimization](https://docs.microsoft.com/azure/architecture/framework/services/compute/virtual-machines/cost-optimization)

### Azure Well-Architected レビュー

[Azure Well-Architected レビュー](https://docs.microsoft.com/ja-jp/assessments/)

サブスクリプション (Azure アカウント) とリンクさせ、自動で Well-Architected Framework の適合状況をチェックしてくれるツール。

Microsoft的には、[定期的に実行してチェックすることをオススメ](https://techcommunity.microsoft.com/t5/azure-architecture-blog/you-finished-your-well-architect-review-now-what/ba-p/3165827)しています。

### AWS Well-Architected (Framework)

こちらは AWS の Well-Architected シリーズ。クラウドの考え方としては抽象化して Azure でも参考になるネタは多いですし、読んでおいて損はないかと。

[AWS Well\-Architected – 安全で効率的なクラウドアプリケーション](https://aws.amazon.com/jp/architecture/well-architected/?wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.sort-order=desc)

読み進め方は、[こちら](https://dev.classmethod.jp/articles/aws-well-architected-guide2022/)が大変参考になります。

## Azure 標準化ガイドライン

<https://github.com/Azure/Azure-standardization-guideline>

Azure 上にシステムを構築するにあたり検討しておいた方が良いことが詰まっています。「テーラリングが前提」ではあるものの、一旦すべて目を通しておいて損はないと思います。また、「最新情報は適宜確認すること」は重要ですね。

## Channel 9

[Channel 9](https://channel9.msdn.com/)

英語中心ですが、時々面白い動画コンテンツが公開されています。

## Workshop-O-Matic

[microsoft/workshop\-library: A library of workshops written by and for Microsoft Learn Student Ambassadors and Cloud Advocates and their local communities](https://github.com/microsoft/workshop-library)

AI系、Data系、Web系のワークショップ題材を集めたもので、どちらかというと講師向けに用意されたリポジトリとのこと。内容的には基礎レベル。

## Azure AD webinar

<https://github.com/yusukekodama/PMActivities/blob/master/Webinar/Schedule.md>

Azure AD に関するオンデマンドセミナが沢山！

## Microsoft Azure 総合事例集

[Microsoft Azure 総合事例集 [2022年9月版]](https://info.microsoft.com/JA-MigSQL-CNTNT-FY23-09Sep-28-Microsoft-Azure-Collaboration-Case-Collection-September-2022-Edition-SRGCM7842_LP01-Registration---Form-in-Body.html)

具体的な実装というよりは、どんなソリューションをどんな目的でビジネスに活用しているのか、という観点で参考に。

## その他

### AWS を知っている人が勉強を開始する際に

[AWS プロフェッショナルのための Azure \- Azure Architecture Center \| Microsoft Docs](https://docs.microsoft.com/ja-jp/azure/architecture/aws-professional/)

### 作図に便利なアプリ等

* [Draw.io](https://app.diagrams.net/)
* [ClowdSkew](https://www.cloudskew.com/)

Azureのアイコンなども簡単に利用可能。ちょっとした設計書を書く時にも便利。

* [mermaid](https://mermaid-js.github.io/mermaid/#/)

Markdown でフローチャートなどを描ける。GitHub にて表示対応。
