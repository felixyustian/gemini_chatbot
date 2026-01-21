# Gemini Chatbot (Jupyter Notebook Implementation)


This repository contains a standalone Jupyter Notebook designed to test and demonstrate the capabilities of a custom chatbot using Google's **Gemini API**. It serves as a testing ground for refining prompts, managing conversation history, and integrating with Google Cloud Platform (GCP).

## 📄 Repository Contents

* `Gemini_Part_2_Revamped.ipynb`: The primary notebook containing the Python code for initialization, API interaction, and chat logic.

## 🚀 Overview

The project provides a step-by-step interactive environment to:
1.  Authenticate with Google Cloud / Gemini API.
2.  Initialize the Generative AI model.
3.  Simulate a chat session with maintained context/history.
4.  Experiment with different system instructions (prompts) to alter the bot's persona.

## 🛠️ Technology Stack

* **Language**: Python 3.x
* **Environment**: Jupyter Notebook / Google Colab
* **API**: Google Generative AI (Gemini)
* **Infrastructure**: Google Cloud Platform (GCP)

## 📋 Prerequisites

To run this notebook successfully, you will need:

* **Python 3.9+** installed.
* **Jupyter Notebook** or access to **Google Colab**.
* A valid **Google Cloud Project** with Vertex AI enabled, OR a **Gemini API Key** from Google AI Studio.

## 🔧 Installation & Usage

### Option 1: Running Locally
1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/felixyustian/gemini_chatbot.git](https://github.com/felixyustian/gemini_chatbot.git)
    cd gemini_chatbot
    ```

2.  **Install Dependencies**
    You will likely need to install the Google Generative AI SDK. Run this command in your terminal (or inside a notebook cell):
    ```bash
    pip install google-generativeai jupyter
    ```

3.  **Launch Jupyter**
    ```bash
    jupyter notebook Gemini_Part_2_Revamped.ipynb
    ```

4.  **Execute Cells**
    Follow the instructions within the notebook. You may need to insert your API key or configure your GCP credentials in the first few cells.

### Option 2: Google Colab
1.  Upload the `Gemini_Part_2_Revamped.ipynb` file directly to [Google Colab](https://colab.research.google.com/).
2.  Set your runtime secrets (API Key) or authenticate via the provided Colab authentication cells.
3.  Run the notebook.

## 📄 License

This project is distributed under the **GPL-3.0 License**. See the `LICENSE` file for more details.
