# Scripts and data associated with "Mobilizing microbial data: Insights from a ELIXIR Pathogen Data Focus Group and ELIXIR Microbiome Community Workshop (ELIXIR All Hands Meeting 2025)" Report

This repository includes all data and the scripts needed to produce figure in the report.

# Requirements

- Install [conda](https://conda.io/miniconda.html)

    ```
    $ make install-conda
    ```

- Create the conda environment

    ```
    $ make create-env
    ```

# Usage

## Update data

- Launch the dedicated script

    ```
    $ bash bin/get_data.sh
    ```

## Plot results

- Launch [Jupyter](https://jupyter.org/) to access the notebooks to generate graphs

    ```
    $ make run-jupyter
    ```

- Go to [http://localhost:8888](http://localhost:8888) (a page should open automatically in your browser)