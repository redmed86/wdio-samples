# WDIO Samples

Demo project to understand WDIO configuration both for local chrome execution and localhost execution on Browserstack. You must have NodeJS installed on your system for this demo to work.

## Starting the Application

To start the application locally simply run:

1. `npm i`
2. `npm run dev`

## To run WDIO locally against chrome

This project is setup to run against chrome 89. If you have a different version on your local system update the `"chromedriver": "^89",` key:value in the `package.json` to match your system version. You can find that information here, [Chromedriver Docs](https://sites.google.com/a/chromium.org/chromedriver/downloads).
