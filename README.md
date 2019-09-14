# dotnet-oauth-example

A simple example to show how to perform OAuth authentication with Google APIs in C#/.Net.

## Instructions

* Install .Net if you haven't already.
* Download this repo onto your workstation.
* Login to Google and create a Cloud Platform account and project, if you don't already have one.
* Enable the [Google Books API](https://console.developers.google.com/apis/api/books.googleapis.com/overview) used in this example.
* Go to the [Google APIs Console](https://console.developers.google.com/apis/credentials).
* Click *Create Credentials* and choose *OAuth Client ID*.
* Choose "Other", enter a memorable name, and click *Create*.
* Click *OK* - you don't need these details.
* Back on the Console screen, click the download icon on the far right of the screen next to the client ID you just created.  This downloads a JSON file to your workstation.
* Move it into the folder which contains this README file.
* At the command prompt in the same folder, type `dotnet run` to run the program.
* Follow the instructions on the screen, which will direct you to visit a URL, give your consent for this app to use your Google Books data, and then send a message to this app with authentication information.
* You should then see a list of your bookshelves in Google Books printed in console output.

Note that this very simple example runs at the terminal.  OAuth handles web and mobile applications too, but the code is slightly different.

## How does it work?

* Find out more about OAuth [here](https://www.varonis.com/blog/what-is-oauth/).
* Instructions on how to use the Google OAuth client in .Net are [here](https://developers.google.com/identity/protocols/OAuth2InstalledApp).
* Documentation for the Google Books API is [here](https://googleapis.dev/dotnet/Google.Apis.Books.v1/latest/api/Google.Apis.Books.v1.html).
