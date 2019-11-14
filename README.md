# Python-trading-bot-for-XTB
Intended to be a contribution to others who want to get started automating their trades @ xtb.com and to invite collaboration to create a shared bot for real.

Disclaimer:
This project is not a recommendation to adhere to XTB, nor to get involved in trading.  It's just a contribution following the license stick to this project if you find it could benefit at your own decision, your own risk, and under the license terms (which I didn't write either).

If you are new to Python and/or an IDE for Python, I suggest you investigate first how to get started with Python from an expert or dedicated site for that matter.  I am not a Python expert but there are plenty of sites ilustrating how to get started with.

Requirements:
You may find at http://developers.xstore.pro/api/wrappers/2.5.0 two important pieces:
1. How to setup a demo account so that you play with no real money
2. How to setup the source libraries shared by XTB and binding to their terms using those libraries

What to find in this project?
Providing that the above requirements are met, my contribution is to share a sample code that actually connects to the broker and shows a few basic functions you may use if you plan to automate your own trades using Python.

Scope of functions include:
* Login / authenticate / connect to the broker
* Browsing quote history for a specific symbol (instrument)
* Calculating potential benefit for a forecasted open / close value
* Creating a dummy position
* Checking postion status
* Canceling that position
* Closing that position
* Obtaing actual balance 
* Logoff from the broker

As you may read, that is not a trading bot, just showing how to use thouse libraries shared by XTB.

If you would like to collaborate in writing a trading bot with the author of this project, feel free to share.
