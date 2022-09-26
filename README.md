# UFOs- The UFO sighting was design with the index.html, consisting of the Head, Body and the Class.
The Head consist of the meta- this incorporate the charset, http and the name. this component makes up the background
the title gives the intented purpose of the finding 
The link consist of the stylesheet of the webpage 
The Body of the page make use of class, this contain the color, size, body discription of the webpage with the visualization of the design
The visualization will run with app.js contain the code, and the data.js, which populate the webpage.
From data.js const tableData was use to get the data, var tbody = d3.select for the table ref. function buildTable use to clear the table for tbody.html
Loop function through the object and append function use to add data to the cell and row.
A variable was created to track of the filters as an object
ChangedElem set to d3.select
Function updateFilters() for update in the table with the filterid set to changedElem.property(value).
