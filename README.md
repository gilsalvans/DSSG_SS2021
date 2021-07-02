# 21S856137 SS : Data Science and Machine Learning for Social Good
## Final Assignment
#### Team: 
  - Simon Donike 
  - Gil Salvans Torras 
 <br>
This repository corresponds to the Final Assignment of the course Data Science and Machine Learning for Social Good. <br> <br>

## Assigment title: Assessing bias and fairness in the COMPAS Recidivism Risk dataset: Study case for Gender and Race 
This project takes as input the COMPAS dataset (https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis), which contains the criminal history, jail and prison time, demographics and COMPAS risk scores for defendants from Broward County from 2013 and 2014. This data has already been subject to a classification on the risk scores. Its results represent whether each criminal has a low, medium or high recividism risk. Criminals with high and medium risks are considered that will be charged with a felony or misdemenor in the two years after administation of COMPAS assessment. Low is considered a prediction of non-recidivism. This is based on ProPublica's interpretation of Northpointe's practioner guide. <br>
With this, the aim of this assignment is to assess bias and fairness in this resulting dataset. In this case, on one hand, gender, and on the other hand, race, will be the two taken inputs to assess potential prediction biasses. To do so, the Python library from Aequitas (https://github.com/dssg/aequitas) will be the main instrument used for this analysis (besides other Python libs for data manipulation -see notebook-). 

<b>For Development: Link to Colab notebook -> https://colab.research.google.com/drive/1NrLMF_vvGI5fgbraXDwrz4mHSUt7mmM0?usp=sharing </b>
