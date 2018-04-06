# Twitter
#Getting started To collect data you need a Twitter account and a Twitter application. Assuming you already have a Twitter account use the following instructions to create a Twitter application

##Twitter application

Open a web browser and go to https://apps.twitter.com/app/new
Sign in with your normal Twitter username and password if you are not already signed in.
Enter a name, description, and temporary website (e.g. http://coming-soon.com)
Read and accept the terms and conditions – note principally that you agree not to distribute any of the raw tweet data and to delete tweets from your collection if they should be deleted from Twitter in the future.
Click "Create your Twitter application"
Click on the "API Keys" tab and then click "Create my access token"
Wait a minute or two and press your browser's refresh button (or ctrl+r / cmd+r)
You should now see new fields labeled "Access token" and "Access token secret" at the bottom of the page.
You now have a Twitter application that can act on behalf of your Twitter user to read data from Twitter.
##Connect your Twitter application to these scripts

1.Download the code in the repository if you haven't already
2.Open the auth_example.py file in a text editor (gedit, kate, notepad, textmate, etc.)
3.Update the following lines with the information displayed in the web browser for your application:
    consumer_key="..." #Note this is now called API key	
    consumer_secret="..." #Note this is now called API secret
    access_token="..." 
    access_token_secret="...."
    #Replace the … with whatever values are shown in your web browser. Be sure to keep the quotation marks.
4.Save the file as auth.py (not the same name as before)
