# Finetune-language-model-with-ParlAI
Code and experiment for finetuning Blenderbot-90M with ParlAI toolkit

1. Introduction
This project aims to finetune Blenderbot 90M [1] on recent datasets and measure the improvement of the model in the general chit-chat domain. The finetuning of the model on all datasets has been completed.

2. Problem Formulation
This project focuses on Dialog modeling and conversational AI/ML task. The Blenderbot 90M parameter model was released in 2020 by Facebook. The base model used in this project has been pre-trained on the Blended Skill talk (BST)[5] dataset. The model serves as a good baseline for testing the efficacy of recent conversational datasets.

4. Dataset and Experiments
   
    •Datasets: daily dialog [2], ConvAi2 [3], a subset of Wizard of Wikipedia [4]

    •Test data: 500 samples from the test sets

    •Hardware environment: Nvidia A100 40GB rented through Google Colab

    •Model parameters: 90M parameters

    •Training settings: 20 epochs for finetuning and, Adam Optimizer

5. Results and Discussions:
   
    • Results and discussion are in the final report.
    • Raw Evaluation outputs are in the Evaluation_outputs folder.
7. Key references:
   
    1. Roller, Stephen, et al. "Recipes for building an open-domain chatbot." arXiv preprint arXiv:2004.13637 (2020).
    2. Rashkin, Hannah, et al. "Towards empathetic open-domain conversation models: A new benchmark and dataset." arXiv preprint arXiv:1811.00207 (2018).
9
    3. Zhang, Saizheng, et al. "Personalizing dialogue agents: I have a dog, do you have pets too?." arXiv preprint arXiv:1801.07243 (2018).
    4. Dinan, Emily, et al. "Wizard of wikipedia: Knowledge-powered conversational agents." arXiv preprint arXiv:1811.01241 (2018).
    5. Smith, Eric Michael, et al. "Can you put it all together: Evaluating conversational agents' ability to blend skills." arXiv preprint arXiv:2004.08449 (2020).
