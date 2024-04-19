# restuarant_ittle_lemon_Django
# Little Lemon Website Development README

## Introduction
This document provides instructions and guidelines for completing the Course Assessment to build the Menu and Menu Item pages for the Little Lemon website using Django framework.

### Scenario
Little Lemon, a local bistro, aims to enhance customer experience through a digital presence. As a developer, you've been assisting Mario and Adrian, the owners, in building their website. The next crucial step is completing the Menu page.

## Instructions

### Part 1: Create the Menu Page
1. **Model Creation**: Define the `Menu` model in `models.py` with attributes `name` and `price`.
2. **Admin Panel Integration**: Register the `Menu` model in `admin.py`.
3. **Database Migration**: Perform migrations using commands in the terminal.
4. **URL Configuration**: Ensure URL paths are configured in both project-level and app-level `urls.py`.
5. **Admin Panel Data Entry**: Create a superuser and add menu items via Django admin panel.
6. **View Function**: Implement the `menu()` view function in `views.py`.
7. **Template Creation**: Develop the `menu.html` template with dynamic content.

### Part 2: Create the Menu Item Page
1. **Model Update**: Enhance the `Menu` model in `models.py` by adding the `description` attribute.
2. **Admin Panel Update**: Update menu items' descriptions via Django admin panel.
3. **View Function**: Implement the `display_menu_items()` view function in `views.py`.
4. **URL Configuration**: Add URL path for the menu item page in `urls.py`.
5. **Template Update**: Design the `menu_item.html` template for individual menu items.

### Part 3: Create the Footer Template
1. **Footer Template Creation**: Develop the `_footer.html` template for website footer.
2. **Integration**: Link the footer template in the `base.html` file.

### Additional Steps
1. **Reservation Submission**: Submit a reservation form on the Little Lemon website.
2. **Database Inspection**: Verify reservation data in the SQLite database using SQLite Explorer.

## Getting Started
1. **Environment Setup**: Ensure Python and Django are installed.
2. **Project Setup**: Clone the project repository and navigate to the project directory.
3. **Activation**: Activate the virtual environment (if used).
4. **Installation**: Install project dependencies.
5. **Configuration**: Configure necessary settings.
6. **Development**: Follow the provided steps to implement features.
7. **Testing**: Test functionality and verify data entry.
8. **Deployment**: Deploy the website to the desired server (if applicable).

## Conclusion
Upon completing the steps outlined in this README, you'll have successfully developed the Menu and Menu Item pages for the Little Lemon website. Ensure thorough testing and adherence to coding standards throughout the development process. Happy coding!
