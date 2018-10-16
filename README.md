<html dir="ltr" lang="en-US"><head>
<title>Jon Phillips - Maker Of Fine Internet Stuffs</title>
	<meta charset="utf-8">
	<meta name="description" content="Jon Phillips is a maker of fine internet stuffs. A designer, developer, entrepreneur, lover of typography and photography.">
	<meta name="keywords" content="Jon Phillips, design, designer, developer, Montreal, Canada, UX, usability, typography, css, html, jQuery, PHP, user experience, user interface, BuySellAds, Contrastly">
	<meta name="author" content="Jon Phillips">
	<meta name="robots" content="index, follow">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="apple-touch-icon" href="/apple-touch-icon.png">
	<link rel="Shortcut Icon" href="/favicon.ico" type="image/x-icon">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
	<link rel="stylesheet" href="/style.css?4" type="text/css" media="screen">
</head>
<body>

<main class="container">
	<section class="content">
		<h1>Nick Lynaugh</h1>
		<p id="desc">Writer</p>
		<a href="mailto:nicklynaugh@gmail.com" title="Email Nick Lynaugh">Contact</a>
	</section>
</main>


<script>
var showText = function (target, message, index, interval) {
	if (index < message.length) {
		$(target).append(message[index++]);
		setTimeout(function () { showText(target, message, index, interval); }, interval);
	}
}
$(function () {
	showText("#desc", "Writer", 0, 100);
});
</script>


</body></html>
