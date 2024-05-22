# React ToDo List App 📆
[![Javascript](https://img.shields.io/badge/JavaScript-★★★★★-orange)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![React](https://img.shields.io/badge/React-★★★★★-blue)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-★★★★★-yellow)](https://vitejs.dev/)

A simple ToDo List application utilizes several key React concepts for managing state, component composition, and event handling. Built using: **React, utilizing the Vite.js build tool** <img height=25px src="https://skillicons.dev/icons?i=react"> <img height=25px src="https://skillicons.dev/icons?i=vite">. 

# React Concepts Used 🥇
### 🎖 State Management with useState Hook

- The app uses the `useState` hook to manage two key pieces of state:
  - `inputText`: to store the value of the input field where users add new tasks.
  - `items`: to maintain the list of tasks.

### 🎖 Component Composition and Tree Management

- The app is composed of several components:
  - `App`: The main component responsible for rendering the entire application.
  - `ToDoItem`: A child component representing individual todo items.
  
- The component tree is managed efficiently, with each component focusing on a specific responsibility.

### 🎖 Event Handling

- `handleChange` function: This function handles the `onChange` event of the input field, updating the `inputText` state with the new value entered by the user.

- `addItem` function: This function adds a new item to the list of tasks (`items` state) when the user clicks the "Add" button. It utilizes the spread operator to create a new array with the updated list of items.

- `deleteItem` function: This function removes an item from the list of tasks when the user clicks the delete button on a specific todo item. It uses the `filter` method to create a new array excluding the item to be deleted.

### 🎖 Spread Operator

- The spread operator (`...`) is used in the `addItem` function to create a new array by spreading the previous items and adding the new item entered by the user. This ensures immutability of state.






## Technologies Used 🎯
[![My Skills](https://skillicons.dev/icons?i=react,vite,js)](https://skillicons.dev)

- **React**: A JavaScript library for building user interfaces.
- **Vite.js**: A build tool that provides a fast development environment.
- **JavaScript (ES6+)**: Modern JavaScript features and syntax.
- **CSS**: Styling for the components.



## Screenshots - 
![Todo 1](https://github.com/shanibider/React-Vite-Projects/assets/72359805/0fcd6cd1-cecc-45a8-86c0-4ceadcbccae4)
![Todo 2](https://github.com/shanibider/React-Vite-Projects/assets/72359805/16396988-f64d-45f0-8df3-b96944d84d96)
![Todo 3](https://github.com/shanibider/React-Vite-Projects/assets/72359805/f05e38bb-f247-4fbf-8240-851677972784)

## Code Snippets ⌨
###### App.js:
![2](https://github.com/shanibider/React-Vite-Projects/assets/72359805/1b37def8-538c-4e9d-9ae7-1df75e742ae1)

###### TodoItem.js:
![3](https://github.com/shanibider/React-Vite-Projects/assets/72359805/fe62fca7-df30-43a8-b29a-e2f690483491)

###### InputArea.jsx:
![1](https://github.com/shanibider/React-Vite-Projects/assets/72359805/a3b5021a-fdd6-43fd-9b30-e3e810bc4486)

###### style.css
![4](https://github.com/shanibider/React-Vite-Projects/assets/72359805/7c132f14-0f0c-4e76-b8ad-c316e11d1f03)



## Folder Structure 📁

```
react-todo-list/
  ├── src/
  │   ├── components/
  │   │   ├── App.js
  │   │   ├── TodoItem.js
  │   │   └── InputArea.jsx
  │   ├── index.html
  │   └── ...
  ├── public/
  │   └── styles.css
  ├── package.json
  └── ...
```


## 🚀 Running the Projects
To get started with these projects, clone the repository and install the dependencies.
To run any of the projects, navigate to the project directory and start the development server:

```bash
git clone <link-to-project>
npm i
npm run dev
```

> [!TIP]
> Feel free to explore my repositories and see my projects. I'm always open to collaboration and welcome feedback to improve and grow as a developer. Let's code something amazing together! 🚀😊👩‍💻💻


## 🚀 Contact
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shani-bider/)
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://shanibider.onrender.com/)
<br>For any questions or feedback, please reach out to [shanibider@gmail.com](mailto:shanibider@gmail.com).


---

Happy Coding! 🎉

## License📄

This project is licensed under the MIT License.
