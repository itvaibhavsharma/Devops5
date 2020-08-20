# Devops5


Integrate Prometheus and Grafana and perform in following way:
1.  Deploy them as pods on top of Kubernetes by creating resources Deployment, ReplicaSet, Pods or Services
2.  And make their data to be remain persistent 
3.  And both of them should be exposed to outside world
    

**Job1**
Here We need to create two images
Grafana
Prometheus 
Using the Docker files we make the images docker files are renamed here for no conflicts and easily understandable

**Creating image for grafna**
![Pic1](images/1.png)
![Pic1](images/3.png)

**Creating image for prometheus**
![Pic1](images/4.png)

**Using grafana.yml(graf.yml) && prometheus.yml(new.yml)**
kubectl apply -f grapf.yml
kubectl apply -f new.yml
![Pic1](images/5.png)

minikube ip
to know ip
![Pic1](images/9.png)

***Graphana Server Running 
![Pic1](images/6.png)
Prometheus server Running
![Pic1](images/8.png)

All files are provided on repo needs renaming
