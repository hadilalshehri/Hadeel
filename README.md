# Arabic Sentiment Analysis using Different Versions of BERT

This project aims to develop a machine learning model that can perform sentiment analysis on Arabic text using different versions of BERT (Bidirectional Encoder Representations from Transformers). The models are trained on a dataset of labeled Arabic text and use pre-trained BERT language models to extract features and classify the text as either positive, negative, or neutral.

The dataset used is
- ARcSarcasm 
- Saudi Data

Three different  Bert Version used to compare them 
- AraBert ( common and standard Arabic BERT)
- MarBert ( This version have Effective on Saudi Dialect) 
- FastAraBert ( Fast verion of Ara Bert )

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
- `Arcsarsesm` - This is the dataset of labeled Arabic text used to train the models.
- `Saudi Data` - This is the dataset of labeled Saudi dialect text used to train the models.


## Contributing

Contributions to this project are welcome. If you would like to contribute, please fork the project and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
