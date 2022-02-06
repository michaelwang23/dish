# GCP Info
Project name: Dish
Project number: 469165124831
Project ID: dish-340506

# Install the latest node package! Make sure npm run works.

# Install the gcloud CLI: https://cloud.google.com/sdk/docs/install

# Setup your gcloud CLI 
Type gcloud auth login, press enter
Sign in to the google account using email: dishfood01@gmail.com, password: [our favorite blind user]!!
Type gcloud config set project, press enter
Type gcloud services enable appengine.googleapis.com, press enter

# Test if it works locally
npm start

# Deploy to cloud 
npm build 
gcloud app deploy --project=dish-340506 --quiet
gcloud app browse -s 



