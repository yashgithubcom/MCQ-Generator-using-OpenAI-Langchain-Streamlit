```markdown
# MCQ-Generator-using-OpenAI-Langchain-Streamlit
This project uses OpenAI, Langchain, and Streamlit to create an interactive Multiple Choice Question (MCQ) generator. Users can input a topic to generate MCQs with options and answers. The user-friendly Streamlit interface and OpenAI's intelligent language processing make it easy to create and refine educational content.


## Project Structure
```
MCQ-Generator-main/
├── .gitignore
├── README.md
├── doubt.txt
├── mcq_training_data.txt
├── requirements.txt
├── response.json
├── setup.py
├── streamlit.py
├── experiments/
│   ├── machine_learning_quiz.csv
│   └── mcq.ipynb
└── src/
    ├── __init__.py
    └── mcqgenerater/
        ├── MCQgenerater.py
        ├── __init__.py
        ├── logger.py
        └── utils.py
```

## Features
- **MCQ Generation**: Generate MCQs from provided text using advanced natural language processing techniques.
- **Complexity Evaluation**: Assess the complexity of the generated MCQs.
- **Web Interface**: User-friendly web interface to interact with the MCQ generator.

## Installation
To install the necessary dependencies, run the following command:
```bash
pip install -r requirements.txt
```

## Usage
To use the MCQ generator, run the `streamlit.py` script:
```bash
streamlit run streamlit.py
```

## Configuration
You can configure various aspects of the project in the `setup.py` file and adjust logging settings in `src/mcqgenerater/logger.py`.

## Data
The project includes example training data (`mcq_training_data.txt`) and a sample response file (`response.json`).

## Experiments
The `experiments` directory contains a Jupyter notebook (`mcq.ipynb`) and a CSV file with machine learning quiz data (`machine_learning_quiz.csv`).

## Acknowledgements
We would like to thank the developers of LangChain and Streamlit for their excellent tools and frameworks. Also, ineuron, for giving us the opportunity to work on this project.

