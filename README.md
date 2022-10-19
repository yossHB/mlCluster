How to install Kubeflow v1.6 on ubuntu


sudo snap install microk8s --classic --channel=1.21/stable
sudo microk8s status
sudo microk8s inspect
sudo usermod -a -G microk8s mimo
sudo chown -f -R mimo ~/.kube
sudo microk8s enable dns storage ingress metallb:10.64.140.43-10.64.140.49








## biblio:
- https://medium.com/@rochageorge/how-to-set-up-microk8s-and-charmed-kubeflow-on-ubuntu-oci-2531bae8daf2
- https://phoenixnap.com/kb/install-kubernetes-on-ubuntu
- https://ubuntu.com/kubernetes/install
- https://charmed-kubeflow.io/docs/install
- https://kubernetes.io/docs/setup/production-environment/tools/kops/
- https://learn.hashicorp.com/tutorials/terraform/install-cli


