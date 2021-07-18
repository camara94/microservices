# Les Microservices
Le principe de l'architecture microservice est de découper un grand problème en un ensemble de petits problèmes, de les résoudre et bien sûr le decoupage se fait avec un niveau de granilarité beaucoup plus faible avec les besoins métiers.
![decoupage](images/decoupage1.png)

## Défis
* faire Communiquer Les Applications Entre elles
  ![def1](images/defi1.png)
* mettre en place un gate way qui permet aux applications clients de ne pas connaître les Adresses des applications qui constituent application microservice. Son rôle est l'acheminement des requests des clients vers nos différentes applications.
  
