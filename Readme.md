# IMDB Sentiment Classification with SimpleRNN (TensorFlow/Keras)

A minimal notebook/script that trains a SimpleRNN on the IMDB movie reviews dataset using `tensorflow.keras`.

## Features
- Loads IMDB dataset (`tensorflow.keras.datasets.imdb`)
- Token padding to fixed length (`tensorflow.keras.preprocessing.sequence`)
- SimpleRNN model with Embedding → SimpleRNN → Dense
- EarlyStopping callback (optional)
- Save model to `.h5` or `.keras`

---

## Requirements

1. Install dependencies:
   ```bash
   pip install -r requirements.txt

2. Run Open and run the simplernn.ipynb notebook.

