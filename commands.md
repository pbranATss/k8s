** Login to namespace:

kubectl vsphere login --server IP-ADDRESS-SUPERVISOR-CLUSTER --vsphere-username VCENTER-SSO-USERNAME

kubectl config use-context SUPERVISOR-NAMESPACE

List the available virtual machine classes.

kubectl get virtualmachineclassbindings

Create cluster:

Log in to the Supervisor Cluster.

kubectl vsphere login --server IP-ADDRESS-SUPERVISOR-CLUSTER --vsphere-username VCENTER-SSO-USERNAME

Switch context to the target vSphere Namespace.

kubectl config use-context SUPERVISOR-NAMESPACE

List and describe the available Tanzu Kubernetes releases.

kubectl get tanzukubernetesreleases
kubectl describe tanzukubernetesreleases

