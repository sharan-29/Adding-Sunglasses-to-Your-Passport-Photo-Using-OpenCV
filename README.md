# Adding Sunglasses to Your Passport Photo Using OpenCV

**Name :** Sharan Kumar G  
**Reg No:** 212224230260

## 1. Aim

To overlay sunglasses onto a passport-size photograph using OpenCV, image masking, and arithmetic operations in Python.

## 2. Project Description

This project demonstrates how to add sunglasses to a face image using OpenCV. A passport-size photograph is used as the input image, and a sunglasses image is placed over the eye region. Image masking and arithmetic operations are used to blend the sunglasses with the original photograph and produce the final output.

## 3. Technologies Used

- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Jupyter Notebook

## 4. Requirements

- Python installed on the system
- OpenCV library
- NumPy library
- Matplotlib library
- A passport-size photograph in JPG or PNG format
- A sunglasses image with an alpha channel or a suitable background

## 5. Installation

Install the required libraries using the following command:

```bash
pip install opencv-python numpy matplotlib
```

## 6. Implementation Steps

1. Import the required Python libraries.
2. Load the passport-size photograph.
3. Load the sunglasses image from the GitHub repository.
4. Resize the sunglasses to fit the eye region.
5. Separate the color and alpha channels, or create a mask if necessary.
6. Use image masking and arithmetic operations to combine the sunglasses with the eye region.
7. Adjust the coordinates and dimensions for proper alignment.
8. Display and save the final output image.

## 7. Input and Output

**Input:** Original passport-size photograph and sunglasses image.

<img width="447" height="546" alt="image" src="https://github.com/user-attachments/assets/e05e31cc-4d78-46df-9113-ae3eea3b2544" />


**Output:** Passport-size photograph with sunglasses placed over the eyes.

<img width="1380" height="817" alt="image" src="https://github.com/user-attachments/assets/3a9fac42-8256-49cf-95f0-bb22f4f2e83e" />



## 8. Result

Sunglasses are overlaid onto the eye region of the passport-size photograph using OpenCV, image masking, and arithmetic operations. The final image is displayed and saved for submission.


