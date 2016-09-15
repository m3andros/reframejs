# reframejs

A very basic lightweight plugin that makes iframes or any &lt;div&gt; responsive.

Perhaps "responsive" isn't the right word here.  Think of when you omit the height on an image, it will scale when you define its width. By default, iframes don't do that, but this plugins allows them to be scaled.

The functionality is pretty straightforward - it just creates a parent element of the correct width/height around an element that dictates the original element's height, and then resizes the inside one proportionately as needed for responsiveness (i.e., using CSS only).

