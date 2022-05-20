# ハンズオン系の情報

手を動かす際に参考になるハンズオンセミナ／技術情報などを残していっています。サービスごとにまとめようと思いましたが、複数サービスを使うハンズオンなども多いため、疑似タグっぽくしてみました。

## Web Application (& Database)

* [チュートリアル: Azure App Service での ASP.NET Core および Azure SQL Database アプリの作成](https://docs.microsoft.com/ja-jp/azure/app-service/tutorial-dotnetcore-sqldb-app)  
Web Apps および Azure SQL Database で構成される Web アプリケーションをデプロイする
  * `Web Apps`, `Azure SQL Database`, `ASP.NET Core`

* [Deploy a highly available and scalable Wordpress on Azure](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/deploy-a-highly-available-and-scalable-wordpress-on-azure/ba-p/2507554)
  * `Virtual Machine Scale Set`, `Azure Database`, `Private Endpoint`, `Wordpress`

* [スケーラブルな Web アプリケーション](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/app-service-web-app/scalable-web-app)  
WebApp, Functions, Redis for Cache などなど、まとめて実装
  * `Web Apps`, `Azure SQL Database`, `Front Door`, `Functions`,`Cosmos DB`

* [POC Scenario Contoso Expenses: Deploying to App Service Environment](https://github.com/Azure/fta-internalbusinessapps/blob/master/appmodernization/app-service-environment/ase-walkthrough.md)  
  Azure Architecture Center で [安全に管理された Web アプリケーション](https://docs.microsoft.com/ja-jp/azure/architecture/example-scenario/apps/fully-managed-secure-apps) として公開されているモデル。App Service Environment での Web アプリケーションの構築ハンズオンとなっている
  * `App Service Environment`, `Azure SQL Database`, `Application Gateway`, `CI/CD`

* [Azure Cosmos DB with ASP.NET Core Web API](https://code-maze.com/azure-cosmos-db-with-asp-net-core-web-api/)  
.NET Core で Cosmos DB と連携する Web API を作成する
  * `Cosmos DB`, `ASP.NET Core`, `API Apps`

* [Azure Linux 仮想マシン上の MEAN スタックで Web アプリケーションを構築して実行する](https://docs.microsoft.com/ja-jp/learn/modules/build-a-web-app-with-mean-on-a-linux-vm/)  
MongoDB と JavaScript を使用した Web アプリ。アプリは簡素だがサンプルとしても流用できそう。
  * `MongoDB`, `JavaScript`, `Express`, `Node.js`

* [クイックスタート: ASP.NET Web アプリで Azure Cache for Redis を使用する](https://docs.microsoft.com/ja-jp/azure/azure-cache-for-redis/cache-web-app-howto)  
Cache for Redis のサンプルアプリ。サクッと試すなら Python のほうもオススメ
  * `Cache for Redis`, `ASP.NET`, `Web Apps`

* [Azure Cache for Redis のサンプル](https://docs.microsoft.com/ja-jp/azure/azure-cache-for-redis/cache-redis-samples)  
公式のリンク集。外部 GitHub などが多め
  * `Cache for Redis`

* [Azure Database for MySQL - フレキシブル サーバーを使用して WordPress アプリを AKS にデプロイする](https://docs.microsoft.com/ja-jp/azure/mysql/flexible-server/tutorial-deploy-wordpress-on-aks)  
  * `AKS`, `Azure Database`

* [クイック スタート:初めての Azure Spring Cloud アプリケーションをデプロイする](https://docs.microsoft.com/ja-jp/azure/spring-cloud/quickstart)  
  * `Java`, `Spring Cloud`

* [Spring Boot アプリを Azure にデプロイする \- Learn \| Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/modules/deploy-java-spring-boot-app-service-mysql/)  
Spring Boot アプリケーションを作成し、MySQL (Azure Database) に接続。最終的には Azure App Service にデプロイする。
  * `Java`, `Spring Boot`, `Azure Database`, `App Service`

* [クイック スタート:Microsoft ID プラットフォームを使用して ASP\.NET Core Web API を保護する](https://docs.microsoft.com/ja-jp/azure/active-directory/develop/quickstart-v2-aspnet-core-web-api)  
  ASP.NET Core にて、Azure AD 認証を要求するようにするチュートリアル
  * `.NET Core`, `ASP.NET`, `Azure AD`

## Microservices (& Kubernetes, Functions, Web API)

* [Spring マイクロサービスを Azure にデプロイする](https://docs.microsoft.com/ja-jp/learn/modules/azure-spring-cloud-workshop/)  
Azure Spring Cloud と Azure Database を使用して Spring Boot アプリをデプロイする
  * `Spring Boot`, `Azure Database`, `Java`

* [コンテナー化されたアプリケーションを Azure Kubernetes Service にデプロイする](https://docs.microsoft.com/ja-jp/learn/modules/aks-deploy-container-app/)  
AKS に簡単なアプリをデプロイしてネットワーク接続を構成する
  * `AKS`

* [チュートリアル: Azure Kubernetes Service (AKS) 用のアプリケーションの準備](https://docs.microsoft.com/ja-jp/azure/aks/tutorial-kubernetes-prepare-app)  
一連のチュートリアルを通して、ACR と連携した簡単なアプリのデプロイから構成変更までを試す
  * `AKS`, `ACR`, `Python`

* [AAD Pod Identity の使用例 - AKS の Pod にマネージド ID で Azure リソースへのアクセス権を割り当てる](https://jpaztech.github.io/blog/containers/aks-aad-pod-identity/)  
AKS の AAD Pod Identity 連携を利用して、Key Vault から接続情報を取得して Cache for Redis に接続する
  * `AKS`, `Key Vault`, `Cache for Redis`

* [AKS のマイクロサービス アーキテクチャ \- Azure Architecture Center](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/containers/aks-microservices/aks-microservices)  
リンク先の GitHub に、Kubernetes と Cosmos DB を使ったサンプルがある。が、デプロイが大変。
  * `AKS`, `Cosmos DB`

* [\.NET と ASP\.NET Core を使用してマイクロサービスを作成する \- Learn \| Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/paths/create-microservices-with-dotnet/)  
AKS 上でマイクロサービスを動作させ、サーキットブレーカーなどの様々な改修を実施していくラーニングパス
  * `AKS`, `ASP.NET`, `Polly`

* [Container Apps (Preview) Example Scenario](https://github.com/mspnp/container-apps-fabrikam-dronedelivery)  
上記の Container Apps 版
  * `Container Apps`, `Cosmos DB`, `Cache for Redis`, `Service Bus`

* [How to build a personal finance app using Azure](https://techcommunity.microsoft.com/t5/azure-ai/how-to-build-a-personal-finance-app-using-azure/ba-p/2088995)  
Cognitive Service (Form Recognizer, Cognitive Search) を利用し、レシート画像からお小遣い帳サイトを作る
  * `Cognitive Service`, `Cosmos DB`, `Cache for Redis`, `Service Bus`

* [Visual Studio で Azure 関数を開発、テスト、デプロイする \| Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/modules/develop-test-deploy-azure-functions-with-visual-studio/)  
Web API (Azure Functions) の初期サンプル。テストコードの作り方まで含んだチュートリアル 
  * `Azure Functions`, `C#`

* [チュートリアル: ASP.NET Core で Minimal Web API を作成する](https://docs.microsoft.com/aspnet/core/tutorials/min-web-api)  
Minimal Web API とインメモリの簡易 DB で Web API を作ってみるチュートリアル
  * `.NET Core`, `ASP.NET`, `Entity Framework`

* [Application Gateway と API Management で API を保護する](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/apis/protect-apis)  
API の入りの部分の考慮ポイントが分かりやすいが、バックエンドのアプリは自分で用意する必要あり
  * `Application Gateway`, `API Management`

* [Azure Functions と API Management を使用して Visual Studio でサーバーレス API を作成する](https://docs.microsoft.com/ja-jp/azure/azure-functions/openapi-apim-integrate-visual-studio)  
Functions を API Management と Swagger とで連携してデプロイまで行うチュートリアル
  * `Azure Functions`, `API Gateway`, `Swagger`

* [Azure でリアルタイムのイベント ドリブン Java ソリューションを構築する](https://docs.microsoft.com/ja-jp/learn/modules/deploy-real-time-event-driven-app/)  
[チュートリアル:Azure Cosmos DB と Event Hubs で Java 関数を使用する \| Microsoft Docs](https://docs.microsoft.com/ja-jp/azure/azure-functions/functions-event-hub-cosmos-db)  
Azure Functions と Event Hub を使用して、イベントベースの利用統計情報を Azure Cosmos DB に送信する
  * `Azure Functions`, `Cosmos DB`, `Event Hub`

* [Terraform を使用して Azure Kubernetes Service (AKS) で Kubernetes クラスターを作成する](https://docs.microsoft.com/ja-jp/azure/developer/terraform/create-k8s-cluster-with-tf-and-aks)  
  * `Terraform`, `AKS`

* [Securing an Azure Kubernetes Service deployment](https://techcommunity.microsoft.com/t5/apps-on-azure/securing-an-azure-kubernetes-service-deployment/ba-p/2838794)  
AKS を使う上で適用しておきたいセキュリティ設計等。一番最後に Azure CLI で AKS を作成する際のサンプルあり
  * `AKS`

* [Using Azure Kubernetes Service with Grafana and Prometheus \- Microsoft Tech Community](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/using-azure-kubernetes-service-with-grafana-and-prometheus/ba-p/3020459)  
AKS 上で Grafana と Prometheus を Helm でデプロイするチュートリアル的な記事
  * `AKS`, `Grafana`, `Prometheus`

* [Azure Kubernetes Service を使用して CNCF プロジェクトをビルドする \- Azure Example Scenarios \| Microsoft Docs](https://docs.microsoft.com/ja-jp/azure/architecture/example-scenario/apps/build-cncf-incubated-graduated-projects-aks)  
Jaegar や Ceph などの CNCF アプリが色々詰まった環境を Helm でデプロイする。詳細はリンク先から飛べる GitHub リポジトリを参照。
  * `Kubernetes`, `Grafana`, `Prometheus`, `Ceph`, `Jaegar`, `Harbar`, `Linkerd`, etc.

* [Using Azure Service Operator to provision and manage Azure Database for MySQL \- Flexible Server from within Kubernetes](https://techcommunity.microsoft.com/t5/azure-database-for-mysql-blog/using-azure-service-operator-to-provision-azure-db-for-mysql/ba-p/3056231)  
Azure Service Operator を利用して Azure Database のリソースを構成する方法
  * `AKS`, `Azure Database`

* [openfaas/workshop: Learn Serverless for Kubernetes with OpenFaaS](https://github.com/openfaas/workshop)  
Kubernetes 上で FaaS を実装できる [OpenFaaS](https://www.openfaas.com/) のハンズオンラボ。有志による[日本語化](https://github.com/openfaas/workshop/tree/master/translations/ja)もされている。
  * `Serverless`, `Kubernetes`, `OpenFaaS`

## Other

* [Azure Storage へのアプリの接続](https://docs.microsoft.com/ja-jp/learn/modules/connect-an-app-to-azure-storage/)  
Azure Storage の REST API と C# or JavaScript での簡単なアプリ実装
  * `Azure Storage`, `C#`, `JavaScript`

* [Azure-Network-Security/Lab Templates](https://github.com/Azure/Azure-Network-Security/tree/master/Lab%20Templates)  
Azure Firewall や Front Door などのネットワークおよびセキュリティ機能をそろえた環境を作成できる  
概要の絵などは[こちら](https://techcommunity.microsoft.com/t5/azure-network-security/azure-network-security-demo-lab-environment-with-new-updates-v2/ba-p/2892204)の記事も参照すると良い
  * `Azure Firewall`, `Front Door`, `Bastion`, `DDoS Protection`

* [Azure Stream Analytics によるストリーム処理](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/data/stream-processing-stream-analytics)  
7GB ほどのサンプルデータ付き
  * `Cosmos DB`, `Event Hubs`, `Stream Analytics`

* [対話型音声応答ボット](https://docs.microsoft.com/ja-jp/azure/architecture/solution-ideas/articles/interactive-voice-response-bot)  
  * `Web Apps`, `LUIS`, `Azure Search`, `Cosmos DB`

* [Azure Data Lake を使用したスケーラブルなデータ サイエンス : エンド ツー エンド チュートリアル](https://docs.microsoft.com/ja-jp/azure/architecture/data-science-process/data-lake-walkthrough)
  * `Azure Data Lake`, `Python`, `Azure Machine Learning`

* [Azure DevOps Starter](https://docs.microsoft.com/ja-jp/azure/devops-project/)  
Azure DevOps を利用した CI/CD 環境を簡単に作ることができる。あとはいじるだけ！
  * `Web Apps`, `CI/CD`, `Azure DevOps`, `JavaScript`, etc.

* [Bicep を使用して Azure でリソースをデプロイして管理する \- Learn \| Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/paths/bicep-deploy/)  
Bicep を学ぶならコレ。あとは実践あるのみ！
  * `Bicep`

* [Bicep アクションと GitHub アクションを使用して Azure リソースをデプロイする \- Learn \| Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/paths/bicep-github-actions/)  
Bicep ネタではあるものの、GitHub Actions の CI/CD について良くまとまっていると思います。
  * `Bicep`, `GitHub`, `CI/CD`, `Pester`

* [Get Started \- Azure \| Terraform \- HashiCorp Learn](https://learn.hashicorp.com/collections/terraform/azure-get-started)  
Terraform の Azure チュートリアル


## 検証に使えるサンプルアプリケーション等

Azure 学習目的のハンズオンではないものの、手を動かす際に活用できそうなサンプル等を残していっています。

### アプリケーション

* [TERASOLUNA Sample (Tour Reservation Sample Application)](https://github.com/terasolunaorg/terasoluna-tourreservation)  
Java および Spring ベースのフレームワークでつくられたサンプル。UI はちょっと微妙。
  * `Java`, `PostgreSQL`, `Spring`

* [Azure\-Samples/azure\-voting\-app\-redis:](https://github.com/Azure-Samples/azure-voting-app-redis)  
Azure のコンテナサービス系ではおなじみ、投票サンプルアプリケーション。永続DBは無し。
  * `AKS`, `Python`

### データベース

* [aws\-samples/aws\-database\-migration\-samples:](https://github.com/aws-samples/aws-database-migration-samples)  
[DB初学者のためのサンプルデータベース構築法 \| DevelopersIO](https://dev.classmethod.jp/articles/how-to-create-sample-database-for-begginer/)  
AWS の DMS 向けのサンプルデータベース。SQL文で流すので、たぶん Azure Database でも使えるはず
  * `Azure Database`, `Cosmod DB`

## テンプレート関連

* [Azure/azure-quickstart-templates: Azure Quickstart Templates](https://github.com/Azure/azure-quickstart-templates)  
ARM Template の テンプレート集
  * `ARM Template`
* [Azure-Sentinel/Playbooks at master · Azure/Azure-Sentinel](https://github.com/Azure/Azure-Sentinel/tree/master/Playbooks)  
Azure Sentinel の Playbook のテンプレート集
  * `Azure Sentinel`
