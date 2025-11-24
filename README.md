# News YouTube Video Success Prediction

YouTube video success prediction based on data analytics

Things to analyze:
- General video success criteria
- General news video success criteria
- Fox news video success criteria

## Data collection
Data will be collected using the YouTube Data V3 API

Initial video information will be collected using a query search. Queries will be generated using GPT 4o mini.

For general videos, queries will be generated based on video category label. Data for the news videos will be extracted from the news category.
Data for Fox video performance will be scraped directly from the channel.

Feature engineering will be decided after an analysis of the data

## Model
Three main models will be created with the goal of predicting either video performance numerically or categorically.
One or more submodels may be trained for a deeper analysis of YouTube video titles and their effect on view counts.
