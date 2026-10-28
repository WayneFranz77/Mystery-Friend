# Mystery Friend

A text-classification project that uses scikit-learn to guess which of three
authors wrote an anonymous postcard. The exercise uses a bag-of-words
representation and a Multinomial Naive Bayes classifier.

## Project structure

```text
Mystery Friend/
├── Mystery Friend.ipynb             # Completed exercise
├── Mystery Friend_Solution.ipynb    # Reference solution
├── goldman_emma_raw.ipynb           # Emma Goldman writing samples
├── henson_matthew_raw.ipynb         # Matthew Henson writing samples
├── wu_tingfang_raw.ipynb            # TingFang Wu writing samples
├── .gitignore
├── LICENSE
└── README.md
```

Keep the writing-sample notebooks in the project root: the exercise notebook
imports them as Python modules with `import_ipynb`.

## Getting started

1. Install Python.
2. Install the project dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Open `Mystery Friend.ipynb` in Jupyter and run its cells from top to bottom.

The final exercise cell also displays the classifier's estimated probabilities
for each author. Edit `mystery_postcard` to try other writing samples.

## License

This project is available under the MIT License. See [LICENSE](LICENSE).
