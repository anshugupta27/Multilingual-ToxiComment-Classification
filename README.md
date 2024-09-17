# Multilingual Toxic Comment Classification

## Project Overview

This project implements a **multilingual toxicity classifier** designed to detect harmful or offensive comments across various languages. Leveraging **BERT-based models** with **few-shot** and **zero-shot learning**, this classifier effectively handles multiple languages with minimal labeled data. It is evaluated using **GRU** and **Bidirectional LSTM** architectures with **GloVe embeddings** to enhance the classification of toxic comments.

## Key Features
- **Multilingual Toxicity Classification:** Utilized BERT-based models for toxic comment detection in multiple languages.
- **Few-shot & Zero-shot Learning:** Implemented advanced learning methods to detect toxicity with limited labeled data.
- **Model Performance:** Achieved an **AUC of 0.96** using GRU and **0.94** with Bidirectional LSTM, both utilizing GloVe embeddings.

## Technologies Used
- **Languages & Frameworks:**
  - Python
  - Keras
  - NumPy
  - Pandas

- **Libraries & Tools:**
  - TQDM (for progress bars)
  - Plotly (for data visualization)
  - Geopandas (for handling geospatial data)
  - GloVe (Global Vectors for Word Representation)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/anshugupta27/Multilingual-ToxiComment-Classification.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Multilingual-ToxiComment-Classification
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Train the Classifier:**
    ```bash
    python train.py --model bert --data data/multilingual_comments.csv
    ```

2. **Evaluate the Classifier:**
    ```bash
    python evaluate.py --model gru --data data/multilingual_comments.csv
    ```

3. **Visualize Model Performance:**
    ```bash
    python plot_results.py --model gru --metric auc
    ```

## Results

- **GRU Model:** Achieved an **AUC of 0.96** with GloVe embeddings.
- **Bidirectional LSTM Model:** Achieved an **AUC of 0.94** with GloVe embeddings.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or collaboration opportunities, feel free to reach out:
- **Email:** [rush2anshugupta@gmail.com](mailto:rush2anshugupta@gmail.com)
- **LinkedIn:** [Anshu Gupta](https://www.linkedin.com/in/anshu-gupta-471431190/)
