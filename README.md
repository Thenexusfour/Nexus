# Social Media Web page

## creating with simple html and css codes 

# Here is the  HTML code:

```html
<!DOCTYPE html>
<html>
<head>
	<title>Social Media Buttons</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="background-image"></div>
	<div class="social-buttons">
		<a href="https://www.instagram.com" target="_blank">
			<button class="instagram-button">
				<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/640px-Instagram_icon.png">
			</button>
		</a>
		<a href="https://www.facebook.com" target="_blank">
			<button class="facebook-button">
				<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Facebook_Logo_%282019%29.png/1024px-Facebook_Logo_%282019%29.png">
			</button>
		</a>
		<a href="https://www.bereal.com" target="_blank">
			<button class="bereal-button">
				<img src="https://upload.wikimedia.org/wikipedia/en/4/40/BeReal_logo.png">
			</button>
		</a>
		<a href="https://twitter.com/" target="_blank">
			<button class="twitter-button">
				<img src="https://cdn4.iconfinder.com/data/icons/social-media-icons-the-circle-set/48/twitter_circle-512.png">
			</button>
		</a>
	</div>
</body>
</html>

```
# Here is the css code
```css
body {
	margin: 0;
	padding: 0;
}

.background-image {
	background-image: url("https://images.pling.com/img/00/00/64/96/96/1726919/nature-minimalist-style-201.jpg");
	background-size: cover;
	position: absolute;
	top: 0;
	left: 0;
	height: 100%;
	width: 100%;
	filter: blur(2px);
	z-index: -1;
}

.social-buttons {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	display: flex;
	flex-direction: row;
	align-items: center;
	justify-content: center;
}

.instagram-button, .facebook-button, .bereal-button, .twitter-button {
	background-color: transparent;
	border: none;
	cursor: pointer;
	padding: 0;
	margin: 20px;
}

.instagram-button img, .facebook-button img, .bereal-button img, .twitter-button img {
	height: 150px;
	transition: all 0.3s ease-in-out;
}

.instagram-button:hover img, .facebook-button:hover img, .bereal-button:hover img, .twitter-button:hover img {
	transform: scale(1.1);
}

.instagram-button:active img, .facebook-button:active img, .bereal-button:active img, .twitter-button:active img {
	transform: scale(0.9);
}

        ```
        


