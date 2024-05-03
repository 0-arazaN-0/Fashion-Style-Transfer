# Fashion Style Transfer

Fashion Style Transfer is an innovative project aimed at integrating artistic styles with clothing designs. Leveraging deep learning techniques, the project enables users to apply style transfer to clothing images while preserving their original shape and structure.

## Key Features

- Interactive clothing style transfer: Users can selectively apply artistic styles to specific regions of clothing images using an interactive GrabCut algorithm.
- Preservation of clothing shape: The project utilizes distance transform-based outline extraction to ensure the preservation of the original shape of clothing items during style transfer.
- Efficient image processing: The VGG-19 network is employed as an image feature extractor, enhancing the accuracy and efficiency of style transfer.
- Customizable fashion designs: By combining different artistic styles with clothing images, users can generate unique and visually appealing fashion designs.

## Usage

- Upload content and style image: Upload your own content image and style image on kaggle.
- Interactive cloth selection: Change the rectangle of GrabCut algorithm to select only the cloth part from the content image.
- Generate stylized image: Rerun the code and wait for all the iterations to complete. Generated image will be stored in result_image.

## Dependencies:

- Python
- OpenCV
- NumPy
- Keras
- TensorFlow

## Installation

- [Fashion Style Transfer](https://www.kaggle.com/code/arazan/nash-cs528?kernelSessionId=174013843&authuser=5) : Link to kaggle file
- Download and install vgg-19 weight in kaggle environment.

## Contributing

Contributions to the Fashion Style Transfer project are welcome! If you have any ideas for improvements or new features, feel free to do it.
