</head>
<body>
	<h1>Creating a Custom Splash Screen for KDE Plasma</h1>
	<p>This is just a quick guide I have put together for anyone wanting to customise their splashscreen in KDE Plasma, It is not complete and mainly to help people get a quick start.</p>
	<h2>Instructions:</h2>
	<ol>
		<li>Rename the folder to what you want to call your splashscreen</li>
		<li>Inside the folder, open metadata.desktop and change the following lines to match the name of the folder:
			<ul>
				<li>Comment</li>
				<li>Name</li>
				<li>X-KDE-PluginInfo-Name</li>
			</ul>
			Change to your name:
			<ul>
				<li>X-KDE-PluginInfo-Author</li>
			</ul>
		</li>
		<li>Open contents/splash/images and copy the image you wish to use for the background, rename this image background.png</li>
		<li>If the file is not a png, you can either convert the image or change the following line in Splash.qml:
			<pre>source: "images/background.png"</pre>
			Change to the name and extension of your picture.
		</li>
		<li>You can also change the logo the same way</li>
		<li>Other colors, etc., you may want to change can be found in Splash.qml and use a hex code</li>
	</ol>
	<h2>Preview:</h2>
	<img src="https://github.com/smokey5787/EOS-Blank-Splashscreen/blob/main/EOS-Blank/contents/previews/splash.png" alt="preview">
</body>
</html>
