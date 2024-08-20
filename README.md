# nosql-challenge
Module 12 Challenge

For this challenge, data was imported from the establishments.json file to evaluate various food establishments across the United Kingdom and to give a proper food hygiene rating. The database used is uk_food and the collection is 'establishments', which was assigned a variable in preparation for use. From here, queries were established to gather the necessary data, such as the rating values given to each establishment. For this code, regex was employed, then the aggregation method was used to see which establishments were scored within the top ten authority areas. 

Using the count_documents check and an update_many query, fields were converted from strings to decimals in order to make the rating value an integer. During the analysis, count_documents was used to get the correct number of documents, then pprint was used to print the resutls. Finally, the result was converted to a Pandas DataFrame to display the first 10 rows.

Resources:
ChatGPT was used for some of the regex commands, as well for implementing the find_one command.
