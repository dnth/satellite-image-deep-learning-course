# course
- Website using [quarto](https://quarto.org/docs/books/)
- Each chapter is a Jupyter notebook or markdown file (if no code)
- Notebooks should be self contained by including a cell for installing requirements, and runnable on Google colab

## Run notebooks locally
Each of the notebooks can be run locally. It is necessary to create and activate a virtual environment with the required dependencies.
- `python3 -m venv venv`
- `source venv/bin/activate`
- `pip install -r requirements.txt`

## Contributing
Contributions are welcome! Create a fork with your changes and make a pull request. Note that the python dependencies should be available in the Google Colab environment.

## Quarto commands
- To preview the website in the browser: `quarto preview`