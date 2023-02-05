# demo-static-website

Two HELM charts that will deploy nginx server with static content from ConfigMap. I use config map, because it was easy to not bother creating my own image for example. In the first chart we will create NGINX Ingress object to route the traffic for both charts/services. 