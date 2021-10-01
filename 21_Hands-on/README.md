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

* [How to build a personal finance app using Azure](https://techcommunity.microsoft.com/t5/azure-ai/how-to-build-a-personal-finance-app-using-azure/ba-p/2088995)  
Cognitive Service (Form Recognizer, Cognitive Search) を利用し、レシート画像からお小遣い帳サイトを作る
  * `Cognitive Service`

* [Visual Studio で Azure 関数を開発、テスト、デプロイする \| Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/modules/develop-test-deploy-azure-functions-with-visual-studio/)  
Web API (Azure Functions) の初期サンプル。テストコードの作り方まで含んだチュートリアル 
  * `Azure Functions`, `C#`

* [Application Gateway と API Management で API を保護する](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/apis/protect-apis)  
API の入りの部分の考慮ポイントが分かりやすいが、バックエンドのアプリは自分で用意する必要あり
  * `Application Gateway`, `API Management`

* [Azure Functions と API Management を使用して Visual Studio でサーバーレス API を作成する](https://docs.microsoft.com/ja-jp/azure/azure-functions/openapi-apim-integrate-visual-studio)  
Functions を API Management と Swagger とで連携してデプロイまで行うチュートリアル
  * `Azure Functions`, `API Gateway`, `Swagger`


## Other

* [Azure Storage へのアプリの接続](https://docs.microsoft.com/ja-jp/learn/modules/connect-an-app-to-azure-storage/)  
Azure Storage の REST API と C# or JavaScript での簡単なアプリ実装
  * `Azure Storage`, `C#`, `JavaScript`

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


## 検証に使えるサンプルアプリケーション等

Azure 学習目的のハンズオンではないものの、手を動かす際に活用できそうなサンプル等を残していっています。

* [TERASOLUNA Sample (Tour Reservation Sample Application)](https://github.com/terasolunaorg/terasoluna-tourreservation)  
Java および Spring ベースのフレームワークでつくられたサンプル。UI はちょっと微妙。
  * `Java`, `PostgreSQL`, `Spring`