https://blog.knoldus.com/what-is-headless-service-setup-a-service-in-kubernetes/

kubectl run -it temporary --image=radial/busyboxplus:curl 
kubectl attach -it temporary -c temporary
kubectl attach -it temporary
kubectl exec -it temporary -- nslookup 10-1-2-61.default.pod.cluster.local
