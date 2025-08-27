# Sleep Quality & Cycle Finder App

A machine learning-powered web application that predicts sleep quality and provides personalized recommendations for better sleep based on lifestyle factors.

## 🌟 Features

- **Sleep Quality Prediction**: Uses a trained Random Forest model to predict sleep quality based on multiple lifestyle factors
- **Sleep Cycle Calculator**: Estimates the number of complete sleep cycles (90-minute cycles) based on sleep duration
- **Personalized Recommendations**: Provides actionable tips to improve sleep quality based on your input data
- **Interactive Web Interface**: Built with Streamlit for an intuitive user experience
- **Real-time Analysis**: Instant predictions and suggestions as you adjust the input parameters

## 🔬 How It Works

The app analyzes five key lifestyle factors to predict sleep quality:

1. **Sleep Duration** (4-10 hours) - Total time spent sleeping
2. **Physical Activity Level** (1-10 scale) - Daily exercise intensity
3. **Daily Steps** (1,000-20,000) - Total steps taken per day
4. **Heart Rate** (40-120 bpm) - Resting heart rate
5. **Stress Level** (1-10 scale) - Daily stress assessment

The machine learning model was trained on a comprehensive sleep health dataset and uses a Random Forest Classifier to make predictions.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Sleep_quality_App-main
   ```

2. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   streamlit run app.py
   ```

4. **Open your browser**
   Navigate to `http://localhost:8501` to access the app

## 📱 Usage

1. **Adjust the sliders** to match your current lifestyle:
   - Set your average sleep duration
   - Rate your physical activity level
   - Input your daily step count
   - Enter your resting heart rate
   - Assess your stress level

2. **View Results**:
   - **Predicted Sleep Quality**: The model's prediction of your sleep quality
   - **Estimated Sleep Cycles**: Number of complete 90-minute sleep cycles
   - **Improvement Tips**: Personalized recommendations based on your inputs

3. **Optimize Your Sleep**: Use the provided tips to make lifestyle adjustments for better sleep quality

## 🏗️ Project Structure

```
Sleep_quality_App-main/
├── app.py              # Main Streamlit application
├── model.py            # Model loading and prediction interface
├── sleep_model.py      # Model training and evaluation script
├── utils.py            # Utility functions for calculations and tips
├── requirements.txt    # Python dependencies
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## 🔧 Technical Details

- **Framework**: Streamlit for the web interface
- **Machine Learning**: Scikit-learn Random Forest Classifier
- **Data Processing**: Pandas for data manipulation
- **Model Persistence**: Joblib for model serialization
- **Features**: 5 numerical features for sleep quality prediction

## 📊 Model Performance

The Random Forest model is trained on a comprehensive sleep health dataset and provides:
- Sleep quality classification based on lifestyle factors
- Personalized improvement recommendations
- Sleep cycle calculations (90-minute cycles)

## 🎯 Target Users

- **Health Enthusiasts**: People looking to optimize their sleep quality
- **Fitness Trackers**: Users with wearable devices tracking sleep and activity
- **Wellness Seekers**: Individuals interested in improving their overall well-being
- **Sleep Researchers**: Anyone curious about the relationship between lifestyle and sleep

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## ⚠️ Disclaimer

This application is for educational and informational purposes only. It should not be considered as medical advice. Always consult with healthcare professionals for sleep-related concerns.

## 🔮 Future Enhancements

- Integration with wearable device APIs
- Sleep tracking over time
- Advanced analytics and trends
- Mobile app version
- Multi-language support
- Export functionality for sleep reports

---

**Happy Sleeping! 💤✨**  
