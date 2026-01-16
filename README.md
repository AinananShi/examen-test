Ce projet lance une pipeline automatisée les actions de github :

* **Intégration Continue (CI) :** A chaque push sur la branche master ou develop on installe node js 18, les dépendances puis exécute les tests et la vérification du code 
* **Déploiement Continu (CD) :** Sur la branche master, l'image docker est construite, pushé sur docker hub puis scannée par trivy