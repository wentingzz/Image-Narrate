# Image Narrate

Image Narrate is a web application that generates captions for uploaded images. It uses a pre-trained natural language processing (NLP) model to analyze the content of the image and generate a descriptive caption.

## Features

- **Image Upload**: Users can upload images in various formats.
- **Caption Generation**: The system generates a descriptive caption for the uploaded image.
- **Image URL**: User can paste url of image to get the caption. 

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/wentingzz/image-narrate.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```
   

## Usage
1. Run the application:

    ```bash
    python image_narrate_blip_transfomers.py
     ```
2. Open the application in your web browser.
3. Upload an image.
4. Click the "Submit" button. The system will process the image and display a descriptive caption.

## Technologies Used

- **Langchain**: A library for building and managing language model pipelines.
- **Hugging Face Transformers**: For natural language processing tasks.
- **IBM Watson Machine Learning**: For model deployment and management.
- **IBM WatsonxLLM Extension**: An extension for managing language model pipelines.
