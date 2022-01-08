## 0/ Intro
Bonjour c’est moua
Je suis n Prépa
MP2I
J’adore les Math et l’informatique !!!
Depuis la sixième en autodidacte
Ouais j’ai aussi une chaîne youtube et twitch
Chuis pas un expert donc si y’a des problèmes n’hésitez pas à me dire !
Regarde la description pour d’éventuelles corrections
Trop bien moi aussi !
Nan à toi l’honneur
Nanan j’insiste !
Hehe merci

## 1) Comment faire une langue mathématique ?

### A) Les langues

On peut ? non => toujours des subtilité en français.
Une langues transmet de l'information (langua des signes, expressions facilae, français). On va créé une langue écrite => alphabet de symboles.
Pour transmettre de l'information => besoin de règles
Comment définir les règles ? Avec une autre langue (ici on défini les mathématiques en français)
2 moyen de définir une langue :
 - Avec une autre langue (souvent langue parlé stylé français)
 - Avec des exemples (le français est appris avec des exemple de phrase lors de l'enfance)

### B) Alphabet, règles et axiomes des mathématiques
On veut étudier et créé des phrases en mathématiques. Il faut des règles pour construire des phrases.
On va différencier 2 type de règles :
 - Règles du langage (règle d'introduction / destruction des opérateurs logique)
 - Axiomes (phrase du langage considéré vrai, qui utilisé selon les règles d'introduction et destruction permetteront d'établir des théorèmes

## 2) Les fondement de la logique

### A) Les propositions
= tout ce que l'on peut dire en math. (différent de tout ce qui est prouvable).
Donne des exemples 

$54+9$

On peut utiliser des proposition entre guillemet => permet d'`eval` en python un texte en math. On peut utiliser du français dans une proposition, si le français est traductible en mathématique sans ambiguïté.
Très important la notion de proposition : Chaque théorème est résumable en une proposition. Un axiom est une proposition aussi (donc vraie)
On peut voir les proposition comme des phrases :
 - Une proposition fausse corresponderait à une phrase fausse
 - Un anssemblage de terme mathématique n'est pas forcément une proposition (tout comme une asemblage de mot n'est pas forcément une phrase ("Je manger présent ornithorynque")
.

### B) Définir les opérateurs
On va inventer des symboles permettant de donner des relations entre des propositions.
$A\implies B$
Règles d'introduction :
 - Le ET : Si on a 2 propositions A, B, vraie, on peut avoir la proposition A ET B. 
 - Le OU : Si on a une proposition A vraie, on pêut avoir la proposition A OU B, ou B est n'importe quelle proposition
 - => : Si en ayant une proposition A on obtient une proposition B, on a A => B
Notter différence entre ou mathématique et ou français. Introduire le ou exclusif.
Ceci sont des règles entre des propositions. Les propositions primaires = axiomes
Règles de destruction :
 - Le ET: Si on a une proposition A ET B vraie, on peut avoir une proposition A vraie et une propoisition B vraie
 - L'=> : Si on a une proposition A => B vraie et une porposition A, on a une proposition B
 - Le OU : Si on a une proposition A OU B vraie, une proposition A => C et une porposition B => C, on en déduit une proposition C
Parresse complexes, parceque elle le sont ! Manières de simplifier tout ça

D'autre sopérateur définie avec ceux si : A=> B et B=> A est la même chose que A <=> B
$A \implies B$

### C) Le vrai, le faux, la négation
Une proposition que l'on invente aussi c'est le vrai. L'équivalent de "Cette phrase dis vrai" en fraçais, la tautologie.
$\lnot A$
La règle d'introduction est "de rien, j'en conclu la tautologie"
On à un équivalent inverse ! Le paradoxe.
 - Du paradoxe, je déduit n'importe quelle proposition A. On le note "faux"
On défini la négation de P comme => faux, car si P implique un paradoxe, alors P est faux

## 3/ La logique classique

### A) La galère des règles d'inférence
pas grand chose à dire, c'est galère. Et pourtant non, on le voit dans les raisonnement (disjonction des cas = création de deux application pour le OU etc) Dans les raisonnement, on utillise les règles dinférence etc mais dans le résumer d'un théorème c'est galère



### B) Notre premier axiome
"P ou non P" "non non P <=> P" aka Tout proposition est vraie ou fausse (Tiers-exclu). Nous permet de simplifier une compréhension des propositions. 
Table de vérité : Comme tout est vrai ou faux, chaque opérateur à une table de vérité. Idée de test tout les combinaisons. Peut facilement déterminer si une proposition est vrai ou fausse à l'aide de ça. Ici que commence la prépa (on voit pas ce que je viens de faire avant)
$$
P \lor \lnot P
$$
$$
P \iff \lnot \lnot P
$$
Expliquer la table de vérité de l'implication (casse tete)

### C) L'absurde et la contraposé
Si on assume que tout V/F => on peut en déduire le raisonnement par l'absurde (basiquement non A => faux donc non non A (définition du non) donc par le tiers exclu A)
Contraposée aussi
On peut passer par table de vérité mais chiant xD

$$
(\lnot P \implies \bot ) \implies P
$$
$$
(P \implies Q) \iff (\lnot Q \implies \lnot P)
$$

## 4/ Théorie des ensembles

### A) Créé des objets
On peut utilliser que des propositions et des opérateur, très faible. Besoin de créé des objets plus intéressant pour modéliser des comportements. Il faut un objet permettant de tout simuler
Cet objet = l'ensemble. Explication de ce qu'es un ensemble (contiens des objets deux à deux non égaux)

### B) Ajoute de appartient et de pour tout
Explication de appartient et de son fonctionnement
Explication de pour tout (pour tout sur vide = vrai)
Explication de il existe
Exemple avec des propriétés style pour tout nombre x dans {4,0,-2}, (x-4)\*(x+2)x = 0

$$
\forall x, x\in \{1,2\} \implies x \in \{0,1,2,3,4\}
$$
$$
\exists x, x\in \{1,2\} \land x \in \{2,3\}
$$
$$
\exist x, \in A
$$

### C) Les axiomes
10 axiomes (certains + important que d'autres)
 - axiome de compréhension
 - axiome de l'ensemble vide
 - axiome d'extensionalité

$$
\exist A,\forall x, \lnot (x \in A)
$$
$$
\forall A,\forall B, [\forall x, x \in A \iff x \in B] \implies A = B
$$
Soit P une propriété
$$
\forall A, \exist B, [\forall x, P(x) \iff x \in A ]
$$

## 5/ Une preuve !!!
Racine de 2 est irrationnel pour expliquer les raisonnements
Toute partie borné de N admet un minimum et un maximum pour les ensembles
