### URLSearchParams
* Per MDN web docs, the URLSearchParams interface defines utility methods to work with the query string of a URL
* the constructor:

* an object implementing URLSearchParams can be used in a for..of structure
    ```
    for (const [key,value] of mySearchParams){}
    for (const [key,value] of mySearchParams.entries()){}
    ```
* the docs list tons of methods used on the URLSeachParams object

#### URLSearchParams.toString()
* the toString() method of URLSearchParams returns a query string suitable for use in a URL
* includes query string without question mark( this is different from window.location.search which includes the question mark)
* returns an empty string if no search params have been set
* not much information on the application here...

#### Location
* the location interface representes the location (URL) of the object its linked to 
* Document and Window interface have a Location 
* for example, Window.location
* basically its the URL. for example http://example.org:8888/foo/bar?q=baz#bang
* Location.reload() reloads the current location
#### hashchange event
* fired with the fragment identifier of the URL has changed (the part of the URL beginning with and following the # symbol)
* can be used in an event listener
*
```
function locationHashChanged() {
  if (location.hash === '#cool-feature') {
    console.log("You're visiting a cool feature!");
  }
}

window.onhashchange = locationHashChanged;
```

