# Deploy Jenkins with kubernetes
Objets Kubernetes used on this project 
    Namespace: jenkins-ns
    ServiceAccount : jenkins-sa
    Deployement : jenkins-deploy, with matchLabels : jenkins-server 
    Service: jenkins-srv
    PersistentVolume Claims : jenkins-pvc
    PersistentVolume  : jenkins-pv
    ClusterRoleBinding: jenkins-crb
    kind: ClusterRole: jenkins-cr

Refer https://github.com/devopskingndom/jenkins for step by step process to use these manifests.

