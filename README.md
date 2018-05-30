# Twitter-Bot-Script
R script that tweet out content

The script does not compose new tweets. Instead the tweet content is sourced from previous tweets. I then strip the tweets from any user mentions and html links and then proceeed to tweet out content. To provent the account from being banned, I randomized the interval in the tweets will be sent out using modulo arithmetic. 


I have removed my own authentation keys for safte reason but you can make your own by following the steps outlined in https://iag.me/socialmedia/how-to-create-a-twitter-app-in-8-easy-steps/ and then substituting the values in the script
