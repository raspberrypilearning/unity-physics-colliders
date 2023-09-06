Un collider est une forme utilisée pour détecter la collision ou l'intersection d'un GameObject avec un autre GameObject. Il est beaucoup plus rapide pour un ordinateur de vérifier les collisions avec une forme de collision simple qu'avec la forme complexe d'un GameObject.

Un Box Collider a la forme d'un simple cube qui peut être dimensionné et positionné pour empêcher les GameObjects d'occuper le même espace.

Pour ajouter un Box Collider, va sur **Add Component** dans la fenêtre Inspector de ton GameObject et sélectionne **Box Collider**.

![Le menu déroulant Add Component avec « box » tapé dans la barre de recherche et « Box Collider » mis en surbrillance.](images/component-box.png)

Modifie les valeurs des propriétés « Center » et « Size » jusqu'à ce que tu sois satisfait qu'elles soient au-dessus du sol et qu'elles recouvrent l'ensemble de ton GameObject.

![Le composant Box Collider avec les valeurs Center y = 0.5, Size x = 0.7, y = 1, et z = 0.7.](images/cone-properties.png)

![Le modèle Roadworks Cone dans la vue Scene avec les lignes vertes du Box Collider en forme de cube s'adaptant autour du cône.](images/colider-cone.png)

**Astuce :** les Box Colliders devront être ajoutés à tous les GameObjects dont tu veux éviter qu'ils n'occupent le même espace.
