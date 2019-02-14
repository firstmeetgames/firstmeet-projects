# firstmeet-projects
firstmeet project modules(git submodule)

## 0. 克隆主项目 
```
克隆主项目 
$ https://github.com/firstmeetgames/firstmeet-projects.git

递归克隆整个项目
$ git clone https://github.com/maonx/firstmeet-projects.git --recursive 

$ cd firstmeet-projects
```

## 1. 添加子模块
```
$ git submodule add https://github.com/firstmeetgames/mservice-grpc-apis.git                                firstmeetgames/mservice-grpc-apis 

$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-mservice-mta-track.git             ups/firstmeet-mservice-mta-track
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-mservice-paycenter.git             ups/firstmeet-mservice-paycenter
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-mservice-paycenter-000chujian.git  ups/firstmeet-mservice-paycenter-000chujian
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-mservice-shippingcenter.git        ups/firstmeet-mservice-shippingcenter
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-mservice-shoppecenter.git          ups/firstmeet-mservice-shoppecenter
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-mservice-usercenter.git            ups/firstmeet-mservice-usercenter
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-mservice-usercenter-000chujian.git ups/firstmeet-mservice-usercenter-000chujian
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-ups-configserver.git               ups/firstmeet-ups-configserver
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-ups-mservice-webhooks.git          ups/firstmeet-ups-mservice-webhooks
$ git submodule add https://devops.16801.com/bitbucket/scm/ups/firstmeet-web-pay-bluepay.git                ups/firstmeet-web-pay-bluepay

$ git submodule add https://devops.16801.com/bitbucket/scm/sdk/firstmeet-andsdk-common-utils.git            sdk/firstmeet-andsdk-common-utils
$ git submodule add https://devops.16801.com/bitbucket/scm/sdk/firstmeet-andsdk-mta-000framework.git        sdk/firstmeet-andsdk-mta-000framework
$ git submodule add https://devops.16801.com/bitbucket/scm/sdk/firstmeet-andsdk-mta-001chujian.git          sdk/firstmeet-andsdk-mta-001chujian
$ git submodule add https://devops.16801.com/bitbucket/scm/sdk/firstmeet-andsdk-thailand.git                sdk/firstmeet-andsdk-thailand
$ git submodule add https://devops.16801.com/bitbucket/scm/sdk/firstmeet-andsdk-ups-000framework.git        sdk/firstmeet-andsdk-ups-000framework
$ git submodule add https://devops.16801.com/bitbucket/scm/sdk/firstmeet-andsdk-ups-001chujian.git          sdk/firstmeet-andsdk-ups-001chujian
$ git submodule add https://devops.16801.com/bitbucket/scm/sdk/firstmeet-iossdk-thailand.git                sdk/firstmeet-iossdk-thailand
$ git submodule add https://devops.16801.com/bitbucket/scm/sdk/firstmeet-sdk-mta-java.git                   sdk/firstmeet-sdk-mta-java

$ git submodule add xxxxx.git ups/xxx
$ git submodule add xxxxx.git ups/xxx
$ git submodule add xxxxx.git ups/xxx
$ git submodule add xxxxx.git ups/xxx
$ git submodule add xxxxx.git ups/xxx
```

## 2. 更新子模块
```
更新项目内子模块到最新版本
$ git submodule update
```
```
更新子模块为远程项目的最新版本
$ git submodule update --remote
```

## 3. 查看.gitmodules
```
[submodule "mservice-grpc-apis"]
	path = mservice-grpc-apis
	url = https://github.com/firstmeetgames/mservice-grpc-apis.git
[submodule "firstmeet-mservice-mta-track"]
	path = firstmeet-mservice-mta-track
	url = https://devops.16801.com/bitbucket/scm/ups/firstmeet-mservice-mta-track.git
```