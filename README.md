# CS360
Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

  This Inventory App required to include features where the user could login, register a new account, add items to their inventory, change the quantity of an item, delete an item, and receive a text notification when an item's quantity reached 0.
  
What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

   For the login feature, there needed to be a login screen that took in email and password credentials. If the user did not have a registered login, they needed to be able to create a new account. For this requirement, I decided to develop a separate screen that took in email, password, and phone number credentials. Then, once the user was signed in, they could see their inventory item list. So, there is a separate screen the item list. If the user wanted to add a new item, they can press the "Add Item" button to get brought to the Add Item screen. On this screen, the user can input the item description/SKU and the item quantity. Once the item is added, the user is brought back to the Item Inventory screen. If the user wants to enable or disable SMS notices, they can press the Text Notice button to open an Alert Notice. I wanted to make the application easy to understand and navigate for the user. So, I tried to meet the user requirements without making the application overly complicated.
 
How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

  Since Android was very new to me, I had to do a lot of research on how to properly code functions, such as SQLite databases, alert dialogs, and lists. This taught me how to look for solutions to problems. Research is very important in system development, especially if the developer is asked to build something they have no prior knowledge of that subject.

How did you test to ensure your code was functional? Why is this process important and what did it reveal?

  I ran my application after developing every feature to see if everything worked properly. Also, I used breakpoints while I debugged the system to figure out issues when my application wasn't working properly. For example, the SMS notification was not working properly, even though SMS permission was accepted. With the help of breakpoints, I was able to figure out that the user phone number input was null and I forgot to add the phone number to the database bundle.

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

  Originally, I had the user to only register their email and password when creating a new account. Then, they inputted their phone number later. I was having issues transferring the phone number into the database. So, I decided to have the user register their phone number when they created a new account. Then, I had a separate screen for enabling and disabling SMS notifications. Though, I felt like that was a waste of a screen and more complicated for the user. Instead of a SMS settings screen, I decided to just build an alert dialog.

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

  I'm really happy with how my list and its requirements were built, such as the increase, decrease, and delete components. I believe that my list is super easy for users to understand and use.
