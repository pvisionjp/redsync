# Integrate Redmine with Trello

RedSync integrates Redmine with Trello. It supports a project manager to track the project status timely and accurately without asking administrative hassles of the project members.

[Link to User's Guide](https://pvision.jp/apps/2022/03/17/redsync-power-up/)

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

The Pro version supports two-way integration. The work information like the work status, progress, and the completion date can be updated on a Card and propagated to the connected Redmine Issue. Therefore the Pro version fully enables the project tracking capability and would save your projects.

The Free version provides one-way (Redmine to Trello) integration. It is valuable for organizing project tasks as Cards based on WBS defined in Redmine, but the project tracking capability is minimal.

|Feature|Free|Pro|
|---|---|---|
|Create Card from Redmine Issue|Y|Y|
|Update schedule from Redmine Issue|Y|Y|
|Report work status on Card|-|Y|
|Report work on Card|-|Y|

# System Requirements
## Redmine
Version: 4.1, 4.2, 5.0
Protocol:

- HTTPS
- CORS

# Support
We provide RedSync power-up on an "as-is" basis with Q&A support only.

Please submit any questions or defects to this the Issues of this repository.

We welcome your feedback and feature suggestions.
