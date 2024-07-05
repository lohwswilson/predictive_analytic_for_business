---
title: Data Mining Techniques
author: [Wilson Loh]
date: 2022-05-01
---

## Introduction to data mining

Data mining, also referred to as knowledge discovery in data (KDD), involves the process of unveiling patterns and valuable insights within extensive datasets. With the advancement of data warehousing technology and the surge in big data, the adoption of data mining techniques has experienced rapid growth over the past few decades. These techniques have been instrumental in helping organizations convert their raw data into actionable knowledge. Nevertheless, despite ongoing technological progress in handling large-scale data, leaders still grapple with challenges related to scalability and automation.

<br>
Data mining has significantly enhanced decision-making within organizations through insightful data analyses. The techniques underpinning these analyses serve two primary purposes: they can either describe the characteristics of the target dataset or predict outcomes by leveraging machine learning algorithms. These methods are employed to structure and sift through data, bringing forth the most pertinent information, spanning areas such as fraud detection, user behaviour analysis, identifying operations bottlenecks, and even uncovering security breaches for software.

<br>
The key properties of data mining are

- **Automatic:** Data mining operates autonomously, utilizing algorithms to extract insights from data. As such, it does not necessitate human intervention to uncover patterns and trends within datasets.
- **Predictive:** Data mining serves as a valuable tool for making predictions regarding future events. For instance, a bank could employ data mining to forecast which customers are at risk of loan default.
- **Knowledge Discovery:** Data mining has the capacity to unearth novel knowledge from datasets. This newfound knowledge can be harnessed to enhance decision-making, pinpoint emerging opportunities, and mitigate costs.
- **Large Datasets:** Data mining can be effectively applied to extensive datasets, commonly referred to as big data. This is made feasible by the inherent capability of data mining algorithms to handle substantial data volumes.
- **Various Data Types:** Data mining is adaptable across various data types, encompassing structured data such as customer records and unstructured data like text and images.

## The Scope of Data Mining**

The term _data mining_ draws an analogy to the process of extracting valuable business insights from extensive databases, akin to mining for precious ore within a mountain. Both endeavours share the commonality of needing to navigate through vast volumes of material, whether by sifting through it systematically or by intelligently probing to pinpoint areas of value. When dealing with databases of substantial size and quality, data mining technology offers a range of capabilities that can catalyse new business opportunities, including:

- **Automated Prediction of Trends and Behaviours:** Data mining serves as an automated means of uncovering predictive information within large databases. Questions that previously demanded extensive manual analysis can now be swiftly addressed directly from the data itself. A quintessential example of a predictive challenge lies in targeted marketing. Data mining harnesses historical data from past promotional mailings to identify the individuals most likely to yield the highest return on investment in future campaigns. Other predictive tasks encompass forecasting bankruptcy or default rates and discerning segments within a population prone to exhibiting similar responses to specific events.

- **Automated Discovery of Previously Unknown Patterns:** Data mining tools traverse databases in search of concealed patterns, unveiling them in a single comprehensive step. For instance, pattern discovery can be observed in the analysis of retail sales data, where seemingly unrelated products that are frequently purchased together are identified. Additional pattern discovery applications extend to the detection of fraudulent credit card transactions and the recognition of anomalous data points that may signify data entry errors.

In essence, data mining is akin to the astute exploration of a data-rich terrain, unearthing valuable insights and patterns that were previously hidden beneath the surface, thereby empowering businesses to make informed decisions and discover novel opportunities (Tan 2019).

## Six Phases of Data Mining Process

Using the flexible CRISP-DM phases, data teams can move back and forth between stages as needed. Also, software technologies can do some of these tasks or support them for data mining process.

### Business Understanding

Commencing the process, the data scientist or data miner initially delineates the project's objectives and its scope. This involves close collaboration with business stakeholders to ascertain specific details, which encompass

- Identifying the issues that demand resolution
- Recognizing project constraints or limitations
- Assessing the potential business ramifications of proposed solutions

Subsequently, this information serves as the foundation for delineating data mining objectives and pinpointing the resources indispensable for the pursuit of knowledge discovery

### Data Understanding

Upon comprehending the business challenge at hand, data scientists initiate an initial examination of the data. This process involves collecting data sets from diverse origins, securing necessary access permissions, and crafting a comprehensive data description report. This report encompasses crucial details such as data types, volume, and the hardware and software prerequisites essential for data processing. Once the business greenlights their strategy, they embark on the journey of data exploration and validation. They employ elementary statistical methods to manipulate the data, evaluate its quality, and ultimately select a definitive data set for the ensuing phase

### Data Preparation

This phase consumes the majority of data miners' time as data mining software demands top-notch data quality. Business operations typically accumulate and maintain data for purposes unrelated to mining, necessitating data refinement before it can be employed for modelling. Data preparation encompasses the subsequent procedures

- Clean the data: This involves tasks such as addressing missing data, rectifying data errors, handling default values, and making necessary data corrections
- Integrate the data: This process entails merging two distinct data sets to create the ultimate target data set
- Format the data: This step includes actions like data type conversions or configuring data to align with the specific mining technology in use

###Data Modelling

Data miners feed the refined data into the data mining software and examine the outcomes. In this process, they have the flexibility to select from a variety of data mining techniques and tools. Additionally, they need to devise tests to evaluate the quality of the data mining results. When modelling the data, data scientists have the capacity to

- Train machine learning (ML) models using smaller datasets with known outcomes
- Employ the model to delve deeper into the analysis of unfamiliar datasets
- Fine-tune and adapt the data mining software until the results meet the desired level of satisfaction

### Evaluation

After constructing data mining models to address specific business objectives, data miners shift their focus to evaluating the models. This evaluation phase involves sharing the model outcomes with business analysts and collecting their input. Depending on the feedback received, data miners have the flexibility to refine the model, adapt the initial business objectives, or revisit the data itself. This iterative process of evaluation, feedback, and adjustments is a pivotal element of the knowledge discovery process. It not only ensures that the models align with the evolving business needs but also allows for the discovery of unexpected patterns or opportunities that may enhance decision-making

<br>
For instance, in the context of a retail company using data mining to optimize marketing strategies, the evaluation phase might reveal that a previously overlooked demographic is responding exceptionally well to a campaign. This newfound insight can lead to a targeted marketing approach and potentially influence the modification of the existing model to incorporate this valuable discovery. Ultimately, this ongoing cycle of assessment and refinement enables data mining efforts to continually provide actionable insights and adapt to the dynamic landscape of business objectives

### Deployment

During the deployment phase of data mining, the organization puts the data-driven insights and models into practical use. Data scientists lead this phase, ensuring seamless integration of the models into existing systems. They also educate stakeholders on the model's functionality and provide ongoing support. Business analysts utilize the deployed models to craft reports, enhance decision-making, and improve business processes. Continuous monitoring and maintenance of the data mining application are essential to uphold its performance and adapt it to changing data and business needs

<br>
For instance, in the context of an e-commerce company, data scientists integrate a recommendation system into their website and mobile app. Business analysts use this system to provide personalized product recommendations to customers, while data scientists continuously monitor and fine-tune the model for accuracy. This ongoing deployment process ensures that data-driven insights become an integral part of the organization's operations, ultimately enhancing customer experiences and business outcomes (Data Mining: What Is It and Why It’s Important - AWS, 2023)

## Data Quality and Data Mining

&nbsp;  
In the real world, data often exhibits a degree of disorderliness. This disorderliness can stem from a variety of factors, including device malfunctions, errors during data entry, or the amalgamation of data from disparate sources. To attain high-quality results from data mining that are not only actionable but also beneficial, it is imperative to rectify this disorderly data.

Furthermore, data can be extensive both in terms of its size and the number of attributes it encompasses, which can lead to the concealment of significant patterns within its subcomponents. Hence, it is crucial to direct our attention to the pertinent sections of the data, considering both its volume and attributes.

Data preprocessing plays a critical role in data mining and machine learning by ensuring the quality of the data used for analysis. Various factors are employed to assess data quality., including:

- **Incompleteness:**  Missing data in a dataset, resulting from various factors like data entry errors or transmission issues, poses a critical challenge in data preprocessing for data mining and machine learning. To maintain dataset completeness and reliability, preprocessing techniques like imputation are employed. Imputation involves estimating missing values based on available data, ensuring that statistical characteristics are preserved. This step is essential for accurate and meaningful analysis, as it enables data scientists to address missing data effectively and enhance the quality of the dataset for subsequent modeling and insights.
- **Inconsistency:** Inconsistent data, stemming from errors in data entry, integration, or storage, can introduce conflicts and contradictions in a dataset. Data preprocessing techniques, such as data cleaning and data integration, are essential for detecting and resolving these inconsistencies. Data cleaning involves identifying and rectifying errors and standardizing formats, while data integration focuses on harmonizing conflicting data from multiple sources. By employing these techniques, data scientists ensure that the dataset is accurate and consistent, facilitating meaningful analysis and reliable model construction.
- **Noise:** Noise in a dataset, stemming from random or irrelevant data introduced during data collection or entry errors, can obscure meaningful patterns. Data preprocessing techniques like data smoothing and outlier detection are crucial for noise reduction. Data smoothing helps remove unnecessary variations, creating a more stable dataset, while outlier detection identifies and isolates data points significantly deviating from the majority, often erroneous or irrelevant, ensuring dataset integrity. These preprocessing steps result in a cleaner, more reliable dataset, facilitating accurate analysis and modelling.
- **Outliers:** Outliers, which are data points significantly differing from the majority in a dataset, can arise from various sources such as data collection or entry errors. Data preprocessing is instrumental in addressing outliers through techniques like detection and removal. Outlier detection systematically identifies these exceptional data points to prevent distortions in subsequent analyses and models, while outlier removal ensures dataset consistency and robustness. This preprocessing step enhances data quality, rendering it more suitable for accurate and reliable analysis and modelling, as illustrated by the example of an outlier student's exam score influencing the class's average performance analysis.
- **Redundancy**: Redundancy in a dataset denotes the presence of duplicated or overlapping data, often arising from processes like data integration or storage. To enhance dataset efficiency, preprocessing techniques such as data deduplication are employed. Data deduplication systematically identifies and eliminates duplicate data points, ensuring data uniqueness and preventing unnecessary replication. This streamlining process simplifies subsequent analysis and modeling, as exemplified by removing duplicate entries of the same customer in a customer database.
- **Data format:** Data format and structure in a dataset refer to how information is organized, encompassing various formats like text, numbers, or categories. Data preprocessing steps, such as data transformation and normalization, are vital for converting data into a consistent format for analysis. Data transformation involves altering data formats, aggregating or disaggregating, or creating new features, ensuring uniformity in data structure. Normalization scales numerical data to a consistent range, enhancing compatibility for analytical methods and allowing fair comparisons. These preprocessing techniques enable data scientists to work with a standardized dataset, promoting meaningful analysis and modelling, exemplified by converting product prices in various currencies to a common format in a product dataset. (Data Mining Data Attributes and Quality, 2020).

## Forms of Data Preprocessing

Data pre-pocessing encompasses a range of tasks, as elaborated upon in the subsequent sections (_Janeja 2022_).

- **Data Cleaning:** In the realm of network traffic data, issues frequently arise, such as missing data values stemming from dropped packets, temporal fluctuations in traffic, and inherent redundancies in communication data. This initial phase addresses the general tidying up of untidy data, tackling (a) missing data values, (b) noisy data, and (c) data inconsistencies and redundancies.
- **Data Transformation and Integration:** When data originates from multiple sources, it may possess differing resolutions, such as yearly versus daily timestamps, or exhibit varying attribute ranges, sometimes spanning large intervals. In these scenarios, the data requires transformation to enable consistent application of traditional data mining algorithms. Additional integration steps, including mapping the structure and content, must also be performed.
- **Data Reduction:** Data mining proves invaluable when patterns must be extracted from vast datasets, such as Wireshark's network traffic data or source-destination communication graphs. is a process in data mining and data analysis aimed at reducing the volume but producing the same or similar analytical results. It involves techniques and methods to simplify and condense complex datasets while retaining their essential characteristics.

## Data Mining Techniques

Data mining techniques are a set of methods, algorithms, and tools used to extract meaningful patterns, knowledge, and insights from large and complex datasets. These techniques enable organizations to uncover hidden information, make predictions, and support decision-making processes. Data mining is widely applied across various domains, including business, healthcare, finance, and science (Simplilearn, 2022).

Here, we'll discuss some fundamental data mining techniques:

### Classification

Classification involves the grouping of data into predefined categories or classes based on attributes' values. The primary objective of this data mining method is to assign a document to a specific class by analysing the attributes. The core aim is to organize data into predetermined classes.

<br>
The most common application of classification is predicting a variable with multiple potential values based on one or more input factors, known as predictors. For example, it can be used to differentiate between spam and non-spam emails or to assess product reviews as good, neutral, or negative.

### Clustering

Clustering is another data mining technique that entails grouping similar entries within a dataset to form clusters. Instead of predefined categories, clustering identifies these groups within the dataset and then categorizes elements based on their inherent characteristics. Unlike classification, which assigns variables to established categories, clustering focuses on discovering inherent data patterns.

<br>
For instance, you can cluster customers based on their purchasing behaviours, such as those who consistently buy specific beverages or pet food with consistent taste preferences. Once these clusters are identified, targeted advertising can be directed toward them

<br>
Clustering serves various purposes, including applications in web analytics, text mining, biological computation, and medical diagnosis.

### Association Rule Learning

Association rule learning involves discovering patterns between two or more independent variables. This data mining technique seeks to identify if-then relationships among variables. A common example is the association between buying bread and butter; often, when bread is purchased, butter is also bought, and vice versa. Supermarkets often place these two items together due to this association.

<br>
However, associations can be more intricate. For instance, Walmart observed that sales of Strawberry Pop-Tarts surged just before a hurricane, as people stocked up on them along with essentials like batteries. This association may not be immediately obvious but was discovered through data mining techniques.

### Regression

Regression is a data mining technique that establishes relationships between variables. Its purpose is to identify the most appropriate function that captures the relationship between variables. Linear regression, for example, employs a linear function (y = ax + b) to model the connection. Other forms of regression, such as multiple linear regression and quadratic regression, can account for different types of relationships.

<br>
Regression finds applications in planning and modelling, such as estimating a customer's age based on their past purchases or forecasting prices based on factors like consumer demand.

### Anomaly Detection

Anomaly detection is a data mining technique used to identify outliers or values that deviate significantly from the norm. For instance, it can detect unusual sales spikes at a store during a specific week in e-commerce data. Anomaly detection has various applications, including detecting credit card fraud, identifying network attacks or disruptions, and pinpointing irregularities in data (IBM Documentation, 2021).

## Making Decision on Choosing Data Mining Techniques

The best data mining technique to use will depend on the specific problem you are trying to solve. For example, if you are trying to predict customer churn, you might use classification. If you are trying to identify customer segments, you might use clustering.

When choosing a data mining technique, it is important to consider the following factors:

- The data: What data do you have available? What is the quality of the data?
- The problem: What are you trying to solve? What are your goals?
- The resources: What resources do you have available? How much time and money do you have?
- The expertise: What level of expertise do you have in data mining?

By considering these factors, you can choose the data mining technique that is most likely to be successful for your specific problem.

## Transform Your Business with Data Mining

![type:video](https://www.youtube.com/embed/7rs0i-9nOjo?si=V4oYXJhgsoF8Ico4)


## Reference List

- Geeksforgeeks. (2020). _Data Mining: Data Attributes and Quality - GeeksforGeeks._ <https://www.geeksforgeeks.org/data-mining-data-attributes-and-quality/>.
- Amazon Web Services. (2023). _Data Mining: What is it and why it's important - AWS._ <https://aws.amazon.com/what-is/data-mining/>.
- IBM. (March 2021). _Data mining functions and algorithms. IBM Documentation._ <https://www.ibm.com/docs/en/db2/10.1.0?topic=miner-data-mining-functions-algorithms>.
- IBM Technology. (2022). What is Data Mining? \[YouTube Video\]. In _YouTube_. <https://www.youtube.com/watch?v=7rs0i-9nOjo&t=377s>
- Janeja, V. P. (2022). Introduction to Data Mining: Clustering, Classification, and Association Rule Mining. In Data Analytics for Cybersecurity (pp. 29–59). Cambridge University Press. <https://doi.org/10.1017/9781108231954.004>
- Simplilearn. (2022, November 22). _Types of Data Mining Techniques_. Simplilearn.com; Simplilearn. <https://www.simplilearn.com/types-of-data-mining-techniques-article>
- Tan, P.-N., Steinbach, M., Karpatne, A., & Kumar, V. (2019). Introduction to data mining (Second edition.). Pearson Education, Inc.