# 次の一歩

「はじめの一歩」をあらかた押さえた後、覚えておきたい情報源などを紹介しています。  

## Azure Skills Navigator

「System Administrators」と「Solution Architects」へのスキルアップのロードマップ資料

[New Azure Skilling Guides\! \- Microsoft Tech Community](https://techcommunity.microsoft.com/t5/azure-infrastructure-blog/new-azure-skilling-guides/ba-p/3423689)

「Network Engineers」も追加されました。

[Azure Skills Navigator for Network Engineers](https://azure.microsoft.com/ja-jp/resources/azure-skills-navigator-for-network-engineers-/)

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
