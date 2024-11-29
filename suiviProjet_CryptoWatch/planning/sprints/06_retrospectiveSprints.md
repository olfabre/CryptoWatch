# Rétrospective des Sprints

# Projet CryptoWatch  

Ce document est destiné à faire le bilan de chaque sprint. Il sert à analyser ce qui a bien fonctionné, ce qui peut être amélioré, et à définir des actions concrètes pour le prochain sprint.  

---

## Rétrospective Sprint 1 : Configuration et fonctionnalités de base  
- **Durée** : Du 01/12/2024 au 07/12/2024  
- **Objectif principal** : Mise en place de l’environnement de développement et implémentation des fonctionnalités de base (affichage des cryptomonnaies).  

### Ce qui a bien fonctionné  
- L’environnement de développement a été configuré rapidement, et l’intégration de la base de données s’est bien déroulée.  
- Le travail en équipe a été fluide, chaque membre a respecté les délais pour ses tâches.  
- La communication dans l’équipe a été très efficace pour résoudre rapidement les problèmes techniques.

### Ce qui a posé problème  
- L’affichage des cryptomonnaies a pris plus de temps que prévu en raison d’un manque d’expérience avec l’API utilisée pour récupérer les données.  
- Le développement de la fonctionnalité de recherche a été plus complexe que prévu, en particulier pour gérer les résultats en temps réel.  
- Les tests n’ont pas pu être réalisés à temps pour toutes les fonctionnalités, car certaines étaient encore incomplètes à la fin du sprint.

### Actions à entreprendre pour le prochain sprint  
- **Améliorer la gestion des APIs** : Prévoir une phase de test API au début du sprint pour mieux comprendre son fonctionnement.  
- **Optimiser la gestion du temps** : Utiliser des outils de suivi du temps pour éviter que certaines tâches ne dépassent la limite estimée.  
- **Planification des tests** : Intégrer les tests dans le processus de développement dès le début du sprint pour éviter les retards à la fin.

---

## Rétrospective Sprint 2 : Visualisations graphiques  
- **Durée** : Du 08/12/2024 au 14/12/2024  
- **Objectif principal** : Permettre la visualisation graphique des variations de prix.  

### Ce qui a bien fonctionné  
- L'intégration de la bibliothèque de graphiques (D3.js) a été réussie, et l'équipe a bien réussi à s'adapter à la nouvelle technologie.  
- La fonctionnalité de visualisation des graphiques a été bien accueillie par l’équipe et fonctionne bien pour les périodes de temps demandées (1 jour, 1 semaine).  
- Le processus de développement a été plus rapide, et nous avons pu avancer sur plusieurs tâches en parallèle.

### Ce qui a posé problème  
- Le défi principal a été la gestion de la superposition des graphiques pour la comparaison de plusieurs cryptomonnaies, cela a nécessité plus de travail que prévu.  
- Des problèmes de performance ont été constatés lors de la génération de graphiques pour un grand nombre de données.  
- Le temps estimé pour l’ajout de la fonctionnalité de comparaison a été sous-estimé.

### Actions à entreprendre pour le prochain sprint  
- **Optimiser la performance** : Analyser la source des problèmes de performance et prévoir des solutions (ex. : utiliser des échantillons de données ou implémenter des mécanismes de lazy loading).  
- **Réévaluer les estimations de temps** : Mieux prendre en compte la complexité des tâches avant de donner des estimations.  
- **Tests dès le début** : Planifier les tests plus tôt dans le sprint afin d’éviter des retards dans la validation des fonctionnalités.

---

## Rétrospective Sprint 3 : Alertes personnalisées  
- **Durée** : Du 15/12/2024 au 21/12/2024  
- **Objectif principal** : Implémenter les alertes personnalisées et finaliser l’application.  

### Ce qui a bien fonctionné  
- La mise en place des alertes de prix a été réalisée comme prévu et fonctionne correctement.  
- Le déploiement des fonctionnalités finales s’est bien déroulé, avec une validation des alertes par l’équipe avant la mise en production.  
- La gestion des tâches a été plus efficace grâce à une meilleure estimation des durées.

### Ce qui a posé problème  
- Le temps de développement des alertes a été affecté par la complexité de l’architecture backend (gestion des notifications en temps réel).  
- Quelques problèmes de synchronisation entre les alertes et les données en temps réel ont été rencontrés.

### Actions à entreprendre pour le prochain sprint  
- **Améliorer la gestion des notifications en temps réel** : Travailler sur la mise en place de mécanismes plus robustes pour la gestion des alertes en temps réel (ex. : services de push notifications).  
- **Revue continue de l’architecture** : Prévoir des revues d’architecture à mi-sprint pour détecter les problèmes potentiels avant qu’ils ne deviennent critiques.  
- **Continuer à prioriser les tests** : S’assurer que les tests de régression sont bien effectués pour éviter de briser des fonctionnalités existantes.

---

## Récapitulatif des points clés pour l'amélioration continue  
- **Communication et collaboration** : Maintenir une communication régulière au sein de l’équipe pour éviter les malentendus et les retards.  
- **Gestion du temps** : Utiliser des outils de suivi de tâches plus précis et prévoir des marges de sécurité pour les tâches complexes.  
- **Tests et validations** : Intégrer les tests tout au long du développement et non à la fin, et prévoir des tests unitaires pour les nouvelles fonctionnalités.  

---

## Conclusion  
Le projet avance bien, mais nous avons constaté qu’une meilleure planification des tâches complexes et des tests en amont pourrait améliorer notre efficacité. Nous allons continuer à nous concentrer sur ces points d’amélioration pour les prochains sprints.  
