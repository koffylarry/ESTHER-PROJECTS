<h1>Hi, I'm Esther! <br/><a href="https://github.com/koffylarry">Programmer</a>, <a href="https://www.linkedin.com/in/oluwayemisi-adebanjo-07589a139/">Data Analyst</a>,
<h2>👨‍💻 Customer Insight Analyst:</h2>


<h2>COMPARISON OF TWO ALGORITHMS -DECISION TREE AND ARTIFICIAL NEURAL NETWORK </h2>
The accuracy and other performance metrics of two classification algorithms were compared in this </h2>
study. Decision Tree Classification Algorithm and Artificial Neural Network were the two MLAs whose
performance were compared. The two MLAs were implemented on the PIMA India Diabetes dataset.
The result of the comparison depicted that ANN performed better than decision tree classifier as it has
better classification accuracy. Azure machine learning was also used to implement the classification
algorithms on the dataset and the comparison of the result shows it is in tandem with the analysis
carried out in Jupyter notebook..

* datasets used for CLASSIFICATION was downloaded from https://data.world/data-society/pima-indians-diabetes-databas
*All codes were run on jupyter notebooks 6.4.8 version
*name of dataset used is Diabetes.csv
*Diabetes.csv datasets has 768rows and  9columns using df.shape
        Pregnancies
	Glucose
	BloodPressure
	SkinThickness
	Insulin
	BMI
	DiabetesPedigreeFunction
	Age
	Outcome


*libraries used in carrying out this task are :

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from matplotlib import rcParams
plt.style.use("ggplot")
rcParams['figure.figsize'] = (12, 6)
%matplotlib inline


 

    <h2>Association rule mining was implemented an online retail dataset.</h2> 
    Apriori ARM method was used to
establish the relationships for the items/products that were bought together based on different the
transactions done in some countries in the dataset. The result of the ARM was obtained for at least 8
countries in the dataset to show the items/products that were frequently bought together. The lift,
support and the confidence are the three metrics that were used to determine how often customers lift
these products together from the shelf. The result of the mining technique was used to inform retailers
the products that were actually bought together in each of the transactional countries.
* datasets used for the AASOCIATION RULE was downloaded from https://archive.ics.uci.edu/ml/datasets/online+retai
*All codes were run on jupyter notebooks 6.4.8 version
*name of dataset used is Online Retail.csv
*Online Retail.csvdatasets has 532621rows and 8columns using df.shape
*Online Retail dataset consist of this variables
        InvoiceNo
	StockCode
	Description
	Quantity
	InvoiceDate
	UnitPrice
	CustomerID
	Country

*libraries used in carrying out this task are :

 import numpy as np
import pandas as pd
from mlxtend.frequent_patterns import apriori, association_rules

 Enclosed in the Submission file are:
*Sentiment Analysis Jupyter notebook code
  - Codes are saved as ADEBANJO_YEMISI.IPYNB
*Sentiment analysis was carried out on tourist dataset using VADER module of nltk python library. The
dataset contains the customers’ review of the hotels/Restaurant. 30 distinct hotels were selected and
the VADER implemented to calculate the polarity scores of the customers’ review for each of the hotel,
this was in turn used to categorize the review s into positive, neutral and negative sentiments. The
result of the study shows that 28 of the 30 randomly selected hotels/Restaurant have positive
reviews/sentiments from their customers while the remaining 2 have a negative review/sentiment.

(data1 = df.drop_duplicates(subset=["Hotel"], keep="last").sample(n=30,random_state=1)
* datasets used for the sentiment analysis was downloaded from blackboard(University Of Salford)
*All codes were run on jupyter notebooks 6.4.8 version
*name of dataset used is tourist_accommodation_reviews.csv
*tourist_accommodation_reviews.csv datasets has 53644rows and 5columns using df.shape
*tourist_accommodation_reviews.csv dataset consist of this variables
   ID	
Review Date	
Location	
Hotel/Restaurant name	
Review
*libraries used in carrying out this task are :

 import pandas as pd #For data manipulation and analysis
 import numpy as np #For mathematical calculations
 import matplotlib.pyplot as plt #for visualisations and graph plotting
 import nltk #For statistical language Processing
 import seaborn as sns #For visualisation
 import re #For string manipulation
 from wordcloud import WordCloud #for Textual sentiment analysis
 from nltk.probability import FreqDist #for Textual sentiment analysis
 from nltk.sentiment.vader import SentimentIntensityAnalyzer #for Textual sentiment analysis
 nltk.download(['stopwords',
               'punkt', 
               'wordnet', 
               'omw-1.4', 
               'vader_lexicon'])
 %matplotlib inline


 Enclosed in the Submission file are:
*Association Rule in Jupyter notebook code
  - Codes are saved as Clustering(Task 3).IPYNB

*In this study, two Clustering Algorithms namely K means Clustering and BIRCH Clustering Algorithms
were implemented on a dataset. To implement the Clustering Algorithms, the dataset was pre-
processed to identify the invariate and the most suitable variables for the analyses. After pre-processing,
the elbow method was used to identify the number of clusters appropriate for the Clustering
techniques. Then two Clustering Algorithms were then implemented based on the number of clusters.
After implementation of the Algorithms, the result gotten showed the same cluster pattern for the two
Algorithms used.

* datasets used for CLUSTERING was downloaded from https://catalog.data.gov/dataset/association-rule-mining-data-for-census-tract-chemical-exposure-analysis
*All codes were run on jupyter notebooks 6.4.8 version
*name of dataset used is ARM Dataset.xlsx
*Online Retail.csvdatasets has 464075rows and 7columns using df.shape


*libraries used in carrying out this task are :

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

- <b>Data Structures and Algorithms Practice (AlgoExpert)</b>
  - [Praciting DS & Algos in Python](https://github.com/joshmadakor1/Algorithms-Practice)
- <b>Full Stack Web App (React, NodeJS, Azure, and Machine Learning Components)</b>
  - [Image Analysis Middleware](https://github.com/joshmadakor1/4chan-Image-Analysis-Middleware-C964) <b><i>(Potentially NSFW)</b></i>
- <b>PowerShell</b>
  - [Windows EventLog: Failed RDP Logins Source IP to full GeoData Conversion](https://github.com/joshmadakor1/Sentinel-Lab)
  - [JWipe (Disk Wiping Utility)](https://github.com/joshmadakor1/Jwipe.PowerShell)
  - [Active Directory Bulk User Creation](https://github.com/joshmadakor1/AD_PS)
  - [FIM (File Integrity Monitor)](https://github.com/joshmadakor1/PowerShell-Integrity-FIM)
- <b>C# (.NET Desktop Applications)</b>
  - [Ransomware Proof of Concept (Encrypter)](https://github.com/joshmadakor1/EncrypterPOC)
  - [Ransomware Proof of Concept (Decrypter)](https://github.com/joshmadakor1/DecrypterPOC)
  - [Keylogger with Email Capability](https://github.com/joshmadakor1/Key-Logger-With-Email)
- <b>Python</b>
  - [Package Delivery Application (Datastructures and Algorithms Demo)](https://github.com/joshmadakor1/Package-Delivery-Pathfinding-Algorithm)

<h2>📺 Popular YouTube Videos</h2>

- [How to get into Cybersecurity Starting From Zero](https://www.youtube.com/watch?v=a83ASGn_V_s)
- [A Day in the Life of a Cybersecurity Anayst](https://www.youtube.com/watch?v=uHy3oM7NnoU)
- [How to Create a KeyLogger (C#)](https://www.youtube.com/watch?v=N-L9hklSlNk)
- [Ransomware Demonstration (C#)](https://www.youtube.com/watch?v=OfvdQeh79s0)
- [Is WGU Legit?](https://www.youtube.com/watch?v=E2MwRWxDBkA)

<h2> 🤳 Connect with me:</h2>

[<img align="left" alt="JoshMadakor | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube]
[<img align="left" alt="JoshMadakor | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="JoshMadakor | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="JoshMadakor | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

[twitter]: https://twitter.com/joshmadakor
[youtube]: https://www.youtube.com/c/joshmadakor
[instagram]: https://www.instagram.com/joshmadakor/
[linkedin]: https://linkedin.com/in/joshmadakor

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
