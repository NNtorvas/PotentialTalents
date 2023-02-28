# Potential Talents Project

## Background:

The goal of this project is to create a NLP model to rank job candidates based on specific keywords or a role model candidate.

## Data Description:

The data comes from our sourcing efforts. We removed any field that could directly reveal personal details and gave a unique identifier for each candidate.

Attributes:
* id : unique identifier for candidate (numeric)

* job_title : job title for candidate (text)

* location : geographical location for candidate (text)

* connections: number of connections candidate has, 500+ means over 500 (text)

Output (desired target):
* fit - how fit the candidate is for the role? (numeric, probability between 0-1)

Keywords: “Aspiring human resources” or “seeking human resources”

## Summary of the Project:

Our Analysis was conducted following these steps:

1. Import Libraries and Load Data
2. Data preprocessing
3. Modify our data to have them ready for our model
4. Create our word2vec model to rank the candidates
5. Make a process to re-rank the candidates based on a role model candidate

### Insights:

* The dataset had N/A values and duplicates, which we dealt with.

### Conclusion:

* The model is ranking the candidates very good based on the keywords and the role model candidate later. The company can save time by using our modle to find the best people for the job.