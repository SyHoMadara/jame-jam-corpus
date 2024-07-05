<p align="center">
    <a>
        <img src="./assets/images/jamejam.svg" alt="dataset_image" width="640">
    </a>
    <br>
    <b>A universe of information within your fingertips.</b>
    <br>
</p>

<br>

# Jam-e Jam News Corpus

Welcome to the official repository for the Jam-e Jam News Dataset and NLP Model. This repository contains a comprehensive dataset of news articles scraped from the [Jam-e Jam Online](https://jamejamonline.ir) website. The dataset includes information such as title, tags, types, timestamp, summary, and content for over 1.4 million news articles.

In addition to the dataset, we have developed a powerful NLP model for classifying news articles based on their types and tags. This model can be used for tasks such as text classification.

## Contents
<!-- vscode-markdown-toc -->
- [Jam-e Jam News Corpus](#jam-e-jam-news-corpus)
  - [Contents](#contents)
  - [Dataset Formats](#dataset-formats)
  - [NLP Model](#nlp-model)
  - [Requirements](#requirements)
    - [Python Compatibility](#python-compatibility)
    - [Dependencies](#dependencies)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

## Dataset Formats

The dataset is available in various formats to cater to different needs:

- SQLite: [Link to SQLite dump file](./datasets/sqlite/dataset.sqlite)
- PostgreSQL: [Link to PostgreSQL dump file](./datasets/psql/dataset.dump)
- CSV: [Link to CSV file](./datasets/csv/dataset.csv)
- TSV: [Link to TSV file](./datasets/tsv/dataset.tsv)
- XLSX: [Link to XLSX file](./datasets/xlsx/dataset.xlsx)

Feel free to choose the format that best suits your requirements.

## NLP Model

We have developed a state-of-the-art NLP model for classifying news articles. The model can predict the type and tags of a news article, making it a valuable tool for various applications.

## Requirements

### Python Compatibility

This bot is written entirely in Python. Tested versions are `python 3.11`, `3.10`, `3.9`, `3.8`, `3.7`. While older versions should not cause any problems, we recommend using the latest version of `python3`.

### Dependencies

This package requires the following packages:

- [AsyncIO](https://docs.python.org/3/library/asyncio.html) - A library to write concurrent code using the async/await syntax.
- [AIOHTTP](https://docs.aiohttp.org/en/stable/) - Asynchronous HTTP Client/Server for `asyncio` and Python.
- [SQLAlchemy](https://www.sqlalchemy.org/) - A Python SQL toolkit and Object Relational Mapper.
- [BS4](https://www.crummy.com/software/BeautifulSoup/) - A Python library designed for quick turnaround projects like screen-scraping.
- [Psycopg](https://www.psycopg.org/) - The most popular `PostgreSQL` adapter for Python.
- [aiosqlite](https://github.com/omnilib/aiosqlite) - An asyncio bridge to the standard `sqlite3` module.
