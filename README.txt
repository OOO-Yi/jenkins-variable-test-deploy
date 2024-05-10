
# Go Starter Application

Bluemix provides a Go starter application as a template so that you can add your code and push the changes back to the Bluemix environment.


## Files

The Go starter application has files as below:

*   instructions.md

	This file describes the Next Steps for getting started with this template.

*   app.go

	This file contains a simple web server written in the Go programming language.

*   static/

	This directory contains the static files that are part of this application.

*   Procfile

	This file is required by the Go buildpack. It specifies the command to start the app.

*   Godeps/

        This directory contains the app's dependencies and is created by the Godep tool.



#K8S下Jenkins基于dockerhbu构建进行并部署，需要修改镜像路径
k8s-dev.yaml、k8s-qa.yaml、k8s-prod.yaml
#K8S下Jenkins基于harbro构建进行并部署，需要修改镜像路径
k8s-dev-harbor.yaml、k8s-qa-harbor.yaml、k8s-prod-harbor.yaml
