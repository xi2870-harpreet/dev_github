---
slug: challenge1
id: orkizwbw6qcz
type: challenge
title: test challenge 1
teaser: Learn how to create directory
notes:
- type: text
  contents: |-
    Please wait while we set up the first challenge

    ![k8 workflow.png](..\assets\k8 workflow.png)
tabs:
- title: Shell
  type: terminal
  hostname: container
  workdir: /etc/dropbear
- title: Webpage
  type: website
  url: https://container-15778-$_SANDBOX_ID.env.play.instruqt.com/[[ Instruqt-Var
    key="url" hostname="container" ]]
- title: google
  type: service
  hostname: container
  path: https://www.google.com/
  port: 443
  new_window: true
- title: googlewebsite
  type: website
  url: https://www.google.com/
  new_window: true
difficulty: basic
timelimit: 600
---
```sh
su - enterprisedb
```
```sh
echo $PGDATA
```
```text,nocopy
output:
/var/lib/edb/as15/data
```
```sh
vi $PGDATA/postgresql.conf
```