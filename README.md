(DRAFT - Under Preparation)

# Integrate Redmine with Trello

RedSync integrates Redmine with Trello. It supports a project manager to track the project status timely and accurately without asking administrative hassles of the project members.

[Link to Full Documentation (User's Guide)](https://pvision.jp/apps/2022/03/17/redsync-power-up/)

![Solution Overview](https://pvision.jp/apps/wp-content/uploads/2022/03/redsync-system-overview.png)

# Difficulty in tracking project

For a project manager, it is imperative to share the project schedule with the project members and track their progress timely. But what about the project members? Activities such as checking the schedule and reporting the progress are often regarded as administrative hassles and given less priority. It leads to a delay in perceiving bad signs of the project and exposes the project to critical risks.

![As-Is Solution](https://pvision.jp/apps/wp-content/uploads/2022/03/redsync-as-is-system-overview.png)

# Incorporate project tracking into day-to-day project work

RedSync incorporates the project tracking capability into Trello’s ability to support daily project work. By integrating Redmine with Trello, Trello becomes a single tool for project members to perform the project work and the project tracking.

![To-Be Solution](https://pvision.jp/apps/wp-content/uploads/2022/04/redsync-system-to-be.png)

Trello is a great tool to support daily project work. A project manager defines a work on a Card, and the project members then populate it with additional work information like work instructions and work results.

RedSync creates Cards from Redmine Issues; hence the daily work defined in Cards aligns with the project WBS defined in Issues. Then RedSync synchronizes the information between the Cards and the Issues. Thus a Card and an Issue represent each other.

![Card with Redmine Data](https://pvision.jp/apps/wp-content/uploads/2022/03/redsync-sync-card-and-issue.png)

As a result,

- A project manager can organize the work (Cards) according to WBS (Issues).
- Project members can check the schedule and priority of their assigned work on the Card and report the work’s progress as a part of day-to-day project work.
- A project manager can monitor the work progress and grasp the overall project status using the reporting tools of Redmine like the Gantt chart.

# Free version vs. Paid version

RedSync comes in two versions a free version and a paid version.

The Free version provides one-way (Redmine to Trello) integration. It is valuable for organizing project tasks as Cards based on WBS defined in Redmine, but the project tracking capability is minimal.

The Pro version supports two-way integration. The work information like the work status, progress, and the completion date can be updated on a Card and propagated to the connected Redmine Issue. Therefore the Pro version fully enables the project tracking capability and would save your projects.

|Feature|Free|Pro|
|---|---|---|
|Create Card from Redmine Issue|Y|Y|
|View work schedule on Card|Y|Y|
|View work status & progress on Card|Y|Y|
|Update schedule from Redmine Issue to Card|Y|Y|
|Report work status & progress on Card|-|Y|

# System Requirements
## Redmine
Version: 4.1, 4.2, 5.0
Protocol:

- HTTPS
- CORS

## Browser
Tested with Chrome, Firefox, Safari, Edge

# RedmineとTrelloの統合

RedSyncはRedmineをTrelloと統合します。RedSyncはプロジェクト管理者が、プロジェクトメンバーに作業負担をかけることなく、プロジェクトの状態を迅速かつ正確に追跡できるようにサポートします。

[詳細はこちら(ユーザーズガイド)](https://pvision.jp/apps/2022/03/24/redsync-power-up-jp/)

![Solution Overview](https://pvision.jp/apps/wp-content/uploads/2022/03/redsync-solution-overview.png)

# 日々のプロジェクト作業の中にプロジェクトの追跡を組み込む

Trelloはプロジェクトの日々の作業を支援する優れたツールです。

RedSyncは、Trelloのこの優れた作業支援の能力に、プロジェクトを追跡するための機能を追加します。RedSyncは、RedmineのチケットからTrelloのカードを作成し紐付けます。そしてチケットとカードの間で、プロジェクトに関する情報を同期します。

![Card with Redmine Data](https://pvision.jp/apps/wp-content/uploads/2022/03/redsync-card-and-issue.png)

その結果、

- プロジェクト管理者は、プロジェクトの作業 (カード) をWBS (チケット) に基づいて編成することができます。
- プロジェクトメンバーは、日々の作業の中で、カード上で割り当てられた作業のスケジュールや優先度を確認し、また作業の進捗について報告することができます。
- プロジェクト管理者は、各作業の進捗をRedmineのチケット上で追跡し、またガントチャートなどRedmineのレポートツールを使って、プロジェクト全体の進捗を俯瞰することができます。

# フリー vs. プロ バージョン

RedSyncは、フリーとプロの２つのバージョンで提供されます。

フリー版は、RedmineからTrelloへの片方向の統合を行います。これはWBS (チケット) に沿って作業 (カード) を編成する上で有用です。ただしTrelloからRedmineへのステータスや進捗の報告はできません。報告はRedmineのチケットに直接書き込む必要があります。(このためにカード上のリンクからチケットを開くことができます)

プロ版は、RedmineとTrelloの双方向の統合を実現します。作業のステータスや進捗をカード上で更新でき、その結果はRedmineのチケットに反映されます。これにより、プロジェクトメンバーに負担を強いることなく、プロジェクトの状況を迅速かつ正確に把握できるようになります。

|機能|フリー|プロ|
|---|---|---|
|チケットからカードを作成|◯|◯|
|作業のスケジュールをカード上で見る|◯|◯|
|作業のステータスや進捗をカード上で見る|◯|◯|
|作業のステータスや進捗をカードから報告する|-|◯|
|作業のステータスをカードから報告する|-|◯|

# システム要求
## Redmine
バージョン: 4.1, 4.2

プロトコル:
- HTTPS
- CORS

Redmineサーバーは、利用環境のブラウザからアクセスできる必要があります。

## ブラウザ
テスト済み: Chrome, Firefox, Safari, Edge
