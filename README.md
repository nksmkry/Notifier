Notifier
========

## Description
send slack message

## Requirement
- Slack
- Incoming Webhooks
- Webhook URL

## Installation
`git clone https://github.com/nksmkry/notifier.git`

## Usage
0. `cd notifier/slackAPI/`
0. `echo "{Webhook URL}" > secret_url.txt`
0. `echo [title] | ./send_slack.sh [-m message] [-c channel] [-i icon] [-n botname]"`
