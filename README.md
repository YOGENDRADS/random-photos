# https://yogendrads.github.io/random-photos/
# random-photos
we will create different random image generator using JavaScript and HTML source code. Firstly, it requires an array to contain the URLs of images to be displayed on the webpage.

The images you see on a website generating randomly, are already stored in a database or an array. These images display to the user within a regular time interval or change by a click. You can also provide the address of an image directly from the internet.

Declare an array using JavaScript to store the images.

Provide the link or URL of images in the declared array. You can also pass the height and width in the array for the image size to display on the webpage.

Declare a JavaScript variable to store a random value calculated using this # floor(Math.random()*randomImage.length) method. It will generate a random number between 0 and the length of the array that will be assigned to the images to display randomly.

Now, return the random images selected using a number calculated in the previous step.

Put all the above steps in a user-defined function (getRandomImage), which will call by clicking on a Generate Image
In HTML code, we will use a tab and provide an ID to display an image over another image. So, the images will show you one by one, by overwrapping each other.
