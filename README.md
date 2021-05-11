# Items_3D_NG

La description des fichiers serra ici:



#1 - animation_controllers
#2- animations
#3- models 
#4- attachables
#5- textures
#6- render_controllers


#1: Query pour def les animations, empecher que certaines se fassent au mauvais moment.
#2: Déroulement de l'animation, /!\ ET AUSSI EMPLACEMENT DANS LA MAIN /!\
#3: Models de l'item à mettre en 3D
#4: Fichier permettant de relier chaque fichiers entre eux, ainsi dans ce fichier nous trouvons la texture, le model et les animations disponibles dans le pack.
#5: Ici, 2 choses importantes: La textures dans la hotbar, et la texture à appliquer sur le model
#6: Fichier Optionnel permettant de pouvoir appliquer un effet d'enchantement sur un item 3D. Sans, la texture "animé" d'un enchant ne serras pas présente.


Fichiers obligatoire à chaques nouvel item: 

- attachables/votre_item.json
- models/votre_item.geo.json
- textures/hotbar/votre_item.png
- textures/entity/votre_texture.geo.png
