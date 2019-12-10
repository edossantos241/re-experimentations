# Alfred - Majordome de Batman

## Modélisation sytème

### Use Cases

![alt text](https://github.com/edossantos241/re-experimentations/blob/master/img/UC.PNG)

Description :

Cas d'utilisations représentés :
    - Afficher la température
    - Contrôler la qualité de l'air : Mesurer la température,...
    - Mesurer la consommation électrique
    - Connaître la consommation d'eau
    - Connaître la production électrique
    - Connaître le rendement électrique

Les "Requirement" contiennent un attribut "text" une référence au document "exiengence.txt".
exemple : Requirement1
![alt text](https://github.com/edossantos241/re-experimentations/blob/master/img/requirement1.PNG) 



### Block Definition Diagrams

![alt text](https://github.com/edossantos241/re-experimentations/blob/master/img/BlockDefinitionDiagram.PNG)

Description:

Acteur : Batman

Bloc contexte : Alfred

Autres blocs* :
- Mesures
- Analyses
- Prévisions
- Fonctionnalités

*Ces blocs représentent les différentes catégories d'informations d'Alfred, on pourra nottament les représenter comme des menus d'Alfred.

### Internat Block Diagram

![alt text](https://github.com/edossantos241/re-experimentations/blob/master/img/InternalBlockDiagramAlfred.PNG)

Description : Ce diagramme représente le bloc "Alfred" et son contenu. On y retrouve les blocs qui le composent ainsi qu'un port d'alimentation électrique.



### Sequence Diagram

![alt text](https://github.com/edossantos241/re-experimentations/blob/master/img/SequenceDiagram.PNG)

Description : Ce diagramme représente les différentes interractions entre les acteurs du système. On y retrouve l'ensemble des exigences décritent dans le diagramme des cas d'utilisation.

### State Machine Diagram

![alt text](https://github.com/edossantos241/re-experimentations/blob/master/img/StateMachineDiagram.PNG)

Description : Avec ce diagramme, on a voulu représenter les différents états par lesquels le système (Alfred) passe lors d'un contrôle de qualité de l'air lancé par Batman. Le point d'entrée est la demande d'affichage de la qualité de l'air et le point de sortie est l'affichage de la qualité de l'air.