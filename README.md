Note : This prroject still in In-progress
# helloworld-gitops
This repo will provide the details of deploying helloworld to K8s cluster in gitops approach

Steps:


Steps to build and push docker image to registry

To Docker hub
---------------
1) docker build -t helloworld:1.0 .
2) Login in to docker hub registry - docker login registry-1.docker.io/v1 (enter your username and password)
3) Tag the local image with the remote. Repo - docker tag <fa43b0158118> atanum1/helloworrld:1.0
4) Then push to registry - docker push  atanum1/helloworrld:1.0 
