Permet de créer des petits plats à partir d'ingrédients achetés ou récolter.
- **Caractéristiques** : Intelligence(Nature) et Sagesse(Survie)
- **Collecte** : Détermine le nombre de jet de collecte qui peut être effectué par le cuisinier

| Nombre de jet      | Type     | Taille               |
| ------------------ | -------- | -------------------- |
| 3                  | Nature   | -                    |
| 1 avec désavantage | Créature | Très petite à petite |
| 1                  | Créature | Moyenne              |
| 2                  | Créature | Grande               |
| 3                  | Créature | Très grande          |
| 4                  | Créature | Gigantesque          |
- **Récompense** : Le cuisinier peut additionner le/les résultat(s) de son/ses jets pour obtenir un score de collecte (SC). Il peut ensuite dépenser ces SC pour obtenir un certains nombres de matériaux de cuisine.  
	- Exemple : Je fais 3 jets de collecte sur une créature très grande, j'obtiens au dés : 5, 10 et 18 pour un total de 33 SC. Je dépense ensuite ces SC pour obtenir une ressource légendaire (25 SC) et une ressource commune (2 SC) et peu commune (5 SC) pour un total de 32 SC dépensés.


| Coût en SC | Récompense                | Modificateur de cuisine |
| ---------- | ------------------------- | ----------------------- |
| 2 SC       | Une ressource commune     | -                       |
| 5 SC       | Une ressource peu commune | -                       |
| 10 SC      | Une ressources rare       | +1 MC                   |
| 15 SC      | Une ressource très rare   | +2 MC                   |
| 25 SC      | Une ressource légendaire  | +3 MC                   |
- **Marinade** : Le cuisinier peut produire tout les plats qu'il imagine. Les bonus apportés par ses plats sont dépendants des ingrédients utilisés et du résultat finale de son  plat. 

La cuisine se découpe en plusieurs étapes, chacune permettant d'accumuler des Modificateur de Cuisine qui améliore le résultat finale.

- **Etape 1** : Le choix des ressources
Un plat donnera un nombre de portions en fonction de la rareté de la resources utilisés (une portion donnera un bonus à un aventurier pour une journée complète).

| Rareté      | Nombre de portions | Coût des Ingrédients |
| ----------- | ------------------ | -------------------- |
| Commune     | 1                  | 50 po                |
| Peu commune | 4                  | 200 po               |
| Rare        | 8                  | 2 000 po             |
| Très rare   | 12                 | 20 000 po            |
| Légendaire  | 15                 | 100 000 po           |
- **Etape 2** : La préparation des ingrédients
Le cuisinier choisit un style de préparation, définissant la difficulté du jet et son effet.

| Style                    | Jet                                      | DC  | Effet                          |
| ------------------------ | ---------------------------------------- | --- | ------------------------------ |
| Préparation traditionnel | Dextérité (Outils de cuisine)            | 10  | +1 MC si réussite, -1 si échec |
| Préparation de précision | Dextérité (Outils de cuisine)            | 13  | +2 MC si réussite, -1 si échec |
| Préparation de maître    | Sagesse (Survie) ou Intelligence(Nature) | 15  | +3 MC si réussite, -1 si échec |
- **Etape 3** : L'assaisonnement
Le cuisinier choisit un style d'assaisonnement, définissant la difficulté du jet et son effet. L'assaisonnement arcanique utilise aussi un niveau d'emplacement de niveau 2.

| Méthode                  | Jet                           | DC  | Effet                          |
| ------------------------ | ----------------------------- | --- | ------------------------------ |
| Assaisonnement herbeux   | Dextérité (Outils de cuisine) | 10  | +1 MC si réussite, -1 si échec |
| Assaisonnement d'épices  | Dextérité (Outils de cuisine) | 13  | +2 MC si réussite, -1 si échec |
| Assaisonnement arcanique | Intelligence (Arcane)         | 16  | +3 MC si réussite, -1 si échec |
- **Etape 4** : La cuisson des ingrédients
Le cuisinier choisit un style de cuisson, définissant la difficulté du jet et son effet.

| Style               | Jet                   | Coût                            | DC  | Effet                          |
| ------------------- | --------------------- | ------------------------------- | --- | ------------------------------ |
| Cuisson simple      | Intelligence (Arcana) | Emplacement de sort de niveau 1 | 12  | +1 MC si réussite, -1 si échec |
| Cuisson élémentaire | Intelligence (Arcana) | Emplacement de sort de niveau 2 | 15  | +2 MC si réussite, -1 si échec |
| Cuisson légendaire  | Intelligence (Arcana) | Emplacement de sort de niveau 3 | 20  | +3 MC si réussite, -1 si échec |
- **Etape 5** : Les événements de la cuisine
La cuisine peut révélé des surprises. A chaque étape, un dé 10 sera lancé, permettant de déterminer ce qu'il se passe.

| Résultat du dé | Conséquences                            | Effet                                            |
| -------------- | --------------------------------------- | ------------------------------------------------ |
| 1              | Les ingrédients perdent de leurs effets | -1 MC                                            |
| 2              | Un ingrédient est de qualité supérieur  | +2 MC                                            |
| 3              | La cuisson fait exploser de l'huile     | 1d6 de dégâts de feu                             |
| 4              | Les épices s'infusent dans le plat      | +2 MC                                            |
| 5              | Le plat craque pendant la cuisson       | -1 MC                                            |
| 6              | Inspiration divine                      | Permet de relancer un dé si échoué (+1 MC sinon) |
| 7              | Un esprit de la nature se manifeste     | +3 MC                                            |
| 8              | Un ingrédient se révèlent pourri        | -1 MC                                            |
| 9              | Rien ne se passe                        | Aucun effet                                      |
| 10             | Le Dieu de la nature vous observe       | +2 MC                                            |
- **Etape 6** : La mise en assiette
Le plat est prêt est doit être mise en assiette pour être dégusté. L'alchimiste lance un dé 20 auquel il ajoute le modificateur de cuisine (MC).

| Résultat | Effet                                                                                                          | Rareté nécessaire |
| -------- | -------------------------------------------------------------------------------------------------------------- | ----------------- |
| 1-5      | Le plat est cramé, -1 à tout les jets de ceux mangeant leur portion                                            | -                 |
| 6-10     | Le plat est réussi                                                                                             | -                 |
| 11-15    | Le plat est bon, octroyant 5 PV temporaire                                                                     | -                 |
| 16-18    | Le plat est très bon, octroyant 10 PV temporaire                                                               | -                 |
| 19-24    | Le plat est délicieux, octroyant 15 PV temporaire et avantage sur un jet au choix avant le prochain long repos | Rare +            |
| 25-27    | Le plat est magique, octroyant 20 PV temporaire et avantage sur un type de jet jusqu'au prochain long repos    | Très rare +       |
| 28+      | Le plat est divin, octroyant 25 PV temporaire et avantage à tous les jets jusqu'au prochain long repos         | Légendaire        |
