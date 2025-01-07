# Philippine Spam SMS Clustering Project

This study explores the use of **unsupervised clustering algorithms**, such as **K-means** and **agglomerative hierarchical clustering**, to categorize and analyze spam SMS in the Philippines. By applying clustering techniques, it aims to uncover meaningful patterns and groupings within the dataset of Philippine spam messages.

---

## **Dataset**  
This utilizes the publicly available **Philippine Spam/Scam SMS dataset** by **Bwandowando**, which contains 948 spam SMS text messages received from November 12, 2022 to November 13, 2024 in the Philippines. Contains both Filipino and English forms of languages.
- **Source**: [Philippine Spam/Scam SMS on Kaggle](https://www.kaggle.com/datasets/bwandowando/philippine-spam-sms-messages)  

---

## **Resources**  
To enhance the preprocessing and analysis, the following resources were used:  

1. **Filipino Wordlist**  
   - A comprehensive list of Filipino words to assist with tokenization and text processing.  
   - [GitHub Repository](https://github.com/AustinZuniga/Filipino-wordlist/blob/master/Filipino-wordlist.txt)  

2. **NLTK Stopwords List**  
   - A predefined list of common stopwords to filter out non-informative words.  
   - [Access the list](https://gist.github.com/sebleier/554280)  

3. **Filipino Stopwords**  
   - An extended list of Filipino-specific stopwords to refine the clustering process.  
   - [GitHub Repository](https://github.com/stopwords-iso/stopwords-tl/blob/master/raw/genediazjr-tagalog.txt)  

---

## **Goals**  
- To address the **need for multi-classification** by categorizing spam SMS into types such as regular, informational, advertisements, and fraud. While not all spam is harmful, some types, such as fraud, pose significant dangers. 
- To **categorize spam SMS messages** using clustering algorithms without relying on predefined labels.  
- To identify patterns, common phrases, and characteristics unique to spam messages in the Philippines.   
- To provide insights that may contribute to the improvement of spam detection systems. 
