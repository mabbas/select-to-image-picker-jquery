# JQuery Image Picker based on existing HTML select box! #

This project shows how to change HTML select box to graphical image picker, based on JQuery UI modal window.

All you need is to include JQuery library, JQueryUI library and our library:
```
<link href="/resources/css/jquery.imagepicker.css" rel="stylesheet" type="text/css" />
<link href="/resources/css/jquery-ui.css" rel="stylesheet" type="text/css" />

<script src="/resources/js/jquery-1.11.1.min.js" type="text/javascript"></script>
<script src="/resources/js/jquery-ui.js" type="text/javascript"></script>
<script src="/resources/js/jquery.imagepicker.js" type="text/javascript"></script>
```
Then, when you have such an HTML element:
```
<select id="#icon">
  <option value="/path/to/image/1.png">title #1</option>
  <option value="/path/to/image/2.png">title #2</option>
  <option value="/path/to/image/3.png">title #3</option>
  <option value="/path/to/image/4.png">title #4</option>
</select>
```
Then, just call JQuery function:
```
<script>
$(document).ready(function(){

	$("#icon").imagePicker();

});
</script>
```
Live demo (click on the round image):

http://www.fridayweekend.com/create

Works on:

- Safari: YES
- Opera: YES
- Firefox: YES
- Icewasel: YES
- Lynx: YES (our picker remains a valid HTML!!!)
- IE: YES (a new one...)

Have an awesome weekend!

Cheers!
Lukasz