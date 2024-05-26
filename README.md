# OCR_arabic_IDs
Using OCR (Optical Character Recognition) and advanced image processing techniques to extract and rectify data from Egyptian ID. 
## the main parts 
1-Card Rectification Algorithm: Utilizes the UNetRNN model to correct the orientation and perspective of the ID card image.
2-Comparison with Reference Image: Aligns the corrected ID card image with a reference image to ensure proper orientation and format.
3-Text Detection: Uses ArabicOCR for detecting text fields on the ID card.
4-ID Number Extraction: Employs Tesseract-OCR to accurately extract the ID number.
