Master e worker nodes 

- Master
  ETCD Cluster -> Store information about the cluster
  kube-scheduler -> Responsabel for scheduler the application or container on nodes
  kube Controller Manager -> node controller, replication controller ...
  kube-apiserver -> Orquestrate all operations in the cluster 

- Worker
  kubelet - lisening per instructions from the kube api server
  kube-proxy - helping enable communication between the cluster