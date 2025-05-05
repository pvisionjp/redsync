# RedmineとTrelloの統合

RedSyncはRedmineをTrelloと統合します。RedSyncはプロジェクト管理者が、プロジェクトメンバーに作業負担をかけることなく、プロジェクトの状態を迅速かつ正確に追跡できるようにサポートします。

[詳細はこちら(ユーザーズガイド)](https://pvision.jp/apps/2022/03/24/redsync-power-up-jp/)

![Solution Overview](https://pvision.jp/apps/wp-content/uploads/2022/03/redsync-system-overview-jp.png)

# プロジェクトの状況把握の難しさ

プロジェクト管理者にとって、プロジェクトのスケジュールをプロジェクトメンバーと共有し、その進捗を追跡することは、極めて重要な作業です。しかしプロジェクトメンバーにとってはどうでしょうか? スケジュールの確認や進捗の報告は、しばしば事務的な負担とみなされ、後回しにされがちです。その結果、プロジェクトの問題の把握が遅れ、深刻なリスクに直面することになります。

![As-Is Solution](https://pvision.jp/apps/wp-content/uploads/2022/03/redsync-as-is-system-overview-jp.png)

# 日々のプロジェクト作業の中にプロジェクトの追跡を組み込む

RedSyncは、Trelloの日々の作業を支援する能力に、プロジェクトを追跡する機能を組み込みます。RedmineをTrelloと統合することで、プロジェクトメンバーにとって、Trelloはプロジェクトの作業と追跡を行うための、統一されたツールとなります。

![To-Be Solution](https://pvision.jp/apps/wp-content/uploads/2022/03/redmine-system-to-be-jp.png)

Trelloはプロジェクトの日々の作業を支援する優れたツールです。プロジェクト管理者は、プロジェクトの作業をカードに割り当て、そこにプロジェクトメンバーが、作業手順を追加したり、作業結果を記録したりできます。

RedSyncは、RedmineのチケットからTrelloのカードを作成することで、カードに定義された日々の作業と、チケットとして定義されたWBSを紐づけます。更にRedSyncは、カードとチケットの間で情報を同期することで、作業状況の追跡を可能にします。つまりカードとチケットは、プロジェクトの情報を共有する上で、表裏一体の関係となります。

![Card with Redmine Data](https://pvision.jp/tech/wp-content/uploads/2023/07/image.png)

その結果、

- プロジェクト管理者は、プロジェクトの作業 (カード) をWBS (チケット) に基づいて編成することができます。
- プロジェクトメンバーは、日々の作業の中で、カード上で割り当てられた作業のスケジュールや優先度を確認し、また作業の進捗について報告することができます。
- プロジェクト管理者は、各作業の進捗をRedmineのチケット上で追跡し、またガントチャートなどRedmineのレポートツールを使って、プロジェクト全体の進捗を俯瞰することができます。

# システム要求
## Redmine
バージョン: 5.0, 5.1, 6.0

プロトコル:
- HTTPS
- CORS

Redmineサーバーは、利用環境のブラウザからアクセスできる必要があります。

## ブラウザ
テスト済み: Chrome, Firefox, Safari, Edge

## サポート
RedSync Power-Upは「現状のまま (as-is) 」での提供とさせて頂きます。

質問、不具合などはこちらのIssuesでご連絡頂ければ、可能な範囲で対応させて頂きます。

ご要望についてもIssuesでお知らせ頂けると幸いです。
