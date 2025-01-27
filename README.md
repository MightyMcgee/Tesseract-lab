# Tesseract-lab
This project uses openCV to open all of the images in a folder and crop them. For this example I used Magic the Gathering Cards and cropped each so only the name of the card was left. Then the cropped images are saved and I use tesseract-ocr to read the text left in the image. The output of tesseract is put into a different output file for each card.
To use this program create a folder with images that you want to read then adjust the dimensions you crop the images to so it only includes thee text you want. Then, run it and you will have output files with all of the text. Also, make sure the os and openCV modules are installed
https://www.geeksforgeeks.org/how-to-install-opencv-for-python-in-windows/
https://www.geeksforgeeks.org/python-loop-through-folders-and-files-in-directory/
https://www.geeksforgeeks.org/how-to-iterate-over-files-in-directory-using-python/
