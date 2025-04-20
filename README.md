# IPL Win Predictor

A machine learning-powered web app built with *Streamlit* that predicts the winner of an IPL match based on match conditions like batting team, bowling team, venue, and target.

# Live Demo

 🌐 <a href="https://ipl-win-predictor-by-sk.streamlit.app" target="_blank" alt="Broken link">Try now..</a>


# Features

- Predicts match outcome using a trained ML model
- Sleek, interactive UI built with *Streamlit*
- Real-time data input and instant prediction
- Uses historical IPL match data (`matches.csv`, `deliveries.csv`)
- Deployable on *Streamlit Cloud*


# Tech Stack

| Component      | Technology       |
|----------------|-------------------|
| Frontend       | Streamlit         |
| Backend        | Python            |
| ML Model       | Scikit-Learn      |
| Data Handling  | Pandas            |
| Deployment     | Streamlit Cloud   |


---

# How to Run Locally

1. Clone this repo:
   ```bash
   git clone https://github.com/shivkumars005/IPL-Win-Predictor.git
   cd IPL-Win-Predictor
   pip install -r requirements.txt
   streamlit run app.py

# How It Works
  Data from matches.csv and deliveries.csv is used to train a pipeline.
  The trained model is saved as pipe.pkl.
  The app.py loads the model and takes user input via a Streamlit UI.
  Prediction is based on real-time inputs like current score, overs, target, and teams.

# Acknowledgements
  Kaggle (Datasets)
  YouTube
  
# Contact
  Made with ❤️ by Shiva Kumar Souta
  📧 Reach me at: shivakumarsouta18@gmail.com
  🌐 <a href="https://shivakumarsouta-portfolio.vercel.app/" target="_blank" alt="Broken Link">Visit My Portfolio</a>
