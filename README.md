<!DOCTYPE html>
<html>
<head>
	<title></title>
	<style type="text/css">
		.filho{
			width: 500px;
			height: 500px;
			border: 1px solid black;
		}
	</style>
<head>
<body>
<div class="pai">
	<div class="filho"></div>
	<div class="filho"></div>
	<div class="filho"></div>
	<div class="filho"></div>
	<div class="filho"></div>
	<div class="filho"></div>
<div>
<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<script>
//aplicar cor vermelha apenas nos elementos que possui número impar
	$(function(){
		var index = 0;
		$('.pai .filho').each(function(){
			if(index%2 == 1){
				$(this).css('background','red');
			}
			index++;
		})
		
	})
</script>
<body>
</html>	
