# projet_cloud_computing



##  ** Introduction **

Environnement : 

-  Pipeline CI/CD détaillé : 
- outils sélectionnés : github actions
-  Stratégie IaC : Terraform
-  


## ** Explication de mise en place  ** 


Cloud Provider : AWS (Amazon Web Services).
il est certifié HDS, et c'est le plus documenté sur Internet (facile de trouver de l'aide).
Condition stricte : Vous devez sélectionner la région Paris (eu-west-3) pour respecter la souveraineté des données.
Conteneurisation : Docker.
Usage : Pour "emballer" l'application Java Spring Boot.
Orchestration : Amazon EKS (Elastic Kubernetes Service).
Usage : C'est le Kubernetes managé par AWS. Plus simple que d'installer Kubernetes soi-même.
Infrastructure as Code (IaC) : Terraform.
Usage : Pour créer le réseau (VPC), la base de données et le cluster EKS par du code.
CI/CD (Automatisation) : GitHub Actions.
Usage : C'est gratuit, intégré à votre code source, et beaucoup plus simple à configurer que Jenkins pour des débutants.
Base de Données : Amazon RDS for PostgreSQL.
Usage : Service managé (PaaS) pour remplacer vos serveurs PostgreSQL actuels.
Stockage Fichiers : Amazon S3.
Usage : Pour remplacer le NAS de 15 To et stocker les documents médicaux.

## ** Ressources ** 

```bash

https://drive.google.com/file/d/1GhdwhF2zA9PifVI-5PgjVOVQe7npN84l/view?usp=sharing


```

