| Étudiante        | Travail principal                                 | Pondération |
| ---------------- | ------------------------------------------------- | ----------- |
| **Yasmine**      | Préparation des données + Introduction du rapport | 33 %        |
| **Roua**         | Feature engineering + Modélisation GNN            | 33 %        |
| **Maherinirina** | Analyses post-hoc + Conclusion                    | 33 %        |


##  Projet 12 — Prédiction de centralité sur le réseau social Pokec

Ce projet étudie le réseau **Pokec**, un ancien réseau social slovaque, pour évaluer la capacité des modèles de réseaux de neurones de graphes (**GNN**) à prédire des mesures structurelles telles que la **centralité de proximité** des utilisateurs.

### 📂 Structure du projet

```
projet-12/
│
├── projet-12-1.ipynb           # Notebook principal (ancienne version)
├── projet-12-1-merged.ipynb    # Version corrigée et améliorée
│
└── dataset/
    ├── soc-pokec-profiles.txt
    └── soc-pokec-relationships.txt
```

###  Dépendances nécessaires

Ce projet utilise :

* Python ≥ 3.10
* PyTorch ≥ 2.0
* PyTorch Geometric ≥ 2.5
* scikit-learn, seaborn, matplotlib, pandas, numpy, umap-learn, community (python-louvain), networkx

Installation typique :

```bash
pip install torch torch-geometric scikit-learn pandas numpy seaborn matplotlib umap-learn python-louvain networkx
```

###  Jeu de données requis

Le jeu de données **Pokec** doit être téléchargé depuis le site officiel de Stanford SNAP :

🔗 **[https://snap.stanford.edu/data/soc-pokec.html](https://snap.stanford.edu/data/soc-pokec.html)**

Tu dois placer les deux fichiers suivants dans un sous-dossier nommé `dataset/` :

* `soc-pokec-profiles.txt`
* `soc-pokec-relationships.txt`


