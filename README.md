# About the Project
This is a project for the subject Data Science at Rennes School of Business. It aims to create cluste
It aims to analyze Sephora products using clustering techniques in a dataset called df_prod, and perform sentiment analysis on review 
comments in a dataset called df_rev. We will use techniques to group Sephora products based on various attributes such as price, category, brand, and customer ratings. This clustering helps to identify patterns and trends within the product offerings. Additionally, the sentiment analysis is used to review comments to assess customers feedback. This analysis will provide valuable insights into customer perceptions and preferences.     

Our approach includes visualizing data distributions, examining relation between different factors, clustering and sentimental techniques sucha s the polarity, intensity, and aspects analysis. The insights derived aim to enhance our understanding of customer behavior and preferences, enabling more effective marketing strategies.

Through collaboration among our team of five university students, we aim to leverage our diverse skill sets in programming, data analysis, and statistical modeling to deliver a comprehensive report that addresses the research question: "How can clustering and sentiment analysis of Sephora products and reviews improve marketing strategies?"    


## Team member
*   **[Kuan-Yu HOU](https://github.com/DoreenHou)** 
*   **[Shao Yu-Linn](https://github.com/shaoyulinn)**   
*   **[Annie HUNG](https://github.com/RUEI-CHIEH)**
*   **[Yi-Hsin TUNG](https://github.com/evatung0719)**
*   **[Xian Harding Anglés](https://github.com/r41ss4)**    

## The Dataset
The datasets have been obtained through **[Kaggle](https://www.kaggle.com/)** platform and selected to provide relevants insights regarding Sephora products and reviews. 
*   **df_prod:** It includes a wide range of products available in Sephora and its characteristics, such as name, brand and size, and more. It includes 27 columns and 8494 rows. It was extracted from **[Sephora Products and Skincare Reviews](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data?select=product_info.csv)**      
*   **df_rev:** Dataset contains multiple reviews done by customers in Sephora's website. It includes 18 columns and 49918 rows. It was extracted from **[Sephora Products and Skincare Reviews](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data?select=product_info.csv)**           

## Folders and organization 
```
rennes_ds/          
│           
├── data/         
│   ├── raw/                   
│   │   ├── raw_products.csv               
│   │   └── raw_reviews.csv     
│   ├── cleaned/        
│   │   ├── clean_products.csv        
│   │   └── clean_reviews.csv            
│   └── clust_sent/ 
│       ├── prod_clust.csv        
│       ├── prod_clust_sent.csv        
│       └── rev_sent.csv           
│                       
├── notebooks/                    
│   ├── Cleaning.ipynb         
│   ├── Clustering.ipynb          
│   ├── sentimental.ipynb      
│   └── coming.ipynb              
│       
├── .ipynb_checkpoints/     
├── .jupyter/           
├── .virtual_documents/         
├── .DS_Store   
├── Insights.md               
└── README.md          
```

## Methodology
**1. Data Cleaning:** We will preprocess the datasets to handle missing values, outliers, and inconsistencies.          
    
**2. Clustering Analysis:** Grouping similar products together based on their attributes to identify patterns and trends within the dat.
    **2.1. Elbow method:** Use the elbow method to determine the optimal number of clusters.     
    **2.2 Distribution analysis:** Evaluate the distribution of prices and ratings within each cluster.          
**3. Sentimental Analytics:** Perform sentiment analysis on review comments done by customers in Sephora website. 
    **Intensity:** Analyze the intensity of sentiments expressed in the reviews in a scale from -1 to 1.     
    **Polarity:** Determine the polarity (positive, negative, neutral) of the comments in a scale from -1 to 1.     
    **Aspect:** Identify specific aspects (features or attributes mentioned) in the feedback.       

## Conclusions
Feel free to review our findings in the file **[Insights.md](https://github.com/r41ss4/rennes_ds/blob/main/Insights.md)**. For more information, there is a full report available by request to team members of the project. 

## Tools and Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Visual Studio Code 
- GitHub repository

