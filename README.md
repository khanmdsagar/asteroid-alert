# asteroid-alert
It's an alert library build with JavaScript. You can replace your traditional JavaScript alert, confirm and toast with the library.
## Follow the html file to use the library
## This link is for version 1.0.0 clone project and use as-min.js for version 2.0.0
### CDN V1.0.0: https://dl.dropbox.com/s/yrr7z4avnas4a6c/asteroid-alert-min.js

### Functions
<pre>
$confirm("Do you want to delete?", "#E74C3C")
  .then(() => {
     $toast("Deleted", "#E74C3C");
})<br>
  
$alert("Successfull", '#E74C3C') 
$toast("No internet connection", "#F4D03F")

## Loading alert in v2
$loader_show("#FF5733") If you don't provide any color code it will take default color
$loader_hide()

If you don't provide any color code it will take default color
</pre>
