# 発展・実践系ドキュメント

## Financial-grade Cloud Fundamentals (FGCF)

[FgCFコンテンツ一覧 \| Microsoft Base](https://www.microsoft.com/ja-jp/events/azurebase/fgcf/)

## Azure 標準化ガイドライン

<https://github.com/Azure/Azure-standardization-guideline>

Azure 上にシステムを構築するにあたり検討しておいた方が良いことが詰まっています。「テーラリングが前提」ではあるものの、一旦すべて目を通しておいて損はないと思います。また、「最新情報は適宜確認すること」は重要ですね。

## Cloud Adoption Framework (CAF)

* [Azure 向けの Microsoft Cloud 導入フレームワーク \- Cloud Adoption Framework \| Microsoft Docs](https://learn.microsoft.com/ja-jp/azure/cloud-adoption-framework/)
  * [ガバナンス ガイド](https://learn.microsoft.com/ja-jp/azure/cloud-adoption-framework/govern/)

下記の Cloud Adoption Framework CAF Boot Camp もオススメです。

* [Cloud Adoption Framework \(CAF\) Boot Camp \- YouTube](https://www.youtube.com/playlist?list=PL1RqQ3kddIpZe9hQozXALLITeTJtMiXHv)

### Azure Landing Zone

[Azure ランディング ゾーンとは \- Cloud Adoption Framework \| Microsoft Learn](https://learn.microsoft.com/ja-jp/azure/cloud-adoption-framework/ready/landing-zone/)

## Azure Review Checklists

[Azure/review\-checklists](https://github.com/Azure/review-checklists)

主に設計時に活用できる、設計考慮事項のチェックリストを作成することができる。自動翻訳だが日本語にも対応。

2022年2月現在は「Azure Kubernetes Service」「Azure Virtual Desktop」「Azure VMware Solution」「Landing Zone」「Security」といったカテゴリのみ。一般的なシステムでは「Landing Zone」と「Security」が使いやすいかと。

## Azure Well-Architected Framework

* [Microsoft Azure Well-Architected Framework](https://learn.microsoft.com/ja-jp/azure/well-architected/)
* [Microsoft Azure Well-Architected Framework を使用して優れたソリューションを構築する](https://learn.microsoft.com/ja-jp/training/paths/azure-well-architected-framework/)

VM や Storage Account などにおける可用性やコストの面での推奨事項がまとめられ始めており、設計時には是非見ておきたいポイントです。

* [Azure Well\-Architected Framework のレビュー \- Virtual Machines \- Microsoft Azure Well\-Architected Framework \| Microsoft Learn](https://learn.microsoft.com/ja-jp/azure/well-architected/services/compute/virtual-machines/virtual-machines-review)

### Well-Architected Framework 解説セッション

[Well\-Architected Framework 全体像と、5つのピラー解説](https://note.microsoft.com/CatalogueDisplay-SRDEM82102_CatalogDisplayPage.html)

## Azure Mission-Critical & Azure AlwaysOn

[Azure/Mission\-Critical](https://github.com/Azure/Mission-Critical)

その名の通り、Azure上でミッションクリティカルなシステムを実装する際の考慮事項等がまとめられている。英語なのが少し辛いですが…

## Azure Business Continuity Guide (ABC Guide)

[Azure/BusinessContinuityGuide: A BCDR guide for Microsoft Azure customers](https://github.com/Azure/BusinessContinuityGuide)

ビジネス継続性を持つために実施するアクティビティや、それに役立つツールが公開されている。英語です…

## Azure アプリケーション アーキテクチャ ガイド

[Azure アプリケーション アーキテクチャ ガイド](https://learn.microsoft.com/ja-jp/azure/architecture/guide/)

アーキテクチャ設計を俯瞰して捉えるのに良いです。Azure Well-Architected Framework 等を見ながら、適宜立ち返るのが良いでしょう。

[一部の OSS を利用する時の考慮事項](https://learn.microsoft.com/ja-jp/azure/architecture/guide/open-source-scenarios) や [一部のサードパーティソフトウェアを利用する際の考慮事項](https://learn.microsoft.com/ja-jp/azure/architecture/guide/partner-scenarios) などもあります。

## クラウドアプリケーションのベストプラクティス

[クラウド アプリケーションのベスト プラクティス](https://learn.microsoft.com/ja-jp/azure/architecture/best-practices/index-best-practices)

API 設計に始まり、キャッシュや CDN などなど、一通りのクラウド系の設計要素がまとめられたもの。

## .NET アプリのアーキテクチャ ガイド

[.NET アプリケーション アーキテクチャのドキュメント](https://learn.microsoft.com/ja-jp/dotnet/architecture/)

「電子書籍」に様々なアーキテクチャガイドがあります。

### Reliable web app pattern for .NET

[\.NET に対して信頼性の高い Web アプリ パターンを適用する \- Azure Reference Architectures \| Microsoft Learn](https://learn.microsoft.com/ja-jp/azure/architecture/reference-architectures/reliable-web-app/dotnet/apply-pattern)

.NET をベースにした高信頼 Web アプリパターンの実践。英語だが解説動画と一緒に公開されている。

## Support for Oracle Database workloads within Azure IaaS

* [Azure/Oracle\-Workloads\-for\-Azure: Oracle workloads for Azure infrastructure as a service \(Oracle Azure IaaS\)](https://github.com/Azure/Oracle-Workloads-for-Azure)
* [Oracle on Azure IaaS Recommended Practices for Success](https://github.com/Azure/Oracle-Workloads-for-Azure/blob/main/Oracle%20on%20Azure%20IaaS%20Recommended%20Practices%20for%20Success.pdf)

Azure IaaS 上で Oracle DB を実行 (移行) するにあたっての情報がまとめられている。