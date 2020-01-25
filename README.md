This Guide will you to setup HELM on Kubernetes Cluster.

Follow below steps to do the same

1. Install wget on your master
2. wget https://get.helm.sh/helm-v3.0.2-linux-amd64.tar.gz
3. untar -xvf helm-v3.0.2-linux-amd64.tar.gz
4. cp linux-amd64/helm /usr/bin/helm 
5. helm version 
6. helm ls # to check the current release
7. helm install release-name helm-package
   example:
   helm install kubernetes-dashboard mychart-0.1.0.tgz
