---
title: Descriptve Analytics and Data Analysis
author: [Wilson Loh]
date: 2022-05-01
---

## Introduction to descriptive analytics and its role in data analysis

Business Analytics Domain of business analytics encompasses three key areas: descriptive analytics, predictive analytics, and prescriptive analytics. Databases and Data Warehousing facilitate efficient data storage and retrieval. Descriptive analytics focuses on reporting past events, while predictive analytics creates future predictions based on historical data. Prescriptive analytics employs optimization, heuristics, or simulation models to recommend optimal solutions and actions (Asllani, A., 2015).

<br>
Descriptive analytics involves quantitatively summarizing organizational data's key characteristics. Its goal is to summarize a sample of data rather than make inferences about the broader population it represents. Common tools in descriptive statistics include sampling, measures like mean and median, graphical representations, and summary statistics presented through charts, tables, and single numerical values.

<br>
Descriptive analytics, as exemplified by Netflix, involves identifying trends in customer preferences and behaviour. Netflix collects user data to determine which TV series and movies are trending, displaying them prominently on its platform. This not only helps users discover popular content but also informs Netflix's decision-making regarding future content creation, production contracts, marketing strategies, and retargeting campaigns, showcasing the practical use of descriptive analytics in enhancing user experience and guiding business strategies (What Is Descriptive Analytics? 5 Examples | HBS Online, 2021).

## Data Driven vs Model Driven Approach

Descriptive analytics encompasses two primary methodologies: data-driven and model-driven approaches.

<br>
Data-driven descriptive analytics relies on data to portray past occurrences or trends without requiring prior knowledge of the system or process under scrutiny. This approach proves valuable in scenarios where comprehension of the system or process is limited.

<br>
Model-driven descriptive analytics employs a pre-established model of the system or process to depict past events or trends. This necessitates some prior knowledge of the system or process but has the potential to yield more precise and intricate insights.

<br>
The choice between these approaches depends on the specific circumstances. When understanding of the system or process is minimal, data-driven descriptive analytics is a suitable choice. Conversely, when there is a more comprehensive understanding, model-driven descriptive analytics can be employed to attain more accurate and detailed insights (_Reality Analytics, 2016_).

<br>
Here are some examples illustrating the applications of each approach:

<br>
Data-driven descriptive analytics can be utilized to:

- Identify trends in customer behaviour
- Analyse the effectiveness of a marketing campaign
- Track the performance of a machine learning model

Model-driven descriptive analytics can be employed to:

- Understand the impact of a new product launch
- Forecast demand for a product
- Analyse the risk of a financial crisis

In general, data-driven descriptive analytics offers greater flexibility and can be applied across a broader spectrum of scenarios. However, model-driven descriptive analytics can deliver heightened accuracy and detailed insights when there exists a solid grasp of the system or process under examination.

## Aspect of Data Quality

Data quality plays a pivotal role in evaluating whether information is suitable for a specific context, such as data analysis. To gauge the quality of a dataset, it's essential to consider specific data quality characteristics. These characteristics encompass five key traits: accuracy, completeness, reliability, relevance, and timeliness, each of which is essential for assessing data quality effectively (Rachel Levy Sarfin, 2022).

- **Accuracy:** As the term suggests, pertains to the correctness of information. To ascertain the accuracy of data, it's essential to consider if the information accurately represents a real-world scenario.

- **Completeness:** It involves ensuring that all necessary data points are present and accounted for. For instance, while collecting customer information, you may require both the first and last names, with the middle initial being optional. The importance of completeness in data quality lies in its usability

- **Timeliness:** Timeliness refers to the freshness or recency of data. It assesses whether data is up-to-date and relevant within the current timeframe. Timeliness is crucial in scenarios where outdated data can lead to missed opportunities or inaccurate assessments. Ensuring data is timely involves maintaining regular updates and minimizing delays in data collection and reporting.

- **Reliability:** In the context of data quality, reliability indicates that a piece of information does not contradict information from other sources or systems. Reliability is a critical data quality characteristic because when data contradicts itself, trust in the information is compromised. Such inconsistencies can lead to costly errors and reputational damage for a business or organization.

- **Relevance:** Relevance pertains to whether the data is pertinent and applicable to the context in which it is used. It involves ensuring that the data collected or analysed serves a meaningful purpose and aligns with the objectives of the analysis or decision-making process. For example, in a marketing campaign, relevant data would include customer demographics and preferences that directly influence campaign targeting. Irrelevant data can clutter analyses and lead to misguided decisions.

## Types of data

Data types encompass various attributes or quantities that exhibit variability among different units of investigation. These attributes can take on different values, making them key elements in data analysis.

When dealing with quantitative data, it can be categorized into two main types: discrete and continuous data.

- **Discrete Data:** Discrete data refers to a variate that can assume only a finite or countable number of distinct values. This type of data typically involves counting or enumerating items. For example, when counting the number of customers in a store, the resulting data is discrete since it can only take on whole numbers, such as 1, 2, 3, and so forth. Discrete data is often represented using bar charts or histograms, which visually display the frequency of each possible value.

- **Continuous Data:** On the other hand, continuous data relates to a variate that represents measurements and can take any value within a specific interval along the real number line. These measurements can include quantities like weight, height, or temperature. Unlike discrete data, continuous data can assume an infinite number of values within its range. Visual representations of continuous data typically involve smooth curves, such as probability density functions or frequency polygons. Continuous data analysis often involves calculating statistics like mean, standard deviation, and percentiles to understand central tendencies and variability within the data.

Understanding the distinction between discrete and continuous data types is essential in descriptive statistics, as it influences the choice of appropriate statistical techniques and visualizations for analysing and interpreting the data effectively.

## Scale of Measurement

In statistics, measurement scales, also known as levels of measurement or types of data, classify variables into four main categories based on the nature of the data and the mathematical operations that can be performed on them. These four measurement scales are:

1. **Nominal Scale:**
    - Nominal data represent categories or labels that cannot be ranked or ordered.
    - It is the simplest form of measurement scale.
    - You can only perform basic operations like counting and mode calculation on nominal data.
    - Examples:
        - Colours (e.g., red, blue, green)
        - Marital status (e.g., married, single, divorced)
        - Types of animals (e.g., cat, dog, bird)
2. **Ordinal Scale:**
    - Ordinal data represent categories with a natural order or ranking.
    - The intervals between categories are not necessarily equal.
    - You can perform operations like counting, mode calculation, and median calculation on ordinal data.
    - Examples:
        - Educational levels (e.g., elementary, middle school, high school, college)
        - Customer satisfaction ratings (e.g., very dissatisfied, dissatisfied, neutral, satisfied, very satisfied)
        - Socioeconomic status (e.g., low income, middle income, high income)
3. **Interval Scale:**
    - Interval data represent values with equal intervals between them, but they lack a true zero point.
    - Arithmetic operations such as addition and subtraction can be performed, but multiplication and division are not meaningful.
    - Examples:
        - Temperature measured in degrees Celsius or Fahrenheit (0°C does not mean absence of temperature)
        - IQ scores (a score of 0 does not mean a complete lack of intelligence)
4. **Ratio Scale:**
    - Ratio data have all the properties of interval data but also have a true zero point, which signifies the absence of the quantity being measured.
    - You can perform all arithmetic operations (addition, subtraction, multiplication, and division) on ratio data.
    - Examples:
        - Age (0 years indicates the absence of age)
        - Height in centimeters or inches (0 cm/inch indicates no height)
        - Income (0 income indicates no income)

In summary, these measurement scales help researchers and statisticians determine the appropriate statistical techniques and operations to apply to their data. Nominal and ordinal data are often referred to as categorical data, while interval and ratio data are considered numerical data. Understanding the measurement scale of your data is crucial for selecting the right statistical analyses and drawing meaningful conclusions from your research.

## Central Tendency Measures

The concept of central tendency measures serves as a statistical tool for characterizing the core or representative value within a dataset. It offers a means to concisely encapsulate a collection of data points with a single value that embodies the essence of the entire dataset. The three primary central tendency measures commonly employed are the mean, median, and mode.

- **Mean (Average):**

The mean, also known as the average, is derived by adding up all the values in a dataset and then dividing this sum by the number of values.

The mean is sensitive to extreme values (outliers) and is primarily suited for data following a roughly normal distribution.

- **Median:**

The median corresponds to the middle value when arranging data points in ascending or descending order. In cases with an even number of data points, the median is computed as the average of the two middle values.

Calculating the median is straightforward for datasets with an odd number of values, but for datasets with an even number of values, you must determine the average of the two central values.

  - Example 1 (odd number of values): Consider the dataset \[12, 7, 19, 4, 21\]. After sorting it in ascending order: \[4, 7, 12, 19, 21\], the median is 12, which occupies the central position.

  - Example 2 (even number of values): For the dataset \[8, 15, 22, 11\], when arranged: \[8, 11, 15, 22\], the median becomes the average of 11 and 15, which equals 13.

The median is less influenced by outliers and is often applied to skewed or non-normally distributed data.

- **Mode:**

The mode signifies the value that appears most frequently within a dataset. A dataset can possess a solitary mode (unimodal) or multiple modes (multimodal) if two or more values share the highest frequency.

  - Example 1 (unimodal):

    In the dataset \[5, 7, 7, 9, 11\], the mode is 7 as it appears most frequently (twice).

  - Example 2 (multimodal):

    In the dataset \[3, 3, 5, 7, 7, 9\], two modes emerge: 3 and 7, since both values exhibit the highest frequency (twice).

The mode assists in identifying the most common value(s) in categorical or discrete data

<br>
The selection of the appropriate measure hinges on the nature of your data and the specific query you aim to address. In certain cases, a combination of these measures may be necessary to attain a more comprehensive understanding of central tendency within your dataset (Measures of Central Tendency, 2023).

## Distribution - Frequency Analysis

Frequency analysis is a statistical method that describes the distribution of values in a set of data. It does this by counting the number of times each value occurs. This information can be used to understand the shape of the distribution, identify the most common values, and find out how spread out the data is (_Shreffler & Huecker, 2023_).

<br>
Here is an example of frequency analysis. Let's say we have a set of data that shows the heights of 100 people. We can create a frequency table to show how many people have each height. The table might look like this:

<br />
<div class="center-table" markdown>
| Height (cm) | Frequency |
--------------|------------
|     160     |     20    |
|     165     |     25    |
|     170     |     30    |
|     175     |     15    |
|     180     |     10    |
</div>
<br />

This table tells us that 20 people in the data set are 160 cm tall, 25 people are 165 cm tall, and so on. We can see that the most common height is 170 cm, and that the data is fairly evenly distributed.

<br>
Frequency analysis is a powerful tool that can be used to gain insights into a data set. It is a relatively simple method to understand, but it can be very effective in summarizing and describing data.

<br>
Here are some additional details about frequency analysis:

- The frequency table is the most common way to display the results of frequency analysis. It can be either a simple table or a more complex table with additional information, such as the cumulative frequency or relative frequency.
- The cumulative frequency is the sum of the frequencies of all the values less than or equal to a given value. The relative frequency is the frequency of a value divided by the total number of values in the data set.
- Frequency analysis can be used to create other graphical representations of data, such as histograms and bar charts. These graphs can be helpful in visualizing the distribution of data and identifying patterns.
- Frequency analysis is a versatile tool that can be used in a variety of statistical applications. It is a valuable tool for understanding data and making informed decisions.

## Measures of variability

A measure of variability in statistics serves to depict the extent to which values within a dataset are dispersed, quantifying the degree of variation present in the data. Various measures of variability are available, with some of the most prevalent ones encompassing:

- **Range:** This measure calculates the disparity between the highest and lowest values found in the dataset.
- **Interquartile Range (IQR):** The IQR quantifies the deviation between the 75th and 25th percentiles, offering insights into the central 50% of the data.
- **Variance:** This metric computes the average of the squared deviations from the dataset's mean.
- **Standard Deviation:** The standard deviation is essentially the square root of the variance, providing a measure of dispersion around the mean.
- **Coefficient of Variation:** This dimensionless statistic, obtained by dividing the standard deviation by the mean, is frequently used to compare variability among datasets with different units of measurement.

The choice of which measure of variability to apply hinges on the specific dataset under examination and the objectives of the analysis. The range is the simplest but less sensitive to variations within the middle of the dataset. In contrast, the IQR is more responsive to mid-range variability but less influenced by outliers compared to the variance and standard deviation. The latter two are the most sensitive measures, yet they are susceptible to the influence of outliers.

<br>
For illustration, suppose we possess a dataset detailing the heights of 100 individuals, where the mean height stands at 170 cm. The range, in this case, spans 20 cm (ranging from the tallest at 190 cm to the shortest at 170 cm). Meanwhile, the IQR encompasses 10 cm (with the 75th percentile at 175 cm and the 25th percentile at 165 cm). The variance amounts to 25 cm², while the standard deviation is 5 cm.

<br>
Each of these variability measures offers distinct insights into the dataset. The range signifies the span between the dataset's smallest and largest values. The IQR provides information about the middle 50% of data points. The variance and standard deviation elucidate the degree of dispersion around the mean.

<br>
These varied measures of variability can be employed to address diverse questions concerning the dataset. The range helps pinpoint the dataset's extremities, while the IQR focuses on the central portion. Meanwhile, the variance and standard deviation gauge the extent of data dispersion relative to the mean (Expert Help Guides: Maths: Measures of Variability, 2023).

## Measure of Shape Distribution

In a statistic, a measure of distribution shape refers to a statistical metric that characterizes how the distribution of a dataset is structured. This measure quantifies the extent of symmetry, the level of peakiness, and the presence of outliers within the dataset.

Various metrics exist to assess distribution shape, with some of the most common ones including:

- **Skewness:** Skewness measures the degree of asymmetry in a distribution. If a distribution is not symmetrical around its mean, it is considered skewed. Skewness can be either positive (right-skewed) or negative (left-skewed).
- **Kurtosis:** Kurtosis gauges the peakedness or flatness of a distribution. A distribution is described as kurtotic if its peak is more pronounced or flatter compared to a normal distribution. Kurtosis can be positive (leptokurtic), negative (platykurtic), or equal to 0 (mesokurtic).
- **Outliers:** Outliers are values that significantly deviate from the rest of the data points in a distribution. They can arise due to data collection errors or genuine variations within the population.

The selection of the appropriate measure of distribution shape depends on the specific dataset and the objectives of the analysis. Skewness and kurtosis are often used in combination to provide a comprehensive description of a distribution's shape. Outliers can be detected using various techniques, such as the interquartile range (IQR) or the Grubbs test (Measures of Shape, 2023).

## Correlation Analysis

Correlation analysis is a statistical technique employed to assess the strength and direction of the connection between two variables. This analytical approach is bivariate in nature, focusing solely on examining the association between a pair of variables at any given time.

<br>
The correlation coefficient serves as a metric for gauging the intensity of the bond between these two variables. It assumes values within the range of -1 to 1. A correlation coefficient of +1 signifies a complete positive correlation, -1 indicates an absolute negative correlation, and 0 suggests no discernible correlation.

<br>
The orientation of this association is conveyed by the sign of the correlation coefficient. A positive correlation coefficient signifies that both variables move in tandem, while a negative correlation coefficient implies opposing movements.

<br>
For instance, suppose we have data detailing the heights and weights of 100 individuals. Using correlation analysis, we can explore the connection between height and weight. In this scenario, the calculated correlation coefficient is 0.8, signifying a robust positive correlation. Essentially, taller individuals tend to have greater weight, whereas shorter individuals tend to have lower weight.

<br>
Correlation analysis can address various inquiries, including the presence of a linear connection between two variables, the degree of this association, its direction, and whether one variable can be utilized to predict the other.

<br>
This method is adaptable and applicable across diverse domains such as psychology, sociology, economics, business, and medicine. Here are additional instances where correlation analysis comes into play:

- Investigating the link between smoking habits and lung cancer incidence.
- Assessing the relationship between income levels and educational attainment.
- Exploring the correlation between body weight and height.
- Examining the connection between test scores and study hours.

In essence, correlation analysis is a valuable analytical tool with a wide range of applications, enabling insights into relationships between variables in various disciplines and research areas (Correlation in Statistics: Correlation Analysis Explained, 2023).

## Reference List

- Asllani, A. (2015). Business analytics with management science models and methods (1st edition). Pearson Education.
- Stephanie Glen. "Correlation in Statistics: Correlation Analysis Explained" From StatisticsHowTo.com: Elementary Statistics for the rest of us! <https://www.statisticshowto.com/probability-and-statistics/correlation-analysis/>
‌- Latrobe. (2023). _Measures of variability - Maths - Expert help guides at La Trobe University._ <https://latrobe.libguides.com/maths/measures-of-variability>.
- Australia Bureau of Statistics. (2023). _Measures of central tendency | Australian Bureau of Statistics._ <https://www.abs.gov.au/statistics/understanding-statistics/statistical-terms-and-concepts/measures-central-tendency>.
- Australia Bureau of Statistics. (2023). _Measures of shape | Australian Bureau of Statistics._ <https://www.abs.gov.au/statistics/understanding-statistics/statistical-terms-and-concepts/measures-shape>.
- Rachel Levy Sarfin. (2022, November 2). 5 Characteristics of Data Quality - See why each matters to your business. Precisely; <https://www.precisely.com/blog/data-quality/5-characteristics-of-data-quality>
- Reality Analytics. (2016, July 20). _Model-Driven vs Data Driven methods for Working with Sensors and Signals_. Medium; Medium. <https://medium.com/@RealityAI/model-driven-vs-data-driven-methods-for-working-with-sensors-and-signals-98fc6ac8cc92>
- Shreffler, J., & Huecker, M. R. (2023, February 13). Exploratory Data Analysis: Frequencies, Descriptive Statistics, Histograms, and Boxplots. Nih.gov; StatPearls Publishing. <https://www.ncbi.nlm.nih.gov/books/NBK557570/>
- Catherine Cole. (2021). _What Is Descriptive Analytics? 5 Examples | HBS Online._ <https://online.hbs.edu/blog/post/descriptive-analytics>.
