# HSCode

# Commodity Description to HS Code Matcher

This project is designed to match commodity descriptions to Harmonized System (HS) codes using a combination of keyword extraction, similarity calculations, and BERT embeddings.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to provide a method for matching commodity descriptions to HS codes. It achieves this using the following steps:

1. Preprocessing commodity descriptions, including:
   - Removing special characters and digits.
   - Removing stop words.
2. Keyword extraction for each chapter based on TF-IDF scores.
3. Finding the best chapter match based on Jaccard similarity with input keywords.
4. Encoding the input and descriptions using BERT embeddings.
5. Calculating cosine similarity between the input and descriptions.
6. Returning the top 5 HS codes with the highest similarity scores.

## Prerequisites

Before running the code, ensure you have the following libraries and resources installed:

- Python 3.x
- Pandas
- NLTK
- Scikit-learn
- TensorFlow
- TensorFlow Hub
- TensorFlow Text
- spaCy
- Pretrained BERT model (downloaded and linked in the code)

You can install most of these dependencies using `pip` or `conda`.

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/HSCode.git
   cd commodity-hs-matcher
2. Install the required dependencies.
3. Run the code
4. Enter a commodity description as input.
5. The code will output the top 5 matching HS codes and their respective similarity scores.
