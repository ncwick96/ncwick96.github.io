# ncwick96.github.io
# Testing a thing
<html>
<head>
<script type="text/javascript" src="jquery-1.3.2.min.js"></script>

<style type="text/css">
	.htmlClass{
		padding:8px;
		border:1px solid blue;
		margin-bottom:8px;
	}
</style>

</head>
<body>
  <h1>jQuery html() example</h1>

  <div class="htmlClass">I'm going to replate by something ....</div>
  
  <div class="htmlClass">I'm going to replate by something 2....</div>
  
  <p>
  <button id="getHtml">html()</button>
  <button id="setHtml">html('xxx')</button>
  <button id="reset">reset</button>
  </p>

  <script type="text/javascript">
	
    $("#getHtml").click(function () {
		
	  alert($('.htmlClass').html());
	  
    });
	
    $("#setHtml").click(function () {
		
	  $('.htmlClass').html('<b>This is a new text</b>');
	  
    });
	
    $("#reset").click(function () {
	  location.reload();
    });
	
</script>
</body>
</html>
