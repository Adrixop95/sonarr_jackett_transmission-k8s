# sonarr_jackett_transmission-k8s
A simple stack for automated anime download.

# Usage example
```console
$ kubectl apply -f storage_service.yml
$ kubectl apply -f service.yml
$ kubectl expose deployment service --type=LoadBalancer --name=service
```