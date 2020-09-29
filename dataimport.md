# DATA IMPORTATION

## Data table

A data table is a range of cells in which you can change values in some in some of the cells and come up with different answers to a problem.


## Data types

+ **Categorical**: represent characteristics such as a person’s gender, marital status, hometown, or the types of movies they like.
+ **Numeric**: numerical data is a data type expressed in numbers, rather than natural language description.
+ **Boolean**: it has one of two possible values (usually denoted true and false) which is intended to represent the two truth values of logic and Boolean algebra. 
+ **Dates**: it stores the calendar date as values.
+ **Strings**: it's traditionally a sequence of characters, either as a literal constant or as some kind of variable.


## Data formats

- **.csv**: a Comma Separated Values (CSV) file is a plain text file that contains a list of data.
- **.json**: a JavaScript Object Notation (JSON) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate.
- **.xml**: is an Extensible Markup Language (XML) data file. It is formatted much like an .HTML document, but uses custom tags to define objects and the data within each object. 
- **.xls**: an XLS file is a spreadsheet file created by Microsoft Excel or another spreadsheet program that contains one or more worksheets, which store and display data in a table format.


## Local vs remote repositories

+ **URL**: a URL uniquely describes the location of a resource on the Internet. 
+ **APIS**: is a data access layer that defines a generic representation of a data store. 


## Secure Data transfer protocols

It is used to safeguard proprietary and personal data in transit and at rest. Most secure file sharing methods use standard protocols, including:

+ *Secure File Transfer Protocol (SFTP)*: encrypted network protocol that can enable a remote login to operate over a network that lacks security.
+ *File Transfer Protocol – Secure (FTPS)*: offers encryption and uses an application layer wrapper, known as Secure Sockets Layer (SSL) to enable secure and private communications across a network.
+ *Hypertext Transfer Protocol – Secure (HTTPS)*: secures websites when users are providing sensitive information like credit card numbers or other personal information. 
+ *Applicability Statement 2 (AS2)*: facilitates the ability to exchange AS2 EDI messages and other types of data over the HTTP or HTTPS protocol.


## Procedures for Data importing

+ *From an .csv:* 
```py
mport pandas as pd
mydata= pd.read_csv("C:\\Users\\mariosolven\\Desktop\\file1.csv")
```

+ *From an .txt*:
```py
import pandas as pd
mydata = pd.read_csv("C:\\Users\\mariosolven\\Documents\\example2.txt"")
```

+ *From an URL*:
```py
import pandas as pd
mydata = pd.read_csv("http://fifa.com/champions_league/90s_decade_winners.csv")
```


