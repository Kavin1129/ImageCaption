
# Image Caption Generation

This project involves generating captions for images using a machine learning model. The model is designed to provide descriptive text for images, but please note that it is not perfect due to limitations in computational power.


## Model

The model used for generating captions is approximately 500 MB in size. You can download the saved model using the following link:

https://drive.google.com/drive/folders/12Jv3gNo1WWS3RfmkPUGCt-3TEUArTma3?usp=sharing

## Installation

Ensure you have a Python environment set up. The requirements.txt file contains the necessary libraries. Please note that this file includes libraries from a previous project and might not be fully optimized for this project. If you encounter any issues with library versions or dependencies, you may need to manually adjust them.

```bash
git clone https://github.com/Kavin1129/ImageCaption.git
```

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

```bash
pip install -r requirements.txt
```
Download the saved model and place it in the appropriate directory as indicated in the project documentation.

After downloading all the necessary libraries and model, run the following command:
```bash
uvicorn app:app --reload
```
## Screenshots

![Screenshot 2024-09-18 144055](https://github.com/user-attachments/assets/bc08accf-89f4-48ea-9e75-d06122cd2644)

