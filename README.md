# Markov Chain Generator

This project is a simple HTML application that generates new sentences from input text using a Markov Chain.

## Overview
- Generates sentences starting from a specified starting word.
- Selects the next word based on transition probabilities between words.
- Easy to try with a simple UI.

## How to Use
1. Open `markov_chain.html` in your browser.
2. Enter a starting word.
3. Enter the length of the sentence.
4. Click the "Generate" button to display the generated result.

## Specifications
- Input data is defined in `inputData` within JavaScript.
- Sentences are split and processed word by word to calculate word transition probabilities.
- Determines the next word using random numbers and weighted selection.

## Key Elements
- `inputData`: Training text data
- `storedData`: Word transition information
- `storedPercentageData`: Transition probabilities for each word
- `generate()`: Sentence generation process
- `weightedChoice()`: Weighted random selection process

## Notes
- The starting word must be a word that exists within the input data.
- Assumes input is in lowercase.
- Because generation results are random, different sentences may be produced each time.

## File Structure
- `markov_chain.html`: Main file containing HTML, JavaScript, and styles
- `favicon.svg`: Page favicon

## Example
Input:
- Starting word: `english`
- Length: `10`

Output Example:
- `english is a ...`

## Supplementary Notes
This code is created for learning and demonstration purposes, and is a simplified version compared to practical natural language generation tools.
README.md
「README.md」を表示しています。
