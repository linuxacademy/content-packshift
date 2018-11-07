# OpenShift v3.9 clusterroles


````
[centos@master0 ~]$ oc get clusterroles
NAME
admin
asb-access
asb-auth
basic-user
cluster-admin
cluster-debugger
cluster-reader
cluster-status
edit
hawkular-metrics-admin
management-infra-admin
namespace-viewer
registry-admin
registry-editor
registry-viewer
sar-creator
self-access-reviewer
self-provisioner
service-catalog-controller
servicecatalog-serviceclass-viewer
storage-admin
sudoer
system:aggregate-to-admin
system:aggregate-to-edit
system:aggregate-to-view
system:auth-delegator
system:aws-cloud-provider
system:basic-user
system:build-controller
system:build-strategy-custom
system:build-strategy-docker
system:build-strategy-jenkinspipeline
system:build-strategy-source
system:certificate-signing-controller
system:certificates.k8s.io:certificatesigningrequests:nodeclient
system:certificates.k8s.io:certificatesigningrequests:selfnodeclient
system:controller:attachdetach-controller
system:controller:certificate-controller
system:controller:clusterrole-aggregation-controller
system:controller:cronjob-controller
system:controller:daemon-set-controller
system:controller:deployment-controller
system:controller:disruption-controller
system:controller:endpoint-controller
system:controller:generic-garbage-collector
system:controller:horizontal-pod-autoscaler
system:controller:job-controller
system:controller:namespace-controller
system:controller:node-controller
system:controller:persistent-volume-binder
system:controller:pod-garbage-collector
system:controller:replicaset-controller
system:controller:replication-controller
system:controller:resourcequota-controller
system:controller:route-controller
system:controller:service-account-controller
system:controller:service-controller
system:controller:statefulset-controller
system:controller:ttl-controller
system:daemonset-controller
system:deployer
system:deployment-controller
system:deploymentconfig-controller
system:discovery
system:disruption-controller
system:endpoint-controller
system:garbage-collector-controller
system:gc-controller
system:heapster
system:hpa-controller
system:image-auditor
system:image-builder
system:image-pruner
system:image-puller
system:image-pusher
system:image-signer
system:job-controller
system:kube-aggregator
system:kube-controller-manager
system:kube-dns
system:kube-scheduler
system:master
system:namespace-controller
system:node
system:node-admin
system:node-bootstrapper
system:node-problem-detector
system:node-proxier
system:node-reader
system:oauth-token-deleter
system:openshift:aggregate-to-admin
system:openshift:aggregate-to-edit
system:openshift:aggregate-to-view
system:openshift:controller:build-config-change-controller
system:openshift:controller:build-controller
system:openshift:controller:cluster-quota-reconciliation-controller
system:openshift:controller:deployer-controller
system:openshift:controller:deploymentconfig-controller
system:openshift:controller:horizontal-pod-autoscaler
system:openshift:controller:image-import-controller
system:openshift:controller:image-trigger-controller
system:openshift:controller:origin-namespace-controller
system:openshift:controller:pv-recycler-controller
system:openshift:controller:resourcequota-controller
system:openshift:controller:sdn-controller
system:openshift:controller:service-ingress-ip-controller
system:openshift:controller:service-serving-cert-controller
system:openshift:controller:serviceaccount-controller
system:openshift:controller:serviceaccount-pull-secrets-controller
system:openshift:controller:template-instance-controller
system:openshift:controller:template-service-broker
system:openshift:controller:unidling-controller
system:openshift:templateservicebroker-client
system:persistent-volume-provisioner
system:registry
system:replicaset-controller
system:replication-controller
system:router
system:scope-impersonation
system:sdn-manager
system:sdn-reader
system:service-catalog:aggregate-to-admin
system:service-catalog:aggregate-to-edit
system:service-catalog:aggregate-to-view
system:statefulset-controller
system:webhook
view
````
