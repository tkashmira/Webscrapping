# Webscrapping

I will be using Python and several Python libraries. Installed some libraries.

```
The wikipedia webpage https://en.wikipedia.org/wiki/List_of_largest_banks provides information about largest banks in the world by various parameters. 
Scrape the data from the table 'By market capitalization' and store it in a JSON file.
```
```
Used the contents and beautiful soup loaded the data from the By market capitalization table into a pandas dataframe. 
The dataframe should have the country Name and Market Cap (US$ Billion) as column names. Display the first five rows using head.
```
```
Loaded the data from the By market capitalization table into a pandas dataframe. 
The dataframe should have the country Name and Market Cap (US$ Billion) as column names. 
Used the empty dataframe data and the given loop extract the necessary data from each row and append it to the empty dataframe.
```
```
Usually you will Load the pandas dataframe created above into a JSON named bank_market_cap.json using the to_json() function.
This time the data will be sent to another team who will split the data file into two files and inspect it.
```
