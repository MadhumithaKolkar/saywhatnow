# 🚀 SayWhatNow: LSTM-Based Next Word Predictor

**SayWhatNow** is a simple yet powerful LSTM-based next word prediction model trained on **space-related data**. The project demonstrates how deep learning (specifically RNNs using LSTM layers) can be used to predict the next most probable word in a sentence, given some initial input.

---

## 🧠 What It Does

This notebook trains a language model that:

- Tokenizes and vectorizes space-related text
- Builds sequences of words for supervised learning
- Uses an LSTM neural network to learn word order and context
- Predicts the **next word** given a seed input

Example:

> Input: `"The spacecraft is set to"`  
> Output: `"launch"`

---

## 📚 Data

The training data is themed around **space exploration, NASA missions, astronomy, and sci-fi text**, giving the model a niche vocabulary and context.

You can easily adapt this to any domain by changing the input corpus.

---

## 🛠️ How to Use

### 1. Clone the repository

```bash
git clone https://github.com/MadhumithaKolkar/saywhatnow.git
cd saywhatnow
2. Set up your environment
We recommend using a virtual environment:

python3 -m venv venv
source venv/bin/activate
3. Install dependencies

pip install numpy pandas tensorflow keras matplotlib nltk
(You may also run nltk.download('punkt') in the notebook.)

4. Run the notebook

jupyter notebook saywhatnow.ipynb
Follow the cells to:

Load and clean the data

Tokenize and vectorize sentences

Train the LSTM model

Predict next words for custom inputs

📈 Model Architecture
Embedding Layer

LSTM Layer

Dense (Softmax) Output

Model learns from sequences of words and generalizes their order and context.

🔮 Sample Usage
Once trained, try running:

predict_next_word("The stars are")
# Output: "aligning"
📁 Project Structure

saywhatnow/
│
├── saywhatnow.ipynb        # Main notebook
├── README.md               # Project overview
└── requirements.txt        # (Optional) dependencies
✍️ Contributing
Feel free to fork this repo, improve the model, or try different corpora (e.g., medical, legal, fantasy).

📄 License
This project is under the MIT License. Use it, learn from it, remix it freely.

🙋‍♀️ Author
Created by Madhumitha Kolkar — passionate about NLP, GenAI, and exploring how machines can speak our language.

“The cosmos is within us. We are made of star-stuff. We are a way for the universe to know itself.” — Carl Sagan

Would you like me to also generate a `requirements.txt` for this based on typical LSTM NLP projects?
