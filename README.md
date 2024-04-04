# RNN Text Generation

This project demonstrates text generation using a Recurrent Neural Network (RNN) implemented in PyTorch.

## Overview

The project aims to generate text based on a given input sequence. It utilizes a character-level RNN, which predicts the next character in a sequence. The model is trained on a small dataset of text and learns to generate text similar to the input.

## Dependencies

- Python 3.x
- PyTorch
- NumPy

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/your_username/rnn-text-generation.git
    ```

2. Navigate to the project directory:

    ```
    cd rnn-text-generation
    ```

3. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Prepare your text dataset and update the `text` variable in the `rnn_text_generation.py` script with your data.

2. Run the script:

    ```
    python rnn_text_generation.py
    ```

3. The script will train the RNN model and generate text based on the provided input.

## Example

Input: 'good'
Output: 'good i am fine '
