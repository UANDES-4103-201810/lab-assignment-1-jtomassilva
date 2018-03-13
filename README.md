# lab-assignment-1
Base project for lab assignment 1

3. ELEMENTS: There are two principal tags, the Head tag and the Body tag.

	On the Head tag its shown the general page information such as:
		The title: 'Hacker News' between the <tittle> tags.
		The favicon, the little image that appears on the browser tab (The orange 'Y' icon).
		The stylesheet, wich defines the style of the page (the design).
		And other things that I dont know what they are.

	On the Body part it goes the specific information thats shown on the site, wich its divided on diferent tags that belong to the Body tag. This subtags are:
		The <center> tag wich have the porpouse of align the content at the center of the browser window.
			Inside the <center> tags its defined a <table> tag. This table tag its a way to store information in an orderly manner, inside rows and columns.
			(In this site there is a main table with two rows, the first row, which store the logo, tittle, menu and login of the site. 
			And, a second row, wich store another table, that has many rows on it, and each row store a diferent post.)
				Then, inside the table, its defined the <tbody> wich its the body of the table itself, inside this tags its defined the table content.
					Inside the <tbody> its the <tr> tag, wich defines a new table row.
						Then, inside the <tr>, there is the <td> tag that defines the objects that are shown on the row.
							And finally, the <a> tag wich store the link that redirects to the origin site of the news on the post.


4. SOURCES: There are 6 elements on the sources of this site.
	
	1. The (index) element, wich has the code of the page on html format. 
	2. The second element it is https://news.ycombinator.com/hn.js?XmeMkOgGRBw9auMJ1Y7Q, and its where the functions are defined. This functions are called on the page code,
		and used every time a user log in, or submits a comment, etc.
	3. The third item it is https://news.ycombinator.com/news.css?XmeMkOgGRBw9auMJ1Y7Q, and its where the styles of the page are stored. The object designs, text font, sizes, colors, etc.
	4,5 and 6. Are images (or gifs). The logo of the page, the gray arrows, etc.

5. NETWORK: XHR (XMLHttpRequest) its an JavaScript object that allows to obtain information from a URL without having to reload the full webpage. The files where loaded the first time it was visited
	and they where stored so when you have to visit it again it will not need to reload all the content.

6. SECURITY: The connection to this site is using a valid, trusted server certificate issued by COMODO RSA Domain Validation Secure Server CA.
	The certificate its valid from 21-08-2014 to 21-08-2019.	
