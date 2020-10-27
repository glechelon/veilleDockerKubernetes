# Docker & Kubernetes

## Docker

### Historique

#### Containers 

Au départ le fonctionnement nominal était de mettre une application par serveur physique. Les serveurs étaient de ce fait souvent surdimensionné. 
Pour remédier à ce problème apparait la virtualisation (VMWARE) mais plus couteux en terme de ressources (CPU, RAM, ...) et financièrement. 
Chaque VM nécessitant son propre OS en plus de celui de l'hôte.
C'est pour répondre à ce problème que les containers sont introduits. Car en effet, un container ce n'est qu'un seul OS (celui de l'hôte) découpé en plusieurs morceaux.
Ce qui fait qu'il n'y a pas de coût supplémentaire. L'apparition des containers est étroitement liée à celle de l'architecture microservices. La multiplication du nombre d'applicatifs constiuant l'application en elle même rend la réduction des coûts en ressources importante.  

#### Docker

### Vue haut niveau 

### Docker engine

#### Historique 

#### Implémentations

### Images

### Registeries 

### Bonnes pratiques

### Contenairizé une application

### Multi-stage builds

### Containers 

### Logging

### Docker Swarm

#### Reseau

#### Service discovery

#### Load balancing

#### Secrets

#### Stacks

### Docker EE

## Kubernetes

### Historique 

### Vue haut niveau

### Architecture

### Control plan

### Objets

#### Master

#### Nodes

#### Pod

#### Deploy

#### API & API server

#### Services

### Déployer sur Kubernetes

### Scaling et MAJ
