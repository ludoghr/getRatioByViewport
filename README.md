# Get Ratio By Viewport SCSS
If you need to find an element's height based on the viewport width. No javascript needed.

The usage:
In a full responsive website you have to find the height of an element.
You know that the element is 640*800 at a viewport width of 1024px.

You just need to call the function as the value of the css attribute you need to find (height mainly):

.myElement {
    height: getRatioByViewport(640, 800, 1024);
}

You can also call this function if you need some top absolute positioning based on another element's height.

Feel free to ask questions if you have any.
