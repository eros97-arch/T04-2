# Appliance Energy Australia

A data visualisation website exploring television energy consumption in the Australian market.

## Project Overview

This project explores television energy consumption using Australian government data. The website presents visualisations that examine screen technology, screen size, brands, power consumption and energy ratings.

The project was developed for COS30045 Data Visualisation and demonstrates data processing with KNIME, data visualisation, web development and communicating data insights through a data story.

## Website

The website contains three main pages:

- **Home** - Introduction to the project and appliance energy consumption.
- **Televisions** - Data story exploring television energy consumption.
- **About Us** - Information about the project and development.

## Data Source

The dataset used in this project is:

**Energy Rating Data for household appliances – Labelled Products**

Source: Australian Government Department of Climate Change, Energy, the Environment and Water (DCCEEW)

The television data contains information about television models registered for sale in Australia and New Zealand, including attributes such as brand, model, screen technology, screen size, power consumption and energy rating.

Data source:
https://data.gov.au/data/dataset/energy-rating-for-household-appliances

The dataset is provided under the Creative Commons Attribution 3.0 Australia licence.

## Data Processing

The television dataset was processed using KNIME before being used for visualisation.

The main processing steps included:

1. Reading the television CSV dataset.
2. Removing unnecessary columns.
3. Sorting and checking the data.
4. Removing duplicate records.
5. Filtering the dataset to relevant television models.
6. Converting screen size from centimetres to inches.
7. Standardising brand names to consistent capitalisation.
8. Grouping and aggregating the data to answer the visualisation questions.
9. Creating charts and scatter plots for the data story.

The processed dataset contained 4,750 television records and 9 relevant columns after cleaning and transformation.

## Data Story

The visualisations explore the following questions:

1. What TV technologies are available?
2. What screen sizes are most common?
3. Which brands have the greatest number of different models?
4. Which screen technology consumes the least power?
5. What is the relationship between screen size and power use?
6. What is the relationship between star rating and screen size?

An additional visualisation explores differences in average power consumption between brands.

## Key Findings

- LCD (LED) is the most frequently represented screen technology in the dataset.
- Larger screen sizes, particularly around 55 to 75 inches, are strongly represented.
- KOGAN has the greatest number of models, followed by LG and SAMSUNG ELECTRONICS.
- LCD has the lowest average power consumption among the three screen technologies.
- Power consumption generally increases as screen size increases, although individual models vary.
- Screen size does not appear to have a strong relationship with star rating by itself.
- Average power consumption varies between television brands.

## Data Limitations

The dataset represents registered television products and should not be interpreted as a complete list of every television available in the Australian market.

The number of models represented by each brand may also differ because the dataset contains different numbers of registered models for different brands.

The visualisations show patterns within the available dataset. They do not establish that one characteristic directly causes another. For example, the relationship between screen size and power consumption may also be affected by other characteristics of individual television models.

## Privacy and Ethics

The dataset contains information about television products rather than personal information about individual consumers.

The project does not collect or display personal information from users.

The visualisations are presented to communicate patterns in the dataset without making claims beyond what the available data can support.

## Technologies Used

- HTML
- CSS
- JavaScript
- KNIME
- GitHub
- Vercel

## GenAI Declaration

Generative AI tools were used to assist with the development of this project.

AI assistance was used for tasks such as brainstorming, reviewing content, troubleshooting code and improving the presentation of the website.

The final website, data processing workflow, visualisations and written content were reviewed and adapted by the author.

## Author

Awang Syahrul Akmal Bin Awang Kasti

COS30045 Data Visualisation

2026