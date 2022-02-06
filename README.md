# Onboarding
Install the latest node package! Make sure npm run works. <br/>
Install the gcloud CLI: https://cloud.google.com/sdk/docs/install <br/>
gcloud auth login <br/>
Sign in to the google account using email: dishfood01@gmail.com, password: [our favorite blind user]!! <br/>
gcloud config set project <br/>
gcloud services enable appengine.googleapis.com <br/>

# Test locally
npm start <br/>
 
# Deploy to cloud 
npm run build <br/>
gcloud app deploy --project=dish-340506 --quiet <br/>
gcloud app browse <br/>



