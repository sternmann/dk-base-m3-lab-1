# Sprint 2
TODO: Student to complete code and comments in the sections below.

## Install Kubernetes node 2

- Results from kubeadm --join:

- $ sudo kubeadm join 172.31.35.56:6443 --token 04iy1d.clyirnl5cgb80vlb \
        --discovery-token-ca-cert-hash sha256:260cf274cc96d450437915945097b3ee767eca4138b9bce2616b1d6a435032c8 
[preflight] Running pre-flight checks
[preflight] Reading configuration from the cluster...
[preflight] FYI: You can look at this config file with 'kubectl -n kube-system get cm kubeadm-config -o yaml'
[kubelet-start] Writing kubelet configuration to file "/var/lib/kubelet/config.yaml"
[kubelet-start] Writing kubelet environment file with flags to file "/var/lib/kubelet/kubeadm-flags.env"
[kubelet-start] Starting the kubelet
[kubelet-start] Waiting for the kubelet to perform the TLS Bootstrap...

This node has joined the cluster:
* Certificate signing request was sent to apiserver and a response was received.
* The Kubelet was informed of the new secure connection details.

Run 'kubectl get nodes' on the control-plane to see this node join the cluster.
