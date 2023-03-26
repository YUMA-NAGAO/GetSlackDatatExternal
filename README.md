# GetSlackDatatExternal
You will be able to retrieve Slack data using Slack's API.


This code uses the Slack API to collect messages made on each Slack channel, store them in a pandas data frame, and download them as a csv file. The code details are as follows

1. Use the Slack API to get a list of channels and get the ID and name of each channel.
2. For each channel, use the API to retrieve the messages made on that channel. It also retrieves messages within a thread.
3. Organize and save the retrieved messages into a pandas data frame.
4. Download the saved data frame as a csv file.


The overall code flow is a process of collecting data using the Slack API, organizing the data using pandas, and saving it as a csv file. Finally, the downloaded csv file can be used to analyze and report on the communication that took place in the channel.


If you want to create a Python environment, use Google Colabratory.
We've created an easy to run environment for you.

[Click here to see the finished product.](https://colab.research.google.com/drive/17jvGzuTT8xct3WJOCDOXIGKlXz_APrKC#scrollTo=u9Poam6bfECu)
