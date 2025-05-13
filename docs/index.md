# Projet IFT3150: [Méthode interprétable par auto-encodeur creux pour l'encodage de l'activité cérébrale IRMf](https://github.com/neurok8050/template-projet)

> **Thèmes**: Neuro-imagerie, Science des données, Apprentissage-machine  
> **Superviseur**: Lune Bellec  
> **Collaborateurs:** 

## Informations importantes

!!! info "Dates importantes"
    - **Description du projet** : 16 mai 2025
        - **Foire 1: Prototypage** : 9-13 juin 2025
        - **Foire 2: Version beta** : 14-18 juillet 2025
        - **Présentation et rapport** : 11-15 août 2025

## Équipe

- Claudéric DeRoy

## Description du projet
- L'encodage cérébral permet de modéliser l'activité cérébral sachant un stimulus. Pour modéliser cette encodage, on utilise différent modèle comme une *Linear Support Vector Machine* (SVC) ou encore des *Random Forest* (RF) (Zhang et al., 2021) ou plus récemment le *Ridge Regression* (RR) (Ahmadi et al., 2024). décrire le pipeline de base du algonauts projets 2025

### Contexte
- Un parallèle intéressant est fait entre un réseau de neurone artificiel (*Artificial Neuron Network* (ANN)) et les réseaux neuronales du cerveau humain (citation).
### Problématique ou motivations
- Un des plus populaire modèle est le RR, toutefois il est lourd à entraîner (Ahmadi et al., 2024). De plus, le RR est difficilement interprétable.

### Proposition et objectifs
- Le but est donc de réduire la dimension du modèle utilisé, dans ce cas un RR,  par l'auto-encodage proposé par (Cunningham et al., 2023). La réduction de la dimensionnalité fait par l'auto-encodeur à matrice creuse s'effectue par l'extraction les caractéristiques les plus interprétables du modèle. Ensuite, un *Graph Convolutional Network* (GCN) permet de relier 

## Échéancier

!!! info
    Le suivi complet est disponible dans la page [Suivi de projet](suivi.md).

| Jalon (*Milestone*)            | Date prévue   | Livrable                            | Statut      |
|--------------------------------|---------------|-------------------------------------|-------------|
| Ouverture de projet            | 1 mai         | Proposition de projet               | ✅ Terminé  |
| Analyse des exigences          | 16 mai        | Document d'analyse                  | 🔄 En cours |
| Prototype 1                    | 23 mai        | Maquette + Flux d'activités         | ⏳ À venir  |
| Prototype 2                    | 30 mai        | Prototype finale + Flux             | ⏳ À venir  |
| Architecture                   | 30 mai        | Diagramme UML ou modèle C4          | ⏳ À venir  |
| Modèle de donneés              | 6 juin        | Diagramme UML ou entité-association | ⏳ À venir  |
| Revue de conception            | 6 juin        | Feedback encadrant + ajustements    | ⏳ À venir  |
| Implémentation v1              | 20 juin       | Application v1                      | ⏳ À venir  |
| Implémentation v2 + tests      | 11 juillet    | Application v2 + Tests              | ⏳ À venir  |
| Implémentation v3              | 1er août      | Version finale                      | ⏳ À venir  |
| Tests                          | 11-31 juillet | Plan + Résultats intermédiaires     | ⏳ À venir  |
| Évaluation finale              | 8 août        | Analyse des résultats + Discussion  | ⏳ À venir  |
| Présentation + Rapport         | 15 août       | Présentation + Rapport              | ⏳ À venir  |
