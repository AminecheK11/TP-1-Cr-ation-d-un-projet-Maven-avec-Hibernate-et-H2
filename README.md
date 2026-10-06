## Étape 1 : Classe App.java

<img width="1280" height="799" alt="cap2_lab1" src="https://github.com/user-attachments/assets/108ddfd5-5609-4ef2-992a-363a9629de23" />

Cette capture montre la classe principale App.java, qui utilise Hibernate/JPA pour créer et insérer trois produits (Laptop, Smartphone et Tablette) dans la base de données H2.
Elle montre également le maintien de l’application en exécution afin de permettre l’accès à la console Web H2 et la vérification des données enregistrées

## Étape 2 : Exécution Hibernate

<img width="742" height="652" alt="cap3_lab1" src="https://github.com/user-attachments/assets/9a998213-a44c-4658-88e6-b92999fd91df" />

Cette capture montre l’exécution réussie de l’application Hibernate, avec l’insertion des trois produits dans la table Produit et l’exécution automatique des requêtes SQL.
Elle confirme également la récupération correcte des données, avec l’affichage de Laptop, Smartphone et Tablette ainsi que leurs identifiants et leurs prix.

## Étape 3 : Vérification de l'exécution et accès à la console H2

<img width="578" height="241" alt="cap4_lab1" src="https://github.com/user-attachments/assets/c39d78f2-6851-4abd-b541-ecaec09a4640" />

Cette capture montre que les trois produits ont été récupérés correctement et que la recherche du produit avec l’ID 2 retourne le Smartphone.

Elle confirme également que la console Web H2 est disponible sur le port 8082 et que l’application reste active pour permettre la consultation de la base de données.

## Étape 4 : Vérification des données dans la console H2


<img width="1167" height="666" alt="cap5_lab1" src="https://github.com/user-attachments/assets/39ee851e-c902-48d7-b174-f945d1b25631" />


Cette capture montre la table PRODUIT générée par Hibernate dans la base de données H2 avec les colonnes ID, NOM et PRIX.

L’exécution de la requête `SELECT * FROM PRODUIT;` confirme que les trois produits ont bien été enregistrés dans la base de données.
