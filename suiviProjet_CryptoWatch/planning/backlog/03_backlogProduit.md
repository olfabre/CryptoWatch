# Backlog Produit

# Projet CryptoWatch  

Le backlog produit regroupe toutes les user stories identifiées pour le projet, classées par priorité et regroupées par fonctionnalité ou module. Chaque story suit le format :  
**En tant que [utilisateur/acteur]**, je veux [fonctionnalité] afin de [bénéfice attendu].  

---

## 1. User stories par module  

### 1.1 Module : Consultation des prix  
- **US01** : En tant qu’utilisateur, je veux voir la liste des principales cryptomonnaies avec leur prix actuel afin de connaître leur valeur en un coup d’œil.  
  - **Critères d’acceptation** :  
    - La liste affiche au moins 50 cryptomonnaies.  
    - Les prix sont mis à jour toutes les 10 secondes.  

- **US02** : En tant qu’utilisateur, je veux pouvoir rechercher une cryptomonnaie spécifique par nom ou symbole afin de gagner du temps.  
  - **Critères d’acceptation** :  
    - Une barre de recherche est disponible sur la page.  
    - Les résultats s’affichent en temps réel dès la saisie.  

### 1.2 Module : Visualisation graphique  
- **US03** : En tant qu’utilisateur, je veux voir un graphique des variations de prix pour une cryptomonnaie afin de suivre son évolution sur différentes périodes (1 jour, 1 semaine, 1 mois).  
  - **Critères d’acceptation** :  
    - Le graphique est interactif avec un curseur de temps.  
    - Les données sont récupérées via une API fiable.  

- **US04** : En tant qu’utilisateur, je veux pouvoir comparer graphiquement deux cryptomonnaies afin d’identifier la plus performante.  
  - **Critères d’acceptation** :  
    - Deux graphiques superposés ou côte à côte.  
    - Sélection des cryptomonnaies via un menu déroulant.  

### 1.3 Module : Alertes personnalisées  
- **US05** : En tant qu’utilisateur, je veux configurer une alerte pour être notifié quand une cryptomonnaie atteint un prix précis.  
  - **Critères d’acceptation** :  
    - Possibilité de définir un seuil minimum ou maximum.  
    - Notification envoyée par e-mail ou affichée sur l’interface.  

- **US06** : En tant qu’utilisateur, je veux visualiser la liste de mes alertes configurées pour les modifier ou les supprimer si nécessaire.  
  - **Critères d’acceptation** :  
    - Une liste des alertes est accessible depuis un menu dédié.  

---

## 2. Priorisation des user stories  
Les user stories sont classées par ordre de priorité pour guider le développement.  

| **ID**   | **Description**                                       | **Priorité**  | **Sprint prévu** |
|----------|-------------------------------------------------------|---------------|------------------|
| US01     | Voir la liste des cryptomonnaies avec prix actuel     | Haute         | Sprint 1         |
| US02     | Rechercher une cryptomonnaie par nom ou symbole       | Moyenne       | Sprint 1         |
| US03     | Visualiser un graphique des variations de prix        | Haute         | Sprint 2         |
| US04     | Comparer graphiquement deux cryptomonnaies            | Moyenne       | Sprint 2         |
| US05     | Configurer une alerte sur le prix                     | Moyenne       | Sprint 3         |
| US06     | Voir et gérer mes alertes                             | Basse         | Sprint 3         |

---

## 3. Évolution du backlog  
Le backlog produit sera mis à jour à chaque sprint en fonction des retours utilisateurs et de l’avancement des développements.  

---

## 4. Références API  
Certaines user stories nécessitent l’utilisation des API suivantes :  
- [CoinGecko API](https://www.coingecko.com/en/api) pour les données sur les cryptomonnaies.  
- [CoinMarketCap API](https://coinmarketcap.com/api/) pour les graphiques et statistiques avancées.  

---

## 5. Notes  
- Les critères d’acceptation définissent quand une user story peut être considérée comme *Terminée*.  
- Les priorités sont définies selon l’impact utilisateur et la faisabilité technique.  
