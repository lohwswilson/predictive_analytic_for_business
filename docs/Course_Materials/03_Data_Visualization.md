---
title: Data Visualization
author: [Wilson Loh]
date: 2022-05-01
---

## What is Data Visualization ?

Data visualization is a powerful tool that translates complex data into easily understandable and insightful visuals. It goes beyond just presenting numbers and figures; it transforms raw data into graphical representations that can uncover trends, correlations, and anomalies that might otherwise remain hidden.

<br>
The primary aim of data visualization is to convey information in a clear and efficient manner using visual elements. It's important to note that effective data visualization doesn't have to sacrifice aesthetics for functionality or complexity for beauty. To effectively convey ideas, both visual appeal and practicality must work together, simplifying the understanding of complex and sparse data sets by presenting their essential aspects in an intuitive manner.

<br>
For example, imagine you have a dataset containing monthly sales figures for a retail store over the past year. Instead of looking at a long list of numbers, you can create a line chart that shows the sales trends over time. By visualizing the data in this way, you can quickly spot whether sales are increasing, decreasing, or remaining stable. This visual representation makes it much easier to grasp the overall sales performance and identify specific months where there might have been a spike or a dip in sales.

<br>
Data visualization isn't limited to simple charts and graphs; it can also involve more complex visualizations like heatmaps, scatter plots, and geographic maps. These visualizations can reveal intricate patterns and relationships within data, aiding in data exploration and decision-making (Friedman 2008).

## The Beauty of Data Visualization

David McCandless, a British data-journalist, curates a visually striking collection of graphs, charts, and maps covering diverse topics like science, food, dogs, and countries on his blog, "Information is Beautiful" (McCandless 2018).

<br>
One particularly intriguing creation, "International Number Ones: Because every country is good at something" (McCandless 2016), showcases unique achievements of each country according to data. Notably, the visualizations on this website are regularly refreshed and refined as new data becomes accessible.

<br>
<figure markdown="span">
  ![Country Visualization](./assets/03-01.png){ height="600" }
  <figcaption>Country Visualization</figcaption>
</figure>


## The Purpose of Data Visualization

The purpose of data visualization is quite evident: it aims to elucidate data and leverage the information for the advantage of the organization. Nevertheless, data itself is intricate, and its value escalates when it is visualized. Devoid of visualization, swiftly conveying data discoveries and pinpointing patterns to extract insights and engage seamlessly with the data becomes challenging.

<br>
While data scientists can discern patterns or anomalies without the aid of visualization, the ability to convey data findings and extract essential insights is of paramount importance. This is where interactive data visualization tools play a pivotal role.

<br>
A pertinent and contemporary illustration can be found in the ongoing pandemic. Undoubtedly, data scientists can delve into the data and derive insights. However, in the face of such an overwhelming volume of data, data visualization has proven invaluable in assisting experts in remaining informed and composed.

<br>
Data visualization amplifies the impact of messaging directed at various audiences and presents the results of data analysis in the most compelling fashion. It serves as a unifying force for messaging across diverse groups and departments within the organization.

<br>
Visualization enables individuals to grasp extensive data sets quickly and with greater clarity. It facilitates a deeper understanding of the data, enabling a more profound assessment of its impact on the business, and communicates these insights visually to both internal and external stakeholders.

<br>
Informed decision-making cannot occur in isolation. Access to available data and insights empowers decision-makers to conduct thorough decision analysis. Unbiased, accurate data is the key to accessing the right type of information, and visualization serves as the means to effectively represent and maintain the relevance of this information.

<br>
The potential of data visualization in resolving various business challenges is substantial. It is imperative for all businesses to integrate data visualization tools into their critical operational areas to reap transformative benefits (kesav kalluri, 2020).

## Basic Chart Type and Graphs

Charts play a vital role in the realm of data analysis, offering a means to distil vast data sets into easily comprehensible formats. Visual representations of data not only unearth insights for newcomers to the data but also effectively communicate discoveries to those who may not have access to the raw data. The vast array of available chart types each serves distinct purposes, and often, the greatest challenge in crafting a data visualization lies in selecting the most suitable chart type for the specific task at hand.

<br>
The choice of the appropriate chart type hinges on several factors. Consideration should be given to the nature of the metrics, attributes, or variables slated for representation. Additionally, the intended audience plays a pivotal role – is the visualization primarily for personal exploration or destined for a broader viewership? Finally, the desired message that you wish the audience to glean from the visualization should guide your selection (Mike YiMary Sapountzis, 2019).

- **Bar Chart:** A bar chart employs bars to represent values, with each bar aligning with a specific category or group. These charts can be oriented either vertically or horizontally, with vertical ones often referred to as column charts. Opting for a horizontal bar chart is advantageous when dealing with numerous bars to visualize, or when labels necessitate extra space for clarity.
- **Line Chart:** Line charts depict fluctuations in values along continuous measurements, particularly when data is tracked over time. The upward or downward movement of the line highlights positive and negative shifts, revealing overarching trends that assist readers in making predictions or future projections. Additionally, multiple line charts can lead to the creation of related charts like sparklines or ridgeline plots.
- **Scatter Plot:** A scatter plot represents values on two numerical variables through points placed on two separate axes, each dedicated to one variable. Scatter plots offer a flexible means of illustrating the connection between these variables, whether the correlation is robust or weak, positive or negative, linear or nonlinear. They are also valuable tools for pinpointing outlier points and detecting potential data gaps.
- **Box Plot:** A box plot employs boxes and whiskers to provide a concise summary of value distribution within distinct measured groups. The positioning of the box and the ends of the whiskers indicates the central areas where the bulk of the data is concentrated. Box plots are frequently utilized when there are multiple groups for comparative analysis, while other charts with greater detail are favoured when dealing with a single group for representation.
- **Histogram:** When the groups represented in a bar chart involve continuous numeric ranges, it's possible to condense the bars to create a histogram. In histograms, the lengths of the bars usually represent the frequency counts of data points, and their configurations reveal the distribution of variables within your data. However, if the vertical value doesn't represent a frequency count, a different chart type, such as a line chart, is typically chosen.
- **Stacked Bar Chart:** A variation of the typical bar chart involves splitting each bar into several smaller bars according to values from a secondary grouping variable, known as a stacked bar chart. This approach enables you to not only assess the primary group values, as you would in a standard bar chart, but also visually represent the proportionate breakdown of each group's entirety into its individual components.
- **Area Chart:** An area chart shares a common basis with a line chart, featuring interconnected value points with line segments. However, it introduces an element from the bar chart, incorporating shading between the line and a baseline. This type of chart is frequently utilized in conjunction with stacking, effectively illustrating changes not only in the overall total over time but also in the contributions of its individual components.
- **Bubble Chart:** An alternative method for illustrating the connection between three variables involves adapting a scatter plot. If the third variable is categorical, various shapes or colours can be employed to denote group affiliation among the data points. If there's an inherent order to the data points, they can also be linked with line segments to depict the sequence of values. When the third variable is numerical, this is where the bubble chart becomes relevant. A bubble chart extends the fundamental scatter plot by using the value of the third variable to determine the size of each data point.
- **Heat Map:** The heatmap displays a grid of data points derived from two variables under consideration. These axis variables can take on numerical or categorical forms, and the grid is formed by dividing each variable into intervals or categories, similar to how a histogram or bar chart is constructed. The cells within this grid are coloured according to their values, typically with darker shades indicating higher values. When there's a substantial number of data points to represent, but their density makes it challenging to discern the genuine relationship between variables, a heatmap offers an intriguing alternative to a scatter plot.
- **Pie Chart:** Pie charts are used widespread. However, pie charts employ an unconventional representation, depicting values as segments carved from a circular shape. As pie charts usually don't include explicit value labels around their circumference, it can be challenging to precisely determine the size of each slice. Nevertheless, both the pie chart and its variation, the donut plot, are particularly effective at emphasizing that the primary focus of the visualization should be the comparison of parts to the whole.
- **Map Plot:** There are various categories of specialized plots organized by their intended applications, and in concluding this article, we'll briefly explore one of them: map-based or geospatial plots. When data points within a dataset are associated with real geographic locations, it can be quite beneficial to visually represent them using a map. A prevalent example of this category is the choropleth map, similar to the one depicted above. In this approach, value is represented through colour, adopting a heatmap style, but instead of arranging values in a grid, they are assigned to specific regions on the map.

### What makes a chart effective?

Data visualization is a blend of creativity and scientific principles. In the realm of creativity, there are no fixed rules for visualization; numerous methods exist for presenting data. However, when dealing with facts, figures, and measurements, a structured approach enhances understanding and effectiveness.

<br>
For those new to data visualization, selecting the most suitable chart type can be challenging. Many individuals learn by emulating others' work without grasping the underlying rationale, resulting in a lack of theoretical understanding.

<br>
Therefore, prior to embarking on data visualization, it is essential to consider the following:

- **Determine the Purpose** (_Kosara 2016_) - (Analytical or Presentational): Understanding why you are creating a visualization is crucial. Visualizations can serve various purposes, such as exploring and analysing data to enable viewers to discover insights on their own or presenting findings to raise awareness or make decisions. For instance, a journalist creating a weather report visualization aims to present key trends and inform the general public, while climate scientists use visualizations to convey their findings to policymakers regarding climate change action.
- **Identify Your Audience** (_Mekhatria 2017_): After clarifying the purpose, it's vital to know who the intended audience is. Regardless of the target audience, customization to their specific needs, interests, expertise, and analytical abilities is essential. Cultural preferences, expertise levels, and other factors, like colour symbolism in different cultures, play a significant role in designing an effective visualization. For example, in Chinese culture, red represents dynamism or positivity, whereas in much of the Western world, blue or green symbolizes positive trends, such as sales revenue. A visualization created for a finance analyst will differ from one designed for a marketing manager, highlighting the importance of customization for effectiveness.
- **Choose the Right Chart Type** (_Mekhatria 2017_): Once the purpose and audience are determined, selecting the appropriate chart type is crucial. This ensures that the visualization resonates with the audience and empowers them to explore data, uncover insights, and make decisions based on different scenarios.

By addressing these questions, you can develop a clearer vision of the ideal chart for your data. A simplified guideline for using various chart types includes using line charts to track trends over time, bar charts for quantity comparisons, scatter plots for assessing the relationship between two data variables, bubble charts to depict the interaction of three data variables, and pie charts for comparing parts within a whole. However, let's delve further into various presentation styles and common chart types.

## Data Visualization Tools and Software

Data visualization tools are software applications crafted to assist individuals and organizations in visually representing data, simplifying the comprehension and extraction of insights from intricate datasets. These applications convert raw data into graphical formats, such as charts, graphs, maps, and dashboards, enabling users to discern trends, patterns, and correlations within the data.

<br>
Below are several well-known data visualization tools, accompanied by brief descriptions and instances of their utility:

- **Tableau:** Among the most widely used tools, Tableau is known for its user-friendly interface and capability to handle extensive datasets. It effectively manages big data through integration with database applications like MySQL, Hadoop, and Amazon AWS.
- **FusionCharts:** FusionCharts stands out for its convenience in graphic creation. Users can begin with templates and input their project-specific data, simplifying the visualization process.
- **Highcharts:** Highcharts boasts simplicity and is a favorite among many top global companies. Its user-friendly design ensures that specialized training is not necessary, and it places a strong emphasis on cross-browser support for wider accessibility.
- **Plotly:** Plotly shines when it comes to creating intricate visuals, thanks to its integration with programming languages like Python and R. However, users should exercise caution not to overcomplicate visualizations, as the primary goal is to convey information clearly and swiftly.
- **Sisense:** Sisense excels at consolidating data from various sources, even with large datasets. It simplifies the sharing of finalized products across departments, ensuring widespread access to essential information.
- **Shiny:** Shiny, an open package from RStudio, offers a web application framework for creating interactive web visualizations known as Shiny apps. Its user-friendly nature has made it popular among R users.
- **Microsoft Office:** Microsoft Office, with Excel as its data source, provides a variety of tools for creating simple yet well-designed graphs. Excel, in particular, is renowned for viewing raw data and offers graph creation tools.
- **Google Suite:** Google Suite, encompassing Docs, Sheets, and Slides, offers collaborative document editing and data management. Sheets, similar to Excel, holds raw data and provides straightforward graph creation tools that update dynamically with changing data.

<br>
Each of these tools possesses its unique strengths and limitations. The choice of a specific tool hinges on your particular data visualization requirements, your familiarity with the tool's interface, and the complexity of your dataset. The selection should align closely with your objectives and the specific insights you aim to extract from your data.

## Visual Encoding and Design Principles

Visual encoding involves representing data using visual elements like charts, graphs, or maps, which are more easily and swiftly processed by the human brain compared to text or numbers.

The significance of data visualization in conveying intricate insights concealed within data is paramount. This importance is growing as the audience for data visualizations continues to expand in tandem with the escalating volume of data. Presently, data visualizations are being consumed by individuals across diverse professional backgrounds. Consequently, ensuring accessibility and user-friendliness has become a pressing concern. While data scientists and analysts possess the expertise to extract pivotal insights from even intricate visualizations, this might not be the case for high-level business stakeholders or the average person.

<br>
Hence, the demand for effective data visualization has never been more pronounced. Effectively conveying data is an art, and yet, many data scientists find themselves trailing behind in terms of the design and aesthetic aspects of data visualization.

<br>
Listed below are some essential design principles for crafting visually appealing and impactful data visualizations that cater to a broad audience  (Koshy 2018).

### Melissa Anderson’s Principles of Design

The subsequent design principles for data visualization are sourced from Anderson's work in 2017.

- **Balance:** Achieving balance in design means ensuring that essential visual elements like colour, shape, texture, and negative space are distributed harmoniously. It's not about rigid symmetry on both sides of the visualization, but rather about even distribution of elements across the dashboard. It's crucial to consider non-data elements such as logos, titles, and captions, as they can influence the overall balance of the display.
- **Emphasis:** Emphasis involves directing the viewer's focus towards significant data by utilizing key visual elements. This principle is closely linked to the act of reading design principles. It entails being aware of what captures the viewer's attention in the artwork. When crafting data visualizations, it's vital to remain mindful of the central message and how the entire visualization guides or distracts the viewer's attention.
- **Movement:** Ideally, movement within a design should follow the natural reading pattern, starting from the top, moving horizontally, and then vertically. Movement can also be induced by employing complementary colours to guide the user's gaze across the page or through the use of animations.
- **Pattern:** Patterns are effective for presenting similar sets of data or datasets with equal values. Introducing disruptions in patterns can be a compelling way to pique the viewer's curiosity.
- **Repetition:** By repeating chart types, shapes, or colours, relationships between different datasets can be conveyed effectively.
- **Proportion:** Proportion plays a crucial role in indicating the importance of datasets and illustrating the actual numerical relationships. It can significantly enhance the viewer's understanding and experience. However, there is a risk of subconscious deception through proportion, as our brains tend to interpret data based on images. Hence, it's vital to accurately represent proportion in data visualization and remain critical of potential misuse.
- **Rhythm:** A well-designed rhythm is achieved when visual elements create a pleasing flow for the viewer's eye. Adjusting visual elements' arrangement can help achieve this when it's not naturally occurring.
- **Variety:** Variety in terms of colour, shape, and chart types captures and sustains the viewer's engagement with the data. Introducing variety can enhance information retention. However, excessive variety can lead to the oversight of critical details. When applied thoughtfully, variety complements balance and aids information recall, but overuse can result in visual clutter.
- **Unity:** Unity in design naturally emerges when all other design principles are effectively applied.

These principles serve as guidelines for creating visually appealing and impactful data visualizations  (Anderson 2017).

## Common mistake to avoid for data visualization

The objective of data visualization is to effectively convey information to the intended audience. Nevertheless, there are certain challenges to be mindful of when endeavouring to achieve this objective while creating visual representations of data.

<br>
The following highlights seven prevalent mistakes often made by Data Analysts when illustrating their discoveries in a visual manner (Ginsberg, 2022).

1. **Commencing with Excessive Complexity:** The allure of crafting highly detailed, real-time dashboards can be strong. However, rather than investing extensive time in the initial version, it's more prudent to undergo multiple short cycles of prototyping, testing, and refinement.
2. **Employing Unintelligible Metrics:** Dashboards should employ metrics or concepts that resonate with a broader audience. The use of esoteric jargon and metrics fails to effectively convey the intended message.
3. **Overloading the Dashboard with Extraneous Graphics and Confusing Widgets:** Dashboards should prioritize simplicity in visual presentation over flashiness or excessive design. Rapidly and clearly conveying the dashboard's primary message should take precedence, as clutter detracts from this objective.
4. **Waiting for Complex Technology and Extensive BI Deployment Projects:** Traditional business intelligence tool implementations often exceed their anticipated timeframes. Delaying for such projects to materialize can result in prolonged waits. Dashboard solutions entail repetitive, iterative processes with incremental improvements.
5. **Underestimating Time and Resources for Dashboard Creation and Maintenance:** Despite a dashboard typically occupying just one page or screen, assuming it will be quick and straightforward to create and maintain is unwise.
6. **Failure to Align Metrics with Goals:** Dashboards should not merely showcase departmental activities but should establish connections between departmental efforts and the organization's overarching goals and objectives.
7. **Utilizing Ineffective, Poorly Designed Graphs and Charts:** When designing graphs and charts for dashboards, meticulous attention is essential. Adhering to principles for creating effective data visualizations is crucial to prevent dashboards from featuring inadequately designed graphs and charts.

## Reference List

- Anderson, Melissa. (2017). Data Visualization and the 9 Fundamental Design Principles. iDashboard, ” <https://www.idashboards.com/blog/2017/07/26/data-visualization-and-the-9-fundamental-design-principles/>.
- Friedman, Vitaly. (2008). Data-Visualization-and-Infographics. Smashing Magazine. <https://www.smashingmagazine.com/2008/01/monday-inspiration-data-visualization-and-infographics/>.
- Ginsberg, C. (2022, January 7). _7 Common Mistakes to Avoid in Data Visualization_. Nobledesktop.com. <https://www.nobledesktop.com/classes-near-me/blog/most-common-data-visualization-mistakes>
- Kesav kalluri. (2020, August 14). _Importance, Purpose, and Benefit of Data Visualization Tools!_ Business Analytics Platform with Pre-Built Insights | SplashBI. <https://splashbi.com/importance-purpose-benefit-of-data-visualization-tools/>
- Kosara, Robert. (2016). Reflecting on the Design Criteria for Explanatory Visualizations. Tableau. <https://research.tableau.com/sites/default/files/Kosara-C4PGV-2016.pdf>.
- Koshy, Jacob. (2018). 8 Design Principles for Effective Data Visualization. <https://www.promptcloud.com/blog/design-principles-for-effective-data-visualization/>
- Lewis, Anna. (2012, December 6). 10 Best Or Worst Ways To Visualise Web Analytics Data - Online Behavior. Online Behavior. <https://online-behavior.com/analytics/data-visualization/>
- McCandless, David. 2016. International Number Ones. Information is Beautiful. <https://informationisbeautiful.net/2016/international-number-ones/>.
- Mekhatria, Mustapha. 2017. 5 Steps to Create an Effective Data Visualization. Highcards Blog. <https://www.highcharts.com/blog/post/5-steps-to-create-an-effective-data-visualization/>
- Mike YiMary Sapountzis. (2019). Essential Chart Types for Data Visualization. Chartio; Chartio. <https://chartio.com/learn/charts/essential-chart-types-for-data-visualization/>
- Michael Schermann. (2019, June 10). Chapter 2 Fundamentals | A Reader on Data Visualization. Github. <https://mschermann.github.io/data_viz_reader/fundamentals.html#data-visualization-in-business>
- David McCandless. (2012). The beauty of data visualization \[YouTube Video\]. TED-Ed. In YouTube. <https://www.youtube.com/watch?v=5Zg-C8AAIGg>
- Wilke, C. (Claus). (2019). Fundamentals of data visualization : a primer on making informative and compelling figures (First edition.). O’Reilly Media, Inc.