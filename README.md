# museumStore
In previous chapters, you worked with a museum store. In this project, create a class for the items that are sold in the store. There are 3 types or categories of items – clothing, toys, and tools (like pencils). The class for the inventory items needs instance variables for the name, category, price, and quantity in inventory. Create a constructor that accepts those 4 pieces of data to populate the instance variables for the inventory item object. Write a method to display the inventory items. Create a “sell” method that accepts a parameter for the quantity sold. First display the information – the item and requested quantity. If there is enough quantity in inventory, the sale is good, so remove that sold quantity from the inventory quantity and display a message with the cost of the sale. If there is not enough quantity in inventory, display an error message that there was no sale.  In the driver class, instantiate 6 items in inventory, 2 of each category. You may choose the details of those items. Display the 6 items. Write the code to sell some quantity of 3 of the items – one of those sales attempts must be invalid, trying to sell more than the available quantity. After each sale attempt, display the inventory item to show the change in quantity. Even if the sale was not valid, display the inventory item.  Note that there is no user interaction in this project, you are testing the methods by calling them explicitly.


== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project.  We have an
[open {bug ticket, mailing list thread, etc.} ](INSERT_LINK) where the
project contributors are actively discussing how we can move away from GitHub
in the long term.  We urge you to read about the
[Give up GitHub](https://GiveUpGitHub.org) campaign from
[the Software Freedom Conservancy](https://sfconservancy.org) to understand
some of the reasons why GitHub is not a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please
[check this resource](INSERT_LINK) for how to send us contributions without
using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)
