# SafePayAI - Fraud Detection Using GAN

## Installation & Running the Project

### Frontend Setup
1. Navigate to the Frontend directory:
   ```bash
   cd fraudAI_Frontend_React
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open the app in your browser at [http://localhost:3000](http://localhost:3000).

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd AI_model_server_Flask
   ```
2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure the trained model file `best_rf_model.pkl` is present in the directory.
4. Start the Flask server:
   ```bash
   python app.py
   ```
5. The API will be accessible at [http://127.0.0.1:5000/](http://127.0.0.1:5000/).
