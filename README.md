<<<<<<< HEAD
FirstDial
=========

First attempt at YUI dial
=======
SecondDial
==========

On Saturday night, there were a few issues
1. works just fine on first drag of handle, but once let go of handle (lift finger) it never works
	correctly again. numbers are balky, handle goes zooming off the page, etc.
		a. possible 'fix' to re-instantiate or re-build the dial any time a number does not change for 
		   1 second? (preserving the old values, not re-initializing them?)
2. I still cannot find out where the font size and positioning of the variable is defined. I suspect
	that it is buried in the js itself.
3. when loading in the browser, the intro string (e.g. Hubble and my ass) show up until the dial
	builds, then they disappear (under white viewing frame?). Each F5 in browser shows them  briefly
	only to disappear when the dial appears
4. the loading spinner has a flea in it?

hacking YUI Dial code to learn more HTML
>>>>>>> 56e5b59c3e6bc9f22293972783bc565d744c0624
