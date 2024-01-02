# Apprentissage-artificiel
Projet pour *Apprentissage artificiel*

### Contribueurs du groupe
> CHENG Weixuan, GUI Kexin, Huang Yidi


## Objectif  
Proposer un (des) classifieur(s) pour cette tâche, étudier ses (leurs) performances sur cette tâche. Comparer aux informations données dans les actes.

## Comment ça marche ?

1. Extraction : 
    - `Scripts/extraction.py`
2. Prétraitement des données : 
    - Outils : **spaCy** 
    - Script : `Scripts/prétraitement.py`
    - Données : `corpus_prétraité/`
3. Entraînement des modèles (classifieur)
    1. **Modèle 1** : Régression logistique
        - Script : `Scripts/classifieur_lg`
        - Résultat (image) : `résultats/martice_de_confusion_lg` <br>
    Résultat (Métriques) : `résultats/rapport_classification_lg`
