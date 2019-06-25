# JAVA_Excel_Parsing
POI Library by Apache

## Before start...
I had a Excel file that has to be upload to my database. Each cells were mixed by  imformations, blanks, and formulas. And I had to parse ExcelFile in forms like\ "1","apple","red","","Round"...etc.\ So first, I decided to use Java and I found POI Library.

## What Library?
There are some Library to use when we handle Excel. Most of people used POI Library. Because there are version of Excel we could use. Most of people use higher version Excel, So we have to think of Excel version. I have 2007 version, so I used POI Library. 

### POI Library
- Download here : https://poi.apache.org/

![POI](https://user-images.githubusercontent.com/32008149/60108008-dffe6c80-97a2-11e9-963f-7d87a7cf7d5a.PNG)

- 
![POI2](https://user-images.githubusercontent.com/32008149/60109091-afb7cd80-97a4-11e9-99f9-56b4ec8a9a40.PNG)

- In Maven, you could put dependency to POM.xml (Beacareful for the Version)\
You can find Here: 
![POI3](https://user-images.githubusercontent.com/32008149/60109311-1937dc00-97a5-11e9-8ef5-db98598edaad.PNG)

Now What I have to do is importing csv file to my DataBase.\
But there were serious Problem in imporing to DataBase.


## CSV
I had problem with importing csv file to Database. My program made xlsx file and I convert to 