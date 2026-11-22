# Projet GenAI — Génération d'images avec GANs et VAE

Projet du cours *Generative AI for Computer Vision* (énoncé : `IA_Gen_project-1.pdf`).

## Partie 1 — DCGAN sur Quick Draw (moutons)

Notebook : `partie1_dcgan.ipynb` (exécuté, avec toutes les sorties)  
Rapport : `rapport_partie1_dcgan.docx`

- `modules/` : classes `DCGAN`, `WGANGP` et `ImagesCallback` fournies.
- Les données (`QuickDraw/origine/sheep.npy`, 126 121 dessins 28×28) sont téléchargées automatiquement par le notebook si elles sont absentes.
- Les sorties (images par epoch, figures, modèles `.h5`) sont écrites dans `run/SHEEP1/`.

### Exécution sur Google Colab

1. Copier le dossier du projet dans Google Drive sous `MyDrive/projet_genai`.
2. Ouvrir `partie1_dcgan.ipynb` dans Colab, choisir un environnement d'exécution GPU.
3. Tout exécuter. La première cellule monte le Drive et installe `fidle`.

### Exécution locale

```
pip install -r requirements.txt
jupyter notebook partie1_dcgan.ipynb
```

Sous Windows natif, TensorFlow ≥ 2.11 n'utilise pas le GPU. L'entraînement complet (10 epochs) prend environ 10 min sur GPU contre plusieurs heures sur CPU.

## Parties 2 et 3

À venir.
