# loopcounter

This is simple countdown timer using JQuery.

## How to add this?
loopcounter has a dependency in JQuery. So you need to first add the JQuery in your HTML and the add the `loopcounter.js` which is already in js folder and the add the `loopcounter('class_selector');`

Add this code in HTML file. Here is a date format please follow this date format(yyyy-mm-dd hh:mm:ss)
```
<div class="first-counter" data-date="2018-06-08 10:20:30"><!-- Date Formate Input yyyy-mm-dd hh:mm:ss -->
	<div><span class="counter-days"></span> Days</div>
	<div><span class="counter-hours"></span> Hours</div>
	<div><span class="counter-minutes"></span> Minutes</div>
	<div><span class="counter-seconds"></span> Seconds</div>
</div>
```
Include this in footer of the HTML file-
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.2/jquery.min.js"></script>
<script src="./js/loopcounter.js"></script>
<script type="text/javascript">
	$(document).ready(function(){
		loopcounter('first-counter');
		//loopcounter('second-counter');
	});
</script>
```
