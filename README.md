## Next Word Predictor using LSTM

This project utilizes an LSTM (Long Short-Term Memory) model for next-word prediction. By training on a sequence of words, the model learns the likelihood of subsequent words, enabling it to predict the next word in a sequence accurately.

### Features

* **Deep Learning with LSTM:** Employs an LSTM neural network to model sequential dependencies in text.
* **Text Generation:** Predicts the next word in a sentence or phrase based on learned patterns.
* **Customizable Training Data:** Can be trained on various text sources for specific use cases (e.g., formal text, casual conversation).

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/RohitRao7722/Next_word_preditor-using--LSTM.git
   cd Next_word_preditor-using--LSTM
   ```

2. **Install dependencies:**

   ```bash
   pip install tensorflow numpy pandas
   ```

### Usage

To run the next-word predictor, open the Jupyter notebook file `next_word_predictor.ipynb` and execute the cells in order. This will train the model (if not already trained) and allow you to input text for prediction.

### Example Usage

After loading the notebook, you can provide an input like:

```
"The quick brown fox"
```

and the model might predict:

```
"jumps" 
```

### Model Overview

* **`next_word_predictor.ipynb`:** Jupyter notebook containing the entire pipeline, from data preprocessing and model training to prediction and evaluation.

### Contributing

Contributions are welcome! Please open an issue to 
