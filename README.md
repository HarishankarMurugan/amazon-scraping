# Amazon-Scraping
In this project, I used scrap the data from amazon India website. Before getting into it, we have to know what is Web Scraping. Web Scraping is nothing but the process of extracting the data from the website. And this information is collected and then exported into a format that is more useful for the user. Be it spreadsheet or an API.

•	So there is also an important thing to be known about web scraping. It is illegal when non publicly available data was extracted.
•	Now, We are going to extract some data from the amazon and then converting those data to the CSV file (Example into Microsoft Excel)
•	I was going to extract some data’s about Iphone which is available in Amazon India Website, like details about descrption, Price, Review count and Star rating out of 5 star. 




### Libraries

So three most important libraries are need for this web scrapping project

* csv 
* bs4
* selenium

### Starting up the Webdriver
A webdriver is a tool that allows you to automate interactions with a web browser, we enter what we want to search in amazon.

### Extract the collection.

And extract the entire code by using the html parser.

### Prototype the record.

•	Now we are testing for the first product of iPhone,
•	Like we are getting the data like description, url, price, rating, and review count.

### Generalize the pattern.
now making the code into simple snippet.

### Error Handling
We are just handling the error by just using try-except block, for the code which not extract no data.

### Getting next Page.

Until now we are only getting the data of the 1st page of the respective, but we have to get the complete data so now going through entire page till the end.

### Combining the complete code into a single code!

At last, we used to combine the entire code which we have tried into a single snippet and running the code. And also getting those data in csv file.


# Screenshots!
#### The browser in which process going on!
![Screenshot 2023-04-27 145611](https://user-images.githubusercontent.com/124061758/234833341-8394ff90-656f-4832-8877-c3d00775bd8b.png)

#### The Save file in the respective folder.
![Screenshot 2023-04-27 145855](https://user-images.githubusercontent.com/124061758/234833626-e456878b-80d4-45e9-afd9-3fc2decaaab4.png)

#### Final ouput in CSV File.
![Screenshot 2023-04-27 150117](https://user-images.githubusercontent.com/124061758/234833676-03737480-ec3f-499a-babe-764d69bf66c4.png)
