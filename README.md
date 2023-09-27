## About this project

This project was done as my first own project during my bootcamp at neuefische. It was about learning hypothesis-driven exploratory data analysis. The goal was to select and develop a business case, identify steakholder needs, develop 3 hypotheses about the data and then test them. In the end, 3 recommendations could be derived. 

[Here](presentation_eda_house_pricing.pdf) you can find the presentation on the project. <br>
And [here](eda_house_prices.ipynb) is the notebook to the project. 

The basis of the work is the King county house pricing dataset which you can find [here](https://data.kingcounty.gov).

## Requirements and environment

Requirements:
- pyenv with Python: 3.11.3

Environment: 

For installing the virtual environment you can either use the Makefile and run `make setup` or install it manually with the following commands: 

```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt