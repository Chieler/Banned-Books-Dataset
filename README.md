
![Framework](https://img.shields.io/badge/Dataset-blue) ![Languages](https://img.shields.io/badge/Original-white)

# Banned-Books-Dataset
Dataset of Censored and Uncensored Books

# [Link](https://www.kaggle.com/datasets/chielerli/banned-book-dataset)

# About The Project:
Book bans limit access to information ad restrict freedom of expression. There has been no comprehensive data for training ML models on if a book will be censored (challenged/banned) or not. This dataset aims to address that. The title and author of banned books are obtained through non-profits like the ALA and Pen America while metadata like description and genre for them are obtained through webscraping Goodreads.
The books that are labeled as uncensored are obtained through kaggle then filtered.

# Setup:
```bash
#Clone the repo
git clone https://github.com/Chieler/Banned-Books-Dataset/
```
or
```python
# pip install kagglehub[pandas-datasets]
import kagglehub
from kagglehub import KaggleDatasetAdapter

# Set the path to the file you'd like to load
file_path = ""

# Load the latest version
df = kagglehub.load_dataset(
  KaggleDatasetAdapter.PANDAS,
  "chielerli/banned-book-dataset",
  file_path,
  # Provide any additional arguments like 
  # sql_query or pandas_kwargs. See the 
  # documenation for more information:
  # https://github.com/Kaggle/kagglehub/blob/main/README.md#kaggledatasetadapterpandas
)
```
And then your done! To run it simply go to V1Application.java and run it!

