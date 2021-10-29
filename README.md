# iPhone13ProInventory
Checks if iPhone 13 Pro is in inventory, on "Mahsaney Hashmal"

I run this on my Windows PC, with Jupyter Notebook. (it didn't work for me on a remote notebook)

Enter your gmail email, and your gmail app password on the top of the notebook
<b>MY_EMAIL</b> and <b>MY_GMAIL_APP_PASSWORD</b> respectively.

The <b>site</b> variable below is the url that gives me only the iPhone 13 Pro with 128GB storage, you can change it to any other filtering you want.

This program will send an email if any of the items on the page is in stock, scraping the webpage every 5 minutes. If it finds any item in stock it will also stop running. Time between each scraping can be changed on the last line inside time.sleep.

Enjoy!
