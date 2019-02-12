# VendingMac
Installation details:
1)	Prerequisites:
•	Admin rights are required to install this app.
•	Microsoft dotnet framework ver. 3.5 or higher. 
•	AccessDatabaseEngine2010 (included in the installer folder).
2)	Once the AccessDatabaseEngine2010 has been installed, run the setup/.msi file and install the app on your computer.
3)	After the app is installed, go to the folder path where you installed the app to and right click on the EXE and click on send to desktop to create a shortcut or open the app directly from the folder.

Vending Machine app details:
App function and layout
1)	The insert coin button displays 4 coin denominations that you can choose from to insert money into the vending machine.  The “Amount inserted” textbox shows the total amount of money inserted at a specific time. 
2)	Once a sufficient amount is inserted, the user then selects an item. The “Change due” textbox displays the amount of change that has to be given to the user if any.
3)	If a sufficient amount is not inserted for a particular item then the user is informed via the black information box located below the Coca-Cola logo.
4)	If an item is not available then the user is notified in the info box and the user’s money is returned.
5)	The “Item Quantity” indicators that run along the left side of the application window, indicates the quantity available in the vending machine for a specific item. The maximum quantity allowed per item is 20 units. If an item’s quantity is between 20 and  6 then the quantity indicator is green. If the quantity is between 5 and 1 then the quantity indicator turns yellow and if there is no stock available for an item then the quantity indicator turns red.
6)	The “Coin Count” indicator in the bottom right of the application window shows the number of coins available per coin denomination that is available to be given as change.
7)	The admin button is used to bring up the admin login. The admin user and password is listed below in the User and Passwords section. Once the correct admin user and password is typed in, then the “Re-stock Products” and “Re-load Coins” buttons appear. They are used to restock all items to a quantity of 20 and all coin denominations to a quantity of 100. The “Refresh Products” button in the top left corner and the “Refresh Coins” button in the top right corner are used to refresh the Item Quantities displayed in the “Item Quantity” indicators and coins available in the “Coin Count” indicators after they are re-stocked/reloaded via the admin Re-stock/Reload buttons.
8)	The user is shown that the app is refreshing via the “Refreshing…” sign that comes up at the bottom of the Coca-Cola logo when a refresh is in progress.
9)	Exceptions are handled and written to an error log in the logs folder of the app.
10)	A password protected access database is used to store the Product and Coins data.
11)	An encrypted config file in the config folder of the app is used to store the database and admin login passwords.
12)	3 forms are used for the entire app but they all appear in one application window making it appear as it is a single page application.
User and passwords:
The user for the admin login is Vendor
The password for the admin login is admin123

The password for the access database is Vendor123
