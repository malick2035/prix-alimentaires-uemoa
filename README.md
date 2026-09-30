# Prix alimentaires dans l'UEMOA : quand et où acheter ?

Analyse des prix alimentaires au **Bénin**, au **Togo**, au **Niger** et au **Sénégal** (2019-2026), à partir des données officielles du **Programme alimentaire mondial (PAM)**, pour aider commerçants, entreprises et décideurs à mieux planifier leurs achats et à anticiper les hausses de prix.

## Pourquoi ce projet ?

Les prix alimentaires pèsent sur tout le monde : l'importateur qui remplit ses entrepôts, le grossiste, le supermarché, et le ménage qui achète son huile ou ses tomates. Pourtant, les décisions d'achat se prennent souvent sans données. Ce projet transforme **plus de 200 000 relevés de prix** en réponses concrètes.

## Les 5 questions traitées

1. **Quand acheter ?** Les mois où chaque produit est le moins cher.
2. **Où acheter ?** Les écarts de prix entre départements et entre pays.
3. **Quels produits sont risqués ?** La fréquence des chocs de prix.
4. **Produits importés ou locaux ?** Lesquels sont les plus instables.
5. **À quoi s'attendre ?** La tendance des prochains mois.

## Résultats clés

- **Bénin, 2019-2025** : hausse des prix de **+33 %** (riz importé) à près de **+70 %** (huile d'arachide, gari, tomates).
- **Acheter au bon mois** fait économiser jusqu'à **53 %** sur les tomates (septembre), **41 %** sur les oignons (avril) et **21 %** sur le maïs (novembre).
- **Le lieu compte** : un même produit peut coûter **plus de 2 fois plus cher** selon le département (gari : 187 FCFA/kg dans le Couffo, 460 dans l'Alibori).
- **Le risque vient des produits frais locaux** : tomates et oignons subissent un choc de prix plus de **4 mois sur 10**, contre **1 mois sur 100** pour le riz importé.
- **Chaque pays a son avantage** : le maïs est le moins cher au Bénin (155 FCFA/kg), le mil et le sorgho au Niger, le riz importé au Sénégal (342 FCFA/kg, contre 542 au Bénin).
- **Le prix du maïs a doublé au Togo** entre 2019 et 2025 (+101 %).

## Méthode

| Étape | Ce qui a été fait |
|---|---|
| Collecte | Données du PAM (plateforme HDX des Nations unies) pour 4 pays |
| Diagnostic | Vérification des périodes, des valeurs manquantes et des types de prix |
| Préparation | Harmonisation des noms de produits entre pays, prix de détail 2019-2026 |
| Analyse | Indice saisonnier (neutralise l'inflation), médianes par département et par pays, fréquence des chocs de prix (> 10 % en un mois) |
| Visualisation | Graphiques Python pensés pour les décideurs, puis tableau de bord Power BI |

## Contenu du dépôt

| Fichier | Description |
|---|---|
| `Prix_Alimentaires_UEMOA.ipynb` | Notebook Google Colab : préparation, analyses, graphiques et synthèse |
| `Tableau_de_bord_Prix_Alimentaires_UEMOA.pbix` | Tableau de bord Power BI interactif |
| `Prix_Alimentaires_UEMOA_Tableau_de_bord_V2.pdf` | Version PDF du tableau de bord, lisible sans Power BI |

## À qui cette analyse est utile ?

- **Importateurs, grossistes, supermarchés** : planifier les achats, choisir les zones d'approvisionnement, protéger les marges.
- **Pouvoirs publics et ONG de sécurité alimentaire** : repérer les produits et les zones à surveiller, anticiper les périodes de soudure.
- **Ménages** : savoir quand les produits de base sont les moins chers.

## Limites

- Prix de **détail** uniquement (les prix de gros sont trop rares dans la source).
- Les produits suivis diffèrent selon les pays : la comparaison régionale porte sur les **céréales** (maïs, mil, sorgho, riz).
- Le riz importé n'est plus suivi au Togo depuis 2022 ; le riz local est peu suivi au Niger.
- La tendance des prochains mois est une **projection saisonnière**, pas une certitude.

## Prochaines étapes

- Vérifier la tendance prévue dès la publication des nouveaux prix.
- Construire une **prévision 2026-2027** avec plusieurs méthodes, dont le Machine Learning.
- Étendre l'analyse à d'autres pays de l'UEMOA.

## Source

Programme alimentaire mondial (PAM), base de données des prix alimentaires, via HDX (data.humdata.org).

## Auteur

**Malick OKASSE**, consultant Data Analytics & IA, Natitingou (Bénin)
Contact : data.malick9@gmail.com

*Vous avez des données (ventes, stocks, prix, terrain) et besoin d'une analyse ou d'un tableau de bord pour mieux décider ? Contactez-moi.*
