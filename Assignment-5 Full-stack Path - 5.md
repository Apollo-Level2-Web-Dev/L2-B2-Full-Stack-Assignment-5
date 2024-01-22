# Assignment-5 Full-stack Path-5

## Smartphone **Management Dashboard**

Each product must have following information

-  Product name
-  Product price
-  Product quantity

**Note: Additionally, ensure to include more product information based on the specified filter criteria mentioned in point 4.**

## **Requirements:**

**Objective:**
The primary objective of this assignment is to design and implement a comprehensive Smartphone Management Dashboard, providing the tools to efficiently manage the smartphone inventory, track sales, and analyze sales history. The assignment will incorporate features such as authentication, CRUD operations, state management, real-time UI updates, and smartphone filtering.

**Authentication:**

1. **User Registration and Login:**
   -  Users must register and log in to access the dashboard.
   -  Use JWT (JSON Web Tokens) for secure authentication.
   -  For now, there will be a single role, essentially a user responsible for managing the system.

**Functionality:**

1. Smartphone **Management:**
   -  CRUD Operations:
      -  Add a new smartphone to the inventory.
      -  Delete existing smartphones from the inventory.
      -  Update smartphone details.
      -  Read and view the list of smartphones in the inventory.
      -  Implement a robust filtering system to effectively narrow down smartphone selections based on various criteria.
2. **Sales Management:**

   -  Users can search for a product to sell, and upon finding it, they can click the "Sell" button. On clicking the sell button a form will pop up. The form will have the following fields:
      -  Quantity of the product to be sold (Input quantity cannot exceed the current available stock of the product)
      -  Name of the buyer
      -  Date of the sale

   **Note: If the quantity reaches zero, the product will be removed from the inventory.**

3. **Sales History:**
   -  View sales history categorized by:
      -  Weekly
      -  Daily
      -  Monthly
      -  Yearly
4. **Smartphone Filtering (Implement on the smartphone management page)**

-  Implement a comprehensive smartphone filter system to optimize inventory management. The filter options should cater specifically to smartphones and mobile devices:
   -  **Filter by Price:** Allow users to set a price range for smartphones.
   -  **Filter by Release Date:** Provide options for filtering smartphones based on their release or production date.
   -  **Filter by Brand:** Implement a real-time search functionality for smartphone brands to quickly find smartphones by a specific manufacturer.
   -  **Filter by Model:** Enable searching by smartphone model for unique identification.
   -  **Filter by Operating System:** Categorize smartphones based on their operating systems (iOS, Android, etc.) and allow users to filter by their preferred categories.
   -  **Filter by Storage Capacity:** Include a filter for smartphone storage capacities to easily manage phones with specific storage sizes.
   -  **Filter by Screen Size:** Allow users to filter smartphones based on their screen sizes.
   -  **Additional Relevant Filter Parameters:** Introduce other relevant filter parameters such as camera quality, battery life, or any custom attributes associated with the smartphones.

5. **User Interface Features:**
   -  Gracefully update the UI in real-time when changes occur (e.g., product updates, sales, etc.).
   -  Utilize RTK Query for efficient CRUD operations.
   -  Implement **Re-fetching** functionality to ensure data accuracy and consistency.
6. **State Management:**
   -  Utilize Redux for state management to maintain a consistent application state.
7. **Bulk Delete Product Options:**
   -  Enable users to efficiently manage their inventory by implementing a bulk delete feature for the smartphones.
   -  Provide a user-friendly interface to select and delete multiple smartphone options simultaneously.
8. Implement a feature within the product list that includes a button. Upon clicking this button, users will be redirected to a form where product data is pre-filled. Users can then make modifications as needed to create a new product based on the existing one. The button could be named "Duplicate & Edit" or "Create Variant" to convey the idea that users can duplicate an existing product and make modifications to create a new one.
9. **Additional Features:**
   -  Implement any other relevant features that enhance the usability and functionality of the dashboard.

**Technical Requirements:**

-  Use RTK Query for efficient CRUD operations.
-  Implement Redux for state management.
-  Ensure the UI updates gracefully in real time.
-  Use the **Re-fetching** functionality for data accuracy.
-  Apply tags for improved organization and categorization.
-  Optimize for mobile responsiveness to ensure a reasonable user experience on various devices.
-  Ensure there are at least 10 commits in your GitHub repository.
-  Avoid the use of AI tools or libraries for generating code. Write the code manually to demonstrate a clear understanding of the concepts.
-  You can create the backend for this assignment in a single page, but we highly recommend applying the modular pattern we introduced in Level 2 for enhanced code organization and maintainability.

**Submission Guidelines:**

-  Submit a well-documented codebase with clear comments.
-  Make sure to add a README file that explains how to set up and use the application. In the README, include details like the project name, live URL, features, technology used, and other important information. Try to make it look professional by doing some research and making it appealing.

### **Submission:**

-  Provide the GitHub repository links of the front-end and back-end and ensure there is a README file with explicit instructions for running the application locally.
-  Live

deployment link

-  Submit a demo video showcasing the functionality of the Inventory Management Dashboard.

**Note:**
The assignment should reflect best practices regarding code organization, security, and user experience. It should demonstrate proficiency in using the specified technologies and effectively address shopkeepers' needs to manage their inventory.

### **Deadline:**

-  60 marks: January 28, 2024 11.59 PM
-  50 marks: January 29, 2024 11.59 PM
-  30 marks: After January 29, 2024 11.59 PM
