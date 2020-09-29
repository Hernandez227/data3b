# *Erick Hernández Data 3B*

##Data Types:  categorical, numeric, boolean, dates and strings.
####*A data type or simply type is an attribute of data which tells the compiler or interpreter how the programmer intends to use the data.*

###*Categorical data type
Categorical data is the analysis of data where the response variable has been grouped into a set of mutually exclusive ordered (such as age group) or unordered (such as eye color) categories.

###*Numeric data type
Numerical data is a data type expressed in numbers, rather than natural language description. Sometimes called quantitative data,numerical data is always collected in number form.

###*Boolean data type
Is a data type that has one of two possible values (usually denoted true and false) which is intended to represent the two truth values of logic and Boolean algebra.

###*Dates data type

The DATE data type stores the calendar date

###*String data type
Used in programming, such as an integer and floating point unit, but is used to represent text rather than numbers.

##The common data formats: csv, json, xml y xls.

+ __CVS:__  A comma-separated values file is a delimited text file that uses a comma to separate values. Each line of the file is a data record. Each record consists of one or more fields, separated by commas.


+ __JSON:__ JSON stands for JavaScript Object Notation. JSON is a lightweight format for storing and transporting data. JSON is often used when data is sent from a server to a web page.    


+ __XML__: Extensible Markup Language is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable.


+ __XLS:__ XLS files are Microsoft Excel's workbook files in use between 97-2003. Later Excel versions use the XLSX extension. XLS and XLSX file formats contain all the information from the worksheets in a workbook, including formatting, charts, images, formulas, etc.

##Differentiate between local and remote repositories

####*Understanding the difference between a Local Server and a Remote server is very important. If you are referring to a Local Server, this means that you have a server setup on your current machine. When the server is Remote, this just means that it is on another computer*

+ __URL:__ A Uniform Resource Locator, colloquially termed a web address, is a reference to a web resource that specifies its location on a computer network and a mechanism for retrieving it. A URL is a specific type of Uniform Resource Identifier, although many people use the two terms interchangeably

+ __APIS:__ An application programming interface is a computing interface which defines interactions between multiple software intermediaries. It defines the kinds of calls or requests that can be made, how to make them, the data formats that should be used, the conventions to follow, etc.

##The secure data transfer protocols.
__*The secure transmission refers to the transfer of data such as confidential or proprietary information over a secure channel. Many secure transmission methods require a type of encryption. Only File Transfer Protocol (FTP) and File Transfer Protocol SSL (FTPS) are used for transferring files, and of the two FTPS is the only secure, encrypted protocol.*__

##The procedures for data importing
__*The import and export of data is the automated or semi-automated input and output of data sets between different software applications. It involves "translating" from the format used in one application into that used by another, where such translation is accomplished automatically via machine processes, such as transcoding, data transformation, and others. True exports of data often contain data in raw formats otherwise unreadable to end-users without the user interface that was designed to render it.*__

###Example: Importing a Microsoft Access File

This example imports a Microsoft Access table called CUSTOMERS and from it creates a permanent SAS data set named SASUSER.CUST. The MS Access table has user-level security and, therefore, you need to specify the following statements: PWD=, UID=, and WGDB=. This example is repeated from the SAS Procedures Guide; see it for the following example's output and SAS log. 

	proc import table="customers" out=sasuser.cust dbms=access;
            uid="thomas";
            pwd="rocket";
            database="c:\hrdiv\east.mdb";
            wgdb="c:\winnt\system32\security.mdb";
	proc print data=sasuser.cust;
	run;

##Data characteristics: raw and clean.

+ __Raw data:__ Is data that has not been processed for use. A distinction is sometimes made between data and information to the effect that information is the end product of data processing. Raw data that has undergone processing is sometimes referred to as cooked data.

+ __Clean data:__  Is the process of detecting and correcting (or removing) corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data.

##Statistical techniques of the exploratory data analysis

+ __Histogram:__  A histogram is a plot that lets you discover, and show, the underlying frequency distribution (shape) of a set of continuous data. This allows the inspection of the data for its underlying distribution (e.g., normal distribution), outliers, skewness, etc.

+ __Scatter Analysis:__ Is used when you need to compare two data sets against each other to see if there is a relationship. Scatter plots are a way of visualizing the relationship; by plotting the data points you get a scattering of points on a graph.

+ __Univariate Analysis:__ Is the simplest form of analyzing data. “Uni” means “one”, so in other words your data has only one variable. It doesn't deal with causes or relationships (unlike regression ) and it's major purpose is to describe; It takes data, summarizes that data and finds patterns in the data.













