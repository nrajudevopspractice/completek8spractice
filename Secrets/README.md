### For Secrets workload
# Secret is similar to config map with following differences
    # Secret is used to store a small amount of sensitive data. Secret is base64 encoded
    # K8s ensures that secrets are passed only to the nodes that are running the Pods that need respective secrets
# Types of Secrets
    # generic
    # tls
    # docker-registry