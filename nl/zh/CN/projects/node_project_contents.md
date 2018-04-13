---
copyright:
  years: 2015, 2018
lastupdated: "2018-03-16"
---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:new_window: target="_blank"}

# Node.js 项目文件
{: #node-project-files}

对于 Node.js 项目，以下信息列出了通常在 {{site.data.keyword.Bluemix}} 中可找到的内容。创建初学者工具包时，会创建这些文件。如果要迁移应用程序以在 {{site.data.keyword.Bluemix_notm}} 中进行托管，您可能希望查看这些信息以避免潜在的冲突。
{:shortdesc}

下表列出了生成的 Node.js 项目中包含的常见目录和文件。

| 目录和文件| 描述
|
|:------------------------------------------------|:------------------------------------------|
|<b>`./`</b>                                             |  |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;package.json| 元数据文件|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;cli-config.yml| CLI 配置选项|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;manifest.yml| Cloud Foundry 部署文件|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dockerfile| 用于 `bx dev run`、`bx dev deploy` 和 `docker` 命令的 Dockerfile|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dockerfile-tools| 用于 `bx dev build` 和 `bx dev test` 的 Dockerfile|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;docker-compose.yml| Docker Compose 的应用程序服务配置|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;webpack.config.js| 用于与构建相关的信息的 Webpack 配置|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LICENSE|  |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;README.md| 项目描述|
|<b>`./public/`</b>|  |  |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;swagger.yml| 用于描述 REST API 的 Swagger 规范|
|<b>`./public/index.html`</b>|  |  |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;index.html| Web 应用程序的框架标记|
|<b>`./public/server/`</b>| |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;server.js| 服务器实现文件|
|<b>`./test/`</b>| |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;test-server.js| Express 服务器的集成测试|
|<b>`./.bluemix/`</b>| |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;container_build.sh| |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;deploy.json| |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;kube_deploy.sh| |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pipeline.yml| IBM Cloud 管道定义|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;toolchain.yml| IBM Cloud 工具链定义|
|<b>`./chart/<projectname>/`</b> | |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Chart.yaml| Helm 图表|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;values.yaml| Helm 图表值|
|<b>`./chart/<projectname>/templates/`</b>| |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;deployment.yaml| 部署模板|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;service.yaml| 服务模板|
{: caption="表 1. 生成的 Node.js 项目的内容" caption-side="top"}
