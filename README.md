# Fine-tuning LLaMa 2 avec 4-bit Quantization et PEFT

Ce projet fournit un guide étape par étape pour effectuer le **fine-tuning du modèle LLaMa 2** en utilisant la **quantification 4 bits** et les **paramètres PEFT (Parameter-Efficient Fine-Tuning)**. Ces techniques permettent de rendre le fine-tuning plus efficace en termes de consommation mémoire et de temps d'entraînement, tout en maintenant des performances élevées.

## Fonctionnalités

- **Fine-tuning de LLaMa 2** : Guide détaillé pour fine-tuner le modèle LLaMa 2 avec des datasets personnalisés, y compris l'utilisation de la quantification 4 bits pour réduire la taille du modèle.
- **Quantification 4 bits (4-bit Quantization)** : Cette approche permet de réduire la taille du modèle tout en maintenant des performances proches de celles d'un modèle non quantifié, ce qui rend l'entraînement et l'inférence plus rapides et plus efficaces.
- **PEFT (Parameter-Efficient Fine-Tuning)** : Utilisation de techniques PEFT pour adapter uniquement certains paramètres du modèle au lieu de l'ensemble, permettant un fine-tuning plus rapide et plus léger.
- **Utilisation du dataset "guanaco-llama2-1k"** : Le modèle est fine-tuné sur le dataset **"guanaco-llama2-1k"**, un sous-ensemble du dataset **timdettmers/openassistant-guanaco**, spécifiquement traité pour le format des prompts de LLaMa 2.

## Prérequis

- Python 3.x
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- [PyTorch](https://pytorch.org/)
- [Datasets SQuAD ou tout autre dataset adapté](https://huggingface.co/datasets)
- Google Colab (facultatif, pour utiliser un GPU)
- [PEFT library](https://github.com/huggingface/peft) pour la gestion des paramètres PEFT.

## Installation

1. Clonez ce repository :
   ```bash
   git clone https://github.com/votre-nom-utilisateur/fine-tuning-llama-2-4bit-peft.git

   
<img width="529" alt="Capture" src="https://github.com/user-attachments/assets/229af0d3-7a2b-49e6-9f1a-9e2bf74a9391" />


