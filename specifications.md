create multi-node clusters command
    cluster --config=config.yaml


create pod
    kubectl apply -f k8s/pod.yaml
Forward Port
    kubectl port-forward pod/goserver 8000:80

create replicas from your pod
    kubectl apply -f k8s/replicaset.yaml