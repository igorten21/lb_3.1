# lb_3.1

Город: Compton
# Используемый код:
```
<html>
<meta charset="UTF-8">
	<head>
		<title>Sample page</title>
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
		<script>
			var settings = {
				"async":true,
				"crossDomain":true,
  			"url": "https://api.openweathermap.org/data/2.5/weather?lat=33.89&lon=-118.22&appid=f7e9ad829f9315b0ab91004548138ff7",
  			"method": "GET",
  			"timeout": 0
		}

		$.ajax(settings).done(function (response) {
  			console.log(response);
		});
	</script>
	</head>
<body>
	<h2>Sample page</h2>

</body>
</html>
```
