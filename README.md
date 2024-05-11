# 👋 Welcome to Salama Mama!

## About Salama Mama
Salama Mama is an innovative digital platform designed to assist new mothers dealing with postpartum depression (PPD) using artificial intelligence technology. This intelligent application offers soothing conversations, relevant insights, and customized resources according to each user's unique situation and requirements. With a focus on Goal 3: Good Health & Well-being, Goal 10: Reduced Inequalities, and Goal 4: Quality Education as part of the United Nations' Sustainable Development Goals, Salama Mama strives to make a lasting positive impact on users and their communities. The app serves as a secure haven for new mothers seeking assistance with their mental health during the critical postpartum phase by offering personalized data and aid, thereby promoting self-efficacy and resiliency amidst challenges.

## Inspiration
Our team identified the significant challenge faced by many women struggling with postpartum depression, especially among underrepresented communities lacking adequate mental health care resources. Expensive treatments and therapies often hinder these individuals from obtaining essential support during such vulnerable times. Recognizing the potential impact of combining our expertise and innovative minds, we resolved to develop creative solutions capable of providing global assistance to women dealing with postpartum depression. Ultimately, our goal is aligned with UN Sustainable Development Goals (SDGs) 3—Good Health and Well-being and SDG 10—Reduced Inequalities, aiming to bridge gaps and empower underserved populations worldwide and Reducing Inequalities for marginalized populations suffering from postpartum depression.

## ⚙ What it does -
- Mood Tracking: Allows users to log and monitor changes in their mood over time. Providing insights into patterns and trends helps users understand fluctuations in their emotional states.

- Dynamic Feed Content: Offers customized content tailored to individual users, including activities, educational materials, and curated articles intended to encourage, educate, and inspire users towards improvement.
  
- Personalized User Story Preferences: Enables users to select topics they resonate with or face difficulties in order to display relatable experiences shared by others navigating similar issues.
  
- Motivational Quotes: Presents daily inspirational quotes carefully selected to boost morale and instill hope amid challenging circumstances.
Accessibility – Text-to-Speech Functionality: Caters to differently-abled users by delivering core information via synthesized voices, enhancing overall inclusivity and experience.

## 💪 Challenges we ran into -
The model was overwriting previous prompts which gave us a challenge during text to speech generation when two or more prompts were available.

## 📌 Accomplishments that we're proud of -
We are proud of the entire system as a whole and our heart is fully content to choose one feature over the other.

## 📚 What we learned -
We learnt how to use GitHub & conventional commits, using Gemini AI API, prompt engineering, text-to-speech, team collaboration and personalization with AI.

## ⏭ What's next for -
- Helping the user set goals for the day
- Creating mailing lists and notification
- Having a statisics created for the moods over a week
- Reverse prompting the AI

## Getting Started

Follow these instructions to set up the Salama Mama project on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following prerequisites installed:
- Firebase CLI: To install and initialize Firebase in your project, follow the instructions provided by Firebase here: <https://firebase.google.com/docs/cli#installation>.
  
- Python 3.8 or higher: Make sure that you have Python 3.8 or a later version installed on your system. You can download it from the official website: <https://www.python.org/downloads/>.
pip: This is the package manager for Python. It comes bundled with recent versions of Python. If not, you can install it from here: <https://pip.pypa.io/en/stable/installing/>.

  - Virtual Environment: It is recommended to use virtual environments while working with Python projects. Create one using venv as follows: python -m venv env. Activate it using the appropriate command based on your operating system. For Windows, run .\env\Scripts\activate, and for Linux/MacOS, run source env/bin/activate.
  - Required Packages: Once the virtual environment is activated, install the required packages using pip: pip install flask flask-cors requests google-cloud-storage google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client google-cloud-texttospeech

-Google Cloud SDK: Follow the instructions provided by Google to set up the SDK: <https://cloud.google.com/sdk/docs/install>
  - Service Account Key: Create a service account key for your Google Cloud Platform (GCP) project and save the JSON file locally. Refer to these steps: <https://cloud.google.com/iam/docs/creating-managing-service-account-keys#creating_service_account_keys>

### Installation Guide

#### Clone the Repositories

```bash
git@github.com:SalamaMama/.github.git

```

#### Backend and YouTube Microservices Setup

```bash
cd backend
pip install -r requirements.txt
python app.py  # Runs the Flask server
```

#### Frontend Setup

```bash
cd frontend  # Assuming you're in the root directory
npm install   # Install dependencies
npm run dev   # Start the development server
```

Ensure you follow the notebook instructions for running the model and generating text. Install any necessary dependencies as specified within the notebook or the repository's documentation.

### Firebase and Other Services Setup

Set up your Firebase project and ensure the `firebase.jsx` file in the frontend directory is updated with your Firebase configuration keys.

# Technical Details
## Technology Stack

- **Frontend:** React (JavaScript)
- **Backend:** Flask (Python 3.8+) | Flask-CORS | Requests | google.generativeai | gtts
- **AI Model:** Firebase Firestone
- **Database & Authentication:** Firebase
- - **Generative Models Endpoint Consumption:** Backend server hosted on Render.com
- **Component Library:** Flowbite

## How to Use

After initiating the frontend and backend servers, open http://localhost:5173 to access the Salama Mama web application. Users can engage with the interactive frontend for recommendations tailored to their needs.

For immediate access, visit our live platform at [Salama Mama](https://salama-mama.vercel.app/)

## Contributing

Your contributions to Salama Mama are highly appreciated. Whether you're improving the application or reporting bugs, please feel free to open an issue or submit a pull request.

## License

Salama Mama is made governed by terms and conditioned outlined in MIT License. For more details, see the [LICENSE.md](LICENSE) file. Any usage must comply strictly with the licence agreement.

## Acknowledgments

We extend our gratitude to all individuals and organizations whose contributions have made Salama Mama a reality. Special thanks to our dedicated team members for their relentless effort and innovation:

- **Danroy Mwangi** 
- **Nelson Kamau** 
- **Samson Mokaya Ongera**
- **Nicole Ngina**

Together, we continue to strive towards making a significant impact on the well-being of new mothers worldwide.
