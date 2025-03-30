# AROGAYA-NETRA-VASISTHA

## Problem Statement
In today's world, understanding the nutritional value of food is becoming increasingly complex. Consumers face several challenges:

- **Information Overload**: Nutrition labels are difficult to interpret for the average consumer.
- **Lack of Personalization**: Most nutrition apps don't account for individual dietary needs or allergies.
- **Fragmented Knowledge**: No single source provides comprehensive analysis of food items with actionable recommendations.
- **Limited Tracking**: Traditional food journals lack detailed nutritional insights and health impact evaluation.
- **Health Impact Uncertainty**: Most people struggle to understand the long-term health implications of their food choices.

**FoodBar** addresses these challenges by providing an intuitive, AI-powered solution for nutritional analysis and health tracking.

---

### Demo Video link:
https://drive.google.com/file/d/1H3xI2EpKO8uOwQqK3p7T7cf75JhFzI7L/view?usp=drivesdk

## To see working view of our app on your mobile/system, download the apk available in APK folder.

## Team Members
- **G Naga Vamshi** 
- **Chris Mathew** 
- **P V L Narasimha Naidu** 
- **S Advaith Ressy** 

---

## Solution
FoodBar is a comprehensive mobile application that transforms how users understand and interact with nutritional information. Our solution offers:

### Key Features

#### Multi-Modal Food Recognition
- Label scanning for packaged foods.
- Image recognition for meals and unpackaged foods.
- Barcode scanning for quick product identification.
- Manual food entry with AI-assisted nutritional calculation.

#### Advanced Nutritional Analysis
- Detailed breakdown of macro and micronutrients.
- "Netra Ranks" health scoring system with visual indicators.
- Personalized allergen alerts and warnings.
- Assessment of positive and negative nutritional factors.

#### Personalized Health Insights
- Custom allergen profiles for individual safety.
- Daily intake tracking with nutritional balance visualization.
- Contextual recommendations for nutritional improvement.
- Historical analysis with multi-dimensional filtering.

#### Culturally-Informed Health Scoring
- Sanskrit-inspired tiered ranking system: **Amrit, Prana, Shakti, Santulit, Saadharan, Vishakt**.
- Comprehensive **0-100** scoring based on holistic nutritional evaluation.
- Visual representation of health scores with intuitive color coding.
- Detailed explanations of health impacts and recommendations.

---

## Technologies Used
- **Flutter** for cross-platform development.
- **Google's Gemini AI** for advanced image recognition and nutritional analysis.
- **Shared Preferences** for local data storage.
- **Material Design 3** for modern UI components.
- **Custom health scoring algorithms** for nutritional evaluation.

---

## Getting Started

### Prerequisites
- **Flutter SDK** (version 3.0 or higher)
- **Android Studio / VS Code** with Flutter plugins
- **Git**
- **Google API key** for Gemini AI

### Installation
```bash
# Clone the repository
git clone https://github.com/your-repo/foodbar.git
cd foodbar

# Set up environment variables
# Create a .env file in the project root with the following content:
GOOGLE_API_KEY=your_google_api_key

# Install dependencies
flutter pub get

# Run the app
flutter run
```

---

## Project Structure
```
foodbar/
│── lib/
│   ├── main.dart                 # Application entry point
│   ├── logic.dart                 # Core business logic and state management
│   ├── my_home_page.dart          # Main UI components and screens
│   ├── models/                    # Data models for food items, health scores, etc.
│   ├── screens/                    # Different app screens
│   ├── widgets/                    # Reusable UI components
│   ├── services/                   # Service classes for external APIs and calculations
│   ├── utils/                      # Utility functions and helpers
│   ├── data/                       # Static data and constants
│── .env                            # Environment variables (not committed to repo)
│── pubspec.yaml                    # Flutter dependencies and configurations
│── README.md                       # Documentation
```

---

## What you can see
### We added only the required files required to run this app.

## How to Use

### 1. Label Scanning
- Tap the **"Scan"** button on the home screen.
- Select **"Label Scan"** option.
- Point your camera at a nutrition label.
- Review the detailed analysis, including health score and nutrient breakdown.
- Add to your daily intake if desired.

### 2. Food Scanning
- Tap the **"Scan"** button on the home screen.
- Select **"Food Scan"** option.
- Take a photo of your meal.
- Review the AI-generated nutritional breakdown.
- Adjust portions if needed and add to daily intake.

### 3. Daily Intake Tracking
- Navigate to the **"Daily Intake"** tab.
- View summary of daily nutrient consumption.
- See visual representation of nutritional balance.
- Review individual food items consumed.

### 4. Food History
- Navigate to the **"History"** tab.
- Filter history by date, health score, or allergens.
- View detailed information for each food item.
- Analyze trends in your nutritional habits.

### 5. Allergen Management
- Tap the allergen warning icon in the top bar.
- Set up your personal allergen profile.
- Receive automatic warnings when scanning foods with your allergens.
- View allergen details in food analysis.

---

## You can find gemini api key in *.env* file which we used in our app for chatbot.
## You can see the requirements required in this project in requirements.txt file.

## Future Enhancements
- Integration with wearable devices for health metric correlation.
- Social sharing features for healthy meal suggestions.
- Meal planning based on nutritional goals.
- Expanded database of regional and cultural foods.
- Integration with grocery delivery services.

---

## Acknowledgments
- **Google** for the Gemini AI platform.
- **Flutter team** for the SDK.
- **USDA Food Database** for nutritional reference data.
