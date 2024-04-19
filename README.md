# restuarant_little_lemon_Django
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
1. add the footer part to the `base.html` file 

### Additional Steps
1. **Reservation Submission**: Submit a reservation form on the Little Lemon website.
2. **Database Inspection**: Verify reservation data in the SQLite database using SQLite Explorer.

## Getting Started# Getting Started
## Getting Started
1. **Environment Setup**: Ensure Python and Django are installed, clone the project repository, navigate to the project directory, and activate the virtual environment (if used).
   ```bash
   # Check Python installation
   python --version

   # Install Django (if not installed)
   pip install django

   # Clone repository
   git clone <repository_url>

   # Navigate to project directory
   cd <project_directory>

   # Activate virtual environment (if used)
   source <virtual_env_directory>/bin/activate



## Conclusion
Upon completing the steps outlined in this README, you'll have successfully developed the Menu and Menu Item pages for the Little Lemon website. Ensure thorough testing and adherence to coding standards throughout the development process. Happy coding!


images:
home page:
![image](https://github.com/Nicole09999/restuarant_little_lemon_Django/assets/106644205/6b05785d-00f1-45f7-ae45-6aa69470ad5b)

menu:
![image](https://github.com/Nicole09999/restuarant_little_lemon_Django/assets/106644205/1f1303fe-c895-4684-8d22-4183fb7a3d4a)

menu_item:
![image](https://github.com/Nicole09999/restuarant_little_lemon_Django/assets/106644205/3bc3832a-c66e-4f32-b699-3dc490669ae5)

reservation:
![image](https://github.com/Nicole09999/restuarant_little_lemon_Django/assets/106644205/b7005e4b-1d75-46c7-933f-a9b8492bbf53)

about us:
![image](https://github.com/Nicole09999/restuarant_little_lemon_Django/assets/106644205/4ecab77c-c9ec-4150-985a-e0c3162980eb)

database:
![image](https://github.com/Nicole09999/restuarant_little_lemon_Django/assets/106644205/0bf276b3-ccbc-4e5c-9706-26df3d8b1b6d)

![image](https://github.com/Nicole09999/restuarant_little_lemon_Django/assets/106644205/82c7daf6-adbe-40e6-b8c6-51892e8c056e)





