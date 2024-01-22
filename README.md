# Book-Challenge-Helper

This is a helper for the 52 Book Club's 2024 Book Challenge.
<br>The link to the challenge can be found [here](https://www.the52book.club/2024-reading-challenge/).
<br>The helper is a python notebook that uses basic web scraping to parse through the Goodreads list for all the various prompts. This is to enter any book name you wish to look for as input and get a list of all the prompts in the challenge it is suitable for. 

I have added the notebook file here. To run the notebook, upload it to your personal google colab [here](https://colab.research.google.com/). Wait for the connection to be made to the server and go to Runtime -> Run all to run the notebook. Name of the book and author can be entered when prompted. The categories will be printed in the end.

In case you encounter library issues, install requests and beautifulsoup using pip command by adding the following commands before import statements:
<br>`pip install requests`
<br>`pip install beautifulsoup4`
