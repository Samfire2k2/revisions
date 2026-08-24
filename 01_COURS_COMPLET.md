# FINANCE D'ENTREPRISE — COURS COMPLET
### M1 MIAGE Nantes — Préparation aux rattrapages
*Reconstitué à partir du polycopié de cours (XMS1IE402/502), du TD et des contrôles continus fournis.*

---

# AVANT-PROPOS : ce que tu dois savoir avant de commencer

## 1. Vérification de tes documents (tu avais raison de demander)

J'ai comparé chaque CC à la table des matières du polycopié de cours. Voici le tri :

| Fichier | Contenu | Verdict |
|---|---|---|
| **CC1 2025-2026** | Équilibres financiers / ETE / ESOG — FRNG, BFR, TN — Rentabilité & effet de levier | ✅ **Finance d'entreprise** (chap. I, II, III) |
| **CC2 2025-2026** | BFR normatif — Tableau de flux | ✅ **Finance d'entreprise** (chap. IV, V) |
| **CC3 2025-2026** | Escompte / Équivalence / Escompte vs découvert / Intérêts composés | ✅ **Finance d'entreprise** (chap. VI, VII) |
| **CC1 2023-2024** | Annuités & taux, comparaison d'offres bancaires (TAEG), politique d'investissement (VAN/TIR) | ⚠️ **PROBABLEMENT UNE AUTRE MATIÈRE** |
| **Corrigé_Cas_renégociation_prêt** | Emprunts indivis, mensualités, renégociation | ⚠️ **AUTRE MATIÈRE** — le pied de page dit littéralement *« TD Mathématiques financières »* |

**Pourquoi cette conclusion ?** Le polycopié de cours 2023 contient exactement **7 chapitres** : bilan, CAF/trésorerie, rentabilité, BFR normatif, tableau de flux, intérêts simples, intérêts composés. **Il n'y a aucun chapitre sur les tableaux d'amortissement d'emprunt, le TAEG ou la VAN/TIR.** Or les trois CC de 2025-2026 couvrent *pile* les 7 chapitres, à raison de 2-3 chapitres par CC. C'est cohérent et fermé.

**Ce que je fais quand même :** je te mets une **Annexe A** en fin de document qui traite les emprunts indivis, le TAEG et la VAN/TIR. C'est court mais suffisant pour ne pas être pris au dépourvu si jamais le prof mélange. Ne commence par là **sous aucun prétexte** : c'est le dernier truc à réviser, pas le premier.

## 2. La structure de l'épreuve (déduite des 3 CC)

Un CC = **2 à 4 exercices indépendants**, chacun avec un « Travail à faire » numéroté, et **toujours une question de commentaire** à la fin (qui vaut 1 à 3 points sur 20 — ne la saute jamais, c'est le meilleur ratio points/effort de l'épreuve).

Le rattrapage couvrira très probablement **tout le programme d'un coup**, donc les 7 chapitres.

## 3. Pourquoi ton prof change les inconnues (et comment le neutraliser)

Tu as parfaitement identifié le problème. Regarde le CC3 :

> *« Déterminer la **date d'échéance** des 2 effets, sachant que le montant crédité s'élève à 14 860 € »*

Dans le cours, l'exercice type c'est : on connaît la date d'échéance, on cherche l'agio. Là il inverse. C'est **exactement la même formule**, lue dans l'autre sens.

Une formule à 4 variables, c'est **4 exercices possibles**. Une formule à 5 variables, c'est 5 exercices. Ton prof exploite ça systématiquement.

**La parade** : pour chaque formule du cours, ce document te donne **toutes les inversions possibles**, chacune avec un exemple numérique. Tu ne dois plus jamais « reconnaître un exercice » — tu dois savoir *isoler n'importe quelle lettre*.

Le réflexe universel :

```
1. J'écris la formule dans le sens du cours (le sens que je connais).
2. Je place TOUTES les valeurs connues dedans.
3. Il reste UNE lettre → c'est une équation à une inconnue.
4. Je résous algébriquement. Point.
```

Ce n'est pas de la finance à ce moment-là, c'est du collège. Le seul piège c'est de paniquer parce que « l'exercice n'est pas comme en TD ».

## 4. Comment utiliser ces 4 fichiers

| Fichier | Quand |
|---|---|
| **01_COURS_COMPLET.md** (celui-ci) | J-10 à J-4 : lecture active, chapitre par chapitre |
| **02_CORRIGES_DES_CC.md** | J-6 à J-3 : tu refais les CC en conditions réelles, puis tu compares |
| **04_BANQUE_EXOS.md** | J-5 à J-2 : les 60+ mini-exos « une inconnue différente à chaque fois » |
| **03_FICHE_MEMO.md** | J-1 et le matin même |

---

# CHAPITRE 0 — LES BASES : comprendre les documents comptables

*Si tu maîtrises déjà bilan et compte de résultat, saute au chapitre 1. Sinon, lis ça, tout le reste en dépend.*

## 0.1 À quoi sert la finance d'entreprise ?

Une entreprise, c'est une machine qui transforme de l'**argent** en **plus d'argent**, en passant par des étapes intermédiaires (acheter des machines, acheter de la matière, produire, vendre, encaisser).

Cette machine peut mourir de **deux** façons — et c'est fondamental, tout le cours tourne autour de ces deux morts :

**Mort n°1 : elle n'est pas rentable.** Elle vend à perte, elle brûle du capital. → Chapitre 3 (rentabilité).

**Mort n°2 : elle n'a plus de trésorerie.** Elle est peut-être rentable sur le papier, mais elle ne peut pas payer son fournisseur mardi prochain. C'est la **cessation de paiements**, et ça tue beaucoup plus d'entreprises que le n°1. → Chapitres 1, 2, 4, 5, 6.

> **La phrase à retenir** (elle est dans ton poly, et elle résume tout) : *« La pérennité d'une entreprise repose sur sa rentabilité **et** sur sa capacité à générer de la trésorerie pour faire face à ses dettes. »*

Une entreprise peut être rentable et mourir. C'est même le cas classique de la **croissance mal maîtrisée** : les ventes explosent, donc les stocks et les créances clients explosent aussi, donc l'argent est immobilisé, donc la trésorerie s'effondre. Tu verras ce scénario **dans presque tous les cas du cours** (Hermès, LVMH…). Retiens-le, c'est le commentaire-type.

## 0.2 Le bilan : une photo

Le bilan, c'est une **photo à un instant T** (le 31/12/N). Deux colonnes qui font toujours le même total.

```
        ACTIF                      PASSIF
   « ce que je possède »      « d'où vient l'argent »
   « où est allé l'argent »   « à qui je le dois »
   
   = les EMPLOIS              = les RESSOURCES
```

**Règle d'or : ACTIF = PASSIF, toujours.** Chaque euro qui entre a une origine (passif) et une destination (actif).

### Le côté ACTIF, du plus « figé » au plus « liquide »

| Poste | Ce que c'est |
|---|---|
| **Immobilisations incorporelles** | Ce qui n'est pas palpable : fonds commercial, brevets, licences, frais d'établissement |
| **Immobilisations corporelles** | Terrains, constructions, machines (installations techniques), matériel |
| **Immobilisations financières** | Participations (actions d'autres sociétés), prêts accordés |
| **Stocks** | Matières premières, en-cours, produits finis, marchandises |
| **Créances clients** | Le client a acheté mais n'a pas encore payé. **C'est de l'argent qui te manque.** |
| **Créances diverses** | TVA déductible, avances, etc. |
| **VMP** | Valeurs mobilières de placement : SICAV, placements court terme |
| **Disponibilités** | Le cash sur le compte |
| **Charges constatées d'avance (CCA)** | Tu as payé en N une charge qui concerne N+1 (ex : loyer de janvier payé en décembre) |

### Le côté PASSIF, du plus « stable » au plus « exigible »

| Poste | Ce que c'est |
|---|---|
| **Capital** | Ce que les associés ont mis |
| **Primes d'émission** | Le supplément payé par les actionnaires lors d'une augmentation de capital |
| **Réserves** | Les bénéfices des années passées qu'on n'a pas distribués |
| **Report à nouveau** | Le reliquat de bénéfice (ou de perte, si négatif) non affecté |
| **Résultat de l'exercice** | Le bénéfice (ou la perte) de N |
| **Provisions pour risques et charges** | Une dette probable mais dont on ne connaît ni le montant exact ni la date |
| **Dettes financières** | Emprunts bancaires, emprunts obligataires. **Attention : contiennent souvent les CBC** |
| **Dettes fournisseurs** | Tu as acheté mais tu n'as pas encore payé. **C'est de l'argent que tu gardes.** |
| **Dettes fiscales et sociales** | TVA à payer, URSSAF, salaires du mois |
| **Produits constatés d'avance (PCA)** | Tu as encaissé en N un produit qui concerne N+1 |

### Les 3 colonnes BRUT / A&P / NET — LE point à ne jamais rater

```
BRUT  −  Amortissements & Provisions  =  NET
```

- **Brut** = le prix payé à l'origine (valeur d'acquisition).
- **A&P (ou A&D)** = ce qu'on a « effacé » comptablement, soit parce que ça s'use (**amortissement**), soit parce que ça a perdu de la valeur (**provision / dépréciation**).
- **Net** = la valeur comptable actuelle. On dit aussi **VNC** (valeur nette comptable).

> ⚠️ **PIÈGE MAJEUR, apprends-le par cœur :**
> - **Bilan fonctionnel → on travaille en BRUT**
> - **Bilan financier → on travaille en NET**
> - **Tableau de flux → variation du BFR en valeurs NETTES**
>
> Se tromper de colonne, c'est perdre l'exercice entier. On y revient au chapitre 1.

### Les concours bancaires courants (CBC)

Les CBC (= découvert bancaire) et les **soldes créditeurs de banque (SCB)** sont **écrits dans les dettes financières** au bilan comptable, avec une note de bas de page du type *« (1) dont concours bancaires courants : 1 900 »*.

**Il faut TOUJOURS les sortir des dettes financières** pour les mettre en trésorerie de passif. Pourquoi ? Parce qu'un découvert n'est pas un financement stable : la banque peut le couper du jour au lendemain. C'est de la trésorerie négative, pas une ressource durable.

**Cette note de bas de page est mise là exprès. Si tu l'oublies, tout ton bilan fonctionnel est faux.**

## 0.3 Le compte de résultat : un film

Le compte de résultat, c'est le **film de l'année** : tout ce qui s'est passé du 01/01/N au 31/12/N.

```
   CHARGES  (ce qui appauvrit)      PRODUITS  (ce qui enrichit)
   
   Charges d'exploitation           Produits d'exploitation
   Charges financières              Produits financiers
   Charges exceptionnelles          Produits exceptionnels
   Participation des salariés
   Impôt sur les bénéfices
   
   Résultat (si bénéfice)     ←→    Résultat (si perte)
```

**Astuce de lecture** : le résultat est placé du côté qui manque pour équilibrer.
- Résultat **écrit du côté CHARGES** → c'est un **BÉNÉFICE** (les produits étaient plus gros)
- Résultat **écrit du côté PRODUITS** → c'est une **PERTE** (les charges étaient plus grosses)

C'est exactement le cas dans le **CC1 2025-2026 partie I** : le résultat de 2 500 est du côté produits, donc **RNC = −2 500** (une perte). Beaucoup d'étudiants prennent +2 500 et se plantent sur toute la CAF.

### Les trois niveaux d'opérations

| Niveau | Contenu | Idée |
|---|---|---|
| **Exploitation** | Achats, ventes, salaires, loyers, impôts et taxes, DAP d'exploitation | Le métier de l'entreprise |
| **Financier** | Intérêts versés/reçus, différences de change, DAP financières | Comment elle est financée |
| **Exceptionnel** | Cessions d'immobilisations, amendes, opérations non récurrentes | Ce qui ne se reproduira pas |

### Le vocabulaire codé qu'il faut décrypter instantanément

| Sigle | Signification | Où | Encaissable / décaissable ? |
|---|---|---|---|
| **DAP** | Dotations aux amortissements et provisions | Charges | ❌ NON décaissable |
| **RAP** | Reprises sur amortissements et provisions | Produits | ❌ NON encaissable |
| **VCEAC / VNCEAC / VCIICFC** | Valeur comptable des éléments d'actif cédés | Charges exceptionnelles | ❌ NON décaissable |
| **PCEA / PCIICF** | Produit de cession des éléments d'actif | Produits exceptionnels | ✅ Encaissable, mais **pas de l'activité** |
| **EBE** | Excédent brut d'exploitation | Calculé | — |
| **CAF** | Capacité d'autofinancement | Calculée | — |

> **Note** : dans le CC1 2025-2026, ton prof note **VCIICFC** = *valeur comptable des immobilisations incorporelles, corporelles, financières cédées* = **VCEAC**, et **PCIICF** = le produit de cession correspondant = **PCEA**. Même chose, notation différente. Ne te laisse pas déstabiliser par le sigle.

### Les 4 charges/produits « fantômes »

C'est LE concept central du chapitre 2. Quatre postes du compte de résultat **ne correspondent à aucun mouvement d'argent** :

1. **DAP** — on constate l'usure d'une machine. Aucun euro ne sort.
2. **RAP** — on annule une dépréciation. Aucun euro n'entre.
3. **VCEAC** — on sort une machine du bilan à sa valeur nette. Aucun euro ne sort.
4. **PCEA** — l'argent entre vraiment, MAIS c'est le produit d'une **cession**, donc une opération d'**investissement**, pas d'**activité**.

Toute la logique de la CAF et du tableau de flux consiste à **neutraliser ces quatre-là**.

## 0.4 La variation des stocks : le piège de signe

C'est **le** piège le plus rentable pour un correcteur, et il est présent dans le TD **et** dans le CC1 2025-2026.

Il y a deux postes de nature opposée dans le compte de résultat :

### « Variation des stocks » (marchandises, matières premières) — côté CHARGES

```
Variation de stocks = Stock Initial − Stock Final
```

| Signe | Interprétation | Le stock… | Le BFRE… |
|---|---|---|---|
| **Positif (+)** | SI > SF | **diminue** ↓ | **diminue** ↓ (ce n'est PAS un besoin) |
| **Négatif (−)** | SI < SF | **augmente** ↑ | **augmente** ↑ (c'est un besoin) |

*Logique : la variation de stock est une charge. Si tu as consommé plus que tu n'as acheté, ton stock baisse et la charge augmente.*

### « Production stockée » (produits finis, en-cours) — côté PRODUITS

```
Production stockée = Stock Final − Stock Initial
```

| Signe | Interprétation | Le stock… | Le BFRE… |
|---|---|---|---|
| **Positif (+)** | SF > SI | **augmente** ↑ | **augmente** ↑ (c'est un besoin) |
| **Négatif (−)** | SF < SI | **diminue** ↓ | **diminue** ↓ |

### Le moyen mnémotechnique

> **Les deux postes ont des formules INVERSÉES.**
> - *Variation de stocks* (charge) : **SI − SF** → le signe est **contre-intuitif**
> - *Production stockée* (produit) : **SF − SI** → le signe est **intuitif**

**Comment ne jamais se tromper** : ne mémorise pas les 4 lignes. Retiens juste que **la production stockée est un PRODUIT, donc quand elle est positive, l'entreprise a fabriqué du stock → le stock monte → le BFRE monte.** Et que **la variation de stocks est une CHARGE, donc c'est l'inverse**.

### Application au CC1 2025-2026

Dans le compte de résultat du CC1 :
- Variation des stocks de marchandises : **+1 500** (côté charges) → SI > SF → stock ↓ → BFRE **−1 500**
- Variation des stocks de MP : **−3 000** (côté charges) → SI < SF → stock ↑ → BFRE **+3 000**
- Production stockée : **−4 500** (côté produits) → SF < SI → stock ↓ → BFRE **−4 500**

---

# CHAPITRE 1 — L'ANALYSE DU BILAN

## 1.1 À quoi ça sert ? (le contexte)

Le bilan comptable est fait pour l'administration fiscale et les commissaires aux comptes. Il est **inutilisable tel quel** pour un analyste financier.

Alors on le **retraite**, de deux façons différentes selon la question qu'on se pose :

| Approche | Question posée | Optique | Valeurs |
|---|---|---|---|
| **Bilan FONCTIONNEL** | *L'entreprise finance-t-elle correctement ses cycles ? Est-ce que ça tourne bien ?* | **Continuité d'exploitation** | **BRUTES** |
| **Bilan FINANCIER** | *Si l'entreprise s'arrêtait demain, pourrait-elle payer tout le monde ?* | **Risque / liquidation** | **NETTES** |

Le fonctionnel est celui du banquier qui accompagne la croissance. Le financier est celui du banquier qui a peur d'être remboursé.

## 1.2 Le bilan fonctionnel

### Le principe : classer par CYCLE

L'entreprise a trois cycles :
- **Cycle d'investissement** (long) : acheter des machines, les utiliser 10 ans
- **Cycle de financement** (long) : lever du capital, emprunter
- **Cycle d'exploitation** (court) : acheter → stocker → produire → vendre → encaisser

La règle fondatrice tient en une phrase :

> **Un besoin stable doit être financé par une ressource stable ; un besoin d'exploitation par une ressource d'exploitation.**

### Le tableau de construction (à savoir refaire de mémoire)

```
┌──────────────────────────────────┬──────────────────────────────────┐
│ EMPLOIS STABLES                  │ RESSOURCES STABLES               │
│ + Actif immobilisé BRUT (Total I)│ + Capitaux propres (Total I)     │
│ + Frais d'émission des emprunts  │ + AMORTISSEMENTS & PROVISIONS    │
│                                  │   (total de la colonne A&P)      │
│                                  │ + Provisions pour risques/charges│
│                                  │ + Dettes financières − CBC − SCB │
├──────────────────────────────────┼──────────────────────────────────┤
│ ACTIF CIRCULANT D'EXPLOITATION   │ DETTES D'EXPLOITATION            │
│ + Stocks (tous) BRUT             │ + Avances et acomptes REÇUS      │
│ + Avances et acomptes VERSÉS     │ + Dettes fournisseurs            │
│ + Créances clients BRUT          │ + Dettes fiscales et sociales    │
│ + Autres créances d'exploitation │ + Autres dettes d'exploitation   │
│ + Charges constatées d'avance    │ + Produits constatés d'avance    │
├──────────────────────────────────┼──────────────────────────────────┤
│ ACTIF CIRCULANT HORS EXPLOITAT.  │ DETTES HORS EXPLOITATION         │
│ + Créances diverses              │ + Dettes sur immobilisations     │
│ + VMP                            │ + Dettes d'impôt sur les bénéf.  │
│                                  │ + Autres dettes diverses         │
├──────────────────────────────────┼──────────────────────────────────┤
│ TRÉSORERIE D'ACTIF               │ TRÉSORERIE DE PASSIF             │
│ + Disponibilités                 │ + Concours bancaires courants    │
│                                  │ + Soldes créditeurs de banque    │
└──────────────────────────────────┴──────────────────────────────────┘
```

### Les 6 retraitements à ne jamais oublier

1. **Tout l'actif en BRUT.** On lit la colonne « Brut », pas « Net ».
2. **Les amortissements et provisions (colonne A&P) basculent au PASSIF**, dans les ressources stables. Logique : un amortissement, c'est de l'argent qui n'est pas sorti, donc c'est un financement interne.
3. **Les provisions pour risques et charges** (au passif) → ressources stables aussi.
4. **CBC et SCB sortent des dettes financières** → trésorerie de passif. *(Cherche la note de bas de bilan !)*
5. **Frais d'émission des emprunts** → ajoutés à l'actif immobilisé (emplois stables).
6. **CCA et PCA sont rattachés à l'EXPLOITATION.** (Sauf indication contraire explicite.)

> ⚠️ **Le piège des VMP.** Dans **ce cours**, au bilan fonctionnel, les VMP sont classées en **actif circulant hors exploitation**. MAIS dans le **tableau de flux** (chapitre 5), la trésorerie est définie comme *disponibilités + VMP − CBC*. **Ce sont deux définitions différentes de la trésorerie, dans deux chapitres différents.** Le poly le dit noir sur blanc : *« Cette définition diffère de celle du bilan fonctionnel. »* Ne mélange pas.

### Contrôle indispensable

**Total actif du bilan fonctionnel = Total passif = Total BRUT du bilan comptable.**

Si ça ne tombe pas, tu as oublié un poste. **Fais ce contrôle systématiquement en 10 secondes** : il te sauve l'exercice.

## 1.3 Les quatre agrégats fondamentaux

### Les formules

```
FRNG  = Ressources stables − Emplois stables
BFRE  = Actif circulant d'exploitation − Dettes d'exploitation
BFRHE = Actif circulant hors exploitation − Dettes hors exploitation
BFR   = BFRE + BFRHE
TN    = Trésorerie d'actif − Trésorerie de passif
```

**Et la relation qui les relie toutes :**

```
        ╔══════════════════════╗
        ║  TN = FRNG − BFR     ║
        ╚══════════════════════╝
```

### Ce que chacun VEUT DIRE (indispensable pour le commentaire)

**Le FRNG** = l'excédent de ressources durables une fois toutes les immobilisations financées. C'est le **matelas de sécurité long terme**.
- FRNG > 0 → les immobilisations sont bien financées par des ressources stables. ✅
- FRNG < 0 → l'entreprise finance ses machines avec du crédit court terme. 🚨 Très grave.

**Le BFR** = l'argent bloqué dans le cycle d'exploitation. Tu paies tes fournisseurs et tes salariés **avant** d'encaisser tes clients : ce décalage coûte de l'argent en permanence.
```
BFR  =  STOCKS  +  CRÉANCES CLIENTS  −  DETTES FOURNISSEURS
        (argent    (argent chez        (argent des autres
        immobilisé) les clients)        que tu gardes)
```
- BFR > 0 → **besoin** de financement (cas de l'industrie, du BTP, du luxe)
- BFR < 0 → **dégagement** = ressource ! (grande distribution, restauration : les clients paient comptant, les fournisseurs sont payés à 60 jours)

**La TN** = ce qui reste. **C'est une résultante, pas un objectif.** On ne « décide » pas de sa trésorerie : elle est la conséquence mécanique du FRNG et du BFR.

### Les 6 situations types (à connaître pour le commentaire)

| FRNG | BFR | TN | Diagnostic |
|---|---|---|---|
| **+** | **+** petit | **+** | 💚 Situation saine et confortable. Attention à la trésorerie oisive si elle est énorme. |
| **+** | **+** grand | **−** | 🟠 **Le cas le plus fréquent en examen** : croissance mal maîtrisée. Le FRNG ne suit pas le BFR → recours aux CBC. |
| **+** | **−** | **++** | 💚 Idéal (grande distribution). L'exploitation *finance* l'entreprise. |
| **−** | **+** | **−−** | 🔴 **Danger maximal.** Immobilisations financées à court terme ET besoin d'exploitation. Cessation de paiements probable. |
| **−** | **−** | **+** | 🟠 Situation fragile mais tenable (distribution). Tout repose sur le maintien du BFR négatif. |
| **+** | **+** | **≈ 0** | 🟡 Équilibre tendu, zéro marge de manœuvre. |

## 1.4 ★ TOUTES LES INCONNUES POSSIBLES SUR LA RELATION FONDAMENTALE

C'est ici que ton prof s'amuse. La relation `TN = FRNG − BFR` a **3 variables**, et le BFR se décompose en 2. Donc au moins **5 questions différentes** possibles.

### Inconnue 1 : la TN (le cas « normal »)
> *FRNG = 6 191 ; BFR = 6 203. Calculer la TN.*

**TN = 6 191 − 6 203 = −12**

### Inconnue 2 : le FRNG
> *Le BFR est de 6 203 et la trésorerie nette de −12. Calculer le FRNG.*

`TN = FRNG − BFR` → **FRNG = TN + BFR = −12 + 6 203 = 6 191**

### Inconnue 3 : le BFR
> *Le FRNG est de 6 191 et la trésorerie nette de −12. Calculer le BFR.*

**BFR = FRNG − TN = 6 191 − (−12) = 6 203**

⚠️ Attention au signe : moins par moins fait plus. Erreur classique.

### Inconnue 4 : le BFRHE
> *BFR = 6 203, BFRE = 6 161. Calculer le BFRHE.*

`BFR = BFRE + BFRHE` → **BFRHE = 6 203 − 6 161 = 42**

### Inconnue 5 : un poste du bilan
> *L'actif circulant d'exploitation brut s'élève à 7 141 k€ et le BFRE à 6 161 k€. Quel est le montant des dettes d'exploitation ?*

`BFRE = ACE − DE` → **DE = ACE − BFRE = 7 141 − 6 161 = 980**

### Inconnue 6 : les ressources stables
> *Actif immobilisé brut = 4 094 ; FRNG = 6 191. Calculer les ressources stables.*

**RS = FRNG + Emplois stables = 6 191 + 4 094 = 10 285**

### Inconnue 7 : ★ la variation de TN par DEUX méthodes
**C'est littéralement la question 3 du CC1 2025-2026.** Le prof veut vérifier que tu sais que les deux chemins mènent au même endroit.

```
Méthode 1 (par le haut du bilan) :  ΔTN = ΔFRNG − ΔBFR
Méthode 2 (par le bas du bilan)  :  ΔTN = ΔTrésorerie d'actif − ΔTrésorerie de passif
```

**Exemple chiffré (données réelles du CC1) :**
- Méthode 1 : ΔTN = 1 030 − 994 = **+36**
- Méthode 2 : ΔTN = (4 − 7) − (16 − 55) = (−3) − (−39) = **+36** ✅

> **Réflexe :** pour la méthode 2, ΔTP se **soustrait**. Si les CBC **baissent** (de 55 à 16), la trésorerie **s'améliore**. Un raisonnement en clair vaut mieux qu'une formule mal recopiée.

### Inconnue 8 : sens de variation à partir d'informations littéraires

C'est le format du **CC1 2025-2026 partie I**, où on ne te donne pas les bilans mais des phrases :

| Information | Effet sur le BFRE |
|---|---|
| « Le poste Clients a **augmenté** de 3 000 » | BFRE **+3 000** |
| « Le poste Clients a **diminué** de 3 000 » | BFRE **−3 000** |
| « Le poste Fournisseurs a **augmenté** de 1 500 » | BFRE **−1 500** |
| « Le poste Fournisseurs a **diminué** de 1 500 » | BFRE **+1 500** |
| « Les stocks ont **augmenté** de X » | BFRE **+X** |

> **Le raisonnement, pas la table** : *« Une créance client, c'est de l'argent qui n'est pas chez moi. Plus il y en a, plus j'ai besoin de financement. »* / *« Une dette fournisseur, c'est de l'argent des autres que je garde. Plus il y en a, moins j'ai besoin de financement. »*
>
> **ACTIF circulant ↑ → BFR ↑** &nbsp;&nbsp;|&nbsp;&nbsp; **DETTES circulantes ↑ → BFR ↓**

## 1.5 Les ratios de l'approche fonctionnelle

### Ratio de couverture des capitaux investis

```
Ratio = Ressources stables / (Immobilisations + BFRE)
```

**Interprétation :** doit tendre vers **100 %**. En pratique, **90 % est considéré comme un bon taux**. Il vérifie que le financement stable couvre non seulement les machines mais aussi le besoin d'exploitation permanent.

### Taux d'endettement

```
Taux d'endettement = Endettement TOTAL / Ressources propres (capitaux propres)
```

Dans le corrigé du cours : `(1 800 + 3 074 + 986 + 137) / 5 153 = 1,16` → « correct et acceptable ». Note bien qu'on prend **toutes les dettes** (financières + exploitation + hors exploitation + trésorerie passif), pas seulement les dettes financières.

### Capacité de remboursement

```
Dettes financières / CAF
```

**Un ratio de 3 signifie qu'il faut 3 ans de CAF pour rembourser toute la dette.** Au-delà de 3-4, les banquiers commencent à tiquer.

## 1.6 Le bilan financier

### Le principe : classer par ÉCHÉANCE

Ici on abandonne les cycles. On se demande : *si tout s'arrête, qui est payé, et dans quel ordre ?*

- **Actif** classé par **liquidité croissante** (capacité à se transformer en cash)
- **Passif** classé par **exigibilité croissante** (proximité de l'échéance)

```
┌────────────────────────┬───────────────────────────┐
│ ACTIF À PLUS D'1 AN    │ CAPITAUX PROPRES          │──┐
│ (en valeurs NETTES,    ├───────────────────────────┤  │ CAPITAUX
│  actif fictif déduit)  │ DETTES À PLUS D'1 AN      │──┘ PERMANENTS
├────────────────────────┼───────────────────────────┤
│ ACTIF À MOINS D'1 AN   │ DETTES À MOINS D'1 AN     │
└────────────────────────┴───────────────────────────┘
```

### Actif fictif : les « non-valeurs »

L'**actif fictif** = des charges qu'on a mises à l'actif pour les étaler, mais **qui n'ont aucune valeur de revente**. Si tu liquides l'entreprise, personne ne t'achètera tes « frais d'établissement ».

Liste à connaître :
- Frais d'établissement
- Frais de recherche et développement
- Frais d'émission des emprunts
- Primes de remboursement des obligations

**Traitement : on les élimine de l'actif ET on les retire des capitaux propres** (double soustraction, pour garder l'équilibre).

```
ACTIF NET = ACTIF RÉEL − DETTES
ACTIF NET = CAPITAUX PROPRES − ACTIF FICTIF
```

### Les 4 retraitements du bilan financier

1. **Actif fictif** : éliminé de l'actif **et** des capitaux propres.
2. **Reclassements d'échéance** : la part de l'actif immobilisé à moins d'1 an descend en bas ; la part de l'actif circulant à plus d'1 an monte en haut. *(Ces montants sont dans les notes de bas de bilan : « dont à moins d'un an : 100 », « dont à plus d'un an : 47 ».)*
3. **Dividendes à distribuer** : la part du résultat qui sera distribuée n'appartient plus à l'entreprise → **retirée des capitaux propres, ajoutée aux dettes à moins d'1 an**.
4. **Provisions pour risques et charges** :
   - Justifiées, échéance < 1 an → dettes à moins d'1 an
   - Justifiées, échéance > 1 an → dettes à plus d'1 an
   - **Sans objet réel (non justifiées)** → réintégrées aux capitaux propres

**Les CCA restent à l'actif réel ; les PCA sont traités comme des dettes.**

### Fonds de roulement financier — les deux formules

```
FRF = Capitaux permanents − Actif à plus d'un an
FRF = Actif à moins d'un an − Dettes à moins d'un an
```

**Les deux doivent donner exactement le même résultat.** C'est ton contrôle. Si l'énoncé dit « calculer par deux méthodes », c'est ça qu'il attend.

### Les ratios financiers — tableau complet

| Ratio | Formule | Norme | Interprétation |
|---|---|---|---|
| **Degré de liquidité** | Actif < 1 an / Actif réel total | selon secteur | Plus l'activité est capitalistique, plus il tend vers 0 |
| **Autonomie financière** | Capitaux propres / Dettes | **> 0,5** | Règle du tiers : CP = 1/3, DLT = 1/3, DCT = 1/3 |
| **Indépendance financière** | CP / Capitaux permanents | **≈ 0,5** | > 0,5 = correct |
| **Solvabilité générale** | Actif réel total / Dettes | **> 1** | Peut-elle rembourser TOUS ses créanciers ? |
| **Liquidité générale** | Actif < 1 an / Dettes < 1 an | **> 1** | Peut-elle tenir 1 an ? |
| **Liquidité réduite** | (Actif < 1 an − stocks) / Dettes < 1 an | **> 1** souhaitable | Mesure le poids des stocks (peu liquides) |
| **Liquidité immédiate** | (Trésorerie + VMP) / Dettes < 1 an | **toujours < 1** | Trop élevé = trésorerie pléthorique, argent qui dort |
| **Financement des investissements** | Capitaux permanents / Actif > 1 an | **> 1** | C'est le FRF exprimé en ratio |

> **Astuce mémo** : les 3 ratios de liquidité sont **emboîtés** — générale ⊃ réduite ⊃ immédiate. On enlève d'abord les stocks, puis les créances. Ils sont donc **forcément décroissants**. Si tu trouves l'inverse, tu t'es trompé.

## 1.7 Les erreurs qui coûtent le plus cher (chapitre 1)

| Erreur | Conséquence | Antidote |
|---|---|---|
| Prendre le NET au lieu du BRUT | Tout le bilan fonctionnel est faux | Souligne « Brut » au surligneur dès la lecture |
| Oublier de sortir les CBC | FRNG surestimé, TN fausse | Cherche systématiquement la note « (1) dont concours bancaires courants » |
| Oublier de basculer les A&P au passif | Le bilan ne s'équilibre pas | Contrôle Total actif = Total passif |
| Mettre les VMP en trésorerie au bilan fonctionnel | BFRHE faux | Bilan fonctionnel → VMP en ACHE. Tableau de flux → VMP en trésorerie |
| Classer les CCA en hors exploitation | BFRE et BFRHE faux | CCA et PCA = **exploitation** |
| Signe de ΔBFR mal interprété | Commentaire et ETE/ESOG faux | « Actif circulant ↑ = BFR ↑ » |

---

# CHAPITRE 2 — CAF, AUTOFINANCEMENT, ETE ET ESOG

## 2.1 À quoi ça sert ?

Le résultat comptable est un **mauvais indicateur de richesse réelle**, pour deux raisons :
1. Il contient des charges et produits **fictifs** (DAP, RAP, VCEAC).
2. Il contient des opérations **non récurrentes** (les cessions d'immobilisations).

La **CAF** répond à la question : *combien d'argent l'activité de l'entreprise a-t-elle réellement dégagé cette année ?* C'est la ressource interne, celle qui sert à :
- rémunérer les actionnaires (dividendes),
- financer les investissements,
- rembourser les emprunts.

Puis on affine encore :
- **L'ETE** répond à : *combien de trésorerie **réelle** l'exploitation a-t-elle générée ?* (la CAF ignore les décalages de paiement)
- **L'ESOG** généralise l'ETE à toute l'activité de gestion.

## 2.2 L'excédent brut d'exploitation (EBE)

### Définition

> **L'EBE = les produits d'exploitation ENCAISSABLES − les charges d'exploitation DÉCAISSABLES.**

C'est la richesse créée par le métier de base, **avant** toute politique d'amortissement, de financement et de fiscalité. C'est le meilleur indicateur pour **comparer deux entreprises** : il est indépendant de leur structure financière et de leurs choix comptables.

### Le calcul (tableau du cours)

```
    Ventes de marchandises
  + Production vendue (biens et services)
  + Production stockée                        ← attention au signe !
  + Production immobilisée
  + Subventions d'exploitation
  − Achats de marchandises
  − Variation des stocks de marchandises      ← attention au signe !
  − Achats de matières premières
  − Variation des stocks de matières premières
  − Autres achats et charges externes
  − Impôts, taxes et versements assimilés
  − Salaires et traitements
  − Charges de sécurité sociale et prévoyance
  ═══════════════════════════════════════════
  = EXCÉDENT BRUT D'EXPLOITATION
```

### Ce qui n'est PAS dans l'EBE (liste de vérification)

❌ Dotations aux amortissements et provisions (non décaissables)
❌ Reprises sur provisions (non encaissables)
❌ Autres produits / autres charges d'exploitation (ils entrent dans la CAF, pas dans l'EBE)
❌ Tout le financier, l'exceptionnel, la participation, l'impôt

> **Attention à la variation des stocks** : elle est **soustraite** dans la formule. Donc si la variation vaut **−3 000**, on fait `− (−3 000) = +3 000`. Erreur ultra-classique.

### Exemple appliqué (CC1 2025-2026)

```
  Ventes de marchandises              24 000
+ Production vendue                  164 000
+ Production stockée                 − 4 500
                                   = 183 500
− Achats de marchandises              14 000
− Variation stocks marchandises        1 500
− Achats de matières premières        78 000
− Variation stocks MP                − 3 000
− Impôts et taxes                      1 200
− Charges de personnel                76 800
                                   = 168 500
─────────────────────────────────────────────
  EBE = 183 500 − 168 500        =    15 000
```

## 2.3 La CAF — méthode ADDITIVE

### La formule

```
    RÉSULTAT NET COMPTABLE (RNC)
  + Valeur comptable des éléments d'actif cédés   (VCEAC)
  − Produits de cession d'éléments d'actif        (PCEA)
  + Charges non décaissables (DAP)
  − Produits non encaissables (RAP)
  ═══════════════════════════════════════════════
  = CAF
```

### Pourquoi ces quatre corrections ?

- **+ VCEAC** : c'était une charge, mais aucun euro n'est sorti → on l'annule en la rajoutant.
- **− PCEA** : c'était un produit encaissé, mais c'est de l'**investissement**, pas de l'activité → on l'enlève.
- **+ DAP** : charge calculée, aucun euro sorti → on l'annule.
- **− RAP** : produit calculé, aucun euro entré → on l'annule.

> **Mnémotechnique** : *« Je pars du résultat, et j'annule les quatre fantômes. »* Les charges fantômes se **rajoutent** (+), les produits fantômes se **retranchent** (−).

### Exemple appliqué (CC1 2025-2026)

```
  RNC (PERTE, donc négatif)          − 2 500
+ VCIICFC (= VCEAC)                  +   500
− PCIICF  (= PCEA)                   −   300
+ DAP                                + 15 300
− Reprises sur provisions            −  1 100
──────────────────────────────────────────────
  CAF                                = 11 900
```

**Remarque pédagogique importante** : le résultat est une **perte de 2 500** et pourtant la CAF est **positive de 11 900**. C'est parfaitement normal et c'est même une question de cours du TD :

> *« Peut-on se trouver dans le cas d'un résultat déficitaire et d'une CAF excédentaire ? »*
> **Réponse : OUI, si les dotations nettes de reprises sont supérieures à la perte de l'exercice.**

## 2.4 La CAF — méthode SOUSTRACTIVE

### La formule

```
    EXCÉDENT BRUT D'EXPLOITATION (EBE)
  + Autres produits d'exploitation          (sauf reprises)
  − Autres charges d'exploitation           (sauf dotations)
  + Produits financiers                     (sauf reprises)
  − Charges financières                     (sauf dotations)
  + Produits exceptionnels                  (sauf reprises ET sauf PCEA)
  − Charges exceptionnelles                 (sauf dotations ET sauf VCEAC)
  − Participation des salariés aux résultats
  − Impôts sur les bénéfices
  ═══════════════════════════════════════════════
  = CAF
```

### La règle unique qui gouverne tout

> **On part de l'EBE et on ajoute/retranche TOUT le reste du compte de résultat, SAUF les quatre fantômes (DAP, RAP, PCEA, VCEAC).**

Tu n'as donc qu'une seule chose à retenir : **balayer les lignes de haut en bas, et sauter les quatre fantômes.**

### Exemple appliqué (CC1 2025-2026)

```
  EBE                                  15 000
+ Produits financiers                 +   500
− Charges financières                 − 1 500
+ Produits exceptionnels              + 1 200   ← PCIICF (300) EXCLU
− Charges exceptionnelles             −   400   ← VCIICFC (500) EXCLU
− Participation des salariés          −   900
− Impôt sur les bénéfices             − 2 000
─────────────────────────────────────────────
  CAF                                = 11 900   ✅ identique à l'additive
```

> **Stratégie d'examen** : quand on te demande la CAF « par les deux méthodes », fais l'**additive en premier** (elle est plus courte et plus sûre), puis la soustractive. Si tu ne retrouves pas le même chiffre, l'erreur est presque toujours dans l'EBE (variation de stocks) ou dans un fantôme oublié dans l'exceptionnel.

## 2.5 ★ TOUTES LES INCONNUES POSSIBLES SUR LA CAF

### Inconnue 1 : la CAF (le cas normal)
Vu ci-dessus.

### Inconnue 2 : le résultat net
> *La CAF s'élève à 11 900. Les DAP sont de 15 300, les reprises de 1 100, la VCEAC de 500 et le PCEA de 300. Quel est le résultat net ?*

```
RNC = CAF − VCEAC + PCEA − DAP + RAP
RNC = 11 900 − 500 + 300 − 15 300 + 1 100 = − 2 500  (perte)
```

### Inconnue 3 : les dotations aux amortissements
> *La CAF est de 11 900, le résultat est une perte de 2 500, la VCEAC de 500, le PCEA de 300, les reprises de 1 100. Calculer les DAP.*

```
DAP = CAF − RNC − VCEAC + PCEA + RAP
DAP = 11 900 − (−2 500) − 500 + 300 + 1 100 = 15 300
```

### Inconnue 4 : l'EBE à partir de la CAF
> *La CAF est de 11 900. Produits financiers 500, charges financières 1 500, produits exceptionnels 1 200, charges exceptionnelles 400, participation 900, IS 2 000. Calculer l'EBE.*

```
EBE = CAF − 500 + 1 500 − 1 200 + 400 + 900 + 2 000 = 15 000
```

### Inconnue 5 : ★ les dividendes versés
**C'est l'inconnue la plus fréquente et la plus rentable de tout le programme.** Elle sert au chapitre 2 (autofinancement) ET au chapitre 5 (tableau de flux).

Quand l'énoncé ne donne pas les dividendes, on les retrouve **par la reconstitution de l'affectation du résultat N−1** :

```
╔═══════════════════════════════════════════════════════════════╗
║  Dividendes versés en N =  Résultat N−1                       ║
║                          − Variation des réserves (N − N−1)   ║
║                          − Variation du report à nouveau      ║
╚═══════════════════════════════════════════════════════════════╝
```

**Logique** : le bénéfice de N−1 n'a que trois destinations possibles → il va en réserves, en report à nouveau, ou il est distribué. Ce qui n'est pas dans les deux premières cases a été distribué.

> ⚠️ **« Réserves » signifie TOUTES les réserves** : réserve légale + réserves statutaires + réserves réglementées + autres réserves. Ne prends pas qu'une ligne.

**Exemple A (cas Décorex du TD)** :
Résultat N−1 = 297 ; réserve légale 163 → 178 ; autres réserves 1 649 → 1 767.
```
Dividendes = 297 − (178 − 163) − (1 767 − 1 649) = 297 − 15 − 118 = 164
```

**Exemple B (cas Hermès du cours)** : « La moitié du résultat N−1 a été distribuée », résultat N−1 = 40 → **dividendes = 20**. *(Ici c'est donné en clair, mais on peut vérifier : réserve légale 70 → 90, soit +20 ; 40 − 20 = 20 ✅)*

**Exemple C (CC2 2025-2026)** : Résultat N−1 = 24 000 ; réserves 160 800 → 160 800 (inchangées) ; RAN 7 200 → 7 200 (inchangé).
```
Dividendes = 24 000 − 0 − 0 = 24 000   (tout le résultat a été distribué)
```

### Inconnue 6 : le résultat N−1 à partir des dividendes
> *Les dividendes versés en N sont de 840. Les réserves ont augmenté de 960. Quel était le résultat N−1 ?*

```
Résultat N−1 = Dividendes + Δréserves + ΔRAN = 840 + 960 = 1 800
```

## 2.6 L'autofinancement

```
AUTOFINANCEMENT BRUT = CAF − Dividendes distribués
AUTOFINANCEMENT NET  = Autofinancement brut − Dotations nettes de reprises
```

où `Dotations nettes de reprises = DAP − RAP`.

**Interprétation :**
- L'**autofinancement brut** = ce qui reste réellement dans l'entreprise après avoir payé les actionnaires.
- L'**autofinancement de maintien** = la part qui sert juste à remplacer l'outil de production usé (≈ les dotations).
- L'**autofinancement net** = ce qui permet de **grandir**, une fois le maintien assuré.

**Exemple (cas Hermès)** : CAF = 153, dividendes = 20, DAP = 130, RAP = 20.
```
AF brut = 153 − 20 = 133
AF net  = 133 − (130 − 20) = 133 − 110 = 23
```

### Avantages / inconvénients de l'autofinancement (question de cours)

| Avantages | Inconvénients |
|---|---|
| Augmente les capitaux propres → améliore l'autonomie financière et permet d'emprunter ensuite en gardant un bon équilibre | Facteur de hausse des prix (on augmente le prix de vente pour alimenter la CAF) |
| Évite les charges d'intérêts | Diminution des dividendes → baisse du cours de l'action pour les sociétés cotées |
| Permet de régulariser les dividendes par la variation des réserves | Risque d'investissements calibrés sur les possibilités d'autofinancement plutôt que sur les besoins réels (trop ou trop peu) |

## 2.7 ETE et ESOG

### Les formules

```
╔══════════════════════════════════╗
║  ETE  = EBE − VARIATION DU BFRE  ║
║  ESOG = CAF − VARIATION DU BFR   ║
╚══════════════════════════════════╝
```

### La différence EBE / ETE (question de cours du TD, tombe souvent)

> **L'EBE** est un **niveau de résultat** lié à l'activité. En raison des décalages de paiement (crédit client, crédit fournisseur, stockage), **l'EBE n'est pas immédiatement encaissé**.
>
> **L'ETE** part de l'EBE et **tient compte de la variation du BFRE**. C'est un **surplus de TRÉSORERIE** lié à l'activité, pas un résultat.

**Image** : l'EBE, c'est ce que tu as *gagné*. L'ETE, c'est ce que tu as *dans la poche*.

### Pourquoi l'ETE est-il l'indicateur le plus précieux ?

Le poly est explicite : *« Il permet de détecter de manière précoce les difficultés des entreprises : c'est l'indicateur le plus sensible aux variations de l'activité. »*

Une entreprise en croissance rapide a un EBE qui monte **et** un BFRE qui explose. L'ETE, lui, peut devenir négatif alors que tout a l'air d'aller bien. C'est le signal d'alarme.

### Différence ETE / ESOG

| | Périmètre | Formule |
|---|---|---|
| **ETE** | Exploitation seule | EBE − ΔBFRE |
| **ESOG** | Toute la gestion (exploitation + financier + exceptionnel) | CAF − ΔBFR |

L'ESOG est *« le flux de liquidités réellement disponible pour financer d'autres types d'opérations »* (investissement, financement).

### Exemple appliqué (CC1 2025-2026)

ΔBFRE = **−4 500** (le BFRE a **diminué**, c'est donc une **libération** de trésorerie), ΔBFR = **−9 000**.

```
ETE  = EBE − ΔBFRE = 15 000 − (−4 500) = 19 500
ESOG = CAF − ΔBFR  = 11 900 − (−9 000) = 20 900
```

> ⚠️ **Le double signe négatif.** Quand le BFR **diminue**, la trésorerie **s'améliore**, donc l'ETE est **supérieur** à l'EBE. Beaucoup d'étudiants font `15 000 − 4 500 = 10 500` : c'est faux, et le correcteur voit immédiatement l'incompréhension.

## 2.8 ★ TOUTES LES INCONNUES POSSIBLES SUR ETE / ESOG

### Inconnue 1 : l'ETE
`ETE = EBE − ΔBFRE` → cas normal.

### Inconnue 2 : la variation du BFRE
> *L'EBE est de 15 000 et l'ETE de 19 500. Calculer la variation du BFRE.*
```
ΔBFRE = EBE − ETE = 15 000 − 19 500 = − 4 500
```

### Inconnue 3 : l'EBE
> *L'ETE est de 19 500 et le BFRE a diminué de 4 500. Calculer l'EBE.*
```
EBE = ETE + ΔBFRE = 19 500 + (−4 500) = 15 000
```

### Inconnue 4 : la variation du BFR (via l'ESOG)
> *La CAF est de 11 900 et l'ESOG de 20 900.*
```
ΔBFR = CAF − ESOG = 11 900 − 20 900 = − 9 000
```

### Inconnue 5 : le BFRHE
> *ΔBFR = −9 000, ΔBFRE = −4 500.*
```
ΔBFRHE = −9 000 − (−4 500) = − 4 500
```

## 2.9 Le tableau « Origine et utilisation du FRNG »

Ce tableau apparaît dans le cours (cas Hermès), dans le TD **et** dans le cas LVMH Synthèse. **C'est un candidat très sérieux au rattrapage.**

### La structure

```
┌──────────────────────────────────┬──────────────────────────────────┐
│           EMPLOIS                │          RESSOURCES              │
├──────────────────────────────────┼──────────────────────────────────┤
│ Dividendes versés                │ CAF                              │
│ Acquisitions d'immobilisations   │ Cessions d'immobilisations (PCEA)│
│ Frais d'émission des emprunts    │ Émission d'emprunts              │
│ Remboursement d'emprunts         │ Augmentation de capital          │
├──────────────────────────────────┼──────────────────────────────────┤
│ TOTAL EMPLOIS                    │ TOTAL RESSOURCES                 │
└──────────────────────────────────┴──────────────────────────────────┘

        RESSOURCES − EMPLOIS = VARIATION DU FRNG
```

### Exemple (cas LVMH Synthèse)

| Emplois | | Ressources | |
|---|---|---|---|
| Dividendes | 840 | CAF | 21 430 |
| Acquisition immobilisations | 21 400 | Cession d'immobilisations | 1 800 |
| Frais d'émission des emprunts | 300 | Émission d'emprunt | 500 |
| Remboursement d'emprunt | 400 | Augmentation de capital | 6 000 |
| **Total** | **22 940** | **Total** | **29 730** |

→ **ΔFRNG = 29 730 − 22 940 = + 6 790** ✅ (identique au calcul par les masses du bilan)

### ★ Inconnue classique : retrouver un poste par différence

C'est **exactement** ce que fait le TD : *« On sait pour les 20k, donc on déduit pour l'acquisition d'immo. »*

> *La CAF est de 19 250, les cessions de 5 000, l'émission d'emprunt de 1 500, les dividendes de 6 250. La variation du FRNG est de +5 750. Quel est le montant des immobilisations acquises ?*

```
Ressources = 19 250 + 5 000 + 1 500 + 0 = 25 750
Emplois    = Ressources − ΔFRNG = 25 750 − 5 750 = 20 000
Acquisitions = 20 000 − 6 250 (dividendes) − 0 − 0 = 13 750
```

### Autres inconnues déductibles

| Poste cherché | Méthode |
|---|---|
| **Émission d'emprunts** | `DF fin = DF début + émissions − remboursements` → isole les émissions |
| **Remboursement d'emprunts** | Même équation, isole les remboursements |
| **Augmentation de capital** | `Δcapital + Δprimes d'émission` |
| **Acquisitions d'immobilisations** | Colonne « Augmentations » du tableau des immobilisations |
| **Cessions** | Le PCEA du compte de résultat |

> **L'outil universel : le petit tableau de mouvement.** Pour n'importe quel poste, écris :
> ```
> Valeur début  +  Augmentations  −  Diminutions  =  Valeur fin
> ```
> Tu connais trois des quatre → tu déduis la quatrième. C'est le couteau suisse du chapitre 2 et du chapitre 5.

---

# CHAPITRE 3 — LA RENTABILITÉ ET LE RISQUE

## 3.1 À quoi ça sert ?

Deux personnes différentes regardent l'entreprise avec deux questions différentes :

| Qui ? | Question | Indicateur |
|---|---|---|
| **Le dirigeant, le gestionnaire** | *Mon outil économique est-il efficace ?* | **Rentabilité économique (Re)** |
| **L'actionnaire, l'investisseur** | *Mon argent rapporte-t-il ?* | **Rentabilité financière (Rf)** |

Et la question qui les relie : **est-ce que s'endetter enrichit l'actionnaire ?** → c'est l'**effet de levier**.

## 3.2 La rentabilité économique (Re)

### Les formules

```
Re avant impôts = Résultat économique / Actif économique
Re après impôts = Re avant impôts × (1 − s)
```
où **s** = taux d'impôt sur les bénéfices.

### L'actif économique (= capitaux investis) — DEUX formules équivalentes

```
Capitaux investis = Capitaux propres HORS RÉSULTAT + Dettes financières (hors CBC/SCB)
Capitaux investis = Immobilisations + BFRE
```

> **Pourquoi « hors résultat » ?** Parce que le résultat de l'année est justement ce qu'on cherche à mesurer. L'inclure dans le dénominateur, c'est mesurer le rendement d'un capital qui inclut déjà le rendement. **L'énoncé le précise presque toujours ; lis-le.**

### ★ Quel « résultat économique » prendre ? (question à 3 points)

C'est **le** point délicat du chapitre, et le CC1 2025-2026 le teste directement.

Le résultat économique est *« le revenu procuré par l'actif économique, calculé avant impôt, avant intérêts et avant impôt »*. Concrètement, deux formulations :

| Formulation | Formule | Quand l'utiliser |
|---|---|---|
| **A** | Résultat d'exploitation | Quand l'énoncé le dit explicitement (*« l'entreprise retient comme résultat économique le résultat d'exploitation »*) |
| **B** | **RNC + IS + charges d'intérêts** (= résultat avant intérêts et impôts, RAII) | **Par défaut**, et **obligatoirement** si la question demande de vérifier par l'effet de levier |

> **La règle de sécurité absolue** : si la question 5 dit *« Retrouver la rentabilité financière par la formule de l'effet de levier »*, alors la formule **doit** boucler. Elle ne boucle qu'avec **B**. Utilise B.
>
> Quand le compte de résultat n'a ni financier ni exceptionnel (hors intérêts), A = B et le problème ne se pose pas. C'est le cas du « Cas 2017 » du cours : `96 750 + 32 250 + 56 000 = 185 000` = le résultat d'exploitation exactement.

### ★ Le taux d'impôt (s) — inconnue fréquente

**Le CC1 2025-2026 pose littéralement la question** : *« Calculer le taux d'impôts sur les bénéfices en retrouvant le lien entre le résultat avant impôts, l'impôt sur les bénéfices et le résultat après impôts. »*

```
Résultat AVANT impôts = Résultat APRÈS impôts + Impôt sur les bénéfices

        ╔══════════════════════════════════════════════════════╗
        ║  s = IS / (IS + Résultat après impôts)               ║
        ║  s = IS / Résultat avant impôts                      ║
        ╚══════════════════════════════════════════════════════╝
```

**Exemple (Cas 2017 du cours)** : IS = 32 250, résultat = 96 750.
```
s = 32 250 / (32 250 + 96 750) = 32 250 / 129 000 = 25 %
```

**Exemple (Cas 2010 du TD)** : IS = 4 256, résultat = 10 944.
```
s = 4 256 / (4 256 + 10 944) = 4 256 / 15 200 = 28 %
```

> ⚠️ **Cas particulier de la perte.** Dans le CC1 2025-2026, l'IS est **nul** et le résultat est une perte de 8 700. Donc `s = 0 / (−8 700) = 0 %`. C'est logique : **on ne paie pas d'impôt sur une perte.** La conséquence est que `Re après impôts = Re avant impôts`. Écris-le explicitement, c'est un point.

## 3.3 La rentabilité financière (Rf)

```
╔════════════════════════════════════════════════════════╗
║  Rf après impôts = RNC / Capitaux propres HORS RÉSULTAT ║
╚════════════════════════════════════════════════════════╝
```

C'est le **ROE** (return on equity). *« C'est le principal indicateur des performances de l'entreprise »* pour les apporteurs de capitaux.

**Elle se calcule généralement APRÈS impôts**, parce que l'actionnaire touche ce qui reste une fois le fisc payé.

## 3.4 L'effet de levier — le cœur du chapitre

### L'idée en une phrase

> **Si l'argent emprunté rapporte plus qu'il ne coûte, l'écart va dans la poche de l'actionnaire.**

L'entreprise emprunte à 5 % et fait fructifier cet argent à 12 % dans son activité. Les 7 points d'écart ne vont ni à la banque (payée 5 %) ni au fisc : ils **augmentent la rentabilité des capitaux propres**.

### La formule maîtresse

```
╔════════════════════════════════════════════════════════════════════╗
║                                                                    ║
║   Rf  =   Re × (1 − s)      +      (Re − i) × (D/CP) × (1 − s)     ║
║          ─────────────             ────────────────────────────    ║
║          Rentabilité éco              EFFET DE LEVIER              ║
║          après impôt                                               ║
║                                                                    ║
╚════════════════════════════════════════════════════════════════════╝
```

Et donc, par différence :

```
Effet de levier = Rf − Re après impôts
Effet de levier = (Re − i) × (D/CP) × (1 − s)
```

### Décryptage des trois facteurs

| Facteur | Nom | Rôle |
|---|---|---|
| **(Re − i)** | Le **différentiel** | Le moteur. S'il est positif, le levier joue. S'il est négatif, c'est la massue. |
| **(D/CP)** | Le **bras de levier** | L'amplificateur. Plus tu es endetté, plus l'effet (bon ou mauvais) est fort. |
| **(1 − s)** | Le **frein fiscal** | Le fisc prend sa part de l'effet. |

### Les notations

| Symbole | Signification | Comment on le calcule |
|---|---|---|
| **Re** | Rentabilité économique **avant impôt** | Résultat économique / Actif économique |
| **i** | Coût de la dette | **Charges d'intérêts / Dettes financières** |
| **D** | Dettes financières | Hors CBC |
| **CP** | Capitaux propres | Hors résultat |
| **s** | Taux d'impôt | IS / Résultat avant impôt |

### Les trois configurations (question de commentaire garantie)

| Situation | Conséquence | Nom |
|---|---|---|
| **Re > i** | L'endettement **augmente** la Rf. Rf > Re après impôts. | ✅ **Effet de LEVIER** (positif) |
| **Re = i** | Aucun effet. *« L'argent emprunté coûte autant qu'il ne rapporte. »* | ⚪ Effet **nul** |
| **Re < i** | L'endettement **détruit** la Rf. Rf < Re après impôts. | 🔴 **Effet de MASSUE** |

**Deux cas où l'effet de levier est nul :**
1. **D/CP = 0** → aucun endettement, donc rien à amplifier.
2. **Re = i** → aucun différentiel à amplifier.

### La limite à l'endettement (question de cours)

> *« Tant que Re > i, plus l'entreprise s'endette, plus elle améliore sa rentabilité financière — jusqu'à un seuil où le prêteur n'accepte plus un endettement excessif par rapport aux capitaux propres et élève son taux d'intérêt au-dessus du taux de rentabilité économique. »*
>
> **La règle prudentielle : les dettes financières ne doivent pas dépasser les capitaux propres (D/CP ≤ 1).**

### Le risque financier

> **Le risque financier = l'impact de l'endettement sur la rentabilité des capitaux propres.**
>
> - Financement par capitaux propres → seul le **risque d'exploitation** existe.
> - Financement par emprunt → les charges d'intérêts sont assimilées à des **charges fixes**, elles majorent les charges de structure, **le levier opérationnel augmente et le risque augmente aussi**. Le risque financier **s'ajoute** au risque d'exploitation.

C'est exactement ce que montre le Cas 2010 du TD : quand le CA baisse de 10 %, l'entreprise A (non endettée) voit sa Rf passer de 10,7 % à 9,1 % ; l'entreprise B (endettée) la voit passer de 13,2 % à 9,1 %. **La chute est bien plus violente chez B.**

## 3.5 ★ TOUTES LES INCONNUES POSSIBLES SUR L'EFFET DE LEVIER

La formule contient **5 variables** (Rf, Re, i, D/CP, s). Ton prof peut donc poser **5 questions différentes**. Les voici toutes, avec l'algèbre.

*Données de base pour les exemples : Re = 14,9 % ; i = 7,2 % ; D = 32 000 ; CP = 70 200 ; s = 28 %.*

### ▸ Inconnue 1 : Rf (cas normal)
```
Rf = Re(1−s) + (Re − i)(D/CP)(1−s)
Rf = 14,9 % × 0,72 + (14,9 % − 7,2 %) × (32 000/70 200) × 0,72
Rf = 10,73 % + 7,7 % × 0,4558 × 0,72 = 10,73 % + 2,53 % = 13,2 %
```

### ▸ Inconnue 2 : i (le coût de la dette)
```
             Rf − Re(1−s)
(Re − i) = ─────────────────      →      i = Re − [ (Rf − Re(1−s)) / ((D/CP)(1−s)) ]
           (D/CP) × (1−s)
```
> *Exemple : Rf = 13,2 %, Re = 14,9 %, D/CP = 0,4558, s = 28 %. Calculer i.*
```
(13,2 % − 10,73 %) / (0,4558 × 0,72) = 2,47 % / 0,3282 = 7,53 %
i = 14,9 % − 7,53 % ≈ 7,4 %      (≈ 7,2 % aux arrondis près)
```
**Vérification directe** : `i = charges d'intérêts / dettes financières = 2 300 / 32 000 = 7,2 %` ✅

### ▸ Inconnue 3 : le levier D/CP
```
D           Rf − Re(1−s)
── =  ───────────────────────
CP      (Re − i) × (1 − s)
```
> *Exemple : Rf = 13,2 %, Re = 14,9 %, i = 7,2 %, s = 28 %. Quel est le rapport D/CP ?*
```
D/CP = (13,2 % − 10,73 %) / (7,7 % × 0,72) = 2,47 % / 5,544 % = 0,4455 ≈ 0,45
```

### ▸ Inconnue 4 : Re (la rentabilité économique)
Attention : Re apparaît **deux fois**. Il faut développer et factoriser.
```
Rf = Re(1−s) + (Re − i)(D/CP)(1−s)
Rf = (1−s) × [ Re + (Re − i)(D/CP) ]
Rf/(1−s) = Re × (1 + D/CP) − i × (D/CP)

              Rf/(1−s) + i × (D/CP)
        Re = ───────────────────────
                   1 + D/CP
```
> *Exemple : Rf = 13,2 %, i = 7,2 %, D/CP = 0,4558, s = 28 %. Calculer Re.*
```
Re = (13,2 %/0,72 + 7,2 % × 0,4558) / (1 + 0,4558)
Re = (18,33 % + 3,28 %) / 1,4558 = 21,61 % / 1,4558 = 14,85 %  ≈ 14,9 %  ✅
```

### ▸ Inconnue 5 : s (le taux d'impôt)
```
Rf = (1−s) × [ Re + (Re − i)(D/CP) ]

                          Rf
        (1 − s) = ─────────────────────────
                  Re + (Re − i) × (D/CP)
```
> *Exemple : Rf = 13,2 %, Re = 14,9 %, i = 7,2 %, D/CP = 0,4558.*
```
(1−s) = 13,2 % / (14,9 % + 7,7 % × 0,4558) = 13,2 % / 18,41 % = 0,717
s = 28,3 %  ≈ 28 %  ✅
```
**Vérification directe** : `s = IS / (IS + RNC) = 3 612 / (3 612 + 9 288) = 28 %` ✅

### ▸ Inconnue 6 : Re après impôts à partir de Re avant impôts (et réciproquement)
```
Re après = Re avant × (1 − s)          →          Re avant = Re après / (1 − s)
```
> *Exemple : Re après impôts = 10,7 %, s = 28 %. Calculer Re avant impôts.*
```
Re avant = 10,7 % / 0,72 = 14,9 %
```

### ▸ Inconnue 7 : les capitaux propres ou les dettes financières
> *L'actif économique est de 102 200 et les dettes financières de 32 000. Quels sont les capitaux propres ?*
```
CP = Actif économique − D = 102 200 − 32 000 = 70 200
```

### ▸ Inconnue 8 : les charges d'intérêts
> *Le coût de la dette est de 7,2 % et les dettes financières de 32 000.*
```
Charges d'intérêts = i × D = 7,2 % × 32 000 = 2 304
```

## 3.6 Le risque d'exploitation (ou risque économique)

### Le compte de résultat différentiel

C'est le point de départ. Il faut savoir le présenter :

```
        Chiffre d'affaires                            100 %
      − Charges VARIABLES                              
      ─────────────────────────────
      = MARGE SUR COÛTS VARIABLES  (M/CV)             taux de MCV
      − Charges FIXES
      ─────────────────────────────
      = RÉSULTAT D'EXPLOITATION
```

### Les 4 indicateurs

```
Taux de MCV          = M/CV / CA = (CA − CV) / CA

Seuil de rentabilité = Charges fixes / Taux de MCV

Marge de sécurité    = CA − Seuil de rentabilité

Indice de sécurité   = Marge de sécurité / CA = (CA − SR) / CA
```

**Le seuil de rentabilité (SR)** = le chiffre d'affaires à partir duquel le résultat devient positif. C'est le CA « critique ».

**L'indice de sécurité** de 10 % signifie : *si le CA baisse de plus de 10 %, l'entreprise devient déficitaire.*

**Plus le SR est élevé (proche du CA), plus le risque d'exploitation est grand.**

### Le levier opérationnel (LO)

> Le levier opérationnel mesure la **sensibilité du résultat d'exploitation aux variations du chiffre d'affaires**.

**Trois formules équivalentes :**
```
LO = Marge sur coûts variables / Résultat d'exploitation
LO = 1 / Indice de sécurité
LO = Variation du RE en % / Variation du CA en %
```

**Interprétation** : *un LO de 5 signifie que si le CA varie de 1 %, le résultat d'exploitation varie de 5 %* — **dans les deux sens**. C'est une opportunité en croissance et un danger en récession.

### Le lien structure de coûts → risque

> **Beaucoup de charges FIXES → LO élevé → risque d'exploitation élevé.**

C'est le message du Cas 2010 : A (CF = 7 300) a un LO de 1,48 ; B (CF = 25 400) a un LO de 2,67. **B est bien plus risquée** alors qu'elles ont le même CA et la même rentabilité économique.

### Comment réduire le risque d'exploitation (question de cours)

- **Réduire les charges fixes** : sous-traiter une partie de la production, recourir à l'intérim, louer plutôt qu'acheter, gagner en flexibilité industrielle
- **Augmenter le taux de M/CV** : améliorer les marges, réduire les coûts variables unitaires
- Les deux abaissent le seuil de rentabilité
- Diversifier l'activité, stabiliser les revenus

> **Nuance à écrire dans le commentaire** (le corrigé du TD la mentionne) : *« Cela reste très théorique et difficile à mettre en œuvre dans la pratique. »* Ce genre de recul est apprécié.

## 3.7 ★ TOUTES LES INCONNUES POSSIBLES SUR LE RISQUE D'EXPLOITATION

*Données : CA = 1 825 000 ; CV = 900 000 ; CF = 740 000.*
*→ M/CV = 925 000 ; taux de MCV = 50,68 % ; RE = 185 000 ; SR = 1 460 317 ; MS = 364 683 ; indice = 20 % ; LO = 5.*

| Inconnue | Formule | Exemple |
|---|---|---|
| **Seuil de rentabilité** | SR = CF / taux MCV | 740 000 / 0,5068 = **1 460 317** |
| **Charges fixes** | CF = SR × taux MCV | 1 460 317 × 0,5068 = **740 000** |
| **Taux de MCV** | taux = CF / SR | 740 000 / 1 460 317 = **50,68 %** |
| **Charges variables** | CV = CA × (1 − taux MCV) | 1 825 000 × 0,4932 = **900 000** |
| **Résultat d'exploitation** | RE = CA × taux MCV − CF | 925 000 − 740 000 = **185 000** |
| **CA nécessaire pour un résultat cible R** | CA = (CF + R) / taux MCV | pour R = 300 000 : (740 000+300 000)/0,5068 = **2 052 093** |
| **Indice de sécurité** | IS = 1 / LO | 1/5 = **20 %** |
| **Levier opérationnel** | LO = M/CV / RE | 925 000/185 000 = **5** |
| **Variation du RE** | Δ%RE = LO × Δ%CA | CA −10 % → RE **−50 %** |
| **Variation du CA** | Δ%CA = Δ%RE / LO | RE −30 % → CA **−6 %** |
| **Point mort (en date)** | (SR / CA) × 360 jours | (1 460 317/1 825 000)×360 = **288 j** ≈ 18 octobre |

## 3.8 La stratégie de réponse type sur un exercice de rentabilité

Face à un exercice de rentabilité, déroule **toujours** ce plan, dans cet ordre. Il te fait gagner du temps et t'évite les erreurs en chaîne :

```
1. Résultat avant impôts = RNC + IS
2. s = IS / Résultat avant impôts
3. Résultat économique = RNC + IS + charges d'intérêts     (= RAII)
4. Actif économique = CP hors résultat + Dettes financières
5. Re avant impôts = (3) / (4)
6. Re après impôts = (5) × (1 − s)
7. Rf = RNC / CP hors résultat
8. i = charges d'intérêts / Dettes financières
9. Vérification : Rf = Re(1−s) + (Re − i)(D/CP)(1−s)      ← DOIT tomber juste
10. Commentaire : Re vs i → levier ou massue ? Quelle limite ?
```

Si l'étape 9 ne tombe pas juste, reviens à l'étape 3 : c'est presque toujours le résultat économique qui est mal choisi.

---

# CHAPITRE 4 — LE BFR NORMATIF

## 4.1 À quoi ça sert ?

Le BFR calculé au chapitre 1 (à partir du bilan) est une **photo à un instant T**. C'est une **méthode statique**. Il a deux défauts majeurs :
- Il dépend de la date de clôture (une entreprise saisonnière clôturant en janvier n'aura pas le même BFR qu'en juillet).
- Il ne dit **rien** sur ce qui se passera l'année prochaine.

Le **BFR normatif** est une **méthode dynamique**. Il exprime le besoin de financement en **nombre de jours de chiffre d'affaires hors taxes**, ce qui le rend :
- **prévisionnel** : si je connais mon CA prévisionnel, je connais mon BFR prévisionnel
- **comparable** : « 120 jours contre 90 en moyenne dans le secteur »
- **actionnable** : je vois exactement quel poste est responsable

> **Le mot « normatif » vient de « norme »** : c'est le BFR correspondant aux **conditions normales d'exploitation** (durées de stockage habituelles, délais de crédit contractuels). Si ces normes sont respectées, la **seule cause de variation du BFRE est le niveau d'activité**.

### La relation de proportionnalité de base

```
BFRE prévisionnel = (BFRE / CAHT) × CA prévisionnel
```

## 4.2 Le principe de conversion — l'équation à comprendre

Toute la méthode tient dans cette décomposition :

```
╔═══════════════════════════════════════════════════════════════════════╗
║  Montant du poste  =  Durée de stockage × Ratio de structure × CA/360 ║
║        au bilan             (DS)                (RS)                  ║
╚═══════════════════════════════════════════════════════════════════════╝
```

Développée :

```
                Valeur moyenne du poste × 360     Valeur annuelle du poste     CA annuel
Montant  =  ──────────────────────────────  ×  ───────────────────────────  ×  ─────────
                 Valeur annuelle du poste            CA annuel HT                 360
```

> **★ Observation capitale (elle sauve beaucoup d'exercices) :**
> Dans le produit **DS × RS**, la « valeur annuelle du poste » **se simplifie**. Donc :
>
> ```
> DS × RS  =  (Valeur moyenne du poste × 360) / CAHT
> ```
>
> **Conséquence pratique** : si tu hésites sur la base de coût à utiliser (coût d'achat ? coût de production ? avec ou sans amortissements ?), **le nombre de jours final est le même**, tant que tu utilises **la même base au numérateur du DS et au numérateur du RS**. Ça te donne un **contrôle infaillible** de tes calculs, et ça désamorce les énoncés ambigus.

## 4.3 La durée de stockage (DS)

### La formule générale

```
DS = (Valeur MOYENNE du poste × 360) / Valeur ANNUELLE du poste (flux)
```

avec `Valeur moyenne = (valeur initiale + valeur finale) / 2`

Et la notion voisine :
```
Vitesse de rotation = Valeur annuelle / Valeur moyenne
```
La rotation indique **combien de fois le poste a été renouvelé** dans l'année. **DS et rotation sont inverses l'une de l'autre** : `DS = 360 / rotation`.

### Le bon dénominateur pour chaque poste

| Poste | Dénominateur (flux annuel) |
|---|---|
| **Stock de marchandises** | Coût d'achat des marchandises **vendues** |
| **Stock de matières premières** | Coût d'achat des matières premières **utilisées** |
| **Stock de produits finis** | Coût de production des produits **vendus** |
| **En-cours de production** | Coût de production des en-cours |
| **Clients** | Chiffre d'affaires **TTC** |
| **Fournisseurs** | Achats **TTC** |
| **TVA collectée** | CAHT × taux de TVA |
| **TVA déductible** | Achats HT × taux de TVA |
| **Personnel** | Charges de personnel |

### Le calcul des coûts

```
Coût d'achat des marchandises vendues = Achats + Stock initial − Stock final
                                      = Achats + Variation de stocks  (au sens PCG)

Coût de production des produits vendus = Achats de matières + charges directes et
                                          indirectes de production décaissables
                                        − Production stockée (SF − SI)
```

### ★ Les conventions de délais — à connaître par cœur

| Formulation dans l'énoncé | Durée de stockage retenue |
|---|---|
| Paiement **au comptant** | **0 jour** |
| **30 jours** | 30 jours |
| **30 jours FIN DE MOIS** | 30 + **15** = **45 jours** |
| **60 jours fin de mois** | 60 + 15 = **75 jours** |
| TVA réglée le **24 du mois suivant** | **15 + 24 = 39 jours** |
| TVA réglée le **20 du mois suivant** | 15 + 20 = **35 jours** |
| TVA réglée le **21 du mois suivant** | 15 + 21 = **36 jours** |
| TVA réglée le **22 du mois suivant** | 15 + 22 = **37 jours** |
| Salaires payés **fin de mois** | **15 jours** |
| Cotisations sociales le **15 du mois suivant** | 15 + 15 = **30 jours** |

> **D'où viennent ces 15 jours ?** Une opération peut avoir lieu n'importe quel jour du mois. En moyenne, elle a lieu au milieu, soit **30/2 = 15 jours** avant la fin du mois. On ajoute donc 15 jours d'attente moyenne. **C'est la question de cours la plus fréquente sur ce chapitre : sache l'expliquer en une phrase.**

### Les délais pondérés

Quand l'énoncé donne une répartition, on fait une **moyenne pondérée** :

> *Exemple du cours : « Les fournisseurs sont réglés 50 % au comptant, 20 % à 30 jours et 30 % à 60 jours. »*
```
DS = (50 % × 0) + (20 % × 30) + (30 % × 60) = 0 + 6 + 18 = 24 jours
```

> *Variante : « … et 30 % à 60 jours FIN DE MOIS »*
```
DS = (50 % × 0) + (20 % × 30) + (30 % × (60 + 15)) = 0 + 6 + 22,5 = 28,5 jours
```

> *Exemple DCG 2023 : « Crédit clients : 10 % au comptant, 90 % à 50 jours »*
```
DS = (0 × 0,10) + (50 × 0,90) = 45 jours
```

## 4.4 Le ratio de structure (RS)

### La définition

> **Le RS est un coefficient de pondération qui convertit les temps d'écoulement en une unité commune : le jour de chiffre d'affaires hors taxes.**

```
RS = Valeur annuelle du poste / CAHT
```

**Ou, si les coûts sont donnés à l'unité :**
```
RS = Coût unitaire du poste / Prix de vente unitaire HT
```

### Le tableau des RS (référence)

| Poste | Ratio de structure |
|---|---|
| Stocks de marchandises | Coût d'achat des marchandises vendues / CAHT |
| Stocks de matières premières | Coût d'achat des MP utilisées / CAHT |
| Stocks de produits finis | Coût de production des produits vendus / CAHT |
| En-cours | Coût de production des en-cours / CAHT |
| **Clients** | **CA TTC / CAHT** |
| **Fournisseurs** | **Achats TTC / CAHT** |
| **TVA collectée** | (CAHT × taux TVA) / CAHT |
| **TVA déductible** | (Achats HT × taux TVA) / CAHT |

### ★ La technique du « je pose x = le CA »

C'est **la** méthode pour tous les énoncés en pourcentages. Le cours l'utilise systématiquement.

**Cas 1 — le prix d'achat représente 50 % du prix de vente (TVA 20 %) :**
```
On pose x = le CAHT.
RS Stock marchandises = 0,5x / x           = 0,50
RS Fournisseurs       = (0,5x × 1,2) / x   = 0,60
RS TVA déductible     = (0,5x × 0,20) / x  = 0,10
```

**Cas 2 — marge de 50 % SUR LE PRIX D'ACHAT** (attention, ce n'est pas pareil !) :
```
On pose x = le PRIX D'ACHAT.
Marge = 0,5x  →  Prix de vente = x + 0,5x = 1,5x
RS Stock marchandises = x / 1,5x           = 0,67
RS Fournisseurs       = (0,67x × 1,2) / x  = 0,80
RS TVA déductible     = (0,67x × 0,20) / x = 0,13
```
> ⚠️ **« Marge de 50 % sur le prix d'achat » ≠ « prix d'achat = 50 % du prix de vente ».** Lis très attentivement.

**Cas 3 — 30 % du CA à l'export (pas de TVA sur l'export) :**
```
RS Clients       = (70 % × 1,2 + 30 % × 1,0) = 0,84 + 0,30 = 1,14
RS TVA collectée = (70 % × 0,20 + 30 % × 0)  = 0,14
```

**Cas 4 — deux taux de TVA (40 % alimentaire à 5,5 %, 60 % vins à 20 %) :**
```
RS Clients       = (40 % × 1,055) + (60 % × 1,20) = 0,422 + 0,720 = 1,142
RS TVA collectée = (40 % × 0,055) + (60 % × 0,20) = 0,022 + 0,120 = 0,142
```

### ★ Le cas des salaires et cotisations (le plus technique)

> *Exemple du cours : les charges de personnel représentent 40 % du prix de vente. Charges sociales SALARIALES = 25 % du brut, charges sociales PATRONALES = 35 % du brut.*

**Méthode : on raisonne sur un salaire brut de 100.**
```
Salaire brut                             100
+ Charges patronales (35 % de 100)      + 35
────────────────────────────────────────────
= COÛT TOTAL POUR L'ENTREPRISE           135     ← c'est ça, "les charges de personnel"

Dont salaire NET versé au salarié : 100 − 25 = 75
Dont charges sociales totales (URSSAF) : 25 + 35 = 60
                                         ────
                                          135  ✅
```
Puis on répartit les 40 % du CA proportionnellement :
```
RS Dettes de personnel      = (75/135) × 0,40 = 0,22
RS Dettes organismes sociaux = (60/135) × 0,40 = 0,18
                                              ────
                                Contrôle :      0,40  ✅
```

> **Variante du TD (Cas 2013)** : patronales 40 %, salariales 20 % → coût total 140, net 80, cotisations 60.
> `RS salaires = (80/140) × (120/500)` et `RS cotisations = (60/140) × (120/500)`.

> **Contrôle imparable** : la somme des deux RS doit être **exactement égale** au poids total des charges de personnel dans le CA.

## 4.5 Le tableau de calcul du BFRE normatif

```
┌──────────────────────┬────────┬────────┬──────────┬──────────────┐
│      POSTES          │   DS   │   RS   │ BESOINS  │ DÉGAGEMENTS  │
│                      │  (1)   │  (2)   │ (1)×(2)  │   (1)×(2)    │
├──────────────────────┼────────┼────────┼──────────┼──────────────┤
│ Stocks MP            │        │        │    X     │              │
│ Stocks en-cours      │        │        │    X     │              │
│ Stocks produits finis│        │        │    X     │              │
│ Clients              │        │        │    X     │              │
│ TVA déductible       │        │        │    X     │              │
├──────────────────────┼────────┼────────┼──────────┼──────────────┤
│ Fournisseurs         │        │        │          │      X       │
│ Dettes de personnel  │        │        │          │      X       │
│ Organismes sociaux   │        │        │          │      X       │
│ TVA collectée        │        │        │          │      X       │
├──────────────────────┴────────┴────────┼──────────┼──────────────┤
│ BFRE NORMATIF = Besoins − Dégagements  │  Σ (1)   │    Σ (2)     │
└────────────────────────────────────────┴──────────┴──────────────┘

BFRE normatif en JOURS DE CAHT = Σ Besoins − Σ Dégagements
BFRE normatif EN VALEUR (€)    = Nb de jours × (CAHT / 360)
```

### La règle mémo : qui est un besoin, qui est un dégagement ?

> **Tout ce qui est à l'ACTIF du bilan = BESOIN.**
> **Tout ce qui est au PASSIF du bilan = DÉGAGEMENT.**

Stocks, créances clients, TVA déductible → à l'actif → **besoins**.
Dettes fournisseurs, dettes de personnel, dettes sociales, TVA collectée → au passif → **dégagements**.

## 4.6 ★ TOUTES LES INCONNUES POSSIBLES SUR LE BFR NORMATIF

*Base des exemples : BFRE normatif = 20,8 jours de CAHT ; CAHT = 192 000 k€ ; CA quotidien = 533,33 k€.*

### ▸ Inconnue 1 : le BFRE en valeur, à partir des jours
```
BFRE (€) = jours × CAHT/360 = 20,8 × 533,33 = 11 093 k€
```

### ▸ Inconnue 2 : le BFRE en jours, à partir de la valeur
```
Jours = BFRE (€) / (CAHT/360) = 11 093 / 533,33 = 20,8 jours
```

### ▸ Inconnue 3 : le CAHT
> *Le BFRE normatif est de 20,8 jours et représente 11 093 k€. Quel est le CAHT ?*
```
CAHT = BFRE (€) × 360 / jours = 11 093 × 360 / 20,8 = 192 000 k€
```

### ▸ Inconnue 4 : la DS d'un poste
> *Le poste Clients pèse 65 jours de CAHT et son ratio de structure est de 1,20. Quelle est la durée de crédit clients ?*
```
DS = Besoin / RS = 65 / 1,20 = 54,2 jours
```

### ▸ Inconnue 5 : le RS d'un poste
> *Le stock pèse 23,2 jours de CAHT pour une durée de stockage de 59,3 jours.*
```
RS = Besoin / DS = 23,2 / 59,3 = 0,39
```

### ▸ Inconnue 6 : la valeur moyenne d'un poste au bilan
> *Le poste fournisseurs représente 56,3 jours de dégagement pour un CAHT de 192 000.*

En utilisant `DS × RS = valeur moyenne × 360 / CAHT` :
```
Valeur moyenne = 56,3 × 192 000 / 360 = 30 027 ≈ 30 000 k€
```

### ▸ Inconnue 7 : ★ l'impact d'une modification d'une durée
**C'est la question 4 du sujet DCG 2023 que tu as en annexe. Très probable au rattrapage.**

```
╔════════════════════════════════════════════════════════════╗
║   Impact en jours de CAHT  =  Variation de la DS  ×  RS    ║
╚════════════════════════════════════════════════════════════╝
```

> *Exemple DCG 2023 : le délai clients passe de 45 à 40 jours. RS clients = 1,20. Le BFRE était de 59 jours.*
```
Impact = (45 − 40) × 1,20 = 6 jours de CAHT
Nouveau BFRE = 59 − 6 = 53 jours
```
> **Commentaire attendu** : *réduire le délai clients de 5 jours réduit le besoin de financement de 6 jours de CAHT — l'effet est amplifié par le RS de 1,20, car les créances clients sont TTC alors que le BFR est exprimé en jours de CA HT.*

### ▸ Inconnue 8 : l'impact d'une modification d'un RS
> *La part de l'export passe de 30 % à 50 % (TVA 20 %). DS clients = 60 jours.*
```
RS avant = 0,7 × 1,2 + 0,3 × 1,0 = 1,14  →  besoin = 60 × 1,14 = 68,4 j
RS après = 0,5 × 1,2 + 0,5 × 1,0 = 1,10  →  besoin = 60 × 1,10 = 66,0 j
Gain = 2,4 jours de CAHT
```

### ▸ Inconnue 9 : ★ l'économie de trésorerie par rapport au secteur
**C'est la question du cas 2009 du cours.**
```
Économie = (BFRE de l'entreprise − BFRE du secteur) × CAHT/360
```
> *Exemple : 120,1 jours contre 90 jours pour le secteur, CAHT = 2 120 000.*
```
Économie = (120,1 − 90) × (2 120 000/360) = 30,1 × 5 889 = 177 258 €
```
(le corrigé indique 176 640, aux arrondis près — **ne panique pas pour 0,3 % d'écart, mets ton calcul**)

### ▸ Inconnue 10 : la DS cible pour atteindre un BFRE objectif
> *Le BFRE actuel est de 59 jours. On veut le ramener à 50 jours en agissant uniquement sur le crédit clients (RS = 1,20, DS actuelle = 45 j). Quelle nouvelle durée ?*
```
Réduction nécessaire = 9 jours de CAHT
Réduction de DS = 9 / 1,20 = 7,5 jours
Nouvelle DS clients = 45 − 7,5 = 37,5 jours
```

## 4.7 Intérêts et limites du modèle (question de cours quasi certaine)

| **INTÉRÊTS** | **LIMITES** |
|---|---|
| Comprendre l'**origine** de chaque poste (durée ou structure ?) | Hypothèses simplificatrices : durées moyennes, CAHT régulièrement réparti sur l'année, proportionnalité stricte entre BFRE et CAHT |
| **Cibler les actions correctrices** sur la DS ou sur le RS | Modèle **peu adapté aux activités saisonnières** |
| Mesurer l'**incidence d'une modification** d'un poste | Ne prend pas en compte les besoins **conjoncturels** ni le **hors exploitation** |
| Déterminer le **BFRE prévisionnel** à partir d'un CA prévisionnel | Le BFRE normatif est calculé **hors amortissements** (charges non décaissables) |
| Faciliter les **comparaisons sectorielles** | Diffère du BFRE du bilan fonctionnel (dynamique vs statique, stock moyen vs stock final) |
| Simuler les effets d'une modification | |

### Le lien BFRE ↔ rentabilité économique (question du TD)

```
Re = Résultat économique / (Immobilisations + BFRE)
```
> **Plus le BFRE est élevé, plus le dénominateur est grand, plus la rentabilité économique diminue.** Maîtriser le BFR, c'est directement améliorer la rentabilité.

### Les leviers d'action sur le poste clients (question du DCG 2023)

- Réduire les délais de paiement contractuels avec les clients professionnels
- Augmenter la part de clients particuliers, qui paient comptant
- Mettre en place un contrat d'**affacturage** : l'entreprise cède ses créances à un *factor* qui se charge de l'encaissement contre une commission. Le factor **devient propriétaire** des créances : l'entreprise est protégée du **risque de non-recouvrement**, transféré au factor. En contrepartie, le coût financier peut être important.
- Accorder un **escompte de règlement** pour paiement anticipé
- Facturer plus rapidement, relancer plus tôt

### Le décalage BFRE normatif ≠ BFRE du bilan (question du TD)

> *« La différence principale provient du fait que le BFRE calculé selon le bilan de fin d'exercice est obtenu avec un **stock FINAL** alors que le BFR normatif a été calculé à partir du **stock MOYEN** »*, plus les différences d'arrondis.

---

# CHAPITRE 5 — LE TABLEAU DE FLUX DE TRÉSORERIE

## 5.1 À quoi ça sert ?

Le bilan fonctionnel explique la trésorerie par des **stocks** (FRNG − BFR). Le tableau de flux l'explique par des **flux** : *d'où est venu l'argent, où est-il parti ?*

Le poly justifie ce choix par trois arguments à connaître :

1. **La trésorerie est un indicateur clé** — c'est un problème vital pour toute entreprise. C'est grâce à elle qu'elle finance son activité à court terme (BFR) et assure sa pérennité à moyen-long terme (autofinancement, investissement).
2. **C'est un concept objectif** qui, contrairement au FRNG, **ne dépend pas de conventions comptables**. On ne peut pas « maquiller » sa trésorerie.
3. **C'est un outil de prévision**, qui s'inscrit dans une démarche budgétaire encaissements/décaissements.

> **La force du tableau de flux** : il répond en un coup d'œil à *« Comment cette entreprise finance-t-elle sa croissance ? »* → par son activité, par ses actionnaires, ou par sa banque ?

## 5.2 La structure en 4 blocs

```
╔═══════════════════════════════════════════════════════════════╗
║  A — FLUX LIÉ À L'ACTIVITÉ        (le métier)                 ║
║  B — FLUX LIÉ À L'INVESTISSEMENT  (les machines)              ║
║  C — FLUX LIÉ AU FINANCEMENT      (les actionnaires/banques)  ║
║  ─────────────────────────────────────────────────────────    ║
║  A + B + C = VARIATION DE LA TRÉSORERIE                       ║
╚═══════════════════════════════════════════════════════════════╝
```

Ce que chaque solde raconte :

- **A** : *« L'entreprise gagne-t-elle de l'argent en faisant son métier ? »* Il *« délivre une information sur la capacité de l'entreprise à rembourser ses emprunts, à payer les dividendes et à procéder à de nouveaux investissements sans faire appel à des sources de financement externe. »*
- **B** : *« Investit-elle ? »* Presque toujours négatif dans une entreprise saine. Il révèle le type de croissance : **interne** (acquisition d'immobilisations corporelles/incorporelles) ou **externe** (acquisition de participations = rachat d'entreprises).
- **C** : *« Qui finance ? »* Il *« permet de montrer si l'entreprise s'endette pour payer les distributions qu'elle met en paiement »* — une pratique très critiquable.

## 5.3 Le tableau complet (à savoir reproduire de tête)

```
┌────────────────────────────────────────────────────────────────────┐
│  FLUX DE TRÉSORERIE LIÉS À L'ACTIVITÉ                              │
├────────────────────────────────────────────────────────────────────┤
│   Résultat net                                                     │
│ + Dotations aux amortissements et provisions NETTES DE REPRISES    │
│      (SAUF celles sur ACTIF CIRCULANT)                             │
│ − Plus-value de cession        (= PCEA − VCEAC)                    │
│ − Transfert de charges aux frais d'émission des emprunts           │
│      (= augmentation des FEE de l'exercice)                        │
│ ══════════════════════════════════════════════════════════════════ │
│ = MARGE BRUTE D'AUTOFINANCEMENT (MBA)                              │
│ ────────────────────────────────────────────────────────────────── │
│  Moins la variation du BFR lié à l'activité (en valeurs NETTES) :  │
│    Stocks                          (− si augmente)                 │
│    Créances d'exploitation         (− si augmente)                 │
│    Dettes d'exploitation           (+ si augmente)                 │
│    Autres créances liées à l'activité (− si augmente)              │
│    Autres dettes liées à l'activité   (+ si augmente)              │
│ ══════════════════════════════════════════════════════════════════ │
│ = FLUX NET DE TRÉSORERIE GÉNÉRÉ PAR L'ACTIVITÉ            (A)      │
├────────────────────────────────────────────────────────────────────┤
│  FLUX LIÉ AUX OPÉRATIONS D'INVESTISSEMENT                          │
├────────────────────────────────────────────────────────────────────┤
│ − Acquisitions d'immobilisations                                   │
│ + Cessions d'immobilisations                    (= PCEA)           │
│ + Réduction d'immobilisations financières                          │
│ ± Variation des dettes et créances sur immobilisations             │
│ ══════════════════════════════════════════════════════════════════ │
│ = FLUX LIÉ AUX OPÉRATIONS D'INVESTISSEMENT               (B)       │
├────────────────────────────────────────────────────────────────────┤
│  FLUX LIÉ AUX OPÉRATIONS DE FINANCEMENT                            │
├────────────────────────────────────────────────────────────────────┤
│ − Dividendes versés                                                │
│ ± Incidence des variations de capital                              │
│ + Émissions d'emprunts                                             │
│ − Remboursements d'emprunts                                        │
│ ══════════════════════════════════════════════════════════════════ │
│ = FLUX LIÉ AUX OPÉRATIONS DE FINANCEMENT                 (C)       │
├────────────────────────────────────────────────────────────────────┤
│  VARIATION DE TRÉSORERIE (A + B + C)                               │
│  Trésorerie d'ouverture  =  Dispo + VMP − CBC/SCB   (au 01/01)     │
│  Trésorerie de clôture   =  Dispo + VMP − CBC/SCB   (au 31/12)     │
└────────────────────────────────────────────────────────────────────┘
```

**LE CONTRÔLE ABSOLU :**
```
A + B + C  =  Trésorerie de clôture − Trésorerie d'ouverture
```
Si ça ne tombe pas juste, il y a une erreur. **Fais toujours ce contrôle et écris-le sur ta copie** : ça montre au correcteur que tu maîtrises la logique.

## 5.4 Les 5 subtilités qui font perdre des points

### ① « Nettes de reprises, SAUF sur actif circulant »

On rajoute au résultat les DAP **moins** les reprises. **Mais on exclut** les dotations et reprises portant sur l'**actif circulant** (dépréciation des stocks, dépréciation des créances clients, dépréciation des VMP).

**Pourquoi ?** Parce que les stocks et créances sont ensuite repris **en valeurs nettes** dans la variation du BFR. Les compter dans les dotations *et* dans la variation du BFR, ce serait les compter deux fois.

> **Exemple (cas LVMH du TD)** : DAP totales 21 330, dont 700 sur stocks et 20 sur VMP. Reprises 1 100, dont 800 sur créances clients et 200 sur stocks.
> ```
> DAP nettes retenues = (21 330 − 700 − 20) − (1 100 − 800 − 200) = 20 610 − 100 = 20 510
> ```

> **Exemple (CC2 2025-2026)** : dotations aux amortissements 91 200 + dotation aux provisions pour risques et charges 2 400 = **93 600**. La dotation de 2 400 pour dépréciation des comptes clients est **exclue** (actif circulant).

### ② La variation du BFR se fait en valeurs NETTES

**C'est l'inverse du bilan fonctionnel.** On prend les colonnes « Net » du bilan.

**Pourquoi ?** Parce que les dépréciations ont déjà été neutralisées au point ①. Cohérence.

### ③ Le sens des signes

```
Un ACTIF qui AUGMENTE     → l'argent sort      → SIGNE −
Un ACTIF qui DIMINUE      → l'argent rentre    → SIGNE +
Une DETTE qui AUGMENTE    → l'argent reste     → SIGNE +
Une DETTE qui DIMINUE     → l'argent sort      → SIGNE −
```

> **Le raccourci du TD :**
> ```
> Actif circulant ↑ → BFRE ↑ → on met en −
> Actif circulant ↓ → BFRE ↓ → on met en +
> Dettes ↑          → BFRE ↓ → on met en +
> Dettes ↓          → BFRE ↑ → on met en −
> ```

### ④ La plus-value de cession se retranche

```
Plus-value = PCEA − VCEAC
```
On la **retranche** du résultat, car l'encaissement complet (le PCEA) sera repris dans le bloc **investissement**. Sinon, double comptage.

> Si c'est une **moins-value** (PCEA < VCEAC), le terme est négatif et `− (moins-value)` devient une **addition**. Ne te trompe pas de signe.

### ⑤ La trésorerie inclut les VMP

```
Trésorerie = Disponibilités + VMP − Concours bancaires courants − Soldes créditeurs de banque
```
> ⚠️ **Rappel** : au **bilan fonctionnel**, les VMP étaient en actif circulant hors exploitation. Ici elles sont **dans la trésorerie**. Deux chapitres, deux définitions. Le poly l'assume explicitement.

## 5.5 ★ TOUTES LES INCONNUES POSSIBLES SUR LE TABLEAU DE FLUX

Le tableau de flux, c'est **90 % de reconstitution de données manquantes**. Voici toutes les techniques.

### ▸ Inconnue 1 : ★ les plus ou moins-values de cession
**C'est littéralement la question 1 du CC2 2025-2026.**

```
┌───────────────┬────────────┬───────────┬──────────────┬──────────┬──────────────┐
│   Élément     │ Prix de    │ Valeur    │Amortissements│   VNC    │ Plus/moins   │
│               │ cession(1) │ d'origine │  pratiqués   │ (2)−(3)  │ value (1)−(4)│
│               │            │    (2)    │     (3)      │   (4)    │              │
├───────────────┼────────────┼───────────┼──────────────┼──────────┼──────────────┤
│ Constructions │   31 200   │  36 000   │    12 000    │  24 000  │   + 7 200    │
│ Matériels     │    2 400   │  12 000   │     4 800    │   7 200  │   − 4 800    │
│ Participations│   14 400   │  12 000   │        0     │  12 000  │   + 2 400    │
└───────────────┴────────────┴───────────┴──────────────┴──────────┴──────────────┘
```
**Où trouver les données :**
- Prix de cession → donné en clair (« Produits de cession des II, IC et IF »)
- Valeur d'origine → **colonne « Diminutions » du tableau des IMMOBILISATIONS**
- Amortissements pratiqués → **colonne « Diminutions » du tableau des AMORTISSEMENTS**

> **La logique** : quand on cède une immobilisation, on la sort du bilan → elle disparaît des immobilisations **et** ses amortissements disparaissent aussi. Les deux colonnes « Diminutions » se répondent.

### ▸ Inconnue 2 : les acquisitions d'immobilisations
= **colonne « Augmentations » du tableau des immobilisations**.
> *CC2 : 4 800 + 96 000 + 132 000 = 232 800*

Si le tableau n'est pas fourni :
```
Acquisitions = Immo brutes fin − Immo brutes début + Valeur d'origine des cessions
```

### ▸ Inconnue 3 : la réduction d'immobilisations financières
= la diminution des **prêts** (un prêt qu'on t'a remboursé) — à ne pas confondre avec une cession de participations.
> *CC2 : prêts 16 800 → 12 000, diminution = 4 800*

### ▸ Inconnue 4 : ★ les dividendes versés
```
Dividendes = Résultat N−1 − Δ(toutes les réserves) − Δ(report à nouveau)
```
> *CC2 : 24 000 − 0 − 0 = **24 000***
> *Cas Décorex : 297 − (178−163) − (1 767−1 649) = **164***
> *Cas LVMH : 1 800 − [(890 + 4 070) − (800 + 3 200)] = 1 800 − 960 = **840***

### ▸ Inconnue 5 : ★ les émissions et remboursements d'emprunts
Le tableau de mouvement :
```
Dettes financières fin (hors CBC) = Dettes début (hors CBC) + Émissions − Remboursements
```
> *Cas LVMH : DF début = 42 896 − 896 = 42 000 ; DF fin = 44 000 − 1 900 = 42 100 ; remboursements donnés = 400.*
> ```
> 42 000 + X − 400 = 42 100   →   X = 500  (émissions)
> ```
> *CC2 : DF 48 000 → 36 000, « pas de nouvel emprunt en N » → **remboursements = 12 000***

> ⚠️ **Toujours retirer les CBC des dettes financières avant ce calcul.** Sinon le résultat est faux.

### ▸ Inconnue 6 : l'augmentation de capital
```
Incidence des variations de capital = Δ Capital + Δ Primes d'émission
```
> *Cas LVMH : (20 000 − 15 000) + (1 000 − 0) = **6 000***
> *CC2 : 672 000 − 552 000 = **120 000***

### ▸ Inconnue 7 : la trésorerie d'ouverture ou de clôture
```
Trésorerie = Disponibilités + VMP − CBC − SCB
```
> *CC2 : ouverture 14 400 (pas de VMP ni de CBC) ; clôture 12 000 → variation −2 400*

### ▸ Inconnue 8 : un flux manquant, retrouvé par le contrôle
> *Le flux d'activité est de 93 600, le flux de financement de 84 000, et la trésorerie est passée de 14 400 à 12 000. Quel est le flux d'investissement ?*
```
A + B + C = ΔTrésorerie
93 600 + B + 84 000 = 12 000 − 14 400 = − 2 400
B = − 2 400 − 93 600 − 84 000 = − 180 000
```

### ▸ Inconnue 9 : le résultat net à partir de la MBA
```
Résultat net = MBA − DAP nettes + Plus-value + Transfert de charges FEE
```
> *MBA = 122 400, DAP nettes = 93 600, plus-value = 4 800.*
> `RN = 122 400 − 93 600 + 4 800 = 33 600`

### ▸ Inconnue 10 : la variation d'un poste du BFR
> *La MBA est de 122 400 et le flux d'activité de 93 600. Quelle est la variation du BFR lié à l'activité ?*
```
Variation = 93 600 − 122 400 = − 28 800   (le BFR a augmenté de 28 800)
```

## 5.6 MBA ou CAF ? La question qui piège

Ce sont **deux notions voisines mais différentes** :

| | Point de départ | Traitement des dépréciations d'actif circulant | Frais d'émission d'emprunts |
|---|---|---|---|
| **CAF** (chap. 2) | Résultat net | **Incluses** dans les DAP | Non concerné |
| **MBA** (chap. 5) | Résultat net | **Exclues** | Le transfert de charges est retranché |

Elles convergent quand il n'y a ni dépréciation d'actif circulant, ni frais d'émission d'emprunts.

> *Vérification sur le CC2 : CAF = 33 600 + 93 600 + 2 400 (dotation clients) − 4 800 = 124 800 ; MBA = 122 400. L'écart de 2 400 est exactement la dotation sur actif circulant.* ✅

## 5.7 Les commentaires-types du tableau de flux

Ce sont les phrases qui rapportent 2 à 3 points. Adapte-les au cas.

**Sur le flux d'activité (A) :**
> *« Les flux de trésorerie dégagés par l'exploitation apparaissent [importants / très faibles] au regard de l'activité. C'est surtout [l'augmentation du BFRE (créances clients) / le poids des charges financières] qui explique cette [performance / insuffisance]. »*

**Sur le flux d'investissement (B) :**
> *« L'entreprise a beaucoup investi, surtout par croissance INTERNE (acquisition d'immobilisations corporelles et incorporelles), sans qu'il s'agisse d'un simple renouvellement de son outil de production. Il s'agit d'accroître ses capacités productives pour gagner des parts de marché. »*
>
> *(Variante croissance externe : « L'entreprise a acquis des titres de participation, ce qui traduit une stratégie de croissance externe par rachat d'entreprises. »)*
>
> *(Variante désinvestissement : « L'entreprise a procédé à des cessions importantes. Est-ce un renouvellement de son outil de production, un secteur à obsolescence rapide, ou un virage stratégique ? On manque d'éléments pour conclure. »)*

**Sur le flux de financement (C) :**
> *« Cette croissance s'appuie principalement sur [le recours à l'endettement / un appel aux propriétaires via une augmentation de capital / l'autofinancement]. L'entreprise doit faire face à des échéances importantes en matière de remboursement de ses dettes financières. Elle dispose de la confiance des banques qui l'accompagnent dans ces projets. »*

**Sur la variation de trésorerie :**
> *« Il en résulte néanmoins une dégradation de la trésorerie, marquée par l'apparition de concours bancaires courants. Le montant de la trésorerie de passif devient préoccupant, car le banquier pourrait sans préavis interrompre ce type de financement. »*

**La phrase de conclusion qui marche presque toujours :**
> *« L'entreprise connaît une forte croissance, mais celle-ci n'est pas suffisamment maîtrisée : le BFR croît plus vite que les ressources stables, ce qui dégrade la trésorerie. »*

---

# CHAPITRE 6 — INTÉRÊTS SIMPLES, ESCOMPTE ET DÉCOUVERT

## 6.1 À quoi ça sert ?

Deux objectifs :
1. **Comprendre le lien entre le temps et la valeur** : 100 € aujourd'hui ≠ 100 € dans un an.
2. **Minimiser le coût de financement des déficits de trésorerie de court terme.**

Le chapitre 1 t'a appris à *diagnostiquer* un problème de trésorerie. Le chapitre 6 t'apprend à le *résoudre*, et surtout à **arbitrer entre les solutions**.

## 6.2 Les intérêts simples

### Le principe

**Les intérêts sont calculés uniquement sur le capital initial**, jamais sur les intérêts déjà produits. C'est la convention pour les opérations **de moins d'un an**.

### Les formules

```
Intérêts        :  I  = C₀ × t × n
Valeur acquise  :  Vₙ = C₀ × (1 + t × n)
```

**Il doit y avoir CONCORDANCE entre le taux et la période !** C'est la règle numéro un.

| Raisonnement | n | Intérêts | Valeur acquise |
|---|---|---|---|
| **En années** | n | I = C₀ × ta × n | Vₙ = C₀ (1 + ta × n) |
| **En mois** (m mois) | m/12 | I = C₀ × ta × m/12 | Vₘ = C₀ [1 + ta × (m/12)] |
| **En quinzaines** (q) | q/24 | I = C₀ × ta × q/24 | V_q = C₀ [1 + ta × (q/24)] |
| **En jours** (j) | j/360 | I = C₀ × ta × j/360 | V_j = C₀ [1 + ta × (j/360)] |

> **★ L'année financière fait 360 jours, pas 365.** Le poly explique pourquoi : *« Cette solution est plus favorable au prêteur, car les intérêts sont calculés à partir d'un dénominateur de 360 et non 365. »*
>
> **MAIS** : dans le calcul du **taux réel** (escompte et découvert), on utilise **365**. C'est volontaire : la banque facture sur 360 et on mesure le coût vrai sur 365, ce qui fait apparaître le surcoût.

### Le calendrier (à recopier sur ton brouillon dès le début de l'épreuve)

```
  J    F    M    A    M    J    J    A    S    O    N    D
 31   28   31   30   31   30   31   31   30   31   30   31
```

**Méthode de comptage des jours entre deux dates :**
```
Du 05/03 au 30/04 :  (31 − 5) + 30 = 26 + 30 = 56 jours
```
Règle : **on compte les jours restants du premier mois** (`nb de jours du mois − jour de départ`), puis les mois entiers, puis le jour d'arrivée.

> ⚠️ **Nuance importante** : pour un **placement ou un escompte**, on compte `date de fin − date de début` (on ne compte pas le jour de départ). Pour un **découvert**, l'énoncé dit souvent « du 24/05 **inclus** au 12/06 **inclus** » : là il faut compter **les deux bornes**, donc `(31 − 24 + 1) + 12 = 20 jours`. **Lis le mot « inclus ».**

### ★ Les 4 inconnues des intérêts simples

*Base : C₀ = 12 000 € ; t = 3 % ; 6 mois ; I = 180 € ; V = 12 180 €.*

**① Les intérêts / la valeur acquise**
```
I = 12 000 × 0,03 × 0,5 = 180        V = 12 000 × (1 + 0,03 × 0,5) = 12 180
```

**② Le capital initial**
```
C₀ = Vₙ / (1 + t × n) = 12 180 / (1 + 0,03 × 0,5) = 12 180 / 1,015 = 12 000
```

**③ Le taux**
```
t = I / (C₀ × n) = 180 / (12 000 × 0,5) = 0,03 = 3 %
```
> *Variante : « quel est le taux JOURNALIER ? » → `0,03 / 360 = 0,00008333` soit 0,008333 %*

**④ La durée**
```
n = I / (C₀ × t) = 180 / (12 000 × 0,03) = 0,5 année = 6 mois
```
Ou, en repartant de la valeur acquise :
```
n = (Vₙ − C₀) / (C₀ × t)
```

**⑤ ★ La DATE (l'inconnue préférée du prof)**
> *Un capital de 8 000 € est placé le 4 mars à 4 % l'an. À quelle date obtient-on 8 040 € ?*
```
j = (8 040/8 000 − 1) / 0,04 × 360 = 0,005/0,04 × 360 = 45 jours
Du 04/03 : (31 − 4) = 27 jours pour finir mars → il reste 45 − 27 = 18 jours
→ le 18 AVRIL
```

**⑥ Le temps d'égalisation de deux placements**
> *2 000 € à 8 % et 1 800 € à 10 %. Au bout de combien de temps ont-ils la même valeur acquise ?*
```
2 000 + 2 000 × 0,08 × k = 1 800 + 1 800 × 0,10 × k
200 = 180k − 160k = 20k
k = 10 ans
```
> ⚠️ **Cas où c'est impossible** : 12 000 à 10 % et 10 000 à 12 %. Les deux gagnent 1 200 €/an : les courbes sont **parallèles**, elles ne se croisent jamais. Sache le repérer et l'écrire.

### La règle des quinzaines (livrets réglementés)

> *« Les comptes d'épargne à taux réglementé (Livret A, LDD) ont des intérêts calculés par quinzaines. Seules les quinzaines civiles COMPLÈTES sont prises en compte. Les quinzaines sont à dates fixes : du 1er au 15 du mois, et du 16 à la fin du mois. »*

> *Exemple du TD : dépôt de 4 000 € le 10/09/N, retrait le 05/01/N+1, taux 4,5 %.*
> - La quinzaine du 1er au 15 septembre est **incomplète** (on dépose le 10) → **ne compte pas**
> - La quinzaine du 1er au 15 janvier est **incomplète** (on retire le 5) → **ne compte pas**
> - Quinzaines complètes : 2ᵉ de septembre, 2 en octobre, 2 en novembre, 2 en décembre = **7 quinzaines**
> ```
> V = 4 000 + (4 000 × 0,045 × 7/24) = 4 000 + 52,50 = 4 052,50 €
> ```
> **Le 24 au dénominateur = le nombre de quinzaines dans une année.**

## 6.3 L'escompte commercial

### Le vocabulaire

> **Un effet de commerce** est un document juridique engageant un débiteur à régler, à une date future (**date d'échéance**), un capital déterminé (**valeur nominale**). Il permet à un client de payer son fournisseur plus tard.

> **L'escompte** : la banque rachète l'effet **avant l'échéance**, en contrepartie du paiement d'un **agio**. L'entreprise obtient des liquidités immédiatement.

### Les formules

```
Escompte        :  e  = Valeur nominale × t × (j / 360)
Valeur actuelle :  Va = VN − e = VN × [1 − t × (j/360)]
Agio HT         :  Agio = escompte + commissions HT
Agio TTC        :  Agio TTC = escompte + commissions TTC   (TVA 20 % sur les commissions uniquement)
Net porté au compte : VN − Agio TTC
```

### Les jours de banque

> **Les jours de banque sont des jours supplémentaires ajoutés par la banque** pour la prise en compte des opérations. Ils augmentent artificiellement la durée facturée.

```
Durée FACTURÉE (pour l'escompte) = durée réelle + jours de banque
Durée RÉELLE   (pour le taux réel) = durée sans les jours de banque
```

### Le taux réel

```
╔══════════════════════════════════════════════════════════════╗
║                        Agio HT × 365                         ║
║   Taux réel  =  ───────────────────────────────────────      ║
║                 (Valeur nominale − Agio HT) × Durée réelle   ║
╚══════════════════════════════════════════════════════════════╝
```

**Décryptage :**
- Numérateur : ce que ça coûte vraiment (agio HT), annualisé sur **365**
- Dénominateur : la somme réellement prêtée (VN − agio), sur la durée réellement financée (**sans les jours de banque**)

> **Le taux réel est TOUJOURS supérieur au taux nominal.** Pourquoi ? Trois raisons cumulatives, à citer dans le commentaire :
> 1. **Les jours de banque** : on paie des intérêts sur une durée plus longue que le crédit réel
> 2. **Les commissions fixes** : elles s'ajoutent sans contrepartie de durée
> 3. **Le 360 vs 365** : la banque facture sur 360, on mesure sur 365

### Les types de commissions

| Type | Traitement |
|---|---|
| **Commission fixe par effet** (ex : 2,40 € HT/effet, 6,00 € HT/effet) | S'ajoute en euros à l'agio, **multipliée par le nombre d'effets** |
| **Commission d'endos, proportionnelle au temps** (ex : 0,60 %) | **S'ajoute AU TAUX** : on calcule avec `t + 0,60 %` |
| **Commission proportionnelle à la valeur** (ex : 1 pour mille) | S'ajoute en euros : `VN × 1/1000` |

> *Exemple du sujet « Escompte vs découvert 1 » : taux 11 % + commission d'endos 0,60 % → on calcule l'escompte à **11,60 %**.*

### ★ TOUTES LES INCONNUES DE L'ESCOMPTE

*Base : VN = 5 000 €, taux 7 %, 65 jours réels, 3 jours de banque, commission fixe 4,00 € HT.*

**① L'agio et le net porté en compte (cas normal)**
```
Durée facturée = 65 + 3 = 68 jours
Escompte = 5 000 × 0,07 × 68/360 = 66,11
Agio HT  = 66,11 + 4,00 = 70,11
Agio TTC = 66,11 + (4,00 × 1,2) = 70,91
Net versé = 5 000 − 70,91 = 4 929,09
```

**② Le taux réel**
```
tr = (70,11 × 365) / [(5 000 − 70,11) × 65] = 25 590 / 320 442 = 7,99 %
```

**③ ★ La DATE D'ÉCHÉANCE — c'est la question 1 du CC3 !**
> *Deux effets de 8 000 € et 7 000 € (même échéance) remis à l'escompte le 05/03 au taux de 6 %. Le montant crédité est de 14 860 €. Déterminer la date d'échéance.*
```
Étape 1 — l'escompte :   e = (8 000 + 7 000) − 14 860 = 140 €
Étape 2 — les jours :    140 = 15 000 × 0,06 × j/360
                         j = 140 × 360 / (15 000 × 0,06) = 50 400 / 900 = 56 jours
Étape 3 — la date :      du 05/03, il reste (31 − 5) = 26 jours de mars
                         56 − 26 = 30 → le 30 AVRIL
```

**④ La DATE DE REMISE (l'inverse)**
> *Un effet de 15 000 €, échéance le 30/04, taux 6 %. L'escompte est de 140 €. Quand a-t-il été remis ?*
```
j = 140 × 360 / 900 = 56 jours avant le 30/04
30 avril − 30 jours = 31 mars ; − 26 jours = 5 mars   →  le 05/03
```

**⑤ La VALEUR NOMINALE**
> *Un effet remis 56 jours avant échéance à 6 % a généré un escompte de 140 €.*
```
VN = e / (t × j/360) = 140 / (0,06 × 56/360) = 140 / 0,009333 = 15 000 €
```

**⑥ Le TAUX D'ESCOMPTE**
> *Un effet de 15 000 € remis 56 jours avant échéance a généré un escompte de 140 €.*
```
t = e × 360 / (VN × j) = 140 × 360 / (15 000 × 56) = 50 400 / 840 000 = 6 %
```

**⑦ La VALEUR ACTUELLE / le montant crédité**
```
Va = VN × [1 − t × j/360] = 15 000 × (1 − 0,06 × 56/360) = 15 000 × 0,990667 = 14 860
```

**⑧ Le SEUIL entre deux banques (comparaison en fonction de j)**
> *Banque A : 3 % + 5 € HT fixe. Banque B : 2,5 % + 1 pour mille. Effet de 10 000 €. Quelle banque selon j ?*
```
Agio A = 10 000 × 0,03 × j/360 + 5      = 0,8333 j + 5
Agio B = 10 000 × 0,025 × j/360 + 10    = 0,6944 j + 10
Égalité : 0,8333j + 5 = 0,6944j + 10  →  0,1389j = 5  →  j = 36 jours
```
**Conclusion : si j < 36 jours, la banque A est plus intéressante ; si j > 36 jours, c'est la banque B.**
> *Vérification de bon sens : à j = 0, A coûte 5 € et B coûte 10 € → A est bien meilleure au départ. Fais toujours ce test, il t'évite d'inverser la conclusion.*

## 6.4 L'équivalence d'effets

### Le principe

> **Deux effets sont équivalents à une date donnée si, à cette date, ils ont la MÊME VALEUR ACTUELLE.**

C'est le mécanisme du **renouvellement d'effet** : un client ne peut pas payer, on remplace ses traites par une nouvelle traite à échéance plus lointaine — mais d'un montant plus élevé, pour compenser le temps gagné.

### L'équation fondamentale

```
╔══════════════════════════════════════════════════════════════════════════╗
║   VN_nouveau × [1 − t × j_nouveau/360]  =  Σ VN_i × [1 − t × j_i/360]    ║
╚══════════════════════════════════════════════════════════════════════════╝
```

**Toutes les durées `j` se comptent depuis la DATE D'ÉQUIVALENCE** (la date de la négociation, donnée dans l'énoncé).

### ★ Les inconnues de l'équivalence — c'est la partie II du CC3

*Données CC3 : le 10 avril, on remplace par un effet unique C échéant le 25 mai les traites de 1 400 € au 30 avril, 1 800 € au 15 mai et 2 700 € au 4 juin. Taux 12 %.*

**Étape préalable OBLIGATOIRE — le décompte des jours depuis le 10 avril :**
```
au 30/04 :  30 − 10                    = 20 jours
au 15/05 :  20 + 15                    = 35 jours
au 25/05 :  20 + 25                    = 45 jours
au 04/06 :  20 + 31 + 4                = 55 jours
```

**① La VALEUR NOMINALE de l'effet unique**
```
Valeurs actuelles au 10/04 :
   1 400 × (1 − 0,12 × 20/360) = 1 400 − 9,33   = 1 390,67
   1 800 × (1 − 0,12 × 35/360) = 1 800 − 21,00  = 1 779,00
   2 700 × (1 − 0,12 × 55/360) = 2 700 − 49,50  = 2 650,50
                                            Σ   = 5 820,17

C × (1 − 0,12 × 45/360) = 5 820,17
C × 0,985 = 5 820,17
C = 5 908,80 €
```

**② ★ Le TAUX (l'inconnue du CC3, question 2)**
> *Calculer le taux si la valeur nominale de C est égale à 5 905 €.*

**La méthode qui marche à tous les coups : on développe et on isole t.**
```
5 905 × (1 − t × 45/360) = 1 400(1 − t×20/360) + 1 800(1 − t×35/360) + 2 700(1 − t×55/360)

Membre de gauche :  5 905 − t × (5 905 × 45)/360 = 5 905 − 738,125 t
Membre de droite :  5 900 − t × (1 400×20 + 1 800×35 + 2 700×55)/360
                    5 900 − t × (28 000 + 63 000 + 148 500)/360
                    5 900 − t × 239 500/360 = 5 900 − 665,278 t

5 905 − 738,125 t = 5 900 − 665,278 t
5 = 738,125 t − 665,278 t = 72,847 t

           ╔═══════════════════════════════╗
           ║  t = 5 / 72,847 = 6,86 %      ║
           ╚═══════════════════════════════╝
```
> **La formule générale à retenir :**
> ```
>          VN_nouveau − Σ VN_anciens
>  t = ────────────────────────────────────────────
>      (VN_nouv × j_nouv − Σ VN_i × j_i) / 360
> ```
> **Astuce de contrôle** : la valeur nominale du nouvel effet doit toujours être **supérieure** à la somme des anciens si son échéance est plus lointaine que la moyenne. Ici 5 905 > 5 900 ✅

**③ La DATE D'ÉCHÉANCE de l'effet unique**
> *Le taux est de 12 % et l'effet unique vaut 5 908,80 €. Quelle est son échéance ?*
```
5 908,80 × (1 − 0,12 × j/360) = 5 820,17
1 − 0,12 j/360 = 0,985
0,12 j/360 = 0,015   →   j = 0,015 × 360 / 0,12 = 45 jours
45 jours après le 10 avril  →  le 25 MAI
```

**④ Une des valeurs nominales anciennes**
> *Même énoncé, mais on cherche la 3ᵉ traite, sachant que C = 5 908,80 €.*
```
2 650,50 = X × (1 − 0,12 × 55/360) = X × 0,981667
X = 2 700 €
```

## 6.5 Le découvert bancaire

### Le vocabulaire

> **Découvert bancaire ou facilité de compte** : prêt accordé par une banque lorsqu'elle autorise un client à rendre son compte débiteur.

> **Date de valeur** : date à laquelle une opération est prise en compte par la banque pour déterminer le solde. **Elle diffère de la date d'opération** — et toujours en faveur de la banque.

### Les formules

```
Nombres débiteurs  =  Σ (solde débiteur × nombre de jours)

Intérêts débiteurs =  Nombres débiteurs × (t / 360)
                   =  Nombres débiteurs × t / 36 000   (si t en %)

Agios HT = Intérêts + CPFD + Commission de dépassement + Commission de compte
```

### Les commissions

| Commission | Base de calcul | Formule |
|---|---|---|
| **CPFD** (commission du plus fort découvert) | Le **plus fort découvert de CHAQUE MOIS CIVIL** | Σ (plus fort découvert du mois) × taux |
| **Commission de dépassement** | Le dépassement du **plafond négocié**, par mois civil | Σ (découvert − plafond) × taux, **si positif** |
| **Commission de compte** | Les **mouvements débiteurs** (hors exonérations) | (mouvements − exonérés) × taux |

> **★ Le piège de la CPFD** : on prend **le plus fort découvert de chaque mois civil**, et on **additionne** les mois. Si le découvert de 200 000 € s'étale sur mai ET juin, il compte **deux fois** : `(200 000 + 200 000) × taux`.
>
> **Ne prends jamais « le plus fort découvert de la période ». C'est mois par mois.**

### Le taux réel et le TAEG

```
╔═══════════════════════════════════════════════════════════════╗
║   Taux réel = (Agios HT × 365) / Total des nombres débiteurs  ║
║                                                               ║
║   TAEG (%)  = (Agios HT retenus × 36 500) / Nombres débiteurs ║
╚═══════════════════════════════════════════════════════════════╝
```

> **La différence** : le TAEG **ne retient pas toutes les commissions** (certaines commissions bancaires sont légalement exclues du TAEG). Le taux réel les retient toutes. Si l'énoncé ne précise rien, calcule le **taux réel**.

### ★ TOUTES LES INCONNUES DU DÉCOUVERT

**① Les agios (cas normal)**
> *Découvert de 200 000 € du 24/05 au 12/06 inclus. Taux 6,85 %, CPFD 0,05 % par mois civil.*
```
Jours : (31 − 24 + 1) + 12 = 8 + 12 = 20 jours
Nombres débiteurs = 200 000 × 20 = 4 000 000
Intérêts = 4 000 000 × 6,85/36 000 = 761,11 €
CPFD : plus fort découvert de mai = 200 000 ; de juin = 200 000
       (200 000 + 200 000) × 0,05 % = 200,00 €
AGIOS HT = 961,11 €
```

**② Le taux réel**
```
tr = 961,11 × 365 / 4 000 000 = 8,77 %
```

**③ ★ Un solde débiteur inconnu (exercice 4 du TD)**
> *Trois découverts : 18 300 € pendant 10 jours, 4 200 € pendant 5 jours, et X pendant 6 jours. Total des nombres débiteurs = 241 500. Calculer X.*
```
(18 300 × 10) + (4 200 × 5) + (X × 6) = 241 500
183 000 + 21 000 + 6X = 241 500
```
*(Note : le corrigé du TD écrit 2 100 au lieu de 21 000 ; en refaisant proprement : 4 200 × 5 = 21 000, donc 6X = 37 500 → X = 6 250 €. Le corrigé arrive au même X = 6 250 par une coquille compensée. **Fie-toi à ta propre équation.**)*

**④ Le nombre de jours**
> *Un découvert de 200 000 € a généré 4 000 000 de nombres débiteurs.*
```
j = 4 000 000 / 200 000 = 20 jours
```

**⑤ Le taux du découvert**
> *Les intérêts débiteurs sont de 761,11 € pour 4 000 000 de nombres débiteurs.*
```
t = 761,11 × 36 000 / 4 000 000 = 6,85 %
```

**⑥ Les agios à partir du taux réel**
```
Agios HT = taux réel × Nombres débiteurs / 365 = 0,0877 × 4 000 000/365 = 961 €
```

## 6.6 ★ L'ARBITRAGE ESCOMPTE / DÉCOUVERT — l'exercice roi du chapitre

Cet exercice est présent dans le **cours**, dans le **TD**, dans un **sujet d'annales que tu as en annexe** et dans le **CC3**. C'est le plus probable de tout le chapitre 6.

### La méthode en 6 étapes

```
ÉTAPE 1 — Sélectionner les effets à escompter
  → On ne peut escompter que les effets dont l'ÉCHÉANCE EST POSTÉRIEURE
    à la fin du déficit (sinon ils seraient encaissés naturellement).
  → On prend d'abord les échéances les PLUS PROCHES (moins de jours = moins d'intérêts).
  → On s'arrête dès que le total COUVRE le déficit.
  → À couverture équivalente, préférer PEU d'effets (moins de commissions fixes).

ÉTAPE 2 — Calculer l'agio de l'escompte
  → Par groupe d'échéance : VN × t × (jours + jours de banque)/360
  → + commissions × nombre d'effets

ÉTAPE 3 — Calculer le coût du découvert
  → Tableau : dates | nb de jours | solde débiteur | nombres débiteurs
  → Intérêts = Σ nombres débiteurs × t/36 000
  → + CPFD (mois par mois !) + commission de dépassement

ÉTAPE 4 — Calculer les taux réels (pour comparer en %)

ÉTAPE 5 — Éventuellement, la solution MIXTE
  → Escompte des effets les plus proches + découvert pour le solde

ÉTAPE 6 — Conclure sur DEUX critères : le coût absolu (€) ET le taux réel (%)
```

### Le tableau de comparaison (à reproduire)

```
┌───────────────────────────────┬──────────────┬──────────────┐
│                               │   ESCOMPTE   │   DÉCOUVERT  │
├───────────────────────────────┼──────────────┼──────────────┤
│ Intérêts / escompte           │              │              │
│ Commissions                   │              │              │
│ AGIO HT                       │              │              │
│ Taux réel                     │              │              │
└───────────────────────────────┴──────────────┴──────────────┘
```

### ★ Le piège du commentaire

Regarde attentivement le corrigé de l'annale « Escompte vs découvert 1 » :

> *« Le découvert est plus coûteux que l'escompte (15,15 % contre 12,84 %) : de nombreuses commissions s'ajoutent au taux de base bancaire. **Toutefois, dans l'absolu (81,94 < 133,08), le découvert est plus intéressant que l'escompte.** C'est un mode de financement plus souple qui s'adapte à la durée et au montant des besoins. »*

**Les deux critères peuvent se contredire !**
- Le **taux réel** dit : le découvert est plus cher (en %)
- Le **montant absolu** dit : le découvert coûte moins cher (en €)

**Pourquoi ?** Parce que l'escompte **sur-finance** : on mobilise la valeur nominale entière des effets sur toute leur durée, alors qu'on n'avait besoin que d'une partie, et moins longtemps. Le découvert, lui, **épouse exactement le besoin**.

> **La phrase à écrire dans ta conclusion :** *« Le découvert est un mode de financement plus souple, qui s'adapte à la durée et au montant exacts du besoin, alors que l'escompte impose de mobiliser la valeur nominale intégrale des effets. C'est ce qui explique qu'il puisse coûter moins cher en valeur absolue tout en affichant un taux réel supérieur. »*
>
> Et l'argument inverse quand il faut : *« L'escompte présente l'avantage de ne pas consommer l'autorisation de découvert et de transférer le recouvrement à la banque. »*

### Application au CC3 2025-2026 (partie III)

*Déficit de 200 000 € du 24/05 au 12/06 inclus. Effets : 80 000 + 65 500 + 21 000 à échéance 15/06 ; 40 000 + 20 000 + 5 000 + 3 000 à échéance 20/06. Escompte : 6,30 %, 2,40 € HT/effet, 1 jour de banque. Découvert : 6,85 %, CPFD 0,05 % par mois civil.*

**Q1 — Quels effets escompter ?**
```
Toutes les échéances (15/06 et 20/06) sont postérieures au 12/06 : tous sont éligibles.
On privilégie les échéances les plus proches → les 3 effets du 15/06 = 166 500 €
166 500 < 200 000 → il manque 33 500 €
Dans le lot du 20/06 : 20 000 + 5 000 + 3 000 = 28 000 → INSUFFISANT
                       40 000 → suffit, et c'est UN SEUL effet (2,40 € de commission au lieu de 7,20 €)

→ On escompte 4 effets : 80 000, 65 500, 21 000 (15/06) et 40 000 (20/06) = 206 500 €
```

**Q2 — L'agio de l'escompte**
```
Jours du 24/05 au 15/06 : (31 − 24) + 15 = 22 jours  + 1 jour de banque = 23
Jours du 24/05 au 20/06 : (31 − 24) + 20 = 27 jours  + 1 jour de banque = 28

Escompte 15/06 : 166 500 × 0,063 × 23/360 = 670,16
Escompte 20/06 :  40 000 × 0,063 × 28/360 = 196,00
Commissions    :  4 × 2,40                =   9,60
──────────────────────────────────────────────────
AGIO HT                                   = 875,76 €
```

**Q3 — Le coût du découvert**
```
Jours du 24/05 au 12/06 INCLUS : (31 − 24 + 1) + 12 = 20 jours
Nombres débiteurs = 200 000 × 20 = 4 000 000
Intérêts = 4 000 000 × 6,85 / 36 000       = 761,11
CPFD (mai 200 000 + juin 200 000) × 0,05 % = 200,00
──────────────────────────────────────────────────
AGIOS HT                                   = 961,11 €
```

**Q4 — Le taux réel du découvert**
```
tr = 961,11 × 365 / 4 000 000 = 8,77 %
```

**Q5 — La solution mixte**
```
Escompte des 3 effets du 15/06 : 670,16 + (3 × 2,40) = 677,36
Découvert du solde 200 000 − 166 500 = 33 500 € pendant 20 jours :
   Nombres débiteurs = 670 000
   Intérêts = 670 000 × 6,85/36 000 = 127,49
   CPFD = (33 500 + 33 500) × 0,05 % = 33,50
   Sous-total découvert = 160,99
──────────────────────────────────────────────────
COÛT TOTAL DE LA SOLUTION MIXTE = 838,35 €
```

**Q6 — Conclusion**
```
Solution mixte  : 838,35 €   ← LA MOINS CHÈRE
Escompte seul   : 875,76 €
Découvert seul  : 961,11 €
```
> *La solution mixte est optimale : elle combine le taux le plus bas (escompte à 6,30 % contre 6,85 %) sur la partie prévisible du besoin, et la souplesse du découvert pour l'appoint, sans mobiliser inutilement un effet de 40 000 € pour couvrir un besoin résiduel de 33 500 €. L'escompte seul entraîne un sur-financement de 6 500 €. Le découvert seul est le plus coûteux, pénalisé par un taux supérieur et par une CPFD calculée sur deux mois civils.*

---

# CHAPITRE 7 — LES INTÉRÊTS COMPOSÉS

## 7.1 À quoi ça sert ?

> **Intérêts simples** : les intérêts sont calculés sur le capital **initial**. → opérations **< 1 an**
> **Intérêts composés** : les intérêts produisent eux-mêmes des intérêts (**capitalisation**). → opérations **> 1 an**

C'est le fondement de tout raisonnement financier long terme : placements, emprunts, choix d'investissement, comparaison de flux à des dates différentes.

## 7.2 Les 4 formules de base et leurs inversions

```
╔═══════════════════════════════════════════════════════════════════════╗
║  Valeur acquise    :  Cₙ = C₀ (1 + t)ⁿ                                ║
║  Valeur d'origine  :  C₀ = Cₙ (1 + t)⁻ⁿ = Cₙ / (1 + t)ⁿ               ║
║  Durée             :  n  = ln(Cₙ / C₀) / ln(1 + t)                    ║
║  Taux              :  t  = (Cₙ / C₀)^(1/n) − 1                        ║
║  Intérêts totaux   :  I  = Cₙ − C₀ = C₀ [(1 + t)ⁿ − 1]                ║
╚═══════════════════════════════════════════════════════════════════════╝
```

**Les 4 inconnues, exemple unique (C₀ = 12 000, t = 3 %, n = 6 ans, C₆ = 14 328,63) :**

| Inconnue | Calcul | Résultat |
|---|---|---|
| **Cₙ** | 12 000 × 1,03⁶ | 14 328,63 |
| **C₀** | 14 328,63 / 1,03⁶ | 12 000 |
| **n** | ln(14 328,63/12 000) / ln(1,03) | 6 ans |
| **t** | (14 328,63/12 000)^(1/6) − 1 | 3 % |

> **Sur ta calculatrice** : `ln` pour la durée, `^(1/n)` ou `x√` pour le taux. Entraîne-toi **avant** l'épreuve : c'est là que beaucoup perdent du temps.

## 7.3 Taux proportionnels vs taux équivalents

### La distinction (question de cours quasi certaine)

**Taux PROPORTIONNELS** — on divise bêtement :
> *Deux taux sont proportionnels s'ils sont dans le même rapport que les périodes auxquelles ils s'appliquent : t₁/t₂ = d₁/d₂*

```
ts = ta / 2      tt = ta / 4      tm = ta / 12
```

**Taux ÉQUIVALENTS** — ils donnent la **même valeur acquise** :
> *Un taux tₘ relatif à une période p₁ et un taux tₐ relatif à une période p₂ sont équivalents si, appliqués à un même capital pendant une même durée, ils conduisent à des valeurs acquises égales.*

```
(1 + t_période)^k = 1 + ta
```

### Le tableau complet des taux équivalents

| Je connais | Je cherche | Formule |
|---|---|---|
| Taux **annuel** ta | Taux **semestriel** | ts = (1 + ta)^(1/2) − 1 |
| Taux **annuel** ta | Taux **trimestriel** | tt = (1 + ta)^(1/4) − 1 |
| Taux **annuel** ta | Taux **mensuel** | tm = (1 + ta)^(1/12) − 1 |
| Taux **semestriel** ts | Taux **annuel** | ta = (1 + ts)² − 1 |
| Taux **trimestriel** tt | Taux **annuel** | ta = (1 + tt)⁴ − 1 |
| Taux **mensuel** tm | Taux **annuel** | ta = (1 + tm)¹² − 1 |
| Taux **mensuel** tm | Taux **trimestriel** | tq = (1 + tm)³ − 1 |
| Taux **trimestriel** tt | Taux **mensuel** | tm = (1 + tt)^(1/3) − 1 |

> **★ La règle universelle** : `(1 + t_court)^(nombre de périodes courtes dans la période longue) = (1 + t_long)`.
> Tu n'as **qu'une** formule à retenir. Tout le reste s'en déduit.

### Quand utilise-t-on lequel ?

| | Usage |
|---|---|
| **Taux proportionnel** | Opérations de **moins d'un an** (escompte, découvert). Les **banques l'utilisent pour les EMPRUNTS** (à leur avantage). |
| **Taux équivalent** | Opérations de **plus d'un an** (placements, emprunts long terme). Utilisé le plus souvent pour les **PLACEMENTS**. |

> **La démonstration à connaître** (elle tombe régulièrement) : à intérêts composés, **deux taux proportionnels ne donnent PAS la même valeur acquise** ; deux taux équivalents oui.
> ```
> 20 000 à 6 % annuel pendant 2 ans     : 20 000 × 1,06²  = 22 472 €
> 20 000 à 3 % semestriel (proportionnel) pendant 4 semestres : 20 000 × 1,03⁴ = 22 510 €   ≠
> 20 000 à 2,956 % semestriel (équivalent) pendant 4 semestres : 20 000 × 1,02956⁴ = 22 472 €  ✅
> ```
> **Le taux proportionnel avantage le prêteur.** C'est pour ça que les banques l'utilisent sur les emprunts.

## 7.4 L'équivalence de capitaux

### Le principe

> **Deux capitaux disponibles à des dates différentes sont équivalents si, ramenés à une même date, ils ont la même valeur.**

**La règle d'or : on choisit une date de référence, et on ramène TOUT à cette date.** Le choix de la date ne change jamais la conclusion — choisis celle qui simplifie le plus les calculs (souvent la date 0).

### La méthode en 4 étapes

```
1. Trace un AXE DU TEMPS. Place tous les flux avec leur date et leur signe.
   Encaissements au-dessus, décaissements en dessous.
2. Choisis une date de référence.
3. Écris l'égalité : Σ(flux entrants actualisés) = Σ(flux sortants actualisés)
4. Résous.
```

> **L'axe du temps n'est pas une décoration.** C'est ce qui t'empêche de te tromper d'exposant. Trace-le systématiquement, même pour un exercice « simple ».

### Exemple type (TD exercice 4)

> *Une banque met 40 000 € à disposition le 01/03/N, puis 20 000 € six mois plus tard. L'entreprise rembourse en deux versements égaux V le 01/03/N+2 et le 01/03/N+4. Taux 8 %.*

```
Date de référence : le 01/03/N (époque 0)

40 000 + 20 000 × 1,08^(−0,5)  =  V × 1,08^(−2) + V × 1,08^(−4)
40 000 + 19 245                =  V × (0,857339 + 0,735030)
59 245                         =  V × 1,592369
                                  V = 37 206 €
```

### ★ Le changement de variable et l'équation du second degré

**C'est LE format que ton prof affectionne** : il te donne systématiquement le rappel du discriminant dans l'énoncé (dans le CC1 2023-2024, dans le CC3, dans « Remboursement d'un capital »). **Quand tu vois ce rappel, tu sais que l'exercice se ramène à un trinôme.**

**La technique :**
```
1. Pose  x = (1 + t)^(±1)  ou  x = (1 + t)^n   selon ce qui simplifie
2. Réécris l'équation en x → tu obtiens ax² + bx + c = 0
3. Δ = b² − 4ac
4. x = (−b ± √Δ) / 2a
5. ÉCARTE la solution qui donne un taux négatif ou impossible
6. Reviens à t
```

### ★ Application : le CC3 2025-2026, partie IV (corrigé complet)

> *Un capital de 75 000 € est placé à intérêts composés avec capitalisation MENSUELLE. 17 mois après, on ajoute 20 000 €. 17 mois après ce second versement, la valeur acquise est de 102 260 €. Quel est le taux mensuel ?*

**Étape 1 — l'axe du temps (en MOIS, puisque la capitalisation est mensuelle) :**
```
  mois 0            mois 17                        mois 34
    │                  │                              │
 +75 000           +20 000                       = 102 260
```
Le premier capital est placé **34 mois**, le second **17 mois**.

**Étape 2 — l'équation :**
```
75 000 (1+t)³⁴  +  20 000 (1+t)¹⁷  =  102 260
```

**Étape 3 — le changement de variable.** On pose **x = (1+t)¹⁷**, donc `(1+t)³⁴ = x²` :
```
75 000 x² + 20 000 x − 102 260 = 0
```

**Étape 4 — le discriminant :**
```
Δ = b² − 4ac = 20 000² − 4 × 75 000 × (−102 260)
Δ = 400 000 000 + 30 678 000 000 = 31 078 000 000
√Δ = 176 289,53
```

**Étape 5 — les racines :**
```
x₁ = (−20 000 − 176 289,53) / 150 000 = − 1,3086   →  IMPOSSIBLE (x = (1+t)¹⁷ > 0)
x₂ = (−20 000 + 176 289,53) / 150 000 =   1,04193  →  RETENU
```

**Étape 6 — retour au taux mensuel :**
```
(1 + t)¹⁷ = 1,04193
1 + t = 1,04193^(1/17) = 1,0024191

        ╔═══════════════════════════════════╗
        ║   tm = 0,2419 %  par mois         ║
        ╚═══════════════════════════════════╝
```

**Q2 — Le taux trimestriel équivalent** (1 trimestre = 3 mois) :
```
tt = (1 + tm)³ − 1 = 1,0024191³ − 1 = 0,7275 %
```

**Q3 — Le taux annuel équivalent** (1 an = 12 mois) :
```
ta = (1 + tm)¹² − 1 = 1,0024191¹² − 1 = 2,9419 %  ≈ 2,94 %
```

**Vérification** (fais-la toujours, elle coûte 20 secondes) :
```
75 000 × 1,0024191³⁴ + 20 000 × 1,0024191¹⁷ = 81 440 + 20 839 = 102 260 ✅
```

### Autres cas classiques d'équation du second degré

**Cas A — « Remboursement d'un capital » (annale fournie)**
> *On emprunte 5 000 €. On rembourse 3 000 € la 1ʳᵉ année et 3 000 € la 2ᵉ. Quel taux ?*
```
5 000 = 3 000 (1+t)⁻¹ + 3 000 (1+t)⁻²
On pose X = (1+t)⁻¹ :
5 000 = 3 000 X + 3 000 X²      →      3 X² + 3 X − 5 = 0
Δ = 9 + 60 = 69 ;  √69 = 8,3066
X₁ = (−3 − 8,3066)/6 = −1,884  →  t = (1/−1,884) − 1 < 0  →  IMPOSSIBLE
X₂ = (−3 + 8,3066)/6 =  0,8844 →  t = (1/0,8844) − 1 = 13,07 %  ✅
```
*(le corrigé du prof indique 13,12 %, écart d'arrondi sur √69 ; les deux sont acceptables — pose bien ton calcul)*

**Cas B — CC1 2023-2024, exercice 1**
> *Un emprunt de 6 000 € est remboursé par une annuité de 4 000 € l'année 1 et 3 000 € l'année 2.*
```
6 000 = 4 000 X + 3 000 X²   avec X = (1+t)⁻¹
3 X² + 4 X − 6 = 0
Δ = 16 + 72 = 88 ; √88 = 9,3808
X₂ = (−4 + 9,3808)/6 = 0,89680
t = 1/0,89680 − 1 = 11,51 %
```

**Cas C — TD exercice 5**
> *On place 10 000 €. Un an après on retire 10 000 €. Au bout de 2 ans il reste 500 €.*
```
Après 1 an : 10 000(1+t) − 10 000 = 10 000 t
Après 2 ans : 10 000 t (1+t) = 500
10 000 t² + 10 000 t − 500 = 0
Δ = 10 000² + 4 × 10 000 × 500 = 120 000 000 ;  √Δ = 10 954
t = (−10 000 + 10 954)/20 000 = 4,77 %
```

## 7.5 ★ L'INTERPOLATION LINÉAIRE

### Quand l'utiliser

Quand l'équation ne se résout **pas** algébriquement (puissances multiples et non réductibles à un trinôme). **L'énoncé te met alors toujours sur la voie** avec une mention du type *« taux compris entre 7,5 % et 8 % »*.

### La méthode

```
1. Calcule la valeur de l'expression pour la borne BASSE  → V₁
2. Calcule la valeur de l'expression pour la borne HAUTE  → V₂
3. Applique la proportionnalité :

       t₁ − t₂         V₁ − V₂                        (t₁ − t₂) × (V₁ − Vcible)
    ───────────  =  ───────────      →     t = t₁ − ─────────────────────────
       t₁ − t          V₁ − Vcible                        V₁ − V₂
```

### Exemple (TD exercice 4, question 2)

> *40 000 + 20 000(1+t)⁻⁰·⁵ = 37 000(1+t)⁻² + 37 000(1+t)⁻⁴. Taux compris entre 7,5 % et 8 %.*
```
On ramène tout à une expression comparable :
   4 = 3,7 × [(1+t)⁻² + (1+t)⁻⁴] − 2(1+t)⁻⁰·⁵

Si t = 8,0 %  →  membre de droite = 3,97   (< 4)
Si t = 7,5 %  →  membre de droite = 4,04   (> 4)
La cible 4,00 est donc entre les deux.

      0,08 − t          3,97 − 4,00
   ─────────────  =  ─────────────────
    0,08 − 0,075       3,97 − 4,04

   0,08 − t = 0,005 × (−0,03)/(−0,07) = 0,005 × 0,4286 = 0,00214
   t = 0,0779  →  7,79 %
```

### La règle qui évite l'erreur de sens

> **Vérifie la MONOTONIE** : plus le taux monte, plus les valeurs actualisées baissent. Donc si ta cible est *entre* V₁ et V₂, ton taux est *entre* t₁ et t₂. **Si tu trouves un taux hors de l'intervalle annoncé par l'énoncé, tu t'es trompé de sens.** C'est ton filet de sécurité.

## 7.6 Les suites d'annuités (valeur acquise et valeur actuelle)

Ces formules apparaissent dans l'annale « Intérêts composés 3 » et sont indispensables dès qu'il y a des **versements réguliers**.

```
╔═════════════════════════════════════════════════════════════════════════╗
║  Valeur ACQUISE d'une suite de n versements a (fin de période) :        ║
║                                                                         ║
║          Vₙ = a × [(1 + t)ⁿ − 1] / t                                    ║
║                                                                         ║
║  Valeur ACTUELLE d'une suite de n versements a :                        ║
║                                                                         ║
║          V₀ = a × [1 − (1 + t)⁻ⁿ] / t                                   ║
╚═════════════════════════════════════════════════════════════════════════╝
```

**Les inversions :**

| Inconnue | Formule |
|---|---|
| **a** (le versement) à partir de V₀ | a = V₀ × t / [1 − (1+t)⁻ⁿ] |
| **a** à partir de Vₙ | a = Vₙ × t / [(1+t)ⁿ − 1] |
| **n** à partir de V₀ | (1+t)⁻ⁿ = 1 − V₀t/a → n = −ln(1 − V₀t/a) / ln(1+t) |
| **n** à partir de Vₙ | n = ln(1 + Vₙt/a) / ln(1+t) |
| **t** | pas de solution analytique → **interpolation linéaire** |

### Exemple complet (annale « Intérêts composés 3 »)

> *Une personne place 1 000 € par an pendant 20 ans (à partir de la date 1) et retire 5 000 € tous les 5 ans. Au taux de 4 %, que reste-t-il au bout de 20 ans ?*

```
VERSEMENTS — suite de 20 annuités de 1 000 € :
   V₂₀ = 1 000 × [(1,04)²⁰ − 1] / 0,04 = 1 000 × 29,778 = 29 778 €

RETRAITS — 4 retraits de 5 000 € aux dates 5, 10, 15 et 20.
Il faut les capitaliser jusqu'à la date 20 :
   V₂₀ = 5 000 × 1,04^(20−5) + 5 000 × 1,04^(20−10) + 5 000 × 1,04^(20−15) + 5 000 × 1,04^(20−20)
   V₂₀ = 5 000 (1,04¹⁵ + 1,04¹⁰ + 1,04⁵ + 1,04⁰)
   V₂₀ = 5 000 × (1,8009 + 1,4802 + 1,2167 + 1) = 5 000 × 5,4978 = 27 489 €

RESTE SUR LE COMPTE : 29 778 − 27 489 = 2 289 €
```

> **Le point de méthode** : les retraits ne forment pas une suite d'annuités régulière au sens de la formule (période de 5 ans, pas 1 an). On les capitalise donc **un par un** jusqu'à la date finale. **L'axe du temps est indispensable ici.**

## 7.7 Le choix entre deux modes de paiement

> *Mode 1 : 1 000 € dans 1 an, 1 000 € dans 2 ans, 1 000 € dans 3 ans.*
> *Mode 2 : 2 000 € dans 2 ans et 800 € dans 3 ans.*

**Q1 — Au taux de 5 %, quel mode choisir ?**
```
Mode 1 : V₀ = 1 000(1,05⁻¹ + 1,05⁻² + 1,05⁻³) = 1 000 × 2,7232 = 2 723 €
Mode 2 : V₀ = 2 000 × 1,05⁻² + 800 × 1,05⁻³   = 1 814 + 691   = 2 505 €
```
**Pour l'ACHETEUR (celui qui paie), le mode 2 est préférable : il coûte moins cher en valeur actuelle.**

> ⚠️ **Précise toujours de quel point de vue tu te places !** Ce qui est bon pour l'acheteur est mauvais pour le vendeur. Le correcteur attend cette précision.

**Q2 — À quel taux les deux modes sont-ils équivalents ?**
```
1 000x + 1 000x² + 1 000x³ = 2 000x² + 800x³     avec x = (1+t)⁻¹
On divise par x (x ≠ 0) :
1 000 + 1 000x + 1 000x² = 2 000x + 800x²
200x² − 1 000x + 1 000 = 0     →     x² − 5x + 5 = 0
Δ = 25 − 20 = 5 ; √5 = 2,236
x₁ = (5 + 2,236)/2 = 3,618  →  t = 1/3,618 − 1 = − 72 %   IMPOSSIBLE
x₂ = (5 − 2,236)/2 = 1,382  →  t = 1/1,382 − 1 = − 27,6 % IMPOSSIBLE
```
**Conclusion : il n'existe pas de taux positif rendant ces deux modes équivalents. Le mode 2 est toujours préférable à l'acheteur.**
> **C'est une réponse parfaitement valable.** N'invente pas un résultat : écris que les deux racines conduisent à des taux négatifs, donc économiquement impossibles, et conclus.

**Q3 — Quelle somme m verser dans le mode 1 pour l'équivalence ?**
```
m(1,05⁻¹ + 1,05⁻² + 1,05⁻³) = 2 505
2,7232 m = 2 505
m = 919,9 €
```

---

# ANNEXE A — CHAPITRE BONUS (probablement hors programme)

> ⚠️ **Rappel** : ce contenu vient du **CC1 2023-2024** et du **corrigé de renégociation de prêt**, qui appartiennent selon toute vraisemblance à une **autre matière** (Politique de financement / Mathématiques financières). Le polycopié de Finance d'entreprise ne contient **aucun** de ces chapitres.
>
> **Ne révise ça qu'en dernier, et seulement si tu as fini le reste.** Cette annexe est une assurance, pas une priorité.

## A.1 Les emprunts indivis (annuités constantes)

### La formule de l'annuité constante

```
                 C₀ × t
    a  =  ────────────────────
           1 − (1 + t)⁻ⁿ
```
où C₀ = capital emprunté, t = taux de la période, n = nombre de périodes.

**Toutes les inversions :**

| Inconnue | Formule |
|---|---|
| **a** (annuité) | a = C₀ t / [1 − (1+t)⁻ⁿ] |
| **C₀** (capital) | C₀ = a [1 − (1+t)⁻ⁿ] / t |
| **n** (durée) | n = −ln(1 − C₀t/a) / ln(1+t) |
| **t** (taux) | pas de solution analytique → **interpolation linéaire** |

### Le tableau d'amortissement

```
┌────────┬──────────────┬───────────────┬────────────────┬──────────┐
│ Période│Capital début │   Intérêt     │ Amortissement  │ Annuité  │
│        │  = D(k−1)    │ = D(k−1) × t  │  = a − intérêt │   = a    │
└────────┴──────────────┴───────────────┴────────────────┴──────────┘
```
**Capital début de période k+1 = Capital début de période k − Amortissement k**

### Les lois des amortissements (elles évitent de dérouler tout le tableau)

```
Les amortissements sont en PROGRESSION GÉOMÉTRIQUE de raison q = (1 + t)

    A_k  =  A₁ × (1 + t)^(k−1)

    C₀  =  A₁ × [(1 + t)ⁿ − 1] / t

Capital restant dû après k périodes :
    D_k  =  C₀ − A₁ × [(1 + t)^k − 1] / t
    D_k  =  a × [1 − (1 + t)^(−(n−k))] / t
```

> **Le raccourci du corrigé de renégociation** : pour trouver le capital restant dû au début de la 97ᵉ mensualité, on calcule A₉₇ = A₁ × (1+t)⁹⁶, puis l'intérêt = a − A₉₇, puis **D₉₆ = intérêt / t**. C'est bien plus rapide que 96 lignes de tableau.

### Annuité théorique vs annuité réelle

```
Annuité RÉELLE = Annuité théorique + Assurance + Frais
```
Les frais sont souvent calculés sur le **capital restant dû** (donc décroissants).

## A.2 TAEG et taux réel

| | Ce qu'il inclut |
|---|---|
| **Taux nominal** | Rien d'autre que les intérêts |
| **TAEG** | Intérêts + frais obligatoires + **assurance obligatoire** |
| **Taux réel (de revient)** | Intérêts + **tous** les frais, y compris assurance facultative |

> **Si la banque ne facture ni frais ni assurance obligatoire, TAEG = taux nominal.** (C'est la réponse à la question 1 du CC1 2023-2024.)

**La méthode de calcul** : on cherche le taux qui égalise le capital emprunté et la valeur actuelle des flux réellement décaissés :
```
C₀ = Σ (annuité réelle_k) × (1 + TAEG)^(−k)
```
→ Se résout par **interpolation linéaire** (l'énoncé donne toujours l'encadrement).

## A.3 Choix d'investissement : CAF d'exploitation, FNT, VAN, TIR

### Le tableau des CAF d'exploitation

```
    Chiffre d'affaires
  − Charges variables
  − Charges fixes (hors DAP)
  − Dotations aux amortissements
  ═══════════════════════════════
  = Résultat avant impôts
  × (1 − taux d'IS)
  ═══════════════════════════════
  = Résultat après impôts
  + Dotations aux amortissements       ← on les rajoute : non décaissables
  ═══════════════════════════════
  = CAF d'exploitation
```

### Le tableau des flux nets de trésorerie (FNT)

```
                        Début N   Fin N   Fin N+1  ...  Fin N+4
  CAF d'exploitation               X        X            X
  − Investissement       −I
  − Variation du BFR     −BFR₀    −ΔBFR   −ΔBFR         −ΔBFR
  + Récupération du BFR                                  +BFR cumulé
  + Valeur résiduelle de cession                         +VR
  ═══════════════════════════════════════════════════════════════
  = FNT                  −I−BFR₀    X        X          X+BFR+VR
```

> **Deux points qui coûtent des points** :
> 1. Le **BFR initial** est décaissé **au début** (avec l'investissement), et sa **variation** chaque année.
> 2. Le **BFR est RÉCUPÉRÉ intégralement** en fin de projet (on encaisse les créances, on liquide les stocks). Ne l'oublie jamais.

### VAN et TIR

```
VAN = − I₀ + Σ FNT_k × (1 + i)^(−k)

TIR : le taux pour lequel la VAN est NULLE
      0 = − I₀ + Σ FNT_k × (1 + TIR)^(−k)
```

**Définition du TIR à connaître par cœur** (elle est demandée telle quelle dans le CC1 2023-2024) :
> *« Le TIR est un indicateur financier qui évalue la pertinence d'un investissement. C'est le taux de rentabilité minimum que doit avoir un investissement pour qu'il y ait équivalence entre son coût initial et ses flux de trésorerie futurs. **Le TIR est le taux pour lequel la VAN est nulle.** »*

**Règle de décision** : on retient le projet si **TIR > coût du capital** (ou si VAN > 0).

### Critères NON financiers de choix d'investissement (question de cours)

- La **taille** et la **durée** du projet
- Le **niveau de risque** : économique, environnemental, social, organisationnel, technologique
- La **cohérence avec la stratégie** de l'entreprise
- L'**impact sur l'organisation** de l'entreprise
- Les **conséquences sur les salariés** (compétences, emploi, conditions de travail)
- Les **contraintes logistiques**
- L'image, la conformité réglementaire, l'acceptabilité sociale

---

# ANNEXE B — LA BOÎTE À OUTILS DES COMMENTAIRES

Les questions « Commenter / Conclure » valent **1 à 3 points** et sont les plus rentables de l'épreuve. Voici une structure et des formulations réutilisables.

## B.1 La structure en 4 temps (fonctionne pour tout commentaire)

```
1. LE CONSTAT      → « Le FRNG est de X, le BFR de Y, il en résulte une TN de Z. »
2. L'EXPLICATION   → « Cette situation s'explique par… »
3. LA NUANCE       → « Toutefois… / Néanmoins… »   ← LE point qui distingue une bonne copie
4. LA RECOMMANDATION / QUESTION OUVERTE
```

## B.2 Phrases réutilisables

**Équilibre financier :**
> *« Le FRNG est positif et couvre [largement / partiellement] les besoins de l'activité (BFR) ; il en résulte une trésorerie [positive / négative]. »*
>
> *« Toutefois, cette situation n'est due qu'à un BFRHE négatif. Sans cela, la trésorerie serait négative (FRNG < BFRE). »*
>
> *« Pour les entreprises dont l'exploitation génère un BFR structurellement positif, il est bon que le FRNG soit supérieur au BFRE. Ce financement stable limite le recours aux concours bancaires qui, bien que reconductibles, peuvent être brutalement réduits. »*

**Croissance :**
> *« Au cours de la période, le FRNG augmente, mais le BFR croît [encore plus vite / dans une proportion moindre]. Il en résulte une [dégradation / amélioration] de la trésorerie. »*
>
> *« L'entreprise semble connaître une forte croissance, mais cette dernière n'est pas suffisamment maîtrisée. »*

**Trésorerie :**
> *« La trésorerie est pléthorique : l'entreprise ne fait pas fructifier ses liquidités. »*
>
> *« Le montant de la trésorerie de passif devient préoccupant, car le banquier pourrait sans préavis interrompre ce type de financement. »*
>
> *« L'entreprise se trouve en état de cessation de paiements (actif à moins d'un an < dettes à moins d'un an). Le tribunal de commerce pourrait ouvrir une procédure de redressement ou de liquidation judiciaire. »*

**Rentabilité et levier :**
> *« Tant que la rentabilité économique demeure supérieure au coût de la dette, plus l'entreprise s'endette, plus elle améliore sa rentabilité financière. Mais au-delà d'un certain niveau d'endettement, le prêteur refusera de prêter davantage ou élèvera son taux au-dessus de la rentabilité économique. »*
>
> *« L'effet de levier se transforme alors en effet de massue. »*

**BFR normatif :**
> *« Le BFR normatif représente X jours de CAHT, ce qui semble très élevé par rapport au secteur d'activité où il est en moyenne de Y jours. Plusieurs raisons : des délais de stockage plus longs, des délais de paiement consentis aux clients plus élevés. Si l'entreprise ramenait son BFR au niveau du secteur, elle économiserait Z € de trésorerie. »*

**Investissement :**
> *« L'entreprise a beaucoup investi, surtout par croissance interne, sans qu'il s'agisse d'un renouvellement de son outil de production : il s'agit d'accroître ses capacités productives pour gagner des parts de marché. »*

## B.3 Les 4 questions à te poser systématiquement devant un commentaire

```
1. La trésorerie est-elle positive, et POURQUOI ? (FRNG ? BFR ? BFRHE ?)
2. Y a-t-il des CBC ? (leur apparition est TOUJOURS un signal d'alarme à citer)
3. Quelle est la source du financement ? (activité / actionnaires / banques)
4. Quelle est la nature de la croissance ? (interne / externe / renouvellement)
```

---

# ANNEXE C — PLAN DE RÉVISION SUR 10 JOURS

| Jour | Contenu | Durée |
|---|---|---|
| **J−10** | Chapitre 0 + Chapitre 1 (bilan fonctionnel/financier). Refaire l'exercice 1 du TD | 3 h |
| **J−9** | Chapitre 2 (CAF, ETE, ESOG). Refaire l'exercice 1 et 2 du TD II | 3 h |
| **J−8** | Chapitre 3 (rentabilité, levier). Refaire le Cas 2010 du TD | 3 h |
| **J−7** | **CC1 2025-2026 en conditions réelles (2 h chrono)**, puis correction | 3 h |
| **J−6** | Chapitre 4 (BFR normatif). Refaire le Cas 2013 + l'annale DCG 2023 | 3 h |
| **J−5** | Chapitre 5 (tableau de flux). Refaire LVMH + Décorex | 3 h |
| **J−4** | **CC2 2025-2026 en conditions réelles**, puis correction | 3 h |
| **J−3** | Chapitres 6 et 7. Refaire tout le TD VI et VII | 4 h |
| **J−2** | **CC3 2025-2026 en conditions réelles** + banque d'exercices « toutes inconnues » | 4 h |
| **J−1** | Fiche mémo uniquement. Réécrire de mémoire : tableau de flux, tableau BFR normatif, formule du levier | 2 h |
| **Jour J** | Relecture de la fiche mémo le matin. Recopier le calendrier sur le brouillon dès le début de l'épreuve | 30 min |

## Le protocole des 5 premières minutes de l'épreuve

```
1. Recopie le calendrier :  J31 F28 M31 A30 M31 J30 J31 A31 S30 O31 N30 D31
2. Recopie les 3 formules pivots :
      TN = FRNG − BFR
      CAF = RNC + VCEAC − PCEA + DAP − RAP
      Rf = Re(1−s) + (Re − i)(D/CP)(1−s)
3. Lis TOUTES les questions de TOUS les exercices avant de commencer.
   → Repère lesquelles sont indépendantes (tu peux les traiter même si tu bloques avant).
4. Commence par l'exercice que tu maîtrises le mieux. Les points sont les mêmes.
```

## Les 10 réflexes qui sauvent des points

1. **Toujours poser la formule avant de mettre les chiffres.** Une formule juste avec un chiffre faux rapporte des points ; un chiffre juste sans formule n'en rapporte pas toujours.
2. **Bilan fonctionnel → BRUT. Bilan financier → NET. Tableau de flux (variation BFR) → NET.**
3. **Chercher la note de bas de bilan sur les CBC.** À chaque fois.
4. **Vérifier que le bilan fonctionnel s'équilibre.** 10 secondes.
5. **Vérifier que FRNG − BFR = TN.** 5 secondes.
6. **Vérifier que A + B + C = variation de trésorerie.** Écris-le.
7. **Vérifier que la CAF additive = la CAF soustractive.**
8. **Vérifier que Rf par la formule du levier = Rf directe.**
9. **Ne jamais laisser une question de commentaire vide.** Même 3 phrases valent mieux que rien.
10. **Si tu bloques sur une question, écris la formule et passe à la suivante.** Les questions sont souvent indépendantes.

---

*Bon courage. Tu as tout ce qu'il faut : le programme est fermé, les mécanismes sont peu nombreux, et tu connais désormais toutes les façons dont ils peuvent être retournés.*
