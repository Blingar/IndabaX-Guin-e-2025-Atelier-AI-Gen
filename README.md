# IndabaX Guinée 2025 : IA Générative - De la Théorie Fondamentale à l'Innovation Locale

##  Aperçu du Projet

Ce dépôt contient les ressources et le code source du workshop intensif sur l'**Intelligence Artificielle Générative** présenté lors de l'**IndabaX Guinée 2025**. L'objectif de ce workshop est de fournir une compréhension approfondie des concepts fondamentaux de l'IA générative et de démontrer leur application concrète, notamment dans le contexte local guinéen et ouest-africain.

Le cœur de ce dépôt est le notebook Jupyter : `IndabaX_Guinee_2025_IA_Generative(1).ipynb`.

---

## Événement

*   **Titre :** IA Générative : De la Théorie Fondamentale à l'Innovation Locale
*   **Présenté par :** Dr. Mamadou Pathé LY & Kevin Belingar
*   **Date :** 10 & 11 Décembre 2025
*   **Lieu :** Conakry, CCFG

---

## Contenu du Workshop

Le workshop est structuré autour de trois piliers majeurs de l'IA générative, avec une section dédiée aux perspectives d'avenir.

### 1. GANs (Generative Adversarial Networks)
*   Fondements théoriques des GANs.
*   Implémentation complète d'un modèle.
*   Démonstration de la génération d'images synthétiques.

### 2. Large Language Models (LLMs)
*   Intégration et utilisation des APIs de modèles de langage avancés (ex: Claude, OpenAI).
*   Tests et expérimentations avec des langues locales africaines pour l'adaptation linguistique.

### 3. RAG (Retrieval-Augmented Generation)
*   Implémentation d'un système RAG (*Retrieval-Augmented Generation*) pour améliorer la pertinence des réponses.
*   Utilisation d'une base de données vectorielle (`Vector database`) avec des données synthétiques.
*   Application spécifique et contextualisation pour les défis guinéens.

### 4. Perspectives
*   Stratégies de *fine-tuning* avec des modèles open-source.
*   Discussion sur l'adaptation locale des modèles d'IA pour l'Afrique de l'Ouest.

---

## Prérequis

Pour exécuter les notebooks et reproduire les expériences, vous aurez besoin des éléments suivants :

*   **Python** (version 3.8 ou supérieure)
*   **Jupyter Notebook** ou **JupyterLab**
*   **Clés API** pour les services LLM (Claude, OpenAI) si vous souhaitez exécuter la partie 2.

## Installation

1.  **Cloner le dépôt :**
    ```bash
    git clone [URL_DU_DEPOT]
    cd [NOM_DU_DEPOT]
    ```

2.  **Créer un environnement virtuel (recommandé) :**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # Sous Linux/macOS
    # .venv\Scripts\activate  # Sous Windows
    ```

3.  **Installer les dépendances :**
    ```bash
    # Créez un fichier requirements.txt basé sur les librairies utilisées dans le notebook.
    pip install -r requirements.txt
    ```

## Utilisation

1.  **Lancer Jupyter :**
    ```bash
    jupyter notebook
    ```

2.  **Ouvrir le notebook :**
    Naviguez et ouvrez le fichier `IndabaX_Guinee_2025_IA_Generative(1).ipynb` dans votre navigateur.

3.  **Exécuter les cellules :**
    Suivez les instructions et exécutez les cellules du notebook séquentiellement pour explorer les concepts de l'IA générative.

---

##  Contribution

Les contributions sont les bienvenues ! Si vous trouvez des erreurs, des améliorations ou si vous souhaitez ajouter des exemples d'application locale, n'hésitez pas à soumettre une *Pull Request*.

## Licence

Ce projet est distribué sous la licence [Nom de la Licence, ex: MIT]. Voir le fichier `LICENSE` pour plus de détails.
