## Color For You: Walmart -Intergrating color analysis with shopping 
The project aims to digitize traditional Korean season/color analysis using AI, machine learning, and computer vision. Users can upload photos to a platform where the system analyzes their complexion and facial features. Through selfie segmentation, face detection, and KMeans clustering, the system identifies prominent colors and converts them to HSL values to determine the user's color profile. The user is categorized into one of twelve seasonal color profiles, each linked to specific palettes and Walmart shopping recommendations. This approach democratizes professional fashion advice, making it accessible to a wider audience, particularly those in remote areas, while driving traffic to Walmart.

## Feature
1.Image Upload: Upload an image to detect dominant colors and segment the image.
2.Face Detection: Detects faces in the uploaded image and crops to the first detected face.
3.Color Detection: Identifies dominant colors in the cropped face image and excludes gray colors.
4.Color Palette Recommendation: Provides a recommended color palette based on 12-season color theory.
5.Personalized Shopping: Display clothing items in the Myntra website that match the user's selected filters and recommended color palette


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Sanika1710/Walmart-Color-Palatte.git
    cd Walmart-Color-Palatte
    ```

2. Install the required dependencies:
   * Create a virtual environment
     ```bash
     python -m venv venv
    
    * Activate the virtual environment
      ```bash
      source venv/bin/activate
      
    * Install the dependencies
    ```bash
    pip install -r requirements.txt
## Dependencies
OpenCV
MediaPipe
Streamlit
NumPy
Pillow
scikit-learn
Pandas

  
