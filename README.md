# WDIO Samples

Demo project to understand WDIO configuration both for local chrome execution and localhost execution on Browserstack. You must have NodeJS installed on your system for this demo to work.

## Starting the Application

To start the application locally simply run:

1. Navigate to the root directory
2. `npm i`
3. `npm run dev`

## Run WDIO locally against chrome

This project is setup to run against chrome 89. If you have a different version on your local system update the `"chromedriver": "^89",` key:value in the `package.json` to match your system version. You can find that information here, [Chromedriver Docs](https://sites.google.com/a/chromium.org/chromedriver/downloads).

1. Navigate to the root directory
2. `npm run wdio-local`

## Run WDIO against localhost using Browserstack

Follow the below steps to get your evironment ready and execute on Browserstack.

1. Ensure that you have an account on Browserstack ([Browsertack Signup](https://www.browserstack.com/users/sign_up))
2. Export your Browsertack username `export BROWSERSTACK_USERNAME=<browserstack_username>`
3. Export your Browserstack Access Key `export BROWSERTACK_ACCESS_KEY=<browserstack_access_key>`
4. `npm run wdio-bs`
