# lisatest
## Programs Problems
	- In `programs.html`
		- Added the content from the design.
		- Updated tags to be semantic HTML5


## Home Havoc
	- In `index.html`
		- Added a linear gradient background on home page `about` and `programs` buttons
			- Orange: `#FB6B03`
			- Blue: `#23A9E1`
             - Set content and hero image to a 2 column layout like in the design.


## All About It
	- In `about.html`
		- Put the result from the `cards` function in the `container` element.—It’s already there?
	
## Lacking Login
	- In `login.js`
		- In the `validate` function, password was empty. Called the `authentication` function.

## Serving Server
	- In `server.js`
		- Made conditional statement to see if the requested resource was `"/"` console logged `"Home Page!"`.

## Responding Response
	- In `server.js` 
		- sent a response with the result of `db.checkAuth` at `"/auth"`
