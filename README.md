# Kubernetes (K8)

![](img/Kubernetes_icon.png)

## What is Kubernetes? (K8)
- Open-source container orchestration platform
- Developed and run by Google
- Automates container behaviour
- K8 because there are 8 letters in the word "Kubernetes"

![](img/Docker-Kubernetes-together.png)
![](img/mono_micro_docker_to_k8.png)

## Benefits of Kubernetes
- Easy to scale your application
- Keep code operational and speeds up the delivery process
- Portability and flexibility
  - K8 works with any type of container runtime
  - K8 works with any type of underlying infrastructure (public cloud, private cloud, on prem)
- Multi-cloud capability

## Definitions
### Pod
- Holds one/more containers
- Any containers in the pod share resources and a network and can communicate with each other, even if they are on separate nodes

### Nodes
- Hardware components
- Virtual machine hosted by a cloud provider or a physical machine in a data centre
- CPU/RAM resources to be used by K8 cluster

### Master Node
- Controls deployment of pods and therefore worker nodes

### Cluster
- A series of nodes connected together
- Run the containerised applications managed by K8

![](img/Basic-Setup-of-a-Kubernetes-Cluster-768x432.png)

## Kubernetes Installation
Prerequisites
- Docker Desktop

Installation
- Open Docker Desktop
- Go into settings -> Kubernetes -> Enable Kubernetes -> Click `Apply & Restart`
- In the terminal, type`kubectl` or `kubectl version`

![](img/kubectl_version_cmd.png)