GiphysWorls is a single page app having all kind of GIFs a user can search for.
When a user user lands on the page, he would be able to see the trending Gif images from Giphy that are fetched from the following API in JSON format: 
https://developers.giphy.com/docs/#operation--gifs-trending-get.
This app also include an input field at the top which accepts a search word. A user can GIFs according to his requirement. Also, a return button to return to the default GIFs.
conveniently, you can directly open this app on HTML Browser.

var xhttp = new XMLHttpRequest(): creates an XMLHttpRequest object

xhttp.onreadystatechange = function(): The onreadystatechange property specifies a function to be executed every time the status of the XMLHttpRequest object change.
 if (this.readyState == 4 && this.status == 200): Here, when readyState property is 4 and the status property is 200, the response is ready:
JSON.parse(this.responseText): The responseText property returns a DOMString that contains the response to the request as text in the form of Json, and then converstion of the same text into Json format.
In the next 'for' loop, the giphs extracted from the API are displayed using HTML. 
document.getElementById("demo").innerHTML = html

Whereas, Function reset is called to to reset all form fields to their default values.
Function SearchGif is called to search for the specific gif according to user's demand.

