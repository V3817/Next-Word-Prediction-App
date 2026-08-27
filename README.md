Next Word Prediction App

## Overview

This Streamlit app predicts the next word in a text sequence using a pre-trained LSTM model. It is designed to assist users in generating text continuations interactively.

## Features

- **Text Input**: Enter a sequence of words to predict the next word.
- **LSTM Model**: Utilizes a trained Long Short-Term Memory (LSTM) network for text prediction.
- **Dynamic Interaction**: Displays the predicted word in real-time upon user input.

## Setup Instructions

1. Clone the repository.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the following files in the project directory:
   - `new_word_lstm.h5`: Trained LSTM model file.
   - `tokenizer.pickle`: Tokenizer for text preprocessing.
4. Run the app:
   ```bash
   streamlit run app.py
   ```

## How to Use

1. Input a sequence of words in the provided text box.
2. Click the "Predict Next Word" button.
3. View the predicted word displayed below the input field.

## Example Usage

**Input**:  
`To be or not to`

**Output**:  
`Next word: be`

---

Generate text effortlessly and explore the power of LSTM models! 🌟
