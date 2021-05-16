# Ortelius GitOps
This repository is for gitops research

https://github.com/ortelius/gitops

# Whitepaper link
Link to whitepaper doc: https://docs.google.com/document/d/1Kef4pt4fePhc3Ahsll-Dg4i4BGRZIow8512Bl8T8Gbo/edit?usp=sharing

# Fortnighty meeting
This will occur every second week at 8:30am - 9:30
Please add yourself to the calendar:
https://docs.ortelius.io/guides/contributorguide/things-to-know/things-to-know/#register-to-the-google-groups-and-join-discord

# Contributors
* Brad McCoy ([@bradmccoydev](https://github.com/bradmccoydev))

# Pull Request
Use the Cheatsheet here to add your name to the contributors:
https://docs.ortelius.io/guides/contributorguide/pull-request-cheat-sheet/

# DeployHub Saas
URL: https://console.deployhub.com/dmadminweb/Login#dhmain
Username: bmccoy
Password: Ask @bradmccoydev for the password
Your CLIENTID is f37d4df8-bb32-43fa-a5bb-e9d7ea7ab448 and will be needed when you install your DeployHub Reverse Proxy. See below.

# Important Links
https://docs.deployhub.com/userguide/first-steps/
https://docs.deployhub.com/userguide/installation-and-support/0-saas-and-reverse-proxy/

# CNCF Working Group
slack.cncf.io
Channels: wg-gitops, wg-gitops-principles

# Docker
To Build the docker image:
``` docker build . -t bradmccoydev/ortelius ```
``` docker tag bradmccoydev/ortelius bradmccoydev/ortelius:latest ```
``` docker push bradmccoydev/ortelius:latest ```