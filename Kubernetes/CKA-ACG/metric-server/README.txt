https://github.com/kubernetes-sigs/metrics-server/issues/196

Actually in the new version, is just add it to args

    args:
    - --cert-dir=/tmp
    - --secure-port=4443
    - --kubelet-preferred-address-types=InternalIP,ExternalIP,Hostname
    - --kubelet-use-node-status-port
    - --kubelet-insecure-tls

