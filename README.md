# Learning.AWS
🔹 Étape 1 — Premier pied dans le cloud

Objectif : se connecter à AWS et manipuler un serveur

    Crée ton compte AWS et active la Free Tier

    Configure les alertes de coût (ex. : 1 €)

    Lance une instance EC2 t2.micro (Ubuntu)

        Connecte-toi en SSH

        Installe htop, docker, python

        Joue un peu avec le terminal ☺️

    Éteins-la et redémarre-la

    Supprime-la

➡️ Tu apprends à gérer une machine dans le cloud
🔹 Étape 2 — Stockage et web statique

Objectif : comprendre S3 et héberger un mini site

    Crée un bucket S3

    Active le mode "website static hosting"

    Uploade un fichier index.html de test

    Rends-le accessible publiquement

    Ajoute un fichier CSS ou image

➡️ Tu apprends à stocker et servir des fichiers
🔹 Étape 3 — Dashboard et collecte de données

Objectif : construire ton début de monitoring maison

    Relance un EC2 Ubuntu

    Installe Docker + Docker Compose

    Déploie :

        InfluxDB 2.x

        Grafana

    Teste manuellement l’insertion d’un point via curl

    Crée un dashboard dans Grafana pour voir les données

➡️ Tu touches à la stack de base de ton futur projet de monitoring
🔹 Étape 4 — Sécurisation avec IAM

Objectif : comprendre les permissions

    Crée un utilisateur IAM “admin-labo” avec MFA

    Crée une politique personnalisée pour un accès S3 ou EC2 limité

    Teste les droits avec la console ou la CLI AWS

➡️ Tu apprends les bases de la sécurité AWS
🔹 Étape 5 — Automatisation et scripts

Objectif : commencer à automatiser l'envoi de données

    Sur ton Raspberry Pi ou PC :

        Crée un script Python qui envoie un point à ton InfluxDB sur EC2

        Planifie avec cron un envoi toutes les 5 minutes

    Stocke une copie de ces points dans S3 toutes les heures

➡️ Tu construis ton propre pipeline cloud perso
🔹 Étape 6 — Exploration bonus

Quand tu seras à l’aise :

    Teste Lambda : fonction qui écrit dans Influx ou S3

    Teste CloudWatch : logs, alarmes si température > seuil

    Explore Amazon Timestream (alternative cloud à InfluxDB)
