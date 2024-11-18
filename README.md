# Brain-Tumor-Classification

A deep learning project that uses both Xception and custom CNN models to classify brain tumors from MRI images.

## 🚀 Quick Start

### Google Colab Setup
1. Download the notebook
2. Open [Google Colab](https://colab.research.google.com/)
3. Upload the notebook
4. Set runtime to T4 GPU:
   - Runtime -> Change runtime type -> T4 GPU
   - This significantly reduces training time

### 🏃‍♂️ Running the Project

#### Model Training
The project trains two models:
1. **Xception Model** 
   - Runs for 5-10 epochs
   - Saves as `xception_model.weights.h5`

2. **Custom CNN Model**
   - Runs for 10-12 epochs
   - Saves as `cnn_model.h5`

> ⚠️ Both model files are required for the Streamlit application

#### Environment Setup
1. Create a `.env` file
2. Add your Google AI API key:
   ```
   GOOGLE_AI_API_KEY=your_key_here
   ```
   > Note: Remember to comment out the API key code cell after running

#### Running Streamlit App
1. Ensure you have both model files (`xception_model.weights.h5` and `cnn_model.h5`)
2. Run the OS library imports at the notebook start
3. Execute the Streamlit cells
4. Access the app through the ngrok-generated link

## 🔍 View Complete Code
If the Colab notebook isn't loading in GitHub:
1. Visit [nbviewer.org](https://nbviewer.org/)
2. Paste the GitHub notebook URL
3. View the fully rendered notebook

## 🛠️ Prerequisites
- Python 3.x
- TensorFlow
- Streamlit
- Google Colab account
- `.env` file with Google AI API key

## ❗ Important Notes
- Keep API key secure and commented out when not in use
- Both model files must be present for Streamlit app functionality
- GPU runtime is recommended for optimal performance

## 📫 Support
If you encounter any issues or have questions, please open an issue in this repository.
