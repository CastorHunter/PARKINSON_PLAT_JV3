# PARKINSON_PLAT_JV3

**Touches (données dans le jeu) :**
Z, Q, S, D : Déplacements
Shift : Sprint
A : Dash
R : Poser une balise
E : Retourner à la balise

**Expérience de jeu attentude :**
Ce jeu est un platformer 3D en trois niveau dont un tutoriel. Pour les compléter le joueur doit passer une porte fermée par une clef qu'il a à récupérer dans le niveau correspondant.

**Retour sur le projet :**
Ce projet m'a permi de consolider mes acquis sur Unreal Engine et d'apprendre de nouvelle choses, si bien que je pense être en mesure de développer en autonomie dorénavant. Bien sûr, il me reste beaucoup à apprendre, mais je pense avoir fait le tour de la majorité des bases.

**Difficultés rencontrées :**
- **VFX :** J'ai pris du temps à réussir à bien utiliser les vfx en jeu, et même maintenant c'est encore loin d'être parfait.
- **Mise à l'échelle des Scenes components** : N'y ayant pas pensé en amont, certains programmes touchaient directement au transform et donc à la scale pour la ramener à 1. Certains Scene Components reprenaient donc leurs tailles d'origine, m'obligeant à modifier le programme de base.
- **Ordre d'exécution :** Certains programmes fonctionnaient mal ou pas car j'avais inconsciemment en tête que tout s'exécutait en même temps (ex le BeginPlay) et cela m'a amené à me creuser la tête pour comprendre où ça pêchait.

Sans être une difficulté, le moteur de jeu Unreal me fait un peu peur sur un point : Il y aune quantité très importante de contenu intégré que je ne connais pas, et j'ai peur de faire un jeu mal optimisé non pas parce que je fais mal mon travail mais parce que je ne m'y connais pas assez dans l'optimisation des options du moteur.

**Ce que j'aimerai rajouter/améliorer :**
- **Le personnage :** J'aurai aimé changer l'apparence du personnage pour retoucher à la gestion des transitions des animations et me confronter à plusieurs problèmes que je pourrai avoir dans mes prochains projets.
- **Une meilleure UI :** C'est purement esthétique, mais l'UI me paraît assez laide, j'aurai aimé la changer.
- **Retoucher au saut du personnage :** Bien que le saut me convienne tout à fait, j'aurai aimé créer le mien de A à Z, c'est une des bases que je n'ai pas encore acquise.
