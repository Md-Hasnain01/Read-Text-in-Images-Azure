# Azure AI Vision Text Reading Application

This application utilizes the Azure AI Vision API to read text from images, including printed text and handwriting. It provides a simple command-line interface for users to select an image and view the extracted text along with bounding boxes around the detected text.

## Features

- Read printed text from images (e.g., `Lincoln.jpg`).
- Read handwriting from images (e.g., `Note.jpg`).
- Display detected text and its bounding polygons on the original image.
- Save the annotated image with detected text as `text.jpg`.

## Prerequisites

- Python 3.6 or higher
- Azure account with access to the Computer Vision API
- Necessary Python packages


## Example Output

1: Use Read API for image (Lincoln.jpg)

2: Read handwriting (Note.jpg)

Any other key to quit

Enter a number: 1

Text:

  This is an example of detected text.
  
   Bounding Polygon: ((x1, y1), (x2, y2), (x3, y3), (x4, y4))
   
    Word: 'This', Bounding Polygon: ((x1, y1), (x2, y2), (x3, y3), (x4, y4)), Confidence: 0.9999
    
    Word: 'is', Bounding Polygon: ((x1, y1), (x2, y2), (x3, y3), (x4, y4)), Confidence: 0.9999
    
    ...
    
Results saved in text.jpg


![Screenshot 2024-11-06 115752](https://github.com/user-attachments/assets/9e98be15-a35f-4238-8020-0a9a5b3e575c)


![Screenshot 2024-11-06 115018](https://github.com/user-attachments/assets/21fba4f7-99f4-4cd2-90a6-35fc501fa22c)

![Screenshot 2024-11-06 115533](https://github.com/user-attachments/assets/1c6482fe-a2e6-475a-a7d7-9ca33c87f14b)
