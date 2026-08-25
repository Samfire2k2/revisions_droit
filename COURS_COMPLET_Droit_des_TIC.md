# DROIT DES TIC — Cours complet de révision (M1 MIAGE, Nantes Université)
### Rattrapages — Samuel Ravard

> **Comment utiliser ce document.**
> Ce n'est pas un résumé : c'est un manuel autonome. Il est construit pour que tu puisses répondre à **n'importe quelle variante** du sujet, pas seulement aux cas déjà vus.
> Chaque notion est présentée avec : (1) le **principe** à réciter, (2) un **arbre de décision** couvrant *tous* les cas possibles, (3) un **exemple par valeur possible** de la variable, (4) les **pièges** que le prof exploite.
>
> **Plan :**
> - Partie 0 — Méthodologie (comment répondre, la structure de copie qui rapporte des points)
> - Partie 1 — Introduction générale au droit + **LES JURIDICTIONS** (le chapitre le plus rentable : il tombe à chaque CC)
> - Partie 2 — Propriété intellectuelle
> - Partie 3 — Contrat de travail & TIC
> - Partie 4 — RGPD
> - Partie 5 — Licences & logiciels
> - Partie 6 — Droit des contrats
> - Partie 7 — Contrats numériques & responsabilités
> - Partie 8 — Liberté d'expression, presse, réseaux sociaux
> - Partie 9 — Cybersécurité, cybercriminalité, cryptomonnaies
> - Partie 10 — Fiches mémo condensées (à relire la veille)
> - Partie 11 — Corrigés intégraux des CC récupérés + TD
> - Partie 12 — Banque de variantes : « et si le prof change X ? »

---

# PARTIE 0 — MÉTHODOLOGIE : COMMENT ON RÉPOND

## 0.1 Pourquoi le droit existe (le contexte, pour comprendre au lieu d'apprendre)

Le droit sert à **rendre la vie en société possible**. Il fait trois choses :

1. **Il organise** (qui décide quoi, quelles institutions, quels services publics).
2. **Il arbitre** (quand deux personnes s'opposent, il dit qui a raison et selon quelle règle).
3. **Il sanctionne** (sinon la règle ne serait qu'un conseil).

Dans un cours de **Droit des TIC**, l'idée est que le numérique **n'a pas son propre droit**. Il n'existe pas de « droit d'Internet ». Ce qui existe, c'est le droit général (contrats, travail, propriété, pénal) qu'on **applique** à des objets numériques : un logiciel, une base de données, un avis Google, une adresse IP, un tweet, un bitcoin.

**Conséquence pratique pour l'examen :** face à un cas numérique, ne cherche jamais « la règle spéciale d'Internet ». Cherche **la qualification juridique classique** :
- un logiciel → une **œuvre de l'esprit** (droit d'auteur) ;
- un avis en ligne → un **écrit rendu public** (loi de 1881 ou concurrence déloyale) ;
- une adresse IP → une **donnée à caractère personnel** (RGPD) ;
- une licence → un **contrat** ;
- un piratage → une **infraction pénale** (STAD).

## 0.2 La structure de réponse imposée (celle du prof)

Le prof note en **deux blocs**. Tu dois toujours écrire ces deux mots.

| Bloc | Contenu | Erreur fatale |
|---|---|---|
| **Principe** | La règle **abstraite**, sans citer les noms du sujet. « Le tribunal de commerce est compétent pour les litiges entre commerçants. » | Écrire le cas dans le principe |
| **Au cas présent** | L'application **aux faits**, en citant les noms/chiffres du sujet. « Mme M est commerçante, la SARL S aussi → TC. » | Répéter la règle sans l'appliquer |

Pour les questions plus lourdes (« commenter la décision », « exposer le litige »), la structure est en **4 lignes** :

| Rubrique | Ce qu'on écrit |
|---|---|
| **Les faits** | Résumé neutre, 2–3 phrases, sans qualification juridique |
| **Le problème juridique** | Une **question** commençant par « Un/Une… peut-il/elle… ? » ou « À qui incombe… ? » |
| **La règle de droit** | Le principe + si possible l'article ou l'arrêt |
| **La solution** | La réponse, avec justification, + la suite procédurale |

**Astuce de points faciles :** termine toujours par la **suite de l'affaire** quand il y a une Cour de cassation :
- *arrêt de rejet* → l'affaire est **terminée**, le demandeur est définitivement débouté ;
- *arrêt de cassation avec renvoi* → l'affaire est **rejugée par une autre cour d'appel**, car la Cour de cassation juge le **droit** et non les faits ;
- *arrêt de cassation sans renvoi* → procédure terminée.

## 0.3 La méthode « traduire en langage juridique »

Le sujet est écrit en français courant. Le prof attend que tu **retraduises** chaque expression. Table de conversion complète :

| Expression courante | Traduction juridique |
|---|---|
| « il est mort / décédé » | **Ouverture de la succession** |
| « sa femme, ses enfants » | Conjoint et descendants = **héritiers / ayants droit** |
| « il tient un commerce » | Il exploite un **fonds de commerce**, il a la qualité de **commerçant** |
| « il s'est marié » | Conclusion d'un **contrat de mariage**, régime matrimonial |
| « il a 25 ans » | Il est **majeur**, donc **capable** |
| « il a 15 ans » | **Mineur non émancipé**, **incapable** → nullité **relative** |
| « il a dérobé / volé » | **Vol** = soustraction frauduleuse de la chose d'autrui = **délit** |
| « ils ont voté » | Exercice des **droits politiques** (droit électoral) |
| « il loue un appartement » | **Bail** ; le locataire est **titulaire d'un bail** |
| « il ne paie plus le loyer » | Inexécution d'une **obligation contractuelle** |
| « un huissier » | **Commissaire de justice** / officier ministériel chargé des significations et de l'exécution forcée |
| « le traîner devant les tribunaux » | **Engager une action en justice** |
| « son voisin fait du bruit » | **Trouble anormal du voisinage** |
| « son chef le harcèle » | **Harcèlement moral** = délit (pénal) + litige du travail (CPH) |
| « son père veut la déshériter » | Litige **successoral** |
| « il conteste son avis d'imposition » | Litige **fiscal** → juridiction **administrative** |
| « le gouvernement a mené une réforme » | **Projet de loi** (initiative gouvernementale) ou **proposition de loi** (parlementaire) |
| « privatisation » | Transfert du domaine public au domaine privé |
| « une société est en cessation des paiements » | Droit des **entreprises en difficulté** → **TC** |
| « il a été licencié » | Rupture du contrat de travail à l'initiative de l'employeur |
| « il a démissionné » | Rupture à l'initiative du salarié |
| « des soucis » | **Litiges** potentiels, procès en perspective |

## 0.4 Le vocabulaire procédural (à connaître par cœur, ça tombe en définition)

| Terme | Définition à réciter |
|---|---|
| **Action en justice** | Possibilité offerte au justiciable de s'adresser à la justice pour faire reconnaître ses droits. |
| **Assignation** | Acte d'huissier par lequel le **demandeur** cite son adversaire à comparaître devant le juge. Elle marque le **début du procès**. |
| **Demandeur** | Celui qui agit, qui saisit le tribunal. |
| **Défendeur** | Celui contre qui on agit. (Ne pas écrire « défenseur » : c'est une faute qui revient dans les corrigés.) |
| **Ordonnance sur requête** | Décision **provisoire** rendue **non contradictoirement** (l'adversaire n'est pas prévenu), lorsque les circonstances exigent que la mesure ne soit pas prise à l'insu… c'est-à-dire quand l'effet de surprise est nécessaire. Typiquement : obtenir d'un hébergeur les données d'identification d'un auteur anonyme. |
| **Assignation en référé** | Acte par lequel on cite l'adversaire devant le **juge des référés** : procédure **d'urgence** et **contradictoire** (l'adversaire est présent ou appelé). |
| **Ordonnance de référé** | Décision **provisoire**, rendue à la demande d'une partie, l'autre présente ou appelée, dans les cas où la loi confère à un juge **non saisi du principal** le pouvoir d'ordonner immédiatement les mesures nécessaires (absence de contestation sérieuse, trouble manifestement illicite, dommage imminent). |
| **Juge du principal / le fond** | Le tribunal qui tranchera définitivement le litige (par opposition au juge des référés qui ne fait que du provisoire). |
| **Mesure d'instruction légalement admissible** | Mesure d'enquête ordonnée par le juge s'il existe un **motif légitime** de conserver ou d'établir la preuve de faits dont pourrait dépendre la solution d'un litige. |
| **Mise en demeure** | Sommation adressée au débiteur d'exécuter son obligation. Souvent **préalable obligatoire** aux dommages-intérêts. |
| **Saisie-contrefaçon** | Mesure ordonnée sur requête permettant à un huissier (assisté le cas échéant d'un expert) de constater matériellement la contrefaçon chez le suspect. **C'est un mode de preuve, pas une condamnation** (piège majeur du CC2). |
| **Astreinte** | Somme d'argent par jour de retard destinée à contraindre à exécuter (ex. 300 €/jour tant que l'avis n'est pas supprimé). |
| **Dommages-intérêts (DI)** | Réparation en argent du préjudice. |
| **Force exécutoire** | Un jugement peut être exécuté au besoin par la force publique. |
| **Autorité de la chose jugée** | Ce qui a été jugé est acquis et ne peut être remis en cause, sauf voies de recours. |
| **Voie de recours** | Possibilité pour la partie mécontente de faire réexaminer la décision (appel, pourvoi en cassation, opposition, tierce opposition, révision). |
| **Appel interjeté** | Recours devant la cour d'appel ; elle rejuge **les faits ET le droit** ; elle rend des **arrêts confirmatifs** ou **infirmatifs**. |
| **Pourvoi en cassation** | Recours devant la Cour de cassation, qui ne juge **que le droit**. |
| **« Fait grief à l'arrêt »** | Signale **le demandeur au pourvoi** : c'est celui qui critique la décision d'appel. Repère-le pour identifier qui a perdu en appel. |
| **« Attendu, selon l'arrêt attaqué »** | Introduit **les faits** et la procédure antérieure. |
| **« Mais attendu que… »** | Introduit la **position de la Cour de cassation** (elle rejette le moyen → rejet). |
| **« Qu'en statuant ainsi… a violé les textes susvisés »** | Annonce une **cassation**. |
| **« Vu l'article… »** | Le **visa** = la base légale. |

---

# PARTIE 1 — INTRODUCTION GÉNÉRALE AU DROIT

## 1.1 Les finalités et caractères de la règle de droit

**Finalités :** assurer l'ordre social, protéger l'intérêt général, organiser la société (services publics : éducation, armée, justice), garantir une justice non arbitraire, protéger les personnes et les biens.

**Caractères de la règle de droit** (question classique) :
- **Générale et impersonnelle** : elle s'applique à tous, elle n'est pas conçue pour un cas particulier.
- **Obligatoire / coercitive** : son non-respect est sanctionné par la puissance publique.
- **Permanente** : elle s'applique tant qu'elle n'est pas abrogée.

**Les sanctions :**

| Type | Objet | Exemples |
|---|---|---|
| **Civile** | Rétablir, réparer, contraindre | Contraindre à exécuter (pension alimentaire) ; annuler un acte illégal (achat par un mineur) ; réparer un préjudice (DI) |
| **Pénale** | **Punir** | Amende, emprisonnement |
| **Les deux** | Une infraction qui cause un préjudice privé | Vol → prison (pénal) + DI à la victime (civil) |

## 1.2 Les branches du droit — arbre de décision complet

C'est une question de CC récurrente : « déterminer la branche du droit ». Voici **toutes** les valeurs possibles.

```
Le litige implique-t-il l'ÉTAT / une ADMINISTRATION / une collectivité agissant comme puissance publique ?
│
├── OUI → DROIT PUBLIC
│     ├── Organisation des institutions politiques (Constitution, Parlement, élections nationales,
│     │   contrôle de constitutionnalité) ............................ DROIT CONSTITUTIONNEL
│     ├── Fonctionnement de l'administration, services publics, actes administratifs,
│     │   fiscalité, urbanisme, fonction publique, décisions de l'inspection du travail,
│     │   nationalité, droit électoral ................................ DROIT ADMINISTRATIF
│     └── Sanction d'une infraction (au nom de la société) ............ DROIT PÉNAL
│            (le droit pénal est classé en droit public car l'action publique
│             est exercée par le Ministère public au nom de la société)
│
└── NON → DROIT PRIVÉ
      ├── Rapports entre particuliers : personnes, famille, biens, contrats,
      │   responsabilité, successions, propriété, régimes matrimoniaux .. DROIT CIVIL
      ├── Actes de commerce, commerçants, sociétés commerciales,
      │   fonds de commerce, entreprises en difficulté .................. DROIT COMMERCIAL
      └── Relations individuelles et collectives de travail
          (contrat de travail, licenciement, clauses) ................... DROIT SOCIAL / DU TRAVAIL

Et transversalement :
Le litige comporte-t-il un ÉLÉMENT D'EXTRANÉITÉ (nationalités différentes, États différents) ?
├── Entre États / traités ............................................. DROIT INTERNATIONAL PUBLIC
└── Entre personnes privées de nationalités différentes ................ DROIT INTERNATIONAL PRIVÉ
```

**Un exemple par valeur possible :**

| Situation | Branche | Pourquoi |
|---|---|---|
| Un automobiliste renverse un piéton, qui demande réparation | **Civil** (responsabilité délictuelle) | Rapport entre particuliers, réparation d'un préjudice |
| Une société conteste un redressement fiscal | **Administratif** | Litige avec l'administration fiscale |
| Un voisin en frappe un autre | **Pénal** (+ civil pour les DI) | Coups et blessures = infraction |
| Ouverture d'une succession chez le notaire | **Civil** | Droit des successions |
| 60 sénateurs contestent une loi de finances | **Constitutionnel** | Contrôle de constitutionnalité |
| Un traité sur les OGM non ratifié à temps par deux États | **International public** | Relations entre États |
| L'employeur conteste le refus d'autorisation de licenciement par l'inspection du travail | **Administratif** | On attaque une **décision de l'administration** (piège : ce n'est PAS du droit du travail ici) |
| Un photographe professionnel ne vient pas au mariage | **Commercial** si professionnel, **civil** si non professionnel | Qualité des parties |
| Une société de négoce mise en redressement judiciaire | **Commercial** | Entreprises en difficulté |
| Des époux divorcent | **Civil** (famille) | Dissolution du mariage |
| Trois salariés licenciés pour faute grave contestent le motif | **Social** | Relation individuelle de travail → CPH |
| Un Français veut épouser une Allemande en Italie | **International privé** | Personnes privées, nationalités différentes |
| Un salarié pirate le STAD de son employeur | **Pénal** | Infraction |
| Une entreprise copie le logiciel d'une autre | **Civil/commercial** (PI) **+ pénal** si contrefaçon poursuivie | Double nature de la contrefaçon |
| Une commune installe une vidéosurveillance sur la voie publique | **Administratif** (autorisation préfectorale) | Acte de police administrative |

**Piège classique :** « le droit de l'environnement fait partie du droit… » → réponse du corrigé : **public ET privé** (il est transversal). De même le droit de la consommation, le droit de la propriété intellectuelle (privé mais avec un volet pénal).

## 1.3 Les sources du droit et la hiérarchie des normes

**Principe fondamental :** *un texte de catégorie inférieure ne peut déroger à un texte de catégorie supérieure.*

```
        ┌─────────────────────────────────────────┐
        │ BLOC DE CONSTITUTIONNALITÉ              │  Constitution du 4 octobre 1958,
        │                                         │  DDHC 1789, Préambule 1946,
        │                                         │  Charte de l'environnement, PFRLR
        ├─────────────────────────────────────────┤
        │ TRAITÉS ET DROIT DE L'UNION EUROPÉENNE  │  Traités, règlements (RGPD !), directives (NIS)
        ├─────────────────────────────────────────┤
        │ LOI (votée par le Parlement, art. 34 C.)│  Projet de loi (gouvernement)
        │ ORDONNANCES ratifiées (art. 38 C.)      │  Proposition de loi (parlementaires)
        ├─────────────────────────────────────────┤
        │ RÈGLEMENTS (art. 37 C.)                 │  Décrets (Président, Premier ministre),
        │                                         │  arrêtés (ministériels, préfectoraux,
        │                                         │  municipaux), actes des AAI (CNIL, ARCOM)
        └─────────────────────────────────────────┘
```

**Le Conseil constitutionnel** contrôle le respect de cette hiérarchie. Il peut être saisi par : le **Président de la République**, le **Premier ministre**, le **président de l'Assemblée nationale**, le **président du Sénat**, **60 députés** ou **60 sénateurs**, ou **tout justiciable** par la voie de la **question prioritaire de constitutionnalité (QPC)**.

**Sources formelles (écrites) vs non formelles :**

| Non formelle | Définition | Exemple |
|---|---|---|
| **Coutume** | Règle non édictée, issue d'un **usage prolongé**, dont l'application apparaît obligatoire | La femme mariée prenant le nom de son mari |
| **Jurisprudence** | Ensemble des décisions rendues par les juridictions | Cass. soc. sur la géolocalisation |
| **Doctrine** | Opinions émises par des juristes spécialisés | Articles, commentaires d'arrêts |

**Traité international :** accord conclu entre **États souverains** en vue de produire des effets de droit dans leurs relations mutuelles. Il s'applique en France après **ratification** (par le Président ou après autorisation du Parlement) **et publication au JORF**. Il doit être **conforme à la Constitution**.

**Question type :** « telle réforme relève-t-elle de la compétence de la loi française ? »
→ Toutes les réformes internes (universités, mariage, privatisation, loi de finances, Constitution, OGM) = **compétence française**.
→ L'interdiction européenne de conservateurs alimentaires = **compétence de l'UE**.
→ Un accord France–Gabon = **droit international**, applicable après ratification et publication.

---

## 1.4 ⭐ LES JURIDICTIONS — LE CHAPITRE À MAÎTRISER PARFAITEMENT

C'est **la** question qui tombe dans tous les CC : « Quel tribunal est compétent ? ». Elle vaut souvent plusieurs points et elle est **facile si tu as la méthode**.

### 1.4.1 Toujours répondre en DEUX temps

> **Une compétence juridictionnelle se décompose toujours en :**
> 1. **Compétence d'attribution (ou matérielle)** = *quel type de tribunal ?* → déterminée par la **nature du litige**.
> 2. **Compétence territoriale** = *dans quelle ville ?* → déterminée par le **lieu** (en principe le domicile ou siège social du **défendeur**).

Si tu ne traites qu'un des deux, tu perds la moitié des points. **Toujours écrire les deux titres.**

### 1.4.2 Le schéma d'organisation judiciaire (à savoir redessiner)

```
                    ORDRE ADMINISTRATIF                 |                      ORDRE JUDICIAIRE
                                                        |
                                                        |     Juridictions CIVILES     |   Juridictions PÉNALES
 3e niveau      CONSEIL D'ÉTAT                          |         COUR DE CASSATION (chambres civiles / criminelle)
                                                        |            (ne juge QUE le droit — pas un 3e degré)
 2e degré       COURS ADMINISTRATIVES D'APPEL           |                    COUR D'APPEL
                                                        |         (rejuge les FAITS et le DROIT — arrêts)
 1er degré      TRIBUNAUX ADMINISTRATIFS                |  Tribunal judiciaire   |  Tribunal de police (contraventions)
                                                        |  Tribunal de commerce  |  Tribunal correctionnel (délits)
                                                        |  Conseil de prud'hommes|  Cour d'assises (crimes)
                                                        |
 Ordre européen : COUR DE JUSTICE DE L'UNION EUROPÉENNE (CJUE)  —  et CEDH (droits de l'homme, après épuisement des recours internes)
```

### 1.4.3 L'ARBRE DE DÉCISION COMPLET (couvre toutes les variantes possibles)

```
ÉTAPE 1 — Y a-t-il une INFRACTION PÉNALE (vol, escroquerie, contrefaçon poursuivie
          pénalement, diffamation, injure, harcèlement, piratage/STAD, usurpation
          d'identité, coups et blessures) ?

  ├── OUI → ORDRE JUDICIAIRE PÉNAL. Quelle gravité ?
  │     ├── CONTRAVENTION (la moins grave, amende) ......... TRIBUNAL DE POLICE
  │     ├── DÉLIT (prison ≤ 10 ans) ....................... TRIBUNAL CORRECTIONNEL
  │     │     → C'est le cas de : vol, escroquerie, abus de confiance, contrefaçon,
  │     │       diffamation, injure publique, harcèlement moral/sexuel, atteinte au
  │     │       STAD, usurpation d'identité, violation du secret des correspondances
  │     └── CRIME (le plus grave : meurtre, viol, vol à main armée) ... COUR D'ASSISES
  │
  │     ⚠️ Compétence territoriale en pénal — TROIS options au choix :
  │        - lieu où l'infraction a été commise, OU
  │        - lieu de résidence du prévenu, OU
  │        - lieu d'interpellation/arrestation du prévenu.
  │
  │     ⚠️ Le juge pénal statue AUSSI sur le civil (DI) si la victime se constitue
  │        partie civile → "le pénal tient le civil en l'état" et
  │        "le pénal l'emporte sur le civil".
  │
  └── NON → ÉTAPE 2

ÉTAPE 2 — L'adversaire est-il l'ADMINISTRATION agissant comme puissance publique
          (impôts, urbanisme, fonction publique, décision de l'inspection du travail,
          refus d'autorisation, marché public administratif) ?

  ├── OUI → ORDRE ADMINISTRATIF
  │     1er degré : TRIBUNAL ADMINISTRATIF
  │     2e degré  : COUR ADMINISTRATIVE D'APPEL
  │     Sommet    : CONSEIL D'ÉTAT
  │
  └── NON → ÉTAPE 3 (ordre judiciaire civil)

ÉTAPE 3 — Le litige naît-il de la RELATION DE TRAVAIL entre un employeur et
          UN salarié (licenciement, salaire, clause, requalification en contrat
          de travail, preuve tirée d'un fichier du salarié, géolocalisation) ?

  ├── OUI → CONSEIL DE PRUD'HOMMES (CPH)
  │     Territorialement : le CPH dans le ressort duquel se trouve
  │     L'ÉTABLISSEMENT OÙ EST ACCOMPLI LE TRAVAIL
  │     (ou, si travail hors établissement/à domicile : le domicile du salarié).
  │     ⚠️ Litige INDIVIDUEL. Un conflit collectif (grève, syndicat) → TJ.
  │
  └── NON → ÉTAPE 4

ÉTAPE 4 — Le litige porte-t-il sur la PROPRIÉTÉ INTELLECTUELLE
          (brevet, marque, dessin & modèle, droit d'auteur, logiciel,
          base de données / droit sui generis) — au CIVIL ?

  ├── OUI → TRIBUNAL JUDICIAIRE, et plus précisément un
  │         TJ SPÉCIALEMENT DÉSIGNÉ en matière de propriété intellectuelle
  │         (compétence EXCLUSIVE : art. L.716-3 CPI pour les marques,
  │          L.615-17 CPI pour les brevets).
  │     ⚠️ Même si les deux parties sont des sociétés commerciales !
  │        La PI écarte le tribunal de commerce.
  │     ⚠️ Si en revanche on poursuit la contrefaçon comme DÉLIT (voie pénale),
  │        → tribunal correctionnel (qui statuera aussi sur les DI).
  │
  └── NON → ÉTAPE 5

ÉTAPE 5 — Qualité des parties : qui contre qui ?

  ├── COMMERÇANT contre COMMERÇANT, dans l'exercice de leur activité
  │   (ou société commerciale par la forme : SARL, SAS, SA…)
  │   ou litige relatif à un ACTE DE COMMERCE
  │   ou ENTREPRISE EN DIFFICULTÉ (redressement / liquidation judiciaire)
  │        → TRIBUNAL DE COMMERCE (TC)
  │        Territorialement : SIÈGE SOCIAL DU DÉFENDEUR
  │        (+ exceptions contractuelles, cf. art. 46 CPC ci-dessous)
  │
  ├── PARTICULIER contre PARTICULIER
  │        → TRIBUNAL JUDICIAIRE (TJ)
  │
  ├── COMMERÇANT (demandeur) contre PARTICULIER (défendeur)
  │        → TRIBUNAL JUDICIAIRE (on ne peut pas attraire un
  │          non-commerçant devant le TC)
  │
  └── PARTICULIER (demandeur) contre COMMERÇANT (défendeur)
           → OPTION du demandeur : TJ OU TC (règle du corrigé)
             En pratique le consommateur peut aussi saisir le tribunal
             de son propre domicile (droit de la consommation).

RÉSUMÉ MNÉMOTECHNIQUE DES QUALITÉS (tiré du corrigé du prof) :
  Demandeur PP  / Défendeur PM  → TJ ou TC (au choix)
  Demandeur PM  / Défendeur PP  → TJ
  Demandeur PM  / Défendeur PM  → TC
  Demandeur PP  / Défendeur PP  → TJ
  (PP = personne physique / particulier ; PM = personne morale / société commerciale)
```

### 1.4.4 Compétence territoriale : toutes les valeurs possibles

**Règle de principe (art. 42 CPC) :** le tribunal du lieu où demeure le **DÉFENDEUR**.
- Personne physique → son **domicile**.
- Personne morale → son **siège social** (ou un établissement qui la représente).

**Options offertes au demandeur (art. 46 CPC) — à connaître, c'est ce qui fait la différence :**

| Matière | Le demandeur peut choisir, en plus du domicile du défendeur |
|---|---|
| **Contractuelle** | le lieu de **livraison effective de la chose** OU le lieu d'**exécution de la prestation de service** |
| **Délictuelle** (responsabilité extra-contractuelle) | le lieu du **fait dommageable** OU le lieu où le **dommage a été subi** |
| **Mixte** (immobilier) | le lieu de situation de **l'immeuble** |
| **Aliments / pension** | le lieu du domicile du **créancier** (celui qui reçoit) |

**Clause attributive de compétence :** valable **entre commerçants** seulement. Elle désigne un tribunal précis. Elle est **réputée non écrite** dans un contrat avec un consommateur.

**Consommateur et clause étrangère :** un client d'une plateforme (ex. plateforme de crypto lituanienne) est un **consommateur**, pas un professionnel. En vertu du **règlement Bruxelles I bis du 12/12/2012**, il peut assigner le professionnel **devant le tribunal de son propre domicile**, et la clause attributive au siège du professionnel lui est **inopposable**.

### 1.4.5 Le taux de ressort (les 5 000 €) — piège récurrent

> **TJ, TC et CPH jugent en premier et dernier ressort jusqu'à 5 000 €.**
> **Au-delà de 5 000 €, l'appel est possible devant la cour d'appel.**

**Comment répondre :**
- Demande **≤ 5 000 €** → jugement en **premier et dernier ressort** → **pas d'appel possible**. Seul recours : le **pourvoi en cassation** directement (« jugement rendu en dernier ressort par une juridiction de 1re instance »).
- Demande **> 5 000 €** → **appel possible**.
- **On additionne les chefs de demande** : 15 000 € de loyers + 6 000 € de réparations = 21 000 € > 5 000 € → appel possible.

### 1.4.6 Les décisions et les recours

| Juridiction | Nom de la décision |
|---|---|
| TJ, TC, CPH, TA, tribunal de police, tribunal correctionnel | **Jugement** |
| Cour d'appel, Cour de cassation, Cour d'assises, Conseil d'État, CJUE | **Arrêt** |
| Juge des référés | **Ordonnance** de référé |
| Juge des requêtes | **Ordonnance** sur requête |

**Le double degré de juridiction** : garantie offerte au justiciable de voir son affaire réexaminée par une juridiction supérieure. La cour d'appel rejuge **faits + droit** ; elle rend des arrêts **confirmatifs** (même solution) ou **infirmatifs** (solution contraire).

**La Cour de cassation :** ce **n'est pas un 3e degré de juridiction**, car elle ne juge **que le droit**, pas les faits. Deux issues :

| Décision | Effet | Suite de l'affaire |
|---|---|---|
| **Arrêt de rejet** | Le pourvoi est rejeté, la décision d'appel est validée | **Procédure terminée**, le demandeur au pourvoi est définitivement débouté |
| **Arrêt de cassation AVEC renvoi** | L'arrêt d'appel est annulé | L'affaire est **rejugée par une AUTRE cour d'appel** (de même degré) |
| **Arrêt de cassation SANS renvoi** | Annulation, rien à rejuger | **Procédure terminée** |

### 1.4.7 Vingt cas de compétence — un exemple pour chaque valeur possible

| # | Situation | Compétence d'attribution | Territoriale |
|---|---|---|---|
| 1 | Deux commerçants, travaux mal exécutés dans un magasin | **TC** | Siège du défendeur **ou** lieu d'exécution des travaux |
| 2 | Deux particuliers, dégâts causés par un chien (6 000 €) | **TJ** | Domicile du défendeur ; appel possible (> 5 000 €) |
| 3 | Agression avec vol et coups | **Tribunal correctionnel** (délit) | Lieu des faits / résidence / interpellation |
| 4 | Contestation d'un avis d'imposition | **Tribunal administratif** | Ressort du contribuable |
| 5 | Licenciement contesté | **CPH** | Lieu de l'établissement où le travail est accompli |
| 6 | Requalification d'un indépendant en salarié (plateforme) | **CPH** | Idem |
| 7 | Contrefaçon de marque (action civile) | **TJ spécialisé PI** | Domicile du défendeur |
| 8 | Contrefaçon poursuivie pénalement | **Tribunal correctionnel** | Lieu de l'infraction |
| 9 | Contrefaçon de logiciel + concurrence déloyale entre sociétés | **TJ** pour la PI ; **TC** pour la concurrence déloyale ; **correctionnel** si contrefaçon poursuivie pénalement (statue sur civil + pénal) | — |
| 10 | Concurrence déloyale / dénigrement entre deux sociétés | **TC** | Siège du défendeur |
| 11 | Diffamation ou injure publique | **Tribunal correctionnel** (délit de presse) | Lieu de publication / résidence |
| 12 | Prestataire informatique vs société cliente (inexécution) | **TC** | Siège du défendeur |
| 13 | Prestataire vs client **non professionnel** dans ce domaine | **TC** (deux sociétés) mais **clause abusive** neutralisée | — |
| 14 | Divorce, succession, filiation, nom | **TJ** (JAF pour famille) | Domicile du défendeur |
| 15 | URSSAF assigne une SARL en liquidation judiciaire | **TC** (entreprise en difficulté) | Siège social de la SARL |
| 16 | Consommateur vs plateforme étrangère (crypto) | **TJ** du domicile du **consommateur** (Bruxelles I bis) | Domicile du consommateur |
| 17 | Consommatrice vs filiale française de Booking | La filiale **n'a pas qualité** ; il faut assigner la société **néerlandaise** | — |
| 18 | Vidéosurveillance illicite installée par une commune | **Tribunal administratif** ; sanction CNIL en parallèle | — |
| 19 | Communication de données d'identification d'un anonyme | **TJ** statuant **sur requête** ou **en référé** | Selon le siège de l'hébergeur / lieu du dommage |
| 20 | Litige entre un particulier et une plateforme de location (52 000 €) | **TJ ou TC** au choix (demandeur PP / défendeur PM) | Sauf clause attributive |

### 1.4.8 Questions transversales du chapitre (réponses toutes faites)

**« Sur quels critères se détermine la compétence d'une juridiction ? »**
> La loi détermine la compétence selon l'organisation judiciaire. La **nature du litige** fixe la **compétence d'attribution** (TJ, TC, CPH, correctionnel…). Le **lieu du litige** fixe la **compétence territoriale**, en principe le domicile du défendeur.

**« Quels sont les effets d'un jugement ? »**
> Il a **force exécutoire** (il peut être exécuté au besoin par la force publique) et **autorité de la chose jugée** (ce qui a été jugé est acquis et ne peut être contesté, sauf voies de recours légales).

**« Qu'est-ce qu'une voie de recours ? »**
> La possibilité offerte à la partie mécontente d'une décision de la contester devant une instance supérieure afin de faire réexaminer son affaire : appel, pourvoi en cassation, opposition, révision.

**« Auprès de quel professionnel prendre conseil ? »**
> L'**avocat**, auxiliaire de justice : il conseille, rédige les actes, plaide (monopole de la plaidoirie) et est tenu au **secret professionnel**.

---

# PARTIE 2 — LA PROPRIÉTÉ INTELLECTUELLE

## 2.0 La carte du chapitre

La propriété intellectuelle se divise en **deux branches**. Ne jamais les confondre : c'est la première chose que le prof vérifie.

```
                    PROPRIÉTÉ INTELLECTUELLE (Code de la propriété intellectuelle — CPI)
                                        │
        ┌───────────────────────────────┴───────────────────────────────┐
        │                                                               │
  PROPRIÉTÉ INDUSTRIELLE                                 PROPRIÉTÉ LITTÉRAIRE ET ARTISTIQUE
  → protection par DÉPÔT à l'INPI                        → protection AUTOMATIQUE, sans formalité
  → PP ou PM peuvent en bénéficier                       → seule une PERSONNE PHYSIQUE peut être auteur
        │                                                               │
   ┌────┼────────┬─────────────┐                              DROIT D'AUTEUR
   │    │        │             │                                        │
 BREVET │   DESSINS &      MARQUE                            ┌──────────┴──────────┐
        │    MODÈLES                                    DROIT MORAL          DROITS PATRIMONIAUX
   (invention)  (apparence)   (signe distinctif)      (extrapatrimonial)    (exploitation)
    20 ans      5 ans x5      10 ans renouvelable      perpétuel,            70 ans après
  non renouv.   = 25 ans max   indéfiniment            inaliénable,          le décès
                                                        imprescriptible
```

**Le fil rouge du chapitre :** la sanction est toujours la même → **l'ACTION EN CONTREFAÇON**.

> **Définition à réciter :** la contrefaçon est une **violation d'un droit de propriété intellectuelle** par le fait de **reproduire ou d'imiter** quelque chose **sans en avoir le droit**, ou en affirmant ou laissant présumer que la copie est authentique.
> L'action en contrefaçon suppose une **atteinte au droit de propriété** sur une marque, un brevet, un dessin/modèle ou une œuvre.
> Elle permet d'être **dédommagé au civil** (TJ) et de **condamner le contrefacteur au pénal** (tribunal correctionnel).

## 2.1 Le brevet

**Définition :** le brevet protège une **invention**, définie comme une **solution à un problème technique**. L'intervention de l'homme est nécessaire. Il confère à l'inventeur le droit d'empêcher toute autre personne d'exploiter son invention à des fins commerciales pendant un certain temps.

### Les 4 conditions de brevetabilité (le prof en demande souvent 3)

1. **Susceptible d'application industrielle** (utilité pratique).
2. **Nouvelle** : non comprise dans l'état de la technique, ne fait pas partie des connaissances existantes.
3. **Impliquant une activité inventive** (non évidente pour l'homme du métier).
4. **Licite** : conforme à l'ordre public, aux bonnes mœurs, respectueuse de la santé publique.

**Formalité :** dépôt d'une demande à l'**INPI** (Institut national de la propriété industrielle). Extension possible au niveau **européen** (OEB) ou **international**.

### Effets

- **Monopole d'exploitation de 20 ans, NON renouvelable.**
- Le titulaire peut : exploiter lui-même, **céder** ses droits, **concéder une licence d'exploitation** (contre redevance), l'apporter en société. Le brevet est un **bien meuble incorporel**.
- Il peut **interdire aux tiers** : de fabriquer, utiliser, vendre, importer le produit (**brevet de produit**) ; d'appliquer le procédé sans consentement et d'utiliser/vendre/importer les produits obtenus par ce procédé (**brevet de procédé**).

### ⚠️ Le point clé du cours : LES LOGICIELS NE SONT PAS BREVETABLES

> **L'Office européen des brevets (OEB) exclut de son champ d'application les programmes d'ordinateur EN TANT QUE TELS.** Il admet une protection pour les « programmes-produits », mais **il ne peut être admis qu'un simple artifice de langage permette de délivrer des brevets *contra legem*** (= contraire à la loi).

**Conséquence pratique — le retournement type :** une société attaque en contrefaçon de brevet logiciel → non seulement elle perd, mais **son brevet est annulé pour défaut de brevetabilité**. Il n'y a pas de contrefaçon puisqu'aucun droit de PI valable n'a été violé.

**Critère de l'INPI :** ne répond pas à la définition d'un brevet un procédé comportant un **ensemble d'étapes théoriques et abstraites**, sans préciser les **moyens techniques** qui lui confèrent un caractère technique. Une description qui se borne à affirmer l'objet et à décrire les **résultats** et **possibilités offertes à l'utilisateur**, sans mentionner les caractéristiques techniques, n'est pas brevetable.
Le brevet est alors annulé **pour défaut de brevetabilité** (et non pour défaut d'activité inventive — nuance que le prof souligne).

**Le logiciel est donc protégé par le DROIT D'AUTEUR** (cf. 2.5).

## 2.2 Les dessins et modèles

**Objet :** l'**apparence** d'un produit — lignes, contours, couleurs, forme, texture, matériaux.
- **Dessin** = 2 dimensions.
- **Modèle** = 3 dimensions.

**Conditions :** être **nouveau** + avoir un **caractère propre** (impression visuelle d'ensemble différente des antériorités) + ne pas être contraire à l'ordre public et aux bonnes mœurs.

**Formalité :** dépôt d'une demande d'enregistrement à l'**INPI**. Le **premier déposant** est présumé être le créateur et titulaire des droits.

**Durée :** **5 ans, renouvelable par périodes de 5 ans, jusqu'à 25 ans maximum.**

**Piège du cas « Jean-Eudes » :** celui qui n'a fait **aucune démarche de dépôt** ne peut **pas** invoquer la propriété industrielle. Mais il n'est pas démuni : il bénéficie du **droit d'auteur**, qui existe **sans aucune formalité**. C'est la réponse en deux temps attendue.

## 2.3 Les marques

**Définition :** titre de propriété industrielle permettant de protéger un **signe** servant à **distinguer** les produits ou services d'une personne physique ou morale.

**Formes possibles :**
- **dénomination** : un ou plusieurs mots, nom patronymique, nom géographique, terme de fantaisie, nom d'animal, lettres, chiffres, slogan ;
- **signe figuratif** : logo, forme d'un produit, couleur ;
- **signe sonore** ;
- **marque semi-figurative** = **élément verbal + élément figuratif** (un logo accompagné d'un nom, ou un terme à la calligraphie particulière). *Elle est utile lorsque l'élément verbal est peu ou pas distinctif.*

### Les 3 (+1) conditions de validité — arbre complet

```
1. DISTINCTIF  → le signe ne doit pas être la désignation ordinaire, nécessaire ou générique
                 du produit/service, ni descriptif de ses qualités.
                 ✗ « Banquette » pour un canapé-lit → substantif du produit → REFUS
                 ✗ « Pain » pour de la boulangerie
                 ✓ « Apple » pour des ordinateurs (arbitraire dans ce domaine)
                 ⚠️ Un signe FAIBLEMENT distinctif reste VALABLE, il est juste
                    faiblement protégé (cf. My Luxury Travel).

2. DISPONIBLE  → pas de droit antérieur identique/similaire sur des produits similaires.
                 ⚠️ MARQUE NOTOIRE : elle reste indisponible MÊME pour des produits
                    DIFFÉRENTS (protection renforcée). Ex. « Must » de Cartier opposé
                    à des chewing-gums.
                 ⚠️ La marque ne doit pas porter atteinte au NOM PATRONYMIQUE d'un tiers
                    (confusion dans l'esprit du public ou atteinte à la dignité) —
                    mais si la marque est ANTÉRIEURE à la réclamation, l'homonyme
                    n'obtient pas gain de cause (cas Rivoire ; cas Paul Ricard :
                    interdiction d'utiliser son propre nom face à l'antériorité de Ricard).

3. LICITE      → non contraire à l'ordre public et aux bonnes mœurs.

4. NON DÉCEPTIF→ ne pas être de nature à TROMPER le public sur la nature, la qualité
                 ou la provenance géographique du produit ou service.
```

**Effets :** délivrée pour **10 ans, renouvelable indéfiniment**. Le titulaire peut s'opposer à toute exploitation non autorisée → **action en contrefaçon**. La marque peut être exploitée, cédée, ou concédée en licence.

### Les 3 cas de délit de contrefaçon de marque

| Cas | Explication | Exemple du cours |
|---|---|---|
| **Reproduction** | Copie à l'identique | Polos Lacoste avec le crocodile |
| **Imitation** avec similitude **intellectuelle**, **phonétique** ou **visuelle** | Ressemblance créant un risque de confusion | Café « Label noir » contrefaisant « Carte noire » (similitude intellectuelle) |
| **Utilisation illicite** | Emploi non autorisé de la marque d'autrui | Un concessionnaire qui continue d'utiliser l'enseigne après rupture avec le concédant |

### ⭐ La méthode d'appréciation du risque de confusion (cœur du CC1 2024-2025)

> **Principe à réciter (art. L.713-3 CPI) :** porte atteinte aux droits du titulaire d'une marque l'usage, **dans la vie des affaires**, d'un signe **identique ou similaire** pour des produits ou services **identiques ou similaires**, lorsqu'il existe un **risque de confusion dans l'esprit du public**.
>
> **Méthode :** le risque de confusion s'apprécie par une **APPRÉCIATION GLOBALE** des marques prises **dans leur ensemble**, et non par la seule comparaison d'un élément (phonétique ou verbal). Pour des marques complexes associant un nom et un logo, il faut vérifier si **l'impression d'ensemble** produite par les graphismes est identique. Le public de référence est le **consommateur moyen**, normalement informé et raisonnablement attentif.

**Les trois types de similitude à envisager systématiquement :**

| Type | Question à se poser | Exemple |
|---|---|---|
| **Visuelle** | Les graphismes, logos, couleurs se ressemblent-ils ? | Leonidas utilise un guerrier grec des Thermopyles ; Belidas non → pas de similitude visuelle |
| **Phonétique** | Les marques se prononcent-elles pareil ? | Belidas / Leonidas : même suffixe « -idas » |
| **Conceptuelle (intellectuelle)** | Les marques évoquent-elles la même idée ? | « Travel » et « Voyage » sont **synonymes** → similitude conceptuelle forte |

**Exemples de jurisprudence citée dans le cours pour l'ABSENCE de confusion :** Parogencyl ≠ Tonigencyl ; Apérifromage ≠ Apéricube ; Belidas ≠ Leonidas.

**Le raisonnement circulaire (piège du CC1 2024-2025) :** si le tribunal annulait la marque antérieure pour manque de distinctivité en raison de son seul élément verbal, cela reviendrait à **consacrer aussi le manque de distinctivité de la marque seconde**, qui repose sur le même élément verbal. C'est pourquoi il **maintient la validité** de la marque antérieure malgré son faible caractère distinctif, puis compare les marques **globalement**.

## 2.4 Le droit d'auteur — propriété littéraire et artistique

### 2.4.1 Ce qui est protégé

Les **œuvres de l'esprit** : romans, pièces de théâtre, journaux, **logiciels**, **bases de données**, films, compositions musicales, peintures, dessins, photographies, créations publicitaires, cartes géographiques, dessins techniques.

> **Le droit d'auteur protège la FORME d'expression des idées, jamais les idées elles-mêmes.** (« Les idées sont de libre parcours. »)

**Les conditions cumulatives d'une œuvre protégeable :**

1. **Une création humaine et consciente**, qui **modifie le réel** (donc : émanant d'une **personne physique** ; une IA ou un animal ne peut être auteur).
2. **Une forme** (olfactive, visuelle, auditive) : l'idée non matérialisée n'est pas protégée.
3. **L'ORIGINALITÉ** = l'œuvre porte l'**empreinte de la personnalité de son auteur**, elle traduit un **effort créatif** et des **choix libres et créatifs**.

> **Aucune formalité n'est requise.** Le droit d'auteur naît du seul fait de la création. La qualité d'auteur appartient à **celui sous le nom de qui l'œuvre est divulguée**.

### 2.4.2 ⚠️ L'originalité : le critère qui fait basculer les cas

C'est **la** question piège. Exemples pour chaque valeur possible :

| Situation | Originale ? | Motif |
|---|---|---|
| Photos de produits prises pour « effacer toute subjectivité », angle dicté par des impératifs marketing, sans parti pris esthétique | **NON** | Aucune empreinte de la personnalité ; **apposer un logo ne suffit pas** à conférer l'originalité |
| Un annuaire classant les habitants d'une ville par ordre alphabétique | **NON** | Classement banal, aucun choix créatif |
| Une base de données des meilleurs restaurants de Paris | **OUI** | Les **choix** de sélection relèvent de l'empreinte de la personnalité |
| Une série d'esquisses de détenus par un dessinateur | **OUI** | Création consciente, forme, originalité |
| Un tableau « Moi dans la jungle de Bornéo » | **OUI** | Œuvre de l'esprit à part entière |
| Un logiciel avec des choix d'architecture, d'algorithmes, de structure | **OUI** | Le juge « pointe les différents choix opérés » |

**Conséquence si l'œuvre n'est PAS originale :** pas de droit d'auteur → **pas de contrefaçon possible**.
**MAIS** : la reproduction reste sanctionnable sur le terrain de la **concurrence parasitaire** (cf. Partie 6). C'est la **réponse en deux temps** que le prof attend : *déboutée en contrefaçon, mais gagnante en parasitisme*.

### 2.4.3 Le droit moral (droit extrapatrimonial)

**Caractères (à réciter d'un bloc) : PERPÉTUEL, INALIÉNABLE, IMPRESCRIPTIBLE**, attaché à la personne de l'auteur, **transmis aux héritiers**, **non limité dans le temps**.

**Contenu :** droit de **divulgation**, droit à la **paternité** (au nom), droit au **respect de l'intégrité de l'œuvre**, droit de **retrait et de repentir**.

**Effet redoutable :** l'auteur peut s'opposer à ce qu'on **dénature** son œuvre, **même si la dénaturation est le fait de celui qui l'a acquise et qui en est devenu propriétaire**. Le droit de propriété de l'acquéreur, même absolu, **cède** devant le droit moral.
→ *Exemple : l'acquéreur d'un tableau ne peut pas le découper en morceaux pour revendre chaque partie plus cher.*
→ *Exemple : l'artiste peut demander la restitution de son œuvre pour la détruire, mais il devra **indemniser** le propriétaire à hauteur de la valeur actuelle.*

### 2.4.4 Les droits patrimoniaux

| Droit | Contenu |
|---|---|
| **Droit de représentation** | Communication au public par tout procédé : récitation, représentation, projection publique, télédiffusion, mise en ligne |
| **Droit de reproduction** | Fixation matérielle par tout moyen : dessin, gravure, photographie, moulage, enregistrement, copie numérique |
| **Droit de suite** | Permet à l'auteur d'une œuvre graphique/plastique de percevoir une part du produit de la **revente** de son œuvre |

**Durée :** au décès de l'auteur, les droits d'exploitation sont attribués aux **ayants droit** pendant **l'année civile en cours + 70 ans**.
Après ce délai, l'œuvre tombe dans le **domaine public** : elle peut être exploitée **gratuitement**… mais le **droit moral** subsiste éternellement.

> **⭐ La combinaison qui tombe systématiquement (cas « film tiré d'un roman du 19e ») :**
> Les héritiers ont **deux prétentions** :
> 1. **S'opposer à l'exploitation** → c'est le **droit moral**, **perpétuel** → prétention **JUSTIFIÉE**.
> 2. **Percevoir une redevance** → c'est le **droit patrimonial**, limité à 70 ans post mortem → un siècle s'étant écoulé, l'œuvre est dans le **domaine public** → prétention **REJETÉE**.
>
> **Conclusion à écrire :** les héritiers peuvent seulement s'opposer à l'exploitation ; s'ils l'autorisent, c'est **gratuitement**. Dans les deux cas, **ils ne percevront rien**.

### 2.4.5 Les exceptions au droit d'auteur (une fois l'œuvre divulguée)

L'auteur ne peut plus interdire :
- les **représentations dans le cercle de famille** ;
- les **copies à usage privé du copiste**, non destinées à une utilisation collective ;
- les **analyses et courtes citations** justifiées par le caractère critique, polémique, pédagogique, scientifique ou d'information — **sous réserve d'indiquer le nom de l'auteur et la source** ;
- les actes nécessaires à l'**accès au contenu d'une base de données électronique** dans les limites de l'utilisation prévue au contrat ;
- (également : parodie/pastiche/caricature, exception pédagogique, revue de presse).

### 2.4.6 Œuvre collective, œuvre de collaboration, œuvre de commande — arbre de décision

C'est **une question à variables multiples** : le prof peut changer le scénario. Voici tous les cas.

```
Combien de personnes ont créé l'œuvre ?

├── UNE SEULE (indépendant, hors contrat de travail)
│      → L'AUTEUR est titulaire des droits moraux ET patrimoniaux.
│
├── PLUSIEURS
│   │
│   ├── Peut-on identifier la contribution personnelle de chacun ?
│   │
│   ├── NON — l'œuvre est créée à l'INITIATIVE d'une personne (physique ou morale)
│   │   qui la PUBLIE sous son nom, sans qu'il soit possible d'attribuer à chacun
│   │   un droit distinct sur l'ensemble
│   │        → ŒUVRE COLLECTIVE
│   │        → Les droits appartiennent à LA PERSONNE (PP ou PM) à l'initiative
│   │          Les contributeurs n'ont AUCUN droit et AUCUNE rémunération
│   │          supplémentaire au-delà de leur salaire ou honoraires.
│   │        Exemples : dictionnaire, journal, site web, base de données.
│   │
│   └── OUI — chacun apporte une contribution originale identifiable
│            → ŒUVRE DE COLLABORATION
│            → PROPRIÉTÉ COMMUNE des coauteurs ; ils exercent leurs droits
│              D'UN COMMUN ACCORD ; l'œuvre est divulguée sous le nom de tous
│              et ne peut être exploitée qu'avec l'autorisation de TOUS.
│            → Si les contributions relèvent de GENRES DIFFÉRENTS, chaque coauteur
│              peut exploiter SÉPARÉMENT sa contribution personnelle, sans porter
│              préjudice à l'exploitation de l'œuvre commune.
│            Exemples : œuvre audiovisuelle, roman coécrit, chanson (compositeur
│            + parolier), bande dessinée (scénariste + dessinateur).
│            ⚠️ Le dessinateur d'une BD qui cède ses droits à un éditeur SANS
│               le consentement du scénariste commet une CONTREFAÇON.
│
└── ŒUVRE DE COMMANDE (un client commande à un prestataire)
       Règle de base : l'AUTEUR reste titulaire des droits ; le client
       n'acquiert des droits QUE si le contrat de commande le prévoit.
       ⚠️ EXCEPTION : si le client fournit un CAHIER DES CHARGES avec des
          instructions TRÈS PRÉCISES, laissant PEU DE MARGE au prestataire, dont
          le rôle se limite à un rôle TECHNIQUE → les droits appartiennent AU
          CLIENT, qui a conçu le projet (le prestataire n'a pas fait de choix
          créatifs, donc pas d'empreinte de sa personnalité).
       → Conseil pratique : toujours stipuler dans le contrat qui détient
         les droits et dans quelles conditions.
```

**Œuvre multimédia (site, app, installation interactive) :** protégée par le droit d'auteur. Si un seul auteur → régime classique. Si plusieurs → soit collective, soit de collaboration, **selon les conditions de la création**.

## 2.5 Le cas particulier du LOGICIEL

C'est le cœur du cours (« Droit des TIC »). Retiens ce bloc mot pour mot.

> **Le logiciel est une œuvre protégée par le DROIT D'AUTEUR (pas par le brevet).**
> **Ce qui est protégé :** le **code source**, la **documentation**, voire l'**analyse fonctionnelle détaillée**.
> **Ce qui n'est PAS protégé :** le **code exécutable** (compilé, illisible par un humain, suite de 0 et de 1).

**Le régime dérogatoire du logiciel de salarié (art. L.113-9 CPI) :**

> **« Sauf stipulation contraire, le logiciel créé par un ou plusieurs employés DANS L'EXERCICE DE LEURS FONCTIONS appartient à l'EMPLOYEUR, auquel sont dévolus tous les droits reconnus aux auteurs. »**

C'est une **exception majeure** au principe général. Compare :

| Type de création par un salarié | Titulaire des droits patrimoniaux |
|---|---|
| Une œuvre originale quelconque (article, photo, dessin) | **Le salarié** (l'auteur), même si créée dans le cadre du contrat de travail |
| Un **logiciel** créé **dans l'exercice des fonctions** | **L'EMPLOYEUR**, automatiquement, sauf clause contraire |
| Une contribution à une **œuvre collective** (si le contrat le prévoit) | **L'employeur** (personne à l'initiative) |
| Un logiciel créé **hors fonctions et sans les moyens de l'entreprise** | **Le salarié** (droit commun du droit d'auteur) |
| Un logiciel créé **hors heures de travail MAIS avec le matériel de l'employeur** | **L'EMPLOYEUR** ⚠️ (jurisprudence CA Nancy, affaire DS Compta) |

**Les indices que le juge relève pour dire que le logiciel appartient à l'employeur :**
- le logiciel a été développé **dans les locaux** de la société ;
- des éléments du logiciel apparaissent sur le **disque dur de l'ordinateur professionnel** ;
- le **matériel de l'entreprise** a servi à la transcription ;
- le **temps de travail salarié** a été utilisé (ex. « 85 % pendant le temps où il était salarié »).

> **La formule du corrigé :** « Même s'il était établi que M. M n'a effectué cette transcription qu'en dehors de ses heures de travail, le logiciel élaboré **à l'aide du matériel de son employeur et avec le concours de celui-ci** est devenu la propriété de la société. »
> Le contrat de travail peut prévoir un **intéressement** sur les ventes, mais **ce n'est pas systématique**. Il peut aussi aménager un **droit de préférence** de l'employeur sur les créations hors fonctions susceptibles de l'intéresser.

**Le droit moral de l'auteur salarié de logiciel est très affaibli** : il ne peut pas s'opposer aux modifications de son logiciel par l'employeur, ni exercer son droit de repentir.

## 2.6 Les bases de données : double protection

C'est un point à haut rendement : **deux protections cumulables mais distinctes**.

| | **Droit d'auteur** | **Droit *sui generis*** (art. L.341-1 CPI) |
|---|---|---|
| **Protège** | La **forme originale** (structure, architecture, choix de présentation) | Le **contenu** de la base (l'investissement) |
| **Titulaire** | L'**auteur** (personne physique) | Le **producteur** (celui qui prend l'initiative et le risque) |
| **Condition** | **Originalité** : les choix reflètent l'empreinte de la personnalité | **Investissement SUBSTANTIEL** (humain, matériel ou financier) |
| **Ne protège pas** | Ni les données elles-mêmes, ni les œuvres qui y figurent | La création des données elles-mêmes |
| **Droit conféré** | Reproduction / représentation | **Autoriser ou interdire l'EXTRACTION ou la RÉUTILISATION** du contenu |

**Le producteur au sens de l'art. L.341-1 CPI :** peut se prévaloir de cette qualité la personne réalisant des **investissements substantiels** :
- sur le plan **qualitatif** : présentation d'annonces finalisées, pratiques, complètes et **vérifiées** ;
- sur le plan **quantitatif** : nombre très important d'annonces ;
pour l'**obtention**, la **vérification** et la **présentation** du contenu de sa base.

> **⚠️ La distinction décisive (elle fait basculer les cas) :**
> La protection *sui generis* est accordée pour les investissements liés à l'**obtention, la vérification, le stockage et la présentation** des éléments **une fois ceux-ci réunis**.
> Elle n'est **PAS** accordée pour les investissements liés à la **création elle-même** des données, **avant** leur intégration dans la base.
> → *C'est pourquoi une base constituée simplement en recopiant des annuaires professionnels existants (Pages Jaunes) voit son caractère substantiel **réfuté** : les investissements sont trop faibles.*

**« Le terme substantiel signifie important. Le critère reste subjectif et flou, afin de permettre aux juridictions de bénéficier de la plus grande adaptabilité face à des situations évolutives. »** ← phrase du cours, à replacer.

**Pas de droit sui generis** lorsque la base est créée par une **communauté sans direction** (ex. le réseau Internet, un wiki ouvert) : personne n'a pris **l'initiative**.

**Extraction substantielle — appréciation quantitative :** elle peut être réalisée
- **en une seule fois** (extraction de 10 % de la base), ou
- **en plusieurs fois** (10 fois 1 % de la base) — l'extraction **répétée et systématique** de parties non substantielles est assimilée à une extraction substantielle.

**Sanction :** la violation du droit sui generis est punie de **3 ans d'emprisonnement et 300 000 € d'amende**, et le contrefacteur peut être condamné à des **dommages-intérêts** pour le préjudice du producteur.

## 2.7 Qui peut bénéficier de quoi ? (question de cours fréquente)

| | Personne physique (PP) | Personne morale (PM) |
|---|---|---|
| **Brevet, dessin & modèle, marque** (propriété industrielle) | ✅ Oui | ✅ Oui |
| **Droit d'auteur sur une œuvre de l'esprit** | ✅ Oui (**seule** une PP peut être auteur) | ❌ Non, sauf **œuvre collective** (elle est alors titulaire des droits) et **logiciel de salarié** (dévolution légale) |

**Où se trouvent les règles ?** Dans le **Code de la propriété intellectuelle (CPI)**, qui rassemble propriété industrielle + propriété littéraire et artistique.

**Quels sont les moyens légaux de protection d'une œuvre ?**
- Le **dépôt à l'INPI** pour brevets, dessins, modèles, marques ;
- Le **dépôt à l'APP** (Agence pour la protection des programmes) pour les logiciels — c'est un **mode de preuve de date et de contenu**, pas une condition de protection ;
- L'**action en contrefaçon** et/ou l'**action en concurrence déloyale** pour faire cesser l'atteinte et être indemnisé ;
- La **saisie-contrefaçon** pour établir la preuve.

## 2.8 Établir une contrefaçon de code source : la grille du juge

Quand le sujet donne un cas « ancien salarié qui part et emporte le code », le tribunal raisonne en **5 étapes**. Reprends-les :

1. **Identifier l'œuvre et le titulaire des droits** → certificats de dépôt à l'**APP**.
2. **Vérifier l'ORIGINALITÉ** du logiciel → en pointant les **différents choix opérés** (pas seulement l'existence de lignes de code).
3. **Établir le transfert / la reproduction** → échanges de **courriels professionnels** par lesquels les codes sources ont été transférés ; constat d'**huissier** assisté d'un **expert informatique**.
4. **Mesurer la similarité** → rapport d'analyse technique (« codes identiques à 2 % près » = **98 % identiques**).
5. **Absence d'autorisation** du titulaire → la contrefaçon est **établie**.

**Et en parallèle, la concurrence déloyale :** débauchage massif (ex. 9 salariés), détournement de clientèle, divulgation d'informations confidentielles, désorganisation. → **Tribunal de commerce**.

> **La double casquette procédurale à écrire :**
> - Contrefaçon (PI) → **TJ** au civil, **tribunal correctionnel** si poursuivie comme délit (il statue alors sur le pénal **et** le civil) ;
> - Concurrence déloyale → **tribunal de commerce**.

## 2.9 Défenses possibles du défendeur (pour les questions « décision inverse »)

Quand le prof demande « sur quel argument le tribunal pourrait-il rendre une décision inverse ? », pioche ici :

**Pour faire tomber une action en contrefaçon :**
1. **Nullité du titre** : la marque n'est pas distinctive / disponible / licite ; le brevet n'est pas brevetable (logiciel !) ; l'œuvre n'est pas originale.
2. **Absence de titularité** : le demandeur ne prouve pas être titulaire des droits **à la date des faits** (ex. un **copyright désignant une autre société** est apposé sur le logiciel → preuve de titularité manquante).
3. **Absence de risque de confusion** : appréciation globale, éléments figuratifs distincts, public averti.
4. **Absence de reproduction** : le défendeur a développé sa **propre solution**, dont l'**originalité et le caractère innovant** sont **corroborés par l'expert** ayant assisté l'huissier.
5. **Autorisation / épuisement des droits / exception légale** (courte citation, copie privée, interopérabilité, maintenance).
6. **Prescription**.

**Pour justifier au contraire la contrefaçon :**
1. **Élément verbal prédominant** : si le verbal domine la perception du public, les éléments figuratifs deviennent secondaires.
2. **Similitude conceptuelle + services identiques** = risque de confusion pour le consommateur moyen.
3. **Appréciation globale** : les ressemblances l'emportent sur les différences.
4. **Antériorité et notoriété** : la marque première a acquis une réputation dont la seconde cherche à profiter (parasitisme).

## 2.10 Fiche express « durées » (à mémoriser absolument)

| Droit | Durée | Renouvelable ? |
|---|---|---|
| **Brevet** | **20 ans** | ❌ Non |
| **Dessin & modèle** | **5 ans** | ✅ par périodes de 5 ans, **max 25 ans** |
| **Marque** | **10 ans** | ✅ **indéfiniment** |
| **Droit patrimonial d'auteur** | **70 ans** après le décès (+ année civile en cours) | — |
| **Droit moral** | **Perpétuel** | — |
| **Droit sui generis BDD** | 15 ans à compter de l'achèvement (renouvelé à chaque investissement substantiel nouveau) | — |
| **Conservation des images de vidéosurveillance** | **1 mois maximum** | — |
| **Notification d'une violation de données à la CNIL** | **72 heures** | — |
| **Rétractation e-commerce** | **14 jours** | — |

---

# PARTIE 3 — LE CONTRAT DE TRAVAIL ET LES TIC

## 3.0 Pourquoi ce chapitre existe

Un informaticien est très souvent **salarié**. Or trois questions se posent en permanence :
1. **Est-ce vraiment un salarié ?** (ou un indépendant, un auto-entrepreneur, un prestataire de plateforme)
2. **À qui appartient ce qu'il crée ?** (traité en Partie 2)
3. **Jusqu'où l'employeur peut-il le surveiller** avec les outils numériques ? (cybersurveillance, géolocalisation, fichiers, messagerie)

## 3.1 La définition du contrat de travail

> **Le contrat de travail est une convention par laquelle une personne (le SALARIÉ) s'engage à mettre son activité au service d'une autre personne (l'EMPLOYEUR), sous la SUBORDINATION de laquelle elle se place, moyennant une RÉMUNÉRATION.**

**Les trois éléments constitutifs :**
1. Une **prestation de travail**
2. Une **rémunération**
3. Un **LIEN DE SUBORDINATION JURIDIQUE** ← c'est le seul critère décisif

**Nature :** contrat **synallagmatique** (obligations réciproques) et **contrat d'adhésion** (le contenu est largement déterminé unilatéralement par l'employeur).

**Pourquoi la qualification est essentielle :** elle détermine l'**application du droit du travail** (durée du travail, congés, licenciement, protection sociale) et la compétence du **conseil de prud'hommes**.

## 3.2 ⭐ LE LIEN DE SUBORDINATION — le faisceau d'indices complet

> **Définition à réciter :** le lien de subordination est caractérisé par l'exécution d'un travail **sous l'autorité d'un employeur qui a le pouvoir :**
> - de **donner des ordres et des directives**,
> - d'en **contrôler l'exécution**,
> - et de **sanctionner les manquements** de son subordonné.

> **Principe fondamental (Cass. soc., 19 décembre 2000, n° 98-40.572, arrêt « Société Labbane ») :**
> **L'existence d'un contrat de travail ne dépend NI de la volonté exprimée par les parties, NI de la dénomination qu'elles ont donnée à leur convention, MAIS des CONDITIONS DE FAIT dans lesquelles est exercée l'activité.**

C'est **la** phrase à écrire. Elle signifie : on peut appeler quelqu'un « prestataire indépendant » dans le contrat, si les faits montrent la subordination, c'est un salarié.

**La présomption de non-salariat (art. L.8221-6 C. trav.) :** les personnes inscrites au registre du commerce, au répertoire des métiers, ou auprès de l'URSSAF comme travailleur indépendant sont **présumées** ne pas être salariées. Mais cette présomption est **SIMPLE** : elle peut être renversée par la preuve de conditions de fait révélant une subordination permanente.

### Le tableau des indices — TOUTES les valeurs possibles

Le prof change les indices d'un sujet à l'autre. Voilà la grille complète : pour chaque indice, ce qui plaide pour et contre.

| Indice | Plaide pour la SUBORDINATION (salariat) | Plaide pour l'INDÉPENDANCE |
|---|---|---|
| **Horaires** | Horaires **imposés** (ex. consultations de 8h30 à 12h30) | Le travailleur **choisit librement** ses horaires et son volume horaire |
| **Lieu de travail** | Lieu **imposé** par l'entreprise | Libre choix du lieu / du **secteur géographique** |
| **Fourniture des outils** | L'entreprise fournit **bureau, matériel, logiciels, véhicule, secrétariat** | Le travailleur utilise **ses propres moyens** (ex. moniteur qui possède son véhicule à double commande) |
| **Directives sur le contenu** | Programme, manuel, méthodes **fixés par l'entreprise** | Liberté **pédagogique / méthodologique** totale |
| **Clientèle** | Clientèle **imposée**, rendez-vous organisés par l'entreprise | Le travailleur **démarche** sa propre clientèle |
| **Exclusivité** | Interdiction de travailler pour d'autres | Liberté de proposer ses services à **d'autres structures concurrentes** |
| **Rémunération** | Salaire **fixé au contrat**, versé périodiquement | Honoraires libres, facturation ; ⚠️ *rétrocession d'honoraires* = indice ambigu |
| **Fixation du prix** | Tarifs **fixés unilatéralement** par l'entreprise → **INDICE DE SUBORDINATION** | Le travailleur **négocie ses tarifs** |
| **Objectifs quantitatifs** | Objectifs **imposés**, quotas | **Aucun objectif quantitatif imposé** |
| **Contrôle / évaluation** | Contrôle hiérarchique avec **pouvoir de contraindre à modifier ses pratiques** | Simple **suivi statistique** (taux de réussite) **dépourvu de prérogative hiérarchique** |
| **Pouvoir de sanction** | Sanctions **disciplinaires** (avertissement, mise à pied, licenciement) | Pénalités **purement contractuelles** (ex. pénalité d'annulation à moins de 48h) : elles visent, *comme dans toute relation d'affaires*, à **pénaliser la partie qui n'exécute pas ou exécute mal ses obligations** et **n'instaurent pas de lien de subordination** |
| **Intégration** | Intégration à un **service organisé** dont l'employeur détermine unilatéralement les conditions | Autonomie d'organisation |
| **Risque économique** | Aucun risque supporté | Le travailleur supporte le **risque d'exploitation** |

### La méthode de résolution (à appliquer telle quelle)

```
1. Poser la RÈGLE : définition du contrat de travail + lien de subordination
   + arrêt Labbane (peu importe la dénomination, seuls les faits comptent).
2. Faire le TABLEAU à 3 colonnes : Indice | Fait constaté | Analyse (subordination / indépendance).
   → Prendre EXACTEMENT le nombre d'indices demandé (souvent 3).
3. PESER : lequel des deux faisceaux est PRÉDOMINANT ?
   ⚠️ Un indice isolé ne suffit JAMAIS. Écris explicitement :
      « La fixation unilatérale des tarifs, bien qu'elle constitue un indice,
        n'est pas suffisante à elle seule pour caractériser un lien de
        subordination, au regard de la très grande liberté d'organisation accordée. »
4. CONCLURE sur la qualification, puis sur la CONSÉQUENCE
   (requalification en contrat de travail + application du droit du travail,
    ou maintien du statut d'indépendant).
```

### Exemples résolus — un par configuration

| Cas | Indices de subordination | Indices d'indépendance | Solution |
|---|---|---|---|
| **M. Savant, enseignant** | Programme fixé par l'école, emploi du temps remis, manuel choisi par l'établissement, pas de choix des niveaux | — | **Contrat de travail caractérisé.** Mais nuance : si c'était un **CDD**, il arrive à terme → **pas de licenciement** ; on peut aussi envisager une **démission** |
| **M. Charles, médecin en clinique** | Horaires 8h30-12h30 imposés, bureau et salle d'attente fournis, secrétaire de la clinique organise les RDV, patientèle imposée, rétrocession d'honoraires (pas payé par les patients) | Profession libérale, inscription à l'Ordre | **Éléments du contrat de travail réunis** selon toute vraisemblance. Réserve : il peut officier comme **médecin remplaçant** inscrit à l'Ordre |
| **Moniteurs d'auto-école sur plateforme** | Tarifs fixés unilatéralement, évaluation par les candidats, suivi du taux de réussite, pouvoir de sanction en cas d'annulation < 48h ou de mauvaise évaluation | Libre choix du nombre d'heures, des horaires, du secteur géographique ; liberté de renoncer sans objectif quantitatif ; liberté de travailler pour d'autres structures agréées ; sanctions dépourvues de prérogative hiérarchique ; pas de pouvoir sur les pratiques pédagogiques ; statut indépendant + présomption de non-salariat | **PAS de requalification.** Les indices d'indépendance sont **prédominants** ; modèle de plateforme de mise en relation entre professionnels indépendants |

> **Attention à la lecture du sujet :** le prof met souvent **en gras** dans l'énoncé le paragraphe qui donne la solution (ex. « ces stipulations visent, comme dans toute relation d'affaires, à pénaliser la partie qui n'exécute pas… et **n'instaurent pas de lien de subordination** »). **Repère le gras : c'est la réponse.**

## 3.3 La conclusion du contrat de travail

### Forme

| Exigence | Contenu |
|---|---|
| **Écrit** | Obligatoire pour **tous** les contrats de travail. **Seul le CDI à temps complet peut être non écrit**, sauf disposition conventionnelle contraire et sous réserve des formalités d'embauche (DPAE). |
| **Français** | Le contrat doit être rédigé en français, même s'il est exécuté à l'étranger. Le **salarié étranger peut demander une traduction** dans sa langue. |
| **Preuve** | Avec la remise de l'écrit (reprenant la déclaration préalable à l'embauche) et d'un **bulletin de salaire**, le salarié prouve son appartenance à l'entreprise. |

### Les 3 conditions de validité (identiques à tout contrat — cf. Partie 6)

| Condition | Précision en droit du travail |
|---|---|
| **Consentement** | Personnel et réciproque, **non vicié** par l'erreur, le dol ou la violence |
| **Capacité** | Employeur : PP majeure ou PM. Salarié : PP ; si **mineur**, consentement du **représentant légal** |
| **Contenu** | Possible, déterminé ou déterminable, **licite**, non contraire à l'ordre public et aux bonnes mœurs |

**Clauses générales obligatoires :** identité des parties, lieu de travail, grade/qualification, date de début, éléments du salaire, périodicité de la rémunération, durée du travail journalière ou hebdomadaire.

**Période d'essai :** période pendant laquelle les parties sont libres de **rompre l'engagement à tout moment, sans formalité**. À son issue (éventuellement après renouvellement), l'engagement devient **définitif**.

### Les obligations des parties

| Obligations de l'EMPLOYEUR | Obligations du SALARIÉ |
|---|---|
| Procurer le **travail convenu** et les **moyens** de le réaliser | Exécuter **personnellement et consciencieusement** le travail convenu |
| **Rémunérer** au taux et aux dates prévus | Prendre **soin du matériel** confié |
| Respecter la **réglementation légale et conventionnelle** (lois, conventions collectives) | Respecter la **discipline intérieure** de l'entreprise |
| (+ obligation de sécurité, de loyauté, d'adaptation) | Respecter le **secret professionnel** et s'abstenir de tout **acte de concurrence** |

## 3.4 ⭐ LES CLAUSES FACULTATIVES — le tableau à connaître par cœur

Question ultra-classique : « justifier l'intérêt de la clause » / « apprécier sa validité ».

| Clause | Définition | Conditions de validité | Piège |
|---|---|---|---|
| **Clause d'EXCLUSIVITÉ** | Interdit au salarié, **PENDANT** l'exécution du contrat, de travailler pour d'autres employeurs ou d'exercer une activité concurrente | Être **indispensable à la protection des intérêts légitimes** de l'entreprise, **justifiée** par la tâche à accomplir, **proportionnée** au but recherché | Elle n'empêche pas le salarié de **développer sur son temps de loisir** une activité non concurrente |
| **Clause de NON-CONCURRENCE** | Interdit au salarié, **APRÈS** la rupture, d'exercer une activité susceptible de nuire à l'ancien employeur | **4 conditions CUMULATIVES** : ① limitée dans le **TEMPS** ② limitée dans l'**ESPACE** ③ **proportionnée** compte tenu de l'emploi occupé et **justifiée** par les intérêts légitimes de l'entreprise ④ **CONTREPARTIE FINANCIÈRE** | ⚠️ **Une contrepartie DÉRISOIRE équivaut à une ABSENCE de contrepartie** → clause **NULLE**. Ex. 100 € pour 2 ans ; ou 2,4 mois de salaire pour 24 mois d'interdiction |
| **Clause de MOBILITÉ** | Le salarié accepte **par avance** une modification de son lieu de travail | Zone géographique **précisément définie**, ne peut être étendue unilatéralement, mise en œuvre de **bonne foi** et dans l'intérêt de l'entreprise | Le refus d'une mobilité valablement stipulée peut justifier un licenciement |
| **Clause de DÉDIT-FORMATION** | Le salarié bénéficiant d'une formation financée par l'entreprise s'engage à y rester une **durée minimale** ; à défaut il rembourse | Formation **réelle** entraînant des frais **au-delà** des obligations légales ; clause précisant **objet, durée, coût, engagement** ; conclue **avant** la formation ; remboursement **proportionné** | ⚠️ La jurisprudence **requalifie** le remboursement en **indemnité calculée sur la base du préjudice réellement subi** par l'employeur |
| **Clause de CONFIDENTIALITÉ** | Interdiction de divulguer des informations sensibles | Pas de contrepartie exigée ; peut survivre à la rupture | À distinguer de la non-concurrence |
| **Clause de GARANTIE D'EMPLOI** | L'employeur s'interdit de licencier pendant une durée | — | — |

### Exemple de calcul de dédit-formation (le prof adore changer les chiffres)

> Formation de **4 000 €**, engagement de **2 ans**, remboursement de **500 € par trimestre restant**.
> Le salarié part **1 an** après la fin de la formation.
> → Il reste **1 an** = **4 trimestres** → il doit **4 × 500 = 2 000 €**.
>
> **Méthode générale :** `Montant dû = (nombre de trimestres NON accomplis) × (montant par trimestre)`, dans la **limite des frais réellement engagés**.
>
> **Variantes à savoir traiter :**
> - S'il part **au bout de 2 ans** (terme atteint) → **il ne doit rien**, il peut partir librement.
> - S'il est **licencié** (rupture à l'initiative de l'employeur) → la clause **ne joue pas**, il ne doit rien.
> - S'il démissionne **pendant** la formation → remboursement intégral possible.
> - Si la contrepartie ou les modalités ne sont pas précisées → clause **nulle**.

## 3.5 Le télétravail

> **Définition :** le télétravail est le travail effectué par un salarié **éloigné de son employeur**, en utilisant les technologies de l'information.

**Règles à retenir :**
- Le télétravailleur reste un **salarié de droit commun** : toutes les dispositions du droit du travail lui sont applicables (durée du travail, heures supplémentaires, santé-sécurité, accident du travail).
- **Cadre juridique : l'Accord national interprofessionnel (ANI) sur le télétravail.**
- **Caractère VOLONTAIRE** : pour le salarié **et** pour l'employeur. Il peut faire partie des conditions d'embauche ou être mis en place ensuite sur la base du volontariat → dans ce cas, **avenant au contrat de travail**.
- **Respect de la vie privée** : l'employeur fixe, **en concertation avec le salarié**, les **plages horaires** durant lesquelles il peut le contacter (→ droit à la déconnexion).
- **Contrôle** : si un moyen de surveillance est mis en place, il doit être **PERTINENT et PROPORTIONNÉ à l'objectif poursuivi**, et **le télétravailleur doit en être INFORMÉ**.
- **Consultation préalable du CSE** (comité social et économique) obligatoire.
- Le contrat doit fixer précisément la **durée du travail** et le principe de **rémunération des heures supplémentaires**.

## 3.6 ⭐ LES TIC DANS LA RELATION DE TRAVAIL — surveillance et preuve

C'est le morceau le plus tombé en CC1. Structure-le en 4 sous-questions.

### 3.6.1 Le principe de départ

> **L'ordinateur mis à disposition par l'entreprise ne relève PAS de la vie privée : il reste la PROPRIÉTÉ DE L'ENTREPRISE.**
> Il ne peut comporter que **subsidiairement** des informations relevant de la vie privée.
> **Un mot de passe ou un login protégeant l'accès à l'ordinateur ne le transforme PAS en ordinateur à usage privé.**

> **PRÉSOMPTION D'UTILISATION PROFESSIONNELLE :** Internet et la messagerie sont des outils mis à la disposition des salariés **en vue d'une utilisation professionnelle**. Les fichiers, dossiers, connexions et courriels créés avec l'outil informatique de l'entreprise sont **PRÉSUMÉS PROFESSIONNELS**.

**Conséquence :** le fait que l'employeur ait accès aux documents professionnels détenus par le salarié **l'autorise à s'en servir pour prouver une faute** du salarié.

### 3.6.2 L'exception : les fichiers identifiés comme « personnels »

> Au nom du respect de la vie privée, les fichiers **identifiés comme personnels** sont **EN PRINCIPE inviolables**.
> **Mais cette inviolabilité est conditionnée** : l'employeur peut quand même y accéder :
> - **en présence du salarié**, ou
> - **après l'avoir dûment appelé** (convoqué), ou
> - **en cas de RISQUE ou d'ÉVÉNEMENT PARTICULIER** dans la vie de l'entreprise.
>
> *(Le cours souligne lui-même que cette dernière formule « est vague ! ».)*

**Pour la CNIL :** un message envoyé ou reçu depuis le poste de travail revêt un **caractère professionnel**, **sauf indication contraire dans l'objet du message ou dans le nom du répertoire**, qui lui conférerait le caractère d'une correspondance privée.

**Recommandations CNIL au salarié** — il a la possibilité :
- d'**envoyer et recevoir ses courriers personnels** depuis une **boîte personnelle hébergée sur un serveur externe** ;
- d'indiquer la mention **« personnel »** dans l'**objet** de son message ;
- d'**archiver** le message dans un **répertoire personnel**.

### 3.6.3 ⚠️ L'effet de la CHARTE INFORMATIQUE sur le vocabulaire

C'est le piège le plus vicieux du cours.

> Les arrêts de la Cour de cassation se fondent sur le **contenu de la charte informatique intégrée au règlement intérieur** pour déterminer l'étendue des droits de l'employeur.
>
> **Si la charte impose que les données personnelles soient stockées dans un répertoire nommé « PRIVÉ », alors un dossier nommé « données personnelles » ou « perso » ne suffit PAS** à conférer le caractère personnel : il est **réputé professionnel** et l'employeur peut le consulter librement.

**À écrire :** « La dénomination retenue par le salarié ne correspond pas à celle imposée par la charte informatique ; les fichiers non identifiés "privé" sont donc **réputés professionnels**. L'employeur pourra néanmoins, en présence du salarié ou après l'avoir prévenu, prendre connaissance des informations contenues dans le répertoire "privé". »

**Utilité de la charte informatique (question de cours) :** elle **définit les modalités et les limites de l'utilisation** des moyens informatiques mis à disposition des salariés et permet de **sanctionner les manquements sans qu'il soit nécessaire d'ouvrir les fichiers et messages personnels**. Pour être opposable, elle doit être **annexée au règlement intérieur** (consultation du CSE, dépôt au greffe du CPH, transmission à l'inspection du travail, affichage).

### 3.6.4 Le tableau de la LICÉITÉ DE LA PREUVE — toutes les valeurs possibles

C'est la question « ce moyen de preuve est-il recevable ? ». Chaque ligne est un sujet potentiel.

| Moyen de preuve | Recevable ? | Motif |
|---|---|---|
| **Fichiers professionnels** sur l'ordinateur pro | ✅ Oui, librement | Présomption d'utilisation professionnelle |
| **Fichiers nommés « personnel »/« privé »** conformément à la charte | ⚠️ Seulement **en présence du salarié**, ou après l'avoir appelé, ou en cas de **risque particulier** | Respect de la vie privée |
| **Fichiers nommés « données personnelles »** alors que la charte impose « privé » | ✅ Oui | Dénomination non conforme → réputés professionnels |
| **CLÉ USB** connectée à l'outil informatique professionnel | ✅ Oui, **hors la présence du salarié**, pour les fichiers **non identifiés comme personnels** | *« Une clé USB, dès lors qu'elle est connectée à un outil informatique mis à disposition par l'employeur pour l'exécution du contrat, est **présumée utilisée à des fins professionnelles** »* — elle est le **prolongement de l'outil informatique** |
| **Photos trouvées dans le TIROIR du bureau**, puis fouille des fichiers « perso » de l'ordinateur | ❌ **Non** | La découverte dans le tiroir ne constituait **pas un risque ou événement particulier** justifiant l'ouverture des fichiers personnels → licenciement sans cause réelle et sérieuse, DI dus |
| **Conversation Messenger** ouverte spontanément sur l'écran, découverte par des collègues | ❌ **Non** | Peu importe que la fenêtre soit apparue spontanément : **dès lors qu'il n'est pas démontré que cet affichage résulte d'un acte volontaire du titulaire du compte**, l'employeur ne peut s'en servir comme preuve (messagerie personnelle → **secret des correspondances**) |
| **SMS** reçus par la salariée sur son téléphone, retranscrits par huissier | ✅ **Oui** | Un SMS envoyé **s'affiche sur l'appareil du destinataire et s'enregistre automatiquement** : il est **impossible de prétendre à une exploitation du message à l'insu** de l'expéditeur → preuve **loyale** |
| **Enregistrement d'une conversation téléphonique à l'insu** de l'interlocuteur | ❌ **Non** | **Procédé déloyal** → information **irrecevable** |
| **Géolocalisation** d'un véhicule | ⚠️ Conditions strictes → voir ci-dessous |
| **Vidéosurveillance** non déclarée / sans information des salariés | ❌ Non | Défaut d'information préalable et de proportionnalité |

> **La distinction SMS / enregistrement téléphonique est un grand classique.** Explique-la : « Une conversation téléphonique n'est pas comparable à un échange de SMS. Dans le premier cas, **seul l'enregistrement à l'insu** de l'interlocuteur permet de rapporter ses propos : c'est un procédé **déloyal**. Dans le second, le message **s'enregistre automatiquement** sur l'appareil du destinataire : son exploitation n'a rien de clandestin. »

### 3.6.5 La GÉOLOCALISATION — les 3 conditions cumulatives

> L'utilisation d'un système de géolocalisation pour assurer le **contrôle de la durée du travail** n'est licite que si :
> 1. **Ce contrôle ne peut pas être fait par un AUTRE MOYEN** (subsidiarité) ;
> 2. Le salarié **NE DISPOSE PAS d'une liberté dans l'organisation de son travail** (à défaut, la géolocalisation n'est **pas justifiée**) ;
> 3. Le système est utilisé **UNIQUEMENT pour les FINALITÉS DÉCLARÉES** à la CNIL et **portées à la connaissance des salariés**.
>
> Base légale : **art. L.1121-1 du Code du travail** — *nul ne peut apporter aux droits des personnes et aux libertés individuelles et collectives de restrictions qui ne seraient pas justifiées par la nature de la tâche à accomplir ni proportionnées au but recherché* (principe de **proportionnalité**).

**Application type :** si le contrat de travail prévoit déjà l'obligation de rédiger des **rapports d'activité hebdomadaires**, alors un autre moyen de contrôle existe → **la géolocalisation est exclue** pour contrôler l'activité. Et si le salarié a été informé de l'existence du dispositif **sans qu'on lui indique qu'il servirait à surveiller l'exactitude de ses comptes rendus et notes de frais**, l'usage à cette fin est **illicite** (détournement de finalité).

> ⚠️ **La subtilité procédurale de l'arrêt du cours :** malgré tout cela, la Cour de cassation a **rejeté le pourvoi** car il ne résultait ni des pièces de la procédure ni de l'arrêt que le salarié **avait soutenu devant la cour d'appel** ne pas avoir été informé de cette finalité → **le moyen est IRRECEVABLE** (moyen nouveau, mélangé de fait et de droit, invoqué pour la première fois en cassation). **L'affaire s'arrête là.**
> Moralité à écrire : la solution au fond était favorable au salarié, mais il a perdu pour une **raison de procédure**.

### 3.6.6 Les obligations de l'employeur qui met en place une cybersurveillance (à réciter)

1. **INFORMER PRÉALABLEMENT le personnel** des moyens et techniques de contrôle de l'activité.
2. **CONSULTER le CSE** (information et consultation préalables).
3. **Inscrire le dispositif** dans le contrat de travail, la **charte informatique** ou le **règlement intérieur**.
4. **Formalité CNIL** : le dispositif de contrôle constitue un **traitement de données à caractère personnel** → registre des traitements, et **analyse d'impact** si surveillance à grande échelle. *(Le cours parle de « déclaration à la CNIL » : depuis le RGPD la déclaration est supprimée et remplacée par l'auto-responsabilité, le registre et l'AIPD — mais reprends la formulation du cours en la nuançant.)*
5. Respecter le **principe de PROPORTIONNALITÉ** : les restrictions aux libertés individuelles et collectives doivent être **proportionnées au but recherché**.
6. Respecter la **finalité déclarée** (pas de détournement de finalité).

## 3.7 La responsabilité des administrateurs systèmes et réseaux

| Rôle | Missions |
|---|---|
| **Administrateur SYSTÈMES** | Commande les serveurs, les rend opérationnels, gère leurs évolutions ; transmet les **droits d'accès et identifiants** ; met en œuvre les **sauvegardes** de serveurs et de données |
| **Administrateur RÉSEAUX** | Responsable des systèmes de **sécurité internes et externes** ; rend inaccessibles les ressources aux personnes définies par le **RSI** (responsable de la sécurité informatique) ; détient des informations sur les utilisateurs (données de connexion, accès administrateur) ; peut **contrôler à distance** l'accès aux postes de travail |

**Les deux obligations légales :**

| Obligation | Contenu |
|---|---|
| **Transparence et proportionnalité** | L'intervention des administrateurs et **leurs conditions d'intervention sont diffusées à l'ensemble des salariés** ; le personnel est informé **préalablement** à la mise en œuvre des moyens de contrôle |
| **Confidentialité renforcée** | Les administrateurs **ne doivent pas divulguer** les informations connues dans le cadre de leurs fonctions **si elles relèvent de la vie privée** des utilisateurs et **ne mettent en cause ni le fonctionnement technique des applications, ni leur sécurité, ni l'intérêt de l'entreprise**. Ils **ne sauraient être contraints** de le faire, sauf disposition législative particulière |

**Responsabilité pénale (art. 432-9 C. pén.) :** le fait, pour une personne chargée d'une mission de service public agissant dans l'exercice de ses fonctions, de commettre le **détournement, la suppression ou l'ouverture de correspondances**, ou la **révélation de leur contenu**, est puni de **3 ans d'emprisonnement et 45 000 € d'amende**. Les mêmes peines s'appliquent à un **agent d'un exploitant de réseaux ouverts au public** de communications électroniques ou d'un **fournisseur de services de télécommunications**.

**Tempérament jurisprudentiel :** la **lecture et la retranscription de messages par l'administrateur réseaux entre dans le cadre de son activité** (nécessité technique et de sécurité) et **ne peut être qualifiée d'interception illicite** — à condition que les **salariés aient été informés** des conditions d'intervention de l'administrateur, ainsi que **les membres du CSE**.

---

# PARTIE 4 — LE RGPD (RÈGLEMENT GÉNÉRAL SUR LA PROTECTION DES DONNÉES)

## 4.0 La logique du chapitre

Le RGPD est un **règlement européen** : il est **d'application directe** dans tous les États membres (pas besoin de transposition), et il prime sur la loi nationale. En France il s'articule avec la **loi Informatique et Libertés du 6 janvier 1978** (modifiée).

Le raisonnement se fait **toujours dans cet ordre** :

```
1. Est-ce une DONNÉE À CARACTÈRE PERSONNEL ?          → si non, RGPD inapplicable
2. Y a-t-il un TRAITEMENT ?                            → si non, RGPD inapplicable
3. Le RGPD s'applique-t-il TERRITORIALEMENT ?          → responsable/sous-traitant dans l'UE
                                                          OU personnes ciblées dans l'UE
4. Est-ce une donnée SENSIBLE (interdite) ?            → si oui : interdiction + exceptions
5. Le traitement est-il LICITE et LOYAL ?              → base légale, consentement valable
6. Les PRINCIPES sont-ils respectés ?                  → finalité, minimisation, durée,
                                                          exactitude, sécurité, transparence
7. Les DROITS des personnes sont-ils garantis ?        → information, accès, opposition,
                                                          rectification, effacement, portabilité
8. Les OBLIGATIONS formelles sont-elles remplies ?     → registre, DPD, AIPD, notification 72h
9. Quelles SANCTIONS ?                                 → jusqu'à 20 M€ ou 4 % du CA mondial
```

## 4.1 Les définitions fondamentales

> **DONNÉE À CARACTÈRE PERSONNEL (DCP) :** toute information relative à une **personne physique identifiée ou qui peut être identifiée, DIRECTEMENT OU INDIRECTEMENT**, par référence à un numéro d'identification ou à un ou plusieurs éléments qui lui sont propres.
> Une donnée ne peut être qualifiée de DCP qu'à partir du moment où elle est **rattachée à une personne physique identifiable**.

**Exemples de DCP (le prof pioche dedans) :** nom, prénom, **matricule**, **empreinte digitale**, **ADN**, **plaque d'immatriculation**, adresse mail `nom.prenom@societe.com`, **numéro de téléphone**, **adresse IP**, identifiant de connexion, cookie avec code utilisateur unique, données de **géolocalisation**, photo, numéro de sécurité sociale, données de santé.

**Ne sont PAS des DCP :** les données d'une **personne morale** (une société n'est pas une personne physique), les données **anonymisées de manière irréversible**, les données agrégées non ré-identifiables.
⚠️ Les données **pseudonymisées** (chiffrées, remplacées par un code) **restent** des DCP, car la ré-identification est possible.

> **⭐ L'ADRESSE IP (arrêt à connaître) :** les adresses IP, **qui permettent d'identifier INDIRECTEMENT une personne physique, SONT des données à caractère personnel**. Leur collecte constitue donc un **traitement de DCP** soumis au RGPD.
> *(À l'époque de l'arrêt : elle devait faire l'objet d'une déclaration préalable à la CNIL ; la cour d'appel qui avait jugé que l'IP « se rapporte à un ordinateur et non à l'utilisateur » a été **cassée** pour violation des textes. Conséquence : l'absence de déclaration rendait **caduque** l'utilisation de l'IP comme moyen de preuve.)*

> **TRAITEMENT DE DCP :** toute opération portant sur de telles données, **quel que soit le procédé utilisé** : collecte, enregistrement, organisation, conservation, adaptation, modification, extraction, consultation, utilisation, communication par transmission, diffusion, rapprochement, interconnexion, verrouillage, effacement, destruction.

**Un traitement peut être manuel** (fichier papier structuré) : le RGPD ne vise pas que l'informatique.

> **FICHIER :** tout ensemble de DCP collectées, **structurées selon des critères déterminés** permettant en pratique de les retrouver aisément aux fins d'une utilisation ultérieure.

## 4.2 Le champ d'application

### Champ matériel

Le RGPD s'applique aux traitements de DCP contenues ou appelées à figurer dans des fichiers, **À L'EXCEPTION des traitements mis en œuvre pour l'exercice d'activités EXCLUSIVEMENT PERSONNELLES ou DOMESTIQUES** (répertoire téléphonique, fichier de notes, agenda personnel).

> **⭐ Le raisonnement du blog familial (cas type, avec la variable « bannières publicitaires ») :**
> **Principe :** l'aspect **non professionnel restreint** le champ d'application du RGPD, tandis que le **caractère non exclusif l'ÉTEND**.
> - Un blog partageant des photos de vacances **au sein du seul cercle familial** → activité **exclusivement personnelle** → **hors RGPD**.
> - Le même blog **avec des bannières publicitaires** permettant au propriétaire d'en tirer un **profit financier** → l'activité n'est **plus exclusivement personnelle** → **le blog ENTRE dans le champ du RGPD**.
>
> **Variables possibles que le prof peut changer :** accessibilité publique du blog (ouvert à tous = plus exclusivement domestique), monétisation, référencement, nombre de visiteurs, présence de données de tiers.

**Le RGPD s'applique AUSSI à ceux qui FOURNISSENT LES MOYENS** de traiter des données pour des activités personnelles ou domestiques : les **fournisseurs de réseaux sociaux (Meta)** sont soumis au RGPD, même si leurs utilisateurs individuels agissent à titre privé.

### Champ territorial

Le RGPD s'applique dès lors que :
- un **responsable du traitement OU un sous-traitant est ÉTABLI sur le territoire de l'UE** (que le traitement ait lieu ou non dans l'UE), **OU**
- un **résident européen est VISÉ par un traitement** (offre de biens/services ou suivi du comportement), **même si le responsable n'est pas établi dans l'UE**.

## 4.3 Les acteurs

| Acteur | Définition | Exemple |
|---|---|---|
| **Responsable du traitement** | Celui qui détermine les **FINALITÉS et les MOYENS** du traitement | L'entreprise qui gère son fichier clients |
| **Sous-traitant** | Celui qui traite des DCP **POUR LE COMPTE** d'un responsable de traitement, **sur ses instructions** | Hébergeur, intégrateur de logiciels, société de sécurité informatique, ESN, agence de marketing |
| **Responsables CONJOINTS** | Deux acteurs déterminant **ensemble** finalités et moyens | Facebook + l'administrateur d'une page fan |
| **Personne concernée** | La personne physique dont les données sont traitées | Le client, le salarié, l'internaute |
| **DPD / DPO** | Délégué à la protection des données : **garant de la mise en œuvre du RGPD** | Salarié ou prestataire externe |
| **CNIL** | Autorité de contrôle française | — |

> **La FINALITÉ d'un traitement** = l'**objectif principal** de l'application informatique de données personnelles. Exemples : gestion des recrutements, gestion des clients, enquête de satisfaction, surveillance des locaux, ciblage publicitaire.

### La méthode « qui est responsable, qui est sous-traitant ? »

C'est une question à **tiroirs** que le prof aime multiplier. Applique cette règle :

> **On est SOUS-TRAITANT quand on traite les données POUR LE COMPTE et SUR INSTRUCTIONS d'autrui.**
> **On est RESPONSABLE quand on décide soi-même POURQUOI et COMMENT on traite.**
> **La même entité peut être les deux, selon le traitement considéré.**

**Exemple résolu (entreprise A qui envoie des courriers de prospection avec les fichiers de B et C) :**
- **A est SOUS-TRAITANT** de B et C, car elle traite les données nécessaires à l'envoi des courriers **pour le compte et sur les instructions** de B et C.
- **B et C sont RESPONSABLES DU TRAITEMENT** de leur gestion commerciale, qui inclut l'envoi de courriers de prospection.
- **A peut AUSSI être responsable de traitement** : pour la **gestion de son propre personnel** (elle est employeur), et pour la gestion de **ses propres clients** — dont font partie B et C.

**Exemple résolu (page fan Facebook) :**
> **Principe :** est responsable du traitement la personne qui détermine, à titre principal, les finalités ; est également responsable la personne qui **participe, PAR SES PARAMÉTRAGES** (choix de l'audience cible, objectifs de gestion ou de promotion de ses activités), à la détermination des finalités et des moyens du traitement des DCP des visiteurs de sa page.
>
> **Au cas présent :** le fait pour un administrateur de page fan d'utiliser Facebook pour bénéficier de ses services **ne l'exonère pas du respect de ses obligations** en matière de protection des DCP. La reconnaissance d'une **responsabilité CONJOINTE** de l'exploitant du réseau social et de l'administrateur de la page assure une **protection plus complète** des droits des visiteurs. → **La société S n'est pas dans son bon droit.**

### Les 3 obligations du SOUS-TRAITANT

| Obligation | Contenu |
|---|---|
| **Transparence et traçabilité** | Mettre à disposition des clients les informations démontrant le respect des obligations ; **tenir un registre** recensant les clients et décrivant les traitements effectués |
| **Prise en compte des principes de protection des données** (privacy by design / by default) | Les applications ou services doivent intégrer les principes et garantir que **seules sont traitées les données nécessaires** à la finalité, au regard de l'étendue du traitement, de la durée de conservation et du nombre de personnes y ayant accès |
| **Sécurité des données traitées** | Salariés soumis à une **obligation de confidentialité** ; **notifier au client toute violation** de ses données ; prendre les mesures garantissant un **niveau de sécurité adapté** ; **supprimer les données au terme de la prestation** |

### Le délégué à la protection des données (DPD/DPO)

- Il est le **garant de la mise en œuvre du RGPD**.
- Le responsable du traitement et le sous-traitant veillent à ce qu'il soit **associé** à toutes les questions relatives à la protection des DCP.
- Il peut être un **salarié** du responsable/sous-traitant, ou exercer sa mission **sur la base d'un contrat de service** (DPO externe).
- **INDÉPENDANCE :** il **ne reçoit AUCUNE instruction** concernant l'exercice de ses missions ; il **ne peut être relevé de ses fonctions ni pénalisé** pour l'exercice de ses missions.
- ⚠️ **La désignation d'un DPD ne permet PAS de se soustraire aux autres obligations** (notamment à l'autorisation requise pour certains traitements sensibles).

## 4.4 La CNIL : ses 4 missions

| Mission | Contenu |
|---|---|
| **Informer / protéger** | Informe particuliers et professionnels, met à disposition des outils, mène des actions de **sensibilisation**, promeut les **technologies protectrices de la vie privée** |
| **Accompagner / conseiller** | Objectif de **mise en conformité** : avis sur les projets de loi, **autorisations** pour les traitements les plus sensibles, **recommandations** fixant un cadre juridique ; **certifie** la conformité des processus d'**anonymisation** |
| **Contrôler et sanctionner** | Lors d'un contrôle, elle peut : ① **accéder aux locaux professionnels** ② demander **communication de tout document** nécessaire et **en prendre copie** ③ recueillir tout **renseignement utile et entendre toute personne** ④ **accéder aux programmes informatiques et aux données**. Elle **dénonce au Procureur de la République** les infractions dont elle a connaissance |
| **Anticiper** | Veille sur les usages ayant un impact sur la vie privée, contribution au développement de solutions protectrices, **réflexion sur les problèmes éthiques** |

**Éventail des sanctions CNIL :** avertissement → mise en demeure → **rappel à l'ordre** → **injonction de cesser le traitement** (éventuellement sous astreinte) → **limitation temporaire ou définitive** du traitement → **amende administrative** → **publicité de la sanction** (« name and shame »).

> **Le cas type de la mauvaise foi :** un syndicat envoie des courriels de prospection non sollicités sur une **messagerie professionnelle**, ignore plusieurs courriers, une mise en demeure et une convocation de la CNIL → sanction pécuniaire de 5 000 € **ET publication de la sanction dans un quotidien national**.
> **Principe :** une **adresse électronique professionnelle est une DCP** ; elle doit avoir été **collectée de manière loyale** et la personne doit pouvoir exercer son **droit d'opposition**.
> **Solution :** en ignorant délibérément et à plusieurs reprises les injonctions, le syndicat a fait preuve de **mauvaise foi** ; la CNIL sanctionne **publiquement** les organismes qui ignorent ses mises en demeure ou ne collaborent pas avec elle.

## 4.5 Les données interdites (données sensibles)

| **DONNÉES INTERDITES** | **EXCEPTIONS** |
|---|---|
| Origines **raciales et ethniques** | **Consentement** de la personne concernée |
| Opinions **politiques** | Traitements par un organisme à caractère **religieux, philosophique, politique ou syndical** pour les données de **SES MEMBRES** |
| Opinions **religieuses** | Données **rendues publiques par la personne** concernée |
| Opinions **philosophiques** | Traitements nécessaires à la **constatation, à l'exercice ou à la défense d'un droit en justice** |
| **Appartenance syndicale** | Traitements **statistiques réalisés par l'INSEE** |
| **Santé** et **vie sexuelle** | Traitements nécessaires à la **médecine**, mis en œuvre par un **professionnel de santé tenu au secret professionnel** |
| *(+ données génétiques, biométriques aux fins d'identifier une personne)* | *(+ sauvegarde de la vie humaine, intérêt public important)* |

> **⚠️ Point du cours :** dès lors qu'un tel fichier est constitué, **une AUTORISATION (et non une simple déclaration) est nécessaire de la part de la CNIL**. **La désignation d'un DPD ne permet pas de se soustraire à cette obligation.**

**Applications type :**
- Une gérante veut **segmenter sa base clients selon les fêtes religieuses** en indiquant l'appartenance religieuse → **interdit**, sauf autorisation CNIL / consentement explicite. → Réponse : « Mme A ne peut utiliser ce type de données qu'après autorisation de la CNIL. »
- Un **syndicat** tient un fichier de l'appartenance syndicale de **ses adhérents** → **licite** (exception « membres »), sous réserve de l'autorisation.
- Un **parti politique** tient un fichier de l'appartenance politique de **ses adhérents** → **licite** au même titre.
- Un **employeur** qui ficherait l'appartenance syndicale de ses salariés → **totalement interdit**, aucune exception.

## 4.6 La licéité du traitement et le consentement

### Les conditions de licéité et de loyauté

Un traitement n'est licite que si les données sont :
- **collectées de manière LOYALE ET LICITE**, pour des **finalités DÉTERMINÉES, EXPLICITES ET LÉGITIMES** ;
- les traitements **ultérieurs** doivent être **compatibles** avec ces finalités (*un traitement ultérieur à des fins statistiques est réputé compatible*) ;
- **ADÉQUATES, PERTINENTES ET NON EXCESSIVES** au regard des finalités (**principe de minimisation**) ;
- **exactes** et tenues à jour ;
- **conservées pendant une durée qui N'EXCÈDE PAS la durée nécessaire** aux finalités (**limitation de la conservation**) ;
- traitées avec une **sécurité appropriée**.

### Le consentement

> **Définition :** toute manifestation de volonté **LIBRE, SPÉCIFIQUE, ÉCLAIRÉE (informée) et UNIVOQUE** par laquelle une personne accepte que ses DCP fassent l'objet d'un traitement.

**Le consentement suppose (les 4 exigences du cours) :**
1. Une **information préalable** ;
2. Un **accord pour chaque traitement spécifique** (pas de consentement global) ;
3. Une **indépendance vis-à-vis de l'organisation** qui demande le consentement (pas de déséquilibre, pas de conditionnement d'un service) ;
4. Une **possibilité de revenir sur sa décision** (retrait aussi simple que le don).

> **« Le droit d'être informé est essentiel pour que la collecte des données soit qualifiée de LOYALE. »**

**Les 5 dimensions des droits des personnes (formulation du cours) :** **être informé, faire opposition, interrogation (accès), rectification des données, suppression.**

**Application (cas SDK / start-ups de publicité géolocalisée) :**
> **Principe :** selon le RGPD, le consentement suppose une **information préalable**.
> **Au cas présent :** les personnes ne sont pas informées, lors du téléchargement des applications partenaires, qu'un **SDK** intégré collecte leurs données, notamment de **localisation**. Au moment de l'installation, l'utilisateur n'est informé **ni de la finalité de ciblage publicitaire, ni de l'identité du responsable du traitement**. Les données sont donc traitées **à l'insu des utilisateurs, sans consentement préalable** → **manquement au RGPD**.

**Application (durée de conservation des données de géolocalisation) :**
> **Principe :** les DCP collectées ne peuvent être conservées que pour une **durée strictement proportionnelle à la finalité** du traitement.
> **Au cas présent :** une conservation de **13 mois** est **disproportionnée** au regard d'une finalité de ciblage publicitaire ; pour la CNIL, **seuls quelques mois** semblent possibles.

## 4.7 Les droits des personnes concernées

| Droit | Contenu | Point d'attention |
|---|---|---|
| **Information** | Être informé de la finalité, du responsable, des destinataires, de la durée, des droits | Condition de la **loyauté** de la collecte |
| **Accès** (interrogation) | Obtenir confirmation et copie des données traitées | Gratuit (1re copie) |
| **Rectification** | Faire corriger des données inexactes | — |
| **Opposition** | S'opposer au traitement pour motif légitime ; **absolu en prospection commerciale** | — |
| **Effacement / DROIT À L'OUBLI** | Obtenir l'effacement des données | Cas d'ouverture ci-dessous |
| **PORTABILITÉ** | **Recevoir** les DCP la concernant qu'elle a fournies, dans un format structuré, et les **transmettre à un autre responsable du traitement**, **sans que le premier y fasse obstacle** | Vise à limiter l'enfermement propriétaire |
| **Limitation** | Geler le traitement le temps d'une vérification | — |
| **Ne pas faire l'objet d'une décision automatisée** | Y compris le profilage produisant des effets juridiques | — |

**Le DROIT À L'OUBLI s'applique lorsque :**
- les DCP ne sont **plus nécessaires** au regard des finalités pour lesquelles elles ont été collectées ;
- la personne **retire son consentement** ;
- la personne **s'oppose** au traitement ;
- les données doivent être effacées pour respecter une **obligation légale** ;
- (+ traitement illicite, données d'un mineur collectées via un service en ligne).

**Question type « un client veut être radié du fichier clients » :**
> Le client peut : ① utiliser un **lien de désinscription** prévu à cet effet (présent dans les messages publicitaires) ; ② adresser un **courrier au responsable du traitement**.
> **L'entreprise a l'obligation de tenir compte de cette demande** (et de répondre dans un délai d'un mois).

**Question type « les deux textes qui encadrent la création des fichiers nominatifs » :**
> ① **Le RGPD** (et la loi Informatique et Libertés) : il donne aux personnes physiques inscrites dans les fichiers un droit à l'**information préalable**, un **droit d'accès**, un **droit d'opposition**, un **droit de rectification** et un **droit à l'oubli**.
> ② **Le Code civil** (art. 9) : « chacun a droit au respect de sa vie privée ». On peut l'invoquer pour interdire la collecte d'informations comme l'orientation sexuelle, l'état de santé ou les convictions religieuses.

## 4.8 Les obligations formelles

| Obligation | Contenu | Chiffre clé |
|---|---|---|
| **Registre des activités de traitement** | Inventaire de tous les traitements mis en œuvre. Tenu par le **responsable du traitement** **ET** par le **sous-traitant**. Il **prouve le respect** des obligations (accountability) | — |
| **Notification des violations de données** | À la **CNIL** par le responsable du traitement | **72 heures** après en avoir pris connaissance |
| **Notification du sous-traitant au responsable** | « Dans les **meilleurs délais** » après en avoir pris connaissance | — |
| **Information des personnes concernées** | Si la violation est susceptible d'engendrer un **risque élevé** pour leurs droits et libertés | Dans les meilleurs délais |
| **Analyse d'impact (AIPD/DPIA)** | Étude des risques du traitement envisagé, conditionnant les mesures techniques et organisationnelles | 3 hypothèses obligatoires ↓ |

> **VIOLATION DE DONNÉES PERSONNELLES :** toute **violation de la sécurité** entraînant, de manière **accidentelle ou illicite**, la **destruction, la perte, l'altération, la divulgation ou l'accès non autorisé** à des données personnelles faisant l'objet d'un traitement.
> - **Accidentelle** : divulgation par erreur, par un salarié, de données clients ; perte d'une clé USB ; envoi d'un mail au mauvais destinataire.
> - **Illicite ou malveillante** : **piratage informatique**, rançongiciel, vol de base.

**L'ANALYSE D'IMPACT est OBLIGATOIRE dans 3 hypothèses :**
1. **Évaluation d'aspects personnels** concernant des personnes physiques, fondée sur un **traitement automatisé (PROFILAGE)**, ou sur la base de laquelle sont prises des **décisions produisant des effets juridiques** ;
2. Traitement **à grande échelle de données SENSIBLES** ou de données relatives à des **condamnations pénales et infractions** ;
3. **Surveillance systématique à grande échelle d'une zone accessible au public**.

> **LE PROFILAGE :** il a pour but de **collecter des informations sur un individu afin d'analyser ses caractéristiques et ses comportements**, pour le placer dans une **catégorie** et/ou **prédire ou évaluer** certaines caractéristiques (capacité à réaliser une tâche, intérêts, comportement futur).

**Transferts hors UE :** un transfert vers un pays tiers ou une organisation internationale ne peut avoir lieu que si les **conditions définies par le RGPD sont respectées** par le responsable et le sous-traitant (décision d'adéquation, clauses contractuelles types, BCR, garanties appropriées).

## 4.9 Les sanctions

> **La violation des dispositions du RGPD fait l'objet d'amendes administratives s'élevant jusqu'à 20 MILLIONS D'EUROS ou jusqu'à 4 % DU CHIFFRE D'AFFAIRES ANNUEL MONDIAL** (le montant le plus élevé étant retenu).
> *(Deux paliers en réalité : 10 M€ / 2 % pour les manquements « formels » — registre, DPO, sécurité — et 20 M€ / 4 % pour les manquements aux principes, aux droits des personnes et aux transferts.)*

**Sanctions pénales complémentaires :** le fait de procéder à des traitements de DCP **sans respecter les formalités préalables** prévues par la loi est puni de **5 ans d'emprisonnement et 300 000 € d'amende**.

**Sanction civile — l'objet illicite (arrêt à connaître) :**
> **Principe :** un fichier de DCP **non déclaré** (à l'époque) à la CNIL constitue un **objet ILLICITE**. Le Code civil prévoit qu'**il n'y a que les choses qui sont dans le commerce qui puissent être l'objet de convention**.
> **Solution :** la vente d'un fichier de prospects non déclaré a un **objet illicite** → la vente est **NULLE**. La cour d'appel qui avait jugé que « la loi n'a pas prévu que l'absence de déclaration soit sanctionnée par la nullité » a été **cassée**.
> **Suite :** cassation → l'affaire est **rejugée par une seconde cour d'appel**, la Cour de cassation ne jugeant que le droit.

## 4.10 Cas transversal : le dispositif de « ligne éthique » (whistleblowing)

Ce cas long combine **toutes** les notions. Voilà le corrigé en 4 blocs.

**Contexte :** hot-line (numéro vert + adresse électronique) permettant à 1 500 employés d'alerter les dirigeants sur des irrégularités comptables ou des violations des règles éthiques. **Anonymat possible.** Alertes classées en 4 catégories (RH, fraude/vol, erreur comptable, éthique), résumé transmis par mail crypté, enquête interne, information du salarié visé, **conservation 1 an**. Inspiré de la loi américaine **Sarbanes-Oxley**.

| Question | Réponse |
|---|---|
| **1. Autorisation ou simple déclaration CNIL ?** | **Principe :** les traitements automatisés susceptibles, du fait de leur finalité, d'**exclure des personnes du bénéfice d'un droit, d'une prestation ou d'un contrat**, en l'absence de disposition législative encadrant ce type de traitement, ne peuvent être mis en œuvre qu'**après AUTORISATION de la CNIL**. **Au cas présent :** la CNIL considère que ce système **peut conduire l'employeur à licencier un salarié** → il relève d'une **AUTORISATION**, et non d'une simple déclaration. |
| **2. Conformité au RGPD ?** | **Principe :** un dispositif organisant le recueil de DCP sur des faits contraires aux règles de l'entreprise ou à la loi peut conduire à un **système de DÉLATION PROFESSIONNELLE**. **Au cas présent :** la **possibilité de dénonciation ANONYME** renforce le **risque de calomnie** → non conforme en l'état (la CNIL recommande de ne pas encourager l'anonymat et de traiter les alertes anonymes avec des précautions particulières). |
| **3. Position du RGPD sur la gestion des données ?** | **Principe :** il existe d'autres moyens de garantir le respect des dispositions légales (**sensibilisation par l'information et la formation** du personnel, **audit financier**, saisine de l'**inspection du travail** ou du **juge**). **Au cas présent :** il est fait référence au respect du **principe de PROPORTIONNALITÉ** — le dispositif doit être le moyen le moins intrusif pour atteindre l'objectif. |
| **4. Position sur les DCP dans ce dispositif ?** | **Principe :** pour être licite, un traitement ne peut porter que sur des données **collectées et traitées de manière loyale et licite**. **Au cas présent :** ① les salariés signalés **ne sont pas informés dès l'enregistrement** des données et **n'ont pas les moyens de s'opposer** au traitement → les modalités de collecte **ne peuvent être considérées comme loyales** (pas de consentement obtenu) ; ② la **durée de conservation d'un an** apparaît **disproportionnée** au regard de la finalité. |

## 4.11 La vidéosurveillance — arbre de décision complet

Le régime est **complexe** parce que **deux régimes juridiques se concurrencent** : la loi « Informatique et Libertés »/RGPD d'une part, et l'article 10 de la loi du 21 janvier 1995 d'orientation et de programmation pour la sécurité (autorisation préfectorale) d'autre part.

```
Où le dispositif est-il installé ?

├── LIEU PUBLIC (ou ouvert au public)
│   = tout lieu, du secteur public OU privé, où LE PUBLIC PEUT ACCÉDER
│     (guichet d'une mairie, supermarché, gare, rue, hall d'accueil)
│        → AUTORISATION PRÉFECTORALE nécessaire
│          (notamment quand aucune image n'est enregistrée ni conservée
│           dans des fichiers identifiant des personnes physiques — ex. caméra
│           de circulation)
│
├── LIEU PRIVÉ (ou non ouvert au public)
│   = tout lieu, du secteur public OU privé, où LE PUBLIC NE PEUT PAS ACCÉDER
│     (chaîne de montage, parking réservé au personnel, entrepôt, bureaux fermés)
│        → Formalité RGPD/CNIL (registre ; à l'époque : DÉCLARATION à la CNIL),
│          quand les images sont enregistrées ou conservées dans des fichiers
│          identifiant des personnes physiques
│
└── LIEU MIXTE (lieu ouvert au public comportant des zones privées :
    un supermarché avec sa réserve et ses bureaux)
       → C'est là que le régime pose problème : cumul des deux régimes selon
         les zones ; si les images sont enregistrées dans un fichier ou traitées
         informatiquement → formalité CNIL en plus de l'autorisation préfectorale.
```

**Les 5 conséquences au regard du RGPD (à réciter, chacune vaut un point) :**

1. **Moyens informatiques** → si le dispositif fait appel à des moyens informatiques (caméra IP, stockage des images sur support numérique), il constitue un traitement de DCP → **formalité CNIL** (registre, et à l'époque déclaration).
2. **PROPORTIONNALITÉ** → la mise en œuvre d'un système de vidéosurveillance des employés doit s'effectuer de façon **adéquate, pertinente, non excessive et strictement nécessaire** par rapport à l'objectif poursuivi. *(Corollaire : on ne filme pas en continu un poste de travail individuel, ni les zones de pause, ni les toilettes, ni les locaux syndicaux.)*
3. **OBLIGATION D'INFORMATION** → **il ne peut y avoir de surveillance à l'insu des personnes** (salariés ou visiteurs). Elles sont informées par un **affichage visible** de : l'existence du dispositif, les **destinataires des images**, et les **modalités d'exercice du droit d'accès** aux enregistrements les concernant. *(+ information et consultation du CSE.)*
4. **HABILITATION** → les images ne doivent être visionnées que par les **seules personnes habilitées** dans le cadre de leurs fonctions (responsable, sécurité), qui sont **formées et sensibilisées** aux règles applicables.
5. **DURÉE DE CONSERVATION LIMITÉE** → quelques jours ; en cas d'incident, le visionnage s'effectue rapidement ; **la durée ne doit pas excéder 1 MOIS**.

---

# PARTIE 5 — LES LICENCES ET LES LOGICIELS

## 5.1 Ce qu'on achète vraiment

> **Une personne qui télécharge un logiciel N'ACHÈTE PAS ce logiciel : elle paie une LICENCE, c'est-à-dire l'AUTORISATION D'UTILISER le logiciel.** Celui-ci est accompagné d'un **contrat de licence**.

Rappel du régime (cf. 2.5) : le logiciel est protégé par le **droit d'auteur** ; sont protégés le **code source** et la **documentation**, voire l'**analyse fonctionnelle détaillée** ; le **code exécutable n'est pas protégé**.

## 5.2 La typologie des logiciels — table complète

Ne confonds jamais « libre », « open source » et « gratuit ». Le prof teste exactement ça.

| Type | Code source accessible ? | Gratuit ? | Peut-on modifier ? | Peut-on redistribuer ? | Exemples |
|---|---|---|---|---|---|
| **Logiciel LIBRE** | ✅ Oui | Pas nécessairement | ✅ Oui | ✅ Oui, **dans les mêmes conditions que l'original** | Mozilla Firefox, OpenOffice |
| **Logiciel OPEN SOURCE** | ✅ Oui | Pas nécessairement | ✅ Oui | ✅ Oui | Linux, WordPress |
| **Logiciel GRATUIT (freeware/gratuiciel)** | ❌ **Non** | ✅ Oui | ❌ Non | Selon licence | Adobe Reader |
| **Logiciel PROPRIÉTAIRE** | ❌ Non | ❌ Non | ❌ Non | ❌ Non | Windows, SAP, Oracle |
| **SHAREWARE (partagiciel / contribuciel)** | ❌ Non | Test gratuit puis contribution | ❌ Non | ❌ Non | — |

> **Phrases du cours à replacer :**
> - « **Un logiciel libre est forcément Open Source, mais pas forcément gratuit.** »
> - « Le mouvement du **logiciel libre est dit "social"**, tandis que l'**Open Source est plutôt en rapport avec une méthodologie de développement**. »
> - « Le **code source** est la version du logiciel **intelligible et compréhensible** ; le **code exécutable** apparaît sous forme de bits 0 et 1. »
> - Les licences Open Source relèvent de l'**Open Source Initiative** (opensource.org) ; une des licences de logiciel libre est la **GNU-GPL (GNU General Public License)** (gnu.org).

## 5.3 Les modes d'acceptation de la licence

| Licence | Mécanisme d'acceptation |
|---|---|
| **« Read and wrap »** (la plus répandue) | Les conditions sont **affichées sur l'emballage**. Dès que le consommateur les a **lues (read)** et qu'il a **déchiré l'emballage (wrap)**, il est **réputé accepter** les conditions d'utilisation |
| **« Click-wrap » / freeware** | L'utilisateur ne peut l'utiliser qu'après avoir **coché la case « j'accepte la licence »** |
| **Shareware** | L'utilisateur **teste gratuitement**, puis **verse une contribution** pour continuer (l'auteur fait confiance, ou le logiciel se bloque au-delà d'une période) |

## 5.4 Les licences Creative Commons

> **Définition :** la licence Creative Commons est une **autorisation par laquelle l'auteur permet à chacun d'utiliser GRATUITEMENT ses textes** (protégés par le droit d'auteur), **à condition de respecter certaines conditions**. Cette autorisation s'adosse à un document juridique : le **contrat de licence Creative Commons**.

**Points essentiels :**
- « Creative Commons » se traduit par **« Biens communs créatifs »**.
- **La licence CC ne met PAS l'œuvre dans le domaine public** : elle en **autorise gratuitement l'utilisation** à toute personne intéressée, l'auteur **conservant ses droits**.
- L'auteur pourrait se contenter d'indiquer sur son site qu'il autorise l'utilisation ; l'intérêt de la CC est qu'elle est **immédiatement identifiée par les internautes** (standardisation, sécurité juridique).

### Les 4 options

| Sigle | Option | Signification |
|---|---|---|
| **BY** | **Attribution** | **Obligatoire dans TOUTES les licences CC** : créditer l'œuvre de la manière demandée par l'auteur, **sans suggérer qu'il approuve l'utilisation** |
| **NC** | **Pas d'Utilisation Commerciale** | Reproduction, diffusion (et modification sauf ND) autorisées **pour tout usage autre que commercial** ; l'usage commercial requiert l'autorisation de l'auteur |
| **SA** | **Partage dans les Mêmes Conditions** (*Share Alike*) | Les **adaptations** doivent être diffusées **sous la même licence** ; publier une adaptation sous d'autres conditions requiert l'autorisation |
| **ND** | **Pas de Modification** (*No Derivatives*) | Seul **l'original** peut être reproduit et diffusé ; toute modification requiert l'autorisation |

### Les 6 combinaisons possibles (à savoir lister)

1. **CC BY** — Attribution
2. **CC BY-ND** — Attribution + Pas de Modification
3. **CC BY-SA** — Attribution + Partage dans les mêmes conditions
4. **CC BY-NC** — Attribution + Pas d'Utilisation Commerciale
5. **CC BY-NC-SA** — Attribution + Pas d'Utilisation Commerciale + Partage dans les mêmes conditions
6. **CC BY-NC-ND** — Attribution + Pas d'Utilisation Commerciale + Pas de Modification

*(Pourquoi 6 et pas plus ? Parce que **NC/ND** et **SA** sont incompatibles : si on interdit la modification (ND), l'obligation de partager les adaptations à l'identique (SA) n'a plus d'objet.)*

### ⚠️ Le piège Creative Commons : « libre de droits » ≠ « sans redevance »

> **Cas :** une société diffuse dans son magasin un programme musical d'œuvres présentées comme « libres de tous droits de diffusion » sous licence Creative Commons. La **SPRE** (société pour la perception de la rémunération équitable de la communication au public des phonogrammes du commerce) lui réclame le paiement de la **rémunération équitable**.
>
> **Principe :** l'exploitation commerciale d'une plateforme de mise à disposition de musique génère des bénéfices reversés aux artistes-interprètes. Ces derniers peuvent publier leurs titres en choisissant un type de licence CC, et les professionnels peuvent sélectionner un programme pour sonoriser leurs locaux.
>
> **Solution :** **une musique diffusée dans un magasin sous licence Creative Commons reste soumise à l'obligation de verser une RÉMUNÉRATION ÉQUITABLE, au sens de l'article L.214-1 du CPI.** Cette rémunération s'applique **dès lors qu'un phonogramme est publié à des fins de commerce**. La cour considère que la sonorisation du magasin s'adresse à un **nombre indéterminé de destinataires**, de sorte qu'est réalisée une **communication directe dans un lieu public**.
>
> **Qui s'est pourvu en cassation ?** Ayant été **débouté en appel** (condamné à payer 120 000 € à la SPRE), c'est **la société S** qui se pourvoit. *(Méthode : celui qui a perdu en appel est le demandeur au pourvoi.)*

## 5.5 ⭐ L'ÉPUISEMENT DU DROIT DE DISTRIBUTION (arrêt UsedSoft c/ Oracle, CJUE)

C'est un des points les plus « rentables » du chapitre.

> **La règle dite de l'ÉPUISEMENT DES DROITS :** lorsque le titulaire des droits d'auteur sur un logiciel **met une copie de celui-ci sur le marché**, il **PERD la possibilité d'invoquer son monopole d'exploitation pour s'opposer à la REVENTE de cette copie** par son acquéreur légitime.
> L'acquéreur a le droit de la revendre à un tiers, **sous réserve de cesser lui-même l'utilisation** du logiciel (pas de double usage).

**Le contexte historique :** la règle a été édictée par une **directive européenne** à une époque où les logiciels n'étaient distribués que sur **supports physiques** (CD-Rom, DVD-Rom). Aujourd'hui la distribution se fait principalement **par téléchargement**.

**L'argument d'Oracle :** un téléchargement n'est pas une « vente » au sens de la règle de l'épuisement, qui ne devrait donc pas s'appliquer.

> **La position de la CJUE (à écrire) :**
> **L'épuisement du droit de distribution concerne à la fois les copies MATÉRIELLES ET IMMATÉRIELLES d'un logiciel, y compris les copies téléchargées légalement par un acquéreur.**
> Ce dernier est **libre de revendre la licence à un tiers**, qui en devient le nouveau **« licencié légitime »**.
> **La CJUE prive de tout effet juridique la clause de la licence d'utilisation qui prévoit qu'une licence acquise est INCESSIBLE.**
>
> **Portée :** cette décision **consacre le droit, pour un utilisateur, de revendre ses licences** et **légalise le marché de l'occasion du logiciel**.

### Les 2 restrictions posées par la CJUE

1. **DURÉE ILLIMITÉE** : les licences doivent avoir été **concédées pour une durée illimitée** (une licence à durée déterminée, un abonnement SaaS, n'est pas « vendue » → pas d'épuisement).
2. **REVENTE EN BLOC** : lorsque les licences sont acquises **pour un certain nombre d'utilisateurs**, le **lot doit être revendu EN BLOC**, sans possibilité pour le titulaire de **conserver la quantité qui lui serait utile** (interdiction du « scindage »).

### La suite : l'affaire SAP (résolution complète)

**Les faits :** un éditeur (SAP) modifie ses conditions contractuelles pour entraver la revente de licences d'occasion. Une société allemande spécialisée dans la revente estime que ces modifications constituent une **pratique déloyale**. Deux dispositions posent problème :
- **l'indivisibilité** des licences achetées en volume ;
- les **compléments d'utilisation** (extension des droits soumise à l'autorisation de l'éditeur).

| Rubrique | Contenu |
|---|---|
| **Les faits** | Un éditeur de logiciel interdit à ses clients, **par des mesures contractuelles**, de revendre les licences acquises auprès de lui |
| **Le problème juridique** | Les mesures contractuelles imposées par un éditeur, interdisant à un acheteur de revendre le logiciel, sont-elles **juridiquement valables** ? |
| **La règle de droit** | **a) L'indivisibilité :** la CJUE **n'a PAS exclu** l'indivisibilité, dans la mesure où les programmes d'achat en volume répondent à une **logique économique propre** reposant sur un **équilibre** : un gros volume en échange d'un **traitement tarifaire favorable**. **b) Les compléments d'utilisation :** le vendeur du logiciel d'occasion **ne peut transférer à l'acheteur que les utilisations dont il SE PRIVE**. Si l'acheteur souhaite **étendre** ses droits, il doit en **acquérir l'autorisation** |
| **La solution** | Le titulaire initial **ne peut pas s'opposer à la revente** d'un logiciel pour lequel **son droit de distribution est épuisé** ; tout acquéreur ultérieur constitue un **acquéreur légitime**. En revanche, la question de savoir si l'autorisation peut ou non être acquise auprès de SAP revient **indirectement à contrôler la revente d'occasion** : c'est ce point qui pose problème |

## 5.6 ⭐ La violation d'une licence GNU-GPL (affaire Edu4 / AFPA)

Cas très riche, à connaître dans les 4 rubriques.

**Les faits :** l'**AFPA** lance un appel d'offres de plusieurs millions d'euros pour moderniser ses salles de formation. **Edu4** remporte le marché. Lors de la première phase, l'AFPA découvre qu'Edu4 utilise une **version modifiée du logiciel libre VNC** (prise de contrôle à distance des postes élèves). VNC étant distribué sous **GNU-GPL**, l'AFPA exige la communication des **codes sources**. Edu4 **refuse** pour protéger son savoir-faire. En cours de procédure, Edu4 fournit des codes sources **ne correspondant pas à la version compilée** livrée, et surtout **a modifié les notices de droit d'auteur** pour se prétendre auteur de VNC et **supprimé le texte de la licence GPL**.

| Rubrique | Contenu |
|---|---|
| **Le problème juridique** | Comment l'**utilisateur** d'un logiciel libre peut-il faire respecter les termes de la licence GNU-GPL ? |
| **La règle de droit** | L'utilisateur d'un logiciel libre est **en droit d'exiger le respect des obligations posées par la licence**, en particulier la **communication du code source modifié**. **⭐ L'auteur du logiciel libre n'est PAS le seul à pouvoir faire respecter les termes de la licence.** Le droit reconnaît la **validité juridique** d'une licence GNU-GPL ; par conséquent, la livraison d'une solution qui **ne respecte pas** ce type de licence **équivaut à une LIVRAISON NON CONFORME**, parce qu'elle **expose le client à une action en contrefaçon** |
| **La solution** | Il ne s'agit pas d'un procès entre **l'auteur** d'un logiciel libre et une entreprise qui l'utilise, mais entre **une entreprise qui utilise un logiciel libre et son CLIENT**. La licence GNU-GPL est **juridiquement valable**. Livrer une solution qui ne la respecte pas équivaut à une **livraison non conforme**, engendrant l'application de la **GARANTIE D'ÉVICTION : le vendeur d'une chose doit en garantir la JOUISSANCE PAISIBLE à l'acheteur.** La conformité s'apprécie **à la date de la livraison** — Edu4 ne peut donc pas prétendre qu'il ne s'agissait que d'une « version préparatoire » |
| **Conséquence procédurale** | La cour d'appel **INFIRME** le jugement de première instance (qui avait débouté l'AFPA et l'avait condamnée à payer 1 M€ à Edu4) |

**Les 3 obligations clés de la GNU-GPL (à retenir) :**
1. Fournir ou rendre disponible le **code source** de la version modifiée ;
2. **Conserver les mentions de copyright** et le **texte de la licence** ;
3. Redistribuer sous la **même licence** (effet « copyleft » / viral).

## 5.7 Récapitulatif des sanctions du chapitre

| Fait | Qualification | Tribunal |
|---|---|---|
| Copier le code source d'un concurrent | **Contrefaçon** (droit d'auteur) | TJ (civil) ou correctionnel (pénal) |
| Extraire massivement une base de données | Atteinte au **droit sui generis** — 3 ans + 300 000 € | TJ / correctionnel |
| Livrer un logiciel violant une licence GPL | **Inexécution contractuelle** / livraison non conforme + garantie d'éviction | TC |
| Revendre une licence malgré une clause d'incessibilité | **Aucune faute** : la clause est privée d'effet par la CJUE | — |
| Diffuser de la musique CC dans un magasin sans payer la SPRE | Manquement à la **rémunération équitable** (L.214-1 CPI) | TJ / TC |

---

# PARTIE 6 — LE DROIT DES CONTRATS

## 6.0 La logique du chapitre

Tout, en droit privé, tourne autour du contrat. Un achat de logiciel, une licence, un abonnement téléphonique, une commande de site web, une vente en ligne : ce sont tous des contrats.

La grille de raisonnement est **toujours la même** :

```
1. Y a-t-il un CONTRAT ? (offre + acceptation = échange des consentements)
2. Est-il VALABLE ? (consentement / capacité / contenu)
   → Si non : NULLITÉ (relative ou absolue), effet RÉTROACTIF
3. Comment le CLASSER ? (synallagmatique, onéreux, successif, adhésion…)
4. A-t-il été EXÉCUTÉ ? Sinon → RESPONSABILITÉ + sanctions
5. Y a-t-il des règles SPÉCIALES ? (e-commerce, consommation, clauses abusives)
```

## 6.1 La notion de contrat

> **Le contrat est une convention par laquelle une ou plusieurs personnes s'obligent envers une ou plusieurs autres, à DONNER, à FAIRE ou à NE PAS FAIRE quelque chose.**
> **Le contrat est source d'OBLIGATIONS.**
> **Une OBLIGATION est le lien juridique en vertu duquel un DÉBITEUR est engagé envers son CRÉANCIER.**

**La force obligatoire (art. 1103 et 1104 C. civ., ex-1134) :**
- Les cocontractants **exécutent les obligations** pour lesquelles ils se sont engagés.
- **SEULES LES PARTIES** peuvent modifier ou mettre fin au contrat, et **par consentement mutuel** (mutuus dissensus) ou pour les causes que la loi autorise.
- Le contrat doit être **exécuté DE BONNE FOI** : les cocontractants exécutent fidèlement leurs engagements, **ne nuisent pas** à l'autre partie et **ne rendent pas difficile** l'exécution de son obligation.

> *Art. 1134 ancien (souvent cité dans les sujets) : « Les conventions légalement formées tiennent lieu de loi à ceux qui les ont faites. Elles ne peuvent être révoquées que par leur consentement mutuel, ou pour les causes que la loi autorise. Elles doivent être exécutées de bonne foi. »*

## 6.2 La formation du contrat : offre et acceptation

> **Le contrat se forme par l'ÉCHANGE DES CONSENTEMENTS, c'est-à-dire par l'ACCEPTATION DE L'OFFRE.** À partir de ce moment, la **force obligatoire** s'applique.
> **En matière de VENTE, l'accord des volontés entraîne le TRANSFERT DE PROPRIÉTÉ** (effet translatif immédiat, dès l'accord sur la chose et le prix).

**L'offre assortie d'un DÉLAI :** l'offrant est **tenu de la maintenir** pendant le délai annoncé. S'il la rétracte avant l'expiration, la rétractation est **inefficace** ; si le destinataire accepte dans le délai, **le contrat est formé**.

> **Cas type (Laurent Outan) :** offre de vente d'un appartement le **15 janvier**, valable **2 mois**. Acceptation par LRAR **un mois plus tard (mi-février)**. Rétractation du vendeur **début mars**.
> **Solution :** l'acceptation est intervenue **dans le délai** → le contrat est formé **mi-février** → les voisins sont **devenus propriétaires** dès cet instant → **M. Outan ne peut pas refuser de vendre ni de livrer**. Son motif personnel (rupture avec sa fiancée) est juridiquement **indifférent**.
>
> **Variantes que le prof peut poser :**
> - Acceptation **après** le délai de 2 mois → ce n'est plus une acceptation mais une **nouvelle offre**, que le vendeur est libre de refuser.
> - Acceptation **assortie de modifications** (prix différent) → **contre-offre**, pas d'accord.
> - Offre **sans délai** → maintien pendant un **délai raisonnable**.
> - Décès de l'offrant avant acceptation → l'offre devient **caduque**.

## 6.3 La classification des contrats — table complète

| Critère | Type | Définition | Exemple |
|---|---|---|---|
| **Selon les effets** | **Synallagmatique** | Les parties s'obligent **réciproquement** les unes envers les autres | Contrat de **vente**, contrat de travail, contrat de prestation informatique |
| | **Unilatéral** | Le contrat ne crée d'obligations **qu'à la charge d'une seule** partie | **Donation** |
| | **À titre onéreux** | Chacune des parties est assujettie à **donner ou à faire** quelque chose | Contrat de vente |
| | **À titre gratuit** | Le contractant s'engage **sans contrepartie** | Donation |
| **Selon la durée** | **À exécution instantanée** | L'exécution des obligations se fait **en une seule fois** | Contrat de vente |
| | **À exécution successive** | L'exécution **s'échelonne dans le temps** | **Contrat de travail**, bail, abonnement, maintenance |
| **Selon la qualité des parties** | **De gré à gré** | Les parties **discutent et négocient** les conditions | Contrat de vente négocié |
| | **D'adhésion** | Une des parties **impose** à l'autre les conditions | **Téléphonie mobile**, CGU/CGV, contrat de travail |

**Pourquoi ça compte :**
- **Synallagmatique** → possibilité d'invoquer l'**exception d'inexécution** (« je n'exécute pas tant que tu n'exécutes pas ») et la **résolution** pour inexécution.
- **À exécution successive** → l'anéantissement n'est **PAS rétroactif** : on parle de **RÉSILIATION** (pour l'avenir), pas de résolution.
- **D'adhésion** → contrôle des **clauses abusives**, interprétation **contre celui qui a rédigé**.

## 6.4 ⭐ LES CONDITIONS DE VALIDITÉ DU CONTRAT

Trois conditions cumulatives : **CONSENTEMENT / CAPACITÉ / CONTENU**.

### 6.4.1 Le consentement

> Le consentement doit être **RÉEL, LIBRE et ÉCLAIRÉ**.
> Il n'y a **point de consentement** si celui-ci a été donné par **ERREUR**, extorqué par **VIOLENCE**, ou surpris par **DOL**.
> **Ces vices du consentement entraînent la NULLITÉ (relative) du contrat.**

### ⭐ L'arbre de décision des 3 vices du consentement (toutes les valeurs possibles)

```
Le consentement a-t-il été altéré ? Comment ?

├── PAR UNE CROYANCE FAUSSE SPONTANÉE (personne n'a menti, le contractant
│   s'est trompé tout seul)
│        → ERREUR
│        Définition : idée fausse que se fait l'un des cocontractants.
│        Pour être un vice, elle doit porter sur :
│          • LES QUALITÉS ESSENTIELLES DE LA CHOSE objet du contrat
│            (ex. acheter un tableau que l'on croit d'un maître ;
│             acheter un logiciel que l'on croit compatible)
│          • LA PERSONNE DU COCONTRACTANT, dans les contrats conclus
│            INTUITU PERSONAE (en considération de la personne)
│        ⚠️ N'est PAS une cause de nullité :
│          • l'erreur sur la VALEUR (avoir fait une mauvaise affaire)
│          • l'erreur sur les MOTIFS (les raisons personnelles de contracter)
│          • l'erreur INEXCUSABLE (un professionnel qui aurait dû savoir)
│
├── PAR UNE CONTRAINTE / UNE MENACE
│        → VIOLENCE
│        Elle peut être PHYSIQUE, MORALE ou ÉCONOMIQUE.
│        Elle doit provoquer une CRAINTE pour soi-même, ses proches ou ses biens.
│        La personne doit avoir perçu la menace d'un MAL CONSIDÉRABLE ET ACTUEL.
│        ⚠️ La menace d'exercer une VOIE DE DROIT légitime (« je vous assigne »)
│           n'est PAS une violence, sauf détournement ou avantage excessif.
│        ⚠️ ABUS DE DÉPENDANCE : abuser de l'état de dépendance d'un
│           cocontractant pour en tirer un avantage manifestement excessif.
│
└── PAR UNE TROMPERIE DE L'AUTRE PARTIE
         → DOL
         Définition : MANŒUVRES FRAUDULEUSES qui ÉMANENT D'UN DES
         COCONTRACTANTS et qui sont destinées à TROMPER L'AUTRE afin qu'il s'engage.
         C'est un COMPORTEMENT MALHONNÊTE, par le biais de :
           • TROMPERIES (mise en scène, faux documents)
           • MENSONGES (affirmation contraire à la vérité)
           • RÉTICENCES = LE SILENCE  ← « RÉTICENCE DOLOSIVE »
             (dissimulation intentionnelle d'une information dont on sait
              le caractère déterminant pour l'autre partie)
         Deux éléments doivent être réunis :
           ① élément INTENTIONNEL : l'intention de tromper doit exister
           ② élément MATÉRIEL : les manœuvres doivent avoir été DÉTERMINANTES
              dans la conclusion du contrat
         ⚠️ Le dol émanant d'un TIERS n'est pas une cause de nullité
            (sauf complicité du cocontractant).
```

**Un exemple par vice :**

| Vice | Cas du cours | Solution |
|---|---|---|
| **Dol (réticence dolosive)** | Jean-Eudes achète une voiture d'occasion 5 000 € ; le vendeur **ne l'informe pas** qu'elle a subi un **grave accident** | **Réticence dolosive** → nullité de la vente. Effet : Jean-Eudes **restitue la voiture**, le vendeur **rend le prix** |
| **Dol (manœuvre)** | Un prestataire fait **signer un PV de livraison** alors que **seules les maquettes** du site ont été fournies, puis facture immédiatement les loyers | **Action dolosive** caractérisée → résiliation/résolution du contrat, et le contrat de location est déclaré **caduc** car le PV, déclencheur du paiement des loyers, ne pouvait être pris en compte |
| **Erreur** | Acheter un logiciel présenté comme compatible avec son SI alors qu'il ne l'est pas | Erreur sur les **qualités essentielles** → nullité |
| **Violence économique** | Un fournisseur en position dominante impose une renégociation en menaçant de couper l'approvisionnement vital | Violence économique / abus de dépendance → nullité |

### 6.4.2 La capacité

> **La capacité est l'aptitude à être titulaire de droits et à les exercer.**
> **Sont privés de la capacité :** les **MINEURS non émancipés** et les **MAJEURS PROTÉGÉS** (tutelle, curatelle, sauvegarde de justice).

**Règle :** les mineurs non émancipés ne peuvent contracter que **par l'intermédiaire de leur représentant légal**, **SAUF pour les ACTES DE LA VIE COURANTE** (achats usuels de faible valeur, conclus à des conditions normales).

> **Cas type :** Jean-Eudes, **15 ans**, achète un ordinateur à **750 €**.
> **Principe :** pour produire les effets voulus, le contrat doit respecter la capacité des parties. Les mineurs non émancipés ne peuvent contracter que par leur représentant légal, sauf actes de la vie courante.
> **Au cas présent :** un ordinateur à 750 € n'est **pas un acte de la vie courante** pour un mineur → le contrat encourt une **NULLITÉ RELATIVE**. Il pourrait être **annulé par les parents**. **Conseil à M. V :** inciter les parents à **CONFIRMER l'achat** (la confirmation valide rétroactivement l'acte).
>
> **Variantes :** si le mineur achetait un stylo à 3 € → **acte de la vie courante**, contrat **valable**. Si le mineur était **émancipé** (16 ans, par décision du juge) → **pleine capacité**, contrat valable. Si l'acheteur était sous **tutelle** → même raisonnement, nullité relative demandée par le tuteur.

### 6.4.3 Le contenu

> **Le contenu est l'ensemble des OBLIGATIONS CONTRACTUELLES consenties et explicitées par les parties.** Il comprend les **engagements** sur lesquels l'accord s'est fait, qui peuvent être **exprès ou tacites**, et qui résultent des **documents contractuels, y compris les conditions générales, ainsi que des engagements verbaux.**

Le contenu doit être **possible, déterminé ou déterminable et LICITE**, non contraire à l'**ordre public** et aux **bonnes mœurs**.

> **⭐ Application majeure : l'objet illicite.** Une chose **hors du commerce** ne peut pas faire l'objet d'une convention.
> - Un **fichier de DCP non déclaré** à la CNIL n'était pas « dans le commerce » → sa vente a un **objet illicite** → **nullité** (cf. 4.9).
> - **Le CORPS HUMAIN et ses éléments sont HORS DU COMMERCE** : ils sont **indisponibles** ; les conventions les concernant sont frappées de **nullité ABSOLUE** (ordre public de protection de la personne). Cf. le cas du tatouage, traité en 6.11.

## 6.5 La nullité du contrat

> **La sanction du non-respect des conditions de validité est la NULLITÉ du contrat.**

| | **NULLITÉ RELATIVE** | **NULLITÉ ABSOLUE** |
|---|---|---|
| **Objectif** | Protection d'**INTÉRÊTS PARTICULIERS** | Protection de l'**INTÉRÊT GÉNÉRAL** |
| **Qui peut agir ?** | **Seule la personne que la loi protège** (ou son représentant) | **Toute personne justifiant d'un intérêt légitime** (cocontractant **ou tiers**), + le ministère public |
| **Cas d'ouverture** | Vices du consentement (erreur, dol, violence), **incapacité** | **Objet ou but ILLICITE**, atteinte à l'**ordre public** ou aux **bonnes mœurs**, absence totale de consentement, indisponibilité du corps humain |
| **Confirmation possible ?** | ✅ **Oui** (la personne protégée peut renoncer à agir) | ❌ **Non** (on ne peut pas confirmer un acte illicite) |
| **Prescription** | 5 ans | 5 ans |

**Les effets de la nullité :**
- **EFFET RÉTROACTIF** : les choses sont **remises en leur état antérieur**, **comme si le contrat n'avait jamais existé** → **restitutions réciproques**.
- ⚠️ **EXCEPTION : dans les contrats à EXÉCUTION SUCCESSIVE, l'annulation N'EST PAS RÉTROACTIVE** — on parle alors de **RÉSILIATION** (elle ne vaut que pour l'avenir), car on ne peut pas restituer du temps de travail ou de la jouissance déjà consommée.

**Vocabulaire à ne pas confondre (piège fréquent) :**

| Terme | Cause | Effet dans le temps |
|---|---|---|
| **Nullité** | Défaut de **formation** (condition de validité manquante) | Rétroactif |
| **Résolution** | **Inexécution** d'un contrat à exécution instantanée | Rétroactif |
| **Résiliation** | **Inexécution** d'un contrat à exécution successive, ou anéantissement pour l'avenir | Non rétroactif |
| **Caducité** | Disparition d'un **élément essentiel** après la formation (ex. le contrat principal disparaît → le contrat de location accessoire devient caduc) | Pour l'avenir (avec restitutions) |
| **Clause réputée non écrite** | Clause **abusive** ou **léonine** | Le contrat **survit** sans la clause |

## 6.6 ⭐ LES RESPONSABILITÉS

### Les trois responsabilités du cours

| Type | Origine | Conditions |
|---|---|---|
| **Responsabilité CIVILE** (le cadre général) | — | ① un **FAIT GÉNÉRATEUR** : inexécution, ou exécution **tardive** ou **défectueuse** ② un **DOMMAGE** : seuls sont réparables les dommages **prévus au contrat** ③ un **LIEN DE CAUSALITÉ** : relation **directe** entre le dommage et l'inexécution |
| **Responsabilité CONTRACTUELLE** | Naît de l'**inexécution d'une obligation liée au CONTRAT** | Elle entraîne l'**exécution forcée** lorsque c'est possible, ou une **compensation** (DI) |
| **Responsabilité DÉLICTUELLE** | Naît du dommage causé à un **TIERS** (hors contrat) | Par un **DÉLIT** (fait dommageable **intentionnel**) ou un **QUASI-DÉLIT** (fait dommageable **non intentionnel**, la négligence, l'imprudence) |

> **Les 3 conditions à réciter systématiquement : FAUTE (ou fait générateur) + DOMMAGE (préjudice) + LIEN DE CAUSALITÉ.** Écris toujours les trois, même brièvement.

### ⭐ Obligation de MOYEN vs obligation de RÉSULTAT

C'est la distinction la plus rentable du chapitre, car elle **détermine qui doit prouver quoi**.

| | **OBLIGATION DE MOYEN** | **OBLIGATION DE RÉSULTAT** |
|---|---|---|
| **Définition** | Le débiteur **s'engage à mettre tous les moyens dont il dispose** pour exécuter le contrat ; il promet d'**accomplir toutes les diligences nécessaires** à la réalisation de son obligation | Le débiteur **s'engage à ATTEINDRE UN RÉSULTAT DÉTERMINÉ** |
| **Charge de la preuve** | Le **CRÉANCIER** doit prouver que le débiteur **n'a pas fait diligence** (a été négligent) | Le **résultat non atteint SUFFIT** à engager la responsabilité ; le débiteur ne s'exonère que par la **force majeure** |
| **Critère** | Le créancier a un **rôle ACTIF** / il existe un **aléa** | Le créancier est **PASSIF** / pas d'aléa |
| **Exemples** | Médecin (soigner) ; **opérateur de téléphonie** (Code des postes et communications électroniques) ; **obligation d'information, de mise en garde et de conseil du concepteur de logiciel** ; avocat (plaider) | **Obligation de DÉLIVRANCE** du concepteur de logiciel ; **obligation de sécurité de l'organisateur de saut à l'élastique** ; transporteur (amener à bon port) ; vendeur (livrer la chose) |

> **⭐ Le critère du « rôle actif » (arrêt saut à l'élastique — Cass. 1re civ.) :**
> **Principe :** l'obligation de sécurité constitue une **obligation de RÉSULTAT** dès lors que **le client NE JOUE PAS DE RÔLE ACTIF** dans la mise en œuvre de l'activité et qu'il **s'en remet à l'organisateur** pour assurer sa sécurité.
> **Motivation :** le participant **ne contribue pas à sa sécurité par son comportement** ; la seule initiative qu'il peut avoir réside dans la **décision de sauter ou non** et dans la **force de l'impulsion donnée** ; il **ne dispose d'aucun moyen de se prémunir lui-même du danger** ; **aucun élément ne permet de considérer qu'il joue un rôle actif** au cours du saut.
> **Solution :** le moyen n'est pas fondé → **REJET du pourvoi**, la décision d'appel est confirmée. **L'affaire est terminée.**
>
> **Comment transposer aux TIC :** l'hébergeur qui garantit une disponibilité de 99,9 % avec pénalités → **résultat**. Le consultant qui doit « accompagner la transformation » → **moyen**. Le prestataire qui doit **livrer** un site fonctionnel → **résultat** sur la délivrance, **moyen** sur le conseil.

### La réparation : ce qui est indemnisable

**Articles clés (à citer) :**
- **Art. 1231 C. civ.** : à moins que l'inexécution soit définitive, les DI ne sont dus que si le débiteur a préalablement été **MIS EN DEMEURE** de s'exécuter dans un délai raisonnable.
- **Art. 1231-2 C. civ.** : les DI dus au créancier sont, en général, de **la PERTE qu'il a faite** (*damnum emergens*) et du **GAIN dont il a été privé** (*lucrum cessans*).
- **Art. 1231-3 C. civ.** : **le débiteur n'est tenu que des dommages et intérêts qui ont été PRÉVUS OU QUI POUVAIENT ÊTRE PRÉVUS LORS DE LA CONCLUSION DU CONTRAT**, sauf lorsque l'inexécution est due à une **faute lourde ou dolosive**.
- **Art. 1231-4 C. civ.** : les DI ne comprennent que ce qui est une **suite IMMÉDIATE ET DIRECTE** de l'inexécution.

> **⭐ Le raisonnement « prévisibilité du dommage » (cas SNCF, le classique absolu) :**
>
> **Faits :** M. M réserve un TGV Nantes–Paris et un vol Roissy–Pékin. Le TGV arrive avec **7 heures de retard** ; il rate son avion. Il demande : le prix des **billets de train**, le prix des **billets d'avion**, les **frais d'hôtel à Pékin**.
>
> **Principe :** le débiteur n'est tenu que des DI **prévus ou prévisibles lors de la conclusion du contrat**, sauf faute lourde ou dolosive ; et seulement du dommage qui est une **suite immédiate et directe** de l'inexécution.
>
> **Au cas présent :** en achetant un billet de train, la SNCF **ne pouvait pas prévoir** que le voyageur avait un avion à prendre, ni qu'il avait réservé un hôtel à Pékin. **Seul le prix du billet de train, rendu inutile par le retard, était prévisible.**
> → **La SNCF n'indemnise QUE le prix des billets de train**, à l'exclusion du billet d'avion et des frais d'hôtel.
>
> **Dans l'arrêt cité (l'avocat de Limoges) :** le tribunal avait accordé, en plus du prix du voyage, 500 € de perte d'honoraires, 1 000 € de perte de crédibilité et 500 € pour « l'inquiétude et l'énervement ». La Cour de cassation **CASSE** : ces motifs sont **impropres à établir que le dommage était prévisible** lors de la conclusion du contrat de transport → le tribunal a **privé sa décision de base légale**.
>
> **Variantes du prof :** si le voyageur avait **informé la SNCF** de sa correspondance (billet combiné, réservation unique), le dommage devenait **prévisible** → indemnisation élargie. Si la SNCF avait commis une **faute lourde ou dolosive**, le plafond de prévisibilité **saute**.

### La charge de la preuve

> **Principe (art. 1353 C. civ.) :** **la charge de la preuve incombe au DEMANDEUR**, c'est-à-dire à **celui qui réclame l'exécution d'une obligation**. Réciproquement, **celui qui se prétend libéré de son obligation doit le prouver**.

> **Cas type (société F / société C, câblage informatique) :** F réclame le paiement du solde de son marché. **C'est donc à F de prouver** le contenu du contrat, le **respect de l'exécution de ses obligations** (achèvement des travaux conformément aux prévisions contractuelles) et l'absence de règlement. La cour d'appel qui a exigé de **C** qu'elle démontre l'inachèvement a **INVERSÉ LA CHARGE DE LA PREUVE** → **cassation avec renvoi**.
>
> **L'objet de la preuve** consiste dans la démonstration de l'existence d'un **acte** ou d'un **fait juridique**. Ici : le contrat (acte juridique) est la source des obligations ; l'achèvement des travaux et l'absence de règlement sont des **faits juridiques**.

### La garantie des VICES CACHÉS

> **Art. 1641 C. civ. :** « Le vendeur est tenu de la garantie à raison des **défauts cachés** de la chose vendue qui la rendent **impropre à l'usage auquel on la destine**, ou qui **diminuent tellement cet usage** que l'acheteur ne l'aurait pas acquise, ou n'en aurait donné qu'un moindre prix, s'il les avait connus. »

**Les 3 conditions cumulatives :**
1. Le vice doit être **INHÉRENT À LA CHOSE** : il doit la rendre **impropre à l'usage auquel on la destine**.
2. Le vice doit être **CACHÉ** : non décelable par l'acquéreur au moment de la vente — sachant que **l'acquéreur profane n'est tenu que d'un examen élémentaire** de la chose (l'acheteur professionnel, lui, est tenu à un examen approfondi).
3. Le vice doit être **ANTÉRIEUR À LA VENTE** : il existe avant le transfert de propriété, **même s'il ne se manifeste que postérieurement**.

**Les 3 effets (les actions offertes à l'acheteur) :**
1. **Action RÉDHIBITOIRE** → **restitution intégrale du prix** contre restitution de la chose (anéantissement de la vente) ;
2. **Action ESTIMATOIRE** → **réduction du prix**, l'acheteur garde la chose ;
3. **Demande de DOMMAGES-INTÉRÊTS** au titre du préjudice subi (si le vendeur était de mauvaise foi ou professionnel).

**Distinction à connaître :** garantie des **vices cachés** (défaut rendant impropre à l'usage) ≠ **garantie de conformité** (la chose ne correspond pas à ce qui était convenu) ≠ **erreur** (vice du consentement, à la formation) ≠ **dol** (tromperie).

### La responsabilité du fait des PRODUITS DÉFECTUEUX

**Textes cités dans les sujets :**
- **Art. 1386-6 (auj. 1245-5) C. civ. :** « Est **PRODUCTEUR**, lorsqu'il agit à titre professionnel, le **fabricant d'un produit fini**, le **producteur d'une matière première**, le **fabricant d'une partie composante**. »
- **Art. 1386-7 (auj. 1245-6) C. civ. :** « **Si le producteur ne peut être identifié**, le **vendeur**, le loueur ou tout autre **fournisseur professionnel** est responsable du défaut de sécurité du produit, **dans les mêmes conditions que le producteur**, à moins qu'il ne désigne son propre fournisseur ou le producteur dans un délai de **3 mois** à compter de la notification de la demande de la victime. »

> **Principe :** le **producteur** est responsable du dommage causé par un défaut de son produit, **qu'il soit ou non lié par un contrat avec la victime**.

**Les deux fondements possibles pour la victime — arbre de décision :**

```
La victime a-t-elle un CONTRAT avec la personne qu'elle attaque ?

├── OUI → RESPONSABILITÉ CONTRACTUELLE
│      Le vendeur est soumis à une OBLIGATION DE SÉCURITÉ.
│      La victime doit prouver : une FAUTE (le manquement à l'obligation de
│      sécurité) + un DOMMAGE + un LIEN DE CAUSALITÉ.
│
└── NON → RESPONSABILITÉ DÉLICTUELLE / DU FAIT DES PRODUITS DÉFECTUEUX
       La victime doit prouver : un FAIT GÉNÉRATEUR (mise en circulation du
       produit défectueux) + le DÉFAUT du produit + le DOMMAGE + le LIEN DE
       CAUSALITÉ. Elle agit contre LE PRODUCTEUR.
       ⚠️ Si le producteur NE PEUT PAS ÊTRE IDENTIFIÉ, elle peut engager
          la responsabilité du VENDEUR.
```

> **Cas type (article NX 22, court-circuit et mini-incendie) :**
> **Au cas présent :** la société de vente en ligne **n'est PAS le producteur**. Le client **ne peut donc pas** engager sa responsabilité sur le fondement de la responsabilité **du fait des produits défectueux** (sauf si le producteur ne peut être identifié). **En revanche, il PEUT engager sa responsabilité sur le fondement de la RESPONSABILITÉ CONTRACTUELLE**, le vendeur étant tenu d'une obligation de sécurité.

## 6.7 ⭐ LE COMMERCE ÉLECTRONIQUE

> **Définition :** le commerce électronique est l'**activité économique par laquelle une personne propose, PAR VOIE ÉLECTRONIQUE, la fourniture de BIENS OU DE SERVICES.**

### Le processus de formation du contrat électronique : LE DOUBLE CLIC

> **Pour être valable, un contrat électronique obéit à un processus spécifique en 3 temps :**
> 1. **Le client VÉRIFIE sa commande** (récapitulatif, correction des erreurs) → **1er clic**
> 2. **Le client CONFIRME sa commande** → **2e clic** (« double clic »)
> 3. **Le cybermarchand ACCUSE RÉCEPTION de la commande, par voie électronique**

**⚠️ Les trois étapes doivent être présentes.** Un processus où le client saisit ses coordonnées puis valide directement, et où le vendeur envoie seulement un mail indiquant la **date de livraison**, est **ILLÉGAL** : le client **ne peut pas vérifier sa commande** et il n'y a **pas d'accusé de réception**. → Réponse : « Il est nécessaire de compléter le processus pour que sa validité ne puisse être contestée. »

### Le droit de rétractation

> **Le consommateur dispose d'un délai de RÉTRACTATION de 14 JOURS à compter de la RÉCEPTION du bien** (ou de la conclusion du contrat pour les services).

**Piège systématique :** les CGV du sujet prévoient **7 jours à compter de la livraison** (ancien droit) → **c'est illégal**. Réponse : « Le délai doit être **porté à 14 jours**. »

**Applications :**
- Article livré **il y a 3 jours** → le délai de 14 jours **n'est pas dépassé** → **le consommateur PEUT se rétracter**, sans avoir à motiver.
- Article livré il y a **20 jours** → délai expiré → rétractation impossible (sauf défaut d'information sur le droit de rétractation, qui **prolonge le délai de 12 mois**).

**Exceptions au droit de rétractation** (à citer si le sujet le suggère) : biens confectionnés sur mesure ou personnalisés, biens périssables, **contenus numériques fournis sur support immatériel dont l'exécution a commencé avec l'accord exprès du consommateur**, enregistrements audio/vidéo ou logiciels **descellés** par le consommateur, prestations d'hébergement/transport/loisirs à date déterminée.

### Les informations obligatoires

Le vendeur doit afficher : le **prix**, les **frais de livraison**, la **date limite de livraison**, la **disponibilité du produit**.
*(+ identité et coordonnées du vendeur, caractéristiques essentielles du bien, modalités de paiement, existence et modalités du droit de rétractation, garanties légales.)*

### La fraude au paiement

> **Le contrat est ANNULÉ en cas de paiement après USURPATION DES COORDONNÉES BANCAIRES.** Le titulaire de la carte est **recrédité** ; la charge de la fraude pèse sur le commerçant/la banque, sauf négligence grave du client.

## 6.8 ⭐ LE CADRE JURIDIQUE DES PRATIQUES COMMERCIALES

> **La notion de PRATIQUE COMMERCIALE englobe tous les procédés liés au commerce, c'est-à-dire toute forme d'acte en relation directe avec la PROMOTION, la VENTE ou la FOURNITURE d'un bien ou d'un service au consommateur.**

### 6.8.1 La concurrence déloyale

> **Définition :** la concurrence déloyale désigne un **ABUS de pratique commerciale d'une entreprise par rapport à une autre**. Elle est constituée de l'ensemble des **procédés concurrentiels contraires à la loi ou aux usages, constitutifs d'une FAUTE**.
>
> **L'action en concurrence déloyale exige :**
> ① une **FAUTE** (agissements fautifs) à l'encontre d'un concurrent,
> ② un **PRÉJUDICE** pour ce dernier, résultant de la **perturbation du libre jeu de la concurrence**,
> ③ un **LIEN DE CAUSALITÉ** entre les deux.
>
> **Fondement :** la responsabilité **délictuelle** (art. 1240 C. civ., ex-1382). **Tribunal : le TRIBUNAL DE COMMERCE.**

### ⭐ Les 4 formes de concurrence déloyale (arbre complet)

```
1. DÉNIGREMENT
   = jeter le DISCRÉDIT sur les produits, services ou la personne d'un concurrent
   → cf. Partie 8 (frontière avec la diffamation)

2. IMITATION / CONFUSION (pratique commerciale trompeuse)
   = créer une CONFUSION avec un bien, un service, une marque, un nom commercial
     ou un signe distinctif d'un concurrent

3. DÉSORGANISATION (de l'entreprise rivale ou du marché)
   Les actes cités par le cours :
     • EXPLOITATION des connaissances techniques et du SAVOIR-FAIRE
     • EMBAUCHE FAUTIVE de personnel / DÉBAUCHAGE massif
     • CRÉATION D'UNE ENTREPRISE CONCURRENTE PAR D'ANCIENS SALARIÉS
     • DÉTOURNEMENT DE LA CLIENTÈLE
     • DÉSORGANISATION de l'activité commerciale
     • divulgation d'informations confidentielles

4. PARASITISME (parasitisme commercial)
   = comportements par lesquels une entreprise TIRE PROFIT DES EFFORTS ET DU
     SAVOIR-FAIRE d'une autre entreprise SANS RIEN DÉPENSER
     (ex. utilisation sans autorisation d'un produit de grande marque pour la
      dotation d'un concours promotionnel)
   ⚠️ Le parasitisme N'EXIGE PAS de situation de concurrence entre les parties.
   ⚠️ C'est le FILET DE SÉCURITÉ quand la contrefaçon échoue faute d'originalité.
```

**Application (débauchage massif) :**
> **Au cas présent :** S a recruté **65 des 120 salariés** de C, qui constituaient des équipes en charge de projets générant **90 % du chiffre d'affaires**, CA que C a immédiatement perdu. C subit un **préjudice matériel** (baisse du CA). Il existe un **lien de causalité** : sans ce débauchage, C n'aurait pas subi une telle diminution. **En procédant à ces recrutements et dans ces conditions, S commet un acte de concurrence déloyale.**
>
> ⚠️ **Nuance à écrire pour montrer ta maîtrise :** le simple débauchage n'est pas fautif en soi (liberté du travail et liberté du commerce) ; c'est son **caractère massif**, **ciblé** et **désorganisateur** qui le rend fautif.

### 6.8.2 La pratique commerciale trompeuse

> **Définition (du cours) :** la pratique commerciale trompeuse désigne une **CONFUSION avec un bien, un service, une marque, un nom commercial ou un signe distinctif d'un concurrent.**
> *(Plus largement en droit de la consommation : est trompeuse la pratique reposant sur des allégations, indications ou présentations FAUSSES ou de nature à INDUIRE EN ERREUR sur les caractéristiques essentielles, le prix, la disponibilité, etc.)*

### 6.8.3 La pratique commerciale déloyale (le critère général)

> **Une pratique commerciale déloyale est caractérisée lorsque la pratique est :**
> ① **contraire aux exigences de la DILIGENCE PROFESSIONNELLE** (prise en compte des pratiques sur le marché), **ET**
> ② **susceptible d'ALTÉRER LE COMPORTEMENT ÉCONOMIQUE du consommateur** au regard d'un bien ou d'un service.

### ⭐ Le cas Webedia / shopoon.fr — l'exemple parfait de la double question

Ce cas est **le** modèle : même faits, **deux qualifications différentes, deux réponses opposées**. Le prof adore.

**Faits :** un guide d'achat en ligne (shopoon.fr, édité par Webedia) affiche **70 produits** d'une marque, dont **93 % sont indisponibles** ; l'internaute est renvoyé vers des **produits similaires concurrents** non signalés comme tels. Les articles restent affichés **30 jours**. **Webedia est rémunérée au CLIC.**

| Question | Réponse | Motivation |
|---|---|---|
| **Pratique commerciale TROMPEUSE ?** | ❌ **NON** | La présentation **n'altère pas de manière substantielle le comportement du consommateur normalement informé et raisonnablement attentif** qui, en cas d'indisponibilité, **se tourne de toute façon vers des articles d'une autre marque**. Ce comportement serait **le même** si le produit était distinctement mentionné comme indisponible. De plus, l'allégation d'une mise en avant par la promotion **n'est pas prouvée** (un seul article sur 65 était en promotion) |
| **Concurrence DÉLOYALE ?** | ✅ **OUI** | Webedia est **rémunérée au clic** : elle tire un **avantage** à ce que l'internaute soit dirigé vers d'autres marques. Elle commet un **acte déloyal** en **utilisant la marque S pour attirer la clientèle** et lui proposer des articles d'autres marques. **En utilisant la FORCE D'ATTRACTION de la marque S pour générer un trafic orienté vers d'autres produits, elle commet un acte de concurrence déloyale** (parasitisme) |

> **La leçon de méthode :** ne réponds jamais « oui » ou « non » globalement. **Chaque qualification a ses propres conditions**, il faut les vérifier une par une. Ici : trompeuse = altération du comportement (non établie) ; déloyale = faute + profit indu (établie).

### ⭐ Le cas des 39 photos — contrefaçon KO, parasitisme OK

**Faits :** une entreprise constate que **39 clichés** de son site sont reproduits par un concurrent. Elle assigne en **contrefaçon de droit d'auteur**. Le photographe cherchait à **effacer toute subjectivité** pour mettre en valeur le produit ; l'angle de vue était dicté par des **impératifs marketing** ; les images sont **dénuées de partis pris esthétiques ou de choix arbitraires** portant l'empreinte de sa personnalité. Il y avait apposé un **petit logo**.

| Question | Réponse |
|---|---|
| **Définir l'originalité d'une photographie** | L'originalité est **l'effort créatif portant l'empreinte de la personnalité de l'auteur**. Elle est la **condition que doit remplir toute œuvre** pour faire l'objet du droit d'auteur |
| **Tribunal compétent ?** | **Principe :** entre entreprises, le **TC** ; sauf si le litige porte sur la **PI**, ce qui rend le **TJ** compétent. Toutefois s'il s'agit d'une action en contrefaçon visant à faire cesser une contrefaçon, **qui est un délit**, le **tribunal correctionnel** est compétent. **Au cas présent :** si l'on considère les photos comme contrefaisantes → **correctionnel** (pénal ET civil) ; à défaut → **TJ** (pour les DI) |
| **Pourquoi débouté en contrefaçon ?** | **Principe :** pour être protégées, les photos doivent **refléter la personnalité de leur auteur**. Cette exigence n'est pas remplie lorsque l'objectif poursuivi est d'**effacer toute subjectivité** ; et **le fait d'apposer un logo ne suffit pas** à conférer aux images un caractère original. **Solution :** elles ne sont **pas éligibles** au droit d'auteur ; **la reproduction de photos non originales ne constitue pas une contrefaçon** |
| **Et sur la concurrence parasitaire ?** | **Principe :** la réutilisation d'images entraîne un **risque de confusion** à l'égard des destinataires des sites concurrents ; la reproduction d'un **nombre significatif** d'images révèle une **volonté de tirer profit d'un investissement** dûment justifié pour développer des images d'une **excellente qualité technique**. **Solution :** si la reproduction de photos non originales **ne constitue pas une contrefaçon, elle est synonyme de CONCURRENCE PARASITAIRE**. Le **TC** a condamné le site ayant reproduit les 39 clichés |

## 6.9 Les clauses limitatives et exonératoires de responsabilité

> **Principe :** les parties peuvent prévoir contractuellement de **limiter ou d'écarter toute indemnité** en cas d'inexécution.
> **Conditions :** cela n'est possible que **pour les contrats passés ENTRE PROFESSIONNELS**, et **à condition que cela ne remette pas en cause la SUBSTANCE MÊME du contrat** (l'obligation essentielle).

> **⭐ La notion de NON-PROFESSIONNEL (à écrire absolument) :**
> « On parle de **non-professionnel** lorsque l'un des cocontractants agit **EN DEHORS DE SON DOMAINE D'ACTIVITÉ**, ou lorsqu'il se trouve **dans la même situation d'IGNORANCE qu'un consommateur**. »

**Application (SARL S informatique / SARL BTP) :**
> **Au cas présent :** l'activité de BTP concerne **la construction**. Elle est donc considérée comme un **non-professionnel dans le cadre de ce contrat informatique** et bénéficie de la **protection du droit de la consommation**.
> La société S prévoit une **exonération TOTALE** de sa responsabilité, portant sur la **substance même du contrat** (le fonctionnement du système).
> → **Cette clause est ABUSIVE.** **Le contrat est MAINTENU, mais la clause est RÉPUTÉE NON ÉCRITE et nulle** (clause léonine).

**Application inverse (Faurecia / Oracle) :**
> À l'origine : Oracle s'était engagé à **adapter son PGI** à l'environnement de l'équipementier en développant une **version spécifique** ; l'adaptation n'a pu se faire ; faute d'entente, Faurecia a **rompu unilatéralement** le contrat, chaque partie accusant l'autre.
> **Principe :** le coût d'un projet informatique est fixé sur le **coût des licences** et sur les **clauses prévues au contrat** signé par l'éditeur et son client. « Le coût d'un projet n'est que marginalement constitué de licences ; une implémentation entraîne des coûts dont le remboursement, en cas d'échec, est **soumis à des limitations validées par la Cour de cassation**. »
> **Solution :** **l'existence de clauses limitant la responsabilité de l'éditeur est RETENUE** par la Cour de cassation. Sur un préjudice estimé à **70 millions d'euros** par le client, Oracle n'a eu à rembourser que le **montant effectivement versé des licences, soit 230 000 €**.
>
> **La différence avec le cas BTP :** ici les deux parties sont **des professionnels du même niveau**, la clause **limite** (elle ne supprime pas) la responsabilité et **ne vide pas** l'obligation essentielle de sa substance → **elle est valable**.

**Les 3 hypothèses où la clause tombe :**
1. Elle contredit la **portée de l'obligation essentielle** (elle vide le contrat de sa substance) ;
2. L'inexécution résulte d'une **faute LOURDE ou DOLOSIVE** ;
3. Elle est **abusive** au sens du droit de la consommation (déséquilibre significatif) → **réputée non écrite**.

## 6.10 Le devoir de conseil et l'information lisible

> **Art. L.441-6 C. com. (cité dans les sujets) :** le prestataire de service **fournit à son client une information conforme aux prescriptions, c'est-à-dire LISIBLE ET COMPRÉHENSIBLE**.

> **Cas type (contrat de téléphonie de 37 pages) :**
> **Q1 — Moyen ou résultat ?** Le **Code des postes et communications électroniques** stipule qu'un fournisseur **n'est pas tenu à une obligation de résultat mais de MOYEN**.
> **Q2 — Quelle autre obligation ?** L'**OBLIGATION DE CONSEIL**, qui **inclut une obligation d'information**. Elle consiste à **tenir compte des besoins du client** en se fondant sur le cahier des charges, et à proposer **la solution la mieux adaptée**. **Au cas présent :** le prestataire **n'a pas vérifié, au stade de la conclusion du contrat, la QUALITÉ DU RÉSEAU dans les locaux** de la société → manquement au devoir de conseil.
> **Q3 — Résiliation fondée ?** **Principe :** si une procédure d'incident est indispensable, le prestataire doit, **dès réception de la 1re mise en demeure, la RAPPELER à son client** en lui demandant de la mettre en œuvre. Un client qui adresse **plusieurs mises en demeure** et **ne reçoit aucune réponse** est **fondé à résilier**. **Au cas présent :** on ne peut reprocher au client de ne pas avoir respecté une procédure figurant dans un contrat de **37 pages en très petits caractères dont un seul paragraphe** la décrit ; le prestataire doit fournir une **information lisible et compréhensible**. **Le tribunal CONFIRME la résiliation**, le fournisseur n'ayant pas respecté son devoir de conseil.

## 6.11 ⭐ Le corps humain hors du commerce (cas Jeanne Hultou — CC2)

**Faits :** une actrice tourne un film publicitaire et se fait **tatouer** un cheval cabré sur l'épaule. Une clause du contrat, **au recto**, à laquelle elle n'avait pas prêté attention, stipule : « Jeanne s'engage à se soumettre à une **opération chirurgicale** permettant de **récupérer son tatouage, qui sera vendu aux enchères publiques** ». Frais d'opération et greffe à la charge du producteur ; elle touchera **12 000 €**.

**Corrigé complet :**

| Rubrique | Contenu |
|---|---|
| **Les faits** | Une actrice s'est fait tatouer pour un tournage. Le producteur lui demande d'exécuter une clause l'obligeant à subir une opération chirurgicale de prélèvement de sa peau tatouée, en vue d'une vente aux enchères, moyennant 12 000 €. |
| **Le problème juridique** | Une convention portant sur un **élément du corps humain** est-elle juridiquement valable ? |
| **La règle de droit** | **① Le principe d'INDISPONIBILITÉ et de NON-PATRIMONIALITÉ du corps humain.** Le corps humain et ses éléments sont **HORS DU COMMERCE** : ils ne peuvent faire l'objet d'un **droit patrimonial**. Le Code civil pose que : *le corps humain est **inviolable*** ; *le corps humain, ses éléments et ses produits **ne peuvent faire l'objet d'un droit patrimonial*** ; *les conventions ayant pour effet de conférer une valeur patrimoniale au corps humain, à ses éléments ou à ses produits sont **NULLES***. Le don d'éléments du corps est soumis au **consentement**, à la **gratuité** et à l'**anonymat**. **② Le contenu du contrat doit être LICITE** et non contraire à l'**ORDRE PUBLIC** et aux **BONNES MŒURS**. **③ L'atteinte à l'INTÉGRITÉ du corps humain** ne peut être justifiée que par une **nécessité médicale** pour la personne (ou l'intérêt thérapeutique d'autrui), avec son consentement. |
| **La solution** | **La vente de la peau tatouée de Jeanne N'EST PAS juridiquement valable.** ① Elle confère une **valeur patrimoniale à un élément du corps humain**, ce que la loi prohibe expressément. ② L'opération chirurgicale n'est justifiée par **aucune nécessité médicale** : l'atteinte à l'intégrité corporelle est **illicite**. ③ La clause a un **objet illicite** et contraire à l'**ordre public** → elle est frappée de **NULLITÉ ABSOLUE**, qui peut être invoquée par **toute personne justifiant d'un intérêt légitime**, et elle **ne peut pas être confirmée**. **Conséquence :** la clause est **réputée non écrite** ; Jeanne **n'est pas tenue de subir l'opération** ; le producteur **ne peut pas en exiger l'exécution forcée**, ni obtenir de dommages-intérêts pour inexécution. Le reste du contrat (la prestation d'actrice, déjà payée) **subsiste**. |
| **Arguments SUBSIDIAIRES à ajouter (bonus)** | ① **Clause abusive / non lue** : elle crée un **déséquilibre significatif** ; le tatouage a été réalisé pour les besoins du tournage, l'obligation de mutilation est **manifestement disproportionnée** à l'économie du contrat. ② **Vice du consentement** : Jeanne « n'avait pas prêté attention » à une clause figurant au **recto** ; on peut plaider la **réticence dolosive** (le producteur savait le caractère déterminant de cette information et n'a pas attiré son attention) ou l'**erreur sur les qualités essentielles** de la prestation. ③ **Droit au respect de l'intégrité physique** et **dignité de la personne humaine** (valeur constitutionnelle). |

> **⚠️ La question annexe possible :** « le tatouage est-il une œuvre protégée ? » → **Oui**, un tatouage original est une **œuvre de l'esprit** ; **le TATOUEUR est l'auteur** et conserve son **droit moral**. La vente du support ne transfère pas les droits d'auteur. Cela ajoute un obstacle supplémentaire à la vente aux enchères.

## 6.12 La rupture des pourparlers (phase précontractuelle)

> **Principe :** **la LIBERTÉ DE NE PAS CONTRACTER reste le principe.** Mais ce droit peut, dans certains cas, **dégénérer en ABUS**, engageant la responsabilité (**délictuelle**) de celui qui rompt.
> La **BONNE FOI**, consacrée à l'article 1104 C. civ. (ex-1134) pour l'exécution, **s'applique dès la formation** et contraint les parties à négocier de bonne foi.

**Les deux conditions pour qu'une rupture soit fautive :**
1. Les pourparlers doivent être **SUFFISAMMENT AVANCÉS** (durée, formalisation des bases d'un accord définitif) ;
2. La rupture doit être de **MAUVAISE FOI** (brutale, sans motif légitime, après avoir entretenu une confiance illégitime).

**Les repères jurisprudentiels du cours :**
- Des pourparlers qui **n'ont duré que 2 mois** et étaient **bloqués dès l'origine** ne sont **pas avancés** : chacun reste **libre d'y mettre fin à tout moment**.
- Il n'y a pas non plus de rupture fautive lorsque les parties **en sont restées à un stade exploratoire** et **n'ont aucunement formalisé les bases d'un accord définitif** : en refusant de finaliser, elles n'ont fait qu'exercer leur **liberté contractuelle, qui implique celle de ne pas contracter**.

> **Application type :** M. M négocie 2 mois avec une ESN, **3 rencontres**, mais **la question du prix n'a JAMAIS été abordée**. L'ESN rompt car elle a obtenu un **autre marché** et **ne parvient pas à recruter** du personnel compétent.
> **Solution :** l'ESN a le droit de rompre (**liberté contractuelle**). Sa **bonne foi est présumée**, car elle est contrainte par un **marché existant antérieurement** et un **manque de personnel compétent**. Les pourparlers **n'étaient pas suffisamment avancés** : 2 mois seulement, et **le prix n'a jamais été abordé**. → **Pas de rupture abusive** ; la demande d'indemnisation de M. M **n'est pas opportune**.
>
> **⚠️ Si la rupture était fautive**, le préjudice réparable est limité : **frais engagés + perte de temps**, mais **JAMAIS la perte des gains attendus du contrat non conclu** (pas de perte de chance de conclure).

## 6.13 Le pouvoir d'engager la société (mandat)

> **Principe :** tout **mandataire** (salarié) doit bénéficier d'un **POUVOIR** de la part du **mandant** (chef d'entreprise) pour engager l'entreprise. **Seul le directeur général** (et ses délégataires) peut contracter au nom de la société ; **un salarié n'a pas, sauf délégation spécifique, le pouvoir d'engager la société qui l'emploie**. En l'absence de ce pouvoir de représentation, **l'annulation du contrat peut être obtenue**.

**Application :** un **technicien** signe un bon de commande de 3 500 € auprès d'un commercial → il **ne dispose d'aucune délégation** → **il n'a pas pu engager l'entreprise** → le chef d'entreprise est **fondé à demander l'annulation** du contrat de vente.

**Le tempérament à connaître : la RATIFICATION et le MANDAT APPARENT.**
- **Ratification :** l'appréciation des faits et circonstances qui révèlent la **ratification par le mandant** des actes accomplis par le mandataire relève du **pouvoir souverain des juges du fond**. Si l'entreprise exécute le contrat en connaissance de cause, elle le ratifie.
- Dans l'arrêt cité : l'envoi, le lendemain, d'une **autorisation bancaire signée de la directrice générale** avait **pu entretenir un doute** sur la validité des engagements — mais ce doute a été **dissipé 10 jours plus tard** par une **LRAR** indiquant que M. X **ne disposait d'aucun pouvoir** et demandant, **avant validation**, à connaître le contenu des contrats. → **Pas de ratification** → **rejet du pourvoi**.
- **Mandat apparent :** le tiers de bonne foi peut se prévaloir de l'apparence si sa **croyance aux pouvoirs du prétendu mandataire était LÉGITIME**. Mais ici, « la société ne pouvait **ignorer qu'un comptable n'a pas le pouvoir** d'engager la société » → l'apparence ne joue pas.

## 6.14 Les plateformes numériques : ÉDITEUR ou HÉBERGEUR ?

C'est **la** question du droit du numérique. Elle détermine tout le régime de responsabilité.

| | **HÉBERGEUR** | **ÉDITEUR** |
|---|---|---|
| **Définition** | **Prestataire technique** qui assure **simplement la mise à disposition d'un serveur et d'une interface** | Celui qui, **par son RÔLE ACTIF**, est supposé **avoir connaissance et contrôler le contenu** diffusé sur son site |
| **Responsabilité** | **Allégée** : responsable seulement s'il avait **connaissance** du caractère illicite et **n'a pas agi promptement** pour le retirer. **Pas d'obligation générale de surveillance** | **De plein droit** du contenu publié, comme un directeur de publication |

### ⭐ Les indices du RÔLE ACTIF (à chercher dans le sujet)

- La plateforme **valide l'inscription** des annonceurs/propriétaires ;
- Elle **fixe le contenu** ou le format des annonces ;
- Elle se réserve un **droit discrétionnaire d'évaluer la pertinence** des annonces au regard des CGU ;
- Elle **retire** les contenus qui contreviennent à ses règles ;
- Elle **classe, hiérarchise, recommande**, attribue des **statuts** (« superhost »), gère des avis ;
- Elle **perçoit une commission** sur les transactions ;
- Elle **optimise** ou **promeut** les annonces.

> **⚠️ L'argument de défense classique et sa réfutation :** la plateforme dit « ce n'est pas moi qui sélectionne, c'est **l'application/l'algorithme** qui fait ressortir les bons et les mauvais hôtes ». → Réfutation : c'est elle qui **fixe les critères** de l'algorithme ; le caractère automatisé n'exclut pas le rôle actif.

**Application (plateforme de location de logements) :**
> **Q1 — Parties, demandeur, tribunal ?** Litige opposant un **particulier** (le bailleur, demandeur) et un **commerçant** (la plateforme, défendeur). → **TJ ou TC au choix** (demandeur PP / défendeur PM). **Une autre réponse serait-elle possible ?** Oui : un **autre tribunal sur le plan géographique**, si une **clause attributive de compétence** était intégrée au contrat.
> **Q2 — Statut ?** La plateforme **dispose d'un droit de regard** sur les annonces, elle **en fixe les critères**, elle est **en capacité de vérifier** si l'hôte dispose du droit de proposer son logement à la location saisonnière. Ces éléments témoignent de son **rôle actif** et de son **immixtion dans le contenu** déposé par les hôtes → elle relève du **statut d'ÉDITEUR**.
> **Q3 — Fondement de la condamnation ?** Elle joue un rôle actif dans la mise en relation ; elle ne joue pas un simple rôle d'hébergeur. Elle **exerce une activité illicite d'intermédiaire** et **commet une faute en s'abstenant de toute vérification** dans l'annonce d'un meublé placé sous une **location prohibée** (sous-location sans accord du bailleur). → Condamnation à **52 000 €** de réparation.
>
> **Rappel sur la sous-location :** le locataire **ne peut ni céder le bail ni sous-louer**, sauf **accord ÉCRIT du bailleur, y compris sur le PRIX du loyer**. Le sous-locataire **ne peut se prévaloir d'aucun droit** à l'encontre du bailleur ni d'aucun titre d'occupation.

**Application (escroqueries sur un site de réservations) :**
> **Q1 — Éditeur ou hébergeur ?** La plateforme **prend une part active** dans la diffusion des annonces : elle **valide l'inscription** des propriétaires, **fixe le contenu** des annonces, se réserve le **droit discrétionnaire d'évaluer leur pertinence** au regard des CGU → **statut d'ÉDITEUR**.
> **Q2 — Position du tribunal ?** Même si les escroqueries n'ont pas pour origine directe une faute ou un dysfonctionnement du site, sa responsabilité peut être engagée **en raison de ses AMBIGUÏTÉS** : **aucun avertissement** ne figure sur le site pour **mettre en garde l'utilisateur contre les risques de parasitage de contenus**, et les éléments d'information publiés **ne sont pas mis en exergue** ou sont **mélangés à des informations diverses**. L'annonce frauduleuse figurait sur un **encadré ajouté par incrustation** dans un emplacement réservé à une photo. → **Manquement à l'obligation d'information et de mise en garde** → **responsabilité engagée** envers les 67 victimes.

**Application (Booking.com — la question de la QUALITÉ à défendre) :**
> **Q1 — « En dernier ressort par une juridiction de 1re instance » ?** Le droit français garantit le **double degré de juridiction**. **Au cas présent :** le montant du litige étant **inférieur à 5 000 €**, **l'appel n'est pas possible** ; on passe **directement de la 1re instance à la Cassation**.
> **Q2 — Position de la Cour de cassation ?** **Principe :** lorsque les **CGU** ne donnent **aucun pouvoir ni autorité à une filiale** pour représenter le siège social, **la filiale n'a aucune prérogative juridique**. **Au cas présent :** peu importe la responsabilité de la plateforme dans l'erreur de réservation, la consommatrice **doit assigner l'opérateur du site, Booking.com BV enregistrée aux Pays-Bas**, et non la filiale de droit français. La juridiction de 1re instance, qui n'a pas répondu aux conclusions de la société sur ce point, **n'a pas satisfait aux exigences du texte** → **CASSATION**.
> **Leçon :** vérifie toujours **QUI a la qualité pour défendre** (le bon défendeur), avant même la compétence.

## 6.15 La résolution d'un contrat de développement — le cas complet

**Faits :** commande d'un site marchand, financé par un **contrat de location** (abonnement). Contrat conclu le 28/02/N ; **PV de livraison signé le 26/04/N** alors que **seules les maquettes** ont été fournies. Dès la signature, le prestataire facture les loyers et le prix complet. **Aucun cahier des charges écrit.** Le prestataire n'a pas mesuré l'ampleur de la BDD ni sécurisé son transfert. **7 mois** pour livrer un site truffé de dysfonctionnements : commandes de produits hors stock, absence d'e-mail de confirmation, factures non conformes, **3D Secure non fonctionnel**, erreur de TVA, erreurs dans les liens de contact et de paiement sécurisé, erreur dans le plan d'accès.

| Question | Réponse |
|---|---|
| **Tribunal compétent ?** | **Principe :** le **TC** est compétent pour les litiges entre deux sociétés ; si le litige portait sur la PI, ce serait le **TJ**. **Au cas présent :** le litige porte sur l'**inexécution d'un contrat de fourniture d'une solution informatique** → **TC** |
| **Quand aurait dû être signé le PV ?** | Le PV doit être signé **au moment de la MISE EN LIGNE du site, dûment validé et fonctionnel**, c'est-à-dire à la **date de livraison effective** du site commandé — pas au stade des maquettes |
| **Les manquements justifient-ils la résiliation (analyse par le DOL) ?** | **Principe :** le dol est constitué par des **manœuvres frauduleuses** émanant d'un cocontractant, destinées à **tromper l'autre** afin qu'il s'engage. **Au cas présent :** le PV **caractérise une action dolosive** du prestataire à l'égard de son client (faire signer une livraison qui n'existe pas, pour déclencher la facturation). Les **dysfonctionnements sont réels et suffisants** pour que le client doute d'obtenir un site fiable et efficace. → Le tribunal **prononce la résiliation** du contrat, et **déclare CADUC le contrat de location**, car le PV de livraison — **déclencheur du paiement des loyers** — ne pouvait pas être pris en compte (sa signature ne correspondait pas à la date de livraison réelle) |
| **Conséquences de la résiliation ?** | **Principe :** en cas de dol, **le contrat est censé ne pas avoir eu lieu** ; **les choses sont remises en l'état**. **Au cas présent :** la **résolution judiciaire est RÉTROACTIVE** ; elle entraîne la **restitution des contenus utilisés**, des **droits de gestion des noms de domaine**, des **loyers déjà perçus** et des **sommes versées par le loueur au prestataire** |

---

# PARTIE 7 — LES SPÉCIFICITÉS DES CONTRATS NUMÉRIQUES

## 7.0 La logique

> « La matière est dominée par une **double antinomie** : ① l'opposition entre les **règles générales et spéciales** ; ② le droit des contrats spéciaux qui **protège les consommateurs non professionnels**. »

Autrement dit : on part du droit commun des contrats (Partie 6) et on ajoute des **obligations renforcées** pesant sur le professionnel de l'informatique, parce que le client est souvent **profane**.

## 7.1 La responsabilité des prestataires externes

### 7.1.1 Responsabilité LÉGALE

**Principe général :** un prestataire de service est **responsable des informations qu'il stocke**. **S'il a connaissance d'une information illicite et qu'il n'intervient pas, il engage sa responsabilité.**

| Acteur | Régime |
|---|---|
| **Fournisseur d'accès à Internet (FAI)** | **PRINCIPE DE NON-RESPONSABILITÉ.** Son activité est de permettre l'accès aux services de communication au public. Il n'a **aucune implication dans le choix du destinataire ni dans le contenu** de l'information transmise. Il est **exonéré** et ne peut être condamné pour la transmission d'œuvres protégées. Il **n'a AUCUNE obligation de surveillance** : il ne lui incombe **ni d'enquêter ni de filtrer** les contenus |
| **Hébergeur / Éditeur** | Le RGPD leur confère à tous deux la **qualité de SOUS-TRAITANT**, avec l'obligation de mettre en place un **dispositif de SIGNALEMENT (alerte)** et un **dispositif de FILTRAGE**. Cette obligation de signalement vise à **identifier les sites illicites** (propos racistes, pédopornographie) |

### 7.1.2 Responsabilité CONTRACTUELLE

Pour s'exonérer, les prestataires peuvent **insérer une clause limitative de responsabilité**. Un fournisseur d'hébergement peut préciser au contrat que **le contenu des sites hébergés relève de la responsabilité de l'abonné**, et se prémunir contre les réclamations liées au caractère illicite de l'information transmise. Il s'agit, pour le prestataire, de **rappeler les obligations contractuelles auxquelles a souscrit le client**.

> **⭐ Le cas de la maintenance (obligation de RÉACTIVITÉ) :**
> **Principe :** « Si un prestataire n'est pas responsable du **conflit entre la solution serveur et le logiciel applicatif**, il est de sa responsabilité, **de professionnel spécialiste, d'IDENTIFIER les problèmes afin d'y trouver les solutions**. En n'apportant pas de réponse alors qu'il y a **répétition des réclamations**, un prestataire informatique **manque à ses obligations contractuelles**. »
> **Solution :** le tribunal (TC) condamne le prestataire — **non pas pour la survenance des problèmes**, qui ne lui était pas reprochable en soi, **mais pour avoir TARDÉ à corriger les pannes**.
>
> **Retiens cette dissociation :** *l'origine du dysfonctionnement* ≠ *la diligence à le traiter*. C'est sur la seconde qu'on est condamné.

## 7.2 ⭐ Les obligations du CONCEPTEUR DE SOLUTIONS LOGICIELLES

C'est le cœur du chapitre. Deux blocs à ne jamais confondre.

### Bloc 1 — Obligations d'INFORMATION : ce sont des OBLIGATIONS DE MOYEN

| Obligation | Contenu |
|---|---|
| **Obligation d'INFORMATION** | Le droit fait peser sur le concepteur une **obligation de RENSEIGNEMENT** vis-à-vis de son contractant. Les informations concernant le **fonctionnement du logiciel** sont **indispensables au bon déroulement du projet** |
| **Obligation de MISE EN GARDE** | Les renseignements fournis doivent **attirer l'attention du client sur les RISQUES POTENTIELS et les DIFFICULTÉS INHÉRENTES** au fonctionnement du projet informatique |
| **Obligation de CONSEIL** | **L'obligation de conseil INCLUT l'obligation d'information.** Elle consiste à **tenir compte des BESOINS du client** en se fondant sur le **CAHIER DES CHARGES**. Les conseils du professionnel doivent **répondre aux attentes** du contractant, en lui proposant **la solution logicielle la mieux adaptée** |

> **Hiérarchie à retenir : CONSEIL ⊃ MISE EN GARDE ⊃ INFORMATION.** Le conseil est le plus exigeant : il implique de **déconseiller** une solution inadaptée, voire de **refuser** la commande.

### Bloc 2 — Obligation de DÉLIVRANCE : c'est une OBLIGATION DE RÉSULTAT

| Étape | Contenu |
|---|---|
| **1re étape — RECETTE UNITAIRE** (phase **temporaire**) | La délivrance s'effectue par la **phase de programmation**, c'est-à-dire une phase d'**écritures et de TESTS UNITAIRES**. Le concepteur peut être amené à procéder à des **modifications sur les recommandations de son client** |
| **2de étape — RECETTE FONCTIONNELLE** (phase **définitive**) | Elle comporte l'**intégration** et la **validation des tests de fonctionnement**. **La livraison du logiciel s'effectue**, ainsi que le **transfert de la propriété** et le **paiement du prix** par le client. L'obligation de délivrance **inclut une DOCUMENTATION du logiciel** pour les licences propriétaires |

### ⚠️ Le contrepoids : l'OBLIGATION DE RECETTAGE DU CLIENT

C'est le retournement que le prof aime placer.

> **Cas :** un prestataire livre un site marchand en précisant au client : qu'il lui appartient de **livrer les paramètres « prod »** pour tester la solution de paiement ; qu'il lui appartient, **conformément aux CGV, de VÉRIFIER que tout fonctionne et de VALIDER le site** ; que si la page d'accueil met **3 heures à charger**, c'est **à cause des images immenses que le client aurait dû réduire**. Le prestataire fournit les **codes d'accès administrateur**. **Le client valide le site SANS effectuer de tests.** 8 mois après la mise en ligne, il met le prestataire en demeure d'exécuter « entièrement et correctement » ses obligations.
>
> **Principe :** en vertu des **CGV du prestataire**, **il appartient au CLIENT de vérifier le bon fonctionnement du site, en procédant à son RECETTAGE et en effectuant des TESTS**, d'autant qu'il **disposait des accès administrateur**. **Disposant de ces codes, le client a la responsabilité du fonctionnement du site.**
> **Solution :** le tribunal de commerce **rappelle l'obligation du client** de vérifier le bon fonctionnement en procédant au recettage → **il REJETTE les demandes du client**.

> **Compare avec le cas 6.15** (PV signé alors que seules les maquettes étaient livrées, aucun cahier des charges, dysfonctionnements majeurs) : là, **le prestataire perd**. La différence tient à : ① l'existence de **CGV claires** répartissant les rôles, ② la fourniture des **accès administrateur**, ③ le caractère **exploitable ou non** du site, ④ l'existence d'un **cahier des charges**.
> **→ Ces 4 critères sont les variables que le prof manipule.** Repère-les dans l'énoncé pour savoir qui gagne.

### La responsabilité contractuelle du concepteur envers le CLIENT PROFANE

> La relation contractuelle établie entre le concepteur et **le CLIENT PROFANE** déclenche la responsabilité du professionnel en cas de non-respect de ses obligations. Il faut prouver :
> - **une FAUTE**, qui consiste à montrer l'**inexécution d'une obligation contractuelle** (non-délivrance du logiciel, non-respect des délais de livraison ou du prix convenu) ;
> - **un DOMMAGE MATÉRIEL** (ex. le coût des serveurs excède le budget préconisé par l'éditeur au départ) ;
> - **un LIEN DE CAUSALITÉ** entre le dommage et la faute.
>
> **Le droit rétablit l'ÉQUILIBRE CONTRACTUEL entre le professionnel et le client profane. Il insère des clauses de garanties pour protéger ce dernier.**

## 7.3 Les obligations induites par les contrats informatiques

**AVANT la signature** → les trois obligations d'information, mise en garde et conseil (cf. 7.2, bloc 1).

**APRÈS la signature** → les **garanties spécifiques** :
- garantie de **conformité**,
- garantie de **performance**,
- garantie d'**exécution**,
- garantie de **service régulier**,
- garantie des **matériels et logiciels**.
*(+ garantie d'éviction et garantie des vices cachés du droit commun.)*

## 7.4 Le cas « société S / SARL BTP » — corrigé complet (il tombe souvent)

| Question | Réponse |
|---|---|
| **1. Nature du contrat ?** | Le contrat est passé **entre 2 sociétés dans le cadre de leur activité professionnelle** ; ces sociétés sont **commerciales par la forme (SARL)** → il s'agit d'un **contrat COMMERCIAL**. Le contenu porte sur **l'écriture et la mise au point d'un logiciel** → il s'agit d'une **prestation de service informatique** (contrat d'entreprise / de louage d'ouvrage) |
| **2. Obligations de chaque partie ?** | **Principe :** contrat **synallagmatique**, obligations **réciproques**. **Obligations du PRESTATAIRE :** ① obligation d'**information et de conseil** ② obligation d'**exécuter le travail** ③ obligation de **livraison dans les délais requis**. **Obligations du MAÎTRE D'OUVRAGE (le client) :** ① **réceptionner l'ouvrage** (reconnaître la conformité de la commande) ② **payer le prix** prévu au contrat. **Au cas présent :** la **propriété et les risques** sont transférés au maître d'ouvrage ; ce dernier **coopère de bonne foi**, **ne gêne pas l'exécution** et **facilite les travaux** ; BTP fournit **le cahier des charges** et toute information nécessaire ; S réalise la prestation en **16 semaines** (délai courant à compter de la remise du cahier des charges) et fournit toute information nécessaire à la bonne utilisation du logiciel |
| **3. La clause d'exonération totale est-elle valable ?** | Cf. 6.9 → **NON**, clause **abusive** car BTP est **non-professionnel** dans ce domaine et la clause porte sur la **substance même du contrat** → **réputée non écrite et nulle** (clause léonine), **le contrat étant maintenu** |
| **4. Voies de réparation pour la société C (publicité trompeuse) ?** | **Principe :** l'**action civile** est l'action en justice exercée par la victime pour obtenir des **DI en réparation d'un préjudice**. Elle peut être exercée **en même temps que l'action publique devant le juge pénal**, ou **devant le juge civil**. La victime a **le CHOIX** : ① **la voie PÉNALE** pour obtenir la sanction de l'auteur de l'infraction ; ② **la voie CIVILE** pour obtenir la réparation du préjudice. **Ce choix est IRRÉVOCABLE.** Deux principes doivent être respectés : **« LE PÉNAL TIENT LE CIVIL EN L'ÉTAT »** (le juge civil attend que le juge pénal se prononce) et **« LE PÉNAL L'EMPORTE SUR LE CIVIL »** (le juge civil ne peut se prononcer différemment du juge pénal). **Au cas présent :** la société C obtient réparation en choisissant entre la voie civile et la voie pénale. **La voie pénale est plus rapide, la preuve y est LIBRE**, et elle permet de profiter de la **mise en œuvre de moyens coercitifs** et du **soutien du Ministère public** |
| **5. Conditions de la responsabilité du fait des produits défectueux ?** | Cf. 6.6 : le **producteur** est responsable du dommage causé par un défaut de son produit, **qu'il soit ou non lié par un contrat** avec la victime. Celle-ci met en œuvre soit la **responsabilité contractuelle** (en démontrant la mauvaise exécution du contrat), soit la **responsabilité délictuelle** du producteur (quand elle n'a pas de lien contractuel avec lui). **La personne responsable est le producteur ou le vendeur.** Dans le cadre **contractuel**, la victime prouve **qu'une obligation stipulée au contrat n'a pas été exécutée** ; dans le cadre **délictuel**, elle prouve un **fait générateur** (mise en circulation du produit défectueux) et le **défaut du produit** |

## 7.5 La violation de clauses de confidentialité — corrigé complet

**Faits :** une société S conclut un accord de collaboration avec un prestataire P (traçabilité logistique). Après **32 mois** de travaux encadrés par différents contrats (audit, étude sur sites pilotes, synthèse) réalisés pour **60 000 €**, P **n'est pas retenu** à l'appel d'offres pour le déploiement à grande échelle. P constate la **reproduction et la diffusion, sur le site Internet de S et auprès de ses concurrents**, de son **rapport sur la phase pilote** et de son **cahier des charges fonctionnel** reprenant les fonctionnalités du logiciel. Il demande **600 000 €** (diffusion aux concurrents) + **50 000 €** (pertes directes) + **550 000 €** (perte de chance de gains).

| Rubrique | Contenu |
|---|---|
| **Les faits** | Une entreprise conclut un accord de collaboration avec un prestataire. À l'issue de travaux encadrés par différents contrats, ce dernier n'est pas retenu au terme de l'appel d'offres. Le prestataire constate la **diffusion et l'utilisation de son travail** |
| **Le problème juridique** | En l'absence d'accord conclu sur le déploiement d'une solution et à la suite d'une phase pilote achevée, la **rupture brutale des relations contractuelles** peut-elle être invoquée par l'un des cocontractants ? |
| **La règle de droit** | La **diffusion à grande échelle du produit d'un travail** entraîne le **renforcement de la position des concurrents** sur le marché et un **affaiblissement de la compétitivité de la victime**, ainsi qu'une **atteinte à son image** |
| **La solution** | Il y a **violation, par la société S, des clauses de CONFIDENTIALITÉ, de PROPRIÉTÉ INTELLECTUELLE et de NON-CONCURRENCE**. Le prestataire est **fondé à obtenir réparation**. Pour **chiffrer le préjudice**, 2 éléments sont pris en compte : ① un montant **au moins égal à la valeur d'achat des modules** sur lesquels les informations ont été diffusées ; ② une **proposition de règlement amiable**. **Le préjudice a été fixé à 300 000 €**, incluant la **perte de compétitivité**, l'**atteinte à l'image** et la **perte de l'appel d'offres** |

> **⚠️ Le point clé :** la rupture brutale ne pouvait **pas** être invoquée pour le **déploiement** (aucun accord conclu, phase pilote achevée = les contrats sont **arrivés à leur terme**), mais la société est condamnée **sur le terrain de la violation des clauses**. Encore une fois : **une demande peut échouer sur un fondement et prospérer sur un autre**.

---

# PARTIE 8 — LIBERTÉ D'EXPRESSION, PRESSE ET RÉSEAUX SOCIAUX

## 8.0 La logique du chapitre

> **Un MÉDIA est un support de l'information.** Il englobe Internet, la presse, la radio, les tracts.
> **Il n'y a PAS de différence fondamentale entre le droit qui encadre la liberté d'expression dans la presse classique et sur le net.**

**La particularité de la preuve sur Internet :** elle est **à la fois plus facile** à obtenir (rien n'échappe à Internet) **et parfois plus difficile** (on peut supprimer des données), alors qu'un tract ou un journal, une fois diffusé ou imprimé, est **indélébile**.

> **Et surtout :** « **Il n'existe NI droit de l'Internet, NI droit des réseaux sociaux, mais une APPLICATION DES AUTRES DROITS à l'Internet et aux réseaux sociaux.** » ← phrase à replacer en introduction de toute copie sur ce chapitre.

## 8.1 Les principes de la liberté d'expression

> **« La libre communication des pensées et des opinions est un des droits les plus précieux de l'Homme : tout citoyen peut parler, écrire, imprimer librement, SAUF À RÉPONDRE DE L'ABUS DE CETTE LIBERTÉ. »** (art. 11 DDHC 1789)

- Cette liberté a **valeur CONSTITUTIONNELLE** : elle **s'impose aux lois**.
- Elle s'impose **aux émetteurs ET aux destinataires**, c'est-à-dire au public → d'où découlent le **droit au pluralisme** et à la **transparence**.
- Elle est affirmée en **droit européen** (art. 10 CEDH) : toute personne a droit à la liberté d'expression. **N'importe quel justiciable peut saisir la Cour européenne des droits de l'Homme, UNE FOIS TOUS LES RECOURS ÉPUISÉS EN DROIT INTERNE.**

**Les limites (art. 4 et 5 DDHC) :**
> « **La liberté consiste à pouvoir faire tout ce qui ne nuit pas à autrui.** L'exercice des droits naturels de chaque homme n'a de bornes que celles qui assurent aux autres membres de la société la jouissance de ces mêmes droits. **Ces bornes ne peuvent être fixées que par la LOI.** »

**Les contrôles préventifs prévus par le droit (à citer) :**

| Média | Contrôle |
|---|---|
| **Radio-télévision** | **Contrôle préalable**, pouvoir de tutelle et de contrôle de l'**ARCOM** (Autorité de Régulation de la COMmunication audiovisuelle et numérique) |
| **Cinéma** | L'exploitation des films est soumise à un **contrôle préalable** et à **autorisation** (visa d'exploitation) |
| **Presse écrite** | Diverses formes de **contrôle administratif préalable** |
| **Pouvoirs généraux de police** | Les autorités investies de ces pouvoirs peuvent, **pour assurer le maintien de l'ordre public**, prononcer des **mesures d'interdiction et de saisies de publications** (ex. affaire Dieudonné, 9 janvier 2014 à Saint-Herblain) |

## 8.2 La loi du 29 juillet 1881 sur la liberté de la presse

**Nature :** il s'agit de **DROIT PÉNAL**, avec des mécanismes de responsabilité. Le texte est **avant tout RÉPRESSIF et non RESTRICTIF** — signe que **la liberté d'expression est un PRINCIPE, et non une exception**.

**Articles fondateurs :**
- **Art. 1 :** l'imprimerie et la librairie sont **libres**.
- **Art. 2 :** le **secret des sources des journalistes est protégé** dans l'exercice de leur mission d'information du public.
- **Art. 3 :** tout écrit rendu public porte l'**indication du nom et du domicile de l'imprimeur**.

### Le double aspect du droit pénal

| | **ACTION PUBLIQUE** | **ACTION CIVILE** |
|---|---|---|
| **Définition** | Action pour l'**application de la loi pénale**, exercée **au nom de la société** par le **MINISTÈRE PUBLIC** contre l'auteur supposé de l'infraction | Action en **réparation d'un préjudice**, issu ou non d'une infraction pénale |
| **But** | **Punir** | **Réparer** (DI) |
| **Exercée devant** | Juridictions pénales | Juridictions **civiles OU pénales** |
| **Condition** | Une infraction | L'infraction a porté atteinte à un **intérêt privé** conjointement à l'atteinte à l'ordre public |

> ⚠️ **Argument de défense classique et sa réfutation :** un défendeur soutient parfois que « **seul le procureur a l'opportunité des poursuites** » pour contester une demande. → **Réfutation :** l'opportunité des poursuites du procureur concerne **l'action publique**. Elle **n'empêche nullement** la victime d'exercer son **action civile**, ni de solliciter du juge civil une **mesure d'instruction légalement admissible** pour laquelle il existe un **motif légitime**. Les deux voies sont **indépendantes**.

## 8.3 ⭐ LES DEUX PRINCIPAUX DÉLITS DE PRESSE + LE DÉNIGREMENT

C'est **le** cœur du chapitre. Le prof teste systématiquement la **frontière** entre ces trois notions.

### Les définitions à réciter mot pour mot

> **LA DIFFAMATION** est **toute ALLÉGATION ou IMPUTATION D'UN FAIT qui porte atteinte à l'HONNEUR ou à la CONSIDÉRATION de la personne.**
> **Il n'y a PAS diffamation si la personne qui en est l'auteur PROUVE LA VÉRACITÉ DES FAITS qu'elle avance** (*exceptio veritatis*, l'exception de vérité).

> **L'INJURE** est **toute EXPRESSION OUTRAGEANTE, TERME DE MÉPRIS ou INVECTIVE QUI NE RENFERME L'IMPUTATION D'AUCUN FAIT.**

> **LE DÉNIGREMENT** est le fait d'**attaquer la réputation de quelqu'un, le noircir, le discréditer, parler avec malveillance, le calomnier : dénigrer ses concurrents.**
> **Le dénigrement relève de la CONCURRENCE DÉLOYALE. Ce n'est PAS une infraction : il relève du CIVIL.**

**Moyens de commission de l'injure et de la diffamation :** discours, cris, menaces proférés dans des lieux ou réunions publics ; écrits, dessins, images ou tout autre support de l'écrit ou de la parole ; affiches exposées au grand public ; **tout moyen de communication électronique**.

### ⭐ L'ARBRE DE DÉCISION DIFFAMATION / INJURE / DÉNIGREMENT

```
Des propos négatifs ont été tenus. Que sont-ils ?

ÉTAPE 1 — Sur QUOI portent-ils ?

├── Sur une PERSONNE (physique ou morale), son honneur, sa considération,
│   sa probité, sa compétence professionnelle, sa moralité
│   → on est sur le terrain PÉNAL (loi de 1881)
│   │
│   ├── ÉTAPE 2a — Les propos IMPUTENT-ILS UN FAIT PRÉCIS,
│   │   susceptible de faire l'objet d'une VÉRIFICATION et d'un DÉBAT
│   │   contradictoire ?
│   │
│   ├── OUI (« il a détourné 10 000 € », « c'est une voleuse et une
│   │        arnaqueuse », « il facture des heures non travaillées »)
│   │        → DIFFAMATION
│   │        ⚠️ « Peu importe que le fait soit VRAI ou FAUX, mais il doit
│   │           être PRÉCIS pour faire l'objet d'une vérification et
│   │           d'un débat constructif. »
│   │        Défenses possibles : ① EXCEPTION DE VÉRITÉ (prouver les faits)
│   │                             ② BONNE FOI (but légitime, absence
│   │                                d'animosité personnelle, prudence dans
│   │                                l'expression, enquête sérieuse)
│   │
│   └── NON — pure expression outrageante, mépris, invective, insulte
│            (« faussaire », « mufle », « goujat », « connard », « sorcière »)
│            → INJURE
│            Défense possible : EXCUSE DE PROVOCATION (cf. ci-dessous)
│
└── Sur des PRODUITS, SERVICES ou PRESTATIONS d'une entreprise
    (« ce logiciel est bugué », « leurs cours ne servent à rien »,
     « ils cherchent le profit au détriment du client »)
    → on est sur le terrain CIVIL
    │
    ├── ÉTAPE 2b — L'information se rapporte-t-elle à un SUJET D'INTÉRÊT
    │   GÉNÉRAL et repose-t-elle sur une BASE FACTUELLE SUFFISANTE ?
    │   ├── OUI → cela relèverait de la DIFFAMATION (donc de 1881)
    │   └── NON → DÉNIGREMENT
    │
    └── → DÉNIGREMENT (concurrence déloyale) → TRIBUNAL DE COMMERCE
         ⚠️ « MÊME EN L'ABSENCE d'une situation de concurrence entre les
            personnes concernées, la publication d'un propos de nature à
            jeter le discrédit sur un produit constitue un acte de
            dénigrement. »
         ⚠️ « La divulgation d'une information de nature à jeter le discrédit
            sur un concurrent constitue un dénigrement, PEU IMPORTE
            QU'ELLE SOIT EXACTE. » (≠ diffamation où la vérité exonère !)
         ⚠️ « Les APPRÉCIATIONS, MÊME EXCESSIVES, touchant les PRODUITS,
            les SERVICES ou les PRESTATIONS d'une entreprise N'ENTRENT PAS
            dans les prévisions de l'article 29 de la loi du 29 juillet 1881,
            dès lors qu'elles ne portent pas atteinte à l'honneur ou à la
            considération de la personne physique ou morale qui l'exploite. »
```

### Le tableau comparatif de synthèse

| | **DIFFAMATION** | **INJURE** | **DÉNIGREMENT** |
|---|---|---|---|
| **Nature** | **Délit** (pénal) | **Délit** (pénal) | **Faute civile** (concurrence déloyale) |
| **Objet** | Imputation d'un **FAIT PRÉCIS** portant atteinte à l'honneur/considération d'une **personne** | Expression **outrageante SANS imputation de fait** | Discrédit jeté sur les **PRODUITS / SERVICES / PRESTATIONS** |
| **La vérité exonère ?** | ✅ **OUI** (exception de vérité) | Sans objet | ❌ **NON**, peu importe que l'information soit exacte |
| **Concurrence exigée ?** | Non | Non | ❌ **NON**, même en l'absence de concurrence |
| **Tribunal** | **Correctionnel** | **Correctionnel** | **Tribunal de commerce** (entre PM) |
| **Fondement** | Loi 1881 | Loi 1881 | Art. 1240 C. civ. (délictuel) |
| **Prescription** | **3 mois** | **3 mois** | 5 ans |

> **⚠️ Le raisonnement en DEUX temps que le prof attend (cas de l'auto-école) :**
> **Principe :** ① « Les **jugements négatifs** portés dans une affaire et qui ont pour but de **faire fuir la clientèle** **NE PRÉSENTENT PAS un caractère diffamatoire** » ; ② « Par ailleurs, la **divulgation d'une information de nature à jeter le discrédit sur un concurrent constitue un DÉNIGREMENT** ».
> **Au cas présent :** le **frère de l'auteur de l'avis est un concurrent direct** de l'auto-école → **le tribunal retient la qualification de DÉNIGREMENT au détriment de la diffamation** → **TC compétent** (les propos relevant du dénigrement, qui s'apparente à de la concurrence déloyale).

### ⭐ La question de l'IDENTIFICATION de l'auteur (l'adresse IP)

C'est une question à part entière dans les CC.

> **Principe :** **« Faute de prouver qu'une adresse IP a été piratée ou utilisée par un tiers, son TITULAIRE est PRÉSUMÉ être à l'origine de la publication de l'avis. »**
>
> **Comment on remonte à l'auteur (la chaîne à décrire) :**
> ① **Ordonnance sur requête** auprès de la **plateforme** (Google, Wikimedia, X/Twitter, Facebook) pour connaître le **titulaire du compte** et l'**adresse IP** utilisée ;
> ② **Ordonnance sur requête** auprès du **fournisseur d'accès** pour savoir **à quel abonné correspond l'adresse IP** désignée par la plateforme.
>
> **Les indices que le juge retient pour écarter la thèse du piratage :**
> - l'auteur présumé **n'apporte pas la preuve** que son poste de travail a été piraté ;
> - **concordance temporelle** : la mise en ligne correspond au moment où l'entreprise se sépare de lui, à l'issue d'une période d'essai **très conflictuelle** ;
> - **mobile** : un proche (le frère) est un **concurrent direct**.

**Variante « directeur de la publication » :**
> **Faits :** un habitant titulaire d'une page de réseau social consacrée à sa ville conteste sa qualité de directeur de la publication.
> **Principe :** « **Un smartphone utilisé pour créer un compte sur un réseau social est un élément SUFFISANT pour établir que le titulaire du numéro possède la qualité de directeur de publication.** » (Pour valider la création d'un compte, il faut **confirmer le numéro de mobile par un code envoyé par SMS**.)
> **Au cas présent :** l'habitant est à l'origine de la création de la page (validation par son numéro) ; à ce titre, il **dispose des éléments utiles à sa gestion** et aux publications qui y figurent → **il y a lieu de le considérer comme directeur de publication**. Il prétend, **sans le prouver**, qu'on lui aurait emprunté son portable à son insu → argument écarté.
> **Réserve à écrire (elle rapporte des points) :** « Reste une question à laquelle le tribunal devra répondre : **les propos tenus sont-ils diffamatoires ou non ?** » — établir la qualité de directeur de publication ne suffit pas à condamner.

## 8.4 La responsabilité en cascade des délits de presse

> **Tout journal ou écrit périodique doit avoir un DIRECTEUR DE LA PUBLICATION.**
> **C'est le DIRECTEUR DE LA PUBLICATION qui ENDOSSE la responsabilité des délits de presse.**
> **Les AUTEURS sont poursuivis comme COMPLICES.**

**Transposition au numérique :** le titulaire/administrateur d'un blog, d'une page ou d'un compte est assimilé au directeur de la publication pour les contenus qu'il publie ou qu'il a **choisi de rendre publics**. *(Pour les commentaires de tiers, il n'est responsable que s'il en avait connaissance et ne les a pas retirés promptement — logique de l'hébergeur.)*

## 8.5 ⭐ INJURE PUBLIQUE vs INJURE NON PUBLIQUE (la question des réseaux sociaux)

C'est **la** question typique du chapitre.

| | **INJURE PUBLIQUE** | **INJURE NON PUBLIQUE** |
|---|---|---|
| **Définition** | Injure **pouvant être entendue ou lue par UN PUBLIC** ; les personnes témoins **n'ont pas forcément de liens entre elles** | Injure **adressée sans qu'aucune tierce personne ne soit présente** (SMS, message privé), **OU** prononcée devant un **cercle RESTREINT de personnes**, en présence ou en l'absence de la victime |
| **Exemples** | Injures en pleine rue, entre automobilistes, publiées dans un journal ou sur un site Internet | SMS, mail privé, propos dans un bureau fermé entre 2 collègues |
| **Sur les réseaux sociaux** | Si les propos sont diffusés sur un compte **accessible à TOUS les internautes** → **injure PUBLIQUE** | Si les propos sont diffusés sur un compte accessible à un **nombre RESTREINT d'amis SÉLECTIONNÉS par l'auteur** → **injure NON PUBLIQUE** |
| **Qualification** | **Délit** → tribunal correctionnel | **Contravention** (de 1re classe) → **tribunal de police** |

> **⭐ Le critère technique décisif : LE VERROUILLAGE DU COMPTE.**
> « Les propos tenus sur un réseau social peuvent être considérés comme une injure publique. **Selon le VERROUILLAGE, les propos sont accessibles à tout internaute ou à un cercle restreint.** »

**Les définitions associées (souvent demandées) :**
> **La CONVERSATION PRIVÉE** est une conversation **entre un NOMBRE RESTREINT de personnes IDENTIFIÉES**.
> **A contrario, la CONVERSATION PUBLIQUE** est une conversation **sans qu'il soit possible de connaître l'ensemble des participants**.

### L'EXCUSE DE PROVOCATION

> **Principe :** un auteur bénéficie de l'**excuse de provocation**, qui **fait disparaître l'ÉLÉMENT INTENTIONNEL** de l'infraction d'injure publique envers un particulier, si la provocation est :
> **PERSONNELLE + DIRECTE + FAUTIVE + PROPORTIONNÉE + PROCHE DANS LE TEMPS de l'injure.** (5 conditions cumulatives)

> **Cas type (les deux ex-amis, l'invitation Facebook) :** deux hommes avaient collaboré professionnellement (pochettes de disques, site Internet). **Longtemps après leur rupture**, l'un reçoit une **invitation Facebook** de l'autre, ce qui déclenche sa colère : il répond par un long message le traitant « de faussaire, de mufle, de goujat, de connard ! ».
> **Analyse de l'excuse de provocation :** l'invitation Facebook est-elle une provocation **fautive** ? **Non** — envoyer une invitation n'est pas un comportement fautif. Est-elle **proportionnée** à la violence de la réponse ? **Non.** Est-elle **proche dans le temps** ? Il s'est écoulé **longtemps** depuis la rupture. → **L'excuse de provocation ne joue PAS.**
> **Principe de la décision :** « Le fait que des propos traduisent une **OPINION PERSONNELLE**, **qui ne s'inscrit PAS dans un DÉBAT D'INTÉRÊT GÉNÉRAL ou une POLÉMIQUE existant entre les parties**, **EXCÈDE LES LIMITES DE LA LIBERTÉ D'EXPRESSION**. »
> **Solution :** le tribunal a **condamné pour INJURES PUBLIQUES** la personne qui avait tenu des propos outrageants sur Facebook à l'encontre d'un ancien ami et partenaire professionnel. **Tribunal compétent : le tribunal CORRECTIONNEL** (l'injure publique est un délit).

## 8.6 Le droit au respect de la vie privée et le droit à l'image

> **Fondement : article 9 du Code civil — « Chacun a droit au respect de sa vie privée. »**
> **Le droit à l'image protège l'image dans un cadre public.**

**Les règles :**
- Pour photographier une personne, il faut obtenir une **AUTORISATION ÉCRITE**, précisant la **FINALITÉ** et les **SUPPORTS** de l'image.
- Pour les **mineurs** ou **majeurs incapables** : autorisation des **parents** ou du **représentant légal**.
- **La personne doit être IDENTIFIABLE** pour qu'il y ait atteinte au droit à l'image.

### Les 3 cas où AUCUN consentement n'est requis (à connaître)

1. **FAIT D'ACTUALITÉ** : lorsque l'image relève d'un fait d'actualité, **nul consentement n'est requis** — mais il faut un **LIEN ÉTROIT entre le fait et sa représentation**.
2. **PHOTOGRAPHIE DE GROUPE** : en cas de photographie de groupe, **aucune autorisation ne doit être demandée** (la personne n'y est pas isolée ni individualisée).
3. **PERSONNE PUBLIQUE dans l'exercice de ses fonctions** : de même lorsque la personne visée est une **personne publique se présentant, à cet instant, dans le cadre de ses fonctions**.
*(+ le lieu public où la personne n'est pas le sujet principal du cliché.)*

> **⭐ Le cas de la professeure dans le RER — corrigé complet en 4 rubriques :**
>
> | Rubrique | Contenu |
> |---|---|
> | **Les faits** | Un hebdomadaire publie **sans son accord** la photo d'une passagère du RER entourée de quatre jeunes hommes, avec la légende « la passagère, pas rassurée, se plonge dans sa lecture et n'en sort pas » |
> | **Le problème juridique** | Comment une personne peut-elle **exiger le respect de sa vie privée et de son droit à l'image** ? |
> | **La règle de droit** | Toute personne a droit au respect de sa vie privée ; ce droit **comprend le respect de son IMAGE**. L'image d'une personne **ne peut être utilisée sans son autorisation**. **Il y a atteinte lorsqu'une personne est photographiée À SON INSU, EN DEHORS DE TOUT ÉVÉNEMENT D'ACTUALITÉ LA CONCERNANT, et que la publication contient des éléments relatifs à sa vie privée** |
> | **La solution** | L'hebdomadaire a **porté atteinte au respect de la vie privée** de Mlle M : elle est **identifiable**, la photo a été prise **à son insu**, elle n'était **pas le sujet d'un fait d'actualité la concernant** (le reportage portait sur la banlieue, pas sur elle), et la légende lui **prête des sentiments** (crainte) et **met en cause son autorité** professionnelle. Elle peut demander des **DOMMAGES-INTÉRÊTS pour PRÉJUDICE MORAL devant le TJ du lieu du siège social de l'hebdomadaire** (ou, au choix, du lieu où le dommage a été subi) |
>
> **Aggravation à souligner :** deux des jeunes hommes **faisaient partie de sa classe** → le préjudice professionnel est renforcé.

## 8.7 Le droit des réseaux sociaux

> **Définition :** un réseau social est un **site Internet permettant aux internautes de se créer une page personnelle afin de partager et d'échanger des informations, des photos ou des vidéos avec leur communauté d'amis et leur réseau de connaissances.**

### ⭐ L'arrêt « ami Facebook ≠ ami » (Cass. 2e civ., récusation d'avocats)

**Faits :** à l'occasion d'une **instance disciplinaire** engagée contre lui, Maître X, avocat au barreau de Paris, dépose une **requête en RÉCUSATION** mettant en cause l'**impartialité** de Maîtres A, B, C et D, membres de la formation de jugement du conseil de l'ordre — au motif qu'ils sont « amis » sur un réseau social.

> **Principe :** « **Le terme d'AMI employé pour désigner les personnes qui acceptent d'entrer en contact par les réseaux sociaux NE RENVOIE PAS à des relations d'amitié au sens traditionnel du terme**, et **l'existence de contacts entre ces différentes personnes par l'intermédiaire de ces réseaux NE SUFFIT PAS à caractériser une PARTIALITÉ particulière**, le réseau social étant **un moyen de communication spécifique entre des personnes qui partagent LES MÊMES CENTRES D'INTÉRÊT, et en l'espèce LA MÊME PROFESSION**. »
>
> **Au cas présent :** pour la Cour de cassation, **un ami sur les réseaux sociaux n'est pas un vrai ami** (au sens personnel). Elle considère qu'il n'existe **aucune forme de partialité** entre Maîtres A, B, C et D et Maître X, et **rejette la demande**.
>
> **Suite de l'affaire :** la Cour de cassation **REJETANT le pourvoi**, **l'affaire est CLOSE. Maître X est DÉFINITIVEMENT DÉBOUTÉ de ses demandes.**
>
> **Précision de méthode :** l'arrêt souligne que « **c'est dans l'exercice de son POUVOIR SOUVERAIN D'APPRÉCIATION** que la cour d'appel a retenu… ». C'est la formule qui signale que la Cour de cassation **ne contrôle pas** l'appréciation des faits.

## 8.8 La communication des données d'identification d'un auteur anonyme

C'est le sujet du **CC2 (page Wikipedia)**. Corrigé détaillé.

**Faits :** une personne crée une page Wikipedia sur une société et son dirigeant, contenant des éléments **malveillants** sur sa vie professionnelle et privée. Une **ordonnance sur requête** enjoint à **Wikimedia Foundation Inc.** de communiquer les **données d'identification** de la personne intervenue sous pseudonyme. La fondation américaine **refuse de s'exécuter** → **assignation en référé**. Wikimedia soutient que « seul le procureur a l'opportunité des poursuites ».

| Question | Réponse |
|---|---|
| **1. Définir l'ordonnance sur requête** | Décision **PROVISOIRE**, rendue par un juge **NON CONTRADICTOIREMENT** (sans que l'adversaire soit préalablement appelé), à la demande d'une seule partie, lorsque les circonstances **exigent qu'elle ne soit pas prise contradictoirement** (nécessité d'un effet de surprise, risque de dépérissement de la preuve). Le requérant doit justifier d'un **MOTIF LÉGITIME**. Elle est **exécutoire au seul vu de la minute** et peut faire l'objet d'un **recours en rétractation** devant le juge qui l'a rendue |
| **2. Définir l'assignation en référé et l'ordonnance de référé** | **L'ASSIGNATION EN RÉFÉRÉ** est l'acte d'huissier par lequel le demandeur cite son adversaire à comparaître devant le **juge des référés** ; c'est une procédure **d'URGENCE** et **CONTRADICTOIRE** (l'adversaire est présent ou appelé). **L'ORDONNANCE DE RÉFÉRÉ** est une **décision PROVISOIRE rendue à la demande d'une partie, l'autre présente ou appelée, dans les cas où la loi confère à un juge QUI N'EST PAS SAISI DU PRINCIPAL le pouvoir d'ORDONNER IMMÉDIATEMENT LES MESURES NÉCESSAIRES** — soit qu'il n'existe **aucune contestation sérieuse**, soit pour faire cesser un **trouble manifestement illicite** ou prévenir un **dommage imminent**. Elle **n'a PAS autorité de chose jugée au principal** |
| **3. Tribunal compétent saisi du principal ?** | Il faut distinguer selon l'action envisagée au fond : ① si l'action est fondée sur le **DÉNIGREMENT** (concurrence déloyale) et oppose des personnes morales → **TRIBUNAL DE COMMERCE** ; ② si elle est fondée sur le **CYBERHARCÈLEMENT** ou la **DIFFAMATION** (délits) → **TRIBUNAL CORRECTIONNEL** ; ③ si elle est fondée sur l'**atteinte à la vie privée / au droit à l'image** du dirigeant (personne physique) → **TRIBUNAL JUDICIAIRE**. **Au cas présent**, l'ordonnance vise expressément « une éventuelle action en **DÉNIGREMENT** ou sur le fondement du **CYBERHARCÈLEMENT** » → **TC pour le dénigrement, tribunal correctionnel pour le cyberharcèlement** |
| **4. Pourquoi le TJ est-il compétent (pour la mesure d'instruction) ?** | Le **TJ** statue sur **toutes les matières de droit privé autres que celles que la loi dévolue à une autre juridiction** (compétence de **droit commun**). La demande de communication de données d'identification est une **MESURE D'INSTRUCTION** sollicitée avant tout procès : le TJ, statuant **sur requête** ou **en référé**, est compétent pour l'ordonner. Le tribunal judiciaire considère que **la communication des données d'identification de l'utilisateur qui crée une page Wikipedia sous pseudonyme constitue une MESURE D'INSTRUCTION LÉGALEMENT ADMISSIBLE, pour laquelle il existe un MOTIF LÉGITIME**, à savoir **une éventuelle action en dénigrement ou sur le fondement du cyberharcèlement**. **Réponse à l'argument de Wikimedia :** l'opportunité des poursuites du procureur concerne l'**action publique** ; elle **n'exclut PAS** l'exercice par la victime de son **action civile** ni la sollicitation d'une mesure d'instruction |

### La compatibilité référé / plainte pénale (cas de l'influenceuse sur X-Twitter)

> **Principe :** « Une personne **diffamée dispose d'un MOTIF LÉGITIME** à se voir communiquer les données permettant d'identifier les auteurs des messages. La demande en communication est fondée **dès lors qu'il existe un RISQUE DE DÉPÉRISSEMENT DE LA PREUVE, en raison du DÉLAI DE CONSERVATION des données.** »
> **Au cas présent :** « Le **dépôt de plainte avec constitution de partie civile N'EST PAS un acte de nature à exclure la possibilité de solliciter une mesure d'instruction**, lorsque l'intervention du juge d'instruction **ne se limite pas** à la recherche de l'auteur des propos litigieux. »
> → **Les deux voies sont CUMULABLES.**

**Quelles données peut-on demander ?**
> « Afin de garantir la **PROPORTIONNALITÉ de la mesure**, le tribunal **LIMITE la demande** aux seules données **détenues par la plateforme** et **UTILES à la réunion des éléments susceptibles de solutionner le litige** :
> **l'ADRESSE IP utilisée, l'IDENTIFIANT DE CONNEXION, la DATE DE CRÉATION DU COMPTE, les NOM ET PRÉNOM ou la RAISON SOCIALE du titulaire, les PSEUDONYMES et l'ADRESSE DE COURRIER ÉLECTRONIQUE.** »
>
> ⚠️ **Retiens la logique :** on **n'obtient jamais tout** ; on obtient le **strict nécessaire** à l'identification. C'est une application du **principe de proportionnalité** (le même qu'en RGPD).

**Rappel de la définition du référé (dans ce contexte) :** « Le référé est une **procédure d'URGENCE CONTRADICTOIRE**, qui permet d'obtenir une **mesure PROVISOIRE** qui ne se heurte à **aucune contestation sérieuse**, ou afin de **faire cesser un trouble illicite ou un dommage imminent**. »

## 8.9 Les avis en ligne : le cas de la dentiste (Google My Business)

**Faits :** une patiente mécontente demande à **sa sœur** de rédiger sur le compte Google My Business de la dentiste un commentaire remettant en cause sa **probité et sa compétence professionnelle** : « Zéro professionnalisme à fuir **arnaqueuse et voleuse**… la **sorcière** qui se cache dans la salle de travail et qui **sait comment encaisser l'argent à toute vitesse**… ».

| Question | Réponse |
|---|---|
| **Tribunal compétent** | **Principe :** le TJ statue sur toutes les matières de droit privé autres que celles dévolues à une autre juridiction. **Toutefois**, s'il s'agit d'un litige relatif aux **injures** ou à une **diffamation**, **qui constituent un délit**, le **TRIBUNAL CORRECTIONNEL** est compétent. **Au cas présent :** le litige portant sur une **diffamation** → **tribunal correctionnel**. *(Nuance à ajouter : la dentiste a saisi le juge des référés du TJ pour obtenir en urgence le retrait de l'avis — le référé et l'action au fond sont deux choses distinctes.)* |
| **Définir l'ordonnance de référé** | Cf. 8.8, Q2 |
| **Décision du tribunal** | **Principe :** une diffamation est **l'allégation d'un fait qui porte atteinte à l'honneur ou à la considération d'une personne**. **Peu importe que le fait soit vrai ou faux, mais il doit être PRÉCIS** pour faire l'objet d'une vérification et d'un débat constructif. **Au cas présent :** les termes « arnaqueuse », « voleuse », « sait comment encaisser l'argent à toute vitesse » imputent des faits précis portant atteinte à la **probité** et à la **compétence professionnelle** → **DIFFAMATION**. Le tribunal a condamné **l'auteure du commentaire, AINSI QUE SA SŒUR QUI L'AVAIT INCITÉE À AGIR** (complicité / provocation), à **SUPPRIMER l'avis publié SOUS ASTREINTE de 300 € PAR JOUR DE RETARD**. Les sœurs verseront à la dentiste **300 € de DI** et **1 690 € au titre des impayés** |

> **Le point à ne pas manquer :** **celle qui incite** est aussi condamnée. En droit de la presse, **les auteurs sont poursuivis comme complices** et la provocation à commettre l'infraction est punissable.

## 8.10 L'attitude d'un salarié : vie privée ou vie de l'entreprise ?

**Faits :** M. X, conseiller commercial, est convié à un **voyage organisé par sa société** pour **récompenser les lauréats d'un concours interne**. À la suite d'incidents (**menaces, insultes, comportements agressifs** envers des collègues et supérieurs), il est **rapatrié** et **licencié pour faute grave**.

| Rubrique | Contenu |
|---|---|
| **Le problème juridique** | Les faits commis à l'occasion d'un **séjour d'agrément, en dehors du temps et du lieu de travail**, relèvent-ils de la **vie privée**, quand bien même des supérieurs hiérarchiques et d'autres salariés sont conviés à ce séjour ? |
| **La règle de droit** | Les **menaces, insultes et comportements agressifs** commis **à l'occasion d'un séjour organisé par l'employeur** dans le but de **récompenser les salariés lauréats d'un challenge interne**, et **à l'égard de collègues ou de supérieurs hiérarchiques**, **SE RATTACHENT À LA VIE DE L'ENTREPRISE** |
| **La solution** | La cour d'appel, qui avait jugé le licenciement **sans cause réelle et sérieuse** en estimant que les faits relevaient de la vie privée, **a violé les textes** → **CASSATION**. Le **licenciement de M. X est JUSTIFIÉ**, le voyage étant considéré comme **professionnel dans son entièreté**. **Suite :** cassation **avec renvoi** → l'affaire est rejugée par **une autre cour d'appel** |

> **La ligne de partage à retenir :** un fait de la **vie personnelle** ne peut en principe **pas** justifier un licenciement disciplinaire… **sauf** s'il **se rattache à la vie de l'entreprise** (séminaire, voyage d'entreprise, repas d'affaires, propos visant des collègues) ou s'il constitue un **manquement à une obligation découlant du contrat** (loyauté, sécurité).

---

# PARTIE 9 — CYBERSÉCURITÉ, CYBERCRIMINALITÉ ET CRYPTOMONNAIES

## 9.1 Les trois statuts d'opérateurs (à ne pas confondre)

| Sigle | Nom | Définition | Points clés |
|---|---|---|---|
| **OIV** | **Opérateur d'Importance Vitale** | Organisation **identifiée par l'ÉTAT** comme ayant des activités **indispensables ou dangereuses pour la population** | Environ **250** OIV, dans **12 secteurs d'activité**. **La liste des OIV n'est PAS publique** |
| **OSE** | **Opérateur de Services Essentiels** | Entité **publique ou privée** qui **fournit un service essentiel (SE)** et qui est **tributaire de réseaux informatiques ou de systèmes d'information**, et **dont l'arrêt aurait un impact significatif sur le fonctionnement de l'économie ou de la société** | L'OSE **s'inscrit dans le prolongement de l'OIV** |
| **FSN** | **Fournisseur de Services Numériques** | **Personne MORALE** qui fournit **tout service de la société de l'information**, c'est-à-dire tout service **à distance, par voie électronique et à la demande individuelle d'un destinataire** | Englobe : les **places de marché**, les **moteurs de recherche** et les **services d'informatique en nuage (cloud)** |

**Les systèmes :**

| Sigle | Nom | Définition |
|---|---|---|
| **SIE** | **Système d'Information Essentiel** | Système d'information sur lequel un **incident de sécurité en DISPONIBILITÉ, INTÉGRITÉ ou CONFIDENTIALITÉ a un EFFET DISRUPTIF IMPORTANT** sur la fourniture des services essentiels identifiés |
| **SIIV** | **Système d'Information d'Importance Vitale** | Système pour lequel l'atteinte à la sécurité ou au fonctionnement **risquerait de diminuer d'une façon importante le POTENTIEL DE GUERRE OU ÉCONOMIQUE, la SÉCURITÉ ou la CAPACITÉ DE SURVIE DE LA NATION**, ou pourrait présenter un **danger grave pour la population**. *Cette définition est très proche de celle du service essentiel* |

## 9.2 Les obligations des FSN

**Objectif :** garantir un niveau de sécurité des **réseaux et systèmes d'information (RSI)** nécessaires à la fourniture de leurs services et **adapté aux risques existants**. Cela implique :
- **identifier les risques** affectant la sécurité de leurs RSI ;
- **prendre des mesures** pour gérer ces risques, **éviter les incidents** de sécurité et en **réduire au minimum l'impact**, de manière à **garantir la CONTINUITÉ de leurs services**.

> **Ces mesures concernent 5 DOMAINES (à savoir lister) :**
> ① la **sécurité des systèmes et des installations** ;
> ② la **gestion des incidents** ;
> ③ la **gestion de la continuité des activités** ;
> ④ le **suivi, l'audit et le contrôle** ;
> ⑤ le **respect des normes internationales**.

## 9.3 Les obligations des OSE

### Un SERVICE ESSENTIEL correspond à 3 critères cumulatifs

1. Le service est **essentiel au maintien d'activités sociétales ou économiques CRITIQUES** ;
2. La fourniture de ce service est **tributaire des réseaux et systèmes d'information** ;
3. Un incident sur ces réseaux et systèmes a un **EFFET DISRUPTIF IMPORTANT** sur la fourniture du service.

### L'identification des SIE : les 4 facteurs transsectoriels

L'évaluation de l'effet disruptif est déterminée en prenant en compte :
1. le **NOMBRE D'UTILISATEURS** tributaires du service ;
2. la **DÉPENDANCE DES AUTRES SECTEURS** à l'égard du service fourni par cette entité ;
3. les **CONSÉQUENCES** que les incidents ont **en termes de DEGRÉ et de DURÉE** sur les fonctions économiques ou sociétales ou sur la **sûreté publique** ;
4. la **PORTÉE GÉOGRAPHIQUE**, eu égard à la zone susceptible d'être touchée par un incident.

### Les 3 obligations de l'OSE

| # | Obligation |
|---|---|
| **1** | **Application des 23 RÈGLES DE SÉCURITÉ** aux systèmes d'information essentiels identifiés par l'OSE |
| **2** | **NOTIFICATION à l'ANSSI** (Agence Nationale de la Sécurité des Systèmes d'Information) des **incidents de sécurité** survenus sur les SIE |
| **3** | **COOPÉRATION de l'OSE en cas de CONTRÔLE par l'ANSSI** |

### Les 23 règles sont structurées suivant 4 DOMAINES

1. La **GOUVERNANCE** de la sécurité des réseaux et systèmes d'information ;
2. La **PROTECTION** des réseaux et systèmes d'information ;
3. La **DÉFENSE** des réseaux et systèmes d'information ;
4. La **RÉSILIENCE** des activités.

### La directive NIS — son champ et sa finalité

> **Toutes les entreprises ne sont PAS concernées par la directive NIS** (*Network and Information Security*). Elle concerne **les OSE et les FSN**. **Tous leurs systèmes d'information ne sont pas non plus concernés** : la directive **ne s'applique qu'aux systèmes d'information déclarés comme ESSENTIELS (SIE)** à la réalisation d'activités essentielles à la Nation.
>
> **Le BUT de ces réglementations (à réciter) :**
> ① **élever le niveau global de la CYBERSÉCURITÉ** ;
> ② permettre aux entreprises et organismes d'**être INDÉPENDANTS des grands noms du secteur du numérique, pour la plupart américains** (souveraineté numérique) ;
> ③ **apporter de la CONFIANCE aux citoyens et aux consommateurs** par l'intégration de la sécurité dans les SIE.

## 9.4 ⭐ LE DROIT DE LA CYBERCRIMINALITÉ

> **Définition :** la cybercriminalité est **l'ensemble des infractions pénales susceptibles de se commettre sur les réseaux de télécommunication**. Elle regroupe **toutes les infractions tentées ou commises à l'ENCONTRE ou AU MOYEN d'un système d'information et de communication.**

**La distinction fondamentale :**
- infractions **CONTRE** un SI (piratage, atteinte au STAD, sabotage) ;
- infractions **AU MOYEN** d'un SI (escroquerie en ligne, usurpation d'identité, harcèlement, diffusion de contenus illicites).

### ⭐ Le tableau des infractions et de leurs peines (à mémoriser)

| Infraction | Définition | Peine |
|---|---|---|
| **Atteinte à un STAD** (Système de Traitement Automatisé de Données) | Accéder ou se maintenir, **FRAUDULEUSEMENT**, dans **tout ou partie** d'un système de traitement automatisé de données | **1 an de prison + 15 000 € d'amende** |
| **Traitement de DCP sans respect des formalités préalables** | Procéder à des traitements de DCP sans qu'aient été respectées les formalités préalables prévues par la loi | **5 ans de prison + 300 000 € d'amende** |
| **Escroquerie** (appliquée à la délinquance informatique) | Le fait, **soit par un FAUX NOM, soit par une FAUSSE QUALITÉ, soit par l'ABUS D'UNE QUALITÉ VRAIE, soit par des MANŒUVRES FRAUDULEUSES**, de **TROMPER** une personne physique ou morale et de la **DÉTERMINER**, à son préjudice ou au préjudice d'un tiers, à **REMETTRE DES FONDS, DES VALEURS OU UN BIEN QUELCONQUE**, à **fournir un service** ou à **consentir un acte opérant obligation ou décharge** | **5 ans + 375 000 €** (droit commun) |
| **Usurpation d'identité** | Usurper l'identité d'un tiers ou faire usage de données permettant de l'identifier, en vue de troubler sa tranquillité ou de porter atteinte à son honneur | **1 an de prison + 15 000 € d'amende** |
| **Refus de remettre une convention secrète de déchiffrement** | Le fait, pour quiconque ayant connaissance de la **convention secrète de déchiffrement d'un moyen de cryptologie** susceptible d'avoir été utilisé pour **préparer, faciliter ou commettre un crime ou un délit**, de **refuser de la remettre aux autorités judiciaires** ou de la mettre en œuvre | **3 ans de prison + 270 000 € d'amende** |
| **Violation du secret des correspondances** (par une personne chargée d'une mission de service public ou un agent d'un exploitant de réseau) | Détournement, suppression ou ouverture de correspondances, ou révélation de leur contenu | **3 ans + 45 000 €** |
| **Violation du droit sui generis des BDD** | Extraction ou réutilisation substantielle non autorisée | **3 ans + 300 000 €** |
| **Violation du RGPD** | Manquement aux dispositions du règlement | **20 M€ ou 4 % du CA mondial** (amende administrative) |

### ⭐ La question piège : « peut-on parler de VOL de données ? »

> **Le VOL est défini comme la SOUSTRACTION FRAUDULEUSE DE LA CHOSE D'AUTRUI.**
>
> **La difficulté :** les données sont un **bien INCORPOREL**. Or, la **soustraction** implique classiquement un **déplacement de la chose**, qui prive le propriétaire de sa possession. Quand on copie des données, **le propriétaire en conserve l'usage** : il n'y a pas de « soustraction » au sens classique.
>
> **La réponse à écrire (nuancée, en deux temps) :**
> ① **Position traditionnelle / difficulté :** le vol, conçu pour les choses corporelles, s'accommode mal de la copie de données, puisque le propriétaire n'en est pas dépossédé.
> ② **Position retenue par la jurisprudence moderne :** la Cour de cassation admet **le vol de données** (et **le vol d'informations**), notamment lorsqu'il y a **copie sur un support** ou **soustraction de la possession, même temporaire**. Elle a par ailleurs consacré le **« vol de fichiers informatiques »**.
> ③ **En tout état de cause**, d'autres qualifications sont **plus sûres** et se cumulent : **atteinte au STAD** (accès et maintien frauduleux, extraction, détention, reproduction ou transmission frauduleuse de données), **abus de confiance** si la personne détenait légitimement les données, **traitement illicite de DCP**, et **recel**.

> **Cas type (M. V qui vole les données bancaires et d'assurance de M. M pour rembourser ses dettes de jeu) :**
> **Q1 — Les chefs d'accusation :**
> - **Atteinte à un STAD** (accès et/ou maintien frauduleux, extraction frauduleuse de données) ;
> - **Vol de données** (avec la nuance ci-dessus) ou à défaut **abus de confiance** ;
> - **CHANTAGE** (le fait d'obtenir, en menaçant de révéler ou d'imputer des faits de nature à porter atteinte à l'honneur ou à la considération, une signature, un engagement, des fonds ou des valeurs) ;
> - **Extorsion** si les fonds ont été effectivement remis sous la contrainte ;
> - **Traitement illicite de DCP** ;
> - éventuellement **usurpation d'identité** et **atteinte à la vie privée**.
> **Q2 — Peut-il être accusé de vol ?** Réponse en deux temps comme ci-dessus. **Le mobile (rembourser des dettes de jeu en ligne) est INDIFFÉRENT** à la qualification : il ne joue qu'au stade de la **personnalisation de la peine**.
> **Q3 — Tribunal :** ce sont des **délits** → **TRIBUNAL CORRECTIONNEL**, territorialement compétent au lieu de l'infraction, de la résidence ou de l'interpellation du prévenu.

### Le cas du logiciel de caisse « permissif »

**Faits :** une société informatique **conçoit et commercialise** un logiciel de caisse permettant aux utilisateurs de **faire disparaître des lignes d'écriture comptables** relatives à des ventes payées **en espèces**, avant arrêté comptable.

**Réponse :**
- **L'atteinte au STAD** (accès/maintien frauduleux) est **discutable pour l'ÉDITEUR** : il n'accède pas frauduleusement au système, il **fournit un outil**. En revanche il y a bien **introduction/suppression frauduleuse de données** dans un STAD par **l'utilisateur** du logiciel.
- **L'éditeur peut être condamné comme COMPLICE** (fourniture de moyens en connaissance de cause) des infractions commises par ses clients : **fraude fiscale**, **faux et usage de faux en écritures comptables**, **passation d'écritures inexactes ou fictives**, **travail dissimulé**.
- Il existe en outre un **délit spécifique** réprimant la **fabrication, la détention et la mise à disposition de LOGICIELS DE COMPTABILITÉ OU DE CAISSE PERMISSIFS**, ainsi qu'une obligation de **certification** des logiciels de caisse.
- **Tribunal correctionnel.**

### ⭐ L'HAMEÇONNAGE (phishing) et la négligence grave du client

> **Définition à donner :** l'**hameçonnage** (ou *phishing*) est une **technique d'ESCROQUERIE** consistant à **usurper l'identité d'un organisme de confiance** (banque, administration, opérateur) au moyen d'un **courriel, d'un SMS ou d'un site contrefait**, afin d'amener la victime à **communiquer volontairement des données confidentielles** (identifiants, mots de passe, coordonnées bancaires, codes) qui seront utilisées à des fins frauduleuses.

**La règle bancaire :** en vertu de **l'article L.133-18 du Code monétaire et financier**, **une banque est tenue de REMBOURSER à son client les opérations réalisées en fraude sur son compte, SAUF FAUTE OU NÉGLIGENCE GRAVE de ce dernier.**

> **Cas type :** un client reçoit plusieurs messages portant le **logo de sa banque**, accompagnés d'un « **certificat de sécurité à remplir attentivement** » qu'il **renseigne scrupuleusement**, allant jusqu'à **demander à sa banque la communication de sa nouvelle carte de clés personnelle** pour pouvoir remplir le certificat. **Plus de 7 000 €** sont soustraits.
>
> **Position de la cour d'appel :** remboursement ordonné — le client a fourni ses données **à son insu**, il n'a pas commis de **négligence grave** en tant que client « normalement attentif », et **ne pouvait percevoir les indices** propres à douter de la provenance des messages.
>
> **Position de la COUR DE CASSATION : CASSATION.** Le client a commis une **NÉGLIGENCE GRAVE**. Les éléments retenus :
> - il a communiqué **ses données personnelles de sécurité personnalisées**, ce qu'aucune banque ne demande jamais ;
> - il est allé jusqu'à **demander activement à sa banque une nouvelle carte de clés** pour pouvoir remplir le prétendu certificat — démarche qui révèle qu'il aurait dû s'interroger ;
> - un client **normalement attentif** aurait dû être alerté par des **indices** (adresse de l'expéditeur, fautes, caractère inhabituel de la demande).
> → **La banque n'a pas à rembourser.**
>
> **Q2 — Y aura-t-il une suite ?** **OUI** : la Cour de cassation **casse et annule**, et **ne jugeant que le droit et non les faits**, elle **renvoie l'affaire devant une AUTRE cour d'appel**.

**Le cas du « maillon » de l'escroquerie (mule financière) :**
> **Faits :** une personne, elle-même victime d'une escroquerie au faux crédit (elle a versé 200 € de frais de dossier puis 5 mandats pour 1 800 €), accepte, pour espérer débloquer son prêt, de **recevoir des sommes de Western Union et des mandats cash et de les reverser** à son contact. Elle comprend qu'elle est **le maillon d'une escroquerie** quand une de ses cibles lui demande à être remboursée. **Tracfin** signale qu'elle a été destinataire de **plus de 124 000 €** et a retransmis **plus de 97 000 €** vers **4 destinataires**.
>
> **Q — Sur quelle infraction principale sera-t-elle jugée et en quelle qualité ?**
> → Infraction principale : **ESCROQUERIE** (et/ou **BLANCHIMENT** / **complicité d'escroquerie**, voire **recel**).
> → **Qualité : COMPLICE** (ou auteur de blanchiment), et **non simple victime**. Le fait d'avoir été elle-même victime **ne l'exonère pas** : elle a **prêté son concours en connaissance de cause** (ou à tout le moins a persisté après avoir compris), ce qui caractérise l'élément intentionnel.
> **Tribunal : correctionnel.**
> *(Rappel : **TRACFIN** = Traitement du Renseignement et Action contre les Circuits FINanciers clandestins ; service de renseignement français chargé de la lutte contre la **fraude fiscale**, le **blanchiment d'argent** et le **financement du terrorisme**.)*

## 9.5 Le droit des crypto-monnaies

> **Définition :** les crypto-monnaies sont des **monnaies électroniques destinées à être échangées sur Internet**. Elles se veulent **plus ou moins sécurisées, privées et intraçables**. Elles s'appuient sur **leur propre réseau d'ordinateurs, qui n'est contrôlé NI par les États NI par les banques**, et qui utilise la **blockchain (chaîne de blocs)** comme protocole Internet.

> **La BLOCKCHAIN est un REGISTRE DISTRIBUÉ ET SÉCURISÉ (sur l'ensemble du réseau), qui garde une TRACE DE TOUTES LES TRANSACTIONS effectuées depuis la création de la crypto-monnaie.**

> **Une crypto-monnaie est un LOGICIEL fondé sur des ALGORITHMES et sur du CODE OPEN SOURCE, le tout reposant sur des techniques avancées de la CRYPTOGRAPHIE pour VALIDER et SÉCURISER les transactions.**
> « Une fois acquise la confiance dans le système, les transactions sont **sécurisées et rapides**, et il devient aussi simple d'envoyer de l'argent à quelqu'un qu'un simple courriel. »

### ⭐ Le cas de la plateforme lituanienne — corrigé complet

**Faits :** un étudiant participe **bénévolement**, au sein d'une **fondation**, au développement d'une technologie blockchain, et a été **membre du conseil d'administration**. En parallèle, il ouvre un **portefeuille de crypto-monnaie** sur lequel il réalise **plus de 200 opérations** ; un an plus tard ses conversions se traduisent par un **gain de 300 000 €**. Il est **victime du piratage** de son compte, qui conduit à un **débit de 300 000 €**. Il met en demeure l'éditeur de la plateforme, **société de droit LITUANIEN**, de l'indemniser, **porte plainte pour escroquerie** et **assigne devant un tribunal FRANÇAIS**. La société lituanienne soulève **l'exception d'incompétence**, en invoquant la **clause attributive de compétence** du contrat *« virtual currency agreement »* désignant **le lieu de son siège social**.

| Question | Réponse |
|---|---|
| **1. Le TJ peut-il être compétent ?** | **OUI**, si l'étudiant est qualifié de **CONSOMMATEUR** (particulier agissant en dehors de son activité professionnelle) et que le litige est **civil**. Le TJ est la juridiction de **droit commun** en matière de droit privé. **L'argument adverse :** la société soutiendra qu'avec **plus de 200 opérations**, un **gain de 300 000 €**, une participation au **CA d'une fondation** blockchain et une expertise technique, il agissait en réalité **à titre professionnel**. |
| **2. Le TC peut-il être compétent ?** | **OUI, mais seulement si** l'on considère que l'étudiant a agi **à titre professionnel / comme commerçant** (activité habituelle, spéculative, réalisée à titre de profession), le litige opposant alors deux professionnels. **La qualification de la QUALITÉ des parties est donc la clé** : consommateur → TJ ; professionnel → TC. |
| **3. Décision du tribunal compétent ?** | Il doit d'abord trancher **l'exception d'incompétence**. Si l'étudiant est un **professionnel**, la **clause attributive de compétence est VALABLE** (elle l'est entre commerçants) → **le tribunal français se déclare incompétent** au profit du tribunal lituanien. S'il est **consommateur**, la clause lui est **INOPPOSABLE**. |
| **4. Décision de la COUR D'APPEL ?** | **Principe :** « **En vertu du RÈGLEMENT EUROPÉEN BRUXELLES I BIS du 12/12/2012, un client d'une plateforme de crypto-monnaie N'EST PAS UN PROFESSIONNEL MAIS UN CONSOMMATEUR, ce qui permet à ce dernier d'ASSIGNER LE RESPONSABLE DU SITE AU LIEU DE SON DOMICILE.** » **Solution :** la cour d'appel **écarte la clause attributive de compétence**, **retient la compétence du tribunal FRANÇAIS** du **domicile du consommateur**, et **rejette l'exception d'incompétence** soulevée par la société lituanienne. |

> **Ce qu'il faut retenir de ce cas :** le règlement **Bruxelles I bis** protège le consommateur en lui permettant d'agir **chez lui**, et neutralise les clauses attributives insérées dans les CGU des plateformes étrangères. C'est **exactement le même raisonnement** que dans l'affaire Booking — sauf que là, le problème n'était pas la compétence mais **la qualité pour défendre** (mauvaise société assignée).

## 9.6 Le régime des plateformes face aux escroqueries (rappel)

Cf. Partie 6.14 — l'analyse **éditeur / hébergeur** s'applique intégralement. Ajoute, en cybersécurité, l'**obligation de mise en garde** : l'absence d'avertissement sur les **risques de parasitage de contenus** et la présentation ambiguë des informations engagent la responsabilité de la plateforme.

---

# PARTIE 10 — FICHES MÉMO (à relire la veille et le matin)

## FICHE 1 — Le réflexe « QUEL TRIBUNAL ? » en 30 secondes

```
Infraction pénale ? ────► contravention → TRIBUNAL DE POLICE
                          délit         → TRIBUNAL CORRECTIONNEL
                          crime         → COUR D'ASSISES
                          (territorial : lieu des faits / résidence / interpellation)

Administration ? ───────► TRIBUNAL ADMINISTRATIF → CAA → CONSEIL D'ÉTAT

Relation de travail ? ──► CONSEIL DE PRUD'HOMMES (lieu de l'établissement)

Propriété intellectuelle
(civil) ? ──────────────► TRIBUNAL JUDICIAIRE spécialisé PI

Deux commerçants /
acte de commerce /
entreprise en difficulté ► TRIBUNAL DE COMMERCE (siège social du défendeur)

Tout le reste ──────────► TRIBUNAL JUDICIAIRE (domicile du défendeur)

┌─────────────────────────────────────────────────────────────┐
│ ≤ 5 000 € → 1er ET DERNIER ressort → PAS D'APPEL             │
│ > 5 000 € → APPEL possible devant la cour d'appel            │
└─────────────────────────────────────────────────────────────┘
```

**Ne jamais oublier :** ① compétence d'attribution **ET** ② compétence territoriale.

## FICHE 2 — Les durées et les chiffres

| Notion | Chiffre |
|---|---|
| Brevet | **20 ans** non renouvelable |
| Dessin & modèle | **5 ans** × 5 = **25 ans** max |
| Marque | **10 ans** renouvelable **indéfiniment** |
| Droit patrimonial d'auteur | **70 ans** après le décès |
| Droit moral | **Perpétuel** |
| Taux de ressort (appel) | **5 000 €** |
| Rétractation e-commerce | **14 jours** |
| Notification violation données à la CNIL | **72 heures** |
| Conservation images vidéosurveillance | **1 mois** max |
| Amende RGPD | **20 M€ ou 4 % du CA mondial** |
| Atteinte au STAD | **1 an + 15 000 €** |
| Usurpation d'identité | **1 an + 15 000 €** |
| Traitement DCP sans formalités | **5 ans + 300 000 €** |
| Refus de remettre une clé de déchiffrement | **3 ans + 270 000 €** |
| Violation droit sui generis BDD | **3 ans + 300 000 €** |
| Violation secret des correspondances (agent) | **3 ans + 45 000 €** |
| Prescription des délits de presse | **3 mois** |
| Règles de sécurité OSE | **23 règles**, **4 domaines** |
| Mesures de sécurité FSN | **5 domaines** |
| OIV | ~**250**, **12 secteurs**, liste **non publique** |

## FICHE 3 — Les 3 vices du consentement

| Vice | Mécanisme | Doit porter sur |
|---|---|---|
| **ERREUR** | Croyance fausse **spontanée** | Les **qualités essentielles de la chose** OU **la personne** (intuitu personae). ❌ Pas la valeur, pas les motifs |
| **VIOLENCE** | Contrainte | Crainte d'un **mal considérable et actuel** pour soi, ses proches, ses biens. Physique / morale / **économique** |
| **DOL** | **Tromperie** de l'autre partie | **Manœuvres, mensonges, RÉTICENCE (silence)**. Il faut : ① intention de nuire ② manœuvres **déterminantes** |

→ Sanction : **NULLITÉ RELATIVE**, effet **rétroactif** (sauf contrats à exécution successive → **résiliation**).

## FICHE 4 — Contrefaçon / Concurrence déloyale / Parasitisme

| | Contrefaçon | Concurrence déloyale | Parasitisme |
|---|---|---|---|
| **Fondement** | Droit de PI (titre ou œuvre) | Art. 1240 C. civ. (faute) | Art. 1240 C. civ. |
| **Condition** | Un **droit privatif valable** + reproduction | **Faute + préjudice + lien de causalité** | Tirer profit des **efforts d'autrui sans rien dépenser** |
| **Concurrence exigée ?** | Non | Oui en principe | **NON** |
| **Tribunal** | **TJ** (civil) / **correctionnel** (pénal) | **TC** | **TC** |
| **Quand l'utiliser ?** | Le titre est valable et copié | Débauchage, détournement, confusion, dénigrement | **Quand la contrefaçon échoue faute d'originalité** ← le filet de sécurité |

## FICHE 5 — Obligation de moyen / de résultat

| | Moyen | Résultat |
|---|---|---|
| **Le débiteur promet** | de **tout mettre en œuvre** | d'**atteindre un résultat** |
| **Qui prouve ?** | Le **créancier** prouve la négligence | Le **résultat manquant suffit** |
| **Exonération** | Absence de faute | **Force majeure** seulement |
| **Exemples TIC** | Information, mise en garde, **conseil** ; opérateur télécom ; maintenance (diligence) | **Délivrance** du logiciel ; sécurité de l'organisateur ; livraison conforme |
| **Critère** | Le créancier a un **rôle actif** / il y a un **aléa** | Le créancier est **passif** / pas d'aléa |

## FICHE 6 — Le RGPD en une page

```
DCP = info relative à une PP identifiée ou identifiable, DIRECTEMENT ou INDIRECTEMENT
      → l'ADRESSE IP EST une DCP

TRAITEMENT = toute opération (collecte, conservation, consultation, effacement...)

EXCLUSION : activités EXCLUSIVEMENT personnelles ou domestiques
            (mais bannières pub / monétisation → on RENTRE dans le champ)

ACTEURS :  Responsable = décide FINALITÉS + MOYENS
           Sous-traitant = agit POUR LE COMPTE et SUR INSTRUCTIONS
           → 3 obligations du ST : transparence/traçabilité + privacy by design + sécurité
           DPD = garant, INDÉPENDANT, aucune instruction, non pénalisable

DONNÉES INTERDITES : race/ethnie, opinions politiques, religieuses, philosophiques,
                     appartenance syndicale, santé, vie sexuelle
                     → AUTORISATION CNIL (pas simple déclaration)
                     → un DPD ne dispense PAS de cette obligation

CONSENTEMENT : libre + spécifique + éclairé + univoque
               = information préalable, accord par traitement, indépendance, révocabilité

PRINCIPES : finalité déterminée / minimisation (adéquates, pertinentes, NON EXCESSIVES)
            / durée limitée / exactitude / sécurité / transparence / PROPORTIONNALITÉ

DROITS : information, accès, rectification, opposition, EFFACEMENT (oubli),
         PORTABILITÉ, limitation, non-profilage

FORMALITÉS : registre (responsable ET sous-traitant), notification violation 72h,
             AIPD obligatoire si : profilage / données sensibles à grande échelle /
             surveillance à grande échelle d'une zone publique

SANCTION : 20 M€ ou 4 % du CA annuel mondial
```

## FICHE 7 — Diffamation / Injure / Dénigrement

```
Imputation d'un FAIT PRÉCIS portant atteinte à l'honneur d'une PERSONNE
   → DIFFAMATION → délit → CORRECTIONNEL → la VÉRITÉ exonère

Expression outrageante SANS imputation de fait
   → INJURE → délit → CORRECTIONNEL
      publique (compte ouvert) / non publique (cercle restreint, SMS)
      excuse de PROVOCATION : personnelle + directe + fautive + proportionnée + proche

Discrédit sur les PRODUITS / SERVICES d'une entreprise
   → DÉNIGREMENT → CIVIL → TRIBUNAL DE COMMERCE
      ⚠ peu importe que l'info soit EXACTE
      ⚠ pas besoin d'être concurrent
```

## FICHE 8 — Éditeur / Hébergeur

| Hébergeur | Éditeur |
|---|---|
| Prestataire **technique** : serveur + interface | **Rôle ACTIF** : connaissance et contrôle du contenu |
| Responsable seulement **s'il savait et n'a pas retiré** | Responsable **de plein droit** |
| **Pas d'obligation générale de surveillance** | Assimilé au directeur de la publication |

**Indices du rôle actif :** valide les inscriptions · fixe le contenu · évalue la pertinence · retire des contenus · classe/recommande · attribue des statuts · **perçoit une commission**.

## FICHE 9 — Les formules qui rapportent des points

Recopie-les telles quelles, elles sont issues des corrigés :

1. « **L'existence d'un contrat de travail ne dépend ni de la volonté des parties, ni de la dénomination qu'elles ont donnée à leur convention, mais des conditions de fait dans lesquelles s'exerce l'activité.** »
2. « Le lien de subordination est caractérisé par **l'exécution d'un travail sous l'autorité d'un employeur qui a le pouvoir de donner des ordres et des directives, d'en contrôler l'exécution et de sanctionner les manquements**. »
3. « **Les fichiers créés par un salarié à partir de l'outil informatique mis à sa disposition par l'employeur sont présumés professionnels, sauf s'ils sont identifiés comme étant personnels.** »
4. « **Une clé USB, dès lors qu'elle est connectée à un outil informatique mis à disposition par l'employeur pour l'exécution du contrat de travail, est présumée utilisée à des fins professionnelles.** »
5. « **Une contrepartie financière dérisoire à la clause de non-concurrence équivaut à une absence de contrepartie.** »
6. « **Le risque de confusion doit être examiné au terme d'une appréciation globale des marques, et non de la seule similitude des noms.** »
7. « **L'originalité est l'effort créatif portant l'empreinte de la personnalité de l'auteur.** »
8. « **Sauf stipulation contraire, le logiciel créé par un ou plusieurs employés dans l'exercice de leurs fonctions appartient à l'employeur, auquel sont dévolus tous les droits reconnus aux auteurs.** »
9. « **Les adresses IP, qui permettent d'identifier indirectement une personne physique, sont des données à caractère personnel.** »
10. « **L'épuisement du droit de distribution concerne à la fois les copies matérielles et immatérielles d'un logiciel.** »
11. « **Le débiteur n'est tenu que des dommages et intérêts qui ont été prévus ou qui pouvaient être prévus lors de la conclusion du contrat, sauf faute lourde ou dolosive.** »
12. « **La charge de la preuve incombe au demandeur ; réciproquement, celui qui se prétend libéré de son obligation doit le prouver.** »
13. « **La divulgation d'une information de nature à jeter le discrédit sur un concurrent constitue un dénigrement, peu importe qu'elle soit exacte.** »
14. « **Il n'existe ni droit de l'Internet, ni droit des réseaux sociaux, mais une application des autres droits à l'Internet et aux réseaux sociaux.** »
15. « **La Cour de cassation jugeant le droit et non l'affaire, elle renvoie l'affaire devant une nouvelle cour d'appel.** »
16. « **Le contrat est maintenu, mais la clause est réputée non écrite.** »
17. « **On parle de non-professionnel lorsque l'un des cocontractants agit en dehors de son domaine d'activité, ou se trouve dans la même situation d'ignorance qu'un consommateur.** »
18. « **Le pénal tient le civil en l'état** » et « **le pénal l'emporte sur le civil**. »

---

# PARTIE 11 — CORRIGÉS INTÉGRAUX DES CC

## 11.1 CC1 2023-2024 — corrigé commenté

### I) Juridiction compétente (Mme M / M. C, reconnaissance de dette de 15 000 €)

**Rappel des faits :** Mme M exploite un fonds de commerce à Pau, y est domiciliée. Elle a emprunté **15 000 €** à son **concubin** M. C **pour financer l'achat d'un VÉHICULE PERSONNEL**. Reconnaissance de dette simple, **sans modalité de remboursement**, passée en présence d'une vendeuse. Séparation ; M. C, ayant déménagé à **Toulouse**, réclame le remboursement immédiat.

> **Principe :** le **tribunal judiciaire** est compétent pour les **litiges entre particuliers**. La juridiction **territorialement compétente** est celle du **lieu où demeure le DÉFENDEUR**. Il peut aussi s'agir du tribunal du **lieu de la livraison de la chose** ou du **lieu d'exécution de la prestation de service**.
>
> **Au cas présent :** M. C, **particulier**, assigne Mme M **qui a agi dans le cadre de ses INTÉRÊTS PRIVÉS** (achat d'un véhicule **personnel**, et non pour son commerce). Il s'agit donc d'un **litige entre particuliers**, relevant de la compétence du **TRIBUNAL JUDICIAIRE**. M. C saisira le tribunal du **domicile du défendeur** ou du **lieu de l'engagement** : **le tribunal judiciaire de PAU**, car Mme M y est domiciliée et l'acte a été passé dans les locaux professionnels, à la même adresse.

> ⚠️ **LE PIÈGE À COMPRENDRE, car il se répète :** Mme M **EST commerçante**. Le réflexe serait de dire « tribunal de commerce ». **C'EST FAUX.** Ce qui compte n'est pas la **qualité** de la personne, mais **l'OBJET DE L'ACTE** : ici un prêt personnel pour une voiture personnelle → **acte civil** → **TJ**.
> **La variable que le prof manipule :** *à quoi servait l'argent ?* Si le prêt avait servi à **financer le stock du magasin** ou des **travaux du fonds de commerce**, l'acte serait **commercial** → **TC**.
> **Autres variables :** si le montant avait été **≤ 5 000 €** → jugement en premier et dernier ressort, **pas d'appel**. Ici **15 000 € > 5 000 €** → **appel possible**.
> **Bonus à ajouter :** la reconnaissance de dette **ne prévoit aucune modalité de remboursement** → le prêt est **à durée indéterminée** ; le juge peut **fixer un délai** raisonnable de remboursement. Le remboursement « immédiat » n'est donc **pas automatique**. La présence d'un **témoin** (Mlle E) sert la **preuve** de l'acte.

### II) Brevetabilité des logiciels

> **Q1 — Tribunal compétent ?**
> **Principe :** en matière de litiges entre entreprises, le **TC** est compétent ; néanmoins, **si le litige porte sur les droits de propriété intellectuelle, le TRIBUNAL JUDICIAIRE est compétent**. *(Et si l'on poursuit la contrefaçon comme délit, le tribunal correctionnel.)*
> **Au cas présent :** s'agissant d'un litige relatif à la **propriété intellectuelle (un BREVET)**, le **TRIBUNAL JUDICIAIRE** — spécialement désigné en matière de brevets — est compétent.
>
> **Q2 — Décision ?**
> **Principe :** une description d'un procédé revendiqué **se bornant à affirmer l'objet sans préciser les MOYENS TECHNIQUES mis en œuvre**, **ne détaillant que les RÉSULTATS et les POSSIBILITÉS OFFERTES À L'UTILISATEUR**, sans mentionner les **caractéristiques techniques** du moteur de recherche lui-même, **NE RÉPOND PAS à la définition d'un brevet**. L'invention est réalisable **de façon totalement intellectuelle, sans nécessiter la moindre mise en œuvre de moyen technique**.
> **Au cas présent :** **le brevet est ANNULÉ pour DÉFAUT DE BREVETABILITÉ**, et **non** sur la base d'une **absence d'activité inventive** (fondement pourtant souvent retenu par les tribunaux). **Conséquence :** l'action de la société S se retourne contre elle — non seulement il n'y a **pas de contrefaçon** (aucun droit valable n'a été violé), mais **elle perd son titre**.

### III) Protection de la personne au travail (la clé USB)

> **Q — Le chef d'entreprise peut-il s'appuyer sur ce moyen de preuve ?**
> **Principe :** « **Une clé USB, dès lors qu'elle est connectée à un outil informatique mis à la disposition du salarié par l'employeur pour l'exécution du contrat de travail, est PRÉSUMÉE UTILISÉE À DES FINS PROFESSIONNELLES ; l'employeur peut avoir accès aux fichiers NON IDENTIFIÉS COMME PERSONNELS qu'elle contient, HORS LA PRÉSENCE DU SALARIÉ.** »
> **Au cas présent :** **la clé USB étant le PROLONGEMENT de l'outil informatique**, le chef d'entreprise **peut consulter les fichiers non identifiés comme « personnels »** et les **produire comme moyen de preuve LICITE**. Les agissements (enregistrement d'informations confidentielles sur l'entreprise et de documents personnels de collègues et du dirigeant) sont **constitutifs d'une cause réelle et sérieuse de licenciement pour FAUTE LOURDE**, dont la preuve peut être apportée au moyen des fichiers extraits de la clé USB restée connectée au poste informatique.
> **Solution procédurale :** la cour d'appel qui avait exigé la présence de la salariée a **violé les textes** → **CASSATION** dans toutes ses dispositions, **remise des parties dans l'état antérieur**, renvoi.
>
> ⚠️ **Les variables du prof sur cette question :**
> - **Clé USB NON connectée** (dans un sac, un tiroir) → **pas de présomption professionnelle** → preuve **illicite**.
> - **Fichiers identifiés « personnel »/« privé »** sur la clé → l'employeur ne peut y accéder qu'**en présence du salarié** ou après l'avoir appelé.
> - **Ordinateur personnel** du salarié → **inviolable** sans son accord.
> - **Téléphone personnel** → même régime.
> - **Charte informatique** imposant une dénomination précise → cf. Partie 3.6.3.

## 11.2 CC1 2024-2025 — corrigé complet

### I) Juridiction compétente (Mme M à Belfort / SARL S à Dijon)

**Analyse du litige :** le litige oppose Mme M, **commerçante** exploitant une boutique de prêt-à-porter à Belfort, et la **SARL S** située à Dijon, entrepreneur ayant réalisé des travaux d'aménagement **dans son magasin**. Le conflit porte sur des **travaux inachevés** et des **malfaçons**.

> **COMPÉTENCE MATÉRIELLE :** il s'agit d'un **litige commercial opposant deux parties commerçantes dans le cadre de leur activité professionnelle**. En effet :
> - **Mme M est commerçante** (exploitation d'une boutique de prêt-à-porter) ;
> - **La SARL S est une société commerciale PAR LA FORME** ;
> - **Le contrat de travaux a été conclu dans le cadre de l'activité professionnelle** de Mme M (aménagement de **son magasin**).
>
> Conformément aux **articles L.721-1 et suivants du Code de commerce**, **LE TRIBUNAL DE COMMERCE est compétent** pour connaître des litiges entre commerçants relatifs à leurs activités commerciales.
>
> **COMPÉTENCE TERRITORIALE :** selon **l'article 42 du Code de procédure civile** (et l'art. 46), la juridiction territorialement compétente est, **AU CHOIX DU DEMANDEUR** :
> - celle du **lieu où demeure le défendeur** → siège de la SARL S = **DIJON** ;
> - celle du **lieu de livraison effective de la chose** → lieu des travaux = **BELFORT** ;
> - celle du **lieu d'exécution de la prestation de service** → lieu des travaux = **BELFORT**.
>
> **RÉPONSE :** la juridiction compétente est le **TRIBUNAL DE COMMERCE**. Mme M pourra, **à son choix**, saisir **le TC de DIJON** (siège social de la SARL S) **ou le TC de BELFORT** (lieu d'exécution des travaux).

> **Comparaison instructive avec le CC1 2023-2024 :** même structure de question, **résultat inverse**. Ici les travaux sont faits **dans le magasin** → **acte commercial** → **TC**. Là-bas, le prêt servait à acheter **une voiture personnelle** → **acte civil** → **TJ**. **C'est exactement la variable que le prof manipule.**
>
> **Bonus à ajouter pour gagner des points :** le fond du litige relève de l'**inexécution contractuelle** (travaux inachevés) et de la **garantie des vices cachés / de conformité** (malfaçons). Mme M peut demander l'**exécution forcée**, la **réduction du prix**, la **résolution** du contrat et des **dommages-intérêts**. Le refus du gérant d'intervenir avant six mois, sans motif légitime, caractérise un **manquement à l'obligation d'exécuter de bonne foi**. Elle devra adresser une **mise en demeure** préalable.

### II) Similitude de marques (My Luxury Travel / My Luxury Voyage)

**Rappel :** en N-10, **My Luxury Travel** dépose la marque **semi-figurative** « Luxury » pour des services liés au voyage. En N-6, **My Luxury Voyage** dépose la marque semi-figurative « My Luxury Voyage » pour **les mêmes activités**. My Luxury Travel assigne en contrefaçon et **est DÉBOUTÉE**.

> **Q1 — Tribunal compétent ?**
> Le litige porte sur une **action en contrefaçon de marque semi-figurative**. Conformément à **l'article L.716-3 du Code de la propriété intellectuelle**, les **actions civiles en contrefaçon de marque relèvent de la COMPÉTENCE EXCLUSIVE de TRIBUNAUX JUDICIAIRES SPÉCIALEMENT DÉSIGNÉS** pour connaître des litiges en matière de propriété intellectuelle.
> **RÉPONSE : le TRIBUNAL JUDICIAIRE spécialisé en propriété intellectuelle est compétent.**
> *(À ajouter : territorialement, le TJ du domicile du défendeur ou du lieu du fait dommageable ; et si l'action était portée au pénal, le tribunal correctionnel.)*
>
> **Rappel utile à placer :** « La **marque semi-figurative** comprend **deux types d'éléments : un élément VERBAL et un élément FIGURATIF**. Il peut s'agir d'un logo accompagné d'un nom, mais aussi d'un terme à la calligraphie ou au graphisme particulier. Cette forme de marque **s'avère utile lorsque l'élément verbal n'est pas ou peu distinctif**. »

> **Q2 — Décision rendue par le tribunal ?**
>
> **Analyse (ce que le tribunal a constaté) :**
> - La marque **My Luxury Travel était VALIDE malgré son caractère TRÈS FAIBLEMENT DISTINCTIF** ;
> - **Le raisonnement circulaire :** s'il devait consacrer le manque de distinctivité de la marque en litige **du seul fait du signe verbal**, cela aurait pour conséquence de **consacrer AUSSI celui de la marque My Luxury Voyage** ;
> - Le tribunal a ensuite apprécié la contrefaçon alléguée **en comparant les marques DANS LEUR ENSEMBLE** ;
> - Leur comparaison met en lumière leur **SIMILITUDE CONCEPTUELLE** (« Travel » et « Voyage » sont synonymes).
>
> **Application du droit :** selon **l'article L.713-3 du CPI**, porte atteinte aux droits du titulaire d'une marque l'usage, **dans la vie des affaires, d'un signe similaire ou identique pour des produits ou services identiques ou similaires, lorsqu'il existe un RISQUE DE CONFUSION dans l'esprit du public**.
>
> **RÉPONSE :** au regard de ces seuls éléments — services **identiques**, **similitude conceptuelle**, faible distinctivité de la marque antérieure — **le tribunal devrait reconnaître la CONTREFAÇON** et condamner My Luxury Voyage.
> **CEPENDANT**, selon le cas présenté, **My Luxury Travel A ÉTÉ DÉBOUTÉE**, ce qui suggère que le tribunal a considéré que, **malgré la similitude conceptuelle, D'AUTRES ÉLÉMENTS — NOTAMMENT LES ÉLÉMENTS FIGURATIFS — permettaient de distinguer suffisamment les deux marques pour éviter le risque de confusion**, conformément à la méthode de **l'appréciation globale**.
>
> ⚠️ **Comment traiter cette question sans se tromper :** l'énoncé dit « **a été déboutée** ». **Tu dois donc expliquer POURQUOI**, tout en montrant que les éléments plaidant en sens inverse existaient. Structure : « Les éléments X, Y, Z plaidaient pour la contrefaçon ; MAIS le tribunal, appliquant l'appréciation globale, a retenu que les éléments figuratifs distincts et le très faible caractère distinctif de l'élément verbal excluaient le risque de confusion pour le consommateur moyen. »

> **Q3 — Sur quel argument le tribunal pourrait-il rendre une décision INVERSE ?**
>
> **Argument 1 — Élément verbal prédominant :** si le tribunal avait considéré que **l'élément VERBAL** (« My Luxury Voyage » vs « My Luxury Travel ») est l'**élément DOMINANT** de la marque, rendant les éléments figuratifs **secondaires dans la perception du public**.
> **Argument 2 — Risque de confusion avéré :** le tribunal aurait pu estimer que la **similitude conceptuelle** (« Travel » = « Voyage »), **combinée aux SERVICES IDENTIQUES**, crée un **risque de confusion dans l'esprit du CONSOMMATEUR MOYEN**, même en présence d'éléments figuratifs distincts.
> **Argument 3 — Appréciation globale insuffisante :** le tribunal aurait pu considérer qu'en dépit de l'appréciation globale, **les SIMILITUDES l'emportent sur les DIFFÉRENCES**, notamment du fait du **faible caractère distinctif initial**, qui rend toute imitation plus susceptible de créer une confusion.
> **Argument 4 — Antériorité de la marque :** My Luxury Travel ayant été déposée **4 ans avant** (N-10 vs N-6), le tribunal aurait pu considérer que My Luxury Voyage a cherché à **tirer profit de la notoriété ou de la réputation acquise** par la marque antérieure (parasitisme).
>
> *(Argument 5 possible en bonus : **absence d'argument** sur la **similitude phonétique** et sur le **public pertinent** — le tribunal n'a peut-être pas caractérisé qui est le consommateur moyen de services de voyage de luxe, plus attentif que la moyenne.)*

### III) Permis de conduire en ligne (plateforme et moniteurs)

> **Q1 — Tribunal compétent ? Pourquoi ?**
> **Nature du litige :** il porte sur la **QUALIFICATION JURIDIQUE de la relation** entre la société S et les moniteurs : s'agit-il d'un **contrat de travail** (lien de subordination) ou d'un **contrat commercial** (travailleur indépendant) ?
> **Compétence :** si la relation est **requalifiée en contrat de travail**, la compétence revient au **CONSEIL DE PRUD'HOMMES**, conformément à **l'article L.1411-1 du Code du travail**, qui dispose que le CPH **règle les différends INDIVIDUELS entre employeurs et salariés**.
> **RÉPONSE : le CONSEIL DE PRUD'HOMMES est compétent**, car il s'agit d'un contentieux portant sur **l'existence ou non d'un lien de subordination caractérisant un contrat de travail**. *(Territorialement : le CPH du lieu de l'établissement où le travail est accompli, ou à défaut du domicile du travailleur.)*
> ⚠️ **Le raisonnement à écrire :** le CPH est compétent **pour STATUER SUR SA PROPRE COMPÉTENCE**, c'est-à-dire pour dire s'il y a ou non contrat de travail. Ce n'est pas parce qu'on conclura à l'absence de subordination qu'il était incompétent.

> **Q2 — Tableau des 3 indices**

| **INDICE** | **FAIT CONSTATÉ** | **ANALYSE** |
|---|---|---|
| **1. Fixation unilatérale des tarifs** | Les **tarifs horaires sont fixés unilatéralement par la société S**, qui reverse la rémunération aux moniteurs | **INDICE DE SUBORDINATION :** le moniteur **ne peut pas négocier sa rémunération**, ce qui suggère un **pouvoir de direction** de l'employeur |
| **2. Liberté dans l'organisation du travail** | Les moniteurs choisissent librement le **nombre d'heures**, leurs **horaires**, leur **secteur géographique** ; ils peuvent **renoncer** à des prestations sans **objectif quantitatif imposé** ; ils peuvent **travailler pour d'autres structures agréées** | **INDICE D'INDÉPENDANCE :** grande liberté d'organisation **incompatible avec un lien de subordination**. Le moniteur **maîtrise son temps** et peut exercer **pour plusieurs clients** |
| **3. Pouvoir de sanction limité** | Pouvoir de sanction en cas d'**annulation tardive (< 48 h)** ou de **mauvaise évaluation**, mais ces clauses sont **dépourvues de prérogative hiérarchique** ; **pas de pouvoir de contraindre à modifier ses pratiques** | **INDICE D'INDÉPENDANCE :** les sanctions visent **simplement à assurer l'exécution contractuelle, comme dans toute relation commerciale**. **Absence de pouvoir hiérarchique** |

> *(Si le prof demande un 4e indice, ajoute : **« Évaluation et suivi du taux de réussite »** → fait constaté : la société se réserve le droit de suivre le taux de réussite par enseignant → analyse : **indice ambigu**, qui pencherait vers la subordination, **mais** ces clauses sont **« dépourvues de prérogative hiérarchique permettant de contraindre un moniteur à modifier ses pratiques »** → **indice d'INDÉPENDANCE**. Ou encore : **« Fourniture des instruments de travail »** → les moniteurs disposent de **leur propre véhicule à double commande** et de **leur propre agrément** → **indice fort d'INDÉPENDANCE**.)*

> **Q3 — Décision du tribunal (principe, au cas présent) ?**
>
> **PRINCIPE JURIDIQUE :**
> Selon **l'article L.8221-6 du Code du travail**, il existe une **PRÉSOMPTION DE NON-SALARIAT** pour les personnes inscrites au registre du commerce, au répertoire des métiers, ou auprès d'une URSSAF en tant que travailleur indépendant.
> Cependant, selon la **jurisprudence constante de la Cour de cassation** (arrêt de principe : **Cass. soc., 19 décembre 2000, n° 98-40.572, « Société Labbane »**), **l'existence d'un contrat de travail ne dépend NI de la volonté des parties, NI de la dénomination qu'elles ont donnée à leur convention, MAIS DES CONDITIONS DE FAIT dans lesquelles s'exerce l'activité.**
> **Le lien de subordination** est caractérisé par l'exécution d'un travail **sous l'autorité d'un employeur qui a le pouvoir de donner des ordres et des directives, d'en contrôler l'exécution et de sanctionner les manquements**.
>
> **APPLICATION AU CAS PRÉSENT :**
>
> *Éléments en faveur de l'indépendance (PRÉDOMINANTS) :*
> - **liberté totale** dans le choix du **nombre d'heures** et des **horaires** ;
> - possibilité de **travailler pour d'autres structures concurrentes** ;
> - choix du **secteur géographique** d'intervention ;
> - **absence d'objectifs quantitatifs** imposés ;
> - **pouvoir de sanction limité** à l'exécution contractuelle, **sans prérogative hiérarchique** ;
> - **pas de pouvoir de contraindre** le moniteur à modifier ses **pratiques pédagogiques** ;
> - **statut d'indépendant** et **présomption de non-salariat**.
>
> *Éléments pouvant suggérer une subordination :*
> - **fixation unilatérale des tarifs** par la société S ;
> - **évaluation par les candidats** et **suivi du taux de réussite**.
>
> **RÉPONSE : le Conseil de prud'hommes devrait REJETER la requalification en contrat de travail.**
>
> **MOTIFS :**
> - l'**absence de lien de subordination** est caractérisée par la **très grande liberté d'organisation** laissée aux moniteurs ;
> - les moniteurs conservent une **maîtrise totale de leur activité** (horaires, volume, clientèle) ;
> - la société S **n'exerce aucun pouvoir hiérarchique** ni de contrôle sur les **méthodes pédagogiques** ;
> - **la fixation unilatérale des tarifs, bien qu'elle soit un indice, N'EST PAS SUFFISANTE À ELLE SEULE** pour caractériser un lien de subordination, **surtout au regard de la liberté d'organisation accordée** ;
> - le fonctionnement correspond à celui d'une **plateforme de MISE EN RELATION entre professionnels indépendants et clients**, modèle économique **reconnu par la jurisprudence récente**.
>
> **CONCLUSION :** les moniteurs **conservent leur statut de travailleurs indépendants**. **La relation contractuelle ne sera PAS requalifiée en contrat de travail.**

> ⚠️ **LES VARIABLES QUE LE PROF PEUT INVERSER SUR CE CAS — entraîne-toi à basculer la réponse :**
>
> | Si l'énoncé dit… | Alors… |
> |---|---|
> | Les moniteurs **ne peuvent pas** travailler pour d'autres structures (clause d'exclusivité) | Indice **fort** de subordination |
> | La société **impose les horaires** et le **planning** | Subordination |
> | La société **fournit le véhicule** à double commande | Subordination (fourniture des instruments de travail) |
> | La société **impose une méthode pédagogique** ou des **contenus de cours** | Subordination (directives sur le contenu) |
> | La société **impose un objectif** de X heures/mois | Subordination |
> | La société peut **désactiver le compte** en cas de taux de réussite insuffisant | **Pouvoir disciplinaire** → subordination |
> | La société **attribue** les élèves sans que le moniteur puisse refuser | Subordination (clientèle imposée) |
> | Le moniteur est **noté** et **déclassé** algorithmiquement, avec baisse de commandes | Subordination (contrôle + sanction) |
> | → Dans ces cas : **REQUALIFICATION en contrat de travail** | Conséquences : application du droit du travail, **rappel de salaires**, **indemnités de rupture**, **travail dissimulé** (pénal), régularisation URSSAF |

## 11.3 CC2 2024-2025 — corrigé complet

### I) Communication des données d'identification (page Wikipedia)

→ **Corrigé intégral en Partie 8.8.** Les 4 questions y sont traitées : définition de l'ordonnance sur requête ; définition de l'assignation et de l'ordonnance de référé ; tribunal saisi du principal (TC pour le dénigrement / correctionnel pour le cyberharcèlement) ; compétence du TJ pour la mesure d'instruction + réfutation de l'argument de Wikimedia sur l'opportunité des poursuites.

### II) Contrefaçon de logiciel (société S / société X)

**Rappel des faits :** la société S accuse la société X de contrefaçon de son logiciel L lors d'opérations de **maintenance** chez un client. X a été créée **en N-2 par 3 anciens salariés** de S (partis en N-3) qui avaient travaillé sur ces logiciels. S obtient **2 ordonnances en saisie-contrefaçon** et assigne. **MAIS :**
- S **ne démontre PAS être titulaire des droits d'auteur** sur le logiciel à la date des faits, en raison de l'apposition d'un **copyright désignant une AUTRE société** ;
- S **ne se réserve PAS par contrat la MAINTENANCE CORRECTIVE** de son logiciel → **le client est en droit de faire réaliser cette maintenance par X** ;
- S **ne prouve PAS** que cette intervention implique le recours aux **codes sources** ;
- X a développé **sa PROPRE solution logicielle**, dont l'**originalité et le caractère innovant sont CORROBORÉS PAR L'EXPERT** en informatique ayant assisté l'huissier pendant la saisie-contrefaçon ;
- S **échoue à prouver** les faits de **concurrence déloyale par dénigrement** de X ;
- S **est condamnée à indemniser la défenderesse** pour avoir présenté, **comme ACQUIS EN JUSTICE**, à plusieurs **clients communs**, le principe d'une contrefaçon **sur la base de simples ordonnances de saisie-contrefaçon**.

| Question | Réponse |
|---|---|
| **1. Définir la « concurrence déloyale par DÉNIGREMENT »** | La **concurrence déloyale** désigne un **abus de pratique commerciale d'une entreprise par rapport à une autre** ; elle est constituée de l'ensemble des **procédés concurrentiels contraires à la loi ou aux usages, constitutifs d'une FAUTE**. Le **DÉNIGREMENT** est le fait d'**attaquer la réputation** de quelqu'un, de **le noircir, le discréditer, parler avec malveillance, le calomnier**. **La concurrence déloyale par dénigrement** consiste donc à **jeter publiquement le DISCRÉDIT sur les produits, les services ou la personne d'un concurrent, afin de détourner sa clientèle**. **Elle exige** : ① une **FAUTE** (les propos dénigrants) ② un **PRÉJUDICE** ③ un **LIEN DE CAUSALITÉ**. ⚠️ **Peu importe que l'information divulguée soit EXACTE**, et **une situation de concurrence directe n'est même pas exigée**. **Fondement :** art. 1240 C. civ. — **c'est une faute CIVILE, pas une infraction**. **Tribunal : le TRIBUNAL DE COMMERCE.** |
| **2. Tribunal compétent ?** | **Principe :** en matière de litiges entre entreprises, le **TC** est compétent ; **sauf si le litige porte sur la propriété intellectuelle, ce qui rend le TJ compétent** ; toutefois, s'il s'agit d'une **action en contrefaçon** visant à faire cesser une contrefaçon **qui est un délit**, le **tribunal correctionnel** est compétent. **Au cas présent — DEUX volets :** ① pour la **CONTREFAÇON de droit d'auteur sur le logiciel et de la marque L** → **TRIBUNAL JUDICIAIRE spécialisé en PI** (au civil) ou **tribunal correctionnel** (au pénal, qui statuerait alors sur le civil **et** le pénal) ; ② pour la **CONCURRENCE DÉLOYALE par dénigrement** et pour la **demande reconventionnelle** de X → **TRIBUNAL DE COMMERCE**. *(En pratique, lorsque les demandes sont connexes, le TJ saisi de la contrefaçon peut connaître de la concurrence déloyale qui en découle.)* |
| **3. Décision du tribunal ?** | **La société S sera DÉBOUTÉE de l'ensemble de ses demandes**, et **CONDAMNÉE sur la demande reconventionnelle de X.** **Motifs, point par point :** ① **DÉFAUT DE TITULARITÉ** — S **ne démontre pas être titulaire des droits d'auteur à la DATE DES FAITS LITIGIEUX**, en raison de l'apposition sur le logiciel d'un **copyright désignant une autre société**. Or **il appartient au demandeur à l'action en contrefaçon de PROUVER SA TITULARITÉ** ; à défaut, son action est **irrecevable / mal fondée**. ② **LICÉITÉ DE LA MAINTENANCE** — S **ne s'étant pas réservé par contrat la MAINTENANCE CORRECTIVE**, **le client est EN DROIT de la faire réaliser par un tiers**. ③ **ABSENCE DE PREUVE DE LA REPRODUCTION** — S **ne prouve pas** que l'intervention de X **impliquait le recours aux CODES SOURCES** de son logiciel. **Rappel : la charge de la preuve pèse sur le demandeur.** ④ **ORIGINALITÉ DE LA SOLUTION DE X** — X a développé **sa propre solution**, dont l'**originalité et le caractère innovant sont corroborés par l'EXPERT** ayant assisté l'huissier. **Sans reproduction, pas de contrefaçon.** ⑤ **ÉCHEC SUR LA CONCURRENCE DÉLOYALE** — S **ne prouve pas** les faits de dénigrement qu'elle impute à X. **⚠️ Précision importante :** le fait que les 3 fondateurs de X soient d'**anciens salariés** de S **n'est PAS fautif en soi** : la **liberté du travail** et la **liberté du commerce et de l'industrie** autorisent d'anciens salariés à créer une entreprise concurrente, **sauf clause de non-concurrence valable, débauchage massif ou détournement de clientèle** — non établis ici. |
| **4. À quelles sanctions s'expose la société S ?** | **① CONDAMNATION POUR PROCÉDURE ABUSIVE / DÉNIGREMENT (le point central) :** S est **condamnée à INDEMNISER LA DÉFENDERESSE** pour avoir **présenté, COMME ACQUIS EN JUSTICE, à plusieurs CLIENTS COMMUNS, le principe d'une contrefaçon SUR LA BASE DE SIMPLES ORDONNANCES DE SAISIE-CONTREFAÇON**. **C'EST LE CŒUR DU SUJET :** une **ordonnance de saisie-contrefaçon n'est qu'une MESURE PROBATOIRE, une AUTORISATION de constater** — **elle NE CONSTITUE PAS une décision reconnaissant la contrefaçon**. Présenter cette mesure comme un jugement acquis auprès de clients communs constitue un **acte de DÉNIGREMENT** et de **concurrence déloyale** → **DOMMAGES-INTÉRÊTS** au profit de X. **② DÉBOUTÉ** de toutes ses demandes (pas d'interdiction, pas de DI). **③ NULLITÉ / RÉTRACTATION des ordonnances de saisie-contrefaçon** et **restitution** des éléments saisis. **④ DÉPENS et ARTICLE 700 du CPC** (frais irrépétibles) à sa charge. **⑤ Éventuellement PUBLICATION judiciaire** de la décision, aux frais de S, pour réparer l'atteinte à l'image de X auprès des clients communs. **⑥ Le cas échéant, AMENDE CIVILE pour procédure abusive** si la mauvaise foi est caractérisée. |

> ⚠️ **La leçon de méthode de ce cas :** c'est un cas de **RETOURNEMENT COMPLET**. Le demandeur, qui pensait attaquer, se fait condamner. **Repère toujours dans l'énoncé les phrases négatives** : « ne démontre pas », « ne se réserve pas », « ne prouve pas », « échoue à prouver ». **Chacune est une raison de débouter**, et le prof les a écrites exprès. Compte-les : il y en a **cinq**. Il y a donc **cinq motifs** à écrire.

### III) Conditions de validité du contrat (Jeanne Hultou)

→ **Corrigé intégral en Partie 6.11.**

**Réponse en une phrase pour la conclusion :** *La vente de la peau tatouée de Jeanne n'est PAS juridiquement valable : le corps humain et ses éléments sont hors du commerce et ne peuvent faire l'objet d'un droit patrimonial ; la clause, qui a un objet illicite et contraire à l'ordre public, est frappée de NULLITÉ ABSOLUE et réputée non écrite ; Jeanne ne peut être contrainte de subir l'opération.*

---

# PARTIE 12 — BANQUE DE VARIANTES : « ET SI LE PROF CHANGE X ? »

C'est la partie que tu m'as demandée explicitement : **un exemple par valeur possible de chaque variable**.

## 12.1 Variable « qualité des parties » → compétence

| Demandeur | Défendeur | Objet | Tribunal |
|---|---|---|---|
| Particulier | Particulier | Prêt personnel | **TJ** |
| Commerçant | Commerçant | Travaux dans le magasin | **TC** |
| Commerçant | Commerçant | Contrefaçon de logiciel | **TJ** spécialisé PI (ou correctionnel) |
| Commerçant | Commerçant | Dénigrement / débauchage | **TC** |
| Particulier | Société | Litige de consommation | **TJ ou TC** au choix ; ou TJ du domicile du consommateur |
| Société | Particulier | Impayé | **TJ** |
| Salarié | Employeur | Licenciement, clause, preuve | **CPH** |
| Indépendant | Plateforme | Requalification | **CPH** (il statue sur sa compétence) |
| Contribuable | Administration fiscale | Avis d'imposition | **TA** |
| Employeur | Inspection du travail | Refus d'autorisation de licenciement | **TA** |
| Victime | Auteur d'un délit | Vol, escroquerie, injure, STAD | **Tribunal correctionnel** |
| Consommateur | Plateforme étrangère | Piratage de compte | **TJ du domicile du consommateur** (Bruxelles I bis) |

## 12.2 Variable « à quoi servait l'acte ? » → nature civile ou commerciale

| L'acte sert à… | Nature | Tribunal |
|---|---|---|
| Acheter une **voiture personnelle** | **Civile** | TJ |
| Aménager **son magasin** | **Commerciale** | TC |
| Financer **le stock** du commerce | **Commerciale** | TC |
| Acheter **la maison de famille** | **Civile** | TJ |
| Équiper **le SI de l'entreprise** | **Commerciale** | TC |
| Un usage **mixte** (privé et pro) | L'acte est **commercial pour le commerçant, civil pour le particulier** → le particulier a l'**option** |

## 12.3 Variable « quel titre de PI ? » → régime applicable

| Objet du litige | Titre | Durée | Formalité | Tribunal |
|---|---|---|---|---|
| Une **invention technique** | **Brevet** | 20 ans | Dépôt INPI | TJ spécialisé |
| Un **logiciel** | **Droit d'auteur** (jamais brevet) | 70 ans post mortem | Aucune (dépôt APP = preuve) | TJ spécialisé |
| L'**apparence** d'un produit | **Dessin & modèle** | 5 × 5 = 25 ans | Dépôt INPI | TJ spécialisé |
| Un **nom, logo, slogan** | **Marque** | 10 ans renouvelable | Dépôt INPI | TJ spécialisé (L.716-3) |
| La **structure** d'une base | Droit d'auteur (si originale) | 70 ans | Aucune | TJ |
| Le **contenu** d'une base | **Droit sui generis** | 15 ans | Aucune (investissement substantiel) | TJ |
| Des **photos** non originales | **Aucun** droit d'auteur | — | — | **Parasitisme → TC** |
| Un **savoir-faire** non protégé | **Aucun** titre | — | — | **Concurrence déloyale → TC** |

## 12.4 Variable « quel vice / quelle sanction contractuelle ? »

| Le sujet dit… | Qualification | Sanction |
|---|---|---|
| Le vendeur **a caché** un accident | **Réticence dolosive** | Nullité relative + restitutions |
| Le vendeur **a menti** sur les performances | **Dol (mensonge)** | Nullité relative |
| L'acheteur **s'est trompé** seul sur la nature du bien | **Erreur** sur les qualités essentielles | Nullité relative |
| L'acheteur a fait **une mauvaise affaire** | **Erreur sur la valeur** | ❌ **Pas de nullité** |
| Le contrat a été signé **sous la menace** | **Violence** | Nullité relative |
| Le signataire est **mineur** | **Incapacité** | Nullité relative (confirmation possible par les parents) |
| L'objet est **hors du commerce** (corps humain, fichier non déclaré) | **Objet illicite** | **Nullité ABSOLUE** |
| Le salarié signataire **n'avait pas de délégation** | **Défaut de pouvoir** | Annulation, sauf **ratification** ou **mandat apparent** |
| La clause exonère **totalement** un pro face à un non-pro | **Clause abusive / léonine** | **Réputée non écrite**, contrat maintenu |
| La clause **limite** la responsabilité entre pros, sans vider l'obligation essentielle | **Clause valable** | Elle s'applique (cf. Oracle : 230 000 € au lieu de 70 M€) |
| Le défaut rend la chose **impropre à son usage**, était **caché** et **antérieur** | **Vice caché** | Action **rédhibitoire** / **estimatoire** / DI |
| Le prestataire a **tardé** à corriger les pannes | **Inexécution contractuelle** | Résiliation + DI |
| Le client **n'a pas fait le recettage** alors qu'il avait les accès et des CGV claires | **Faute du client** | **Rejet de ses demandes** |

## 12.5 Variable « quel type de propos ? » → qualification et tribunal

| Le sujet dit… | Qualification | Tribunal |
|---|---|---|
| « C'est une **voleuse**, une **arnaqueuse** » | **Diffamation** (fait précis, atteinte à la probité) | Correctionnel |
| « Espèce de **connard**, de **goujat** » | **Injure** | Correctionnel (publique) / Police (non publique) |
| « Leur **logiciel** est bugué, leurs **cours** ne servent à rien » | **Dénigrement** | **TC** |
| Propos sur un **compte ouvert à tous** | Injure/diffamation **PUBLIQUE** | Correctionnel |
| Propos dans un **groupe fermé de 5 amis sélectionnés** | Injure **NON PUBLIQUE** | Tribunal de police |
| Propos par **SMS** à la victime seule | Injure **NON PUBLIQUE** | Tribunal de police |
| Avis négatif posté par le **frère d'un concurrent** | **Dénigrement** (le mobile concurrentiel emporte la qualification) | **TC** |
| Article de presse portant sur un **sujet d'intérêt général** avec **base factuelle suffisante** | Diffamation, mais **exception de BONNE FOI** possible | Correctionnel |

## 12.6 Variable « quelle preuve ? » → licéité

| Support | Licite ? |
|---|---|
| Fichiers professionnels sur PC pro | ✅ |
| Fichiers « personnel » conformes à la charte | ⚠️ En présence du salarié / après l'avoir appelé / risque particulier |
| Fichiers mal nommés (charte non respectée) | ✅ |
| **Clé USB connectée** au PC pro, fichiers non personnels | ✅ **hors présence** du salarié |
| Clé USB **non connectée** | ❌ |
| **SMS** reçus | ✅ (pas d'exploitation à l'insu) |
| **Enregistrement téléphonique clandestin** | ❌ (déloyal) |
| **Messenger** ouvert spontanément | ❌ (secret des correspondances) |
| Photos dans un **tiroir** puis fouille des fichiers « perso » | ❌ (pas de risque particulier) |
| **Géolocalisation** alors qu'un autre moyen existe | ❌ |
| **Vidéosurveillance** sans information ni affichage | ❌ |
| **Adresse IP** collectée sans formalité | ❌ (à l'époque : rend la preuve caduque) |

## 12.7 Variable « qui est responsable de la donnée ? »

| Situation | Qualification |
|---|---|
| Une entreprise gère **son** fichier clients | **Responsable du traitement** |
| Un hébergeur stocke les données de son client | **Sous-traitant** |
| Une agence marketing route des mails pour un client | **Sous-traitant** |
| La même agence gère **son propre** personnel | **Responsable du traitement** |
| L'administrateur d'une **page fan** Facebook | **Responsable CONJOINT** avec Facebook |
| Un éditeur d'app avec un **SDK** de collecte | **Responsable** (finalités) ; l'éditeur du SDK peut être responsable conjoint |
| Un salarié qui consulte un fichier | Ni l'un ni l'autre : **personne agissant sous l'autorité** du responsable |

## 12.8 Variable « quel est le statut de la plateforme ? »

| Le sujet dit… | Statut | Conséquence |
|---|---|---|
| Elle **héberge** simplement des contenus, sans les regarder | **Hébergeur** | Responsable seulement après **notification** non suivie de retrait |
| Elle **valide** les inscriptions et **fixe** le contenu des annonces | **Éditeur** | Responsable **de plein droit** |
| Elle attribue des **statuts** (« superhost »), classe, recommande | **Éditeur** | Idem |
| Elle **perçoit une commission** sur les transactions | Indice fort d'**éditeur** | Idem |
| Elle est rémunérée **au clic** et détourne le trafic d'une marque | Éditeur + **concurrence déloyale** | DI |
| Elle **n'avertit pas** des risques de parasitage de contenus | Éditeur + **manquement à l'information** | Responsabilité engagée |
| Elle est une **filiale** sans pouvoir de représentation selon les CGU | **Défaut de qualité pour défendre** | Il faut assigner la société **mère étrangère** |

## 12.9 Variable « quelle infraction cyber ? »

| Le sujet décrit… | Infraction | Peine |
|---|---|---|
| Se connecter au SI d'autrui sans droit | **Atteinte au STAD** | 1 an + 15 000 € |
| Rester connecté après avoir découvert l'accès par erreur | **Maintien frauduleux** dans un STAD | 1 an + 15 000 € |
| Effacer / modifier des données | Atteinte au STAD **aggravée** (altération) | Peines aggravées |
| Faux mail bancaire pour obtenir des codes | **Hameçonnage → ESCROQUERIE** | 5 ans + 375 000 € |
| Se faire passer pour quelqu'un en ligne | **Usurpation d'identité** | 1 an + 15 000 € |
| Refuser de donner la clé de chiffrement à la justice | **Refus de remettre une convention secrète** | 3 ans + 270 000 € |
| Copier une base de données concurrente | **Droit sui generis** | 3 ans + 300 000 € |
| Traiter des DCP sans formalités préalables | Délit du Code pénal | 5 ans + 300 000 € |
| Recevoir et reverser des fonds d'escroquerie | **Blanchiment / complicité d'escroquerie** | Correctionnel |
| Vendre un logiciel de caisse permissif | **Complicité de fraude fiscale**, délit spécifique | Correctionnel |

## 12.10 Les 12 questions les plus probables + la première phrase de la réponse

| Question | Ta première phrase |
|---|---|
| **Quel tribunal est compétent ?** | « Une compétence se décompose en compétence d'attribution et compétence territoriale. **Principe :** … » |
| **Quelle sera la décision ?** | « **Principe :** [règle]. **Au cas présent :** … » |
| **Y aura-t-il une suite ?** | « La Cour de cassation ne jugeant que le droit et non les faits, elle renvoie l'affaire devant une autre cour d'appel. » / « Le pourvoi étant rejeté, l'affaire est close. » |
| **Définir X** | Donne la **définition exacte du cours**, puis un exemple, puis la conséquence juridique. |
| **Relever 3 indices de subordination** | Fais le **tableau à 3 colonnes** : Indice / Fait constaté / Analyse. |
| **La clause est-elle valable ?** | « **Principe :** une clause de X est licite si elle réunit les conditions suivantes… Ces critères sont **cumulatifs**. » |
| **Cette preuve est-elle recevable ?** | « **Principe :** les fichiers créés avec l'outil informatique de l'employeur sont présumés professionnels, sauf… » |
| **Y a-t-il contrefaçon ?** | « **Principe :** la contrefaçon suppose ① un droit privatif valable ② une reproduction ou imitation ③ sans autorisation. » |
| **Y a-t-il concurrence déloyale ?** | « **Principe :** l'action exige une faute, un préjudice et un lien de causalité. » |
| **Le RGPD s'applique-t-il ?** | « Il faut vérifier successivement : l'existence d'une DCP, d'un traitement, et l'application territoriale. » |
| **Sur quel argument une décision inverse ?** | Liste **3 à 4 arguments numérotés**, chacun avec son fondement. |
| **À quelles sanctions s'expose X ?** | Liste **civiles** (nullité, DI, restitution, publication), **pénales** (amende, prison), **administratives** (CNIL), **procédurales** (dépens, art. 700). |

---

## ✅ CHECKLIST DE LA VEILLE

- [ ] Je sais redessiner **le schéma de l'organisation judiciaire** (3 colonnes, 3 niveaux).
- [ ] Je récite l'**arbre de décision du tribunal compétent** sans hésiter.
- [ ] Je connais le **taux de ressort : 5 000 €**.
- [ ] Je distingue **rejet / cassation avec renvoi / cassation sans renvoi**.
- [ ] Je récite la définition du **lien de subordination** + l'arrêt **Labbane**.
- [ ] Je connais les **4 conditions cumulatives** de la clause de non-concurrence.
- [ ] Je sais que **le logiciel n'est PAS brevetable** et pourquoi.
- [ ] Je récite **L.113-9 CPI** (logiciel du salarié → employeur).
- [ ] Je distingue **droit d'auteur / droit sui generis** sur les bases de données.
- [ ] Je connais les **durées** : 20 / 25 / 10 / 70 ans.
- [ ] Je sais que **l'adresse IP est une DCP**.
- [ ] Je connais les **72 heures**, les **20 M€ / 4 %**, le **1 mois** de vidéosurveillance.
- [ ] Je distingue **diffamation / injure / dénigrement** et je sais que **la vérité n'exonère pas du dénigrement**.
- [ ] Je distingue **injure publique / non publique** selon le **verrouillage** du compte.
- [ ] Je distingue **éditeur / hébergeur** et je connais les **indices du rôle actif**.
- [ ] Je distingue **obligation de moyen / de résultat** et je sais **qui prouve quoi**.
- [ ] Je connais les **3 vices du consentement** et la **réticence dolosive**.
- [ ] Je sais que le **corps humain est hors du commerce** → **nullité absolue**.
- [ ] Je connais la règle de **l'épuisement des droits** (UsedSoft) et ses **2 restrictions**.
- [ ] J'écris **TOUJOURS** « Principe » puis « Au cas présent ».
