# legendary-giggle: A Background Removal Tool with U-2-Net

## Overview

This is a background removal tool based on the U-2-Net model, designed for efficient and accurate segmentation of objects within images. The tool takes an input image and outputs a version with the background removed, providing a clean and isolated foreground.

- *U-2-Net Model:* Utilizes the U-2-Net architecture for image segmentation.

## Requirements

- Python 3.x
- Dependencies listed in requirements.txt

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ShivamMadlani/legendary-giggle
    cd legendary-giggle
    ```
    

2. Install dependencies(if running on a local machine):

    ```bash
    pip install -r requirements.txt
    ```
 
3. Download u2net model:

    - Download the model from [here](https://drive.google.com/file/d/1ao1ovG1Qtx4b7EoskHXmi2E9rp5CHLcZ/view)
    - paste the downloaded file `u2net.pth` in `saved_models/u2net`

## Usage

1. Run the background removal tool:

    ```bash
    python main.py
    ```

2. Add the images into the `test_data/images/input` folder.
3. The masked images will be generated inside `test_data/images/u2net_results`.
4. The isolated image will be generated in `test_data/images/outpur` folder.

## Acknowledgments

- U-2-Net Model: [Link to U-2-Net Repository](https://github.com/xuebinqin/U-2-Net)
