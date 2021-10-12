---
title: Formation Veille documentaire Master NSA
subtitle: Comment faire de la veille et trouver de l'information sur un sujet
author: Damien Belvèze
---
Objectifs :

- vérifier une allégation
- connaître quelques sources d'information utiles dans la discipline (droit + sciences de la santé)
- débuter une revue de littérature
- automatiser sa Veille

# introduction au cours

On se contente de se présenter et d'indiquer les objectifs de la séance.

## la matière de départ : un extrait d'interview

Note pour l'animateur (pas nécessaire à dire pendant la séance) :
Thinkerview est un média web qui réalise des formats longs (2 ou 3 heures) d'entretiens avec des personnalités proposées par la communauté (au moins en partie)
Cette chaîne est tenue par des professionnels qui ne se disent pas journalistes (plutôt assez critiques à l'égard de la manière dont l'information est calibrée et vendue aujourd'hui) et qui sont proches des milieux hackers.
Pour en savoir un peu plus sur cette chaîne, consulter la vidéo de Victor Ferry qui mentionne notamment cette entretien avec Christophe Brusset.

La vidéo qui sert d'introduction est disponible en streaming [depuis le serveur de Rennes 1](https://video.univ-rennes1.fr/videos/extrait-dune-interview-de-christophe-brusset-thinkerview/#share). Cette vidéo capture uniquement les trois minutes utiles pour le cours (mais tout l'entretien est très intéressant à suivre sur Thinkerview).

Si la formation a lieu en présentiel, il suffit de jouer cette vidéo sur un logiciel lecteur de vidéo (VLC par exemple)

Si la formation a lieu à distance, il faut prendre les précautions suivantes pour donner aux étudiants la meilleure expérience possible lors de la séance. Il s'agit notamment d'éviter des problèmes de synchronisation.
Que l'on joue la vidéo depuis un lecteur en local sur VLC ou bien depuis un site en ligne comme [celui-ci](https://video.univ-rennes1.fr/videos/extrait-dune-interview-de-christophe-brusset-thinkerview), la vidéo doit être décodée en amont une première fois puis elle l'est une deuxième fois lorsqu'elle est présentée à travers Teams (envoi de la machine locale aux serveurs de Microsoft) et elle l'est une troisième fois quand les étudiantsy assistent depuis leur ordinateur à travers leur connexion à Teams

![circuit encodage / décodage de la vidéo](images/circuit.png)

Pour diffuser la vidéo en temps réel aux étudiants et s'assurer qu'ils pourront l'entendre suffisamment bien même avec un débit moyen, suivre la méthode indiquée dans [ce tutoriel](https://techcommunity.microsoft.com/t5/microsoft-mechanics-blog/how-to-present-videos-in-microsoft-teams-meetings-without-lag/ba-p/2482107)

ouvrir powerpoint en ligne, créer une diapositive et y insérer une vidéo en entrant l'[URL de la vidéo sur Youtube à partir du moment où elle est pertinente pour le cours](https://youtu.be/lXXp-PVQ0HQ?t=1051)
au moment de la séance où vous l'avez prévu, jouer [cette vidéo](https://uniren1-my.sharepoint.com/:p:/g/personal/damien_belveze_univ-rennes1_fr/EUk-TAkdRyJLhVJ9H5iIXA4B3omcCn8ywVYk46h65q2tyQ?e=oBBq53) depuis powerpoint.

## poser la problématique

Poser la question aux étudiants :
*quelles questions posent selon vous cette allégation de Christophe Brusset ?*

Réponses possibles :

1. est-il vrai que le droit distingue des autres additifs les auxiliaires technologiques et écarte ces derniers de l'obligation de déclaration sur l'emballage (= question de vérification de l'information)
1. y a t-il une différence autre que formelle et juridique entre additifs et auxiliaires technologiques (cette différence a t-elle un sens du point de vue biologique) = question exploratoire
2. S'il n'y en a pas, quel risque  l'ingestion de ces additifs non déclarés font courir aux consommateurs ? = autre question exploratoire.

on va d'abord traiter la première question et vérifier si dans le droit européen cette différence entre additifs (à déclarer) et auxiliaires technologique (qu'on peut ne pas déclarer) existe ou pas.
Quelle réglement européen gère cette différence de statut entre additif et auxilaire technologique ?
Question sous-jacente : où en ligne trouver le droit européen ?

note: [le travail a déjà été fait](https://captainfact.io/videos/gl7D?statement=3579) par les fact-checkers qui font partie des habitués de la chaîne Thinkerview

# recherche juridique

sur le site https://eur-lex.europa.eu
entrer les mots-clé suivants : "additifs alimentaires" étiquetage "auxiliaires technologiques"
filtrer par la forme de document "réglement"
On obtient 18 résultats. On va plutôt chercher des textes génériques et éliminer tout ce qui comporte des éléments un peu spécifique qui réduisent le champ de la question (aluminium, animaux, emballage plastique, agriculture bio)
Restent deux résultats avec un niveau de généralité satisfaisant :

- [1169/2011](https://eur-lex.europa.eu/legal-content/FR/TXT/?uri=CELEX%3A32011R1169&qid=1634059092820)
- [1133/2008](https://eur-lex.europa.eu/legal-content/FR/TXT/?uri=CELEX%3A32008R1333&qid=1634059092820)

chercher dans les deux textes avec Ctrl+F "auxilaires technologiques"

C'est le réglement 1133/2008 qui nous donne la solution. Le texte indique que les additifs doivent être déclarés sur l'emballage MAIS que les auxiliaires technologiques ne sont pas compris dans cette obligation :

> Les substances qui ne sont pas consommées comme aliments en tant que tels mais qui sont délibérément utilisées dans la transformation d’aliments, ne subsistent qu’à l’état de résidu dans le produit final et n’ont aucun effet technologique sur celui-ci (auxiliaires technologiques) n’entrent pas dans le champ d’application du présent règlement. (article 6)


# introduction à la veille

Poser la questionn de l'évolution de la réglementation européenne sur le sujet des additifs.
Si la loi change, comment en serai-je informé ?
Comment faire pour que l'information vienne à moi et non le contraire.

Expliquer avec un schéma comment le flux d'information peut-être inversé du site web vers l'utilisateur.

notion de flux. Définition d'un flux RSS

Demander aux étudiants de charger l'[extension Feedbro](https://nodetics.com/feedbro/) dans leur navigateur

Avec un lecteur de flux RSS, on peut faire une veille dans les domaines suivants :

- nouveautés paraissant sur un site d'information
- nouvel article indexé dans une base de données
- nouveau tweet sur un sujet qui nous intéresse
liste non exhaustive.

Les flux RSS sont partout mais ils sont relativement invisibles.
S'inscrire à une chaîne de podcasts, c'est aussi utiliser un flux RSS qui nous envoie les derniers épisodes parus.

Conserver dans Feedbro le flux RSS relatif à la requête dans Eur-lex.


# additifs et hyperactivité : un


On va faire une recherche sur l'évaluation des risques pour la santé de certains auxilaires technologiques et notamment leur implication éventuelle dans les troubles de l'attention.

Nécessité de trouver un terme anglo-saxon à "auxiliaire technologique"
Comment trouver un terme équivalent à auxiliaire technologique en anglais

pas de résultats sur les dictionnaires terminologiques (termsciences et dictionnaire multilingue des Techniques de l'ingénieur)
pas de documentation scientifique ou réglemmentaire en anglais depuis l'[article de wikipedia](https://fr.wikipedia.org/wiki/Auxiliaire_technologique)
traduction deepl :
- auxiliaire technologique = technology assistant / support
- des additifs et des auxiliaires technologques = processing aids

Quel type de littérature aller chercher.


# en quête de synthèses scientifiques sur la question

revues de littérature
Où aller chercher ces revues de littérature : propositions
(propositions)
- google scholar
- lens
- Pubmed
- clinical trials
- CAIRN
- Cochrane
- EM premium

Notions de consensus (consensus scientifique // consensus réglementaire)
Biais de publication



Réponses : Pubmed, Cochrane, embase

Pubmed / google scholar = spécificité vs sensibilité. [guide](https://guides.library.utoronto.ca/c.php?g=577919&p=4304403

Qu'est-ce qui augmente la pertinence des résultats de Pubmed (et qui n'existe pas chez Google Scholar ?)

- pas bcp de filtres
- pas de thésaurus

Pubmed : est-ce que additifs, allergie et auxiliaires additifs ont des équivalents Mesh.

!mesh additives -> food additives
!mesh processing aids -> pas de résultat
allergie : passer par le [Mesh inserm](mesh.inserm.fr/) : hypersensitivity

trouver des revues de littérature de moins de 10 ans sur les effets des additifs ou auxilaires technologiques

**Trouver dans Pubmed les méta-analyses sur les éventuels liens entre les additifs et les troubles de l'attention chez l'enfant.**
Quel type d'additif est plus particulièrement visé d'après les résultats de la recherche


Mettre en place un Google Doc pour permettre aux étudiants de recenser leurs trouvailles
https://docs.google.com/document/d/1vVeeFtmhs-_DPKBqwHmbU8wThKgnB11IJKNCNn6RjkA/edit?usp=sharing

- Notion de style bibliographique (Vancouver)
- rétractation d'une étude
- problème d'accès aux articles scientifiques / green, gold and black open access


**Solution Pubmed** : ("Attention Deficit Disorder with Hyperactivity"[MeSH Terms] AND "Food Additives"[MeSH Terms]) AND (meta-analysis[Filter])
4 résultats, 3 traitent des additifs pour la coloration des aliments
prendre le RSS de la requête.

**Solution Web of science** : https://www.webofscience.com/wos/woscc/summary/b4a587c2-8645-4b75-b7f3-b304a9f12a28-0ae78866/relevance/1

101 résultats avec le filtre reviews

**Solution Cochrane Library** : https://www-cochranelibrary-com.passerelle.univ-rennes1.fr/advanced-search/search-manager?search=6814005 16 résultats

Cochrane comme Pubmed ou le Web of Science donnent la possibilité de combiner des requêtes entre elles

Search Name:	hyperactivity food additives
Date Run:	03/10/2021 13:49:21
Comment:

| ID |	Search |	Hits |
|:---:|:---:|:---:|
| \#1 |	MeSH descriptor: [Psychomotor Agitation] explode all trees | 1065 |
| \#2	| MeSH descriptor: [Food Additives] explode all trees |	1069 |
| \#3	| MeSH descriptor: [Attention Deficit Disorder with Hyperactivity] explode all trees |	2897 |
| \#4	| \#2 AND (\#1 OR \#3) | 16 |

# L'aspect social et médiatique de la question : presse en ligne et réseaux sociaux

Dans Europresse : trouver des articles de presse qui mentionnent le problème dont parle Christophe Brusset (additifs utilisés comme auxiliaires technologiques pour ne pas être affiché sur l'emballage)

Quels mots-clé utiliser, quels filtres mobiliser pour obtenir des résultats pertinents

voir par exemple : https://nouveau-europresse-com.passerelle.univ-rennes1.fr/Link/RENNES1AT_1/news%c2%b720181014%c2%b7WM%c2%b75269c71c-cb9b-11e8-ad93-c911e841006e

Et sur Twitter, que dit-on des auxiliaires technologiques

on peut faire une recherche sur Twitter sans avoir de compte
avec [Twitter search](https://twitter.com/explore) ou bien avec https://nitter.fdn.fr
https://nitter.fdn.fr permettra de sauvegarder un flux RSS en lien avec sa recherche sur Twitter
entrer le flux dans la bibliothèque de flux de Zotero

Evaluation finale https://app.klaxoon.com/join/73GJZQF
