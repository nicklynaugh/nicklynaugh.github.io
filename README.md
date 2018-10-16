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
		<a href="mailto:jon@jonphillips.ca" title="Email Jon Phillips">Contact</a>
	</section>
</main>

<footer>
	<a class="tw" href="https://twitter.com/jophillips" title="Jon Phillips on Twitter"><span class="icon-twitter"></span></a>
	<a class="fb" href="https://www.facebook.com/jo.phillips" title="Jon Phillips on Facebook"><span class="icon-facebook"></span></a>
	<a class="ig" href="https://www.instagram.com/phillips_jon/" title="Jon Phillips on Instagram"><span class="icon-instagram"></span></a>
	<a class="li" href="https://www.linkedin.com/in/jonathancphillips" title="Jon Phillips on LinkedIn"><span class="icon-linkedin"></span></a>
</footer>

<script>
var showText = function (target, message, index, interval) {
	if (index < message.length) {
		$(target).append(message[index++]);
		setTimeout(function () { showText(target, message, index, interval); }, interval);
	}
}
$(function () {
	showText("#desc", "User Interface Designer", 0, 100);
});
</script>


</body></html>
