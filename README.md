# Maxime Vigier

Docteur en biotechnologies (Université de Lorraine, 2022) en reconversion **Data Scientist**.
2 ans de R&D en start-up (pilotage de projet, formulation, données d'essais) + certification **Data Scientist Liora × Mines Paris–PSL (RNCP)**.

Je code des pipelines data reproductibles sur des questions que je comprends au niveau métier — biologie, santé, épidémiologie — sans sacrifier la rigueur statistique.

📍 Bordeaux · Full remote, hybride ou freelance · maxime.vigier2@gmail.com

---

## Projets

### 🧠 [alzheimer-gene-expression](https://github.com/MaximeVigier/alzheimer-gene-expression) · [démo](https://alzheimer-gene-expression-6ta5v8ejpemky3vltpszpk.streamlit.app/)
Analyse d'expression différentielle (GSE5281, cortex entorhinal) comparant patients Alzheimer et témoins sains.
Là où mon doctorat (lipides membranaires et Alzheimer, 1er auteur *Int J Mol Sci* 2024) rencontre le code : pipeline reproductible (`src/` modulaire, notebooks versionnés) sur une question de biologie que je maîtrise au niveau paillasse — chaque choix méthodologique est explicite et défendable.

### 🫁 [covid-radiography-benchmark](https://github.com/MaximeVigier/covid-radiography-benchmark)
Benchmark de 13 modèles (SVM, Random Forest, 6 CNN maison, VGG16, InceptionV3, DenseNet) sur 4 classes de radiographies thoraciques (n=2084 en test).
**91,1 % d'accuracy, 0,92 de macro-F1** avec DenseNet et un CNN maison à 5 blocs — étude d'ablation complète.

### 🍽️ [nhanes-risque-cardiometabolique](https://github.com/MaximeVigier/nhanes-risque-cardiometabolique) · [démo](https://nhanes-risque-cardiometabolique-epczfzyrqcqgepmzzywbdw.streamlit.app/)
Le syndrome métabolique est-il prédictible à partir de l'alimentation déclarée (NHANES, 3 cycles) ? Chaîne ML complète (régression logistique → ensembles → MLP Keras), interprétabilité SHAP, analyse en sous-groupes.
Résultat assumé : un résultat négatif net et stable, pas maquillé en signal fort.

### 🤧 [grippe-france-prevision](https://github.com/MaximeVigier/grippe-france-prevision) · [démo](https://grippe-france-prevision-bxkv8ovpkvpjyyffpmykju.streamlit.app/)
Prévision hebdomadaire de l'incidence grippale en France (réseau Sentinelles, 1984–2026). STL, SARIMA, Fourier+ARIMA, ML, LSTM — comparés sur un backtest à origine glissante.
Fourier+ARIMA bat le naïf saisonnier au meilleur rapport qualité/coût ; le deep learning n'apporte rien sur une série nationale seule — dit sans détour.

Chaque projet ci-dessus : README complet (problème → données → méthode → résultats chiffrés → limites), tests, CI GitHub Actions, environnement figé.

---

## Compétences
`Python` `pandas/numpy` `scikit-learn` `Keras/PyTorch` `SQL` `Streamlit` `Git/CI` `stats & design expérimental` `SHAP` · en consolidation : `Docker` `Cloud`

## Autres dépôts
[`peon`](https://github.com/MaximeVigier/peon) — agent orienté événements, architecture modulaire indépendante du LLM (exploration technique perso).
[`token-dashboard`](https://github.com/MaximeVigier/token-dashboard) — dashboard local de suivi de consommation de tokens LLM.
