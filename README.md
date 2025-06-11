# Intégration de la CTI et de l'Apprentissage Automatique pour une Détection Améliorée des Menaces Numériques

## Auteurs
- Tanguy Singeot-Sousa (M2 IA)
- Loïc Blondeau (M2 Cybersécurité)
- Cléo Demay (M2 Cybersécurité)
- Arthur Fagot (M2 Cybersécurité)
- Théo Wattel (M2 Cybersécurité)

## Encadrante
- Mounia Zaydi, enseignante à Junia ISEN

## Présentation
Ce projet de fin d’études s’inscrit dans le cadre de l’obtention du titre d’ingénieur diplômé de l’Institut Supérieur d'Électronique et du Numérique (Junia ISEN). Il vise à étudier et concevoir une solution innovante de détection de logiciels malveillants en combinant la Cyber Threat Intelligence (CTI) et les techniques d’intelligence artificielle (IA), en particulier le Machine Learning.
[![Présentation CTI](Démo%20IA/presentation%20miniature.png)](https://youtu.be/PJcy2o_Fn5o)

## Objectifs
- Réaliser une revue de littérature approfondie sur la CTI, les malwares et l’IA.
- Élaborer une problématique et une question de recherche pertinente.
- Proposer une solution innovante pour améliorer la détection des menaces numériques.
- Mettre en œuvre des modèles de détection et comparer leurs performances sur des données réelles.
- Expérimenter une plateforme sandbox (CAPEv2) pour récupérer des logs de comportements malveillants.

## Contexte
Face à la complexité croissante des cyberattaques, les outils de détection traditionnels montrent leurs limites. La CTI permet d’obtenir un renseignement contextualisé sur les menaces, tandis que l’IA permet d’automatiser et d’enrichir la détection. Le croisement de ces disciplines est donc prometteur pour renforcer la cybersécurité.

## Démo
[![Démo CTI](Démo%20IA/demo%20video%20miniature.png)](https://youtu.be/fMQeO3tCC9E)

## Méthodologie
- Approche agile mêlant Scrum et Kanban (via Notion).
- Découpage en sprints pour structurer les phases de recherche et de mise en œuvre.
- Utilisation de la méthode CRISP-DM pour le traitement des données et l’expérimentation.

## Technologies et outils
- Sandbox : CAPEv2
- Langage de modélisation CTI : STIX 2.1
- Plateforme CTI : OpenCTI
- Environnements de test : machines virtuelles (KVM)
- Modèles IA : KNN, Random Forest, XGBoost, etc.
- Programmation : Python, Jupyter Notebook

## Contributions
- État de l’art sur les modèles de Kill Chain (Lockheed Martin, MITRE ATT&CK, Unified Kill Chain).
- Revue des types de malwares et des vecteurs d’attaque actuels.
- Étude de la chaîne de traitement CTI (collecte, analyse, diffusion).
- Conception et entraînement de modèles IA sur des logs malveillants.
- Évaluation comparative des modèles avec indicateurs de performance (précision, rappel, etc.).

## Résultats
- Meilleurs résultats obtenus avec XGBoost et Random Forest sur les jeux de données analysés.
- Proposition d’un modèle enrichi de détection basé sur des données CTI issues d’une sandbox.
- Perspectives d’intégration future dans un SOC via des outils comme OpenCTI.

## Conclusion
Le projet confirme l’intérêt de coupler CTI et IA pour la détection proactive des menaces. Bien que perfectible, le prototype développé offre des pistes concrètes pour une amélioration continue de la cyberdéfense.
