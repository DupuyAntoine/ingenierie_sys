# TP Ingénierie Système Partie 2 (Diagrammes)

**But :** Réaliser différents diagrammes à partir des spécifications créées par le groupe homologue d'outil de modélisation (Excel).

**Travail réalisé par :** Thomas COLETTE, Antoine DUPUY et Corentin GRANDCHAMPS

## Diagramme d'Exigences 

Le diagramme d'exigences permet de mettre en forme les exigences explicites, et implicites nécessaires à la modélisation de la solution. Dans le cas du Majordome Alfred, il est impératif d'exiger une interface homme machine (boitier par exemple) qui permet à l'utilisateur de faire de la récupération de données depuis des capteurs et de les afficher. Les exigences sont donc ici établies et détaillées.

![Requirement](https://github.com/DupuyAntoine/ingenierie_sys/blob/master/alfred-majordome/Requirement.PNG)

## Diagramme de Cas d'Utilisation

Le diagramme de cas d'utilisation permet de modéliser les différentes les différentes intéractions entre les acteurs extérieurs et le système ainsi que les intéractions internes au système en lui-même. Dans notre cas, un utilisateur peut utiliser le système afin de lire différentes informations calculées en interne et peut aussi interagir sur le système de sécurité de la maison comprenant les portes et les fenêtres.

![UseCase](https://github.com/DupuyAntoine/ingenierie_sys/blob/master/alfred-majordome/UseCase.PNG)

## Diagramme de Définition de Bloc

Le diagramme de bloc permet de discriminer les différents blocs du système. Chaque bloc représentant un élément du système comprenant ses différents attributs et fonctions. Dans notre cas, il nous a ainsi été possible de déterminer l'utilité de chaque composant ainsi que leurs connexions entre eux. Il permet ainsi d'avoir une vision globale du système.

![Block](https://github.com/DupuyAntoine/ingenierie_sys/blob/master/alfred-majordome/Block.png)

## Diagramme de Blocs Internes

Le diagramme de blocs internes permet de se focaliser sur un bloc (du diagramme précédent) du système. Il permet de modéliser les différents composants de ce bloc ainsi que leurs connexions internes et externes avec les autres éléments du système par un système de ports. Dans notre cas, nous avons choisi de modéliser le bloc "Page" représentant une instance d'une page de l'interface du système.

![InternalBlock](https://github.com/DupuyAntoine/ingenierie_sys/blob/block-diagram/alfred-majordome/InternalBlock.PNG)

## Diagramme d'Etat

Le diagramme d'état permet de modéliser les différents états d'un système et les actions permettant le changement de ces états. Dans notre cas, nous avons choisi de modéliser le diagramme d'état du système de sécurité de l'entrée de la maison avec ses interactions avec les portes.

![StateMachine](https://github.com/DupuyAntoine/ingenierie_sys/blob/block-diagram/alfred-majordome/StateMachine.PNG)

## Conclusion

L'utilisation d'Excel pour la modélisation des exigences arrive très vite à ses limites. En effet, même s'il est plutôt simple d'avoir une vue globale du système assez rapidement, nous avons vite été bloqué lorsque nous devions rentrer plus en détails dans les interactions internes et la compréhension plus poussée du système.


------------------------------------------------------------------------
# Tp ingénierie système

Voici le lien vers un google sheet qui recense les exigences du tp :
[https://docs.google.com/spreadsheets/d/1ZBGcZx1jvPsQW67xGV_eFOYSZ4B3JeYL6ARMWkNj6jA/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1ZBGcZx1jvPsQW67xGV_eFOYSZ4B3JeYL6ARMWkNj6jA/edit?usp=sharing)
