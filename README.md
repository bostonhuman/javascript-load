# Javascript Load
The load event is commonly used to trigger scripts that access the contents of the page. In this example, a function called setup() gives focus to the text input when the page has loaded. The event is automatically raised by the window object when a page has finished loading the HTML and all of its resources: images, CSS, scripts (even third party content.) The setup() function would not work before the page has loaded because it relies on finding the element whose id attribute has a value of username, in order to give it focus.

## Components that make the app run
* Note that the event listener is attached to the window object nothe document object as this can cause cross-browser campatibility issues.
* 
