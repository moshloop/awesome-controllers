### Autoscaling / Scheduling

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [uswitch/sqs-autoscaler-controller](https://github.com/uswitch/sqs-autoscaler-controller) |                                                              |
| [hjacobs/kube-aws-autoscaler](https://github.com/hjacobs/kube-aws-autoscaler) | cluster autoscaler for AWS Auto Scaling Groups               |
| [pusher/k8s-spot-rescheduler](https://github.com/pusher/k8s-spot-rescheduler) | Tries to move pods from on-demand to spot instances          |
| [hex108/cron-hpa-controller](https://github.com/hex108/cron-hpa-controller) |                                                              |
| [estafette/estafette-gke-preemptible-killer](https://github.com/estafette/estafette-gke-preemptible-killer) | ensures deletion of preemptible nodes in a GKE cluster is spread out to avoid the risk of all getting deleted at the same time after 24 hour |
| [atlassian/escalator](https://github.com/atlassian/escalator) | batch or job optimized horizontal autoscaler                 |



### Cleanup

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [lwolf/kube-cleanup-operator](https://github.com/lwolf/kube-cleanup-operator) | automatically delete completed jobs and their pods           |
| [hjacobs / kube-job-cleaner](https://github.com/hjacobs/kube-job-cleaner) | delete complete/failed jobs after one hour                   |
| [planetlabs / draino](https://github.com/planetlabs/draino)  | cordon and drain nodes based on node conditions              |
| [weaveworks/kured](https://github.com/weaveworks/kured)      | node reboot daemon                                           |
| [target/pod-reaper](https://github.com/target/pod-reaper)    | delete pods based on matching conditions                     |
| [lachie83/pod-requeue](https://github.com/lachie83/pod-requeue) | recreate failed pods stuck in InsufficientFreeCPU or OutOfcpu states |
| [gardener-attic/auto-node-repair](https://github.com/gardener-attic/auto-node-repair) |                                                              |



### Networking

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [sapcc/kube-parrot](https://github.com/sapcc/kube-parrot)    | dynamically announces routes with BGP                        |
| [pickledrick/vpc-peering-operator](https://github.com/pickledrick/vpc-peering-operator) | manage the lifecycle of AWS VPC Peering Connections          |
| [wikiwi/kube-dns-sync](https://github.com/wikiwi/kube-dns-sync) | syncs Node IPs to a DNS service                              |
| [zekizeki/ingressdns](https://github.com/zekizeki/ingressdns) |                                                              |
| [estafette/estafette-cloudflare-dns](https://github.com/estafette/estafette-cloudflare-dns) |                                                              |
| [aledbf/kube-keepalived-vip](https://github.com/aledbf/kube-keepalived-vip) | VIPs using keepalived                                        |
| [tiglabs/jupiter](https://github.com/tiglabs/jupiter)        | high-performance L4 network load balance service based on DPDK. |
| [szuecs/kube-static-egress-controller](https://github.com/szuecs/kube-static-egress-controller) |                                                              |
| [travisghansen/kubernetes-pfsense-controller](https://github.com/travisghansen/kubernetes-pfsense-controller) |                                                              |
| [Mirantis/k8s-externalipcontroller](https://github.com/Mirantis/k8s-externalipcontroller) |                                                              |



### Chaos / Loading Testing

| Controller                                                   | Description                              |
| ------------------------------------------------------------ | ---------------------------------------- |
| [atomix/chaos-controller](https://github.com/atomix/chaos-controller) |                                          |
| [target/pod-reaper](https://github.com/target/pod-reaper)    | delete pods based on matching conditions |
| [lotusload/lotus](https://github.com/lotusload/lotus)        |                                          |



### Multi-Cluster

| Controller                                                   | Description |
| ------------------------------------------------------------ | ----------- |
| [admiraltyio/multicluster-scheduler](https://github.com/admiraltyio/multicluster-scheduler) |             |
| [oracle/federated-ingress-controller](https://github.com/oracle/federated-ingress-controller) |             |
| [vmware/k8s-endpoints-sync-controller](https://github.com/vmware/k8s-endpoints-sync-controller) |             |
| [awslabs/aws-eks-cluster-controller](https://github.com/awslabs/aws-eks-cluster-controller) |             |
| [gardener/machine-controller-manager](https://github.com/gardener/machine-controller-manager) |             |
| [pharmer/cloud-controller-manager](https://github.com/pharmer/cloud-controller-manager) |             |
| [samsung-cnct/cluster-controller](https://github.com/samsung-cnct/cluster-controller) |             |



### Namespaces

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [kubernetes-replicator](https://github.com/mittwald/kubernetes-replicator) | controller for synchronizing secrets & config maps across namespaces |
| [registry-creds](https://github.com/upmc-enterprises/registry-creds) | Allow for AWS ECR and Google Registry credentials to be refreshed inside your Kubernetes cluster via ImagePullSecrets |
| [namespace-configuration-controller](https://github.com/raffaelespazzoli/namespace-configuration-controller) | keeps a namespace's configuration aligned with one of more policies specified as a CRD |
| [cruise-automation/rbacsync](https://github.com/cruise-automation/rbacsync) |                                                              |
| [tumblr / k8s-config-projector](https://github.com/tumblr/k8s-config-projector) | Create Kubernetes ConfigMaps from configuration files        |




### Admission

| Controller                                                   | Description                                              |
| ------------------------------------------------------------ | -------------------------------------------------------- |
| [open-policy-agent/kubernetes-policy-controller](https://github.com/open-policy-agent/kubernetes-policy-controller) |                                                          |
| [replicatedhq/gatekeeper](https://github.com/replicatedhq/gatekeeper) |                                                          |
| [stefanprodan/kubesec-webhook](https://github.com/stefanprodan/kubesec-webhook) |                                                          |
| [UKHomeOffice/policy-admission](https://github.com/UKHomeOffice/policy-admission) |                                                          |
| [lachie83/internallb-webhook-admission-controller](https://github.com/lachie83/internallb-webhook-admission-controller) |                                                          |
| [jasonrichardsmith/sentry](https://github.com/jasonrichardsmith/sentry) |                                                          |
| [IBM/portieris](https://github.com/IBM/portieris)            |                                                          |
| [yahoo/k8s-namespace-guard](https://github.com/yahoo/k8s-namespace-guard) |                                                          |
| [mikkeloscar/pdb-*controller*](https://github.com/mikkeloscar/pdb-controller) | adds default Pod Disruption Budgets                      |
| [target/portauthority](https://github.com/target/portauthority) | leverages Clair to scan k8s clusters for vulnerabilities |



### Ingress

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [hxquangnhat/*kubernetes*-auto-ingress](https://github.com/hxquangnhat/kubernetes-auto-ingress) | Dynamically create an ingress for an associated service for *Kubernetes*, works with nginx ingress *controller* |
| [torchbox/k8s-ts-ingress](https://github.com/torchbox/k8s-ts-ingress) | *Kubernetes* Ingress *controller* as a Traffic Server plugin |
| [bretagne-peiqi/lvs-nginx-controller](https://github.com/bretagne-peiqi/lvs-nginx-controller) |                                                              |
| [citrix/citrix-k8s-ingress-controller](https://github.com/citrix/citrix-k8s-ingress-controller) |                                                              |
|                                                              |                                                              |
| [wehco/caddy-ingress-controller](https://github.com/wehco/caddy-ingress-controller) |                                                              |
| [stakater/IngressMonitorController](https://github.com/stakater/IngressMonitorController) |                                                              |
| [hootsuite/sens8](https://github.com/hootsuite/sens8)        |                                                              |
| [YakLabs/kube-openresty-ingress](https://github.com/YakLabs/kube-openresty-ingress) |                                                              |
| [philips/backplane-kubernetes-ingress](https://github.com/philips/backplane-kubernetes-ingress) |                                                              |
| [mercari/certificate-expiry-monitor-controller](https://github.com/mercari/certificate-expiry-monitor-controller) |                                                              |
| [nilebox/kanarini](https://github.com/nilebox/kanarini)      |                                                              |



### Reloaders

*Controllers that take action such as restarting a pod or deployment when watched resource such as configmaps and secrets change.*

| Controller                                                   | Description |
| ------------------------------------------------------------ | ----------- |
| [xing/*kubernetes*-deployment-restart-*controller*](https://github.com/xing/kubernetes-deployment-restart-controller) |             |
| [mfojtik/k8s-trigger-controller](https://github.com/mfojtik/k8s-trigger-controller) |             |
| [stakater/Reloader](https://github.com/stakater/Reloader)    |             |
| [stakater/Chowkidar](https://github.com/stakater/Chowkidar)  |             |

### Development Tools

*Libraries used for building new controllers*

| Tool                                                         | Description                                          |
| ------------------------------------------------------------ | ---------------------------------------------------- |
| [pusher/git-store](https://github.com/pusher/git-store)  ||
| [ianlewis/controllerutil](https://github.com/ianlewis/controllerutil)  ||
| [gojektech/kubehandler](https://github.com/gojektech/kubehandler)  ||
| [Microsoft/frameworkcontroller](https://github.com/Microsoft/frameworkcontroller)  ||
| [GoogleCloudPlatform/metacontroller](https://github.com/GoogleCloudPlatform/metacontroller)  ||
| [atlassian/ctrl](https://github.com/atlassian/ctrl)  ||
| [kudobuilder/kudo](https://github.com/kudobuilder/kudo) | Kubernetes Universal Declarative Operator (KUDO)     |
| [slok/kubewebhook](https://github.com/slok/kubewebhook) |                                                      |
