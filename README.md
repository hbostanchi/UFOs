# UFOs
## Modual Overview:
In this module, we worked with VS code to built a table with javascript.  
We organized the webpage with Bootstrap to customized the look of it.we built a navbar with html for the header and then add on with the title and paragraphs and tables.We also created filters to respond users input and make it more dynamic, so they interact with the filters. And finally we css to customize the color and add image and make it how we like.
![webeimage](https://github.com/hbostanchi/UFOs/blob/master/static/images/webpage.png)
## Resources:
Software: VS Code
Data Source: data.js

## Challenge Summary:
Create, update, and deploy JavaScript functions to provide additional table filters.
Update and deploy forEach (for loop) to loop through the filters and update them with user input.
Update and populate the dynamic filters and table using JavaScript and HTML.

## Challenge instructions:
Include five total filters in the table:

1. Date
2. City
3. State
4. Country
5. Shape

To create these additional filters, keep the following points in mind:

- You will need to create a new function that will replace your handleClick(); function. This function saves the element, value, and the id of the filter that was changed.
Create an if-else statement to add filter data from input, or clear the filter if no input data exists.
- Additionally, create a function named filterTable(); that will perform the following actions:
Set the filtered data to the table.
Loop through all of the filters and keep any data that matches the filter values.
Rebuild the table by calling the buildTable(); function created earlier.
- Finally, using d3.selectAll();, attach an event listener to pick up changes that are made to each filter.

![challengeimage](https://github.com/hbostanchi/UFOs/blob/master/static/images/challengefilters.png)
