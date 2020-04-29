# bitrise-fan-out-sample
Simple example of using bitrise to run parallel iOS tests

## Step 1

Fork the following repository into your own GitHub account

- https://github.com/coletiv/medium-ios-automated-testing-fastlane

## Step 2

Add a new app to Bitrise using the repository you forked above

- https://devcenter.bitrise.io/getting-started/adding-a-new-app/

## Step 3

Update the apps bitrise.yml with the contents of the bitrise.yml in this repository. You can edit the bitrise.yml directly by going to your apps Workflow Editor and clicking the bitrise.yml tab.

## Step 4

Generate a Personal Access Token following the guide here: 

- https://devcenter.bitrise.io/getting-started/account-security/#generating-personal-access-tokens-manually

## Step 5

Start a build of the primary workflow of the app just added to Bitrise
