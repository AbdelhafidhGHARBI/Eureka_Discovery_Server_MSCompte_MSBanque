Description longue (à utiliser dans le README ou sur GitHub)
Ce projet implémente un Eureka Discovery Server dans le cadre d'une architecture basée sur des microservices Spring Boot, en particulier 
les services MSCompte et MSBanque.

Le Discovery Server joue un rôle central dans la découverte de services, permettant aux microservices de s’enregistrer dynamiquement 
et de se découvrir les uns les autres, facilitant ainsi la scalabilité, la tolérance aux pannes et la communication décentralisée.

Il s’intègre parfaitement avec des composants tels que Spring Cloud Gateway pour le routage, et peut être connecté à un système 
de configuration centralisé si nécessaire.

✅ Fonctionnalités principales :
Enregistrement dynamique des microservices (clients Eureka)
Tableau de bord Eureka accessible via navigateur
Support de la scalabilité (HA possible)
Intégration prête avec MSCompte, MSBanque et une API Gateway
Configuration extensible (application.yml ou application.properties)
