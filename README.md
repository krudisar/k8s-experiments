# k8s-experiments
Mix of links, Q/A and howtos around Kubernetes and related technologies.

- [ ] VMware PKS Enterprise without NSX-T
- [ ] Terraform / Kubespray / vSphere
- [ ] Add Ingress (Traefik | Nginx)
- [ ] Add Let's Encrypt Integration with Ingress 
- [ ] vSphere Storage for Kubernetes - Modify App to Use Persistent Storage
- [ ] Add Wavefront Monitoring

# VMware Cloud Native Apps
- Apps on PKS - (https://github.com/CNA-Tech/Apps-on-PKS)
  - Ingress, Prometheus, Istio, Contour, Jenkins, ...
- PKS Ninja Community - (https://github.com/CNA-Tech/PKS-Ninja)
- PKS-POC - (https://github.com/CNA-Tech/PKS-POC)
  - Applications-Deployment, Harbor-Integration, NSX-T-Integration, WaveFront-Integration, Persistent-Volumes
  
# Supergiant Blog Around Kubernetes
- Blog: (https://supergiant.io/blog/)
- Deploying Traefik as Ingress Controller for Your Kubernetes Cluster - (https://supergiant.io/blog/using-traefik-as-ingress-controller-for-your-kubernetes-cluster/)
- Kubernetes Storage: Introduction - (https://supergiant.io/blog/kubernetes-storage-introduction/)
- Managing Stateful Apps with Kubernetes StatefulSets - (https://supergiant.io/blog/managing-stateful-apps-with-kubernetes-statefulsets/)

# VMware & Kubernetes
- vSphere Storage for Kubernetes - (https://vmware.github.io/vsphere-storage-for-kubernetes/documentation/index.html)
  - Details - (https://gitee.com/cdtian/kubespray/raw/master/docs/vsphere.md)

# Generic Kubernetes Howtos
- From Start to PKS - (https://github.com/keunlee/from-start-to-pks)
- Ultimate Kubernetes Bootcamp - (https://schoolofdevops.github.io/ultimate-kubernetes-bootcamp/cluster_setup_kubespray/)

# Minikube | Kubespray | MicroK8s | ...

- Get Started With Kubernetes Using Minikube - (https://docs.bitnami.com/kubernetes/get-started-kubernetes/#step-4-install-helm-and-tiller)
- terraform-vsphere-kubespray - (https://github.com/sguyennet/terraform-vsphere-kubespray)
- Kubespray – 10 Simple Steps for Installing a Production-Ready, Multi-Master HA Kubernetes Cluster - (https://aws-labs.com/kubespray-10-simple-steps-installing-production-ready-multi-master-ha-kubernetes-cluster/)
- Kubespray — 10 simple steps for installing a production ready, multi-master HA Kubernetes cluster on bare-metal servers - (https://medium.com/@amit.man1810/kubespray-10-simple-steps-for-installing-a-production-ready-multi-master-ha-kubernetes-cluster-5d3ba9b35703)
- Kubespray Official Documentation - (https://kubespray.io)

# Generic Ingress
- Getting external traffic into Kubernetes – ClusterIp, NodePort, LoadBalancer, and Ingress - (https://www.ovh.com/fr/blog/getting-external-traffic-into-kubernetes-clusterip-nodeport-loadbalancer-and-ingress/)
- Kubernetes Ingress with Nginx Example - (https://matthewpalmer.net/kubernetes-app-developer/articles/kubernetes-ingress-guide-nginx-example.html)
- Kubernetes Nginx Ingress Controller - (https://akomljen.com/kubernetes-nginx-ingress-controller/)

# Traefik Load Balancer & Ingress
- Kubernetes & Traefik 101— When Simplicity Matters - (https://medium.com/@geraldcroes/kubernetes-traefik-101-when-simplicity-matters-957eeede2cf8)
- Traefik as K8S Ingress Controller - (https://medium.com/@dusansusic/traefik-ingress-controller-for-k8s-c1137c9c05c4)
- Kubernetes Ingress Provider - (https://docs.traefik.io/configuration/backends/kubernetes/)
- Kubernetes cluster step-by-step: Services and Load Balancing (Traefik) - (https://icicimov.github.io/blog/kubernetes/Kubernetes-cluster-step-by-step-Part8/)
- Proxying Kubernetes services with Traefik - (https://www.praqma.com/stories/proxying-kubernetes/)
- Awesome Traefik - (https://github.com/containous/traefik/wiki/Awesome-Traefik)
  - A comprehensive list of Taefik resources

# Kubernetes RBAC
- Testing Kubernetes RBAC - (https://medium.com/yld-engineering-blog/testing-kubernetes-rbac-5e00dc93af8e)

# Let's Encrypt
- How to install Let's Encrypt certs on a dockerized Nginx - (https://devopsheaven.com/letsencrypt/devops/docker/nginx/https/www/seo/2017/09/01/letsencrypt-certificates-nginx.html)
- How To Secure a Containerized Node.js Application with Nginx, Let's Encrypt, and Docker Compose - (https://www.digitalocean.com/community/tutorials/how-to-secure-a-containerized-node-js-application-with-nginx-let-s-encrypt-and-docker-compose)
- Deploying multiple Traefik Ingresses with LetsEncrypt HTTPS certificates on Kubernetes - (https://medium.com/@carlosedp/multiple-traefik-ingresses-with-letsencrypt-https-certificates-on-kubernetes-b590550280cf)
- Kubernetes : Ingress Controller with Træfɪk and Let’s Encrypt - (https://aws-labs.com/kubernetes-ingress-controller-traefɪk-encrypt/)

# Helm
- How To Create Your First Helm Chart - (https://docs.bitnami.com/kubernetes/how-to/create-your-first-helm-chart/)

# Kubernetes App Deplyments/Updates Strategies
- Enable Rolling updates in Kubernetes with Zero downtime - (https://medium.com/platformer-blog/enable-rolling-updates-in-kubernetes-with-zero-downtime-31d7ec388c81)
- Save costs in your Kubernetes cluster with 5 open source tools - (https://itnext.io/save-costs-in-your-kubernetes-cluster-with-5-open-source-projects-7f53899a1429)
  - [] Monitor excessive resource requests with Prometheus
  - [] Working hours autoscaling
  - [] Nodes autoscaling
  - [] Horizontal pod autoscaling
  - [] Vertical pod autoscaling
  
# Tips from Internet
- How to wait until Kubernetes assigned an external IP to a LoadBalancer service? - (https://stackoverflow.com/questions/35179410/how-to-wait-until-kubernetes-assigned-an-external-ip-to-a-loadbalancer-service)
