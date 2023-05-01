Download Link: https://assignmentchef.com/product/solved-bme7408-homework-3-image-processing
<br>
Solve the problems 3.22, 3.27, 3.38, 4.3, 4.32 in the textbook.




<h1>Part 2:</h1>

Design a computer program for spatial filtering operations using various types of masks. Test your program with several images and report your results. Discuss the effect of mask size on the processed images and the computation time.

You should design a mask operation function that is flexible for adjusting mask size and setting coefficients in the mask.




<h1>Part 3:</h1>

The Marr-Hildreth edge detection method operates by convolving the image with the Laplacian of Gaussian operators.  Laplacian of Gaussian (LoG) is a second derivative of a Gaussian filter. The LoG can be broken up into two steps. First, smooth the image with a Gaussian filter, and second, convolve the image with a Laplacian mask. Read the Section 10.2 of our textbook for a detailed theory and procedure of this edge detection method.

Implement a computer program for edge detection using the Marr-Hildreth edge detector. Test your program with at least 4 images and compare the results with those processed with the Sobel operator. Sample images are provided in the CEIBA course website. To locate the edges of the images processed with the Marr-Hildreth detector, you will need to further process the images with the zerocrossing detector as described in the textbook.

Discuss the effect of zero-crossing threshold on the Marr-Hildreth edge detection method.




<h1>Part 4:</h1>

Implement an order-statistic filter function which is flexible for users to select: (1) median filter, (2) max filter, (3) min filter. The function should also be flexible in choosing different filter sizes.

Test your program function with Figure 3.43(a), and compare the result with Gaussian filter. Discuss the effect of filter size on the image processing result.




<strong><u>Notes:</u> </strong>

<ol>

 <li>Please submit your programs and report to the AUTOLAB course website before <strong> 3</strong> <strong>(2:20PM).</strong></li>

 <li>Late submission will have a penalty of 10% discount per day of your homework total score toward a maximum of 50% discount. No late submission over five days will be accepted.</li>

</ol>