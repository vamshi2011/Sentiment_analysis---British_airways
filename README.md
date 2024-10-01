# Sentiment_analysis---British_airways
This project takes a sentence as an input and predicts the polarity or the **sentiment** of the sentence based on the words used in the sentence. We have used a pretrained model using a pipeline from hugging face called **sentiment analyser** that takes a sentence and gives its polarity along with its sentiment score(confidence score).

# Required Libraries
1. Transformers
2. Numpy
3. Pandas
4. Matplotlib

# Features 
- **Pretrained model**: The data is directly fed to a pretrained model that classifies the sentence and give its sentiment and its sentiment score.
- **Visualizations**: Using matplotlib, we can visualize the number of positive sentences and number of negative sentences.

# Dataset
The dataset consists of customer reviews made on a online platform. Its just text and its corresponding numbering.

**No preprocessing is needed. The dataset is directly fed to the model and the model gives the sentiment and its sentiment score.**

**The main idea of this project is to know how the customers think about the organization and we have to know that using the large number of online reviews.**

# Instructions
1. **Clone the repo**
   ```bash
   git clone https://github.com/vamshi2011/Sentiment_analysis---British_airways.git
   ```
2. **Launch the application**
   You can directly click on the **sentiment_analysis.ipynb** file. It shows **Open in collab** on the top right. Click on it and it will directly open the project in **Google collab**.
Else you can download the file by cloning the repo and open it in any IDE locally.
