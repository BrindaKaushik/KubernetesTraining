# KubernetesTraining
Kubernetes orchestrates container communications

kubectl describe pod <podname>

kubectl create -f <podfile>

kubectl get nodes

kubectl get pod
  
kubec get pod <podname>

kubectl get service

kubectl exec <podname> -- l     see all files in pod

kubectl exec --stdin --tty <podname> -- /bin/bash

kubectl edit rs <podname>


  '-'   denotes array in manifest file

Create Pod manifest
Expose pod as service
Create replica set, replicas 5
Explore container logs, exec into container, edit
