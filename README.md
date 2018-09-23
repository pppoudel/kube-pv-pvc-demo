# kube-pv-pvc-demo
Sample files for creating PV, PVC, and using them with RabbitMQ deployment
<br/>

Sample files:
 * [shared-services-ns.yml for creating namespace](yaml/shared-services-ns.yml)
 * [svcAccnt.yml for creating service account](yaml/svcAccnt.yml)
 * [rabbitmq-nfs-pv.yml for creating PersistenceVolume](yaml/rabbitmq-nfs-pv.yml)
 * [rabbitmq-nfs-pvc.yml for creating PersistenceVolumeClaim](yaml/rabbitmq-nfs-pvc.yml)
 * [rabbitmq-nfs-pv-poc-depl.yml for creating rabbitmq service and deployment objects](yaml/rabbitmq-nfs-pv-poc-depl.yml)
<br/>


I have written a blog post explaining the detail steps and troubleshooting ideas. See:
[How to Create, Troubleshoot and Use NFS type Persistent Storage Volume in Kubernetes](https://purnapoudel.blogspot.com/2018/08/how-to-create-troubleshoot-use-nfs-type-pestencevolume-in-kubernetes.html)
