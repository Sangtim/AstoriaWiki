
Permet de créer des potions à partir d'ingrédients alchimiques et de collecter des ingrédients alchimiques sur les monstres et dans la nature.
- **Caractéristique** : Sagesse
- **Collecte** : Détermine le nombre de jet de collecte qui peut être effectué par l'alchimiste.

| Nombre de jet      | Type     | Taille               |
| ------------------ | -------- | -------------------- |
| 3                  | Nature   | -                    |
| 1 avec désavantage | Créature | Très petite à petite |
| 1                  | Créature | Moyenne              |
| 2                  | Créature | Grande               |
| 3                  | Créature | Très grande          |
| 4                  | Créature | Gigantesque          |
- **Récompense** : L'alchimiste peut additionner le/les résultat(s) de son/ses jets pour obtenir un score de collecte (SC). Il peut ensuite dépenser ces SC pour obtenir un certains nombres de matériaux d'alchimie.  
	- Exemple : Je fais 3 jets de collecte sur une créature très grande, j'obtiens au dés : 5, 10 et 18 pour un total de 33 SC. Je dépense ensuite ces SC pour obtenir une ressource légendaire (25 SC) et une ressource commune (2 SC) et peu commune (5 SC) pour un total de 32 SC dépensés.


| Coût en SC | Récompense                | Modificateur d'Alchimie |
| ---------- | ------------------------- | ----------------------- |
| 2 SC       | Une ressource commune     | -                       |
| 5 SC       | Une ressource peu commune | -                       |
| 10 SC      | Une ressources rare       | +1 MA                   |
| 15 SC      | Une ressource très rare   | +2 MA                   |
| 25 SC      | Une ressource légendaire  | +3 MA                   |
- **Concoction** : L'alchimiste peut créer la totalité des potions présents dans la catégorie Potions dans [Marchandises](Marchandises). Chaque niveau de rareté de potions (séparé dans le tableau par des =) nécessite l'utilisation d'une ressource de rareté équivalente. Des ressources de rareté supérieur peuvent être utilisés pour améliorer le rendement de la concoction. 

L'alchimie se découpe en plusieurs étapes, chacune permettant d'accumuler des Modificateur d'Alchimie qui améliore le résultat finale.

- **Etape 1** : Le choix des ressources
Une potion nécessite un nombre de ressources égales à son niveau de rareté. 

| Rareté      | Ingrédients |
| ----------- | ----------- |
| Commune     | 1           |
| Peu commune | 2           |
| Rare        | 3           |
| Très rare   | 4           |
| Légendaire  | 5           |
- **Etape 2** : La préparation des ingrédients alchimique
L'alchimiste choisit un style de préparation, définissant la difficulté du jet et son effet.

| Style                    | Jet                                       | DC  | Effet                          |
| ------------------------ | ----------------------------------------- | --- | ------------------------------ |
| Préparation traditionnel | Intelligence (Nature) ou Sagesse (Survie) | 10  | +1 MA si réussite, -1 si échec |
| Préparation de précision | Intelligence (Nature) ou Sagesse (Survie) | 13  | +2 MA si réussite, -1 si échec |
| Préparation de maître    | Sagesse (Médecine)                        | 15  | +3 MA si réussite, -1 si échec |
- **Etape 3** : le mélange des ingrédients
L'alchimiste choisit un style de mélange, définissant la difficulté du jet et son effet. Le mélange arcanique utilise aussi un niveau d'emplacement de niveau 2.

| Méthode           | Jet                   | DC  | Effet                          |
| ----------------- | --------------------- | --- | ------------------------------ |
| Mélange à froid   | Sagesse (Médecine)    | 10  | +1 MA si réussite, -1 si échec |
| Mélange à chaud   | Sagesse (Médecine)    | 13  | +2 MA si réussite, -1 si échec |
| Mélange arcanique | Intelligence (Arcane) | 16  | +3 MA si réussite, -1 si échec |
- **Etape 4** : L'infusion des ingrédients
L'alchimiste choisit un style d'infusion, définissant la difficulté du jet et son effet.

| Style                | Jet                   | Coût                            | DC  | Effet                          |
| -------------------- | --------------------- | ------------------------------- | --- | ------------------------------ |
| Infusion simple      | Intelligence (Arcana) | Emplacement de sort de niveau 1 | 12  | +1 MA si réussite, -1 si échec |
| Infusion élémentaire | Intelligence (Arcana) | Emplacement de sort de niveau 2 | 15  | +2 MA si réussite, -1 si échec |
| Infusion légendaire  | Intelligence (Arcana) | Emplacement de sort de niveau 3 | 20  | +3 MA si réussite, -1 si échec |
- **Etape 5** : Les événements de l'alchimie
L'alchimie est dangereuse et imprévisible. A chaque étape, un dé 10 sera lancé, permettant de déterminer ce qu'il se passe.

| Résultat du dé | Conséquences                                                 | Effet                                                     |
| -------------- | ------------------------------------------------------------ | --------------------------------------------------------- |
| 1              | Les ingrédients perdent de leurs effets                      | -1 MA                                                     |
| 2              | Un ingrédient est de qualité supérieur                       | +2 MA                                                     |
| 3              | Les ingrédients provoquent une réaction en chaîne et explose | 1d6 de dégâts de force par niveau de rareté de la recette |
| 4              | Les forces élémentaires favorise l'infusion                  | +2 MA                                                     |
| 5              | L'appareil de mélange craque pendant l'infusion              | -1 MA                                                     |
| 6              | Inspiration divine                                           | Permet de relancer un dé si échoué (+1 MA sinon)          |
| 7              | Un esprit de la nature se manifeste                          | +3 MA                                                     |
| 8              | Un ingrédient se révèlent pourri                             | -1 MA                                                     |
| 9              | Rien ne se passe                                             | Aucun effet                                               |
| 10             | Le Dieu de la nature vous observe                            | +2 MA                                                     |
- **Etape 6** : La mise en bouteille
La concoction est prête est doit être mise en bouteille. L'alchimiste lance un dé 20 auquel il ajoute le modificateur d'alchimie (MA).

| Résultat | Effet                                           |
| -------- | ----------------------------------------------- |
| 1-5      | La potion est raté, les ressources sont perdues |
| 6-10     | Une potion commune est réussi                   |
| 11-15    | Une potion peu commune est réussi               |
| 16-18    | Une potion rare est réussi                      |
| 19-24    | Une potion très rare est réussi                 |
| 25-27    | Une potion légendaire est réussi                |
| 28+      | La potion est sublimée                          |
Chaque fourchette de résultat supérieur à celui nécessaire permet de créer une potion supplémentaire avec la concoction.
_Exemple_ : Je cherche à faire une potion de soin majeure qui est donc peu commune. Je dois faire pour réussir un score d'alchimie entre 11 et 15. Je fais un score de 20 au total ce qui me permet de produire non pas une seule potion mais 3 car deux fourchettes au dessus de l'objectif.