# 👋 Welcome to Salama Mama!

## About Salama Mama
Salama Mama is an innovative digital platform designed to assist new mothers dealing with postpartum depression (PPD) using artificial intelligence technology. This intelligent application offers soothing conversations, relevant insights, and customized resources according to each user's unique situation and requirements. With a focus on Goal 3: Good Health & Well-being, Goal 10: Reduced Inequalities, and Goal 4: Quality Education as part of the United Nations' Sustainable Development Goals, Salama Mama strives to make a lasting positive impact on users and their communities. The app serves as a secure haven for new mothers seeking assistance with their mental health during the critical postpartum phase by offering personalized data and aid, thereby promoting self-efficacy and resiliency amidst challenges. 
Here is the link to the site: https://salama-mama.vercel.app/

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
