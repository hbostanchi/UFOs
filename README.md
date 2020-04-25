# UFOs
## Modual Overview:
In this module, we worked with VS code to built a table with javascript.  
We organized the webpage with Bootstrap to customized and equip the table with several fully functional filters to allow users to interact with visualizations.we built a navbar with html for the header and then add on with the title and paragraphs and tables.We also created filters to respond users input and make it more dynamic, so they interact with the filters. And finally we css to customize the color and add image and make it how we like.
![webeimage](https://github.com/hbostanchi/UFOs/blob/master/static/images/webpage.png)
## Resources:
- Software: VS Code
- Data Source: data.js

## Objectives
Explain the strengths and weaknesses of JavaScript “standard” and JavaScript version ES6+.
Describe JavaScript syntax and ideal use cases.
Build and deploy JavaScript functions, including built-in functions.
Convert JavaScript functions to arrow functions.
Build and deploy forEach (JavaScript for loop).
Create, populate, and dynamically filter a table using JavaScript and HTML.

## Modual Summery:
### JavaScript:
JavaScript is a well-established coding language that was designed to enhance HTML. It’s the backbone of many popular visualization libraries, such as Plotly, and is often used to create custom dashboards. JavaScript also provides a high level of customization: the dashboards built to deliver visual data, such as maps or graphs, can be as simple or complex as needed.

JavaScript is one of the powerhouse languages out in the wild today. While its strength is in creating visually appealing and dynamic content, it is starting to grow into other fields as well. Tensorflow, a popular machine learning tool, even has its own JavaScript library now.

### ES6:
ECMAScript, also referred to as “ES,” is a scripting language designed to help standardize JavaScript. This means that ES provides guidelines and rules for JavaScript to follow, such as how a function should be created to run correctly, also known as the proper syntax.

Because ES has provided standardization for JavaScript, it also brings updates to the language. There are updates to every major coding language that fix bugs, update code, and provide overall quality of life improvements for the developers. ES6 is no exception!

There have been many updates to ES over the years, though the sixth update was a major one. You’ll probably see “ES6+” mentioned out in the wild pretty often; this is a reference to the “big” update (ES6) as well as the later ones. It’s also commonly known as “ES2015” or “ECMAScript 2015.”

- developers didn't have to wait for new technology to catch up. Normally, that would be waiting on the user to update their web browser to use the product.

- ES6 is backward compatible. The developer can write in any version of ES and the program will run.

- Arrow functions. Abbreviated syntax that made object-oriented code easier to write.

The standard set in writing JavaScript code is to keep it consistent. It allows for code clarity. As a developer the readability of our code is the most important thing. It will make projects easier when collaborating or bugs faster to address.

Our [app.js](https://github.com/hbostanchi/UFOs/blob/master/static/js/app.js)

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
