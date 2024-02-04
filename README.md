# Jenkins-in-Kubernetes
Installing Jenkins inside K8s with Custom Domain and Certification

# Deploy Jenkins
kubectl apply -f jenkins-deployment.yaml


# Create Jenkins Service
kubectl apply -f jenkins-service.yaml


# Set Up Ingress for Jenkins
kubectl apply -f jenkins-ingress.yaml



