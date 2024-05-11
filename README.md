# ITSpecialist-DataAnalytics3
Data Visualization is the art and science of describing data and information using visual elements such as graphs, diagrams and maps to facilitate understanding, analysis and communication. The main goal is to transform complex data into a picture that is easier to understand and use to identify patterns, trends and relationships within it.

## DATA VISUALIZATION 

Data visualization is the representation of data through the use of common graphics, such as charts, plots, infographics, and even animations. These visual displays of information communicate complex data relationships and data-driven insights in a way that is easy to understand.

Matplotlib and Seaborn are Python libraries that are used for data visualization. They have built-in modules for plotting different graphs. While Matplotlib is used to embed graphs into applications, Seaborn is primarily used for statistical graphs.

## Basic Visualization

1. Bar Chart Vertical
   Compare among categories, few categories. Can be used over time
2. Bar Chart Horizontal
   Has a long item label. Compare among categories. Used for many categories
3. Line Chart
   Compare over time, one category
4. Stacked Bar Chart
   Show components in a category, that can be used over time(a few periods). Relative and absolute differences matter.
5. Stacked 100% Bar Chart
   Show components in a category. Composition in percentage, focus contribution on each component. Can be used over time (a few periods) and only relative differences matter.
6. Pie Chart
   Static Composition, Useful for less than 5 categories. A simple share of the total
7. TreeMap
   Static Composition, accumulation to total. Absolute difference matters

Data Visualization Using Python
Python offers several plotting libraries namely Matplotlib and Seaborn for data visualization.

### Matplotlib
1. It used for basic graph plotting
2. It mainly works with dataset and array
3. Matplotlib acts productively with data arrays and frame
4. Matplotlib is more customizable and pairs well with Pandas and Numpy
   
### Seaborn
1. It mainly used for statistics and complex visualization
2. It works with the entire dataset
3. More organized and functional than Matplotlib, the dataset as a solitary unit
4. Seaborn has more themes and statistical analysis.

### Creating variables
Creating two variables to display a chart

<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/f0ffefae-a610-423d-94bb-1e51773fadf2" /></div>

### Displaying a chart from the previously created variables  

<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/4c25d564-b143-4a9a-b237-9372e9dbfeb6" /></div>

### Creating labels
Adding one variable for the Y-axis, still with the same category, which is fruits

<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/362af18e-b845-4f4f-b10b-03957bc32d4c" /></div>

Displaying a chart for the quantity of harvested grapes and kiwis in the specified year. Then, adding title labels to the X and Y axes.

<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/c6ecb21e-ceb4-464a-98e7-f62e51a3211e" /></div>

### Creating tittle and legend
Adding a title to the graph and a legend to indicate the graph based on color (Blue for grapes and Orange for kiwi)

<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/44bc2e19-e15a-4812-906f-84f0f1fc48b6" /></div>

### Creating grid
An easy way to make your charts look beautiful is to use some default styles from the Seaborn library. These can be applied globally using the sns.set_style function.

#### White Grid 
<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/cedf9977-ac30-4c0d-bdd2-fe6916bcf506" /></div>

The syntax above is used to create a graph showing the yields of grapes and kiwi over the years. It sets the X-axis label as 'Year', the Y-axis label as 'Yield (tons per hectare)', and the title of the graph as 'Crop Yields in Kanto'. A legend is added to distinguish between the lines representing grapes and kiwi, with 'grapes' represented by circles (marker='o') and 'kiwi' represented by crosses (marker='x')

#### Black Grid 
<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/e1f82442-ebad-4335-a446-d47c809d5056" /></div>

### Creating a Bar Chart
Creating a bar chart showing the grape yields from year to year in Bandung

<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/243033df-9eab-409f-a5b6-eceed214e168" /></div>

### Creating a Stacked Bar Chart
Creating a stacked bar chart showing the grape and kiwi yields from year to year in Bandung. Grapes are represented by the first bar chart, while kiwi is represented by the second bar chart. The argument bottom=grapes sets the kiwi bar chart to start from the grape yields, thereby showing the comparison between the two yields for each year

<div align="center"><img src="https://github.com/fakhirahazhar/ITSpecialist-DataAnalytics3/assets/165735471/a8f2e907-b961-4195-8b69-8f9181987bb0" /></div>
