# Story 3

The CDC publishes firearm mortality for each State per 100,000 persons https://www.cdc.gov/nchs/pressroom/sosmap/firearm_mortality/firearm.htm. Each State' firearm control laws can be categorized as very strict to very lax. The purpose of this Story is to answer the question, " Do stricter firearm control laws help reduce firearm mortality?"
For this assignment you will need to:
Access the firearm mortality data from the CDC using an available API (https://open.cdc.gov/apis.html)

Create a 5 point Likert scale categorizing gun control laws from most lax to strictest and assign each state to the most appropriate Likert bin.

Determine wether stricter gun control laws result in reduced gun violence deaths

Present your story using  heat maps

# Data

## Firearm Related Mortality
Firearm related mortality data for each state from the [CDC](https://www.cdc.gov/nchs/pressroom/sosmap/firearm_mortality/firearm.htm). Data was acquired using the [Socrate API](https://dev.socrata.com) and wrangled for this presentation. See [DataWrangling.ipynb](https://github.com/CUNY-SPS-Data-Science-Program/your-bio-himalayahall/blob/main/Story%203/DataWrangling.ipynb) for details.

## Gun Law Score
[Giffords Gun Law Scorecard](https://giffords.org/lawcenter/resources/scorecard) for each state. Giffords gun law score have the following scale, from strongest gun laws to weakest: \[A+, A, A-, B+, B, B-, C+, C, C-, D+, D, D-, F\]. 

Original Giffords scores have been coerced into a 5-point [Likert scale](https://en.wikipedia.org/wiki/Likert_scale) and a numeric grade was assigned to each letter grade: \[A: 4, B: 3, C: 2, D: 1, F: 0\].

# Presentation

The presentation uses [Plotly](https://plotly.com/graphing-libraries/) for rendering dynamic plots. 

## Interactive Presentation

To fully experience the dynamic presentation, do one of the following:

- Download and load the standalone [html file](https://github.com/CUNY-SPS-Data-Science-Program/your-bio-himalayahall/blob/main/Story%203/Story3.html) in your favorite browser.
- Download and run the [Jupyter Notebook](https://github.com/CUNY-SPS-Data-Science-Program/your-bio-himalayahall/blob/main/Story%203/Story3.ipynb)

## Static Presentation

A PDF version of the Jupyter Notebook is available [here](https://github.com/CUNY-SPS-Data-Science-Program/your-bio-himalayahall/blob/main/Story%203/Story3.pdf).
