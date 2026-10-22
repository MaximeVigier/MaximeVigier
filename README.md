# Maxime Vigier

Docteur en biotechnologie (Université de Lorraine, 2022), reconverti en data science. Deux ans de R&D en start-up, puis la certification Data Scientist Liora x Mines Paris-PSL (titre RNCP Expert en data science, 2026).

Je construis des pipelines data reproductibles sur des sujets de santé que je connais côté biologie, en gardant la rigueur statistique : évaluation chiffrée, limites écrites, résultats négatifs assumés.

Bordeaux · full remote, hybride ou freelance · maxime.vigier2@gmail.com

---

## Projets

### [alzheimer-risk-rag](https://github.com/MaximeVigier/alzheimer-risk-rag)
Assistant de questions-réponses sur les facteurs de risque d'Alzheimer, sourcé sur 1198 abstracts PubMed. Retrieval hybride dense + BM25 avec reranking (recall@10 = 0,86 contre 0,67 en dense seul), fidélité 0,925 mesurée avec RAGAS par un juge distinct du générateur, +88 % de correctness face au même LLM sans contexte. API FastAPI, Docker, 23 tests et CI GitHub Actions.

### [covid-radiography-benchmark](https://github.com/MaximeVigier/covid-radiography-benchmark)
Projet de certification mené à 4. Plus de 30 configurations (ML classique, CNN construits from scratch, transfer learning) comparées sur 4 classes de radiographies thoraciques (n = 2 084 en test) : 91,1 % d'accuracy et 0,92 de macro-F1 avec DenseNet et un CNN à 5 blocs. Étude d'ablation sur la profondeur et analyse du biais de source. Ma contribution personnelle est détaillée dans le README.

### [grippe-france-prevision](https://github.com/MaximeVigier/grippe-france-prevision)
Prévision hebdomadaire de l'incidence grippale en France (réseau Sentinelles, depuis 1990). STL, SARIMA, Fourier+ARIMA, ML et LSTM comparés par backtest à origine glissante. Fourier+ARIMA bat le naïf saisonnier au meilleur rapport qualité/coût, le deep learning n'apporte rien sur une série nationale seule.

### [nhanes-risque-cardiometabolique](https://github.com/MaximeVigier/nhanes-risque-cardiometabolique)
Le syndrome métabolique est-il prédictible à partir de l'alimentation déclarée (NHANES, 3 cycles) ? Chaîne ML complète, SHAP, analyse en sous-groupes. Le résultat est négatif et stable : à âge et catégorie sociale donnés, l'alimentation déclarée n'ajoute presque rien.

### [alzheimer-gene-expression](https://github.com/MaximeVigier/alzheimer-gene-expression)
Expression génique différentielle dans le cortex entorhinal (GSE5281, 23 échantillons, 54 675 sondes). Pipeline modulaire, notebooks versionnés, choix méthodologiques explicités, limites discutées. Le sujet recoupe ma thèse.

---

## Compétences
`Python` `pandas` `NumPy` `scikit-learn` `Keras` `SQL` `RAG / LLM` `FastAPI` `Docker` `GitHub Actions` `Streamlit` `statistiques et plans d'expérience`
