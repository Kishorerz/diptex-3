# Histogram Equalization Using OpenCV (Grayscale & Color Images)
# Name : Kishor kumar B
# Reg.No: 212223240072
---

## Aim

To write a Python program using OpenCV to perform histogram equalization on both grayscale and color images to enhance image contrast and brightness.

The program performs the following operations:

- Read and display a grayscale image  
- Plot histogram of the grayscale image  
- Apply histogram equalization on grayscale image  
- Read and display a color image  
- Plot histogram of B, G, R channels  
- Convert image to HSV color space  
- Apply histogram equalization on the Value (V) channel  
- Convert the enhanced image back to BGR format  
- Display original and enhanced images with histograms  

---

## Software Used

- Anaconda – Python 3.7  
- Jupyter Notebook / VS Code  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  

---

## Algorithm

### Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the image `parrot.jpg` in grayscale format.

### Step 3:
Display the grayscale image and plot its histogram.

### Step 4:
Apply histogram equalization using `cv2.equalizeHist()` to enhance contrast.

### Step 5:
Display original grayscale image, its histogram, enhanced image, and its histogram using a 2 × 2 grid.

### Step 6:
Read the same image in color format.

### Step 7:
Split the image into B, G, R channels and plot their histograms.

### Step 8:
Convert the image from BGR to HSV color space.

### Step 9:
Apply histogram equalization on the V (Value) channel.

### Step 10:
Merge the channels and convert the image back to BGR format.

### Step 11:
Display original color image, histogram, enhanced image, and enhanced histogram using a 2 × 2 grid.

---

## Program

### Developed By:
**Name:** Kishor Kumar B

### Register No: 212223240072

---

##  Output

### Grayscale Histogram Equalization

- Original grayscale image is displayed

<img width="579" height="348" alt="image" src="https://github.com/user-attachments/assets/f37293ea-8d59-4314-9950-3971edf60855" />
 
- Histogram of original grayscale image is plotted

<img width="620" height="438" alt="image" src="https://github.com/user-attachments/assets/3df6577b-3e24-45e7-961e-68169d1c0c82" />

- Enhanced image after histogram equalization is displayed

<img width="657" height="371" alt="image" src="https://github.com/user-attachments/assets/f4125995-7f76-4ae8-b727-ce2488e14fa7" />

- Histogram of enhanced grayscale image shows improved contrast

<img width="612" height="336" alt="image" src="https://github.com/user-attachments/assets/5835f17a-9cee-4cf5-90a5-400de9dafad4" />
 

### Color Image Histogram Equalization

- Original color image is displayed

<img width="594" height="416" alt="image" src="https://github.com/user-attachments/assets/926d98c8-be29-4287-98a4-2c8dc1e98cf4" />
 
- Histogram of B, G, R channels is plotted

<img width="1170" height="328" alt="image" src="https://github.com/user-attachments/assets/6971eff7-e6e1-4279-bf56-c227228218e9" />

- Enhanced image after HSV-based equalization is displayed

<img width="1148" height="375" alt="image" src="https://github.com/user-attachments/assets/8aa4a8cf-f76b-49f9-b0af-064f709458c8" />

- Histogram of enhanced image shows better intensity distribution
<img width="1148" height="375" alt="image" src="https://github.com/user-attachments/assets/360977f5-ef51-46ff-a494-82ea04f6bfa9" />



---

## Result

Thus, histogram equalization is successfully performed on both grayscale and color images using OpenCV. The contrast and brightness of the images are significantly improved, enhancing visual quality and feature visibility.
