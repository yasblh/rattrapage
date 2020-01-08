# Session rattrapage

Cet exercice sert à évaluer l'étudiant pour le rattrapage. L'exercice consiste à créer les fichiers Terraform nécessaire afin d'automatiser le déploiement de l'application Petclinic sur le cloud AWS.

Les fichiers seront à commiter dans le dossier **answer**.

Afin de pouvoir commiter dans git les fichiers, l'étudiant doit d'abord forker le repository Github dans son propre repository personnel.

Les fichiers Terraform devront permettre la création :
- D'un **VPC** constitué
  - D'un **subnet**
  - D'une **internet gateway**
  - D'un **security group**
  - D'une **route table association**
- D'une **machine virtuelle** Ubuntu constitué
  - D'un **OpenJDK**
  - De **git**
  - De **Maven**
  - Du programme Petclinic disponible ici : **https://github.com/spring-projects/spring-petclinic**

L'étudiant sera noté sur les fichiers Terraform présent dans son repository personnel.