---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "E-Commerce Website"
summary: |2-
  - Architected a website with microservice back-end architecture to structure a set of services that can be developed,  deployed, and tested independently with Node.js, Express.js, Jest, and MongoDB
  - Deployed to Google Kubernetes Engine (GKE) with Docker, Kubernetes; designed Github CI/CD workflow
  - Implemented a server-side rendered (SSR) front-end with Next.js, React.js, and React Hooks
  - Constructed a NATS streaming server as an event bus for asynchronous communications, solved concurrency issues with event versioning
authors: []
tags: [Full Stack, Microservices, Node.js, Docker, k8s, Next.js, React, MongoDB, Redis, CI/CD, Event bus]
categories: []
date: 2021-09-10T16:55:46+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Holychung/ticketing"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
# Microservices
- Built a ticketing cloud service using microservice architecture with Node.js, React.js, Bull, MongoDB.
- Solved concurrency issues in a distributed systems by communicating data between services using NATS streaming server as an event bus.
- Designed the CI/CD workflow using Github Actions and deployed to Google Cloud and DigitalOcean with Docker, Kubernetes, and Skaffold;
- Implemented a countdown expiration service using a queue system via Bull and Redis
- Built a server-side rendered frontend using Next.js; Automated the testing process using Jest.

## Prerequisites
- skaffold [Installing Skaffold](https://skaffold.dev/docs/install/)
- docker [Install Docker Engine on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
- kubectl [Install and Set Up kubectl on Linux](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)
- minikube [minikube start](https://minikube.sigs.k8s.io/docs/start/)
- ingress-nginx [Ingress Nginx Installation](https://kubernetes.github.io/ingress-nginx/deploy/#minikube)
- nodejs & npm `sudo apt install nodejs npm`
### Env
Ubuntu 20.04.4 LTS

## Getting started
### Docker 
```
sudo usermod -aG docker $USER
```
### Minikube
- 2 CPUs or more
- 2GB of free memory
- 20GB of free disk space
- Internet connection
- Container or virtual machine manager, such as: Docker, Hyperkit, Hyper-V, KVM, Parallels, Podman, VirtualBox, or VMware Fusion/Workstation

```bash
sudo service docker start
minikube start
```
### Install ingress
```bash
minikube addons enable ingress
```
### Check the service namspace
```bash
kubectl get namespace
kubectl get services -n ingress-nginx
```
### Change host file
```bash
vim /etc/hosts
# Add this line
192.168.49.2    ticketing.dev
```
### Create secrets to k8s
```bash
kubectl create secret generic jwt-secret --from-literal=JWT_KEY=asdf
kubectl create secret generic stripe-secret --from-literal STRIPE_KEY=sk_test_XXX
```

### Run
```bash=
git clone git@github.com:Holychung/ticketing.git
cd ticketing
skaffold dev
```
![](https://i.imgur.com/tNUpDvo.png)

## Thanks
