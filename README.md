# SIE 533 Project

This is a collaborative project designed specifically for SIE 533 course at the University of Arizona. The project uses heart failure clinical data available on Kaggle: [Heart Failure Clinical Data](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data/data).

## Contributors

### Add your names here ...

-   Garegin Mazmanyan

## Setup Instructions

1. Create a virtual environment:

    ```
    python -m venv .env
    ```

2. Activate the virtual environment:

    - On macOS/Linux:
        ```
        source .env/bin/activate
        ```
    - On Windows:
        ```
        .env\Scripts\activate
        ```

3. Install the required packages:
    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the `models/bases.ipynb` notebook to see the base results of the models:

    ```
    jupyter notebook models/bases.ipynb
    ```

2. To create your own models:
    - Create a new Jupyter notebook
    - Experiment with your own models by tweaking or tuning parameters
    - Important: Do not modify the `bases.ipynb` or any other existing files

## Project Structure

-   `models/`: Contains model implementations and notebooks
-   `data/`: Contains the heart failure clinical dataset used in the project
-   `requirements.txt`: List of required Python packages
