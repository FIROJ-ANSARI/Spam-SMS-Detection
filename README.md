# SMS SPAM DETECTION USING MACHINE LEARNING

## Overview

This project aims to detect spam messages using machine learning techniques, specifically the Support Vector Machine (SVM) classifier. Additionally, a web application is implemented using Flask for user-friendly interaction.

## Table of Contents

- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Training the Model](#training-the-model)
  - [Running the Web Application](#running-the-web-application)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## About the Project

This project utilizes machine learning techniques, specifically the SVM algorithm, to classify SMS messages as spam or non-spam. The core functionality is implemented in the "SPAM SMS DETECTION.ipynb" Jupyter notebook.

The project also includes a web application built with Flask, providing an interactive interface for users to input text messages and receive predictions on whether they are spam or not.

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Flask

### Training the Model

To train the SVM model using the provided notebook:

jupyter notebook "SPAM SMS DETECTION.ipynb"

Follow the instructions in the notebook to train and save the model.

## File Structure

- **SPAM SMS DETECTION.ipynb**: Jupyter notebook containing the machine learning model implementation.
- **app.py**: Flask web application for user interaction.
- **templates/**: HTML templates for the web application.
- **static/**: Static files (CSS, JS) for the web application.


## Dataset

The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
