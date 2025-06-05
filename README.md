# Grocery-List-Manager
🛒 Problem Statement: Grocery List Manager
Managing daily grocery needs can often become disorganized, especially when juggling multiple items, quantities, and updates. People may forget what to buy, duplicate items, or lose handwritten lists. To solve this everyday problem, this project aims to develop a simple console-based Grocery List Manager using Python that helps users add, view, update, and remove grocery items efficiently.

The goal is to simulate a digital grocery assistant that maintains an in-memory list of items and their quantities, helping users plan their shopping and avoid confusion or redundancy.

✅ Key Objectives:
Allow users to add grocery items with quantities.

View all current items in the list.

Update quantities of existing items.

Remove items if no longer needed.

Clear the list entirely when done.

Simple, user-friendly interaction in a command-line interface.

🧠 Function-wise Explanation:

1. display_menu()
   - Prints the menu with options (View, Add, Remove, Update, Clear, Exit).

2. view_list(grocery_list)
   - If the grocery list is empty, it notifies the user.
   - Otherwise, it prints all items and their quantities.

3. add_item(grocery_list)
   - Asks for item name and quantity from the user.
   - If quantity is not provided or invalid, defaults to 1.
   - If the item exists, it increases the quantity.
   - If it doesn’t exist, it adds the item with given quantity.

4. remove_item(grocery_list)
   - Asks for the item name to remove.
   - Deletes the item if it exists, else shows a message.

5. update_item(grocery_list)
   - Asks for the item name and new quantity.
   - If the item exists and quantity is valid, it updates it.
   - If the item doesn’t exist or quantity is invalid, it shows a message.

6. clear_list(grocery_list)
   - Clears the entire grocery list using the clear() method.

7. main()
   - Initializes an empty grocery list.
   - Repeatedly shows the menu and processes user choices using if-elif blocks.
   - Exits the loop if the user chooses '6'.

