# Automated-Mandible-Segmentation
![alt text](https://github.com/Amadeo0312/Automated-Mandible-Segmentation/blob/main/ReadMe-Images/introduction.png)
## How to Use:

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

