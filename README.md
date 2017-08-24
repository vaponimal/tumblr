/* Global colors
********************************/

body {
	color: {color:Body Text};
	background-color: {BackgroundColor};
}

.blog-description {
	color: {color:Secondary text};
}

a {
	color: {color:Body text};
	text-decoration: none;
	border-bottom: 1px solid rgba(136, 136, 136, 0.3);
}

#header h1 a {
	color: {TitleColor};
	border-bottom: none;
}

a:hover {
}

a:active {
	position: relative;
	outline: none;
	top: 1px;
}


.metadata a, #footer-links a, #footer p.promo a, .links a {
	color: {color:Secondary text};
	border-bottom: none;
}

.metadata a:hover, #footer-links a:hover, #footer p.promo a:hover, .links a:hover, .more a:hover, a.mobile-player:hover {

}

.post {
	border-bottom: 1px solid rgba(136, 136, 136, 0.2);
}

.colophon p {
	color: {color:Secondary text};
}


/* Global fonts
********************************/

body {
	font-family: {block:IfBodyFont}{text:Body Font},{/block:IfBodyFont} {font:Body font}, georgia, serif;
	font-weight: normal;
}

.title h1, .link-title h1, .chat-title h1, .q h1, .a h1, .album-info h2, #footer h2 {
	font-family: {block:IfPostHeadlineFont}{text:Post Headline Font},{/block:IfPostHeadlineFont} {TitleFont}, georgia, serif;
	font-weight: {TitleFontWeight};
}

.blog-title h1 {
	font-family: {block:IfTitleFont}{text:Title Font},{/block:IfTitleFont} {TitleFont}, futura, helvetica, arial, sans-serif;
	font-weight: {TitleFontWeight};
	font-size: 96px;
	line-height: 1em;
}

.metadata a {
	font-family: {block:IfSecondaryFont}{text:Secondary Font},{/block:IfSecondaryFont} {font:Body}, helvetica, arial, sans-serif;
	font-weight: normal;
}
