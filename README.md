# A-real-time-application-to-detect-phishing-websites
Detection of Phishing Websites using Random Forest based on a Dataset available in UCI: ML Repository. 
This project provides an interface to users to check any website whether it is phishing or not. This model uses Random Forest. There are two parts of the applicaton which are feature extraction and another is for training the data and dumping the results in a PKL file.
Various libraries has been used for Random forest implementation and features extraction from websites.  Many of the features has been extracted using regular expression. The data has been taken from UCI: Machine Learning Repository. Detailed explanation of the features that are extracted in the module can be found at https://archive.ics.uci.edu/ml/machine-learning-databases/00327/  .
.
.
.
.
.
.
.
.
.
Module for Faeture Extraction:- defined_attributes.py   .
Module for Random Forest:- RandomForest.py  .
.
.
.
.
.
.
.
.
.
This data is in CSVFormat. The relation name is phishing and has 31 attributes. There are 11055 instances in the data set.This collected features hold the categorical values, Legitimate, Suspicious and Phishy, these values have been replaced with numerical values 1,0 and -1 respectively.
Here is the list of the features that are extracted in the Module.

•	having_IP_Address  { -1,1 }
•	URL_Length   { 1,0,-1 }
•	Shortining_Service { 1,-1 }
•	having_At_Symbol   { 1,-1 }
•	double_slash_redirecting { -1,1 }
•	Prefix_Suffix  { -1,1 }
•	having_Sub_Domain  { -1,0,1 }
•	SSLfinal_State  { -1,1,0 }
•	Domain_registeration_length { -1,1}
•	port { 1,-1 }
•	HTTPS_token { -1,1 }
•	Request_URL  { 1,-1 }
•	URL_of_Anchor { -1,0,1 }
•	Links_in_tags { 1,-1,0 }
•	SFH  { -1,1,0 }
•	Submitting_to_email { -1,1 }
•	Abnormal_URL { -1,1 }
•	Redirect  { 0,1 }
•	on_mouseover  { 1,-1 }
•	RightClick  { 1,-1 }
•	popUpWidnow  { 1,-1 }
•	Iframe { 1,-1 }
•	age_of_domain  { -1,1 }
•	DNSRecord   { -1,1 }
•	web_traffic  { -1,0,1 }
•	Page_Rank { -1,1 }
•	Google_Index { 1,-1 }
•	Links_pointing_to_page { 1,0,-1 }
•	Statistical_report { -1,1 }
•	Result  { -1,1 }


