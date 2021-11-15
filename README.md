# Comcast-Telecom-Consumer-Complaints

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

**In this project we focused on customer complaint analysis with Comcast data and analysed the following :**
- Trend chart for the number of complaints at monthly and daily granularity levels.
- Complaint types which are maximum i.e., around internet, network issues, billing, or across any other domains.
- State wise status of complaints in a stacked bar chart for Complaint Status 'Open' and 'Closed' considering 'Open' & 'Pending' to be categorized as 'Open' and 'Closed' & 'Solved' to be categorized as 'Closed'. 
- Finding state with maximum complaints
- Finding state with highest percentage of unresolved complaints.
- Finding percentage of complaints resolved till date, which were received through the Internet and customer care calls.

## 2. Installation <a name="installation"></a>

- Python - [Jupyter Notebook](https://jupyter.org)
- Libraries :
  - pandas
  - numpy
  - matplotlib
  - Scikit-learn
     - Count Vectorizer
     - nltk
     - stopwords
     - LatentDirichletAllocation
  
## 3. Data<a name="data"></a> 

There are Customer Complaint data available of Comcast. This is the data that covers complaints from Jan-2015 to Dec-2015 of dimensionality (2224,12).
Also uploaded above by the name : "Comcast-ComplaintDataset.csv"


## 4. Implementation <a name="model"></a> 
Stepwise analysis is performed with respect to the [Project Motivation](#ProjectMotivation).

## 5. Result<a name="results"></a>
The details of the results are shown in the jupyter notebook itself along the source code.
