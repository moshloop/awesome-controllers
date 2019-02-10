### Cluster / Scheduling

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [awslabs/aws-eks-cluster-controller](https://github.com/awslabs/aws-eks-cluster-controller)  ||
| [gardener/machine-controller-manager](https://github.com/gardener/machine-controller-manager)  ||
| [pharmer/cloud-controller-manager](https://github.com/pharmer/cloud-controller-manager)  ||
| [samsung-cnct/cluster-controller](https://github.com/samsung-cnct/cluster-controller)  ||
| [hex108/cron-hpa-controller](https://github.com/hex108/cron-hpa-controller)  ||
| [estafette/estafette-gke-preemptible-killer](https://github.com/estafette/estafette-gke-preemptible-killer) | ensures deletion of preemptible nodes in a GKE cluster is spread out to avoid the risk of all getting deleted at the same time after 24 hours |
| [lwolf/kube-cleanup-operator](https://github.com/lwolf/kube-cleanup-operator) | automatically delete completed Jobs and their Pods           |
| [pusher/k8s-spot-rescheduler](https://github.com/pusher/k8s-spot-rescheduler) | Tries to move K8s Pods from on-demand to spot instances      |
| [hjacobs/kube-aws-autoscaler](https://github.com/hjacobs/kube-aws-autoscaler) | Simple, elastic Kubernetes cluster autoscaler for AWS Auto Scaling Groups |
| [atlassian/escalator](https://github.com/atlassian/escalator) | Escalator is a batch or job optimized horizontal autoscaler for Kubernetes |
| [hjacobs / kube-job-cleaner](https://github.com/hjacobs/kube-job-cleaner) | Delete complete/failed Kubernetes jobs after one hour        |
| [planetlabs / draino](https://github.com/planetlabs/draino)  | Automatically cordon and drain Kubernetes nodes based on node conditions |
| [weaveworks/kured](https://github.com/weaveworks/kured) | Kubernetes Reboot Daemon                                     |
|                                                              |                                                              |
|                                                              |                                                              |



### Recovery

| Controller                                                   | Descriptiopn                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [lachie83/pod-requeue](https://github.com/lachie83/pod-requeue) | *Kubernetes* *controller* to delete and recreate failed pods stuck in InsufficientFreeCPU or OutOfcpu states |
| [gardener-attic/auto-node-repair](https://github.com/gardener-attic/auto-node-repair)  ||



### Networking



| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [fiunchinho/dmz-*controller*](https://github.com/fiunchinho/dmz-controller) | This is a *kubernetes* *controller* that watches Ingress objects that contain a specific annotation and adds whitelisted … |
| [sapcc/kube-parrot](https://github.com/sapcc/kube-parrot)    | A *Kubernetes* *Controller* that Dynamically Announces Routes with BGP |
| [pickledrick/vpc-peering-operator](https://github.com/pickledrick/vpc-peering-operator) | A *Kubernetes* Operator to manage the lifecycle of AWS VPC Peering Connections |
| [wikiwi/kube-dns-sync](https://github.com/wikiwi/kube-dns-sync) | *Controller* syncing *Kubernetes* Node IPs to a DNS service  |
| [zekizeki/ingressdns](https://github.com/zekizeki/ingressdns)  ||
| [estafette/estafette-cloudflare-dns](https://github.com/estafette/estafette-cloudflare-dns)  ||
| [aledbf/kube-keepalived-vip](https://github.com/aledbf/kube-keepalived-vip) | Kubernetes Virtual IP address/es using keepalived            |
| [tiglabs/jupiter](https://github.com/tiglabs/jupiter) | high-performance 4-layer network load balance service based on DPDK. |
|                                                              |                                                              |



### Cloud

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [estafette/estafette-gke-preemptible-killer](https://github.com/estafette/estafette-gke-preemptible-killer) | *Kubernetes* *controller* that ensures deletion of preemptible nodes in a GKE cluster is spread out to avoid the risk of |
| [atomix/chaos-controller](https://github.com/atomix/chaos-controller)  ||
| [uswitch/sqs-autoscaler-controller](https://github.com/uswitch/sqs-autoscaler-controller)  ||
| [target/pod-reaper](https://github.com/target/pod-reaper)  ||
| [lotusload/lotus](https://github.com/lotusload/lotus)  ||
| [travisghansen/kubernetes-pfsense-controller](https://github.com/travisghansen/kubernetes-pfsense-controller)  ||
| [szuecs/kube-static-egress-controller](https://github.com/szuecs/kube-static-egress-controller)  ||
| [previousnext/k8s-aws-efs](https://github.com/previousnext/k8s-aws-efs)  ||
| [Mirantis/k8s-externalipcontroller](https://github.com/Mirantis/k8s-externalipcontroller)  ||
| [vmware/k8s-endpoints-sync-controller](https://github.com/vmware/k8s-endpoints-sync-controller)  ||
| [admiraltyio/multicluster-scheduler](https://github.com/admiraltyio/multicluster-scheduler)  ||



### Namespaces

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [kubernetes-replicator](https://github.com/mittwald/kubernetes-replicator) | controller for synchronizing secrets & config maps across namespaces |
| [registry-creds](https://github.com/upmc-enterprises/registry-creds) | Allow for AWS ECR and Google Registry credentials to be refreshed inside your Kubernetes cluster via ImagePullSecrets |
| [namespace-configuration-controller](https://github.com/raffaelespazzoli/namespace-configuration-controller) | keeps a namespace's configuration aligned with one of more policies specified as a CRD |
| [cruise-automation/rbacsync](https://github.com/cruise-automation/rbacsync) |                                                              |
| [tumblr / k8s-config-projector](https://github.com/tumblr/k8s-config-projector) | Create Kubernetes ConfigMaps from configuration files        |
|                                                              |                                                              |
|                                                              |                                                              |




### Admission

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [stefanprodan/kubesec-webhook](https://github.com/stefanprodan/kubesec-webhook) | Kubesec.io admission *controller* for #*Kubernetes*Deployments, DaemonSets and StatefulSets |
| [UKHomeOffice/policy-admission](https://github.com/UKHomeOffice/policy-admission)  ||
| [lachie83/internallb-webhook-admission-controller](https://github.com/lachie83/internallb-webhook-admission-controller)  ||
| [jasonrichardsmith/sentry](https://github.com/jasonrichardsmith/sentry)  ||
| [IBM/portieris](https://github.com/IBM/portieris)  ||
| [replicatedhq/gatekeeper](https://github.com/replicatedhq/gatekeeper)  ||
| [yahoo/k8s-namespace-guard](https://github.com/yahoo/k8s-namespace-guard)  ||
| [open-policy-agent/kubernetes-policy-controller](https://github.com/open-policy-agent/kubernetes-policy-controller)  ||
| [mikkeloscar/pdb-*controller*](https://github.com/mikkeloscar/pdb-controller) | *Controller* for adding default Pod Disruption Budgets to *Kubernetes* Deployments and StatefulSets |
| [target/portauthority](https://github.com/target/portauthority) | API that leverages Clair to scan Docker Registries and Kubernetes Clusters for vulnerabilities |



### Ingress

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [hxquangnhat/*kubernetes*-auto-ingress](https://github.com/hxquangnhat/kubernetes-auto-ingress) | Dynamically create an ingress for an associated service for *Kubernetes*, works with nginx ingress *controller* |
| [torchbox/k8s-ts-ingress](https://github.com/torchbox/k8s-ts-ingress) | *Kubernetes* Ingress *controller* as a Traffic Server plugin |
| [bretagne-peiqi/lvs-nginx-controller](https://github.com/bretagne-peiqi/lvs-nginx-controller)  ||
| [citrix/citrix-k8s-ingress-controller](https://github.com/citrix/citrix-k8s-ingress-controller)  ||
| [oracle/federated-ingress-controller](https://github.com/oracle/federated-ingress-controller)  ||
| [wehco/caddy-ingress-controller](https://github.com/wehco/caddy-ingress-controller)  ||
| [stakater/IngressMonitorController](https://github.com/stakater/IngressMonitorController)  ||
| [hootsuite/sens8](https://github.com/hootsuite/sens8)  ||
| [YakLabs/kube-openresty-ingress](https://github.com/YakLabs/kube-openresty-ingress)  ||
| [philips/backplane-kubernetes-ingress](https://github.com/philips/backplane-kubernetes-ingress)  ||
| [mercari/certificate-expiry-monitor-controller](https://github.com/mercari/certificate-expiry-monitor-controller)  ||
| [nilebox/kanarini](https://github.com/nilebox/kanarini)  ||



### Reloaders

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [xing/*kubernetes*-deployment-restart-*controller*](https://github.com/xing/kubernetes-deployment-restart-controller) | *controller* that restarts Deployments when referenced ConfigMaps or Secrets change. |
| [mfojtik/k8s-trigger-controller](https://github.com/mfojtik/k8s-trigger-controller)  ||
| [stakater/Reloader](https://github.com/stakater/Reloader)  ||
| [stakater/Chowkidar](https://github.com/stakater/Chowkidar)  | *controller* that watches/observes events & then takes configured actions |

### Development Tools

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
