
## Apprentissage de représentations vectorielles des mots
- Skip-Gram avec échantillonnage négatif
  - Données
  - Modèle
  - Estimation des représentations des mots
    - Jeu de données
    - Maximisation de la vraisemblance pénalisée par échantillonnage négatif 
    - Estimation des vecteurs mots par descente de gradient stochastique
- Lien avec la mesure d'information mutuelle ponctuelle
- GloVe

## Convolution et réseaux de neurones convolutifs pour la classification textuelle
- Convolution d'un signal temporel par un noyau
  - Définition du produit de convolution dans le domaine temporel 
  - Définition du produit de convolution dans le domaine fréquentiel
    - Transformation de Fourier discrète 
    - Théorème de la convolution
    - Calcul rapide de la transformation de Fourier
- Architecture convolutive pour la classification de documents
  - Entrée
  - Couche de représentation des mots
  - Couches parallèles basées sur la convolution 
  - Couche de sous-échantillonnage
  - Couche de classification

## Réseaux de neurones récurrents pour la classification textuelle
- Cellule “Gated Recurrent Unit” (GRU)
  - Entrée
  - Porte réinitialisation (i.e. porte oubli/mémorisation)
  - État caché candidat
  - Porte mise-à-jour
  - Nouvel état caché
- Architecture pour la classification de documents
  - Entrée
  - Couche de représentation des mots
  - Couche récurrente GRU
  - Couche de classification

## Architecture Encodeur-Décodeur pour la génération de texte
- Encodeur
- Décodeur
  - Couche de classification
  - Début du décodage
  - Décodage auto-régressifs
- Limitation
- Mécanisme d’attention croisée
  - Couche d’attention croisée 
  - Couche de classification

## Mécanisme d'auto-attention multi-têtes et architecture Transformer

