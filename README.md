Council Toolkit Templates
=========

Just the flat HTML/CSS templates to help you get started.

Current template list: 

- Home
- Category
- Category with widget
- Sub-category
- Article
- Guide
- Signpost
- Generic content
- Search results
- A to Z
- Contact
- Home with emergency banner
- Email template


## Adding custom CSS

If you want to add your own CSS we suggest you create a new CSS file and call it from your templates. That will allow you to update these templates without any extra work. Either add your own CSS file(s) or have your Sass files compile to CSS.


## Adding your logo

Replace 'Council name' with 

	<img src="/path/to/logo.svg" data-fallback="/path/to/logo-fallback.png" alt="Council Name" />
	
The SVG version will display for all capable browsers, and is a vector file so scales to any size on any screen. Browsers with no SVG in <img> support will display the PNG fallback version.