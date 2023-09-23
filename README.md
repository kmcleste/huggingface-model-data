# Huggingface Model Data

## Prerequisite

To download the dataset, you will need git-lfs. See [these instructions](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage) on how to install.

## Setup

1. Clone this repository:

    ```bash
    git clone https://github.com/kmcleste/huggingface-model-data.git
    ```

2. Inside the repo directory, download the dataset:

    ```bash
    git lfs pull
    ```

3. (Optional) To run the notebook, you will need to install the python dependencies:

    ```bash
    # Create a virtual environment
    python -m venv venv
    # Source the environment
    source venv/bin/activate
    # Install dependencies
    pip install -r requirements.txt
    ```

    Note: If you decide to run the notebook, scraping will take ~ 45 minutes

## Data

| Column        | Type                |
| ------------- | ------------------- |
| downloads     | int                 |
| id            | str                 |
| lastModified  | datetime (iso-8601) |
| likes         | int                 |
| pipeline_tag  | str                 |
| private       | bool                |
| repoType      | str                 |
| author        | str                 |
| authorData    | dict                |
