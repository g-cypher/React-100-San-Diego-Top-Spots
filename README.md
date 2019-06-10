# React-100-San-Diego-Top-Spots

-Basic bootstrap for page header
-set local state that holds an object called topspots: with a value equal to an empty array
 which will then be populated by the JSON object
-use axios to send an axios GET request to the API holding the Top Spots JSON info.  Respond with the data and set the state
 of topspots: equal to the JSON data within the empty array
-Map through the array of objects now stored in the current state of topspots.  Invoke a function with topspot as a parameter, 
 basically saying : for each object(topspot) in the array of objects(topspots), set the value of "name", "description", "key",
 and "location" equal to each individual topspot object's values.   Pass these values as props to a child component below...
-Create a new folder called topspot.jsx, import React and create a FSC (functional stateless component) that will be the child 
of our main app.  This FSC will take in props as a parameter, and these props will have the values assigned by mapping through 
the JSON data.
-add a button that takes you to the correct location in Google Maps

