# Spelling-Check
# Report for the assignment
## Basic Algorithm
  •	First try to check whether the image contains the noise or not.
  •	Later if it contains noise remove the noise and make the image denoised.
    o	So, for image denoising we can use OTSU Thresholding, K-SVD and other techniques
    o	The one showed contains the OTSU Thresholding and Binary Thresholding (We can use K-SVD which will fetch better results).
  •	Then using OCR Techniques to extract the text from the image. 
    o	The methods which we can use over here will be PyTesseract, Google Vision API etc
    o	Here I have used PyTesseract for fetching the results (Google Vision API will give better results).
  •	After getting text we can check for spelling corrections we can use NLP modules or we can create our own model for spelling correction.
    o	Here I am using TextBlob for spelling correction. But we can use our own model which will fetch better results because we know the prospects of the model used where we can       use transfer Learning to get the pre-trained weights.

## Pre-Process performed on image 
  •	We require for one assignment for pre-processing such as giving only GRAY image after removing noise (Working on that).

## List of experiments performed to get best results
  •	Planned to pre-process the image with more advance models to make work on the less clarified pictures (To use SVD).
  •	Planning to make the spelling check better by creating the model

## Observations:
  •	We require vocabulary which contains some dictionary words for spelling corrections and if the it contains different languages the vocabulary must contain the different       language words also.
  • We require to train the vocabulary to get the spelling corrected.

