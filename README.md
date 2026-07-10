# MiniProject #01: Cobblestone Gifts

by Patrick Donnelly & Burke Havranek

EECE 5644: Introduction to Machine Learning and Pattern Recognition

Northeastern University College of Engineering

Summer 2026, Session B

## Introduction

This repository contains a Jupyter Notebook used to clean data from used car sales to find make a prediction model to set accurate prices without manual oversight. This notebook exhibits the basics of database manipulation, and provides in its auxiliary files (`car_details_v4.csv`, `cleaning_log.md`) a summary of the aforementioned sanitized data, and a raw database of such.

## Installation

This document and associated codebase exists in the form of a Jupyter Notebook with various auxiliary files. No external builds should be required, though Python 3.12 or newer is recommended for guaranteed compatibility. A full list of dependencies is provided in `requirements.txt`, though all such dependencies are installed automatically by the aforementioned notebook. It is recommended to run this notebook in a Python 3.12 virtual environment, though this should not be required for functionality.

## Downloading the Dataset

It is not required to download the raw data set for the program to function, as the program should pull the aforementioned database from Kaggle automatically and save it locally as `raw.csv`. The program does not currently support caching of any kind.

## Running the Notebook

The aforementioned notebook exists in `notebook.ipynb`, and has been engineered to run "out of the box" without additional configuration. Running the notebook from the repository directory should be sufficient.

## Summary of Findings

This project focused on the use of pandas for data sheet manipulation and sklearn for ML model creation and evaluation. In this project a breath of new tools and skills were used to help clean, encode, and scale data to change it to a more desired form. Information was added, removed, and converted to be used in sorted lists, graphs, and equations to understand it more fully. Then data was encoded and scaled, and the model was trained and evaluated. 
