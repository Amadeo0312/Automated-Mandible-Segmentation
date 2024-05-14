# Automated-Mandible-Segmentation
![alt text](https://github.com/Amadeo0312/Automated-Mandible-Segmentation/blob/main/ReadMe-Images/introduction.png)
## How to Use:

  ### 2D UNet

Follow these steps to set up and run the 2D UNet project:

1. **Install the requirements**  
   Use the command below to install the necessary libraries from the requirements file:
  ```sh
   pip install -r requirements.txt
  ```
3. **Prepare your data**  
Place your Head and Neck CT Scans into the appropriate directories:
- Images: `2D UNet/Input/images`
- Masks for the images: `2D UNet/Input/masks`

3. **Train the model**  
Start the training process by running the following command:
```sh
   python train.py
```



 ### UNet-R

Follow these steps to set up and run the UNet-R project:

1. **Install the requirements**  
   Use the command below to install the necessary libraries from the requirements file:
  ```sh
   pip install -r requirements.txt
  ```
3. **Prepare your data**  
Place your Head and Neck CT Scans into the appropriate directories:
- Images: `UNet-R/Input/images`
- Masks for the images: `UNet-R/Input/masks`

3. **Train the model**  
Start the training process by running the following command:
```sh
   python train.py
```

### Sample Data
![alt text](https://github.com/Amadeo0312/Automated-Mandible-Segmentation/blob/main/ReadMe-Images/Sample%20Data.png)

## Architecture:
### 2D UNet
The 2D UNet is a convolutional neural network architecture designed for precise image segmentation, featuring a distinctive U-shaped structure with skip connections that enable detailed analysis with fewer training samples, particularly in medical imaging.
![alt text](https://github.com/Amadeo0312/Automated-Mandible-Segmentation/blob/main/ReadMe-Images/2dUnet.jpg)

### UNet-R
UNet-R is a modified version of the original UNet architecture, incorporating residual connections to improve learning and performance in deep networks for more accurate biomedical image segmentation.
![alt text](https://github.com/Amadeo0312/Automated-Mandible-Segmentation/blob/main/ReadMe-Images/Unet-r.png)



## Research Poster:
![alt text](https://github.com/Amadeo0312/Automated-Mandible-Segmentation/blob/main/ReadMe-Images/poster.jpg)


## Researchers
![alt text](https://github.com/Amadeo0312/Automated-Mandible-Segmentation/blob/main/ReadMe-Images/researchers.jpg)
