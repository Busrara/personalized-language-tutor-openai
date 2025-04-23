# personalized-language-tutor-openai

**Personalized Language Tutor** is a Python-based application that uses **OpenAI's GPT-4** to give personalized language learning assistance. It basically provides grammar corrections, vocabulary suggestions, and generates quizzes for learners according to their text.

## Features

- **Grammar Correction**: Analyzes and corrects grammatical errors.
- **Vocabulary Suggestions**: Recommends alternative words or phrases with explanations for improvement.
- **Interactive Quizzes**: Gives multiple-choice quizzes based on vocabulary used in the text and provides follow-up quizzes according to incorrect answers.

## How it Works

1. **User Input**: You provide a piece of text in English (e.g., a paragraph).
2. **AI Processing**: GPT-4, using **OpenAI’s API**, processes the input and provides:
   - A grammatically corrected version of the text.
   - Vocabulary improvement suggestions.
   - A multiple-choice quiz based on the vocabulary in the text.
3. **Quiz Interaction**: After answering the quiz, follow-up questions are generated based on wrong answers to improve understanding.

## Requirements

- **Python 3.x**
- **OpenAI API Key**: You need an OpenAI API key to interact with GPT-4.

Read my Medium writing on this project to fully understand: https://medium.com/@busraracoban/creating-a-grammar-vocabulary-coach-with-python-and-openai-64c03997005d 

## Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/Busrara/personalized-language-tutor-openai.git
