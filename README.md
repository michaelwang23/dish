# GCP Info
Project name: Dish <br />
Project number: 469165124831 <br />
Project ID: dish-340506 <br />

# Install the latest node package! Make sure npm run works.

# Install the gcloud CLI: <br />
https://cloud.google.com/sdk/docs/install  

# Setup your gcloud CLI 
Type gcloud auth login, press enter <br />
Sign in to the google account using email: dishfood01@gmail.com, password: [our favorite blind user]!! <br />
Type gcloud config set project, press enter <br />
Type gcloud services enable appengine.googleapis.com, press enter <br />

# Test if it works locally
npm start <br />
 
# Deploy to cloud 
npm build <br />
gcloud app deploy --project=dish-340506 --quiet <br />
gcloud app browse -s <br />



