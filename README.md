# Color-Compression-Using-Unsupervised-ML

Many display devices allow only a limited number of colors to be simultaneously displayed. Therefore, true color images may need to be converted to indexed color images for the purpose of saving storage space or display in restricted display devices  In this project, functions are defined to compress the images using some unsupervised Machine Learning algorithms such as k-means, winner takes all and Kohonen maps.

In this project, we are given a full color image in .ppm format. Each pixel of this color image has three components: red, green, and blue components. Each component is an 8-bit unsigned char. There are thus totally 2^24 possible colors. For certain computers which can only display 256 (or 2^8) different colors, that is, each pixel only has 8 bits representing the color information, we will find the best 2^8 colors that can approximate the original full-color image.
