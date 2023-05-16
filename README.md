# Project-Dierenarts
For project Dierenarts I created a winforms app in C#, using Visual Studio, that has access to databases (for this project I used Microsoft Access).

Since this project is made for a veterinarian, which has access to a lot of personal information, I made a login page. 
This login page makes sure that people who SHOULD get access, are able to get access by logging in. 
Once the user has logged in, they can do the following things: 
- Add new customers
- Edit customers
- Remove customers
- Display treatments & prices
- Refresh the program

ADD NEW CUSTOMER

To add a new customer to the database, the user has to fill in the empty textboxes and click on "Toevoegen". 
Once you have added a new customer a messagebox will be displayed saying that you have added a new customer. 
If you want to see the changes you made, click on the refresh button and the winform app will refresh itself.
You can now see the recently added customer in your customerlist. 

EDIT CUSTOMERS

To edit the customers in the database, because of a change in their adres or name etc. Simply click on the customer you want to edit. 
The customer you clicked on will be displayed in the textboxes, now you'll easily be able to make the changes you want to make. 
Once you have finished editing your customer, click on "Wijzigen" in the winforms app. If you want to see the changes you made, click on the refresh button and the winform app will refresh itself.
You can now see the changes you made to the customer in your customerlist. 

REMOVE CUSTOMERS

Sometimes customers move away, or sadly lose their pets. Because of that you might have to remove them from your database. 
The steps for removing the customer is almost the same as editing the customer. To remove the customer from the database click on their name in the listbox (customerlist).
Once you have selected this customer, double check if you have the correct customer (by checking the information that is displayed in the textboxes). 
When you are sure you want to remove this customer click on "Verwijderen". After clicking on that button a messagebox will be displayed on the screen saying that your customer has been removed. 
If you want to see the changes you made, click on the refresh button and the winform app will refresh itself.
You can now see that customer is removed from the customerlist. 

DISPLAY TREATMENTS AND PRICES

When a customer wants to make an appointment or when you want to send a reminder to the customer about certain treatments, simply click on the "Toon behandelingen" button.
A new form will be opened, showing all the treatments and prices. 

In the future this function might be upgraded or changed, since it's not fully complete now and that's all you can do with it for now. 
Because it was a project I made for my study and had to follow some requirements, I didn't do much with this function yet. 
