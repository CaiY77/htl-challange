1. What is the difference between HTTP and HTTPS?
### Although they are very alike, the main difference lies in security. HTTPS includes security protocols.
2. What is the difference between HTTP GET and POST?
### GET pulls data from database while POST sends data to database
3. What is the difference between the HTTP 2xx status codes and 4xx status codes?
### 200s codes stand for request that is successfully received, accepted, understood where as 400s codes usually stands for errors and blockers
4. What is ajax (conceptually, what does it do)? Describe a situation where it is useful.
### Ajax uses javascript and XML. Very similar to what react.js does. Allows browsers to access parts of the server side. This is good in cases you wish to dynamically render stuff from the database or overall faster front-end
5. What is responsive design?
### Design that supports multiple platforms/medias with different screen sizes (iPhone, android, tablet...etc)

6. What is the difference between these 3 CSS rules?
### div applies to all <div> elements
### #div applies to the id name "div"
### .div applies to the class name "div"

```HTML
div {background:#fff;}
#div {background:#fff;}
.div {background:#fff;}
```
7. What is the difference between these 2 uses of the <script> tag?
<script src=”http://example.com/whatever.js”></script>
<script>var whatever = true</script>
### The script with an src links to an external js page while the second is js directly on html page.

8. What is the difference between these two javascript snippets?
```javascript
var x = function() {
return 1+1;
}();
var y = function() {
return 1+1;
};
```
### Both are function expressions just with different names, function expressions are invoked by their name.
