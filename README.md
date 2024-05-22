Project Video Link: https://drive.google.com/file/d/1-ZVQQccgJMSTf-xBQK3wKqecvyHgq4c8/view?usp=sharing

==================== Project Description ====================

![Screenshot 2024-05-22 113522](https://github.com/jay-228/React-Event_Handler/assets/122542095/c91c7e46-7d86-45d3-81b1-2e6f7ba1599d)



# **Event Handler**

**Folder structure**

- src
    - App.js
    - components
        - Post.jsx
        - post.css

**Description**

You are required to build a React app with the following features:

- Upon clicking a "GET POSTS" button, the app should make a fetch request to a specified URL and display the posts as cards.
- You have been provided with two components:

**App.jsx**

- This component manages the state of the posts data.

**Post.jsx**

- This component accepts props named **`title`** and **`body`**, representing the title and body of a post respectively.

**Steps**

1. In the **`App.jsx`** file, include a button and a div.
2. Upon clicking the button, a fetch request should be made to the URL: **`https://jsonplaceholder.typicode.com/posts`**.
3. Once the data is retrieved from the API request, loop over the array of objects received.
4. For each object, render the **`Post`** component located inside the **`Components`** folder (**`src/Components/Post.jsx`**).
5. Inside the **`Post`** component, there should be a **`div`** with the class name **`post`**, containing an **`h1`** tag for the title and an **`h3`** tag for the body.
6. Pass the **`title`** and **`body`** of each post as props to the **`Post`** component, and display them in the respective **`h1`** and **`h3`** tags.
