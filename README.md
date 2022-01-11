# Incubyte Assignment
## Problem Statement

We maintain all customers in one database. There are heaps of customers with user cards to my 
hospital. So, I decided to split up the customers based on the country and load them into 
corresponding country tables.
To pull the customers as per Country, my developers should know what are all the places the 
Customer Data is available. So, the data extracting will be done by our Source System. They will pull the all the relevant customer data and will give us a Data file.

## Libraries Used

- Pandas
- MySQL Connector

## Installing the Libraries

 Installing pandas

```sh
$ pip install pandas
```

Using mysql connector

```sh
$ pip install mysql-connector-python
```

Output

![](https://github.com/sayali1998/Incubyte-Assignment/blob/main/FilteredUsingCountryName.PNG)


![](https://github.com/sayali1998/Incubyte-Assignment/blob/main/Intermediate%20Data.PNG)




