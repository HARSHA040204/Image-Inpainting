
# Image Inpainting using Deep Learning (Partial CNN and U-Net)

This project focuses on image inpainting, a technique used to reconstruct missing/damaged parts of images. Leveraging deep learning, specifically Partial Convolutional Neural Networks (CNN) and U-Net architecture, this repository offers an image inpainting solution.

## Dataset
The model is trained on the [Natural Images Dataset](https://www.kaggle.com/datasets/prasunroy/natural-images) available on Kaggle. This diverse dataset comprises various categories of natural images, serving as the foundation for training our inpainting model.

## Methodology
### Partial CNN
Partial CNNs are employed for their ability to effectively handle holes or missing regions in images, ensuring accurate reconstruction while considering the context of the surrounding pixels.

### U-Net Architecture
The U-Net architecture, known for its success in image segmentation tasks, is adapted here for its prowess in capturing intricate details and features, aiding in high-quality inpainting.

## Usage
### Training
1. **Data Preparation:** Download and preprocess the Natural Images Dataset.
2. **Model Training:** Train the Partial CNN and U-Net models using the prepared dataset.

### Inpainting
The masks are created and added to original images and those are loaded to model along with mask to generate a image free from damage.

## Dependencies
Ensure the following libraries are installed to run the project:
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

## Getting Started
1. Clone this repository.
2. Download and preprocess the Natural Images Dataset from the provided Kaggle link.
3. Train the models following the instructions in the respective directories.
4. Inpaint images using the trained models.

## Acknowledgments
- The Natural Images Dataset by Prasun Roy on Kaggle.
- Inspirations and foundational concepts drawn from academic papers and existing implementations in image inpainting.

## Group Members:
- V Sai Sumanth
- D Veera Harsha Vardhan Reddy

Feel free to contact for any querys 
dveeraharshavardhanreddy@gmail.com
