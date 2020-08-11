# robinttracker
Details on Power BI workflow I built to track Robinhood user growth insights using data from Robintrack.net

Getting Started - To get started you will need to download the Power BI (.pbix) file in this repository. It is called Robinhood User Growth.pbix. Next you will need to go to robintrack.net and go to the download section and download the latest update.

In the Power BI file you will see the folder structure that I have used (I am running this on my local machine). Create a similar version on your machine. Unpack the zip file you have downloaded from Robintrack and place these CSV files from your download into the specific folder you created.

Connect Power BI load to your machines folder and hit refresh in Power BI. When a new update comes out you can go through the process again to update the Robintrack CSV's.

Power BI Updates - Feel free to create and build further on the Power BI file I have created here but please ensure you attribute original work back to me. Some things I have added into this file include a tag for what were the current list of S&P 500 tickers as of July 2020. The limitation of this is that these were not necessarily the same S&P 500 constituents back in 2018 when the Robintrack data dates back to. You will need to also download the file that has these tickers - see Tickers.xlsx and place in an appropriate folder and connect to that in Power BI.

Future improvements - My plan, time permitting is to add other features to this Power BI tracker including price information and other metrics such as sector lassifications etc. The Robintrack.net website already has price information for each ticker so if you are after that then you can look at Casey Primozic's work there.

