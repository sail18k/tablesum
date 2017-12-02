# tablesum

#A plugin can save your time from coding multiple lines in jquery.

#How to use it:

1. Put the latest version of jQuery library and jQuery sumTable.js script at the bottom of the webpage.

	<script src="//code.jquery.com/jquery-3.1.0.slim.min.js"></script>

	<script src="sumTable.js"></script>

2. Just call the function sumTable() on the html table and the plugin will do the rest.
	  <script type="text/javascript">
    $(selector).sumTable({
      "totalClass" : "className anotherClassName", /* Set class for total tr*/
	  "tot_in" : 6, /* Set column position for total text to display.*/
	  "tot_title" : "TOTAL", /* Set text for total column*/
	  "index" : "6,7,8,9,10,11", /* Enter column number to get sum value */
	  "color" : "#ff0000", /* Set color for total column elements*/
    });
  </script>				
