# Power BI – Expertise DAX : Contextes, patterns et calculs industrialisés
**Ref. PBI-DAX | M2i Formation | 1 jour (7h00)**

---

## Informations générales

| | |
|---|---|
| **Public** | Data Analysts confirmés, responsables projets Power BI, consultants BI |
| **Prérequis** | Cours PBI-PE suivi + pratique : créer des mesures DAX, utiliser CALCULATE, comprendre les contextes de ligne et de filtre |
| **Durée** | 1 jour — 4 demi-journées (1 compétence clé par demi-journée) |
| **Note** | 4,6/5 |

---

## Objectifs de formation

1. Consolider la compréhension des **contextes DAX**
2. Concevoir des **mesures avancées et fiables** pour des cas métier complexes
3. Exploiter les fonctions DAX avancées de **filtrage et de Time Intelligence**
4. Utiliser des **patterns DAX réutilisables** (comparaisons, cumul, part de total, classement)
5. Centraliser et maintenir les calculs avec les **Calculation Groups**
6. Améliorer la productivité via le **mode texte (PBIP / TMDL)** et l'**Intelligence Artificielle**

---

## Programme détaillé

### Matin — Bloc 1 : Consolider les contextes DAX

#### 1. Notions essentielles de contexte
- Rappels : contexte de ligne vs contexte de filtre
- **Transition de contexte** : vérification des acquis, erreurs courantes
- Pourquoi certaines mesures "semblent fonctionner" mais sont incorrectes

#### 2. Contrôler le filtre avec CALCULATE
- Fonctionnement réel de `CALCULATE` et ordre d'évaluation des filtres
- Fonctions clés : `ALL`, `ALLSELECTED`, `REMOVEFILTERS`, `VALUES`, `SELECTEDVALUE`
- Utilisation avancée de `FILTER()` — création de tables virtuelles

#### 3. Modifier le comportement des relations
- Fonction `CROSSFILTER`
- Cas d'usage : relations multiples, analyses comparées, scénarios métier spécifiques

> **TP indicatifs :** corriger des mesures avec totaux incohérents · mettre en œuvre CROSSFILTER

---

### Après-midi — Bloc 2 : Calculs avancés et industrialisation

#### 4. Time Intelligence avancée
- Limites des fonctions standards
- Fonctions : `DATESBETWEEN`, `DATESINPERIOD`, `DATEADD`, `PARALLELPERIOD`
- Cas d'usage : périodes glissantes, comparaisons personnalisées, cumul métier

#### 5. Patterns DAX avancés
- Comparaison N / N-1
- Part de total dynamique
- Classements évolutifs avec `RANKX`
- Gestion des totaux et sous-totaux complexes
- `ISINSCOPE` pour adapter les calculs au niveau d'analyse

#### 6. Centraliser les calculs avec les Calculation Groups
- Principe et intérêts — réduction de la duplication des mesures
- Cas d'usage typiques : Time Intelligence, variations, scénarios "what-if"

#### 7. Industrialiser et maintenir le DAX
- Organisation et conventions de nommage
- Travail en mode texte : **PBIP** et **vue TMDL**
- Renommer et refactoriser des mesures à grande échelle

#### 8. IA et productivité du développeur DAX
- Utiliser l'IA pour : comprendre, optimiser, refactoriser des mesures
- Générer ou ajuster des Calculation Groups
- Documenter son projet plus rapidement
- Bonnes pratiques et **limites de l'IA** sur le DAX

> **TP indicatifs :** créer un Calculation Group pour la Time Intelligence · refactoriser des mesures via mode texte et IA

---

## Structure synthétique (vue manuel)

```
Chapitre 1 — Les contextes DAX (rappels et transition)
Chapitre 2 — Maîtriser CALCULATE et le filtrage
Chapitre 3 — Relations et CROSSFILTER
Chapitre 4 — Time Intelligence avancée
Chapitre 5 — Patterns DAX réutilisables
Chapitre 6 — Calculation Groups
Chapitre 7 — Industrialisation : PBIP, TMDL, nommage
Chapitre 8 — IA et productivité DAX
```

---

*Programme M2i Formation — Ref. PBI-DAX — Contenu mis à jour le 04/02/2026*
