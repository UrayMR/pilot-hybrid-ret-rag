# Hybrid Retrieval RAG - Question Answering System

## Description

This project is the implementation of Hybrid Retrieval with BGE-M3 Model for Question Answering System using Retrieval-Augmented Generation (RAG) approach.

## Requirements

- Python 3.10 or newer
- pip
- Internet access for installing dependencies (if required)

## Embedding Model

This project uses the BGE-M3 model for generating embeddings. You can find more information about the model [here](https://huggingface.co/BAAI/bge-m3).

## Datasets

This project using QASPER (dataset for question answering on scientific research papers). You can find more information about the dataset [here](https://huggingface.co/datasets/allenai/qasper).

## LLM Generation Model

This project uses the LongChat-7B-v1.5-32k model for generating answers. You can find more information about the model [here](https://huggingface.co/lmsys/longchat-7b-v1.5-32k/tree/main).

## Setup

Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/Scripts/activate
```

On Windows PowerShell, you can use:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Then install the project dependencies:

```bash
pip install -r requirements.txt
```

If the project uses additional libraries, install them as needed:

```bash
pip install numpy pandas scikit-learn
```

## Run the Project

After the environment is activated and dependencies are installed, run the notebook or script to start

```bash
python app.py
```

## Project Structure

```text
.
├── README.md
├── requirements.txt
├── .venv/
├── src/
│   ├── app/
│   └── data/
└── ...
```

## Notes

This project is intended as an pilot implementation of a hybrid retrieval system for question answering.
