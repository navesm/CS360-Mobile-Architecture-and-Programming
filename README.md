# CS360-Mobile-Architecture-and-Programming
SNHU Mobile Android Design and Development Artifacts


The InventoryApp was developed to help users efficiently manage and track inventory items in a warehouse or small business environment. The app’s primary goal is to simplify inventory monitoring, ensuring users can quickly view, add, edit, or delete items while being alerted when stock levels are low or out of stock. The app addresses common user needs such as maintaining accurate inventory records, preventing stock shortages, and providing actionable alerts to support timely decisions. By streamlining inventory management, the app reduces manual errors and saves time for the user

This app includes several key screens and features to meet user needs:
Login and Registration Screens, an Inventory Dashboard to display the grid of inventory items, 
An Add/Edit Item bottom sheet to allow users to easily add new items or modify existing ones with a modal interface, 
action buttons,
and finally SMS alerts to notify users when items reach low or zero inventory levels.

The approach to coding this out required a design strategy incorporating separation of concerns, RecyclerView Patterns, bottom sheet actions, and runtime SMS permission handling to ensure graceful handling of user denials without crashing the app.

Testing the app was crucial to getting it to function properly, as with any app! A lot of the testing involved in this project was for the purpose of UI validation, permission handling, and user flow. 
Additionally, it was necessary to try edge cases for the various inventory input fields, ensure the low and zero inventory quantities triggered the proper SMS notification response, and that the app still functioned without crashing after being denied SMS permissions.

The project demonstrates my ability to meet challenges through careful layout design and iterative development, integrating database management, dynamic UI, and user-centric design. 
