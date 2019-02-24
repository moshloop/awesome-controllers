

## Operators vs Controllers

An operator is a specifc type of controller that provides a higher level of abstraction for deploying complex resources using custom resource definitions (CRD's). While a controller normally extends or configures existing resources, an operator deploys the resources themeselves.

See [awesome-operators](https://github.com/operator-framework/awesome-operators).

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
| [stakater/Jamadar](https://github.com/stakater/Jamadar)      | cleans up resources after a predefined timeout               |



### Networking

*Controllers that expose networking related functions likeload balancers / DNS outside the scope of CNI.*.
*See [cni#3rd-party-plugins](https://github.com/containernetworking/cni#3rd-party-plugins) for a list of CNI plugins, some of which do provide similar functionality*

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [external-dns](https://github.com/kubernetes-incubator/external-dns) | configure external DNS (Route53, CloudDNS, etc) for ingresses and services |
| [google/metalb](https://github.com/google/metallb)           | load balancer implemented using ARP or BGP                   |
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

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [admiraltyio/multicluster-scheduler](https://github.com/admiraltyio/multicluster-scheduler) |                                                              |
| [oracle/federated-ingress-controller](https://github.com/oracle/federated-ingress-controller) |                                                              |
| [github/kube-service-exporter](https://github.com/github/kube-service-exporter) | Export load balancer services to consul                      |
| [hashicorp/consul-k8s](https://github.com/hashicorp/consul-k8s) | Sync Consul services into first-class Kubernetes services and vice versa |
| [vmware/k8s-endpoints-sync-controller](https://github.com/vmware/k8s-endpoints-sync-controller) |                                                              |
| [awslabs/aws-eks-cluster-controller](https://github.com/awslabs/aws-eks-cluster-controller) |                                                              |
| [gardener/machine-controller-manager](https://github.com/gardener/machine-controller-manager) |                                                              |
| [pharmer/cloud-controller-manager](https://github.com/pharmer/cloud-controller-manager) |                                                              |
| [samsung-cnct/cluster-controller](https://github.com/samsung-cnct/cluster-controller) |                                                              |



### Namespaces

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [mittwald/kubernetes-replicator](https://github.com/mittwald/kubernetes-replicator) | controller for synchronizing secrets & config maps across namespaces |
| [upmc-enterprises/registry-creds](https://github.com/upmc-enterprises/registry-creds) | Allow for AWS ECR and Google Registry credentials to be refreshed inside your Kubernetes cluster via ImagePullSecrets |
| [raffaelespazzoli/namespace-configuration-controller](https://github.com/raffaelespazzoli/namespace-configuration-controller) | keeps a namespace's configuration aligned with one of more policies specified as a CRD |
| [cruise-automation/rbacsync](https://github.com/cruise-automation/rbacsync) |                                                              |
| [tumblr/k8s-config-projector](https://github.com/tumblr/k8s-config-projector) | Create Kubernetes ConfigMaps from configuration files        |
| [stakater/ProxyInjector](https://github.com/stakater/ProxyInjector) | inject an authentication proxy container to relevant pods    |




### Admission

| Controller                                                   | Description                                              |
| ------------------------------------------------------------ | -------------------------------------------------------- |
| [open-policy-agent/kubernetes-policy-controller](https://github.com/open-policy-agent/kubernetes-policy-controller) | Open Policy Agent Admission controller                   |
| [replicatedhq/gatekeeper](https://github.com/replicatedhq/gatekeeper) | Alternative dynamic admission contollers via OPA         |
| [yahoo/k8s-ingress-claim](https://github.com/yahoo/k8s-ingress-claim) | Safeguards against duplicate claiming of hosts / domains |
| [jainishshah17/tugger](https://github.com/jainishshah17/tugger) | Enforce pulling docker images from a private registry    |
| [stefanprodan/kubesec-webhook](https://github.com/stefanprodan/kubesec-webhook) | Enforces minimum kubesec.io scores                       |
| [UKHomeOffice/policy-admission](https://github.com/UKHomeOffice/policy-admission) | Policy enforcement via standard rules and JavaScript     |
| [lachie83/internallb-webhook-admission-controller](https://github.com/lachie83/internallb-webhook-admission-controller) | Enforces only internal cloud load balancers              |
| [jasonrichardsmith/sentry](https://github.com/jasonrichardsmith/sentry) | Policy enforcement for limits, images, health            |
| [IBM/portieris](https://github.com/IBM/portieris)            | Image trust enforcement with Notary / Content Trust      |
| [yahoo/k8s-namespace-guard](https://github.com/yahoo/k8s-namespace-guard) | Prevents accidental deletion of namespaces               |
| [mikkeloscar/pdb-controller](https://github.com/mikkeloscar/pdb-controller) | Adds default Pod Disruption Budgets                      |
| [target/portauthority](https://github.com/target/portauthority) | Leverages Clair to scan k8s clusters for vulnerabilities |



### Ingress

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [hxquangnhat/kubernetes-auto-ingress](https://github.com/hxquangnhat/kubernetes-auto-ingress) | Dynamically create an ingress for an associated service      |
| [torchbox/k8s-ts-ingress](https://github.com/torchbox/k8s-ts-ingress) | Traffic Server ingress controller                            |
| [stakater/Xposer](https://github.com/stakater/Xposer)        | watch for services and dynamically create an Ingress with a TLS certificate |
| [stakater/IngressMonitorController](https://github.com/stakater/IngressMonitorController) | monitor ingresses and create alerts on Pingdom, UptimeRobot and StatusCake |
| [uswitch/yggdrasil](https://github.com/uswitch/yggdrasil)    | Envoy control plane for multi-cluster ingress                |
| [bretagne-peiqi/lvs-nginx-controller](https://github.com/bretagne-peiqi/lvs-nginx-controller) |                                                              |
| [citrix/citrix-k8s-ingress-controller](https://github.com/citrix/citrix-k8s-ingress-controller) |                                                              |
|                                                              |                                                              |
| [wehco/caddy-ingress-controller](https://github.com/wehco/caddy-ingress-controller) |                                                              |
| [hootsuite/sens8](https://github.com/hootsuite/sens8)        |                                                              |
| [YakLabs/kube-openresty-ingress](https://github.com/YakLabs/kube-openresty-ingress) |                                                              |
| [philips/backplane-kubernetes-ingress](https://github.com/philips/backplane-kubernetes-ingress) |                                                              |
| [mercari/certificate-expiry-monitor-controller](https://github.com/mercari/certificate-expiry-monitor-controller) |                                                              |
| [nilebox/kanarini](https://github.com/nilebox/kanarini)      | Canary deployment controller                                 |
| [webrelay/ingress](https://github.com/webrelay/ingress)      | Map tunnels to ingress for [webhookrelay.com](webhookrelay.com) |



### Reloaders

*Controllers that take action such as restarting a pod or deployment when watched resource such as configmaps and secrets change.*

| Controller                                                   | Description |
| ------------------------------------------------------------ | ----------- |
| [xing/kubernetes-deployment-restart-controller](https://github.com/xing/kubernetes-deployment-restart-controller) |             |
| [mfojtik/k8s-trigger-controller](https://github.com/mfojtik/k8s-trigger-controller) |             |
| [pusher/wave](https://github.com/pusher/wave)                |             |
| [stakater/Reloader](https://github.com/stakater/Reloader)    |             |
| [stakater/Chowkidar](https://github.com/stakater/Chowkidar)  |             |

### GitOps

| Controller                                      | Description |
| ----------------------------------------------- | ----------- |
| [pusher/faros](https://github.com/pusher/faros) |             |



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
