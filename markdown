<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>极简markdown博客开发</title>
</head>
<body>

<div id="content">
	
</div>
	<script src="https://cdn.bootcss.com/marked/0.3.6/marked.min.js"></script>
	<script>
	var markedown =' # Marked in browser\n\nRendered by **marked**.'
	              
	html = marked(markedown)
    document.getElementById('content').innerHTML = html
      // marked('# Marked in browser\n\nRendered by **marked**.'); 
  </script>
</body>
</html>
