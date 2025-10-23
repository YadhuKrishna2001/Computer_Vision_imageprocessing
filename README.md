# Computer_Vision_imageprocessing
Basic Image processing methods

Why Do We Apply Multiple Image Processing Steps?

When working with computer vision, especially before feeding images into a model (like CNN or object detector), we almost never use raw images directly.
Why?
Because raw images can have noise, lighting variations, unwanted colors, and irregular sizes — all of which can confuse the algorithm.
So, we process the image step by step to make it clean, standardized, and meaningful for the computer.

# Process 
Convert to grayscale → focus on shapes, not colors
Remove noise → make edges clear
Blur → remove distractions
Adjust contrast → highlight faces
Resize → fit into the model’s expected size
