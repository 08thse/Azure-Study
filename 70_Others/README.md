# 雑記

調べた情報のメモや、中の人が書いた記事などを残しています。

## Azure Infrastructure

* [Azureを頑張る理由と頑張り方（Cloud Skills Challenge for NTT DATA ～2021 冬の陣～ 発表資料）](https://www.slideshare.net/nttdata-tech/azure-cloud-skills-challenge-2021-nttdata)
* [\[Azure\] コンテナイメージを作って ACR に上げるまで](https://08thse.blog.fc2.com/blog-entry-694.html)
* [Azure Service Bus (Queue) へ一度に送信できるメッセージの上限](https://zenn.dev/08thse/articles/45-azure-servicebus-send-limit)
* [Azure SQL Database をバックエンドにした自前の Web API を作るまで](https://zenn.dev/08thse/articles/43-azsql-webapi)
* [Azure App Service のサポート範囲には注意しよう](https://zenn.dev/08thse/articles/38-app-service-support)
* [Grafana (8.0) で Azure Monitor をデータソースに](https://08thse.blog.fc2.com/blog-entry-646.html)
* [[Azure] API Management で WebSocket API と連携する](https://08thse.blog.fc2.com/blog-entry-639.html)
* [Azure 環境内で ARM Template を共有する (Template Specs)](https://zenn.dev/08thse/articles/29-azure-template-specs)
* [Azure Routing Preference が GA したので価格を見てみた](https://zenn.dev/08thse/articles/18-azure-routing-preference-ga)
* [[Azure] Firewall で Web Category でのフィルタができるようになった](https://zenn.dev/08thse/articles/14-az-fw-premium-webcategory)
* [Azure VNET における同一サブネット周りの簡単な動作確認 - Qiita](https://qiita.com/08thse/items/a32b77d054523450510a)

## Azure Functions

* [[Azure] Functions 開発 (Visual Studio) で Swagger 連携](https://08thse.blog.fc2.com/blog-entry-644.html)
* [Azure Functions 非同期リクエストの実装と Core Tools](https://zenn.dev/08thse/articles/27-azfunc-async-reqrep)
* [[Azure Functions] 一定確率で少し待ってから応答を返す関数 (C#) - Qiita](https://qiita.com/08thse/items/766366e7e1f8892fe982)
* [[Azure Functions] 長めの処理時間をかける関数 (C#) - Qiita](https://qiita.com/08thse/items/13852ffd5c943e604274)
* [[Azure Functions] GREAT RACE の放送があるかどうか Slack で知らせる - Qiita](https://qiita.com/08thse/items/4fd6752211f91ae7c89b)

## Azure Kubernetes Service (AKS)

* [AKS Release Note 日本語化](https://zenn.dev/08thse/books/aks-release-notes)
* [AKS におけるリソース予約系のアップデート](https://08thse.blog.fc2.com/blog-entry-709.html)
* [AKS ScaleDown mode の違いによって、どのくらい所要時間が変わるのか？](https://zenn.dev/08thse/articles/66-aks-node-scale-down-mode)
* [AKS のノードをカーネルパニックで落として復旧動作をみる](https://zenn.dev/08thse/articles/65-aks-node-down)
* [GitHub Actions から Terraform で AKS を作成する](https://zenn.dev/08thse/articles/64-create-aks-by-terraform)
* [Kubecost で AKS のコストを可視化してみた](https://zenn.dev/08thse/articles/62-kubecost-on-aks)
* [意外と色々できる、AKS の Kusto Query](https://08thse.blog.fc2.com/blog-entry-690.html)
* [\[Azure\] Chaos Studio で AKS の Pod にカオス注入実験してみた](https://zenn.dev/08thse/articles/61-chaosstudio-aks-pod-kill)
* [WSL2 において az aks get\-credentials を反映させる](https://zenn.dev/08thse/articles/60-aks-wsl2-kubeconfig)
* [\[AKS\] クラスターのローカルアカウントの無効化と、過去の資格情報の無効化](https://zenn.dev/08thse/articles/59-aks-cert-rotate)
* [Kubernetesクラスターのノードにカオス挿入してみよう～Azure Kubernetes Serviceでカオスエンジニアリング：CodeZine（コードジン）](https://codezine.jp/article/detail/14860)
* [Bicep でカスタマイズした AKS をデプロイする](https://zenn.dev/08thse/articles/55-bicep-for-aks)
* [AKS で Azure Policy を使ってコンプライアンス管理](https://zenn.dev/08thse/articles/51-aks-azure-policy)
* [Keptn on Azure Kubernetes Service](https://zenn.dev/08thse/articles/40-aks-keptn)
* [AKS の Secrets Store CSI driver 経由で Key Vault を使う](https://zenn.dev/08thse/articles/31-aks-csi-keyvault)
* [Postgres Operator on Azure Kubernetes Service](https://zenn.dev/08thse/articles/28-aks-postgres-operator)
* [Postgres Operator on Azure Kubernetes Service (2)](https://zenn.dev/08thse/articles/30-aks-postgres-operator-2)
* [AKS で Node に接続する (kubectl debug / Azure Portal)](https://zenn.dev/08thse/articles/26-aks-connect-node)
* [AKS Engine のリポジトリを読んでみた](https://zenn.dev/08thse/articles/25-aks-engine-repo)
* [[AKS] Node の時刻同期が上手くいかなくなる場合がある](https://zenn.dev/08thse/articles/23-aks-node-timesync-error)
* [Monitoring AKS with Prometheus を試してみた](https://zenn.dev/08thse/articles/22-monitoring-aks-prometheus)
* [AKS 上で Helm を使って SQL Server をデプロイする](https://zenn.dev/08thse/articles/21-aks-helm-sql-server-2019)
* [[Azure] AKS の定時起動・停止を Azure Automation で行う](https://zenn.dev/08thse/articles/04-auto-start-aks-by-azure-runbook)
* [AKS の情報採取ツール (AKS Periscope) を試してみた](https://zenn.dev/articles/fda5527c506dfee706d6)

## Azure Container Apps

* [Azure Container Apps で、ひとつの Container App に複数のコンテナイメージを構成する](https://zenn.dev/08thse/articles/67-aca-multiple-containers)
* [Azure Container Apps で Azure Container Registry と連携する時に必要だった作業](https://08thse.blog.fc2.com/blog-entry-705.html)
* [Azure Container Apps のサンプルから見る Dapr](https://zenn.dev/08thse/articles/57-az-containerapp-sample)

## QuickStart Template 読み解き

Azure QuickStart Template の中から面白そうなものを選んで読み解いたものです。

* [[Azure] 101-cosmosdb-webapp テンプレート読み解き](https://zenn.dev/08thse/articles/03-qt-read-101-cosmosdb-webapp)
* [[Azure] 101-vm-multiple-ipconfig テンプレート読み解き](https://zenn.dev/08thse/articles/05-qt-read-101-vm-multiple-ipconfig)
* [[Azure] 101-front-door-create-basic テンプレート読み解き](https://zenn.dev/08thse/articles/06-qt-read-101-front-door-create-basic)
* [[Azure] 101-vm-sshkey ARM テンプレート読み解き](https://zenn.dev/08thse/articles/07-qt-read-101-vm-sshkey)
* [[Azure] ARM テンプレート読み解き (デプロイ後スクリプトの自動実行)](https://zenn.dev/08thse/articles/08-qt-read-101-jenkins-cluster-2-linux-1-win)
* [[Azure] ARM テンプレート読み解き (サイトの死活監視と ISO 8601)](https://zenn.dev/08thse/articles/10-qt-read-101-monitoring-webtest-metric-alert)
* [[Azure] ARM テンプレート読み解き (テンプレートからの出力)](https://zenn.dev/08thse/articles/11-qt-read-101-storage-account-create)
* [DeployToAzureポチからの卒業 / LT\_DeployToAzure \- Speaker Deck](https://speakerdeck.com/08thse/lt-deploytoazure)

## その他

* [Trivy を GitHub Actions で動かしてみた](https://08thse.blog.fc2.com/blog-entry-704.html)
* [Terraform on Azure (GROWI)](https://08thse.growi.cloud/Azure/Terraform)
* [PowerShell のソースコードと \.NET のソースコードの公開場所](https://08thse.blog.fc2.com/blog-entry-688.html)
* [Azure DB の改善アイデア投稿 \(Feature Request\) をしてみた](https://zenn.dev/08thse/articles/58-azdb-idea-request)
* [Web API (OpenAPI) の探索やテストに便利な HttpRepl を使ってみた](https://zenn.dev/08thse/articles/47-tool-httprepl)
* [Kudu 上で使えるダンプ採取ツール SmartDump](https://zenn.dev/08thse/articles/32-smartdump-on-kudu)
* [Active Directory 設計時にスルーされがちだと思うポイント](https://zenn.dev/08thse/articles/09-ad-design-point)
* [試験目的等で Active Directory を NW 分断することはできません](https://zenn.dev/08thse/articles/17-active-directory-separate)
* [コスト見積時には Reserved Instance を考慮しよう](https://zenn.dev/08thse/articles/20-cloud-check-ri-price)
* [Database (PaaS) のサポート期限はチェックしておきましょう](https://zenn.dev/08thse/articles/19-cloud-check-db-eosl)

# 書いている人

## [sou (08thse)](https://twitter.com/08thse)

* SIer勤務。得意なのはMS系だが、Linuxなど他の分野も好き。
* 基本的にはインフラ屋。なのでインフラ屋がクラウド(Azure)を勉強する視点の方が強めです。
* お仕事では、技術者育成なんかも考えながらやっています。