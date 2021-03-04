# boolean flag

```js
//one way to track if we find a match 
//is to use a boolean 'flag'
let   targetFound   = false;


html += "<ul>";
//loop through all items in array
students.forEach(function( oneStudent ){    
    if( targetName === oneStudent){
        //if we find a match, remember this
        //by changing the value of the boolean 'flag'
        targetFound = true;
        //display a special styled list item
        html += `<li style='background-color:yellow'>${oneStudent} <-- target name found!</li>`;   
    }else{
        //otherwise display a normal list item
        html += `<li>${oneStudent}</li>`;
    }
});
html += "</ul>";

/*
we can use the boolean flag to 
determine if a match was found
*/
html += "<h3>Using a boolean flag to search the array...</h3>";
if(targetFound){
    html += "<p>Target name was found in the list (using a boolean flag)</p>";
}else{
    html += "<p>Target name was NOT found in the list (using a boolean flag)</p>";
}
```