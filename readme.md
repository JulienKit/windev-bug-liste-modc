# Bug combos liste dans les modèles de champ

Lorsqu'une combo liste est créé dans un modèle de champ, si sa source de données (FichierParcouru) est une requête intégrée, celle-ci ne sera pas trouvé dans les autres fenêtres (une erreur IHM apparaît dans la console) et sera vide dans la(les) fenêtre(s). 

Les fonctions de sélection n'ont également aucun effet. Un ```.SelectPlus()``` sélectionnera la ligne en GO sur le modèle de champ mais dans la fenêtre qui possède le modèle, cela ne fonctionnera pas. Même en passant via la fenêtre : ```CMOD.MaComboListe.SelectPlus(1)```. 
