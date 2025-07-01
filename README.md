In this project, I built a responsive homepage to serve as a template for a portfolio. The page contains 3 primary sections: a header, main, and footer.

The header first contains a background shape. This shape was made by clipping the bottom right corner up by 55% on the y-axis so the container would have a slant to it. Below this container is an image that uses the properties of min-height and max-width. This is so the image wont overflow its container. When the screen is greater than 500 pixels, the image is 500 pixels in width. When the screen is less than 500 pixe, image has a width of 320 pixels. Next, there is a container with text. This container is to right of the header image when greater than 1000 pixels and below the image when less than 1000 pixels. At the bottom of text container, there are images of the X (formerly Twitter) logo, GitHub logo, and LinkedIn logo.

In the main section, there are 6 cards that represent projects. The responsiveness of the cards is controlled by the minmax CSS function. Each of these projects contain what will be the projects' GitHub link as well as the direct link. 


Lastly, in the footer section, there is another image, a fake phone number, a fake email, both of with contain an SVG along with them, and a repeat of the X (formerly Twitter), GitHub, and LinkedIn logos slightly larger than the header ones. 