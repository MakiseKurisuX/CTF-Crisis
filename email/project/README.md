ReadMe file for Email project challenge

--------------------------------------------------------------
Datasets folder
--------------------------------------------------------------

Phishing Folder:
- Data Emails from Nazario Phishing Corpus for Phishing Challenge Notebook

Non Phishing Folder:
- Data Emails from Enron Dataset & SpamAssassin Easy Ham for Phishing Challenge Notebook

CSV Folder:
- Contains Data of CSV Files used for ML Model:
    - phishing_data_1.csv       (Data used for Strong Model)
    - phishing_data_4.csv       (Data used for Weak Model)
    - non_phishing_data_13.csv  (Data used for Strong Model)
    - non_phishing_data_4.csv   (Data used for Weak Model)

On datasets used:

The final raw email dataset for the strong Machine Learning Model consists of 2417 phishing emails and 4307 legitimate emails. Of the phishing emails, the emails are taken from the publicly available Nazario Phishing Corpus, which consists of phishing emails collected by a Security Researcher. For the legitimate emails, different sources are used to construct the dataset. 1500 emails are taken from the team members’ mailboxes, another 807 emails are taken from the SpamAssassin Easy Ham dataset, another 500 is taken from the SpamAssassin Hard Ham dataset, while another 1500 is taken from the popular Enron dataset. 

For the weak Machine Learning Model, the dataset was designed in such a way to cause a vulnerability within the Machine Learning Model. For this dataset, 2188 phishing emails are taken from the Nazario Phishing Corpus, another 1000 taken from the SpamAssassin Easy Ham dataset, and another 1188 emails were taken from the Enron dataset. To cause the vulnerability, emails from the SpamAssassin Hard Ham dataset, which generally consists of legitimate emails with links, are excluded. This ultimately means that the legitimate email dataset does not contain any emails that consists of links, ultimately causing a vulnerability from the ‘Number of Links’ feature due to lack of emails that consist of links within the dataset.


--------------------------------------------------------------

################################################################

--------------------------------------------------------------
Jupyter Notebooks folder
--------------------------------------------------------------

Feature Extraction (Non-Phishing Emails) - Feature Extraction Program for Non-Phishing Emails
 
Feature Extraction (Phishing Emails) - Feature Extraction Program for Phishing Emails

Prototype (Phishing) - Bad - ML Model Creation for Weak ML Model

Prototype (Phishing) - ML Model Creation for Strong ML Model

--------------------------------------------------------------
Strong model features:
--------------------------------------------------------------

- spamScore
- SenderReplyDiff
- checkAttachments
- subjReply
- subjForward
- subjNoOfWords
- subjNoOfChar
- subjVerify
- subjDebit
- subjBank
- script_exist
- checkPopup
- checkJS
- NoOnClick
- html_exist
- form_exist
- noFunctionWords
- noWords
- noChars
- check_suspend
- check_verify
- check_dear
- unique_Words
- Richness
- noOfURLs
- noOfLinks
- checkIP
- checkAtSym
- checkdoubleslash
- checkURLShorten
- checkImg
- checkPort
- avg_DomainLength
- checkNoDots
- checkContentURL
- checkModal
- check_Here

--------------------------------------------------------------
Weak model features :
--------------------------------------------------------------

- SenderReplyDiff      
- checkAttachments     
- subjReply            
- subjForward          
- subjNoOfWords        
- subjNoOfChar         
- subjVerify           
- subjDebit            
- subjBank             
- script_exist         
- checkPopup           
- checkJS              
- NoOnClick            
- html_exist           
- form_exist           
- noFunctionWords      
- avgDomainLength      
- noWords              
- check_suspend        
- check_verify         
- noOfURLs             
- noOfLinks            
- checkIP              
- checkAtSym           
- checkURLShorten      
- checkImg             
- checkPort            

--------------------------------------------------------------
Solution folder
--------------------------------------------------------------

Tested Answers: Working Emails that can Break Machine Learning Model

crisis-email-answer: Filled Blanks and Suggested Answers for Jupyter Notebook

