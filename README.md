# Testing ingress-nginx on kubernetes on Digital Ocean

[ingress-nginx](https://github.com/kubernetes/ingress-nginx) - Official link to ingress-nginx:

My deployment of ingress-nginx on a test cluster:

[mandatory.yaml](mandatory.yaml) - official ingress-nginx default configuration.

[loadbalancer.yaml](loadbalancer.yaml) - example kubernetes service object of type LoadBalancer which works with digital oceans kubernetes. 

[exterlandns.yaml](exterlandns.yaml) - test running externaldns as a pod which can update add dns entries for ingress rules.

[custom-default-backend.yaml](custom-default-backend.yaml) - playing with custom error backend.
