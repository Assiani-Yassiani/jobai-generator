# AI Job Description Generator

Générateur automatique de descriptions de postes professionnelles utilisant l'intelligence artificielle. Le système apprend à partir de milliers d'offres d'emploi réelles et génère des descriptions de haute qualité à partir de simples mots-clés.

## 🎯 Objectif

Créer des descriptions de postes complètes et professionnelles en quelques secondes, simplement en fournissant des compétences et mots-clés.

## 🔄 Pipeline du Système

### 1. Scraping
Collecte automatique de milliers d'offres d'emploi depuis différentes sources (Indeed, LinkedIn, etc.). Les données incluent titres de postes, descriptions complètes, compétences requises et responsabilités.

### 2. Extraction de Mots-Clés
Analyse des descriptions avec traitement du langage naturel (NLP) pour identifier et extraire les compétences techniques clés, les technologies, les niveaux d'expérience et les langages de programmation mentionnés.

### 3. Préparation des Données
Nettoyage et formatage des données collectées. Suppression des doublons, URLs et informations non pertinentes. Organisation des données au format optimal pour l'entraînement du modèle.

### 4. Fine-Tuning du Modèle
Entraînement d'un modèle de langage (GPT-2) sur le dataset préparé. Le modèle apprend les patterns et structures des descriptions professionnelles pour générer du contenu cohérent et de qualité.

### 5. Génération
Le modèle entraîné reçoit une liste de mots-clés en entrée et génère automatiquement une description de poste complète, structurée et professionnelle.

## 🛠️ Technologies Utilisées

- **Intelligence Artificielle**: GPT-2 (Generative Pre-trained Transformer)
- **Machine Learning**: PyTorch, Transformers (Hugging Face)
- **Traitement du Langage**: spaCy
- **Traitement de Données**: pandas, NumPy
- **Web Scraping**: BeautifulSoup, requests

## 📊 Performances

- Dataset d'entraînement: 30,000+ descriptions de postes
- Temps de génération: 2-3 secondes par description
- Qualité: Descriptions naturelles et cohérentes
- Flexibilité: Adaptable à différents domaines (IT, Marketing, Finance, etc.)



*Projet développé avec GPT-2 et Transformers*
