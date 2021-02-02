# 🗑 slack-cleaner

> Cleaning my Slack notifications on a regular basis.

I use Slack as a notification center for my open-source works, and CI notifications
tend to accumulate quickly.

To avoid saturating my plan with useless short-lived notification messages,
I use a GitHub Action in this repository firing each day at midnight, that
deletes all messages older than 7 days in my notification channels.

To use it in your Slack workspace, follow the instructions in [`sgratzl/slack-cleaner`](https://github.com/sgratzl/slack-cleaner).
