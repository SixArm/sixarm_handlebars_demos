# Handlebars Demo 2:<br>Get JSON data with AJAX

This demo uses the jQuery method `.getJSON()` with AJAX to request the data.

The data is in the local file `song.json`. In a production application, the data would typically be on a server with a URL that starts with `http` or `https`.

Caution: if you view this demo in the Chrome browser, this demo will not work. This is because Chrome blocks requests for local files. The solution is to use a different browser.

Advice: if you view this demo in Firefox, the console may show an error line that says "not well-formed". This is because Firefox expects the JSON file to have a MIME type. You can ignore this. In a production application, the data would have the correct MIME type which is `application/json`. 



