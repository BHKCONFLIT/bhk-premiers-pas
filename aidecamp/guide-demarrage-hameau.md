# Guide de démarrage hameau

Ce guide prend le relais du [guide de démarrage camp](guide-demarrage-camp.md) au moment où ton
camp bascule vers le hameau : tu gères désormais une vraie population (arrivées, métiers,
nourriture, maladies) plutôt que les 5 travailleurs génériques du prologue. C'est le système le
plus mal compris du jeu aujourd'hui, en particulier la nourriture, donc lis-le en entier avant
de foncer.

## 1. La population : maisons, arrivées, naissances

Ta capacité d'accueil dépend uniquement des maisons construites : **3 places par maison en
bois**, **5 places par maison en pierre**. Tant qu'il reste de la place libre, de nouveaux
habitants arrivent tout seuls avec le temps (et des naissances peuvent s'ajouter, au même
rythme, dès qu'il reste de la place). Construis des maisons dès que tu peux si tu veux monter en
population.

Un nouvel habitant arrive **sans métier assigné**. Va sur la page TRAVAILLEURS pour lui en
donner un — attention, **un métier assigné est définitif**, il ne peut plus être changé ensuite
pour cet habitant.

## 2. Les métiers

| Métier | Rôle |
|---|---|
| **Bûcheron** | Coupe du bois (construction, tas de graines d'arbre) |
| **Fermier** | Défriche/sème/récolte sur 1 à 4 fermes en liste ordonnée |
| **Mineur** | Extrait la pierre |
| **Chasseur** | Chasse la viande sur les zones découvertes |
| **Éboueur** | Nettoie les déchets produits par la population (voir §4) |
| **Scientifique** | Travaille au laboratoire (craft) |
| **Commerçant** | Débloque l'upkeep nourriture ; voir §3, c'est le métier le plus mal compris du jeu |
| **Réserviste** | Filet de secours : remplace automatiquement, à rendement réduit, n'importe quel titulaire malade du camp le temps de sa guérison |

## 3. Nourrir sa population : le piège n°1 du jeu

**Avoir des cultures récoltées dans le stock de ton pays ne nourrit PERSONNE tant que 2
conditions ne sont pas réunies :**

1. **Une épicerie construite et terminée.** Le stock brut du pays (ce que tu récoltes) doit
   être **déposé dans l'épicerie** (page INVENTAIRE, bouton dépôt ou "REMPLIR" pour un
   ravitaillement automatique jusqu'à un seuil que tu choisis). Seul le stock **dans**
   l'épicerie compte pour nourrir les gens, jamais le stock brut du pays.
2. **Au moins un habitant vivant avec le métier Commerçant.** Sans lui, l'upkeep nourriture est
   entièrement coupé, même avec une épicerie pleine à craquer. C'est l'erreur la plus fréquente
   en sortie de prologue : le joueur construit son épicerie, la remplit, et personne ne mange
   quand même faute de commerçant assigné.

Une fois ces deux conditions réunies, chaque habitant est nourri **une fois par jour réel** :
**3 unités de qualité abîmée OU 1 unité de qualité excellente**, peu importe la culture
(blé/maïs/tomate/tournesol interchangeables). À défaut de légumes, le stock viande puis
œufs/lait pris dans le même ordre de priorité. Une épicerie sert au maximum **200 habitants** ;
au-delà, construis-en une deuxième.

Depuis peu, une alerte automatique apparaît directement sur la page de ton pays dès que ton
épicerie est terminée mais qu'aucun commerçant n'est assigné — plus besoin de deviner pourquoi
personne ne mange.

Le commerçant a aussi un revenu passif (jusqu'à 3 commerçants payés par camp), indépendant du
succès ou non de l'upkeep nourriture ce jour-là.

## 4. Déchets et éboueur

Chaque habitant produit des déchets en continu ; un éboueur assigné en nettoie une partie. Si
personne n'est éboueur, les déchets s'accumulent sans plafond et augmentent le risque de
dysenterie (voir §5). Un seul éboueur suffit à compenser une petite population, mais il en faut
davantage à mesure qu'elle grandit.

## 5. Faim et maladies : ce qui ralentit ou arrête un travailleur

Deux mécanismes distincts affectent la production d'un habitant, cumulables :

**La faim, par paliers progressifs** (basée sur les jours consécutifs sans repas) :
- 1-2 jours sans manger : production à **75%**
- 3-4 jours sans manger : production à **45%**
- **5 jours ou plus : arrêt complet**, la tâche en cours se fige exactement où elle en est et
  reprend pile à ce point une fois l'habitant de nouveau nourri
- Risque de mort qui grimpe progressivement à partir de 7 jours consécutifs sans manger,
  jusqu'à une certitude absolue à 14 jours

**La maladie, arrêt immédiat sans palier** dès l'apparition, jusqu'à guérison :
- **Malnutrition** : risque quotidien dès 3 jours sans manger ; guérit dès que l'habitant
  remange normalement
- **Dysenterie** : risque quotidien lié au niveau de déchets du camp (voir §4) ; guérison à
  durée fixe une fois déclarée
- **Épuisement** : risque quotidien lié à des horaires de travail trop chargés ; guérison à
  durée fixe une fois déclaré

Un habitant malade ou gelé par la faim est automatiquement remplacé par un **réserviste**
disponible du camp (s'il y en a un), à rendement réduit, le temps de sa convalescence — voir
§2. Sans réserviste disponible, la production correspondante s'arrête simplement jusqu'à
guérison ou réassignation.

## 6. Alertes automatiques à surveiller

La page de ton pays affiche des alertes en temps réel pour les situations qui demandent une
action de ta part : réserve de stock sous un seuil que tu as fixé, plus aucun habitant vivant
dans un métier de production, ou épicerie prête sans commerçant (voir §3). Une alerte reste
affichée tant que tu ne l'as pas fermée ou mise en pause 48h.
