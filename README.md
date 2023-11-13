# Neural Machine Translation (English to Hindi)

This repository contains an implementation of a Neural Machine Translation (NMT) model for translating English sentences into Hindi. The model is built using the Seq2Seq architecture with Long Short-Term Memory (LSTM) networks.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Keras

## Dataset

The dataset used for training and testing the NMT model is the "Hindi_English_Truncated_Corpus" dataset. It has been preprocessed and filtered to focus on a specific source ("ted") and exclude any null values or duplicates.

## Preprocessing Steps

The dataset undergoes several preprocessing steps to clean and format the text data, including:
- Lowercasing
- Removal of special characters and digits
- Tokenization
- Padding sequences

## Model Architecture

The NMT model architecture consists of an Embedding layer, LSTM layers for both encoder and decoder, and a Dense output layer with softmax activation. The model is trained using the RMSprop optimizer and categorical crossentropy loss.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
