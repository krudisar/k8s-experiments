# k8s-experiments
Mix of links, Q/A and howtos around Kubernetes and related technologies.

- [X] VMware PKS Enterprise without NSX-T
- [X] Terraform / Kubespray / vSphere
- [X] MetalLB LoadBalancer with PKS Enterprise 
- [ ] vSphere Storage for Kubernetes - Modify App to Use Persistent Storage
- [ ] HELM Charts with PKS Enterprise
- [X] Add Wavefront Monitoring
- [ ] A Read Only Kubernetes Dashboard (http://blog.cowger.us/2018/07/03/a-read-only-kubernetes-dashboard.html)
- [ ] Add Ingress (Traefik | Nginx)
- [ ] Add Let's Encrypt Integration with Ingress 

# VMware Cloud Native Apps - PKS Resources
- Apps on PKS - (https://github.com/CNA-Tech/Apps-on-PKS)
  - Ingress, Prometheus, Istio, Contour, Jenkins, ...
- PKS Ninja Community - (https://github.com/CNA-Tech/PKS-Ninja)
- PKS-POC - (https://github.com/CNA-Tech/PKS-POC)
  - Applications-Deployment, Harbor-Integration, NSX-T-Integration, WaveFront-Integration, Persistent-Volumes
- TechSummit PKS Demo (https://github.com/bdereims/pks-prep/tree/master/k8s/TechSummit)
  
# Serverless - AWS Lambda #
- Create a REST API Endpoint Using AWS Lambda (https://hackersandslackers.com/create-a-rest-api-endpoint-using-aws-lambda/)
- Serverless API: Creating a Serverless md5 Hash Generator Using AWS Lambda & Chalice (https://medium.com/devopslinks/creating-a-serverless-python-api-using-aws-lambda-chalice-d321dc43ce2)
- AWS Lambda + Serverless Framework + Python — A Step By Step Tutorial — Part 1 “Hello World” (https://medium.com/devopslinks/aws-lambda-serverless-framework-python-part-1-a-step-by-step-hello-world-4182202aba4a)
- Creating a Serverless Uptime Monitor & Getting Alerted by SMS — Lambda, Zappa & Python (https://medium.com/devopslinks/creating-a-serverless-uptime-monitor-getting-alerted-by-sms-lambda-zappa-python-flask-15c5fb31027)

# Monitoring Using Prometheus / Grafana #
- Get Kubernetes Cluster Metrics with Prometheus in 5 Minutes (https://akomljen.com/get-kubernetes-cluster-metrics-with-prometheus-in-5-minutes/)
- !!! - Production grade Kubernetes Monitoring using Prometheus (https://medium.com/devopslinks/production-grade-kubernetes-monitoring-using-prometheus-78144b835b60)
- !!! - Kubernetes Monitoring with Prometheus: AlertManager, Grafana, PushGateway (https://sysdig.com/blog/kubernetes-monitoring-with-prometheus-alertmanager-grafana-pushgateway-part-2/)

# Log Management Using ELK
- Get Kubernetes Logs with EFK Stack in 5 Minutes (https://akomljen.com/get-kubernetes-logs-with-efk-stack-in-5-minutes/)

# Supergiant Blog Around Kubernetes
- Blog: (https://supergiant.io/blog/)
- Deploying Traefik as Ingress Controller for Your Kubernetes Cluster - (https://supergiant.io/blog/using-traefik-as-ingress-controller-for-your-kubernetes-cluster/)
- Kubernetes Storage: Introduction - (https://supergiant.io/blog/kubernetes-storage-introduction/)
- Managing Stateful Apps with Kubernetes StatefulSets - (https://supergiant.io/blog/managing-stateful-apps-with-kubernetes-statefulsets/)

# VMware & Kubernetes
- vSphere Storage for Kubernetes - (https://vmware.github.io/vsphere-storage-for-kubernetes/documentation/index.html)
  - Details - (https://gitee.com/cdtian/kubespray/raw/master/docs/vsphere.md)
- Steps to Install Kubernetes on CentOS7 with Kubeadm and vSphere (https://gist.github.com/kacole2/200ae9362b010480f866d82a363c5327)
  - includes vSphere Persistent Storage Provider

# Generic Kubernetes Howtos
- From Start to PKS - (https://github.com/keunlee/from-start-to-pks)
- Ultimate Kubernetes Bootcamp - (https://schoolofdevops.github.io/ultimate-kubernetes-bootcamp/cluster_setup_kubespray/)

# Minikube | Kubespray | MicroK8s | Typhoon | ...
- Get Started With Kubernetes Using Minikube - (https://docs.bitnami.com/kubernetes/get-started-kubernetes/#step-4-install-helm-and-tiller)
- terraform-vsphere-kubespray - (https://github.com/sguyennet/terraform-vsphere-kubespray)
- Kubespray – 10 Simple Steps for Installing a Production-Ready, Multi-Master HA Kubernetes Cluster - (https://aws-labs.com/kubespray-10-simple-steps-installing-production-ready-multi-master-ha-kubernetes-cluster/)
- Kubespray — 10 simple steps for installing a production ready, multi-master HA Kubernetes cluster on bare-metal servers - (https://medium.com/@amit.man1810/kubespray-10-simple-steps-for-installing-a-production-ready-multi-master-ha-kubernetes-cluster-5d3ba9b35703)
- Kubespray Official Documentation - (https://kubespray.io)

# Heptio
- Kubernetes Contour Ingress Controller for Envoy Proxy - (https://akomljen.com/kubernetes-contour-ingress-controller-for-envoy-proxy/)

# Generic Ingress
- Getting external traffic into Kubernetes – ClusterIp, NodePort, LoadBalancer, and Ingress - (https://www.ovh.com/fr/blog/getting-external-traffic-into-kubernetes-clusterip-nodeport-loadbalancer-and-ingress/)
- Kubernetes Ingress with Nginx Example - (https://matthewpalmer.net/kubernetes-app-developer/articles/kubernetes-ingress-guide-nginx-example.html)
- Kubernetes Nginx Ingress Controller - (https://akomljen.com/kubernetes-nginx-ingress-controller/)

# Traefik Load Balancer & Ingress
- Kubernetes & Traefik 101— When Simplicity Matters - (https://medium.com/@geraldcroes/kubernetes-traefik-101-when-simplicity-matters-957eeede2cf8)
- (!) **Traefik as K8S Ingress Controller** - (https://medium.com/@dusansusic/traefik-ingress-controller-for-k8s-c1137c9c05c4)
  - https://github.com/dusansusic/kubernetes-traefik
- Kubernetes Ingress Provider - (https://docs.traefik.io/configuration/backends/kubernetes/)
- Kubernetes cluster step-by-step: Services and Load Balancing (Traefik) - (https://icicimov.github.io/blog/kubernetes/Kubernetes-cluster-step-by-step-Part8/)
- Proxying Kubernetes services with Traefik - (https://www.praqma.com/stories/proxying-kubernetes/)
- Awesome Traefik - (https://github.com/containous/traefik/wiki/Awesome-Traefik)
  - A comprehensive list of Taefik resources

# MetalLB - Kubernetes Load Balancer / Ingress
- Install and configure MetalLB as a load balancer for Kubernetes (https://blog.inkubate.io/install-and-configure-metallb-as-a-load-balancer-for-kubernetes/)
  - https://github.com/danderson/metallb
  - Using Kubernetes ExternalDNS & MetalLB with a Home/Bare Metal K8S: Part 1 (https://blog.cowger.us/2018/07/25/using-kubernetes-externaldns-with-a-home-bare-metal-k8s.html)
  
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

# Slack API resources #
- https://github.com/slackapi/python-link-button-example
- https://github.com/slackapi/python-message-menu-example

# Python Apps & Kubernetes
- Deploy a simple Python application with Kubernetes (https://developer.ibm.com/tutorials/scalable-python-app-with-kubernetes/)
- Monitoring Your Synchronous Python Web Applications Using Prometheus (https://blog.codeship.com/monitoring-your-synchronous-python-web-applications-using-prometheus/)
- Python + Prometheus Demo (https://github.com/amitsaha/python-prometheus-demo)
- Quickstart for Python/WSGI applications (https://uwsgi-docs.readthedocs.io/en/latest/WSGIquickstart.html)

# Azure #
- Creating web apps with Flask in Azure (https://github.com/Cojacfar/FlaskWeb)


# Environment Variables in Dockerfile, docker-compose & Kubernetes deployment YAML
- Using environment variables in Kubernetes deployment spec (https://serverfault.com/questions/791715/using-environment-variables-in-kubernetes-deployment-spec)
- Define Environment Variables for a Container (https://kubernetes.io/docs/tasks/inject-data-application/define-environment-variable-container/)
- Define a Command and Arguments for a Container (https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#use-environment-variables-to-define-arguments)
- Expose Pod Information to Containers Through Environment Variables (https://kubernetes.io/docs/tasks/inject-data-application/environment-variable-expose-pod-information/)
- Using Variables in Docker Compose files - (https://blog.agchapman.com/using-variables-in-docker-compose-files/)
- Environment variables in Compose (https://docs.docker.com/compose/environment-variables/)
