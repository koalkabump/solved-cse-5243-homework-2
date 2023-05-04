Download Link: https://assignmentchef.com/product/solved-cse-5243-homework-2
<br>
<strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Objective</strong><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">: In this lab, you will work with the </span><strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Wine_quality</strong><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;"> dataset. You should work through each of the sections listed below and answer the questions or perform the analysis as specified. The answers to these questions should be provided either in a report format or within a Jupyter Notebook. Your programming and analysis work should be done in R or Python. Unless specifically stated, you may use off-the-shelf packages. </span>

<strong>Dataset Details</strong>: The wine_quality dataset can be found at the following URL:  <em>https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv  </em>This homework uses the <em>winequality-red.csv</em> dataset.

<strong>Data Preprocessing Tasks: </strong>Before you do any of the analysis below, execute the following tasks:

<ol>

 <li>Create a binary class variable according to the following rule:                   quality &lt;= 5 —&gt; class = “Low”, quality &gt; 5 —&gt; class = “High”</li>

 <li>You will need to remove the <em>quality </em>attribute after you create the class label. I will refer to this new variable as <strong>class</strong>.</li>

</ol>

<strong>Part 1: Business Understanding</strong> (5%): Similar to what you did in homework #1, in this section, you should create a section of your report that provides a brief overview of the data. Some questions you should consider are: Where did the data come from? What do the rows represent? Why and how was the data collected?  What types of questions might you be able to analyze with this data?

<strong>Part 2: Data Understanding</strong> (25%): Perform exploratory data analysis of the dataset by looking at individual attributes and/or combinations of attributes. You should focus on identifying and describing interesting observations and insights that you might uncover from the data. Use the appropriate data visualization and statistical methods to analyze the data.

In addition, your report should answer the following questions (for each question, be sure to justify your response with data, visualizations or statistics as well as an explanation):

<ul>

 <li>Are there any outliers in the data?</li>

 <li>Are any of the independent variables redundant relative to each other?</li>

 <li>Which attribute has the <em>strongest</em> relationship to the class label? 4) Which attribute has the <em>weakest</em> relationship to the class label?</li>

</ul>

<strong>Part 3: Data Transformations</strong> (20%): In this section, you will perform a number of attribute transformations and evaluate the impact of these transformations.

<ul>

 <li>Perform <em>equal interval width discretization</em> (into 10 bins) for the attribute <em>sulfur.dioxide. </em>What do you notice about the result, and do you think this discretization is effective?</li>

 <li>Perform <em>equal frequency discretization</em> (into 10 bins) for the attribute <em>sulfur.dioxide. </em>What do you notice, and how does this compare to the equal interval width discretization?</li>

 <li>Perform a log transformation of the attribute <em>alcohol</em>. Compare the original variable with the transformation; what observations do you have?</li>

 <li>Choose one <em>supervised discretization method</em> (e.g., the method makes use of the class label to more intelligently decide how to discretize a continuous attribute) to apply to the data. You can use an off-the-shelf R or Python package to do this (again, make sure that the functions you choose are appropriate for the given data), or you can code your own custom function. Describe the package that you used and any settings that you chose. Apply this discretization method to the <em>sulfur.dioxide </em>attribute, and compare this discretization to the equal interval width and equal frequency discretization methods performed above.</li>

 <li>Perform both the <em>standardization</em> and <em>normalization</em> transformations for the attribute <em>sulfur.dioxide </em>as well as one other attribute of your choice. Analyze the outcome of these transformations.</li>

</ul>

<h1>Part 4: Principal Component Analysis (20%)</h1>

Using the 11 remaining continuous features (and excluding the class), use an off-theshelf package (in Python or R) to perform a Principal Component Analysis of the data.  1) Briefly discuss and explain the package that you used and the parameters you set

(if any).

<ul>

 <li>Briefly present the results of the analysis and discuss your observations.</li>

 <li>Provide the a table with the eigenvalues and the matrix U (with the eigenvectors).</li>

 <li>How many principle components are needed to capture 95% of the variation in the original data?</li>

 <li>Plot the scatterplot for the transformed data in two dimensions.</li>

</ul>

In addition to working through the analysis in each section outlined above, your <strong>30% of your grade will be based on the overall readability and organization of your report. </strong>Is your report well organized and does the presentation flow in a logical manner? Are there grammar and spelling mistakes? Do the charts/graphs relate to the text?

<strong>Collaboration: </strong>For this assignment, you should work as an individual. You may informally discuss ideas with classmates, but your work should be your own.

<strong>What you need to turn in to Carmen: </strong>

1)      Program (if applicable) 2)         Report

<strong>How to hand in your work: </strong>

Please do this work in either Python or R. All the related files (code and/or report) except for the data will be tarred in a *.zip file or *.tgz file, and submitted via Carmen.

Use this naming convention: “Project2_Surnames_DotNumber.zip” or

“Project2_Surnames_DotNumber.tgz.”  The submitted file should be less than 5MB.