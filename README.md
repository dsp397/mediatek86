# mediatek86

ITS 86 (InfoTech Services 86) est une ESN créée en 2002, spécialisée dans le développement d'applications, l'hébergement web et l'ingénierie système et réseau. Elle compte 32 collaborateurs et intervient auprès de TPE et PME. Dans ce contexte, j'interviens en tant que technicienne développeuse junior pour développer une application de bureau permettant de gérer le personnel des médiathèques du réseau MediaTek86 et leurs absences.

## Fonctionnalités

L'application permet de :

se connecter avec un login et un mot de passe ;
afficher la liste du personnel ;
ajouter un membre du personnel ;
modifier les informations d'un membre du personnel ;
supprimer un membre du personnel ;
consulter les absences d'une personne ;
ajouter, modifier ou supprimer une absence ;
éviter les absences qui se chevauchent.

## Base de données

La base de données est faite avec MySQL.

Elle contient plusieurs tables :

responsable : pour l'identifiant et le mot de passe du responsable ;
personnel : pour les informations des employés ;
service : pour les différents services ;
absence : pour les absences du personnel ;
motif : pour les motifs d'absence.

<img width="1324" height="464" alt="Capture d&#39;écran 2026-05-31 192303" src="https://github.com/user-attachments/assets/c0170953-bc8a-442f-9f85-243c41a93960" />


## Interfaces de l'application

L'application contient plusieurs fenêtres :

- une fenêtre de connexion ;
- une fenêtre principale avec la liste du personnel ;
- une fenêtre pour ajouter ou modifier un personnel ;
- une fenêtre pour afficher les absences ;
- une fenêtre pour ajouter ou modifier une absence.

<img width="776" height="498" alt="Capture d&#39;écran 2026-06-02 215815" src="https://github.com/user-attachments/assets/414ce374-1072-4715-8d3c-98fb0cbb9005" />

## Organisation du projet

Le projet est organisé avec une structure MVC.
mediatek86/
├── bddmanager/
├── dal/
├── controller/
├── model/
└── view/



