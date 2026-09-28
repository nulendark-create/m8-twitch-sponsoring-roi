# m8-twitch-sponsoring-roi
Analyse du ROI de Sponsoring E-sport via le chat Twitch (Cas : Gentle Mates)
# 🎮 Analyse du ROI de Sponsoring E-sport via les Émotions du Chat Twitch (Cas : Gentle Mates)

## 📌 Présentation du Projet
Dans l'e-sport, mesurer l'impact réel des sponsors reste un défi majeur. Ce projet de Data Analysis a pour objectif d'évaluer l'efficacité des sponsors officiels de la structure **Gentle Mates (ALDI, TCL, Deezer)** en corrélant le volume des messages et la "hype" du chat Twitch avec la mémorisation des marques par les spectateurs.

L'analyse repose sur le traitement de **5 000 messages** récupérés lors d'une diffusion de match, analysés minute par minute pour en extraire des insights marketing actionnables.

---

## 🛠️ Stack Technique & Compétences Validées
* **Data Processing & Feature Engineering (Python / Pandas) :** Extraction textuelle par expressions régulières (Regex), création de flags de performance émotifs (`is_hype_message`), et agrégation par fenêtres temporelles de 60 secondes.
* **Data Visualization (Matplotlib & Seaborn) :** Modélisation de courbes d'engagement chronologiques pour identifier les pics d'audience.

---

## 📊 Insights Clés & Impact Business

### 1. Classement Global de la visibilité des marques
Sur l'ensemble de la rencontre, les marques bénéficient d'une visibilité brute très homogène :
* **Deezer :** 714 mentions
* **ALDI :** 711 mentions
* **TCL :** 693 mentions

### 2. Le Phénomène "Hype Peak" (Le Timing Émotionnel)
Le projet isole les minutes du match où le chat s'enflamme pour soutenir l'équipe (spams de `#M8WIN`, `Gentle Mates`). C'est dans ces moments d'intense émoi que le taux de mémorisation est maximal pour un sponsor.

**Classement des marques durant les pics de hype :**
1. **ALDI :** 406 mentions 🏆 (Vainqueur du timing émotionnel)
2. **TCL :** 386 mentions
3. **Deezer :** 382 mentions

**Conclusion Marketing :** Bien que Deezer génère plus de bruit de fond sur la durée totale du flux, **ALDI surclasse ses concurrents aux moments les plus stratégiques du match**, capturant l'attention de l'audience lors des pics d'adrénaline.

---

## 📁 Structure du Repository
* `m8_twitch_sponsoring_roi.ipynb` : Le notebook contenant l'intégralité du code de nettoyage et d'analyse.
* `dataset_final_m8_twitch.csv` : Le jeu de données final, nettoyé et prêt pour l'intégration BI.
* `README.md` : Présentation synthétique de l'étude de cas.
