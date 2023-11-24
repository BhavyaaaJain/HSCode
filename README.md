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
   -Seperating the description into common part and unique part.
2. Encoding the input and descriptions using sentence Transformers.
3. Using another brands dataset.
4. Calculating cosine similarity between the input embeddings and descriptions embeddings.
6. Returning the top HS codes with the highest similarity scores.

## Prerequisites

Before running the code, ensure you have the following libraries and resources installed:

- Python 3.x
- Pandas
- Scikit-learn
- TensorFlow
- Sentence Transformers

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
