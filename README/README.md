# JavaScript-Study from w3schools.com

JavaScript is one of the 3 languages all web developers must learn:

   1. HTML to define the content of web pages

   2. CSS to specify the layout of web pages

   3. JavaScript to program the behavior of web pages

### getElementById

It takes an html element with ID "demo" and changes it to Hello JavaScript.

```
document.getElementById("demo").innerHTML = "Hello JavaScript";
```

* JavaScript accepts both double and single quotes

```
<button onclick="document.getElementById('myImage').src='pic_bulbon.gif'">Turn on the light</button>
```

* JavaScript changes the value of the src (source) attribute of an <img> tag
* JavaScript Can Hide HTML Elements
* JavaScript Can Show HTML Elements



#### In HTML, JavaScript code is inserted between <script> and </script> tags.


#### JavaScript can "display" data in different ways:

* Writing into an HTML element, using innerHTML.
* Writing into the HTML output using document.write().
* Writing into an alert box, using window.alert().
* Writing into the browser console, using console.log().