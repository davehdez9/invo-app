# Invo

You can find the deployed project at https://my-invo-app.herokuapp.com/

Friendly inventory system app that will help to maintain control of any item and have an appropriate control of these, allowing them to enter and update and delete any product.

## Getting Started:
Clone this repository and running in your local system.

    > git clone https://github.com/davehdez9/invo-app.git
    > cd invo-app

Proceed to install the rest using the command below:

    > pip3 install -r requirements.txt

Run the App:

    > FLASK_ENV=development flask run

## Key Features

- Register and log in with your own account.
- Add items.
- Search by category or item name.
- Update any entry or exit of an item.
- Update item information.
- Remove the item.
- Visualize when an item is not in its minimum quantity.
- Conversion of units of measure.
- Edit and delete your profile.

## User Flow 

### Sign Up - Login - Log Out:
Start by creating a new account. Once you create your new account, you will be directed to the home page. You can log out of your account from the home page. Also, you can login with the same information with which you registered.

![sign-up](static/gifs/signup.gif)

### Add Items:
Adding a product requires a category, name, quantity, unit of measure and the minimum quantity required in stock.

![add-item](static/gifs/add-item.gif)
### Edit Quantity:
In the Dashboard it will be displayed in yellow when the item is below the minimum required. You can add or subtract any amount to level according to the minimum required.

![issue-receive](static/gifs/issue-receive.gif)

### Edit Item:
You can edit the category, name, unit of measure and the minimum quantity in stock.

![update-item](static/gifs/update-item.gif)

### Delete Item:
You can remove the item from stock.

![delete-item](static/gifs/delete-item.gif)

### Search Item:
You can filter an item by its category or name.

![search-item](static/gifs/search-item.gif)

### Convert units of measurement:

![convert-unit](static/gifs/convert-unit.gif)
### Edit profile:
Edit the email and the name in the same way that you can delete the profile.

![edit-profile](static/gifs/edit-profile.gif)



## Tech Stack

- HTML & CSS
- Python/Flask
- PostgreSQL
- SQLAlchemy
- Jinja
- WTForms
- Bootstrap
- Heroku
## External APIs
https://spoonacular.com/food-api/docs

## Project Proposal
https://github.com/davehdez9/restaurant-inventory/blob/main/project_proposal.md
