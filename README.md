### Cluster / Scheduling

| Controller                                             | Description |
| ------------------------------------------------------ | ----------- |
| https://github.com/awslabs/aws-eks-cluster-controller  |             |
| https://github.com/gardener/machine-controller-manager |             |
| https://github.com/pharmer/cloud-controller-manager    |             |
| https://github.com/samsung-cnct/cluster-controller     |             |
| https://github.com/hex108/cron-hpa-controller          |             |



### Recovery

| Controller                                                   | Descriptiopn                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [lachie83/pod-requeue](https://github.com/lachie83/pod-requeue) | *Kubernetes* *controller* to delete and recreate failed pods stuck in InsufficientFreeCPU or OutOfcpu states |
| https://github.com/gardener-attic/auto-node-repair           |                                                              |



### Networking



| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [fiunchinho/dmz-*controller*](https://github.com/fiunchinho/dmz-controller) | This is a *kubernetes* *controller* that watches Ingress objects that contain a specific annotation and adds whitelisted … |
| [sapcc/kube-parrot](https://github.com/sapcc/kube-parrot)    | A *Kubernetes* *Controller* that Dynamically Announces Routes with BGP |
| [pickledrick/vpc-peering-operator](https://github.com/pickledrick/vpc-peering-operator) | A *Kubernetes* Operator to manage the lifecycle of AWS VPC Peering Connections |
| [wikiwi/kube-dns-sync](https://github.com/wikiwi/kube-dns-sync) | *Controller* syncing *Kubernetes* Node IPs to a DNS service  |
| https://github.com/zekizeki/ingressdns                       | ingress controllers and then adds an entry to a consul server so that the ingress point has a DNS entry. |
| https://github.com/estafette/estafette-cloudflare-dns        |                                                              |



### Cloud

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [estafette/estafette-gke-preemptible-killer](https://github.com/estafette/estafette-gke-preemptible-killer) | *Kubernetes* *controller* that ensures deletion of preemptible nodes in a GKE cluster is spread out to avoid the risk of |
| https://github.com/atomix/chaos-controller                   |                                                              |
| https://github.com/uswitch/sqs-autoscaler-controller         | controller for scaling Deployments based on AWS SQS queue length |
| https://github.com/target/pod-reaper                         | Rule based pod killing kubernetes controller                 |
| https://github.com/lotusload/lotus                           |                                                              |
| https://github.com/travisghansen/kubernetes-pfsense-controller |                                                              |
| https://github.com/szuecs/kube-static-egress-controller      |                                                              |
| https://github.com/previousnext/k8s-aws-efs                  |                                                              |
| https://github.com/Mirantis/k8s-externalipcontroller         |                                                              |
| https://github.com/vmware/k8s-endpoints-sync-controller      | Cross-Cluster *Kubernetes* Endpoints Sync *Controller*       |
| https://github.com/admiraltyio/multicluster-scheduler        |                                                              |



### Namespaces

| Controller                                        | Description                                                  |
| ------------------------------------------------- | ------------------------------------------------------------ |
| [kubernetes-replicator](https://github.com/mittwald/kubernetes-replicator) | controller for synchronizing secrets & config maps across namespaces |
| [registry-creds](https://github.com/upmc-enterprises/registry-creds) | Allow for AWS ECR and Google Registry credentials to be refreshed inside your Kubernetes cluster via ImagePullSecrets |
| [namespace-configuration-controller](https://github.com/raffaelespazzoli/namespace-configuration-controller) | keeps a namespace's configuration aligned with one of more policies specified as a CRD |




### Admission

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [stefanprodan/kubesec-webhook](https://github.com/stefanprodan/kubesec-webhook) | Kubesec.io admission *controller* for #*Kubernetes*Deployments, DaemonSets and StatefulSets |
| https://github.com/UKHomeOffice/policy-admission             |                                                              |
| https://github.com/lachie83/internallb-webhook-admission-controller | This Kubernetes Admission controller only admits the creation of v1/service resources containing the correct cloud provider annotations to create Internal LoadBalancers. |
| https://github.com/jasonrichardsmith/sentry                  |                                                              |
| https://github.com/IBM/portieris                             | for verifying image trust with Notary.                       |
| https://github.com/replicatedhq/gatekeeper                   |                                                              |
| https://github.com/yahoo/k8s-namespace-guard                 |                                                              |
| https://github.com/open-policy-agent/kubernetes-policy-controller |                                                              |
| [mikkeloscar/pdb-*controller*](https://github.com/mikkeloscar/pdb-controller) | *Controller* for adding default Pod Disruption Budgets to *Kubernetes* Deployments and StatefulSets |



### Ingress

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [hxquangnhat/*kubernetes*-auto-ingress](https://github.com/hxquangnhat/kubernetes-auto-ingress) | Dynamically create an ingress for an associated service for *Kubernetes*, works with nginx ingress *controller* |
| [torchbox/k8s-ts-ingress](https://github.com/torchbox/k8s-ts-ingress) | *Kubernetes* Ingress *controller* as a Traffic Server plugin |
| https://github.com/bretagne-peiqi/lvs-nginx-controller       | IPVS Loadbalancer with keepalived                            |
| https://github.com/citrix/citrix-k8s-ingress-controller      |                                                              |
| https://github.com/oracle/federated-ingress-controller       |                                                              |
| https://github.com/wehco/caddy-ingress-controller            |                                                              |
| https://github.com/stakater/IngressMonitorController         |                                                              |
| https://github.com/hootsuite/sens8                           |                                                              |
| https://github.com/YakLabs/kube-openresty-ingress            |                                                              |
| https://github.com/philips/backplane-kubernetes-ingress      |                                                              |
| https://github.com/mercari/certificate-expiry-monitor-controller |                                                              |
| https://github.com/nilebox/kanarini                          | Canary Deployment *Controller* for *Kubernetes*              |



### Reloaders

| Controller                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [xing/*kubernetes*-deployment-restart-*controller*](https://github.com/xing/kubernetes-deployment-restart-controller) | *controller* that restarts Deployments when referenced ConfigMaps or Secrets change. |
| https://github.com/mfojtik/k8s-trigger-controller            |                                                              |
| https://github.com/stakater/Reloader                         |                                                              |
| [stakater/Chowkidar](https://github.com/stakater/Chowkidar)  | *controller* that watches/observes events & then takes configured actions |

### Development Tools

| Tool                                                  | Description                                          |
| ----------------------------------------------------- | ---------------------------------------------------- |
| https://github.com/pusher/git-store                   | Go git abstraction for use in Kubernetes Controllers |
| https://github.com/ianlewis/controllerutil            |                                                      |
| https://github.com/gojektech/kubehandler              |                                                      |
| https://github.com/Microsoft/frameworkcontroller      |                                                      |
| https://github.com/GoogleCloudPlatform/metacontroller |                                                      |
| https://github.com/atlassian/ctrl                     |                                                      |
