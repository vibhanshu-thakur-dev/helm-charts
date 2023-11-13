# Vibhanshu's HELM Charts

## Index
 - echoserver

## How to use:

### Add repository

 `helm add repo <repo-label> https://vibhanshu-thakur-dev.github.io/helm-charts`
 
example: `helm add repo vrt-repo https://vibhanshu-thakur-dev.github.io/helm-charts`

### Install Chart

 `helm install <release-name> <repo-label>/<chart-name>`

example: `helm install ping-server vrt-repo/echoserver`