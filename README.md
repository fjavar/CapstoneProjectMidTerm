# CapstoneProjectMidTerm
Initial Delivery of the Capstone Project
### Cybersecurity Data Analysis

**Frank Javar**

#### Executive summary
Cybersecurity threats have been on the rise, with hackers employing increasingly sophisticated tactics and advanced tools, including Artificial Intelligence, to cause harm to individuals, financial systems, and critical infrastructure. To counter these evolving challenges, Machine Learning has emerged as a powerful solution for quickly detecting malware and preventing attacks before they occur. This project focuses on utilizing unsupervised machine learning techniques to identify, classify, and analyze anomalies that could signal potential security threats by examining patterns in network traffic. Specifically, the goal is to explore approaches such as clustering algorithms and dimensionality reduction methods to uncover hidden patterns and improve threat detection capabilities.  
#### Rationale
Cybercrime was projected to cost the global economy $8 trillion in 2023, according to Cybersecurity Ventures, with this figure expected to rise to $10.5 trillion annually by 2025, solidifying cybercrime as one of the most significant economic threats worldwide. Additionally, ransomware attacks alone were estimated to cost businesses over $20 billion in 2023, a sharp increase from $11.5 billion in 2019. Implementing more robust methodologies, combined with proactive traffic monitoring and pattern recognition to detect threats before an attack occurs, could prove to be a highly effective strategy for significantly reducing these losses.

#### Research Question
Using “Unsupervised Learning” ML techniques to detect/identify and classify potential threats/anomalies by analyzing patterns in network traffic. 

#### Data Sources
What data will you use to answer you question?
https://www.unb.ca/cic/datasets/index.html
#### Methodology
Exploring techniques such as clustering (e.g., K-means and DBSCAN) or dimensionality reduction (e.g., Principal Component Analysis) to identify patterns in network traffic. For the model several steps completed incldeuing:
 1. Combined four data sets into one and selected most relevant rows thatfor this analysis.
 2. Cleaned up the te data set incuding eliminating Duplicates, NAN, rows with missing values (not a lot of rows elimited here)
 3. Check the outliers (IQR)
 4. Check the data distribution for skewness
 5. Tried to select the right features - This did not work well right now. Left for te final delivery.
 6. Based on my own experiance as a security engineer, I identified columns that can potentially be used by hackers ans used them as Feature columns vs teh  Label column as Target.
 7. Developed the first model based on the Logestic Regression.
 8. For the final delivery, I will develope a Random Forest Model and will compare the results with the Logistic Regression model. 

#### Results
In general, there are several results inclduing:  
Detection of malicious activities - Identify unusual traffic patterns, Detect unauthorized attempts, Spot signs of exploitation
o Identify anatomies - Identify spikes in network traffic, Spot traffic using unusual or rarely used protocols, identify traffic occurring at unusual times
o Threat attribution - Pinpoint the origin of malicious traffic, Determine the type of attack, Link malicious activity to known threat actors or groups
o In particule the inititial results indicat that:
 1. The model is created with Logistic Regression:
    a. Classified types of attacks.
    b. Tabulted metrics inclduing Precesion, Recall, F1-Score, and Support.
    c. Created the confusion Metrix summary of perfroamnce of teh classifications.
 


#### Next steps
o Build other models inclding Random Forst Model and determine best perfroamnce model fo rthis analysis.

#### Outline of project

- https://github.com/fjavar/CapstoneProjectMidTerm.git


##### Contact and Further Information
Frank Javar
fjavar@mitre.org
