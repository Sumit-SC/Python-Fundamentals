# Python-Fundamentals
Repo to track Python self-study progress and study materials used during DS study including basics, advanced topics and data cleaning - visualization Library.

Project Navigation
=============================

| Project | README | Notebook |
| ------- | ------ | -------- |
| IMDb Top 1000 Movies Visualization | [IMDB_Movies_Visualization_info](docs/IMDB_Movies_Visualization_info.md) | [IMDb_Movies_Analysis](notebooks/Visualize_IMDB%20dataset.ipynb) |
| Spotify Dataset Analysis | [Spotify_Dataset_Analysis_info.md](docs/Spotify_Dataset_Analysis_info.md) | [Spotify_Analysis](notebooks/Exploring%20Spotify_dataset%20using%20Pandas%20&%20Matplotlib.ipynb) |
| Covid19-Vaccination (EDA) | [Covid19_Vaccinations-EDA_info.md](docs/Covid19_Vaccinations-EDA_info.md) | [Covid19_Vaccinations-EDA](notebooks/Covid_India_Vaccine.ipynb) |
| Walmart SampleStore (EDA) | [Walmart_Dataset_Analysis_info.md](docs/Walmart_Dataset_Analysis_info.md) | [Walmart_Analysis-EDA](notebooks/Data%20Analysis%20on%20Walmart%20dataset%20using%20Seaborn.ipynb) |

------------
Boilerplate
==============================

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources(if any)
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
