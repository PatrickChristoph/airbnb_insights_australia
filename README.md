# Insights about Airbnb accommodations
This analysis shares some interesting insights about accommodation rentals in
Australia based on an public Airbnb dataset.

## Table of contents
- [Project Motivation](#project-motivation)
- [Get started](#get-started)
- [File Descriptions](#file-descriptions)
- [Conclusion](#conclusion)
- [Creator](#creator)
- [Thanks](#thanks)

## Project Motivation
I was interested in the following questions for the Australian Airbnb market:
1. What are the most common amenities?
2. Is there a coherence between the number of amenities and prices?
3. Is there a coherence between the number of amenities and ratings?
4. Is it possible to predict the rating of an accommodation?

## Get started
- Install [python](https://www.python.org/downloads/) (used version: 3.8.10)
- Install [jupyter notebook](https://jupyter.org/install)
- The required python libraries are listed in the [requirements.txt](https://github.com/PatrickChristoph/airbnb_insights_australia/blob/main/requirements.txt)

All analyses are included in [this](https://github.com/PatrickChristoph/airbnb_insights_australia/blob/main/analysis.ipynb) jupyter notebook.

## File Descriptions
- `/data/listings/` - Folder with csv files for each Australian city/region that
contain various public data about Airbnb accommodations
- `/docs/` - Folder with GitHub page for a blog post about the results
- `analysis.ipynb` - Jupyter notebook with the data analysis
- `requirements.txt` - List of used python libraries to execute the Jupyter notebook

## Conclusion
Here is a short summary of the results for each question:
1. Kitchen is surprisingly the most common amenity with 92%
2. There is hardly no coherence between prices and the number of amenities
3. There is a low coherence between ratings and the number of amenities
4. A rough prediction even with a simple linear regression model is possible

For further details about the findings there is also a [blog post](https://patrickchristoph.github.io/airbnb_insights_australia/)
that summarizes the results.

## Creator

**Patrick Christoph**
- <https://www.linkedin.com/in/patrick-christoph/>
- <https://github.com/PatrickChristoph>

## Thanks

<a href="https://www.udacity.com/">
  <img src="https://www.udacity.com/images/svgs/udacity-tt-logo.svg" alt="Udacity" width="192" height="48">
</a>

Thanks to [Udacity](https://www.udacity.com/) for the introduction course in data science.

<a href="https://www.airbnb.com/">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Airbnb_Logo_B%C3%A9lo.svg/1200px-Airbnb_Logo_B%C3%A9lo.svg.png" alt="Airbnb" height="48">
</a>

Thanks to [Inside Airbnb](http://insideairbnb.com/) for providing the data.
