# Shopping-Cart

Business Prompt
Your local corner grocery store has hired you as a technology consultant to help modernize their checkout system.

Currently, when managing inventory, store employees affix a price tag sticker on each grocery item in stock. And when a customer visits the checkout counter with their selected items, a checkout clerk uses a calculator to add product prices, calculate tax, and calculate the total amount due.

Instead, the store owner describes a desired checkout process which involves the checkout clerk scanning each product's barcode to automatically lookup prices, perform tax and total calculations, and print a customer receipt. To facilitate this process, the store owner has authorized the purchase of a few inexpensive barcode scanners, as well as checkout computers capable of running Python applications.

The store owner says it would be "acceptable but not preferable" to manage the inventory of products via the application's source code, that it would be "better" to manage the inventory of products via a local CSV file stored on the checkout computer, and that it would be "ideal" to be able to manage the inventory of products via a centralized Google Sheet spreadsheet document.

The store owner also says it would be "nice to have" a feature which prompts the checkout clerk or the customer to input the customer's email address in order to send them a receipt via email.




Instructions
Iteratively develop a Python application which satisfies the store owner's objectives, as described in more detail by the "Basic Requirements" below.

Before attempting to implement the basic requirements, take some time to configure your project repository according to the "Setup" instructions below. After doing so, you'll have a remote repo on GitHub and a local copy on your computer within which to develop.

When developing, as you reach key milestones, use the command-line or GitHub Desktop software to intermittently "commit", or save new versions of, your code. And remember to push / sync / upload your work back up to your remote project repository on GitHub at least once before you're done.

If you are able to implement the basic requirements with relative ease, or if you are interested in a challenge, consider addressing one or more of the "Further Exploration Challenges". Otherwise, if you need help breaking the problem up into more manageable pieces, consult the "Guided Checkpoints". And if you would like a narrated walkthrough, consult the "Guided Screencast".

A grocery store name of your choice 
A grocery store phone number and/or website UR- DONEL and/or address of choice
The date and time of the beginning of the checkout process, formatted in a human-friendly way (e.g. 2020-02-07 03:54 PM)
The name and price of each shopping cart item, price being formatted as US dollars and cents (e.g. $3.50, etc.)
The total cost of all shopping cart items (i.e. the "subtotal"), formatted as US dollars and cents (e.g. $19.47), calculated as the sum of their prices
The amount of tax owed (e.g. $1.70), calculated by multiplying the total cost by a New York City sales tax rate of 8.75% (for the purposes of this project, groceries are not exempt from sales tax)
The total amount owed, formatted as US dollars and cents (e.g. $21.17), calculated by adding together the amount of tax owed plus the total cost of all shopping cart items
A friendly message thanking the customer and/or encouraging the customer to shop again 