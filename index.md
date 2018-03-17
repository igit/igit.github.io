# My first IETF Meeting | Ma première confèrence de l'IETF

> Notes to english readers : for the moment this story/log book is only in french... I hope to be able to translate it asap... if some of you want to help me, you're welcome ;-)

> Notes aux lecteurs français : pour livrer mes impressions "à chaud" je devrai écrire très vite sans pouvoir toujours me relire correctement, il y aura sans doute beaucoup de fautes de syntaxe, grammaire et conjugaison dans le texte. Soyez indulgents, j'y revendrai plus tard.


## Qu'est-ce que je fais là ?
Je suis allé plusieurs fois aux [RIPE Meetings](https://www.ripe.net/participate/meetings). C'est vraiment une belle confèrence, très intéressante, très dense, très fatiguante (pas de détail!). Ça allie les parties théorique, production et gouvernance de mon métier. Vraiment beaucoup de choses à apprendre : j'ai pu y puiser de nouvelles expériences, connaissances et surtout, à chaque fois, de nouvelles idées (pour mes collègues... et oui ! c'est quand même pas le chef va faire... non mais !).

J'y ai aussi beaucoup entendu parler des [IETF Meetings](https://www.ietf.org/how/meetings/upcoming/). Là où se discute (entre autres), les normes, les protocoles, les bons usages ... de l'Internet (entre autres). Tout est écrit sous forme de RFC ([Request for comments](https://fr.wikipedia.org/wiki/Request_for_comments)), dans une bibliothèque consultable [ici](https://www.rfc-editor.org/).

C'est un peu difficile de décrire simplement ici l'intérêt pour mon métier et pour moi pour suivre et participer à cette conférence. C'est la "source" de toutes les connaissances que j'apprie lors de mon cursus universitaire, des compétences que j'ai pu développer dans mon métier, des infrastructures, services et matériels que j'ai mise en place. *J'essayerai de trouver un parallèle sur d'autres métiers pour illustrer et tenter de faire une comparaison.*

<img src="ietf2018london.png" style="float: right; width: 300px;"/>
Donc, voilà. Il se trouve que les IETF Meetings ont lieu un peu partout dans le monde et quelques fois en Europe, pas trop loin de la France. Là, en 2018, c'est à Londres du 17 au 23 mars. Bingo! je demande à mon employeur si je peux y aller et OK, c'est accepté. #Cool.


## 2 jours d'hackathon / 5 jours de conférence
La conférence débute le week-end (samedi et dimanche) par un hackathon. Il faut y comprendre *hack* = coder/bidouiller/casser/chercher/trouver et *athon* = marathon. Donc en gros, il y a des participants qui se retrouvent pendant 48 heures pour faire de la "programmation informatique collaborative". L'article Wikipédia [ici](https://fr.wikipedia.org/wiki/Hackathon) explique ça très bien.

Moi, je suis un peu fou-fou... alors ce genre de défit ça me plait bien. Sortir de sa zone de confort, se confronter à d'autres choses, travailler en équipe autour d'un projet innovant, des fois jamais encore réalisé : voilà une belle motivation. Bingo! je demande à mon employeur si je peux aussi y aller et OK, c'est accepté. #Cool aussi.


## Préparation de l'hackathon
Un hackathon ça se prépare. Il y a les *Champions* (capitaine, porteur d'un sujet, référent, souvent des personnes avec une expériences très-très importante) et les participants (comme moi) qui seront là pour étudier et coder les projets/sujets proposés par les Champions. Les Champions doivent proposer et décrire à l'avance leurs projets/sujets afin que globalement l'hackathon ait un sens et que les participants puissent s'engager sur tel ou tel sujet en fonction des affinités. Pour l'IETF101, les sujets sont [là](https://trac.ietf.org/trac/ietf/meeting/wiki/101hackathon). Je suis allé régulièrement sur cette page et au fur et à mesute j'y voyais apparaitre des sujets qui "piquent" (au sens c'est bien-bien compliqué) tous autant intéressant les uns que les autres mais posant tellement de questions... Des sujets comme :

> Demonstration of DNSProxy by Massimiliano Fantuzzi, a local proxy written in C, using a early pre-DoH schema.

> Development of Sending and Receiving Implementations of multipart/multilingual content types. This refers to RFC 8255 - Multiple Language Content Type.

> Measuring leakage from IoT with a MITM proxy.

> An open reference platform implementing an "AMT Gateway" as described in BCP 213 section 3.3.

> IPv6 compression and fragmentation for LPWAN technologies is being defined at the LPWAN WG.

> Considerations for Benchmarking Virtual Network Functions and Their Infrastructure.

> ...

ça laisse réveurs... non ?!

Il fallait bien que je me décide. Je devais trouver le bon rapport entre la prise de risque d'aller sur un sujet non-maitrisé, sortir de ma zone de confort, ne pas non plus me mettre en galère pour que ces 2 jours restent aggréables et que je puisse être utile à quelque chose. 

> Plouf-plouf, à trois ça sera le sujet là. Un, Deux et TROIS !

Ça sera ***Development of Sending and Receiving Implementations of multipart/multilingual content types. This refers to [RFC 8255](https://trac.tools.ietf.org/html/rfc8255) - Multiple Language Content Type***. Bon, encore faut-il que le Champion veuillent bien de moi car c'est lui qui fait son équipe !

<img src="IETF101-101hackathon-RFC8255-Multiple-Language-Content-Type.png" style="float: left; width: 400px;"/>
J'avais repéré ce sujet il y a déjà quelques temps et ça me trottait dans la tête. J'ai donc commencé à regarder plus précisement ce qui se cachait derrière ce titre. De fil en aiguille, les choses me parraissent plus clairs, c'est dans mes cordes, les idées me viennent sans trop me torturer. Deux jours avant le départ je pose mes idées sur une carte heuristique afin de structurer ma pensée et voir ce qui sera possible de faire en l'espace de 48h. Il convient de ne pas trop être "gourmand" et ne pas se lancer dans des choses qui n'aboutiront au terme de 48h. Le but de l'hackathon est de "montrer" quelque chose qui fonctionne à minima. Mais des fois même le minima... c'est long et compliqué.