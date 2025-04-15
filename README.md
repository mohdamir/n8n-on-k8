# n8n-on-k8
n8n deployment on k8
'''

kubectl apply -f n8n-namespace.yaml
kubectl apply -f n8n-pvc.yaml
kubectl apply -f n8n-deployment.yaml
kubectl apply -f n8n-service.yaml
kubectl apply -f n8n-ingress.yaml

'''
