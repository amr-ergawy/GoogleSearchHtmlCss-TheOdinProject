This is an implementation of the Google Search page, without back-end functionality.

An implementation of the HTML/CSS project of the web development course TheOdinProject: http://www.theodinproject.com/web-development-101/html-css

In addition to inspecting the elements of the Google page itself, I googled for solutions for many problems.

The most important solved problems:

1. Handling user zooming-in the browser window by using a relative global container element and bottom padding in the content element that is larger the height and the max-height of the footer. 

The solution from: http://cssreset.com/how-to-keep-footer-at-bottom-of-page-with-css/

2. Handling elements distortion on user resizing the browser window by using min-width values as necessary for many <div/> elements.

3. Handling the buttons group distortion on user zooming-out the browser window by using display: inline-block for their container <div/> to dynamically fits the buttons it. Avoiding the usage of a fixed width for this container <div/>
