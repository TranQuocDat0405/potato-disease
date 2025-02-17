# Potato Disease
This project helps farmers classify whether a plant is diseased by analyzing images of its leaves. This supports meticulous cultivation and plant care, enabling early disease detection for timely intervention.
## Folder Structure
1. `training/`:
   - Contains the code for training models using deep learning.
   - Contains the `PlantVillage` data for training and testing.
2. `save_models/`:
   - Stores the saved models.
3. `frontend/`:
   - Contains the code for website
4. Root Directory:
   - Contains the FastAPI server code (`main.py`).
## Setup Instructions
1. Install Dependencies: Make sure you have Python installed on your system. Install the required Python libraries by running the following command:
   ```
   pip install -r requirements.txt
   ```
2. Run the FastAPI Server: To start the server, use the following command:
   - Run website
   ```
    cd frontend
    npm start
   ```
   
    - Run backend
    ```
    cd api
    python main.py
    ```
## Usage
Upload an image file to the FastAPI endpoint for classification.

The output will include the classification accuracy and the identified disease affecting the plant.
