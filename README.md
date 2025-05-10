# Projet : Exploration RAG et RLHF


** Groupe : 7 **

** Projet réalisé par :**
- EL GHIOUAN ISRAE
- BENCHERAIK ABDESSAMAD



Ce projet explore deux techniques avancées dans le domaine des Grands Modèles de Langage (LLM) : la Génération Augmentée par Récupération (RAG) et l'Apprentissage par Renforcement à partir de Retours Humains (RLHF). Le notebook fourni (`Gr7_Projet2_lab_RAG&RLHF_ISRAE_EL_GHIOUAN_ABDESSAMAD_BENCHERAIK.ipynb`) démontre l'implémentation d'un système RAG simple et offre un aperçu conceptuel de RLHF.


## Contenu du Dépôt GitHub

Le dépôt contient les éléments suivants :
1.  `Gr7_Projet2_lab_RAG&RLHF_ISRAE_EL_GHIOUAN_ABDESSAMAD_BENCHERAIK.ipynb` : Le notebook avec le code source, les explications et les démonstrations.
2.  `Readme.md` : Ce fichier, décrivant le projet, la configuration de l'environnement et la structure du code.
3.  **Présentation Vidéo :**
    *   **Lien :** `[À INSÉRER ICI - Mettez le lien vers votre vidéo hébergée (ex: YouTube, Drive, etc.)]`
    *   **Durée :** `[À INSÉRER ICI - Indiquez la durée de votre vidéo, ex: 6 minutes 45 secondes]` (Doit être inférieure ou égale à 7 minutes)


## Configuration de l'Environnement de Développement

Ce projet a été développé et testé en utilisant Google Colab avec un GPU T4.


### Prérequis
*   Python 3.x
*   Un compte Hugging Face et un jeton d'accès (pour télécharger des modèles).
*   Un GPU est fortement recommandé pour des performances raisonnables, en particulier pour le chargement des modèles.


### Installation des Dépendances
Les dépendances nécessaires peuvent être installées en exécutant la première cellule de code du notebook (`Gr7_Projet2_lab_RAG&RLHF_ISRAE_EL_GHIOUAN_ABDESSAMAD_BENCHERAIK.ipynb`). Les commandes principales sont :


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
