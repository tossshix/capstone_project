Capstone project for RS School Machine Learning course.

This demo uses [Forest cover type](https://www.kaggle.com/competitions/forest-cover-type-prediction) dataset.

# Usage
This package allows you to train model for detecting the forest cover type.
1. Clone this repository to your machine.
2. Download forest cover type dataset, save csv locally (default path is *data/forest.csv* in repository's root).
3. Make sure Python 3.9 and Poetry are installed on your machine (I use Poetry 1.1.11).
4. Run train with the following command:
```bash
poetry run train -d <path to csv with data> -s <path to save trained model>
```
You can configure additional options in CLI. To get a full list of them, use help:
```bash
poetry run train --help