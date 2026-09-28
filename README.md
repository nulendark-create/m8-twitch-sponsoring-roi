# m8-twitch-sponsoring-roi
Impact du Sponsoring E-sport : Ce que le chat Twitch nous dit du ROI (Cas : Gentle Mates)

### Le pitch

Dans l'e-sport, mesurer l'efficacité d'un sponsor va bien au-delà du simple temps d'affichage d'un logo à l'écran. Ce projet vise à évaluer l'impact réel des sponsors officiels de **Gentle Mates (ALDI, TCL, Deezer)** en analysant les réactions en direct des spectateurs. 

L'objectif ? Déterminer si les marques parviennent à s'imposer dans les esprits au moment où l'engagement émotionnel de l'audience est au plus haut. 

L'étude s'appuie sur l'analyse de **5 000 messages** d'un chat Twitch, décortiqués minute par minute. 

Compétences & Outils

* **Préparation des données (Python / Pandas) :** Extraction textuelle via Regex, ciblage des mots-clés, création d'un flag d'activation émotionnelle (is_hype_message) et agrégation par fenêtres d'une minute.
* **Visualisation & Analyse (Matplotlib & Seaborn) :** Modélisation des courbes de volume du chat pour identifier précisément les temps forts du match.

Ce que les données racontent (Insights Business)

### 1. La visibilité globale : Un match très serré

Sur l'ensemble de la diffusion, l'occupation de l'espace textuel par les trois sponsors est quasiment identique. Le "bruit de fond" est très homogène : 

* **Deezer :** 714 mentions
* **ALDI :** 711 mentions
* **TCL :** 693 mentions

### 2. Les pics de "Hype" : Là où tout se joue

Le cœur de l'analyse a consisté à isoler les minutes où le chat s'enflamme complètement (spams de #M8WIN, éclats de joie, soutien massif). C'est durant ces fenêtres d'adrénaline que l'attention est maximale et que la mémorisation d'une marque est la plus forte. 

**Classement des marques uniquement pendant ces pics émotionnels :** 

1. **ALDI :** 406 mentions (Grand vainqueur du timing)
2. **TCL :** 386 mentions
3. **Deezer :** 382 mentions

**Le verdict marketing :** Si Deezer s'en sort légèrement mieux sur la longueur en termes de volume brut, **ALDI réalise le meilleur coup stratégique**. La marque capte l'attention au moment exact où la communauté vibre, maximisant ainsi l'impact mémoriel de son sponsoring. 

### Contenu du projet

* m8_twitch_sponsoring_roi.ipynb : Le code Python complet (nettoyage, structuration et graphiques).
* dataset_final_m8_twitch.csv : Le fichier de données finalisé et prêt à être exploité.
* README.md : Cette synthèse des résultats.
