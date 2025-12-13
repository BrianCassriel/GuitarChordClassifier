# GuitarChordClassifier
Final project for CPSC 393 - Machine Learning

This model predicts with ~65% accuracy on the test set which chord is being played in a given audio sample. Chords are pigeonholed into the 12 main notes.

## Setup
1. Clone the repository.
2. Download the IDMT-SMT-Guitar-V2 database from [here](https://zenodo.org/records/7544110) and extract it into the root directory of the project.
3. Create a virtual environment and install the required packages:
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
4. Use `guitar_chord_classifier.ipynb` to preprocess the data, train the model, and evaluate its performance.