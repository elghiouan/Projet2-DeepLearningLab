# Projet : Exploration RAG et RLHF

**Groupe : 7**

**Projet réalisé par :**
* EL GHIOUAN ISRAE
* BENCHERAIK ABDESSAMAD

## Description du Projet
Ce projet explore deux techniques avancées pour les Grands Modèles de Langage (LLM) : la **Génération Augmentée par Récupération (RAG)** et l'**Apprentissage par Renforcement à partir de Retours Humains (RLHF)**. Le notebook `Gr7_Projet2_lab_RAG&RLHF_ISRAE_EL_GHIOUAN_ABDESSAMAD_BENCHERAIK.ipynb` démontre l'implémentation d'un système RAG simple et présente les concepts de RLHF.

### Définitions Clés :
*   **RAG (Génération Augmentée par Récupération) :** Technique permettant aux LLM d'accéder à des informations externes pour améliorer la pertinence et la factualité de leurs réponses. Le LLM récupère des documents pertinents d'une source externe avant de générer une réponse.
*   **RLHF (Apprentissage par Renforcement à partir de Retours Humains) :** Processus d'affinage des LLM basé sur les préférences humaines, impliquant un modèle de récompense entraîné sur des évaluations humaines et un affinage du LLM par apprentissage par renforcement.

## Structure du Projet

### Jupyter Notebook
*   `Gr7_EL_GHIOUAN_ISRAE_BENCHERAIK_ABDESSAMAD_projet2_LAB.ipynb` : Code source, implémentation de RAG, explications conceptuelles de RLHF, et démonstrations.

### Documentation
*   `README.md` : Ce fichier, décrivant le projet et sa configuration.

### Présentation Vidéo
*   **Lien :** 
*   **Durée :**

## Installation & Prérequis
Développé et testé sur Google Colab avec un GPU T4.

### Prérequis
*   Python 3.x
*   Un compte Hugging Face et un jeton d'accès (pour télécharger des modèles).
*   Un GPU est fortement recommandé pour des performances raisonnables, en particulier pour le chargement des modèles.

### Installation des Dépendances
Exécuter la première cellule du notebook (`Gr7_EL_GHIOUAN_ISRAE_BENCHERAIK_ABDESSAMAD_projet2_LAB.ipynb`). 


Commandes principales :
```bash
!pip install -q --upgrade pip

!pip install -q \
    "fsspec==2025.3.2" \
    "gcsfs>=2025.3.2" \
    transformers \
    langchain \
    langchain-community \
    sentence-transformers \
    faiss-cpu \
    accelerate \
    bitsandbytes \
    huggingface_hub \
    datasets \
    trl \
    einops
