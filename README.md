# Kubernetes Lab Project

A simple Node.js application for learning Kubernetes deployment.

## Local Development

```bash
npm install
npm start
```

## Docker

```bash
docker build -t kube-lab-app:v1 .
docker run -p 8080:8080 kube-lab-app:v1
```

## Kubernetes Deployment

```bash
kubectl apply -f k8s/
kubectl get pods
kubectl get svc
```

Access at: http://localhost:30080