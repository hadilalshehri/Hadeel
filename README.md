# Arabic Sentiment Analysis using Different Versions of BERT

This project aims to develop a machine learning model that can perform sentiment analysis on Arabic text using different versions of BERT (Bidirectional Encoder Representations from Transformers). The models are trained on a dataset of labeled Arabic text and use pre-trained BERT language models to extract features and classify the text as either positive, negative, or neutral.

## Getting Started

To get started with this project, you will need to have Python 3 installed on your computer. You will also need to install the following Python libraries:

- transformers
- pandas
- numpy
- scikit-learn

You can install these libraries using pip, as follows:

```
pip install transformers
pip install pandas
pip install numpy
pip install scikit-learn
```

Once you have installed the required libraries, you can run the sentiment analysis models by running the `arabic_sentiment_analysis.py` file. The models will prompt you to enter an Arabic text, and they will then classify the text as either positive, negative, or neutral using different versions of BERT.

## Project Structure

The project is structured as follows:

- `arabic_sentiment_analysis.py` - This is the main script that runs the sentiment analysis models using different versions of BERT.
- `data.csv` - This is the dataset of labeled Arabic text used to train the models.
- `data_processing.py` - This module contains functions for processing and cleaning the text data.
- `model_training.py` - This module contains functions for training and evaluating the machine learning models using different versions of BERT.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please fork the project and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
