<figcaption style=" text-align: right ">Lena MK, août 2026</figcaption>

# Collections tactiles. Recherche-création en matérialisation de données culturelles



## Introduction 

> L’outil juste répond à trois exigences : il est générateur d’efficience sans dégrader l’autonomie personnelle, il ne suscite ni esclaves ni maîtres, il élargit le rayon d’action personnel. L’homme a besoin d’un outil avec lequel travailler, non d’un outillage qui travaille à sa place. Il a besoin d’une technologie qui tire le meilleur parti de l’énergie et de l’imagination personnelles, non d’une technologie qui l’asservisse et le programme. (Illich 1973, 27)
>

La transformation numérique des institutions culturelles est au cœur de discours provenant du gouvernement, du milieu culturel et de la recherche (*Références à  ajouter*). En constante quête d’améliorations et de mise à niveau, le milieu culturel est souvent considéré « en retard » dans la course vers le progrès tracée par l’adoption de pratiques technologiques (*Références à  ajouter, dont Lamqaddam et al. 2018*). Toutefois, pour en faire une utilisation *conviviale* (au sens d’Ivan Illich), « il nous faut reconnaître qu’il existe non pas une façon d’utiliser les découvertes scientifiques, mais au moins deux » (Illich 1973, 12). Plutôt que de conduire à la spécialisation des tâches et à la centralisation des pouvoir, cette thèse s’aligne avec la proposition d’Ivan Illich dans l’idée de faire fructifier l’invention afin d’accroître le pouvoir et le savoir de chacun (Illich 1973, 12). Ainsi, la création, la mise en ligne et l’utilisation de données culturelles sont abordées dans une approche de recherche-création afin d’explorer « la liberté de façonner les objets qui [nous] entourent » (Illich 1973, 27).

Si la recherche et la création sont des pratiques souvent entremêlées, je situe mon travail dans le cadre de la recherche-création car, d’une part, je mobilise les bases théoriques et techniques de ma recherche dans un processus de création; d’autre part, la pratique n’est pas un aboutissement de la recherche, je l’aborde comme un lieu d’expérimentation qui a le potentiel d’être révélateur ou catalyseur d’enjeux théoriques. Il ne s’agit pas « juste » de produire un objet culturel ou une création, mais de placer l’acte de création dans un processus plus large qui vise à contribuer à la production de connaissances en histoire de l’art. La diffusion de la recherche-création devient ainsi un moment de partage, où l’on peut « éprouver et donner à voir les transformations qui modifient nos manières de réfléchir » (Suchet 2016, 69).

Ma pratique de recherche-création porte sur les données culturelles, c’est-à-dire des données issues du milieu artistique et dont l’étude rejoint la discipline de l’histoire de l’art. Il peut s’agir, par exemple, d’une collection d’œuvres d’art, d’un catalogue raisonné ou d’archives, dont la description est structurés sous la forme de données et donc lisible par une machine *(OPTION Vane 2019, 9)*. Ce type de description systématique présente l’opportunité d’étudier une collection en tant qu’ensemble, avec une approche quantitative. Anne Dymond emploie ainsi des indicateurs statistiques pour analyser les collections canadiennes dans son ouvrage *Diversity Counts: Gender, Race, and Representation in Canadian Art Galleries* (2019). Au cours d’une collaboration avec Valentine Desmorat, nous avons utilisé les données publiées par le Musée d’art contemporain de Montréal (MAC) pour produire des graphiques qui visualisent l’entrée des femmes artistes dans cette collection ([figure 1](#fig1)). Desmorat a poursuivi avec une analyse approfondie de ces graphiques au regard des archives institutionnelles et du contexte historique (Desmorat 2023).

Ces recherches menées sur des institutions canadiennes et québécoises s’inscrivent dans un courant plus large d’études féministes quantitatives en histoire de l’art. Celles-ci émergent notamment des mouvements de libérations des femmes aux États-Unis au cours des années 1960 et 1970, dont le célèbre essai Linda Nochlin « Why Have There Been No Great Women Artists ? » ([1973] 2015) et les interventions percutantes des Guerilla Girls (mettre une figure? ). Joyce Kozloff, aujourd’hui confirmée parmi les membres fondatrices des Guerrila Girls, souligne l’efficacité d’une approche quantitative pour transformer le récit autour d’une institution et de sa collection. Les statistiques, ou même simplement compter les œuvres réalisées par des femmes ou le nombre d’expositions monographiques dédiées à des femmes, dévoilent une « preuve rationnelle » (*logical “proof”*) de la discrimination (Kozloff 2026). S’il existe d’autres sujets qui mêlent les approches quantitatives en histoire de l’art, comme les études portant sur le marché de l’art et l’histoire des expositions par exemple (Joyeux-Prunel 2008, Greenwald 2021), **cette thèse se concentre sur la mise en récit militante des données de collection, dans un but d’éducation et de sensibilisation à des enjeux politiques intrinsèques aux collections**. À titre d’exemple, le projet *Digital Benin* se concentre sur 5000+ objets originaires du Royaume du Bénin. Le travail avec les données permet à l’équipe de *Digital Benin* de dénoncer le pillage de 1897 et la conservation aujourd’hui contestée de ces biens culturels, aujourd’hui répartis parmi parmi 139 institutions et 21 pays (Digital Benin).

Je complémente l’approche quantitative par des représentations visuelles et/ou spatiales des données pour donner un moyen au public d’interpréter et de raisonner à propos de ces informations quantitatives (Tufte 2018 [1983], 91). Dans la littérature, il existe quelques exemples de visualisation de données centrés sur les besoins spécifiques de la recherche en histoire de l’art. Florian Kraütli et Olivia Vane ont créé et testé des outils de visualisation chronologique pour les collections culturelles dans leurs thèses respectives (2016, 2019). D’autres développeur·se·s et ingénieur·e·s se concentrent de façon plus large sur les outils et les solutions techniques requis (Lamqaddam et al 2018). Le domaine connexe de la cartographie thématique rejoint les mêmes enjeux, bien qu’en employant des technologies différentes: il s’agit de visualiser des données à propos d’œuvres, de lieux patrimoniaux ou d’artistes sur un fond de carte pour effectuer une analyse spatiale de ces informations (Palsky 1986; Fletcher et al. 2012; Williams 2018; MK 2021 et 2026; De Oliveira Savoi 2026). 

Bien que les données détiennent une place centrale dans mon processus de recherche-création[^2], la visualisation de données et la cartographie n’y sont pas pour autant de « simples » représentations de ces données. Pour créer une image à partir de données, un algorithme construit une représentation visuelle de façon méthodique ; la formulation de règles explicites dicte la couleur de chaque pixel du graphique en fonction des données fournies en entrées. Cependant, modifier puis exécuter à nouveau l’algorithme donne la possibilité d’itérer des centaines voire des milliers de fois sur le résultat (Molnar 1984). Le travail de design itératif sur un algorithme produit un résultat « *unique, carefully designed and data-specific* » (Tufte 2018 [1983], 179) tout en étant répétable et réutilisable. Cette approche est donc particulièrement intéressante pour une démarche expérimentale en recherche-création. Lorsqu’elle est clairement énoncée, elle permet également d’éviter le piège de l’objectivité scientifique, en préférant exposer le principe interprétatif derrière la proposition (Drucker 2014, 128).  En considérant la visualisation de données comme un récit à construire plutôt qu’un mécanisme à automatiser, sa pratique devient nécessairement critique et située (Hall et Dávila 2023; Haraway 1988).

J’explore donc, dans cette thèse, la représentation critique et située de données culturelles. Parmi l’éventail des formes de représentations de données – comme la cartographie ou la visualisation de données –, j’ai opté pour une pratique encore peu explorée, celle de la matérialisation de données (*data physicalization*). Il s’agit de la création « d’objets (artefacts physiques) dont la géométrie ou la matérialité *encode* des données » (Jansen et al. 2015, 2). La matérialisation de données complémente la visualisation par une approche multisensorielle, combinant les approches visuelle, tactile, auditive ou même olfactive pour offrir une expérience relationnelle (*embodied interaction*) à la perception des données. Dans les recherches et les expérimentations en matérialisation de données recensées dans des publications académiques et par le site web [dataphys.org](https://dataphys.org/) [^3], je n’ai pas trouvé de pratiques documentées portant sur la matérialisation de données culturelles, au sens défini ci-haut. S’y apparente tout de même une œuvre intitulée *The Life of a Building* (2021-2022) ([Figure 6](#fig6)), commanditée par la Galerie d’art d’Ottawa (OAG – *Ottawa Art Gallery*). Il s’agit d’une collaboration entre l’artiste textile Greta Grip et la chercheuse spécialisée en textiles électroniques, en fabrication et en pratiques artisanales hybrides (*hybrid crafts*), Lee Jones. Tout d’abord, entre juillet 2021 et juillet 2022, une machine à tricoter matérialisait en temps réel l’achalandage physique et numérique de la Galerie. Par le biais d’un capteur à l’entrée du bâtiment, ainsi qu’à travers l’utilisation d’un bouton virtuel présenté sur un microsite dédié, chaque visite déclenchait la production d’une rangée du tricot circulaire, tandis que le passage du temps était marqué mensuellement par le changement de couleur de la laine employée. Ensuite, en mai 2023, l’œuvre a ensuite été redéployée pour présenter cette fois le résultat de cette fabrication performative et participative, afin de mettre l’emphase sur l’observation et l’analyse des données ainsi recueillies. « *The data was hung from the ceiling in a way that individuals could see the data spread out* » (Jones et al. 2024, 9). Ce projet a également été le lieu d’une recherche-à-travers-le-design (*research through design*) sur la réception des matérialisations de données, présenté à la conférence internationale sur les Interactions Tangibles, Incarnées et Incorporées TEI (*International Conference on Tangible Embedded and Embodied Interaction*) et documenté dans les actes de la conférence (Jones et al. 2024). *The Life of a Building* matérialise ainsi des données sur le public d’une institution culturelle, une métrique particulièrement importante au lendemain des fermetures causées par la pandémie de la COVID-19.

![](../doc/img/lifeOfABuilding.png)

<figcaption style=" text-align: right " id="fig6">Figure 6:  *The Life of a Building*, Greta Grip et Lee Jones, 2021-2022. Montage d’images disponibles dans l’article de Jones et al. 2024</figcaption>

Au cours d’une recension continue effectuée tout au long de ma recherche doctorale, j’ai également trouvé des créations et des œuvres d’art qui font usage de données, et parfois de données culturelle. Celle-ci ne sont toutefois pas catégorisées comme des matérialisations de données, car leur contexte de création et de production se situe généralement dans une pratique artistique plutôt que dans le domaine académique relié à l’appellation « matérialisation de données ». Dans de nombreux cas, les artistes ont recourt à l’utilisation de données ou à une forme d’encodage de l’information afin de véhiculer un message. Toutefois, c’est davantage un sujet encodé/exprimé par les données que les données elles-mêmes qui se trouvent au cœur du processus de création. [Maya Amer](https://mayaamerdesign.com/about), designer et conceptrice d’animation d’origine palestinienne, explore une hybridation entre le *tatreez* – la broderie en point de croix traditionnelle palestinienne – et la visualisation de données. Dans [*Every Stitch Is A Person* (2023)](https://verweymuseumhaarlem.nl/maya-amer/), la créatrice encode dans une animation un motif de broderie qui représente le nombre de décès engendrés par les massacres de l’armée Israélienne à Gaza en octobre 2023.



- Giorgia Lupi & Stefanie Posavec, *dear data* → visualiser un sujet, choisir une façon de l’encoder puis de le représenter
- Ada K. Dietz → encoder des fonctions mathématiques dans la logique du métier à tisser, résultat forme un motif propre à chaque fonction

Par exemple, l’artiste [Michaëlle Sergile](https://www.michaellesergile.com/about) encode le texte de *Peau noire, masques blancs*  (Franz Fanon) dans une forme visuelle tissée pour souligner « l'absurdité des termes Noir.e et Blanc.he et le manque flagrant de représentations positives des femmes dans ce livre » (*Sergile citée dans MNBAQ 2017-2018*). 

- 
- Casey Jenkins, *Casting my womb* → cycle menstruel *incoporé* dans le tricot et devient une visualisation/matérialisation du cycle
  - (autographic design par le placement de la pelotte… )
- Joyce Wieland *Water Quilt* (?) matérialise un livre sous la forme d’une courtepointe

élargir de l’art contemporain vers design et autres pratiques

- 

exemples sur les données → requiert une aisance technique dans la manipulation et la transformation de données

- *Oiko-nomic Threads*, Afroditi Psarra, Maria Varela and Marinos Koutsomichalis → open data Manpower Employment Offices databases$
- *To Make One Particle* (2025) de Pansee ElAtta à la limite de cet exemple





[métho? → ] collaboration entre artistes/créateur·rice·s et institutions, n’est pas toujours nécessaire pour accéder à des données de collections. En effet, les musées participent de plus en plus au mouvement d’accès ouvert, notamment par la mise en ligne et l’accès en données ouvertes à leurs collections. 



> cette thèse se concentre sur la mise en récit militante des données de collection, dans un but d’éducation et de sensibilisation à des enjeux politiques intrinsèques aux collections









C’est également pourquoi je préfère parler de représentation de *données*, par opposition au terme favorisé par certains spécialistes comme Robert Kosara par exemple (2007), car



(*§ création de visualisations de données est une forme de commissariat / contre-commissariat de données ?*)













De plus, l’une des ambitions de ce domaine est de faire connaître les origines multiples et les apports de différentes cultures à l’histoire de l’encodage et de la transmission de l’information[^1].  Il s’agit ainsi de reconnaître que les données – au sens d’informations enregistrées de façon à en « permettre le stockage, la transmission ou le traitement » ([GDT](https://vitrinelinguistique.oqlf.gouv.qc.ca/fiche-gdt/fiche/8358482/donnee)) – n’ont pas été inventées avec les premiers ordinateurs, ni même par les bureaux de statistiques ou d’autres administrations au fonctionnement centré sur l’écriture. Face à l’amplification exponentielle de la place des données dans notre société, ce travail de reconnaissance historique vise notamment à décentrer le savoir occidental pour faire place à une diversité d’épistémologies. Les recherches en matérialisation de données se développent également en ce sens : de nouvelles pratiques émergent en référence aux autres façons (historiques, culturelles) de penser et d’interagir avec les données.







- visualiser/cartographier (avec des données = espace numérique)
- matérialiser (redonner une forme avec laquelle on peut interagir dans l’espace physique, interactions physiques / tactiles)



#### Revue de litt: matérialisation de données & œuvres connexes

[nb: distinguer la matérialisation de données des œuvres qui matérialisent/font appel à des données]



## Problématique

**comment la matérialisation de données peut-elle offrir une nouvelle forme d’accès pour des données culturelles ?** 

> (Ex synth)Je mènerai cette recherche à partir de l’hypothèse selon laquelle la création de ces nouvelles formes d’accès passe par une posture interdisciplinaire, en pensant l’artisanat comme une technologie et la technologie comme une pratique artisanale. À la croisée des matérialisations de données et des œuvres ou expériences *sensation*nelles, je vais expérimenter avec la fabrication d’objets qui incorporent des données culturelles.



-  réflexion transversale sur l’accessibilité, notamment par une approche multisensorielle

### Études de cas

Une thèse par étude de cas

La différence entre les deux études de cas s’explique par le contexte (à expliquer dans le *Plan de la thèse*? )

#### MAC: 

- données ouvertes publiées depuis plusieurs années
- contexte: j’avais déjà travaillé avec ces données (avec Valentine) et avec l’institution (avec CIECO)
- expérimentation: à partir de mes connaissances pré-existantes et « en consultation » avec leur équipe pour éclairer certaines incompréhensions / questions sur les données + avoir leurs perspectives sur l’angle abordé

#### MPP: 

- ouverture des données: oui (en théorie) mais… 
  - pas d’utilisation connues à ce jour
  - offerte par défaut dans le système de catalogage
  - intention: alimenter la plateforme de cartographie numérique / atlas culturel *Bayt wa balad*
-  contexte: institution et contexte culturel entièrement nouveaux pour moi → stratégie: rejoindre l’équipe pour me familiariser avec leur travail et spécialisation
- expérimentation:
  - requiert d’abord une phase d’accès et d’analyse des données: comme le travail de catalogage était encore en cours, participation aux discussions concernant les choix de structuration des données etc. 
  - ensuite, recherche-création comme complément/extension matérielle dans la salle du musée (matérialisation de données mais aussi du projet *Bayt wa balad*) pour une expérience incarnée et mutlisensorielle 
- structuration en deux chapitres pour aborder le travail dit « préparatoire » nécessaire à la recherche-création avec les données du MPP (projet plus ambitieux: 2x plus de temps)

La première étude de cas est donc un « cas simple » et la seconde un  « cas approfondi », ce qui permet de comparer les deux approches et les résultats obtenus. 



## Cadre théorique

penser l’artisanat comme une technologie et la technologie comme une forme d’artisanat

- instrumentation de la création: Albers, Molnar

« image programmée »: lier cartographie et data viz en représentation visuelle programmée de données

- pratiques algorithmiques



## Métho

### La matérialisation de données comme pratique de recherche-création



### Protocole

Pour mener cette recherche, j’ai créé un protocole d’expérimentation (Annexe 1: protocole) qui fournit un cadre à ma pratique. Ce cadre me permet d’expérimenter la réflexion-dans-l’action (*reflection-in-action*), un terme proposé par le philosophe et urbaniste Donald A. Schon pour énoncer une posture dans laquelle « on réfléchit à ce qu’on fait pendant qu’on le fait » (1983, 54). Le protocole est divisé en trois étapes :

1. ***Faire des choix*** est une étape qui sert à nommer les décisions et les partis pris dans l’élaboration d’une matérialisation de données. Ses trois composantes principales sont les données, l’algorithme de représentation et l’expression matérielle. Chacune requiert des choix et des décisions qui s’influencent de façon itérative. Les tâtonnements, les tests et les différentes versions font partie du processus de la recherche-création.
   - Les **données** sont décrites pour déterminer le sujet à représenter ainsi que pour identifier la source ou l’institution qui les a produites. Elles décrivent, par exemple, le contenu d’une collection muséale de façon structurée. L’analyse de ces données, et donc de la façon dont elles décrivent les objets d’une collection, s’effectue en parallèle du prétraitement des données, une étape préparatoire au cours de laquelle les données sources sont transformées selon les besoins du projet.
   - Un **algorithme de représentation** traduit ensuite ces données d’un format textuel vers une forme visuelle. Par exemple, chaque œuvre d’art dans la collection devient un symbole placé dans l’espace visuel en suivant un ordre chronologique. Cet algorithme lui-même est un protocole, qui applique une logique visuelle et spatiale avec une méthodologie algorithmique. Le choix de symboles et de l’organisation spatiale et visuelle oriente la lecture et contribue à construire un récit à partir des données. Le travail préparatoire et l’esquisse sont algorithmiques. Contrairement à la visualisation de données, le résultat est une étape, une sorte de partition ou de plan de travail.
   - Cette représentation est ensuite incarnée dans une **expression matérielle.** La matérialité, dans les sensations qu’elle évoque et dans le geste même du travail de la matière, exprime également un ou des sens symboliques. La quantité de données exige un geste répétitif, une sorte de travail à la chaîne qu’il faut négocier avec les moyens à disposition, autant techniques que manuels. L’expression matérielle requiert également l’achat ou la collecte de la matière première, imposant des réalités économiques et écologiques au projet.
2. ***(Dé-)montrer*** questionne ce qui est présent lors de la mise à vue publique. Celle-ci requiert une forme d’aboutissement de la première étape, même si le protocole lui-même peut être utilisé de façon itérative. À cette étape, l’enjeu n’est pas uniquement de montrer le résultat de la matérialisation de données. Il s’agit plutôt de produire une démonstration de la recherche-création. Pour expliciter son fonctionnement, son « mode d’emploi » et ses propriétés, l’objet doit être accompagné d’une sélection d’éléments qui rapportent les choix effectués et le processus suivi. La présentation publique est également le lieu de mise en commun et de partage de la recherche-création. La réception peut être participative, au sens où les interactions pensées dans la matérialisation peuvent aller au-delà de l’expérience pour contribuer à l’élaboration de l’objet. Pour toutefois distinguer la présentation d’un projet de l’animation d’un atelier créatif, un cadre de participation est établi au préalable et lui-même présenté dans l’espace. Une question récursive se pose: les expériences vécues par les personnes présentes, leurs actions et leurs rétroactions peuvent-elles / sont-elles exposées elles aussi ?
3. ***Documenter*** est intrinsèque aux deux étapes précédentes. Chaque élément doit pouvoir être mobilisé pour contribuer à la recherche. Cela requiert la production délibérée d’une documentation des composantes, des itérations, de l’exposition et de la documentation elle-même, c’est-à-dire l’emploi de ce protocole. Celui-ci sera publié sur le web et mis à jour au fur et à mesure de son évolution, afin de partager ouvertement les résultats de l’expérimentation.

------

*Observations à propos du protocole*:

Ce protocole prend le parti qu’il n’y a pas de recherche-création sans (dé-)monstration. Pour que la matérialisation puisse faire l’objet d’interactions, le protocole requiert une présentation ou une forme de partage direct avec un public. Elle peut toutefois se dérouler dans des contextes variés, d’une exposition dans une institution culturelle à un événement de vulgarisation ou de partage de connaissance. L’examen de synthèse peut ainsi être le « lieu » de la démonstration, et son jury le public.

Ce protocole est intrinsèquement algorithmique :

- Il fournit des instructions qui peuvent être répétées
- Il définit des variables
- Il a recours aux boucles et à la récursion
- Il exploite les joies de l’aléa, dans les itérations comme dans la participation publique
- Il doit être exécuté pour avoir un résultat
- Il génère des traces et exige une documentation

### La  « mise en thèse »

Cas d’études comme des chapitres de thèse: la production de cahiers/zines

## Plan 

Cette thèse a donc pour objectif d’expérimenter avec une pratique de recherche-création sur la matérialisation des données culturelles afin de stimuler l’imagination et la curiosité envers les collections muséales. La documentation de cette expérimentation prend la forme d’une thèse en quatre chapitre. Le premier chapitre développe le cadre théorique pour (bien) inscrire la pratique dans un contexte de recherche

- **faire** des images programmées? 
- travailler **avec** des données
- *from data feminism to critical making*? Ingold, Berger, Dombrowski et al.



Le second chapitre est présente le premier cas d’étude: l’installation *Célébration de données molles* à propos de la collection du Musée d’art contemporain de Montréal (MAC). 







(exemples

[thèse Alix](https://udemontreal-my.sharepoint.com/personal/alix_chague_umontreal_ca/_layouts/15/onedrive.aspx?ga=1&id=%2Fpersonal%2Falix%5Fchague%5Fumontreal%5Fca%2FDocuments%2FPi%C3%A8ces%20jointes%2Fachague%5Fphd%2Dmss%5Fv1%2E1%2Epdf&parent=%2Fpersonal%2Falix%5Fchague%5Fumontreal%5Fca%2FDocuments%2FPi%C3%A8ces%20jointes) 

thèses par articles

- https://theses.hal.science/tel-03770337v2/document
- https://theses.hal.science/tel-03854403)





 La thèse, comme retour réflexif et mise en commun finale, a donc pour but de rassembler de façon accessible et pérenne les idées, les références et des extraits du protocole. Le format visé sera donc l’autoédition de cahiers/zines. Le respect des standards d’édition numérique permet de considérer les principes d’accessibilité universelle, le libre-accès garantit un accès économique (et l’impression sur demande permet de produire des copies papier en quantités responsables).

[^1]: Parmi les exemples populaires, on retrouve les bulle-enveloppes, des petits objets en argile employés il y a 6000 ans pour la comptabilisation de biens en Mésopotamie ([Wikipédia](https://fr.wikipedia.org/wiki/Bulle-enveloppe)), ou encore les quipus (ou khipus), un système de consignation de données formé de cordes et de nœuds utilisé par l’administration de l’empire Inca et dont les traces remontent à 4500 ans ([Wikipédia](https://fr.wikipedia.org/wiki/Quipu)).
[^2]: ce qui distingue ma pratique de l’infographie ou de la « visualisation de l’*information* » (*information visualisation*, Kosara 2007).
[^3]: Au printemps 2026, j’ai eu le plaisir de découvrir que ma *Célébration de données molles* a été recensée sur dataphys.org 
