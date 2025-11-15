# Generative-AI-Essentials
Character-level text generation using LSTM trained on Alice in Wonderland. Includes model training, checkpointing, inference, and loss visualization. Explores GPT architecture, generative AI applications, and ethical considerations in modern NLP.
# Generative AI Text Modeling Project

This repository contains a hands-on exploration of Generative AI using a character-level LSTM model trained on *Alice in Wonderland*. The project demonstrates how deep learning models can generate coherent text sequences and introduces key concepts behind Generative Pre-trained Transformers (GPTs). It includes model training, inference, visualization, and a conceptual comparison between LSTM and GPT architectures. Ethical considerations and real-world applications of generative models are also discussed.

---

## Project Overview

This project was completed as part of a Generative AI assignment and includes the following tasks:

### Task 1: Dataset Preparation
- Downloaded and cleaned *Alice in Wonderland* from Project Gutenberg.
- Tokenized the text at the character level.
- Created mappings for character-to-index and index-to-character.

### Task 2: Model Training
- Built a sequential model using TensorFlow/Keras: `Embedding → LSTM → Dense`.
- Trained the model using sparse categorical crossentropy.
- Saved model checkpoints for later inference.
- Compared LSTM architecture with GPTs, highlighting differences in attention and sequence modeling.

### Task 3: Text Generation
- Rebuilt a stateful version of the model for inference.
- Implemented a temperature-controlled text generation function.
- Demonstrated output using seed inputs and varying temperature values.

### Task 4: Documentation and Reporting
- Explained the significance of Generative AI.
- Described GPT architecture and functionality.
- Summarized methodology and findings from model training.
- Discussed applications and ethical considerations.
- Provided conclusions and future perspectives.

---

## Setup Instructions

### Option 1: Run in Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload and open `Assignment 13 - Generative AI Essentials.ipynb`
3. Run all cells sequentially

### Option 2: Run Locally

#### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Generative-AI-Essentials.git
cd Generative-AI-Essentials
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
3. Run the notebook Open `Assignment 13 - Generative AI Essentials.ipynb` in Jupyter or Colab.

4. Generate text Modify the `seed_text` and `temperature` in the example cell to experiment with different outputs.

Repository Structure
├── data/                                             # Raw and processed text files
├── checkpoints/                                      # Saved model weights
├── Assignment 13 - Generative AI Essentials.ipynb    # Main notebook
├── README.md                                         # Project documentation


Author
Ifedolapo
Business Intelligence Analyst student at Willis College, Ottawa
Focused on NLP, scalable analytics workflows, and ethical AI applications.

