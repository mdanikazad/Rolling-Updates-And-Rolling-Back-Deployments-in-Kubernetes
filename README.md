# Rolling-Updates-And-Rolling-Back-Deployments-in-Kubernetes
Rolling Updates And Rolling Back Deployments in Kubernetes


kubectl get deployments
kubectl describe deployment httpd-deploy -namespace
kubectl set image deployment httpd-deploy httpd=httpd:2.4.25
kubectl set image deployment httpd-deploy httpd=httpd:2.4.43
kubectl rollout status deployment httpd-deploy

https://www.techcrumble.net/2019/01/kubernetes-deployment-rolling-updates-and-rolling-back/

https://www.assistanz.com/steps-to-create-custom-namespace-in-the-kubernetes/

