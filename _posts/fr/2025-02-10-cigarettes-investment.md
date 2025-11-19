---
layout: post
title: "Cigarettes et investissement : l’impact financier réel du tabac"
lang: fr
categories: [fr, blog]
tags: [finance, vie, données]
---

On sait tous que fumer est une très mauvaise idée pour la santé.  
Une étude du *British Medical Journal* estime qu’**une cigarette réduit votre espérance de vie d’environ 11 minutes**, et qu’en moyenne, les fumeurs vivent **6,5 ans de moins** que les non-fumeurs.

Mais on parle beaucoup moins du **coût financier** — qui est lui aussi énorme.  
Dans cet article, je m’intéresse non seulement à **l’argent dépensé**, mais aussi à **ce qu’un non-fumeur aurait gagné** en investissant la même somme dans un simple indice boursier.

Spoiler : l’écart après 30 ans est gigantesque.

---

## Combien fume un fumeur « moyen » ?

Prenons un fumeur français moyen. Selon l’[OFDT](https://www.ofdt.fr/statistiques-et-infographie/series-statistiques/tabac-evolution-de-lusage-occasionnel-ou-regulier-parmi-les-18-75-ans/), en 2018 un fumeur consommait en moyenne :

- **13 cigarettes par jour**

Ce chiffre varie selon le sexe et l’âge, et est en baisse.  
Les calculs qui suivent sont donc plutôt optimistes.

---

## Évolution du prix du paquet en France

Le prix du tabac a explosé au cours des 30 dernières années, notamment en raison de la fiscalité.

J’ai utilisé les prix historiques disponibles ici :  
<https://github.com/Aunsiels/sp500_simulator/blob/main/data/cigarettes.json>

Cela permet de reconstituer le coût annuel réel du tabac sur trois décennies.

---

## Stratégie d’investissement : simple et réaliste

Imaginons qu’au lieu d’acheter des cigarettes, une personne investisse la même somme dans le **S&P 500**.

À chaque fois qu’un fumeur achète un paquet, le non-fumeur investit l’équivalent.

C’est évidemment une approximation :

- Le prix d’un paquet n’achète pas une action entière → mais le DCA existe  
- On ignore les taxes et les frais  
- On considère la performance historique du S&P 500  
- Ce n’est pas un modèle financier sophistiqué

Mais c’est largement suffisant pour faire une comparaison honnête.

---

## Résultats : fumer vs. investir

Ci-dessous, le résultat de la simulation :  
- **Rouge** = argent dépensé dans les cigarettes  
- **Bleu** = argent investi dans le S&P 500  

<iframe src="{{ '/assets/html/cigarettes.html' | relative_url }}"
        width="100%" height="525" style="border:none;"></iframe>

### Après 30 ans :

**Le fumeur :**  
- Dépense **~40 000 €**  
- ≈ *2,5× le SMIC annuel*  
- ≈ *1,8× le salaire médian*  

**Le non-fumeur :**  
- Accumule **~105 000 €**  
- ≈ *6,5× le SMIC annuel*  
- ≈ *4,7× le salaire médian*

Et cela malgré **quatre récessions majeures** :
- Éclatement de la bulle internet  
- Crise des subprimes  
- COVID-19  
- Guerre en Ukraine  

L’effet de l’intérêt composé est redoutable.

---

## Le cas d’un « gros fumeur »

Pour une consommation d’un paquet par jour (20 cigarettes) :

- Investissement équivalent après 30 ans : **~163 000 €**  
- ≈ *10× le SMIC annuel*

---

## Une conclusion un peu violente

Fumer vous fait :

- **vivre 6,5 ans de moins**,  
- **travailler 6,5 ans de plus**,  
- perdre **des dizaines de milliers d’euros**,  
- et passer à côté de **plus de 100 000 € d’investissement potentiel**.

Cela fait **13 ans perdus** — moins vécus, plus travaillés.

Si vous le pouvez, remplacez les dépenses de tabac par un investissement régulier.  
Les intérêts composés sont lents… puis soudain très rapides.

Le code complet de la simulation est ici :  
<https://github.com/Aunsiels/sp500_simulator>

