# python_gcalendar
Simple Python command-line application that makes requests to the Google Calendar API.

## Table of Contents
 - [Installation](#installation)
 - [Configuration](#configuration)
 - [Usage](#usage)
 - [Contributing](#contributing)
 - [References](#references)

## Installation

To run this application, you'll need:

* Python 2.6 or greater.
* The pip package management tool.
* Access to the internet and a web browser.
* A Google account with Google Calendar enabled.

Run the following command to install the library using pip:
```shell
$pip install --upgrade google-api-python-client
```
## Configuration

Turn on the Google Calendar API:
1. Use [this wizard](https://console.developers.google.com/start/api?id=calendar) to create or select a project in the Google Developers Console and automatically turn on the API. Click **Continue**, then **Go to credentials**.
2. On the **Add credentials to your project** page, click the **Cancel** button.
3. At the top of the page, select the **OAuth consent screen** tab. Select an **Email address**, enter a **Product name** if not already set, and click the **Save** button.
4. Select the **Credentials** tab, click the **Create credentials** button and select **OAuth client ID**.
5. Select the application type **Other**, enter the name "Google Calendar API Quickstart", and click the **Create** button.
6. Click **OK** to dismiss the resulting dialog.
7. Click the :arrow_down: (Download JSON) button to the right of the client ID.
8. Move this file to your working directory and rename it "client_secret.json".

## Usage

Run the application using the following command:
```shell
$python quickstart.py
```
1. The sample will attempt to open a new window or tab in your default browser. If this fails, copy the URL from the console and manually open it in your browser.

2. If you are not already logged into your Google account, you will be prompted to log in. If you are logged into multiple Google accounts, you will be asked to select one account to use for the authorization.
3. Click the **Accept** button.
4. The sample will proceed automatically, and you may close the window/tab.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## References

The following is a list of useful references used for the development of the application:
* [Google Calendar API with Python](https://developers.google.com/google-apps/calendar/quickstart/python)
* [Google Calendar API](https://developers.google.com/apis-explorer/#s/calendar/v3/)
