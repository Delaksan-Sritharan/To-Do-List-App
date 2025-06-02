# To-Do-List-App
To-Do List App Using HTML CSS And JavaScript 
# To Do List Application

This is a simple To-Do List application built with HTML, CSS, and JavaScript. It allows users to add tasks, mark them as completed, and delete them. The data is saved to local storage so that the tasks persist even after the browser is closed.

## Features

* **Add Tasks:** Users can add new tasks by typing them into the input field and clicking the "Add" button.
* **Mark Tasks as Completed:** Users can mark tasks as completed by clicking on the list item. This will toggle the task's completion status and display a strikethrough.
* **Delete Tasks:** Users can delete tasks by clicking the "x" button next to the task.
* **Persistent Data:** The tasks are saved to local storage, so they are preserved even if the browser is closed or refreshed.

## Website
<img width="1440" alt="Screenshot 2025-05-14 at 10 56 31 AM" src="https://github.com/user-attachments/assets/7c69a403-9842-4c08-aaf0-92e58a89745d" />


## Technologies Used

* **HTML:** For the structure of the web page.
* **CSS:** For the styling of the web page.
* **JavaScript:** For the functionality of the application.
* **Local Storage:** For persistent data storage.

## How to Use

1.  Open the `index.html` file in a web browser.
2.  Type a task into the input field.
3.  Click the "Add" button to add the task to the list.
4.  Click on a task to mark it as completed or uncompleted.
5.  Click the "x" button next to a task to delete it.

## File Structure
To-Do-List/
├── index.html
├── style.css
├── script.js
└── images/
├── checked.png
└── unchecked.png
* `index.html`: The main HTML file for the application.
* `style.css`: The CSS file for styling the application.
* `script.js`: The JavaScript file for the application's functionality.
* `images/`: Contains the images used for checked and unchecked states.

## JavaScript Functionality

* **`addTask()`:** This function adds a new task to the list.
* **`saveData()`:** This function saves the current tasks to local storage.
* **`showTask()`:** This function loads the tasks from local storage and displays them.
* An EventListener is added to the listContainer to handle clicks on the list items and span elements.

## CSS Styling

The CSS file (`style.css`) provides the styling for the application. It includes styles for the container, the to-do app, the input field, the buttons, and the list items.

## Local Storage

The application uses local storage to save the tasks. The `saveData()` function stores the HTML of the list container in local storage, and the `showTask()` function retrieves it.

## Improvements

* Add the ability to edit tasks.
* Add the ability to prioritize tasks.
* Add more advanced styling.
* Add more advanced data management.
* Add a clear all completed tasks option.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests. Any contributions are welcome!

