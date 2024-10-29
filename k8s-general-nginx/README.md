# k8s-general-nginx

demostrate the nginx service in two type

1. `load balancer type`: client -> static ip -> nginx load balancer -> nginx service -> nginx pod
2. `Cluster ip type` client -> static ip  -> cloud lb (gcp) -> neg -> nginx service -> nginx pod
