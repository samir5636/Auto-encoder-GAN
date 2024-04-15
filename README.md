# Projet PyTorch - Auto-encodeurs et GANs

Ce projet consiste à implémenter des auto-encodeurs (AE), des auto-encodeurs variationnels (VAE) et des réseaux génératifs antagonistes (GANs) en utilisant la bibliothèque PyTorch. Les modèles seront entraînés sur l'ensemble de données MNIST pour les AE et VAE, et sur un ensemble de données d'art abstrait pour les GANs.

## Partie 1: AE et VAE

### 1. Architecture de l'auto-encodeur (AE)
- Le fichier `autoencoder.py` contient l'implémentation de l'architecture de l'AE.
- Les hyperparamètres optimaux sont définis dans le fichier `parameters.json`.

### 2. Architecture de l'auto-encodeur variationnel (VAE)
- Le fichier `variational_autoencoder.py` contient l'implémentation de l'architecture du VAE.
- Les hyperparamètres optimaux sont également définis dans `parameters.json`.

### 3. Évaluation des modèles AE et VAE
- Le notebook Jupyter `evaluation.ipynb` contient les analyses des performances des modèles, y compris les courbes de perte et de divergence KL.

### 4. Visualisation de l'espace latent
- Le notebook `latent_space_visualization.ipynb` présente la visualisation de l'espace latent des modèles AE et VAE.

## Partie 2: GANs

### 1. Implémentation des GANs
- Les fichiers `generator.py` et `discriminator.py` contiennent les implémentations du générateur et du discriminateur GAN.
- Le fichier `gan.py` gère l'entraînement du GAN.

### 2. Évaluation du modèle GAN
- Le notebook `gan_evaluation.ipynb` évalue les performances du générateur et du discriminateur.

### 3. Génération de nouvelles données
- Le notebook `data_generation.ipynb` génère de nouvelles données à l'aide du générateur GAN et les compare aux données originales.


