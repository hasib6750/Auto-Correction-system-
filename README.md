
# Ai Auto corrector

This repository contains a Python-based spell checker that leverages edit distance algorithms to suggest correct spellings for misspelled words. The implementation includes functions for generating edits at various levels, calculating word probabilities from a large corpus, and testing the accuracy of the correction algorithm using provided test datasets.

## Features
- **Word Probability Calculation**: Reads from `big.txt` to compute word frequencies and probabilities.
- **Edit Distance Algorithms**: Supports single-level (`edit_lvl_1`) and double-level (`edit_lvl_2`) corrections using deletion, insertion, swapping, and replacement.
- **Accuracy Testing**: Compares suggested corrections against multiple test sets (`wikipedia.txt`, `aspell.txt`, etc.) to evaluate performance.
- **Interactive Mode**: Allows users to input words and receive correction suggestions.

## Usage
- Run `read_text()` to process a corpus and create word probability distributions.
- Use `tester()` to evaluate the accuracy of the spell checker with different test files.
- Input words interactively for correction suggestions with `word_correction()`.

## Visualization
- Includes a plotting function using `matplotlib` to display the accuracy percentages of test results.

## Requirements
- Python 3.x
- `numpy`, `matplotlib`

## Future Enhancements
- Extend the corpus for better language model accuracy.
- Optimize edit distance generation for performance.

Feel free to clone, modify, and contribute to improve this spell-checking tool!

---

Would you like any specific details or sections added to this description?
