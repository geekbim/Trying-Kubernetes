## Installation

```bash
$ npm install
```

## Running the app

```bash
$ docker compose build

$ docker compose up -d
```
Let's check if there are any deployments in the cluster:
```bash
$ kubectl get deployments
```
Let's create the deployment by typing:
```bash
$ kubectl apply -f deployment.yaml
```
Then let's try to get the deployments again:
```bash
$ kubectl get deployments
```
We can also get a detail of the pods:
```bash
$ kubectl get pods
```
Let's check if there are any services in the cluster:
```bash
$ kubectl get services
```
Let's create the service by typing:
```bash
$ kubectl apply -f service.yaml
```
Then let's try to get the services again:
```bash
$ kubectl get services
```
Finally, visit localhost:80