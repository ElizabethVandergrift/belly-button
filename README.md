# Dashboard for Bacteria Cultures Analysis

This project visualizes data from bacteria cultures using an interactive dashboard. The dashboard includes metadata for each sample and charts that display the distribution and frequency of bacteria cultures.

https://elizabethvandergrift.github.io/belly-button/

## Table of Contents

- [index.html](index.html): The main HTML file that sets up the dashboard layout.
- [static/js/app.js](static/js/app.js): The JavaScript file containing the core functionality of the dashboard.

## Data

The data used in this project is fetched from a JSON file hosted at: [https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)

The JSON file includes:
- Metadata for each sample.
- Samples data including `otu_ids`, `otu_labels`, and `sample_values`.

## Usage

The dashboard consists of a dropdown menu to select different samples. Upon selection, the metadata panel and charts update to reflect the selected sample's data.

![Screenshot 2024-08-14 155907](https://github.com/user-attachments/assets/d01fbd42-feff-4416-8d2c-e3b4f1cf1e42)

![Screenshot 2024-08-14 155925](https://github.com/user-attachments/assets/3311b25b-9e71-483f-8975-d010021d583e)


## Features

- **Metadata Panel**: Displays metadata for the selected sample.
- **Bubble Chart**: Shows the distribution of bacteria cultures.
- **Bar Chart**: Displays the top 10 bacteria cultures found in the sample.
