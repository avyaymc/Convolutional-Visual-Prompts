# Convolutional-Visual-Prompts
Convolutional Visual Prompts applied at the input and latent level to improve classification accuracy

## Project Description
This project applies convolutional visual prompts at the input and latent levels in a ResNet18 model. Initially trained on ImageNet, the model is fine-tuned and tested on CIFAR-10, including its corrupted version (CIFAR-10-C). The aim is to explore and optimize the use of visual prompts for enhanced model performance without having to retrain the model.

## Components
1. **Fine-Tuning ResNet18 on CIFAR-10**: Adapting the ImageNet-trained ResNet18 to CIFAR-10 data.
2. **Data Preparation - CIFAR-10-C**: Loading corrupted CIFAR-10 data from a drive.
3. **Model Evaluation**: Testing the model on CIFAR-10 and CIFAR-10-C without prompts.
4. **Convolutional Prompting at Latent Level**: Implementing a single random prompt at the latent level.
5. **Input Level Prompt Optimization (simpleoptimize)**: Optimizing input level prompts based on the referenced paper.
6. **Latent Level Prompt Optimization (latentoptimize)**: Enhancing latent level prompts.

