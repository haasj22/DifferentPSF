# DifferentPSF
Created using fspecial in MATLAB seen in documentation below
https://www.mathworks.com/help/images/image-deblurring.html

psf.txt has strengths 2-50 incremented by 2 for angles 180-350 incremented by 10
psf (1).txt has strengths 2-47 incremented by 5 for angles 180-350 incremented by 10
The latter will run a lot faster so is reccomended for use in deblurring if you really don't know the needed strength
If you have a normal slight blur start with strength 2-8 as higher ones will likely just make your image unrecognizable
