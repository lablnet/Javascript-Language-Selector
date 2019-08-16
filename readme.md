
# Javascript Langauge Selector

Create your frontend website in multiple languages by using this class.

### Features
- Simple but yet powerful.
- Enable RTL automatically.
- Super fast.
- Much more...

### Requirement
- Jquery

### How to use?

- Just download this code or clone
	- ``` 
		git clone https://github.com/Lablnet/Javascript-Language-Selector.git```

- Include the `js` file in `head` section of your page
	- ```html 
		<script src="js/LanguageSelector.min.js"></script>```
		
	- Make sure jquery is included in your page

- Load the language file which contain json data
	- ```html 
		<script src="locale.js"></script> ```
		
	  - The `locale.js` file contains language strings something like
	- ```js lang = {
			'en': {
				':heading': 'Javascript Language Selector',
				':h2': 'This is the sub heading',
				':first:p': "Hey! this is the javascript language selector",
				':english': 'English',
				':urdu': 'Urdu',
				':portuguese': 'Portuguese',
				':choose': 'Choose the language',
			},
		}	```
- Now write your markup/html
	- ```html
		<h1>:heading</h1>
		<h3>:h2</h3>
		<p>:first:p</p>	```
- Parse language
	- ```js
		var l = new LanguageSelector();
		l.parse();	```

- That's all.


### LICENSE
- MIT

### Author
[Muhammad Umer Farooq](https://lablnet.github.io/profile/)
