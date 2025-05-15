# Projet IFT3150: [Méthode interprétable par auto-encodeur creux pour l'encodage de l'activité cérébrale IRMf](https://github.com/neurok8050/template-projet)

> **Thèmes**: Neuro-imagerie, Science des données, Apprentissage-machine  
> **Superviseur**: Pierre Lune Bellec  
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
-  *The Algonauts Project* 2025 est une compétition amicale internationale qui consiste en un défi où des chercheur(e)s doivent élaborer un modèle d'encodage de l'activité cérébrale humaine issu de stimuli multimodaux (i.e. stimulus visuel, auditif et langagier). Toutefois, les stimuli ne sont pas sous une forme utilisable pour un modèle d'AM. Il faut donc extraire des stimuli des caractéristiques qui pourront être utilisable par un AM. Dans ce cas, les caractéristiques extraitent sont volumineuses et il est donc préférable d'en réduire la dimension le plus possible. L'algorithme de base pour effectuer cette réduction de dimensionnalité est une *Principal Component Analysis* (PCA). Une fois la dimension effectue, les données sont utilisées avec les données d'activité cérébrale afin d'élaborer un encodeur de l'activité cérébrale. Un des modèles les plus utilisés est le *Ridge Regression* (RR).

### Contexte
- Depuis 2019, *The Algonauts Project* offre à chaque année un défi sous forme de projet afin de faciliter la coopération entre les chercheur(e)s en biologie et en apprentissage machine (AM). Cette année, le défi est trouver un modèle AM qui permet de bien encoder l'activité cérébrale humain provenant de l'exposition à des stimuli multimodaux (i.e. visuel, auditif et langagier).
### Problématique ou motivations
- La méthode courament utilisé pour réduire la dimension des caractéristiques extraites des stimuli multimodaux est la PCA. Malgré la réduction de dimensionalité issu de la PCA, le RR obtenu contient des milliards de paramètres et est donc difficilement interprétable et long à entraîner. 

### Proposition et objectifs
- Nous voulons changer la PCA qui est le plus souvent utilisé afin de réduire la dimension des caractéristiques extraite des stimuli multimodaux par un auto-encodeur à matrice creuse. Ce modèle permettrait d'obtenir une réduction des caractéristiques meilleure et donnerait des résultats plus interprétable avec le RR.

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
