# UFO--Analysis
![image](https://user-images.githubusercontent.com/112978144/215654234-c9408d61-62f9-4aba-a0f2-a6c1a40a2855.png)

# OverView of the Project
In this challenge, a table is created to organize UFO data that is stored as a JavaScript array. The table have the ability to filter data according to assigned criteria and is created using JavaScript as a language tool. Filters are created to make this table fully dynamic,as it changed the table as HTML filtered, and then place the table into an HTML file for easy viewing.

Bootstrap is used to customize web page, and table is also equiped with several fully functional filters that work to interact with visualizations.
# Tools
HTML is filtered using JavaScript. 
There were two deliverables of this challenge. 
# Deliverable 1
Deliverable 1: Filter UFO sightings on multiple criteria
Using JavaScript and HTML in deliverable 1 we were assigned to modify the code in our index.html file to create more table filters. In addition to the date filter created in this module, we added filters for the city, state, country, and shape. HTML is filtered  and starter code file renamed as app.js.
![image](https://user-images.githubusercontent.com/112978144/215642781-f1fbe8f8-a64a-4972-b122-395b8d1060d5.png)
After filtering we got the following table
![image](https://user-images.githubusercontent.com/112978144/215643024-e8ca90cd-e4f6-4038-87dd-94bf1b307dbb.png)
In order to get the data in the column Using JavaScript,we were assign to replace the handleClick() function in our app.js file with a new function that saves the element, value, and id of the filter that was required to changed. Then, we create a new function to loop through and keep only the results that fullfil the criteria. 

# Steps Taken

 * First ufo_starterCode.js,  is renamed as app.js. 



* From the index.html file, the list (<li></li>) element that creates the button are removed.

* Four more list elements are created as city, state, country, and shape.Each element have the same "id" as the object properties in the data.js file.

* In Step 1 of the app.js file, an empty filters variable is created to keep track of all the elements that change when a search is entered. This variable is used in Step 5 to store the property “id” and the value that is entered from user input.

* Next, we write  a code for two functions whose names we were provided in the starter code, updateFilters() and filterTable().

* The updateFilters() function replaced handleClick() function and update the filters variable created in Step 1.
* The filterTable() function filtered the table data by the value that is entered for the "id" that has changed.
* For Step 2, located before the buildTable(tableData) function at the end of the starter code,we modified the event listener so that it detects a "change" on each input element and calls the updateFilters() function.

*In Step 3, we were provided the function, updateFilters(). to write code in Steps 4-5 to update the filters based on user input.

* In Step 4a,a variable is created that saves the element that was changed using d3.select(this).

* In Step 4b, a variable is created that saves the value of the changed element’s property.

* In Step 4c, a variable is created that saves the attribute of the changed element’s id.

* In Step 5,an if-else statement that checks if a value was changed by the user (variable from Step 4b).

* In Step 6, inside the updateFilters() function, the filterTable() function is called to be used in Step 7.

* The filterTable() function in Step 7, filter the table based on the user input and is stored in the filters variable.

* In Step 8,  a variable is created to filter data that hold the updated table data based on the user input.

* In Step 9, we loop through the filters object and store the data that matches the filter values in the variable created in Step 8.

* In Step 10, we rebuild the table with the filtered data by passing the variable created in Step 8.

# summary
In this challenge the main functions were to create filters, update filters and store filtered data. Variables are created to save changed elements and to save attributes of changed elements. FilterTable functions is used to filter table and finally a table is rebuild with a filtered data.
* DrawBack
One drawback of the new design is that the table we got is not in alphabetical order that is little confusing like if it appears in alphabetical order it might be helpful to go to the specific letter to find required result.
Suggestions
1: We can filter it as an alphabetical order to make it more easier to scroll to go to exact letter we need the data and to make it more fancier.
2: If time is called as well it can help a lot to make schedule accordingly for those who are interested to work or research on UFO'S.
