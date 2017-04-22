Small plugin to show modal dialog boxes.
----

### Usage
Download files and link to them in the html head section.

Then:

Write some options and content.
(default values shown below)
```
var options = {
	width: 300,  		 		// in pixels
	height: 200,  				// in pixels
	closeButton: true, 			// show close button / if you hide it, provide user another way to close it
	overlay: true,   			// show overlay to darken webpage
	backgroundColor: 'white',   // can also be '#ddd' format
	fromTop: 10,   				// in percents
	content: ""  				// put in here what you want to be shown, text or html
}	
		
var mod = new Modal(options);	// build modal
mod.show(); 					// display modal
mod.close(); 					// close modal
```
