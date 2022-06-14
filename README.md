# Testing ingress-nginx on kubernetes on Digital Ocean

[ingress-nginx](https://github.com/kubernetes/ingress-nginx) - Official link to ingress-nginx:

My deployment of ingress-nginx on a test cluster:

Currently using helm chart to install the ingress-nginx.
```bash
helm show values ingress-nginx
helm install blabla ingress-nginx/ingress-nginx
```

Now DO setups the loadbalaner and creates it.

[exterlandns.yaml](exterlandns.yaml) - test running externaldns as a pod which can update add dns entries for ingress rules.
