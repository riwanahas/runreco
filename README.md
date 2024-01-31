# Music Running Recommender

Music Recommender for runners who want their music in sync with their tempo.

## Structure

- .github: CI/CD with GitHub Actions. It runs the tests every time there is a pull request to the repository.
- docs: Documentation of the project.
- examples: Jupyter notebooks with machine learning experiments. Here is where you would do data exploration, try different machine learning models, etc.
- spotify_reco: Libraries with common functions that you use in the project. 
- tests: Python tests of the libraries.

## Setup

    pip install -e .
    python -c "import spotify_reco; print(spotify_reco.__version__)"


