# Les Microservices
Le principe de l'architecture microservice est de découper un grand problème en un ensemble de petits problèmes, de les résoudre et bien sûr le decoupage se fait avec un niveau de granilarité beaucoup plus faible avec les besoins métiers.
![decoupage](images/decoupage1.png)

## Défis
* faire Communiquer Les Applications Entre elles
  ![def1](images/defi1.png)
* mettre en place un gate way qui permet aux applications clients de ne pas connaître les Adresses des applications qui constituent application microservice. Son rôle est l'acheminement des requests des clients vers nos différentes applications.
![getway](images/getway.png)
* Discovery Service qui va se charger d'enregistrer tous les microservices, c'est à dire chaque microservice qui est lancé il va enrégistrer
   1. son nom
   2. son adresse IP
   3. son numéro de port
   ![discovery](images/discovery.png)