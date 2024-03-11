# data-harvesting-assignment
Data harvesting assignment repository

How to scrap YouTube API? 

To access and extract information from the YouTube API, an essential prerequisite is to obtain an API KEY. This API key contains sensitive information that should be handled withconfidentiality and not openly shared. Follow the following steps to get an API KEY:

1. First create a Google account to access the Google API console and be able to request an API key. 
2. Second step is to create a project on the Google Developers Console by clicking on the project dropdown that is next to the Google cloud logo. 
3. After creating a new project, go to the left side bar and select "APIs & Services" and then on then clic on the "Enable APIS and Services" and search for the  "YouTube Data API v3", select it and enable it. 
4. After enabling the API, click on the "Create Credentials" button and choose the API key option.
5. Finally, once created, the API key will be displayed on the screen, ensure to copy the API key and keep it secure.

Once we have the API KEY, we can use it on R but as mentioned above when having a API KEY we should be careful to handle it due to several security and privacy concerns, API keys are credentials to access specific resources, therefore we should avoid to give this access to malicious actors to manipulate or retrieve sensitive information. 

So, the next step is to create a ".env" file to keep sensitive information in here and the exposure of this sensitive information to unauthorized persons.
