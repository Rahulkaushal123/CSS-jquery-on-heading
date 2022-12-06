# CSS-jquery-on-heading
<!DOCTYPE html>
<html>
<head>
<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script>
$(document).ready(function(){
$("h1").on({
mouseenter: function(){
$(this).css("background-color","lightgray");
},
mouseleave: function(){
$(this).css("background-color","red");
},
click: function(){
$(this).css("background-color","blue");
}
});
});
</script>
</head>
<body>
<h1>hello this is j query using css</h1>
</body>
</html>
