# AREA

AREA est une application web qui permet aux utilisateurs de créer des automatisations entre différents services tels que Discord, Spotify, Thread, Osu, Riot et Gmail. Avec une interface intuitive en ReactJS pour le web et React Native pour les applications mobiles, AREA permet de gérer facilement des tâches d'automatisation selon des triggers définis par l'utilisateur.

## Fonctionnalités

### Services Intégrés
- Discord : Suivez les messages et les activités des serveurs.
- Spotify : Réagissez aux likes et à l'activité de votre musique.
- Thread : Connectez plusieurs comptes pour gérer vos messages.
- Osu : Suivez vos performances et vos progrès.
- Riot : Intégrez vos jeux et suivez vos statistiques.
- Gmail : Gérez plusieurs comptes et automatisez vos réponses.

### Triggers Personnalisés
- Nombre de followers sur les réseaux sociaux.
- Messages reçus.
- Likes sur Spotify.

### Gestion des Tâches
- Interface pour visualiser toutes les tâches créées.
- Création de nouvelles tâches avec des blocs personnalisables.
- Possibilité d'ajouter des arguments à partir d'anciennes réactions.

### Gestion de Profil
- Page de profil utilisateur.
- Connexion sécurisée à vos comptes de services tiers.

## Documentation

Pour consulter les routes disponibles et la documentation API, rendez-vous sur :

[Documentation des routes](http://localhost:8080/swagger-ui/index.html#/)

**Une fois le serveur lancé** (voir [page commandes importantes](commandes.md))

Pour plus de détails sur l'utilisation et la configuration de l'application, veuillez consulter notre documentation sur Notion.

## Installation
#### Prérequis

Assurez-vous d'avoir Docker, Docker Compose installés sur votre machine ainsi
que d'avoir aux alentours de 10gb d'espace de stockage disponible.

Lancer l'application

Pour démarrer l'application, exécutez la commande suivante dans le terminal :

```bash
$ docker-compose up --build
```

Cette commande construira et démarrera les conteneurs nécessaires pour le backend et le frontend.

## Structure du projet

Le projet est divisé en deux parties principales :

- Backend : Développé avec Java et Spring Boot avec Hibernate pour PostgreSQL.
- Frontend : Développé avec ReactJS + nextJS pour la version web et React Native pour la version mobile.
- BDD : La base de donnée est gérée avec PostgreSQL.

Chaque service et fonctionnalité est conçu pour être modulaire, facilitant ainsi les mises à jour et les extensions futures.

## Tests

Le projet contient des tests unitaires sur Postman.

Demandez à un admin pour avoir accès aux tests :
[Tests unitaires](https://partime-7226.postman.co/workspace/My-Workspace~5aad035e-4587-4c0a-87b0-f2d7136cbc12/overview)

## Contribuer

Les contributions sont les bienvenues ! Si vous souhaitez participer au développement de AREA, veuillez suivre ces étapes :

- Fork ce repository.
- Créez une branche pour votre fonctionnalité (git checkout -b feature/YourFeature).
- Commitez vos modifications (git commit -m 'Add some feature').
- Poussez la branche (git push origin feature/YourFeature).
- Ouvrez une Pull Request.

## Acknowledgements

Un grand merci aux communautés et aux outils open-source qui ont rendu ce projet possible.
Nous remercions aussi Epitech pour nous avoir donné l'idée de ce projet.

## Our team!

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Joan-R">
        <img src="https://github.com/Joan-R.png?size=85" width="85" alt="Joan Ruiz"><br>
        <sub>Joan Ruiz</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Priax">
        <img src="https://github.com/Priax.png?size=85" width="85" alt="Vincent Montero Fontaine"><br>
        <sub>Vincent Montero Fontaine</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/NattanCochet">
        <img src="https://github.com/NattanCochet.png?size=85" width="85" alt="Nattan Cochet"><br>
        <sub>Nattan Cochet</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/tomclgr">
        <img src="https://github.com/tomclgr.png?size=85" width="85" alt="Tom Calogheris"><br>
        <sub>Tom Calogheris</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/kenz0es">
        <img src="https://github.com/kenz0es.png?size=85" width="85" alt="Kenzo Escuret"><br>
        <sub>Kenzo Escuret</sub>
      </a>
    </td>
  </tr>
</table>


