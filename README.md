# IMBD_Sentiment_Analyzer
This project performs sentiment analysis on IMDB movie reviews using an RNN . It classifies reviews as positive or negative based on textual data. Built with TensorFlow, Keras, and NLP techniques, it helps analyze audience opinions.

##  Features  
- Preprocessing of IMDB movie reviews  
- Word embedding using Keras' `Embedding` layer  
- Sentiment classification using **SimpleRNN**  
- Model evaluation with accuracy and loss metrics  

🔗 **(https://imbdsentimentanalyzer.streamlit.app/)**  

## How to Use  
1. Enter a movie review in the text box.  
2. Click **"Predict Sentiment"**.  
3. The model will classify the review as **Positive** or **Negative**.  

## Technologies Used  
- **Python**  
- **TensorFlow & Keras** (Simple RNN)  
- **Streamlit** (for deployment)  
- **Pandas & NumPy** (data processing)  
- **NLTK** (text preprocessing)  
- **Git & GitHub** (version control)

##  Model Overview  
- **Embedding Layer**: Converts words into dense vectors.  
- **Simple RNN**: A basic recurrent neural network to process sequential data.  
- **Dense Layer**: Final classification with a **sigmoid activation function**.  

##  Installation & Running Locally  
To run the app locally, follow these steps:  

```bash
# Clone the repository
git clone https://github.com/SanjanaDuraiswamy/IMBD_Sentiment_Analyzer.git
cd IMBD_Sentiment_Analyzer

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run main.py



