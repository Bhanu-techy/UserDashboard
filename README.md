# Title

    User Management Dashboard

## Objective

    The primary goal of this assignment is to develop a functional web application that serves as a user management dashboard.
    The application should allow users to perform basic operations—viewing, adding, editing, and deleting user data—using a mock backend API. 
    This project is a practical exercise in front-end development, focusing on API interaction, dynamic UI updates, and data handling.

## Tech Stack

  * Front-End : Used React JS, CSS, HTML
  * JSONPlaceholder :  a free online REST API that you can use for demonstration and test purposes

## Completion Instructions

### 1. User Interface

    The user interface is the visual part of the application that users will interact with. It is clean, responsive, and easy to navigate.

    * User List Display:** A table or list to show user details. The required columns are: `ID`, `First Name`, `Last Name`, `Email`.
    * Action Buttons:** Provide clear, clickable elements (buttons or links) for `Add`, `Edit`, and `Delete` actions.
    * User Form:** A dedicated form for entering new user details or editing existing ones. This form should include input fields for `First Name`, `Last Name`, `Email`.
    * Pagination/Infinite Scrolling:** Implement a way to manage large datasets. Choose one of the following:
        -Infinite Scrolling:** Load more users automatically as the user scrolls to the bottom of the page.
    * Filter and Search:**
        - **Filter:** Created a pop-up for filtering users by `First Name`, `Last Name`, `Email`.
        - **Search:** Implemented a search bar or functionality to find users based on text input.
    * Sorting:** Add the ability to sort the user list by different columns (e.g., sort by `Last Name` alphabetically).
    * Responsiveness:** The layout adapts and be usable on various screen sizes, from mobile phones to desktop computers.

  **2. Functionality

      This section details the specific actions application must perform.

        * View: When the page loads, fetch and display the list of all users from the `/users` endpoint using a **GET** request.

        * Add: When a new user is submitted via the form, send a 'POST' request to the `/users` endpoint. Note that JSONPlaceholder will simulate a successful response but will not save the new data permanently.

        * Edit:
            1. Fetch the data for a specific user.
            2. Pre-fill the user form with the fetched data.
            3. When the form is submitted, send a **PUT** request with the updated details to the `/users/:id` endpoint.

        * Delete: When a user is selected for deletion, send a **DELETE** request to the `/users/:id` endpoint. Like with adding a user, this will only simulate success.



  **3. Backend Interaction

    The application will communicate with a free, public REST API to simulate a backend system.
      *  API Service : Used JSONPlaceholder, a free online REST API that you can use for demonstration and test purposes.
      
      *  Specifically, used the '/users' endpoint to fetch and manipulate user data.
      
      * After performing the CRUD operations when the response is success then filtered the data manually, 
          if the response get failure dispalyed a failure view.
        
      * HTTP Methods:
        -GET : To retrieve (view) user data.
        -POST: To add a new user.
        -PUT: To edit an existing user.
        -DELETE: To remove a user.
    
** 4. Error Handling & Validations

A robust application anticipates and gracefully handles potential problems.

* API Errors:** Implement logic to catch and display an error message to the user if an API request (e.g., due to network issues) fails.
* Client-side Validation:** Add checks to the user form to ensure that input fields are not empty or contain invalid data 
  This should happen before the form is even submitted to the API.

## Guidelines

- Code Choice: Used front-end technology such as JavaScript, React.
- HTTP Requests: Used the native `Fetch API` to make your HTTP requests.
- Design: While functionality is the main focus, a clean and organized.
- Modularity: Code that is organized into logical parts or modules, making it easier to read and maintain.
- Assumptions: Used third-party package loader-spinner while fetching the and api and making and afte any changes made in data.

## Code Evaluation Criteria

1. Functionality: Does the application meet all the requirements for viewing, adding, editing, and deleting users?
2. Code Quality: Is the code clean, well-organized, and properly commented?
3. Responsiveness: Does the UI adapt correctly to different screen sizes?
4. Error Handling: Are API and client-side errors handled gracefully?
5. Documentation: Is the `README` file complete and easy to follow?
6. Efficiency: How efficiently does the application handle data and UI updates?

## Reflections (to be included in your README)


Section should be a personal reflection on your development process. Please consider and write about the following:

  * Challenges Faced: What were the most significant challenges you encountered during development? 
    (e.g., handling asynchronous API calls, state management, complex sorting logic, or CSS layout issues).
   * Improvements: If you had more time, what improvements or new features would you implement? 
    (e.g., better UI design, more robust validation, a more scalable architecture, or adding user authentication).


### Submission Instructions
   
   * Intro Video: Record introduction and submit it via the provided link.
   * Code Repository: Share complete implementation on a public Git repository (e.g., GitHub, GitLab).
   * README File: Your repository must include a well-structured `README.md` file. It should contain:
   * Setup Instructions:** Clear, step-by-step guidance on how to set up and run your project locally.
   * Run Instructions:** Commands to start the application.
   * Project Overview:** A brief description of your implementation.
   * Reflections:** A section for reflecting on your process..
   * Deployed Link or Published Link (this is mandatory)

### Submission Links:
   Github : https://github.com/Bhanu-techy/UserDashboard.git
   Code Sanbox : 