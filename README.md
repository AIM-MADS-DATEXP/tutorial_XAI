# README

This repository contains a notebook with examples of the methods for XAI discussed in the lecture. 

# Running the tutorials

To run the tutorial locally execute the following code in a terminal. For google colab you will only need to run the first two lines preceeded by an exclamation mark.

```bash

# Clone the repository with following code or download it manually
git clone https://github.com/AIM-MADS-DATEXP/tutorial_XAI.git

# Navigate into the project directory
cd tutorial_XAI

# (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # On macOS/Linux
venv\Scripts\activate           # On Windows

# Install dependencies from requirements.txt
pip install -r requirements.txt

```

# Resources
The dataset is from:  https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset
You can find more information here: https://christophm.github.io/interpretable-ml-book/data.html 
SHAP: https://shap.readthedocs.io/
LIME: https://lime-ml.readthedocs.io/en/latest/
