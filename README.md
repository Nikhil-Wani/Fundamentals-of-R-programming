# R-programming

"R is an interpreted computer programming language which was created by Ross Ihaka and Robert Gentleman at the University of Auckland, New Zealand." The R Development Core Team currently develops R. It is also a software environment used to analyze statistical information, graphical representation, reporting, and data modeling. R is the implementation of the S programming language, which is combined with lexical scoping semantics.

R not only allows us to do branching and looping but also allows to do modular programming using functions. R allows integration with the procedures written in the C, C++, .Net, Python, and FORTRAN languages to improve efficiency.

In the present era, R is one of the most important tool which is used by researchers, data analyst, statisticians, and marketers for retrieving, cleaning, analyzing, visualizing, and presenting data.

# Features of R programming

R is a domain-specific programming language which aims to do data analysis. It has some unique features which make it very powerful. The most important arguably being the notation of vectors. These vectors allow us to perform a complex operation on a set of values in a single command. There are the following features of R programming:

1. It is a simple and effective programming language which has been well developed.
2. It is data analysis software.
3. It is a well-designed, easy, and effective language which has the concepts of user-defined, looping, conditional, and various I/O facilities.
4. It has a consistent and incorporated set of tools which are used for data analysis.
5. For different types of calculation on arrays, lists and vectors, R contains a suite of operators.
6. It provides effective data handling and storage facility.
7.It is an open-source, powerful, and highly extensible software.
8. It provides highly extensible graphical techniques.
9. It allows us to perform multiple calculations using vectors.
10. R is an interpreted language.

# Pros

1. Open Source
An open-source language is a language on which we can work without any need for a license or a fee. R is an open-source language. We can contribute to the development of R by optimizing our packages, developing new ones, and resolving issues.

2. Platform Independent
R is a platform-independent language or cross-platform programming language which means its code can run on all operating systems. R enables programmers to develop software for several competing platforms by writing a program only once. R can run quite easily on Windows, Linux, and Mac.

3. Machine Learning Operations
R allows us to do various machine learning operations such as classification and regression. For this purpose, R provides various packages and features for developing the artificial neural network. R is used by the best data scientists in the world.

4. Exemplary support for data wrangling
R allows us to perform data wrangling. R provides packages such as dplyr, readr which are capable of transforming messy data into a structured form.

5. Quality plotting and graphing
R simplifies quality plotting and graphing. R libraries such as ggplot2 and plotly advocates for visually appealing and aesthetic graphs which set R apart from other programming languages.

6. The array of packages
R has a rich set of packages. R has over 10,000 packages in the CRAN repository which are constantly growing. R provides packages for data science and machine learning operations.

7. Statistics
R is mainly known as the language of statistics. It is the main reason why R is predominant than other programming languages for the development of statistical tools.

8. Continuously Growing
R is a constantly evolving programming language. Constantly evolving means when something evolves, it changes or develops over time, like our taste in music and clothes, which evolve as we get older. R is a state of the art which provides updates whenever any new feature is added.

# Cons

1. Data Handling
In R, objects are stored in physical memory. It is in contrast with other programming languages like Python. R utilizes more memory as compared to Python. It requires the entire data in one single place which is in the memory. It is not an ideal option when we deal with Big Data.

2. Basic Security
R lacks basic security. It is an essential part of most programming languages such as Python. Because of this, there are many restrictions with R as it cannot be embedded in a web-application.

3. Complicated Language
R is a very complicated language, and it has a steep learning curve. The people who don't have prior knowledge or programming experience may find it difficult to learn R.

4. Weak Origin
The main disadvantage of R is, it does not have support for dynamic or 3D graphics. The reason behind this is its origin. It shares its origin with a much older programming language "S."

5. Lesser Speed
R programming language is much slower than other programming languages such as MATLAB and Python. In comparison to other programming language, R packages are much slower.

In R, algorithms are spread across different packages. The programmers who have no prior knowledge of packages may find it difficult to implement algorithms.

# Install a New Package

In R, there are two techniques to add new R packages. The first technique is installing package directly from the CRAN directory, and the second one is to install it manually after downloading the package to our local system.

<b>Install directly from CRAN</b>

The following command is used to get the packages directly from CRAN webpage and install the package in the R environment. We may be prompted to choose the nearest mirror. Choose the one appropriate to our location.

install.packages("Package Name")  

The syntax of installing XML package is as follows:

install.packages("XML")  

<b>Install package manually</b>

To install a package manually, we first have to download it from https://cran.r-project.org/web/packages/available_packages_by_name.html. The required package will be saved as a .zip file in a suitable location in the local system.

Once the downloading has finished, we will use the following command:

install.packages(file_name_with_path, repos = NULL, type = "source")  
Install the package named "XML"

install.packages("C:\Desktop\graphics\xml2_1.2.2.zip", repos = NULL, type = "source")  
Load Package to Library
We cannot use the package in our code until it will not be loaded into the current R environment. We also need to load a package which is already installed previously but not available in the current environment.

There is the following command to load a package:

library("package Name", lib.loc = "path to library")  
Command to load the XML package

install.packages("C:\Desktop\graphics\xml2_1.2.2.zip", repos = NULL, type = "source")  

# Data types

1. Logical 	True, False 	It is a special data type for data with only two possible values which can be construed as true/false.

2. Numeric	12,32,112,5432	Decimal value is called numeric in R, and it is the default computational data type.

3. Integer	3L, 66L, 2346L	Here, L tells R to store the value as an integer.

4. Complex	Z=1+2i, t=7+3i	A complex value in R is defined as the pure imaginary value i.

5. Character	'a', '"good'", "TRUE", '35.4'	In R programming, a character is used to represent string values. We convert objects into character values with the help of a s.character() function.

6. Raw		A raw data type is used to holds raw bytes.

# R Functions

A set of statements which are organized together to perform a specific task is known as a function. R provides a series of in-built functions, and it allows the user to create their own functions. Functions are used to perform tasks in the modular approach.

Functions are used to avoid repeating the same task and to reduce complexity. To understand and maintain our code, we logically break it into smaller parts using the function. A function should be

1. Written to carry out a specified task.
2. May or may not have arguments
3. Contain a body in which our code is written.
4. May or may not return one or more output values.
"An R function is created by using the keyword function." 

There is the following syntax of R function:

<pre>
<code>
   func_name <- function(arg_1, arg_2, ...) {  
   Function body   
} 
 </code>
</pre>

<b>components of Functions</b>

There are four components of function, which are as follows:

1. Function Name

The function name is the actual name of the function. In R, the function is stored as an object with its name.

2. Arguments

In R, an argument is a placeholder. In function, arguments are optional means a function may or may not contain arguments, and these arguments can have default values also. We pass a value to the argument when a function is invoked.

3. Function Body

The function body contains a set of statements which defines what the function does.

4.Return value

It is the last expression in the function body which is to be evaluated.

<b>Function Types</b>

Similar to the other languages, R also has two types of function, i.e. Built-in Function and User-defined Function. In R, there are lots of built-in functions which we can directly call in the program without defining them. R also allows us to create our own functions.

1. Built-in function

The functions which are already created or defined in the programming framework are known as built-in functions. User doesn't need to create these types of functions, and these functions are built into an application. End-users can access these functions by simply calling it. R have different types of built-in functions such as seq(), mean(), max(), and sum(x) etc.

2. User-defined function

R allows us to create our own function in our program. A user defines a user-define function to fulfill the requirement of user. Once these functions are created, we can use these functions like in-built function.

Creating a function without an argument.  
<pre><code>
new.function <- function() {  
   for(i in 1:10) {  
      print(i^2)  
   }  
}     
new.function()  
</code></pre>

# Data Structures

Data structures are very important to understand. Data structure are the objects which we will manipulate in our day-to-day basis in R. Dealing with object conversions is the most common sources of despairs for beginners. We can say that everything in R is an object.

R has many data structures, which include:

1. Atomic vector
2. List
3. Array
4. Matrices
5. Data Frame
6. Factors

<b>Vectors</b>

A vector is the basic data structure in R, or we can say vectors are the most basic R data objects. There are six types of atomic vectors such as logical, integer, character, double, and raw. "A vector is a collection of elements which is most commonly of mode character, integer, logical or numeric" A vector can be one of the following two types:

1. Atomic vector
2. Lists

<b>List</b>

In R, the list is the container. Unlike an atomic vector, the list is not restricted to be a single mode. A list contains a mixture of data types. The list is also known as generic vectors because the element of the list can be of any type of R object. "A list is a special type of vector in which each element can be a different type."

We can create a list with the help of list() or as.list(). We can use vector() to create a required length empty list.

<b>Arrays</b>

There is another type of data objects which can store data in more than two dimensions known as arrays. "An array is a collection of a similar data type with contiguous memory allocation." Suppose, if we create an array of dimension (2, 3, 4) then it creates four rectangular matrices of two rows and three columns.

In R, an array is created with the help of array() function. This function takes a vector as an input and uses the value in the dim parameter to create an array.

<b>Matrices</b>

A matrix is an R object in which the elements are arranged in a two-dimensional rectangular layout. In the matrix, elements of the same atomic types are contained. For mathematical calculation, this can use a matrix containing the numeric element. A matrix is created with the help of the matrix() function in R.

Syntax

The basic syntax of creating a matrix is as follows:

<code>matrix(data, no_row, no_col, by_row, dim_name)</code>

<b>Data Frames</b>

A data frame is a two-dimensional array-like structure, or we can say it is a table in which each column contains the value of one variable, and row contains the set of value from each column.

There are the following characteristics of a data frame:

1. The column name will be non-empty.
2. The row names will be unique.
3. A data frame stored numeric, factor or character type data.
4. Each column will contain same number of data items.

<b>Factors</b>

Factors are also data objects that are used to categorize the data and store it as levels. Factors can store both strings and integers. Columns have a limited number of unique values so that factors are very useful in columns. It is very useful in data analysis for statistical modeling.

Factors are created with the help of factor() function by taking a vector as an input parameter.

# Data Visualization

In R, we can create visually appealing data visualizations by writing few lines of code. For this purpose, we use the diverse functionalities of R. Data visualization is an efficient technique for gaining insight about data through a visual medium. With the help of visualization techniques, a human can easily obtain information about hidden patterns in data that might be neglected.

By using the data visualization technique, we can work with large datasets to efficiently obtain key insights about it.

<b>Graphics</b>
   
Graphics play an important role in carrying out the important features of the data. Graphics are used to examine marginal distributions, relationships between variables, and summary of very large data. It is a very important complement for many statistical and computational techniques.

<b>Standard Graphics</b>

R standard graphics are available through package graphics, include several functions which provide statistical plots, like:

Scatterplots
Piecharts
Barplots etc.

We use the above graphs that are typically a single function call.

<b>Graphics Devices</b>

It is something where we can make a plot to appear. A graphics device is a window on your computer (screen device), a PDF file (file device), a Scalable Vector Graphics (SVG) file (file device), or a PNG or JPEG file (file device).

There are some of the following points which are essential to understand:

1. The functions of graphics devices produce output, which depends on the active graphics device.
2. A screen is the default and most frequently used device.
3. R graphical devices such as the PDF device, the JPEG device, etc. are used.
4. We just need to open the graphics output device which we want. Therefore, R takes care of producing the type of output which is required by the device.
5. For producing a certain plot on the screen or as a GIF R graphics file, the R code should exactly be the same. We only need to open the target output device before.
6. Several devices can be open at the same time, but there will be only one active device.

<b>Pie chart</b>

The Pie charts are created with the help of pie () function, which takes positive numbers as vector input. Additional parameters are used to control labels, colors, titles, etc.

There is the following syntax of the pie() function:
<code>pie(X, Labels, Radius, Main, Col, Clockwise)</code>

Here,
1. X is a vector that contains the numeric values used in the pie chart.
2. Labels are used to give the description to the slices.
3. Radius describes the radius of the pie chart.
4. Main describes the title of the chart.
5. Col defines the color palette.
6. Clockwise is a logical value that indicates the clockwise or anti-clockwise direction in which slices are drawn.

<b>Bar charts</b>

In R, we can create a bar chart to visualize the data in an efficient manner. For this purpose, R provides the barplot() function, which has the following syntax:
<code>barplot(h,x,y,main, names.arg,col)</code> 

<pre>S.
1.	      H	         A vector or matrix which contains numeric values used in the bar chart.
2.	      xlab	      A label for the x-axis.
3.	      ylab	      A label for the y-axis.
4.	      main	      A title of the bar chart.
5.	      names.arg	A vector of names that appear under each bar.
6.	      col	      It is used to give colors to the bars in the graph.
</pre>

<b>Histogram</b>

For creating a histogram, R provides hist() function, which takes a vector as an input and uses more parameters to add more functionality. There is the following syntax of hist() function:
<code>hist(v,main,xlab,ylab,xlim,ylim,breaks,col,border)</code>

Here,
<pre>
1.    	v	         It is a vector that contains numeric values.
2.	      main	      It indicates the title of the chart.
3.    	col	      It is used to set the color of the bars.
4.    	border   	It is used to set the border color of each bar.
5.    	xlab	      It is used to describe the x-axis.
6.	      ylab	      It is used to describe the y-axis.
7.	      xlim	      It is used to specify the range of values on the x-axis.
8.	      ylim	      It is used to specify the range of values on the y-axis.

<b>Line graph</b>

A line chart is used to connect a series of points by drawing line segments between them. Line charts are used in identifying the trends in data. For line graph construction, R provides plot() function, which has the following syntax:

<code>plot(v,type,col,xlab,ylab)  </code>

Here,

1.    	v	      It is a vector which contains the numeric values.
2.	      type	   This parameter takes the value ?I? to draw only the lines or ?p? to draw only the points and "o" to draw both lines and points.
3.	      xlab	   It is the label for the x-axis.
4.	      ylab	   It is the label for the y-axis.
5.	      main	   It is the title of the chart.
6.	      col	   It is used to give the color for both the points and lines

<b>Scatter plot</b>

The scatter plots are used to compare variables. A comparison between variables is required when we need to define how much one variable is affected by another variable. In a scatterplot, the data is represented as a collection of points. Each point on the scatterplot defines the values of the two variables. One variable is selected for the vertical axis and other for the horizontal axis. In R, there are two ways of creating scatterplot, i.e., using plot() function and using the ggplot2 package's functions.

There is the following syntax for creating scatterplot in R:
<code>plot(x, y, main, xlab, ylab, xlim, ylim, axes) </code>

Here,

1.	      x	         It is the dataset whose values are the horizontal coordinates.
2.	      y	         It is the dataset whose values are the vertical coordinates.
3.    	main	      It is the title of the graph.
4.	      xlab	      It is the label on the horizontal axis.
5.	      ylab	      It is the label on the vertical axis.
6.	      xlim	      It is the limits of the x values which is used for plotting.
7.    	ylim	      It is the limits of the values of y, which is used for plotting.
8.	      axes	      It indicates whether both axes should be drawn on the plot.

