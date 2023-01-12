# Pytesseract Test

In this repo I test the Pytesseract library with different types of text images. The objective in all the types is to properly detect and segment the text in all the images.
The are images with flat text and with text in tables. In the first case, Pytesseract is used directly, while in the second cases an algorithm to go over the cells of the table is implemented.
The output of those cases is saved in a dataframe object. 
