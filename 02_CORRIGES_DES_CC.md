# CORRIGÉS DÉTAILLÉS DES CONTRÔLES CONTINUS 2025-2026

> **Mode d'emploi.** Ne lis pas ce fichier tout de suite. Fais d'abord chaque CC **en 2 heures chrono, sans notes**. Puis compare. C'est le seul moyen de savoir où tu en es réellement.
>
> Chaque corrigé indique **la méthode**, **le calcul**, **le piège** et **ce que le correcteur attend**.

---

# CC1 2025-2026

## PARTIE I — Équilibres financiers, ETE, ESOG

### ▸ Lecture préalable de l'énoncé (le réflexe qui décide de tout)

Avant tout calcul, trois observations à faire sur le compte de résultat :

**① Le résultat est du côté PRODUITS.**
```
Produits : … Résultat de l'exercice (perte) 2 500
```
→ **RNC = − 2 500** (une PERTE). Si tu prends +2 500, toute ta CAF est fausse.

**② Décodage des sigles du prof.**
- **VCIICFC** = *valeur comptable des immobilisations incorporelles, corporelles, financières cédées* = **VCEAC** = 500 (charges)
- **PCIICF** = le produit de cession correspondant = **PCEA** = 300 (produits)

**③ Les trois variations de stocks et leurs signes.**
| Poste | Montant | Formule | Sens du stock | Effet BFRE |
|---|---|---|---|---|
| Variation stocks marchandises (charges) | **+1 500** | SI − SF > 0 | stock **↓** | **− 1 500** |
| Variation stocks MP (charges) | **−3 000** | SI − SF < 0 | stock **↑** | **+ 3 000** |
| Production stockée (produits) | **−4 500** | SF − SI < 0 | stock **↓** | **− 4 500** |

---

### Question 1 — La CAF par les deux méthodes

#### ▪ Méthode ADDITIVE

```
  Résultat net comptable (PERTE)              − 2 500
+ VCIICFC (= VCEAC)                           +   500
− PCIICF  (= PCEA)                            −   300
+ Dotations aux amortissements et provisions  + 15 300
− Reprises sur provisions                     −  1 100
═══════════════════════════════════════════════════════
= CAF                                         = 11 900
```

#### ▪ Méthode SOUSTRACTIVE

**Étape préalable — l'EBE :**
```
  Ventes de marchandises                        24 000
+ Production vendue                            164 000
+ Production stockée                           − 4 500
──────────────────────────────────────────────────────
  Produits d'exploitation encaissables       = 183 500

  Achats de marchandises                        14 000
+ Variation des stocks de marchandises           1 500
+ Achats de matières premières                  78 000
+ Variation des stocks de MP                   − 3 000
+ Impôts et taxes                                1 200
+ Charges de personnel                          76 800
──────────────────────────────────────────────────────
  Charges d'exploitation décaissables        = 168 500

  EBE = 183 500 − 168 500                    =  15 000
```

**Puis la CAF :**
```
  EBE                                           15 000
+ Produits financiers                          +   500
− Charges financières                          − 1 500
+ Produits exceptionnels                       + 1 200      ← PCIICF (300) EXCLU
− Charges exceptionnelles                      −   400      ← VCIICFC (500) EXCLU
− Participation des salariés                   −   900
− Impôt sur les bénéfices                      − 2 000
═══════════════════════════════════════════════════════
= CAF                                          = 11 900     ✅ IDENTIQUE
```

> **⚠️ Le piège n°1** : les **DAP (15 300) et les reprises (1 100) n'apparaissent PAS** dans la méthode soustractive. C'est normal : on part de l'EBE, qui les a déjà exclues. Beaucoup d'étudiants les rajoutent par réflexe.
>
> **⚠️ Le piège n°2** : dans les charges exceptionnelles, on prend **400 seulement**, pas 900. Le VCIICFC de 500 est une ligne distincte, qu'on exclut.
>
> **Le fait remarquable à souligner sur ta copie** : le résultat est une **perte de 2 500**, et pourtant la CAF est **positive de 11 900**. C'est une question de cours du TD : *oui, c'est possible dès lors que les dotations nettes de reprises (15 300 − 1 100 = 14 200) sont supérieures à la perte.*

---

### Question 2.1 — La variation du BFRE

```
Variation des stocks de marchandises = + 1 500  →  SI > SF  →  stock ↓  →  BFRE  − 1 500
Variation des stocks de MP           = − 3 000  →  SI < SF  →  stock ↑  →  BFRE  + 3 000
Production stockée                   = − 4 500  →  SF < SI  →  stock ↓  →  BFRE  − 4 500
Clients et créances d'exploitation : DIMINUTION de 3 000    →  BFRE  − 3 000
Fournisseurs et dettes d'exploitation : DIMINUTION de 1 500 →  BFRE  + 1 500
═══════════════════════════════════════════════════════════════════════════════
                    VARIATION DU BFRE                       =    − 4 500
```

> **Le raisonnement en clair, à écrire sur ta copie** :
> - *les créances clients baissent → mes clients me doivent moins d'argent → mon besoin de financement baisse*
> - *les dettes fournisseurs baissent → je garde moins d'argent des autres → mon besoin de financement augmente*

---

### Question 2.2 — La variation du BFR

```
Variation du BFRE                                             − 4 500
Dettes HORS EXPLOITATION : AUGMENTATION de 4 500  →  BFRHE     − 4 500
═════════════════════════════════════════════════════════════════════
VARIATION DU BFR                                             = − 9 000
```

> **Note** : les dividendes de 4 500 sont une **information distractive** pour cette question. Ils ne servent qu'au calcul de l'autofinancement (non demandé ici). Ne les intègre pas au BFR.

---

### Question 3 — Le commentaire (avec ETE et ESOG)

**Les deux calculs préalables — indispensables, ils sont exigés par la question :**
```
ETE  = EBE − Variation du BFRE = 15 000 − (− 4 500)  =  19 500
ESOG = CAF − Variation du BFR  = 11 900 − (− 9 000)  =  20 900
```

> **⚠️ LE piège de la partie I** : les deux variations sont **NÉGATIVES**. Soustraire un nombre négatif, c'est **additionner**. Si tu écris `15 000 − 4 500 = 10 500`, c'est faux et le correcteur voit immédiatement l'incompréhension du mécanisme. Pose bien les parenthèses.

**Proposition de commentaire :**

> L'exercice se solde par une **perte de 2 500 €**, ce qui traduit une rentabilité insuffisante. Pour autant, l'entreprise **génère de la trésorerie** : la CAF s'élève à 11 900 €, car les charges non décaissables (dotations nettes de reprises : 14 200 €) excèdent largement la perte comptable. L'entreprise a donc les moyens de se financer, mais son exploitation ne crée pas de valeur.
>
> L'**EBE de 15 000 €** montre que l'activité courante est bénéficiaire. La perte provient donc du poids des amortissements (15 300 €) et des charges financières (1 500 €), non de l'exploitation elle-même.
>
> Le **BFRE diminue de 4 500 €** : les stocks de marchandises et de produits finis se sont dégonflés et les créances clients ont reculé. Ce déstockage libère de la trésorerie. L'**ETE atteint donc 19 500 €**, soit **plus que l'EBE** : l'exploitation a encaissé davantage qu'elle n'a produit de richesse comptable, grâce à cette libération de BFR. C'est une situation favorable à court terme.
>
> L'**ESOG de 20 900 €** confirme ce diagnostic sur l'ensemble des opérations de gestion, la baisse du BFR hors exploitation (dettes hors exploitation en hausse de 4 500 €) renforçant encore le flux disponible.
>
> **La nuance indispensable** : cette amélioration de trésorerie provient d'une **contraction de l'activité** (déstockage, baisse des créances), et non d'une performance opérationnelle. Ce n'est pas reproductible : une fois les stocks écoulés, l'effet disparaîtra. Par ailleurs, l'entreprise a distribué **4 500 € de dividendes** alors qu'elle réalise une perte — ce qui ampute son autofinancement et interroge sur la politique de distribution. L'autofinancement brut ne s'élève qu'à 11 900 − 4 500 = **7 400 €**.

---

## PARTIE II — FRNG, BFR, variations

### ▸ Étape 0 — Reconstituer le bilan N−1 en valeurs BRUTES

L'énoncé ne donne le bilan N−1 qu'en **valeurs nettes**. Or le bilan fonctionnel se construit en **BRUT**. D'où les « Renseignements complémentaires concernant le bilan d'ouverture au 01/01/N ». **C'est le premier travail à faire, et c'est là que se joue l'exercice.**

```
Amortissements des immobilisations corporelles au 01/01/N :   986
Provisions pour dépréciation des stocks                   :    20
Provisions pour dépréciation des comptes de clients       :    50
────────────────────────────────────────────────────────────────
TOTAL des amortissements et provisions N−1                : 1 056
```

**Reconstitution :**
```
Actif immobilisé BRUT N−1  = 2 409 (net) + 986 (amortissements)  = 3 395
Stocks BRUT N−1            = (1 100 + 27 + 450) + 20             = 1 597
Créances clients BRUT N−1  = 3 550 + 50                          = 3 600
Actif circulant BRUT N−1   = 5 584 (net) + 70                    = 5 654
────────────────────────────────────────────────────────────────────────
TOTAL ACTIF BRUT N−1       = 3 395 + 5 654                       = 9 049
Contrôle : 9 049 − 1 056 = 7 993  ✅ (= total net donné)
```

> **Autre point de lecture** : au passif N−1, le report à nouveau est **négatif (− 50)**. C'est la seule façon d'obtenir le total de 3 388 annoncé. Vérifie toujours qu'un total de bilan « tombe » — s'il ne tombe pas, tu as mal lu une ligne.

---

### ▸ Étape 1 — Les bilans fonctionnels

#### Exercice N

| ACTIF (brut) | | PASSIF | |
|---|---|---|---|
| **Actif immobilisé** | **4 094** | **Ressources propres** | |
| | | Capitaux propres | 4 064 |
| | | Amortissements & provisions (991 + 50) | 1 041 |
| | | Provisions pour R&C (240 + 1 040) | 1 280 |
| | | **Dettes financières** (650 + 2 436 + 830 − **16 CBC**) | **3 900** |
| | | *Total ressources stables* | ***10 285*** |
| **Actif circulant d'exploitation** | | **Dettes d'exploitation** | |
| Stocks (1 210 + 30 + 500) | 1 740 | Avances et acomptes reçus | 750 |
| Créances clients | 4 965 | Dettes fournisseurs | 230 |
| Autres créances (exploitation) | 428 | | |
| Charges constatées d'avance | 8 | | |
| *Total ACE* | ***7 141*** | *Total DE* | ***980*** |
| **Actif circulant hors exploitation** (VMP) | **42** | **Dettes hors exploitation** | **0** |
| **Trésorerie d'actif** (disponibilités) | **4** | **Trésorerie de passif** (CBC) | **16** |
| **TOTAL** | **11 281** | **TOTAL** | **11 281** |

✅ **Contrôle** : 11 281 = total brut du bilan comptable.

#### Exercice N−1

| ACTIF (brut) | | PASSIF | |
|---|---|---|---|
| Actif immobilisé | **3 395** | Capitaux propres | 3 388 |
| | | Amortissements & provisions | 1 056 |
| | | Provisions pour R&C | 312 |
| | | Dettes financières (508 + 2 722 + 625 − **55 CBC**) | 3 800 |
| | | *Total ressources stables* | ***8 556*** |
| Stocks (1 100+27+450+20) | 1 597 | Avances et acomptes reçus | 230 |
| Créances clients (3 550+50) | 3 600 | Dettes fournisseurs | 208 |
| Autres créances | 388 | | |
| CCA | 6 | | |
| *Total ACE* | ***5 591*** | *Total DE* | ***438*** |
| ACHE (VMP) | **56** | DHE | **0** |
| Trésorerie d'actif | **7** | Trésorerie de passif (CBC) | **55** |
| **TOTAL** | **9 049** | **TOTAL** | **9 049** |

✅ **Contrôle** : 9 049.

---

### Question 1 — La variation du FRNG

```
FRNG N   = 10 285 − 4 094 =  6 191
FRNG N−1 =  8 556 − 3 395 =  5 161
─────────────────────────────────────
Δ FRNG                    = + 1 030
```

---

### Question 2 — La variation du BFRE

```
BFRE N   = 7 141 −   980 =  6 161
BFRE N−1 = 5 591 −   438 =  5 153
─────────────────────────────────────
Δ BFRE                   = + 1 008
```

*(Pour information, non demandé mais utile au commentaire :)*
```
BFRHE N   =  42 − 0 =  42        BFRHE N−1 =  56 − 0 =  56    →  Δ BFRHE = − 14
BFR N     = 6 203                BFR N−1   = 5 209            →  Δ BFR   = + 994
```

---

### Question 3 — La variation de la trésorerie nette PAR DEUX MÉTHODES

**Méthode 1 — par le haut du bilan :**
```
Δ TN = Δ FRNG − Δ BFR = 1 030 − 994 = + 36
```

**Méthode 2 — par le bas du bilan :**
```
Δ TN = Δ Trésorerie d'actif − Δ Trésorerie de passif
Δ TN = (4 − 7) − (16 − 55) = (− 3) − (− 39) = + 36        ✅ IDENTIQUE
```

*Vérification directe :* `TN N = 4 − 16 = −12` ; `TN N−1 = 7 − 55 = −48` ; `−12 − (−48) = +36` ✅

> **Ce que le correcteur attend ici** : que tu **écrives explicitement les deux méthodes** et que tu conclues *« les deux méthodes concordent »*. C'est la raison d'être de la question. Ne fais pas qu'une seule méthode.

---

### Question 4 — Le commentaire

> **La situation reste structurellement déséquilibrée**, mais elle **s'améliore légèrement**.
>
> **Le constat.** Le FRNG progresse de 1 030 k€ (de 5 161 à 6 191). Le BFR progresse de 994 k€ (de 5 209 à 6 203). Le FRNG croît donc un peu plus vite que le BFR, ce qui améliore la trésorerie nette de 36 k€. **Mais la trésorerie nette reste négative** (− 12 k€ contre − 48 k€) : l'entreprise demeure dépendante de son découvert bancaire.
>
> **L'explication.** L'entreprise investit fortement : l'actif immobilisé brut passe de 3 395 à 4 094 k€, soit **+ 21 %**. Elle finance cet effort par des ressources stables en hausse : capitaux propres (+ 676 k€, résultat conservé et réserves), amortissements (+ 55 k€) et surtout provisions pour risques et charges (+ 968 k€, dont une provision pour charges de 1 040 k€ créée dans l'exercice). En revanche, **les dettes financières hors CBC progressent à peine** (3 800 → 3 900) : l'entreprise n'a quasiment pas eu recours à l'emprunt.
>
> **Le point de vigilance.** Le BFRE augmente de 1 008 k€ (+ 20 %), tiré par les créances clients (3 600 → 4 965, soit **+ 38 %**) et les stocks (1 597 → 1 740). **Les créances clients augmentent bien plus vite que l'activité** : soit les délais de paiement se dégradent, soit le recouvrement est insuffisant. C'est le principal levier d'amélioration.
>
> **La nuance.** Les dettes d'exploitation sont anormalement faibles (980 k€ contre 7 141 k€ d'actif circulant d'exploitation) : l'entreprise ne bénéficie quasiment d'aucun crédit fournisseur. Elle finance donc seule tout son cycle d'exploitation, ce qui explique un BFRE structurellement élevé.
>
> **En conclusion.** L'évolution est favorable mais insuffisante. La trésorerie reste négative et l'entreprise dépend de concours bancaires courants, révocables sans préavis. L'action prioritaire porte sur le **poste clients** : ramener les créances au niveau de N−1 libérerait à lui seul plus de 1 300 k€ de trésorerie.

---

## PARTIE III — Rentabilité

### ▸ Le préalable méthodologique (à lire absolument)

L'entreprise est **en PERTE** (− 8 700 k€) et **ne paie aucun impôt**. C'est une configuration inhabituelle qui déroute, mais elle simplifie plutôt les choses. Deux décisions à prendre :

**Décision 1 — quel « résultat économique » retenir ?**

Deux candidats :
```
(a) Résultat d'EXPLOITATION      = 78 150 − 80 880           = − 2 730
(b) Résultat avant intérêts et impôts (RAII) = RNC + IS + intérêts
                                 = − 8 700 + 0 + 6 200       = − 2 500
```

> **★ Prends (b).** Pourquoi ? Parce que la **question 5 demande de retrouver la Rf par la formule de l'effet de levier**. Cette formule ne boucle qu'avec le RAII. C'est ta boussole : *le résultat économique est celui qui rend la formule du levier exacte.*
>
> Écris quand même une phrase sur ta copie : *« On retient comme résultat économique le résultat avant intérêts et impôts (RNC + IS + charges d'intérêts = − 2 500), afin d'assurer la cohérence avec la formule de l'effet de levier. »* Ça montre que tu maîtrises la nuance, et ça te protège si le correcteur attendait (a).

**Décision 2 — quelles charges d'intérêts ?**

Les charges financières totalisent 10 360 k€, mais elles contiennent des dotations (2 110), des différences de change (1 220) et des charges sur cession de VMP (830). **Seule la ligne « Intérêts et charges assimilées » (6 200) rémunère la dette financière.**

---

### Question 1 — La rentabilité économique avant impôts

```
Résultat économique = RNC + IS + charges d'intérêts
                    = − 8 700 + 0 + 6 200                    = − 2 500

Actif économique    = Capitaux propres HORS résultat + Dettes financières
                    = (20 000 + 16 620) + 40 480
                    =  36 620 + 40 480                       =  77 100

        ╔═══════════════════════════════════════════════════╗
        ║  Re avant impôts = − 2 500 / 77 100 = − 3,24 %    ║
        ╚═══════════════════════════════════════════════════╝
```

> **Attention aux capitaux propres** : `20 000 (capital) + 16 620 (réserves) = 36 620`. **On EXCLUT le résultat** (− 8 700). Le total du passif I est de 27 920, mais ce n'est pas ce qu'il faut prendre.
>
> **Les CBC** : la note précise « dont concours bancaires courants — N : 0 ». Donc les 40 480 sont intégralement des dettes financières stables. Rien à retrancher.

*(Si tu retiens le résultat d'exploitation : Re = − 2 730 / 77 100 = **− 3,54 %**. Mentionne-le en variante.)*

---

### Question 2 — Le taux d'impôt sur les bénéfices

```
Résultat AVANT impôts = Résultat APRÈS impôts + Impôt sur les bénéfices
Résultat avant impôts = (− 8 700) + 0 = − 8 700

        s = IS / Résultat avant impôts = 0 / (− 8 700) = 0 %
```

> **Le raisonnement à écrire** : *« L'entreprise réalise une perte de 8 700 k€. Le compte de résultat ne fait apparaître aucun impôt sur les bénéfices, ce qui est cohérent : **une entreprise déficitaire n'est pas imposée**. Le taux effectif d'imposition de l'exercice est donc nul. »*
>
> C'est une question qui déroute parce qu'on attend un 25 % ou 28 %. **Ne cherche pas midi à quatorze heures : réponds 0 % et justifie.** C'est la bonne réponse et elle vaut ses points.

---

### Question 3 — La rentabilité économique après impôts

```
Re après impôts = Re avant impôts × (1 − s) = − 3,24 % × (1 − 0) = − 3,24 %
```

> **La phrase attendue** : *« Le taux d'imposition étant nul, la rentabilité économique après impôts est identique à la rentabilité économique avant impôts. L'absence d'impôt neutralise l'écart habituel entre les deux. »*

---

### Question 4 — La rentabilité financière

```
Rf = Résultat net comptable / Capitaux propres HORS résultat
Rf = − 8 700 / 36 620

        ╔═══════════════════════════════════════════╗
        ║        Rf = − 23,76 %                     ║
        ╚═══════════════════════════════════════════╝
```

**Conclusion attendue :**
> *La rentabilité financière est très fortement négative : **les actionnaires perdent près de 24 % de leur mise sur l'exercice**. Elle est nettement inférieure à la rentabilité économique après impôts (− 3,24 %), ce qui signifie que **l'endettement aggrave considérablement la situation des actionnaires**. L'écart de plus de 20 points entre les deux mesure exactement le coût de l'effet de massue.*

---

### Question 5 — Retrouver la Rf par la formule de l'effet de levier

**Les paramètres :**
```
Re (avant impôts)  = − 3,24 %
i = charges d'intérêts / dettes financières = 6 200 / 40 480 = 15,32 %
D / CP = 40 480 / 36 620 = 1,1054
s = 0 %  →  (1 − s) = 1
```

**Application de la formule :**
```
Rf = Re × (1 − s)  +  (Re − i) × (D/CP) × (1 − s)

Rf = (− 3,24 %) × 1  +  (− 3,24 % − 15,32 %) × 1,1054 × 1
Rf = − 3,24 %  +  (− 18,56 %) × 1,1054
Rf = − 3,24 %  +  (− 20,52 %)

        ╔═══════════════════════════════════════════╗
        ║        Rf = − 23,76 %      ✅ IDENTIQUE   ║
        ╚═══════════════════════════════════════════╝
```

**Décomposition à commenter :**

| Composante | Valeur | Lecture |
|---|---|---|
| Rentabilité économique après impôt | − 3,24 % | L'outil économique ne rapporte rien |
| **Effet de levier** | **− 20,52 %** | **L'endettement détruit 20 points de rentabilité** |
| = Rentabilité financière | − 23,76 % | Ce que perd l'actionnaire |

**Conclusion attendue :**
> *Le coût de la dette (**i = 15,32 %**) est très largement supérieur à la rentabilité économique (**Re = − 3,24 %**). Le différentiel `(Re − i) = − 18,56 %` est massivement négatif, et il est **amplifié par un bras de levier supérieur à 1** (les dettes financières, 40 480 k€, dépassent les capitaux propres, 36 620 k€ — la règle prudentielle D/CP ≤ 1 n'est plus respectée).*
>
> ***L'effet de levier s'est transformé en effet de MASSUE*** *: l'endettement, au lieu d'enrichir l'actionnaire, lui fait perdre 20,5 points de rentabilité supplémentaires.*
>
> *La situation est d'autant plus préoccupante que **le coût apparent de la dette de 15,32 % est anormalement élevé**, ce qui traduit soit une prime de risque exigée par les prêteurs, soit un endettement contracté dans des conditions dégradées. L'entreprise est prise dans une spirale : la perte augmente l'endettement, l'endettement renchérit les intérêts, les intérêts creusent la perte.*
>
> *Les leviers d'action sont, par ordre de priorité : **(1) rétablir la rentabilité économique** (le résultat d'exploitation est négatif, avec 4 470 k€ de dotations sur actif circulant qui signalent des créances douteuses et des stocks dépréciés) ; **(2) se désendetter** ou renégocier le coût de la dette ; **(3) recapitaliser** pour rétablir le ratio D/CP.*

---

# CC2 2025-2026

## PARTIE I — BFR normatif

### ▸ Étape 0 — Identifier les données de base

```
CAHT (= ventes de marchandises)                       = 192 000 k€
CA quotidien = 192 000 / 360                          =     533,33 k€
```

> **⚠️ La production immobilisée (1 800) n'est PAS du chiffre d'affaires.** Le CAHT, c'est uniquement les ventes de marchandises.

**Le taux de TVA n'est pas donné : il faut le déduire.** Teste 20 % :
```
TVA collectée annuelle = 192 000 × 20 % = 38 400
DS TVA collectée = 3 200 (moyenne) × 360 / 38 400 = 30,0 jours   → chiffre rond ✅
TVA déductible annuelle = (78 300 + 14 000) × 20 % = 18 460
DS TVA déductible = 1 538 (moyenne) × 360 / 18 460 = 30,0 jours  → chiffre rond ✅
```
**Le taux de TVA est bien de 20 %**, et l'assiette de la TVA déductible est **achats de marchandises + autres charges externes** — ce que confirme la note de l'énoncé : *« Le poste Dettes fournisseurs ne concerne que les marchandises et les autres charges externes. »*

> **La technique à retenir** : quand une donnée manque, **teste l'hypothèse standard et vérifie qu'elle produit des chiffres ronds**. Si les DS tombent sur 30 jours pile, tu as trouvé.

**Les valeurs MOYENNES (moyenne des bilans N−1 et N) :**

| Poste | N−1 | N | Moyenne |
|---|---|---|---|
| Stocks (brut) | 10 700 | 14 000 | **12 350** |
| Créances clients (brut) | 32 300 | 37 000 | **34 650** |
| TVA déductible | 1 100 | 1 976 | **1 538** |
| Dettes fournisseurs | 29 000 | 31 000 | **30 000** |
| Dettes sociales | 3 994 | 4 540 | **4 267** |
| TVA collectée | 3 000 | 3 400 | **3 200** |

> **L'énoncé dit « à partir des valeurs BRUTES »** : on prend donc la colonne Brut pour les stocks et les créances clients, pas la colonne Net.

---

### Question 1 — Les durées de stockage (DS)

| Poste | Formule | Calcul | **DS** |
|---|---|---|---|
| **Stocks** | Stock moyen × 360 / coût d'achat des mses vendues | 12 350 × 360 / (78 300 − 3 300) | **59,28 j** |
| **Clients** | Créances moyennes × 360 / CA TTC | 34 650 × 360 / (192 000 × 1,2) | **54,14 j** |
| **TVA déductible** | TVA déd. moyenne × 360 / (achats HT × 20 %) | 1 538 × 360 / 18 460 | **30,00 j** |
| **Fournisseurs** | Dettes moyennes × 360 / achats TTC | 30 000 × 360 / (92 300 × 1,2) | **97,51 j** |
| **Dettes sociales** | Dettes moyennes × 360 / charges de personnel | 4 267 × 360 / 76 800 | **20,00 j** |
| **TVA collectée** | TVA coll. moyenne × 360 / (CAHT × 20 %) | 3 200 × 360 / 38 400 | **30,00 j** |

*Détail du coût d'achat des marchandises vendues :*
```
Achats de marchandises          78 300
+ Variation des stocks         − 3 300
────────────────────────────────────────
= Coût d'achat des mses vendues  75 000
```

---

### Question 2 — Les ratios de structure (RS), arrondis à 2 décimales

| Poste | Formule | Calcul | **RS** |
|---|---|---|---|
| **Stocks** | Coût d'achat des mses vendues / CAHT | 75 000 / 192 000 | **0,39** |
| **Clients** | CA TTC / CAHT | 230 400 / 192 000 | **1,20** |
| **TVA déductible** | (Achats HT × 20 %) / CAHT | 18 460 / 192 000 | **0,10** |
| **Fournisseurs** | Achats TTC / CAHT | 110 760 / 192 000 | **0,58** |
| **Dettes sociales** | Charges de personnel / CAHT | 76 800 / 192 000 | **0,40** |
| **TVA collectée** | (CAHT × 20 %) / CAHT | 38 400 / 192 000 | **0,20** |

> **Note sur la note de l'énoncé** *« Pour le calcul du coût de production, la société incorpore toutes les charges d'exploitation »*. Cette indication est là pour lever une ambiguïté sur la valorisation du stock. **Elle ne change rien au résultat final**, grâce à la propriété : `DS × RS = valeur moyenne du poste × 360 / CAHT`. La base de coût se simplifie. **Signale-le sur ta copie, c'est un point de compréhension.**

---

### Question 3 — Le BFR normatif

| Postes | DS | RS | **Besoins** | **Dégagements** |
|---|---|---|---|---|
| Stocks | 59,28 | 0,39 | **23,2** | |
| Clients | 54,14 | 1,20 | **65,0** | |
| TVA déductible | 30,00 | 0,10 | **2,9** | |
| Fournisseurs | 97,51 | 0,58 | | **56,3** |
| Dettes sociales | 20,00 | 0,40 | | **8,0** |
| TVA collectée | 30,00 | 0,20 | | **6,0** |
| | | **TOTAUX** | **91,1** | **70,3** |
| **BFR normatif en jours de CAHT** | | | **20,8 jours** | |

```
BFR normatif en valeur = 20,8 × (192 000 / 360) = 20,8 × 533,33 ≈ 11 093 k€
```

✅ **Contrôle par le bilan** (à écrire sur ta copie, c'est très valorisé) :
```
BFRE moyen = (12 350 + 34 650 + 1 538) − (30 000 + 4 267 + 3 200)
           =  48 538 − 37 467 = 11 071 k€        ✅ cohérent aux arrondis près
```

---

### Question 4 — Le commentaire

> **Le constat.** Le besoin en fonds de roulement normatif s'établit à **20,8 jours de chiffre d'affaires hors taxes**, soit environ **11,1 M€**. Ce niveau est **modéré** pour une entreprise de négoce, et le cycle d'exploitation est loin d'absorber toute la trésorerie.
>
> **Poste par poste.** Le poste **Clients pèse à lui seul 65 jours de CAHT** : c'est de très loin le premier besoin. Le délai de règlement réel est de 54 jours, ce qui est **supérieur au plafond légal de 60 jours date de facture** seulement en apparence, mais reste élevé pour une activité de distribution. Le poste **Stocks représente 23 jours**, avec une durée de stockage de 59 jours — soit environ deux mois de marchandises en réserve, ce qui est important.
>
> **Le facteur d'équilibre.** Ces besoins sont largement compensés par le **crédit fournisseurs, qui dégage 56 jours de CAHT** grâce à une durée de règlement exceptionnellement longue de **97,5 jours**. C'est ce poste qui rend le BFR supportable. **Mais cette durée dépasse très largement les délais légaux de paiement (60 jours maximum en France)** : soit l'entreprise bénéficie de conditions dérogatoires, soit elle est en retard de paiement chronique — ce qui constitue un **risque juridique et commercial majeur**. Si les fournisseurs exigeaient un retour à 60 jours, le dégagement tomberait à 34,7 jours et **le BFR normatif bondirait à environ 42 jours, soit 22,4 M€** : plus du double.
>
> **La tendance.** Tous les postes du BFR progressent entre N−1 et N (stocks + 31 %, clients + 15 %, fournisseurs + 7 %). Les stocks et les créances augmentent **plus vite que les dettes fournisseurs**, ce qui signifie que le BFR se dégrade. Cette évolution, conjuguée à l'apparition de concours bancaires courants (896 → 1 900), confirme une tension croissante sur la trésorerie.
>
> **Les recommandations.** Par ordre d'efficacité :
> 1. **Réduire le délai clients.** Un gain de 10 jours de DS libère `10 × 1,20 = 12 jours` de CAHT, soit **6,4 M€**. Moyens : escompte de règlement, relance systématique, affacturage, acomptes à la commande.
> 2. **Réduire la durée de stockage.** Passer de 59 à 45 jours libère `14 × 0,39 = 5,5 jours`, soit **2,9 M€**.
> 3. **Sécuriser le crédit fournisseurs** — non pas l'allonger davantage (il est déjà hors norme), mais **le contractualiser** pour éviter une remise en cause brutale.

---

## PARTIE II — Tableau de flux

### Question 1 — Les plus ou moins-values de l'exercice

**Où trouver chaque colonne :**
- **Prix de cession** → donné en clair dans l'énoncé
- **Valeur d'origine** → colonne « Diminutions » du **tableau des IMMOBILISATIONS**
- **Amortissements pratiqués** → colonne « Diminutions » du **tableau des AMORTISSEMENTS**

| Éléments | Prix de cession (1) | Valeur d'origine (2) | Amortissements (3) | VNC (4)=(2)−(3) | +/− value (1)−(4) |
|---|---|---|---|---|---|
| **Constructions** | 31 200 | 36 000 | 12 000 | 24 000 | **+ 7 200** |
| **Matériels** | 2 400 | 12 000 | 4 800 | 7 200 | **− 4 800** |
| **Titres de participations** | 14 400 | 12 000 | 0 | 12 000 | **+ 2 400** |
| **TOTAL** | **48 000** | **60 000** | **16 800** | **43 200** | **+ 4 800** |

> **Le rapprochement à faire mentalement** : le tableau des immobilisations affiche 64 800 de diminutions. Mais 4 800 correspondent à la **réduction des prêts** (un prêt remboursé, ce n'est pas une cession). Les cessions représentent donc `64 800 − 4 800 = 60 000`. ✅
>
> **Les titres de participation ne s'amortissent pas** : leur amortissement est nul, la VNC est égale à la valeur d'origine.

---

### Question 2 — Le tableau de flux

#### ▪ Flux de trésorerie liés à l'activité

```
  Résultat net                                                     33 600

+ Dotations aux amortissements et provisions NETTES DE REPRISES
  (sauf sur actif circulant) :
     Dotations aux amortissements  (tableau amort., augmentations)  91 200
   + Dotations aux provisions pour risques et charges                2 400
   − Reprises                                                            0
   [la dotation de 2 400 pour dépréciation des créances clients
    est EXCLUE : elle porte sur l'actif circulant]                 + 93 600

− Plus-value de cession                                            −  4 800
− Transfert de charges aux frais d'émission des emprunts                 ---
═══════════════════════════════════════════════════════════════════════════
= MARGE BRUTE D'AUTOFINANCEMENT                                     122 400
```

**La variation du BFR lié à l'activité (en valeurs NETTES) :**

| Poste | N | N−1 | Variation | Effet trésorerie |
|---|---|---|---|---|
| **Stocks** (7 200 + 108 000) / (12 000 + 96 000) | 115 200 | 108 000 | + 7 200 ↑ | **− 7 200** |
| **Créances d'exploitation** (clients nets) | 24 000 | 21 600 | + 2 400 ↑ | **− 2 400** |
| **Dettes d'exploitation** (43 200+4 800)/(60 000+12 000) | 48 000 | 72 000 | − 24 000 ↓ | **− 24 000** |
| **Autres créances liées à l'activité** (créances diverses) | 36 000 | 40 800 | − 4 800 ↓ | **+ 4 800** |
| **Autres dettes liées à l'activité** | 0 | 0 | 0 | **0** |
| | | | **TOTAL** | **− 28 800** |

```
FLUX NET DE TRÉSORERIE GÉNÉRÉ PAR L'ACTIVITÉ (A) = 122 400 − 28 800 = 93 600
```

> **⚠️ Piège n°1** : les créances clients se prennent **en NET** (24 000 et 21 600), pas en brut. C'est l'inverse du bilan fonctionnel.
>
> **⚠️ Piège n°2** : les dettes d'exploitation **BAISSENT** de 24 000. Une dette qui baisse, c'est de l'argent qui sort → signe **négatif**. C'est le plus gros poste de la variation.
>
> **⚠️ Piège n°3** : la dotation de 2 400 sur les créances clients est exclue du bloc des dotations, **parce que les créances sont ensuite reprises en valeurs nettes**. La compter deux fois est l'erreur la plus fréquente.

#### ▪ Flux de trésorerie lié aux opérations d'investissement

```
− Acquisitions d'immobilisations (colonne « Augmentations »)      − 232 800
    [4 800 (frais d'établissement) + 96 000 (constructions)
     + 132 000 (installations techniques)]
+ Cessions d'immobilisations (prix de cession)                    +  48 000
    [31 200 + 2 400 + 14 400]
+ Réduction d'immobilisations financières (prêts remboursés)      +   4 800
  Variation des dettes et créances sur immobilisations                  ---
═══════════════════════════════════════════════════════════════════════════
= FLUX LIÉ AUX OPÉRATIONS D'INVESTISSEMENT (B)                    − 180 000
```

> **Ne confonds pas** : la cession de **participations** (14 400) va dans « cessions d'immobilisations » (c'est un désinvestissement financier avec plus-value). Le remboursement de **prêts** (4 800) va dans « réduction d'immobilisations financières » (l'entreprise récupère un capital prêté, sans plus-value).

#### ▪ Flux de trésorerie lié aux opérations de financement

```
− Dividendes versés                                               −  24 000
    [Résultat N−1 (24 000) − Δréserves (0) − ΔRAN (0) = 24 000]
+ Incidence des variations de capital (672 000 − 552 000)         + 120 000
+ Émissions d'emprunts   [« pas de nouvel emprunt en N »]                 0
− Remboursement d'emprunts (48 000 − 36 000)                      −  12 000
═══════════════════════════════════════════════════════════════════════════
= FLUX LIÉ AUX OPÉRATIONS DE FINANCEMENT (C)                      +  84 000
```

#### ▪ Variation de trésorerie

```
  Flux d'activité       (A)                                       +  93 600
  Flux d'investissement (B)                                       − 180 000
  Flux de financement   (C)                                       +  84 000
═══════════════════════════════════════════════════════════════════════════
  VARIATION DE TRÉSORERIE                                         −   2 400

  Trésorerie d'ouverture (disponibilités, ni VMP ni CBC)             14 400
  Trésorerie de clôture                                              12 000
  Contrôle : 12 000 − 14 400 = − 2 400                              ✅ OK
```

> **Écris ce contrôle sur ta copie.** C'est la preuve que ton tableau est juste, et le correcteur le cherche.

---

### Question 3 — Conclusion sur la situation de l'entreprise

> **Une entreprise qui investit massivement et se recapitalise, au prix d'une exploitation qui se dégrade.**
>
> **① L'activité génère de la trésorerie, mais moins bien qu'il n'y paraît.** La marge brute d'autofinancement atteint 122 400 €, un niveau très confortable au regard d'un résultat net de 33 600 € — l'écart s'explique par des dotations aux amortissements considérables (91 200 €), signe d'un outil productif lourd. **Mais le besoin en fonds de roulement absorbe 28 800 €**, soit près d'un quart de la MBA. Le flux d'activité ressort à 93 600 €.
>
> **La cause principale de cette absorption n'est pas la croissance, mais le CRÉDIT FOURNISSEUR** : les dettes d'exploitation chutent de 72 000 à 48 000 €, soit **− 33 %**. L'entreprise paie ses fournisseurs beaucoup plus vite qu'auparavant. Cela peut traduire une perte de confiance des fournisseurs, une négociation d'escomptes, ou une politique délibérée — mais dans tous les cas cela coûte 24 000 € de trésorerie. Les stocks progressent par ailleurs de 7 200 € (+ 7 %).
>
> **② L'effort d'investissement est massif et structurant.** 232 800 € d'acquisitions, dont 132 000 € d'installations techniques (+ 55 % du poste) et 96 000 € de constructions (+ 20 %). Il s'agit sans ambiguïté d'une **croissance interne** visant à accroître les capacités productives, et non d'un simple renouvellement. En parallèle, l'entreprise **cède ses participations** (12 000 € de valeur d'origine, soldées à 14 400 €) et récupère ses prêts (4 800 €) : elle **se recentre sur son métier** et abandonne ses positions financières pour financer son outil industriel. Le flux d'investissement net atteint − 180 000 €.
>
> **③ Le financement repose entièrement sur les actionnaires.** L'augmentation de capital de 120 000 € est l'événement majeur de l'exercice : elle couvre les deux tiers de l'investissement. Dans le même temps, l'entreprise **rembourse 12 000 € de dettes** sans souscrire de nouvel emprunt, et **distribue l'intégralité du résultat N−1 en dividendes** (24 000 €). Le flux de financement s'établit à + 84 000 €.
>
> **④ Le point critique.** **L'entreprise distribue 24 000 € de dividendes l'année même où elle sollicite 120 000 € de ses actionnaires et où sa trésorerie se contracte.** C'est une incohérence de politique financière : une mise en réserve du résultat N−1 aurait réduit d'autant le besoin d'appel au marché, à moindre coût. Par ailleurs, alors que la structure financière se désendette (dettes financières de 48 000 à 36 000 €, capitaux propres en forte hausse), **le recours à l'emprunt aurait été une alternative légitime pour financer un investissement productif amortissable sur plusieurs années** — d'autant que le désendettement réduit mécaniquement l'effet de levier.
>
> **⑤ En synthèse.** La variation de trésorerie n'est que de − 2 400 € : l'équilibre est presque tenu, ce qui est remarquable au vu de l'ampleur de l'investissement. La trésorerie reste positive (12 000 €) et sans concours bancaires. **La stratégie est cohérente — investir dans l'outil productif, se recentrer, se désendetter — mais son financement est déséquilibré** : trop d'appel aux actionnaires, pas assez de dette, et une distribution de dividendes injustifiée. Le point de vigilance pour N+1 sera la **remontée du crédit fournisseur** et le **retour sur investissement des 232 800 € engagés**.

---

# CC3 2025-2026

## PARTIE I — Escompte, date d'échéance

> *Deux effets de 8 000 € et 7 000 €, même date d'échéance, remis à l'escompte le 05/03. Taux 6,00 %. Montant crédité : 14 860,00 €. Déterminer la date d'échéance.*

### La logique : on remonte la formule à l'envers

```
ÉTAPE 1 — L'escompte total
   Valeur nominale totale = 8 000 + 7 000 = 15 000 €
   Escompte = VN − montant crédité = 15 000 − 14 860 = 140 €

ÉTAPE 2 — Le nombre de jours
   e = VN × t × j/360
   140 = 15 000 × 0,06 × j/360
   140 = 900 × j/360
   j = 140 × 360 / 900 = 50 400 / 900 = 56 jours

ÉTAPE 3 — La date
   Départ : 05/03
   Jours restants en mars : 31 − 5 = 26 jours   →  on arrive au 31/03
   Reste : 56 − 26 = 30 jours                   →  30 jours d'avril

        ╔═══════════════════════════════════════╗
        ║   DATE D'ÉCHÉANCE : LE 30 AVRIL       ║
        ╚═══════════════════════════════════════╝
```

**Vérification :**
```
15 000 × 0,06 × 56/360 = 140,00 €   →   15 000 − 140 = 14 860 €   ✅
```

> **Points de méthode :**
> - Comme les deux effets ont **la même échéance**, on peut les traiter comme un seul effet de 15 000 €. Inutile de les séparer.
> - **Aucune commission, aucun jour de banque** ne sont mentionnés : l'escompte pur suffit. Ne complique pas.
> - Le calendrier doit être sur ton brouillon : `J31 F28 M31 A30 M31 J30 J31 A31 S30 O31 N30 D31`.

---

## PARTIE II — Équivalence d'effets

> *Le 10 avril, une entreprise convient de remplacer par un effet unique « C » échéant le 25 mai les trois traites suivantes : 1 400 € au 30 avril, 1 800 € au 15 mai, 2 700 € au 4 juin.*

### ▸ Étape 0 — Le décompte des jours depuis la DATE D'ÉQUIVALENCE (10 avril)

```
Du 10/04 au 30/04 :  30 − 10                =  20 jours
Du 10/04 au 15/05 :  20 + 15                =  35 jours
Du 10/04 au 25/05 :  20 + 25                =  45 jours    ← l'effet C
Du 10/04 au 04/06 :  20 + 31 + 4            =  55 jours
```

> **Cette étape doit être faite en premier et écrite explicitement.** Elle vaut des points à elle seule, et toute erreur ici se propage.

---

### Question 1 — La valeur nominale « C » au taux de 12 %

**Le principe : à la date d'équivalence, la valeur actuelle de l'effet unique = la somme des valeurs actuelles des trois traites.**

```
Valeurs actuelles au 10/04 (formule : VN × [1 − t × j/360]) :

  1 400 × (1 − 0,12 × 20/360) = 1 400 × 0,993333 = 1 390,67
  1 800 × (1 − 0,12 × 35/360) = 1 800 × 0,988333 = 1 779,00
  2 700 × (1 − 0,12 × 55/360) = 2 700 × 0,981667 = 2 650,50
  ────────────────────────────────────────────────────────
                                          TOTAL  = 5 820,17

Équation d'équivalence :
  C × (1 − 0,12 × 45/360) = 5 820,17
  C × (1 − 0,015)         = 5 820,17
  C × 0,985               = 5 820,17

        ╔═══════════════════════════════════════╗
        ║        C = 5 908,80 €                 ║
        ╚═══════════════════════════════════════╝
```

> **Contrôle de bon sens** : `C = 5 908,80 > 1 400 + 1 800 + 2 700 = 5 900`. C'est logique : l'échéance moyenne des trois traites (environ 40 jours) est **antérieure** au 25 mai (45 jours), donc le débiteur gagne du temps et paie un peu plus. **Si tu trouvais une valeur inférieure à 5 900, tu aurais une erreur.**

---

### Question 2 — Le taux si C = 5 905 €

**La méthode : on développe les deux membres et on isole t.**

```
5 905 × (1 − t × 45/360) = 1 400(1 − t×20/360) + 1 800(1 − t×35/360) + 2 700(1 − t×55/360)

MEMBRE DE GAUCHE :
   5 905 − t × (5 905 × 45)/360 = 5 905 − 738,125 t

MEMBRE DE DROITE :
   (1 400 + 1 800 + 2 700) − t × (1 400×20 + 1 800×35 + 2 700×55)/360
   = 5 900 − t × (28 000 + 63 000 + 148 500)/360
   = 5 900 − t × 239 500/360
   = 5 900 − 665,278 t

ÉQUATION :
   5 905 − 738,125 t = 5 900 − 665,278 t
   5 905 − 5 900 = 738,125 t − 665,278 t
   5 = 72,847 t

        ╔═══════════════════════════════════════╗
        ║   t = 5 / 72,847 = 0,06864            ║
        ║   soit  t = 6,86 %                    ║
        ╚═══════════════════════════════════════╝
```

**Vérification :**
```
Gauche  : 5 905 × (1 − 0,06864 × 45/360) = 5 905 × 0,991420 = 5 854,33
Droite  : 1 400 × 0,996187 + 1 800 × 0,993327 + 2 700 × 0,989515
        = 1 394,66 + 1 788,00 + 2 671,69 = 5 854,35              ✅
```

> **La formule générale, si tu veux gagner du temps :**
> ```
>              (VN nouveau) − (Σ VN anciens)
>   t = ─────────────────────────────────────────────────
>       [ (VN nouv × j nouv) − Σ (VN_i × j_i) ] / 360
> ```
> Ici : `t = 5 / [(265 725 − 239 500)/360] = 5 / 72,847 = 6,86 %`
>
> **Contrôle de cohérence** : la valeur nominale demandée (5 905) est plus faible que celle calculée à 12 % (5 908,80). Un nominal plus faible pour la même échéance signifie **un taux plus faible**. Trouver 6,86 % < 12 % est donc cohérent. ✅

---

## PARTIE III — Escompte versus découvert

> *Déficit d'environ 200 000 €, du 24/05 au 12/06 inclus. Pas d'autre déficit en mai et juin.*
> *Effets : 80 000, 65 500 et 21 000 € à échéance du 15/06 ; 40 000, 20 000, 5 000 et 3 000 € à échéance du 20/06.*
> *Escompte : taux 6,30 %, commission de manipulation 2,40 € HT par effet, 1 jour de banque.*
> *Découvert : taux 6,85 %, CPFD 0,05 % calculée pour chaque mois civil.*

---

### Question 1 — Quels effets porter à l'escompte ?

**Les trois critères de sélection, dans l'ordre :**

```
① ÉLIGIBILITÉ : l'échéance doit être POSTÉRIEURE à la fin du déficit (12/06).
   → 15/06 et 20/06 sont tous deux postérieurs. Les 7 effets sont éligibles.

② PRIORITÉ AUX ÉCHÉANCES LES PLUS PROCHES (moins de jours = moins d'escompte).
   → On prend d'abord les 3 effets du 15/06 :
        80 000 + 65 500 + 21 000 = 166 500 €
   → Insuffisant : il manque 200 000 − 166 500 = 33 500 €

③ COMPLÉMENT avec le MINIMUM d'effets du 20/06 :
   → 20 000 + 5 000 + 3 000 = 28 000 €  →  INSUFFISANT (< 33 500)
   → 40 000 €                            →  SUFFISANT, et c'est UN SEUL effet
                                             (2,40 € de commission au lieu de 7,20 €)
```

```
        ╔══════════════════════════════════════════════════════════════╗
        ║  On escompte 4 effets :                                      ║
        ║     • 80 000, 65 500 et 21 000 € à échéance du 15/06         ║
        ║     • 40 000 € à échéance du 20/06                           ║
        ║  Total mobilisé : 206 500 €  (couvre bien les 200 000 €)     ║
        ╚══════════════════════════════════════════════════════════════╝
```

> **La justification à écrire** : *« On privilégie les effets dont l'échéance est la plus proche, afin de minimiser la durée d'escompte et donc l'agio. À couverture équivalente, on retient le nombre d'effets le plus faible, la commission de manipulation étant forfaitaire par effet. »*

---

### Question 2 — L'agio relatif à l'opération d'escompte

**Le décompte des jours (remise le 24/05, date d'apparition du déficit) :**
```
Du 24/05 au 15/06 : (31 − 24) + 15 = 7 + 15 = 22 jours  + 1 jour de banque = 23 jours
Du 24/05 au 20/06 : (31 − 24) + 20 = 7 + 20 = 27 jours  + 1 jour de banque = 28 jours
```

**Le calcul :**
```
Escompte sur les effets du 15/06 :
   166 500 × 0,063 × 23/360                              =  670,16 €

Escompte sur l'effet du 20/06 :
    40 000 × 0,063 × 28/360                              =  196,00 €
                                                    ──────────────
   Sous-total escompte                                   =  866,16 €

Commission de manipulation : 4 effets × 2,40 €           =    9,60 €
                                                    ══════════════
        ╔═══════════════════════════════════════════════════════════╗
        ║             AGIO HT  =  875,76 €                          ║
        ╚═══════════════════════════════════════════════════════════╝
```

> **La commission est FORFAITAIRE PAR EFFET**, pas proportionnelle au montant. On multiplie par le **nombre d'effets** (4), pas par le montant.
>
> **Le jour de banque s'ajoute à la durée FACTURÉE**, pas à la durée réelle. Il sert à calculer l'escompte, mais pas le taux réel.

---

### Question 3 — Le coût du découvert

**Le décompte des jours — attention au mot « INCLUS » :**
```
Du 24/05 INCLUS au 12/06 INCLUS :
   Mai  : 31 − 24 + 1 = 8 jours   (le 24, 25, 26, 27, 28, 29, 30, 31)
   Juin : 12 jours
   ─────────────────────────────
   TOTAL : 20 jours
```

**Le tableau des nombres débiteurs :**

| Dates | Nombre de jours (1) | Solde débiteur (2) | Nombres débiteurs (1)×(2) |
|---|---|---|---|
| Du 24/05 au 12/06 | 20 | 200 000 | **4 000 000** |
| | | **TOTAL** | **4 000 000** |

**Le calcul des agios :**
```
Intérêts débiteurs = Nombres débiteurs × t/360
                   = 4 000 000 × 6,85 / 36 000               =  761,11 €

CPFD (commission du plus fort découvert, PAR MOIS CIVIL) :
   Plus fort découvert de MAI   : 200 000
   Plus fort découvert de JUIN  : 200 000
   (200 000 + 200 000) × 0,05 %                              =  200,00 €
                                                        ══════════════
        ╔═══════════════════════════════════════════════════════════╗
        ║             AGIOS HT  =  961,11 €                         ║
        ╚═══════════════════════════════════════════════════════════╝
```

> **⚠️ LE piège de la CPFD** : elle est calculée **pour chaque mois civil**. Le découvert s'étale sur mai ET juin, donc il compte **DEUX FOIS**. Si tu ne comptes qu'une fois (100 €), tu perds la moitié des points de la question.
>
> **Aucune commission de dépassement ici** : l'énoncé ne mentionne pas de plafond de découvert négocié. Ne l'invente pas.

---

### Question 4 — Le taux réel du découvert

```
                    Agios HT × 365          961,11 × 365
   Taux réel  =  ──────────────────────  =  ──────────────  =  0,08770
                 Nombres débiteurs            4 000 000

        ╔═══════════════════════════════════════╗
        ║       TAUX RÉEL  =  8,77 %            ║
        ╚═══════════════════════════════════════╝
```

**Le commentaire attendu :**
> *Le taux réel (8,77 %) est très supérieur au taux nominal du découvert (6,85 %). L'écart de près de 2 points s'explique par deux facteurs : **la commission du plus fort découvert**, prélevée deux fois car le découvert chevauche deux mois civils, et **le passage d'un décompte sur 360 jours (facturation bancaire) à 365 jours (mesure du coût réel)**.*

---

### Question 5 — Le coût de la solution mixte

> *Escompte des effets à échéance du 15/06 et recours au découvert pour le solde.*

**① La partie escomptée :**
```
Escompte : 166 500 × 0,063 × 23/360                        =  670,16 €
Commission : 3 effets × 2,40 €                             =    7,20 €
                                                      ──────────────
   Sous-total escompte                                     =  677,36 €
```

**② La partie découvert :**
```
Solde à financer : 200 000 − 166 500 = 33 500 € pendant 20 jours

Nombres débiteurs = 33 500 × 20                            = 670 000
Intérêts = 670 000 × 6,85/36 000                           =  127,49 €
CPFD : (33 500 en mai + 33 500 en juin) × 0,05 %           =   33,50 €
                                                      ──────────────
   Sous-total découvert                                    =  160,99 €
```

```
        ╔═══════════════════════════════════════════════════════════╗
        ║   COÛT TOTAL DE LA SOLUTION MIXTE  =  838,35 €            ║
        ╚═══════════════════════════════════════════════════════════╝
```

---

### Question 6 — Commentaire

**Le tableau de synthèse (fais-le, il structure ta réponse) :**

| Solution | Montant mobilisé | Agios HT | Classement |
|---|---|---|---|
| **Solution MIXTE** | 166 500 escomptés + 33 500 de découvert | **838,35 €** | 🥇 **1ᵉʳ** |
| **Escompte seul** | 206 500 € | **875,76 €** | 🥈 2ᵉ |
| **Découvert seul** | 200 000 € | **961,11 €** | 🥉 3ᵉ |

**Proposition de commentaire :**

> **La solution mixte est la moins coûteuse**, avec 838,35 € d'agios, soit une économie de **37,41 €** par rapport à l'escompte seul (− 4,3 %) et de **122,76 €** par rapport au découvert seul (− 12,8 %).
>
> **Pourquoi la solution mixte gagne-t-elle ?** Elle combine les avantages des deux instruments :
> - Elle utilise **l'escompte, dont le taux est plus bas** (6,30 % contre 6,85 %), sur la fraction du besoin qui peut être couverte par les effets à échéance la plus proche (166 500 € au 15/06) ;
> - Elle utilise **le découvert, plus souple**, pour l'appoint de 33 500 €, évitant ainsi de mobiliser un effet de 40 000 € pour un besoin de 33 500 € seulement.
>
> **Le défaut de l'escompte seul** est le **sur-financement** : il oblige à mobiliser 206 500 €, soit **6 500 € de plus que nécessaire**, et surtout à escompter un effet à échéance du 20/06 (28 jours facturés) alors que le besoin s'arrête le 12/06. On paie des intérêts sur une somme et une durée dont on n'a pas besoin.
>
> **Le défaut du découvert seul** est double : un **taux nominal supérieur** (6,85 % contre 6,30 %) et une **commission du plus fort découvert prélevée sur deux mois civils** (200 €, soit plus de 20 % du coût total). Son taux réel ressort à **8,77 %**.
>
> **Les critères non financiers à mentionner.** Le choix ne se réduit pas au coût :
> - Le **découvert** est plus **souple** : il s'adapte automatiquement à la durée et au montant exact du besoin, et il n'est facturé que sur les jours réellement utilisés. Mais il **consomme l'autorisation bancaire** et peut être **révoqué sans préavis**.
> - L'**escompte** transfère le **recouvrement** à la banque et **préserve la ligne de découvert** pour d'autres besoins. Mais il est irréversible et rigide.
>
> **Recommandation.** Retenir la **solution mixte** : elle est optimale financièrement et préserve une partie de la capacité de découvert. On escompte les trois effets du 15/06 et l'on couvre le solde de 33 500 € par le découvert.

---

## PARTIE IV — Intérêts composés

> *Placement à intérêts composés de 75 000 €, capitalisation MENSUELLE. 17 mois après, versement supplémentaire de 20 000 €. 17 mois après ce second versement, la valeur acquise est de 102 260 €.*

### ▸ Étape 0 — L'axe du temps (à tracer sur ta copie)

```
   mois 0                  mois 17                      mois 34
     │                        │                            │
  + 75 000                + 20 000                    = 102 260
     └──────── 34 mois de capitalisation ──────────────────┘
                              └──── 17 mois ───────────────┘
```

Le premier capital est placé **34 mois** (17 + 17). Le second est placé **17 mois**.

> **La capitalisation est MENSUELLE** : on raisonne donc avec un **taux mensuel** et un nombre de **mois** comme exposant. Ne convertis rien en années.

---

### Question 1 — Le taux mensuel de capitalisation

**L'équation :**
```
75 000 (1 + t)³⁴  +  20 000 (1 + t)¹⁷  =  102 260
```

**Le changement de variable** — on pose `x = (1 + t)¹⁷`, donc `(1 + t)³⁴ = x²` :
```
75 000 x²  +  20 000 x  −  102 260  =  0
```

**Le discriminant** (l'énoncé te donne le rappel, c'est le signal) :
```
Δ = b² − 4ac
Δ = 20 000² − 4 × 75 000 × (− 102 260)
Δ = 400 000 000 + 30 678 000 000
Δ = 31 078 000 000

√Δ = 176 289,53
```

**Les racines :**
```
x₁ = (− 20 000 − 176 289,53) / (2 × 75 000) = − 196 289,53 / 150 000 = − 1,3086
     → IMPOSSIBLE : x = (1+t)¹⁷ est nécessairement POSITIF. On l'écarte.

x₂ = (− 20 000 + 176 289,53) / 150 000 = 156 289,53 / 150 000 = 1,041930
     → RETENUE
```

**Le retour au taux :**
```
(1 + t)¹⁷ = 1,041930
1 + t = 1,041930^(1/17) = 1,0024191

        ╔═══════════════════════════════════════════════╗
        ║   TAUX MENSUEL  tm = 0,2419 %                 ║
        ╚═══════════════════════════════════════════════╝
```

**Vérification (fais-la, elle prend 30 secondes) :**
```
75 000 × 1,0024191³⁴  =  81 421
20 000 × 1,0024191¹⁷  =  20 839
                          ────────
                          102 260      ✅
```

---

### Question 2 — Le taux TRIMESTRIEL équivalent

Un trimestre contient **3 mois**. La relation d'équivalence :
```
(1 + t_trimestriel) = (1 + t_mensuel)³

t_trim = 1,0024191³ − 1 = 1,0072749 − 1

        ╔═══════════════════════════════════════════════╗
        ║   TAUX TRIMESTRIEL  = 0,7275 %                ║
        ╚═══════════════════════════════════════════════╝
```

---

### Question 3 — Le taux ANNUEL équivalent

Une année contient **12 mois** :
```
(1 + t_annuel) = (1 + t_mensuel)¹²

t_annuel = 1,0024191¹² − 1 = 1,0294181 − 1

        ╔═══════════════════════════════════════════════╗
        ║   TAUX ANNUEL  = 2,9419 %  ≈ 2,94 %           ║
        ╚═══════════════════════════════════════════════╝
```

> **Le contrôle de cohérence** : le taux **proportionnel** annuel serait `0,2419 % × 12 = 2,903 %`. Le taux **équivalent** (2,942 %) est **légèrement supérieur** au taux proportionnel — c'est toujours le cas en capitalisation composée, grâce aux intérêts sur intérêts. **Si tu trouvais un taux équivalent inférieur au proportionnel, tu aurais une erreur.**
>
> **Le contrôle inverse** : `(1 + 0,029418)^(1/12) − 1 = 0,2419 %` ✅ On retombe bien sur le taux mensuel.

> **Erreur à ne surtout pas commettre** : diviser ou multiplier les taux (`0,2419 × 3` ou `0,2419 × 12`). Ce serait le calcul de taux **proportionnels**, alors que la question demande explicitement des taux **ÉQUIVALENTS**. Le mot « équivalent » impose la puissance.

---

# TABLEAU RÉCAPITULATIF DE TOUS LES RÉSULTATS

*À utiliser pour t'auto-corriger rapidement.*

## CC1 2025-2026

| Question | Résultat |
|---|---|
| **I.1** EBE | 15 000 |
| **I.1** CAF (additive = soustractive) | **11 900** |
| **I.2.1** Variation du BFRE | **− 4 500** |
| **I.2.2** Variation du BFR | **− 9 000** |
| **I.3** ETE | 19 500 |
| **I.3** ESOG | 20 900 |
| **II** FRNG N / N−1 | 6 191 / 5 161 |
| **II.1** Variation du FRNG | **+ 1 030** |
| **II** BFRE N / N−1 | 6 161 / 5 153 |
| **II.2** Variation du BFRE | **+ 1 008** |
| **II** BFR N / N−1 | 6 203 / 5 209 |
| **II** TN N / N−1 | − 12 / − 48 |
| **II.3** Variation de la TN (2 méthodes) | **+ 36** |
| **III.1** Résultat économique (RAII) | − 2 500 |
| **III.1** Actif économique | 77 100 |
| **III.1** Re avant impôts | **− 3,24 %** |
| **III.2** Taux d'IS | **0 %** |
| **III.3** Re après impôts | **− 3,24 %** |
| **III.4** Rf | **− 23,76 %** |
| **III.5** i (coût de la dette) | 15,32 % |
| **III.5** D/CP | 1,1054 |
| **III.5** Effet de levier | **− 20,52 %** (massue) |

## CC2 2025-2026

| Question | Résultat |
|---|---|
| **I.1** DS stocks / clients / TVA déd. | 59,28 / 54,14 / 30,00 j |
| **I.1** DS fournisseurs / sociales / TVA coll. | 97,51 / 20,00 / 30,00 j |
| **I.2** RS stocks / clients / TVA déd. | 0,39 / 1,20 / 0,10 |
| **I.2** RS fournisseurs / sociales / TVA coll. | 0,58 / 0,40 / 0,20 |
| **I.3** Total besoins | 91,1 j |
| **I.3** Total dégagements | 70,3 j |
| **I.3** **BFR normatif** | **20,8 jours de CAHT** |
| **I.3** BFR normatif en valeur | ≈ 11 093 k€ |
| **II.1** Plus-value constructions | + 7 200 |
| **II.1** Moins-value matériels | − 4 800 |
| **II.1** Plus-value participations | + 2 400 |
| **II.1** **Plus-value nette** | **+ 4 800** |
| **II.2** Dotations retenues | 93 600 |
| **II.2** **Marge brute d'autofinancement** | **122 400** |
| **II.2** Variation du BFR | − 28 800 |
| **II.2** **Flux d'activité (A)** | **+ 93 600** |
| **II.2** **Flux d'investissement (B)** | **− 180 000** |
| **II.2** Dividendes versés | 24 000 |
| **II.2** **Flux de financement (C)** | **+ 84 000** |
| **II.2** **Variation de trésorerie** | **− 2 400** |
| **II.2** Trésorerie ouverture / clôture | 14 400 / 12 000 |

## CC3 2025-2026

| Question | Résultat |
|---|---|
| **I.1** Escompte | 140 € |
| **I.1** Nombre de jours | 56 j |
| **I.1** **Date d'échéance** | **30 AVRIL** |
| **II.1** Somme des valeurs actuelles | 5 820,17 € |
| **II.1** **Valeur nominale C** | **5 908,80 €** |
| **II.2** **Taux si C = 5 905** | **6,86 %** |
| **III.1** Effets escomptés | 80 000 + 65 500 + 21 000 + 40 000 = **206 500 €** |
| **III.2** **Agio de l'escompte** | **875,76 €** |
| **III.3** Nombres débiteurs | 4 000 000 |
| **III.3** Intérêts / CPFD | 761,11 / 200,00 |
| **III.3** **Coût du découvert** | **961,11 €** |
| **III.4** **Taux réel du découvert** | **8,77 %** |
| **III.5** **Coût de la solution mixte** | **838,35 €** |
| **IV.1** Discriminant Δ | 31 078 000 000 |
| **IV.1** x = (1+t)¹⁷ | 1,041930 |
| **IV.1** **Taux mensuel** | **0,2419 %** |
| **IV.2** **Taux trimestriel équivalent** | **0,7275 %** |
| **IV.3** **Taux annuel équivalent** | **2,94 %** |
