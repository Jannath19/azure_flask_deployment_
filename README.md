# Azure Flask Deployment

Flask application deployment guide

## Step 1: Create Your Flask Application

1. Create your Flask application in Google Cloud Shell.
2. Make sure you have the necessary files in your project directory, including `app.py`, `requirements.txt`, and HTML files (e.g., `about.html`, `base.html`, and `data.html`) with the corresponding content for your app.

## Step 2: Test Your App Locally

1. In the Cloud Shell terminal, run your Flask app by typing `python app.py`.
2. Verify that your app works as expected.

## Step 3: Install Azure CLI

1. Install Azure CLI by running the command: curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash


2. Test the installation by typing `az` in the terminal.

## Step 4: Azure Login

1. Log in to Azure by typing: az login --use-device-code

2. Follow the provided link, sign in with your email, and enter the authentication code displayed in the terminal.

## Step 5: Redeem Azure Student Subscription ID


## Step 6: Create a Resource Group

1. In the Azure web portal, search for "resource groups" and create a new resource group.

2. Ensure the subscription is set to 'Azure for Students' and choose a unique name without special characters or spaces.

## Step 7: Configure Your Azure Web App

1. In Cloud Shell, run the command: az webapp --resource-group <group-name> --name <app-name> --runtime PYTHON|3.9 --sku B1
2. Make sure you are in the right directory containing your Flask app.

## Step 8: Deploy Your App

1. Deploy your app to Azure by running: az webapp up

## Step 9: Backup Your Work on GitHub


## Step 10: Access Your Deployed Flask App

Your Flask application is now live






