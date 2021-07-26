# San Francisco AirBnB Analysis
## Author: Dustin Burnham


### Proposal
In this analysis I will use publicly available [AirBnB data](http://insideairbnb.com/get-the-data.html) to investigate the following:
1. Which factors influence the price of AirBnB rentals in the city of San Francisco, California.
2. Can the price of AirBnB rentals be modeled?  And if so, can we determine which properties are over/undervalued?
3. The creation of geospatial maps for the AirBnB data?

### Plan of Action
1. Perform EDA to invistigate relationships in the data.
2. Create maps between property, review, and calendar data.
3. Data preprocessing.
4. Feature engineering.
5. Modeling (Baseline regression model)
6. Feature importance analysis via SHAP
7. Identification of over/undervalued properties based on models
8. Geospatial mapping

### Data Sources
- [Source](http://insideairbnb.com/index.html)
- [Data Dictionary](https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=982310896)
- [Disclaimers from Source](http://insideairbnb.com/about.html#disclaimers)
- [Data Source License](https://creativecommons.org/publicdomain/zero/1.0/)

### Disclaimer
This project is not being used for any monetary reason.

## Modeling
Training: The model will be trained on temporal data.  For a given day, we have all of the data for all properties.  Use a time series analysis regression model to be able to predict property price given a properties attributes, and time of year.
