## Auto-Kudos
An app to automate giving kudos to your followings. Uses the strava api, with custom features like:
- Authomatic token refreshment
- Dry run mode to view recent activites
- Adjust time range for recent acitivites

## Requirments 
The application requires Python 3.7 or newer and the following Python packages:
*   [`requests`](pypi.org) for making API calls.
*   [`flask`](pypi.org) for handling the initial OAuth callback server.


### Installation
Install the required dependencies using pip:
```bash
pip install requests flask
```

### Usage
#### 1. Register a Strava API Application
- You need to create a free API application within your Strava account settings to get credentials.
- Go to the Strava API Settings page.
- Click "Create Your App".
- Fill in the details:-
- Application Name: Auto Kudos Bot (or whatever you choose).
- Authorization Callback Domain: localhost
- Website: http://localhost:8000
- Save, and note the client ID and Client Secret.

#### 2. Set Environment Variables
- Set your Client ID and Client Secret as environment variables in your terminal. This is safer than hardcoding them in the script.
```bash
export CLIENT_ID=" "
export CLIENT_SECRET=" "
```

#### 3. Set Oauth 
- https://github.com/django-oauth/django-oauth-toolkit

