# 🧠 Next Word Prediction with LSTM
A deep learning-based NLP app that predicts the next word in a given text sequence using an LSTM neural network trained on Shakespeare's Hamlet.

## 📚 Overview
This project showcases a neural network model capable of predicting the next word in a sequence of text, leveraging a Long Short-Term Memory (LSTM) network. The model is trained on the complete text of Hamlet by William Shakespeare and deployed using Streamlit for interactive use.

This project showcases a neural network model capable of predicting the next word in a sequence of text, leveraging a Long Short-Term Memory (LSTM) network. The model is trained on the complete text of Hamlet by William Shakespeare and deployed using Streamlit for interactive use.

## 🔍 Key Features
* LSTM-based sequence prediction model

* Trained on classic literature (Hamlet)

* Interactive interface powered by Streamlit

* Real-time next-word prediction

* Model training includes early stopping for optimization

## 🛠️ Technologies Used

* Python

* TensorFlow / Keras

* Streamlit

* Numpy, Pickle

* Natural Language Processing

* Dataset: hamlet.txt (Shakespeare)


## 🚀 Project Structure

* experiments.ipynb: Main notebook used to train the LSTM model and save artifacts:

  - Next_word_lstm.h5 – Trained LSTM model

  - tokenizer.pickle – Fitted tokenizer for input preprocessing

* app.py: Streamlit application that:

  - Loads the trained model and tokenizer

  - Accepts user input

  - Predicts the next word in real time

* hamlet.txt: Training corpus – the complete text of Hamlet

## ⚙️ How It Works
1. Text Input: Users input a sequence (e.g., “To be or not to”).

2. Tokenization: Text is converted into tokens using a pretrained tokenizer.

3. Sequence Padding: The token list is padded to match the model's input shape.

4. Prediction: The LSTM model predicts the probability distribution of the next word.

5. Output: The word with the highest probability is returned.

## 🌐 Live Demo
🖥️ Try the App:
https://nextwordpredictionbybhaskarkumbhar.streamlit.app/

## 📥 Installation (Local)
```
git clone https://github.com/bhaskar2311/next-word-prediction
cd next-word-prediction
pip install -r requirements.txt
streamlit run app.py
```

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/e401459f-9bc2-4be3-ba40-15f0f73830a0)

## 📝 Notes
This project was fully developed by me. The README was written based on my knowledge and experience, with support from generative AI tools to refine its structure and presentation.

## 📄 License
This project is open source and available under the MIT License.

## 🙋‍♂️ Author
Made with ❤️ by Bhaskar Shivaji Kumbhar


