# TO DO LIST - Python Application

## Overview

This is a simple TO DO LIST application written in Python. The application allows users to manage their tasks by adding, viewing, updating, and deleting items from a to-do list. The tasks are saved in a file, so the list persists between program runs.

## Features

- **Add Tasks**: Add new tasks to your to-do list.
- **View Tasks**: Display all the tasks on your to-do list.
- **Update Tasks**: Mark tasks as completed or edit the task description.
- **Delete Tasks**: Remove completed tasks or tasks you no longer need.
- **Save to File**: Tasks are saved to a file and loaded when the application starts.

## Prerequisites

Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

## How to Run

1. Clone the repository or download the script to your local machine:
    ```bash
    git clone https://github.com/yourusername/todo-list-python.git
    cd todo-list-python
    ```

2. Run the Python script:
    ```bash
    python todo_list.py
    ```

3. Follow the prompts to manage your tasks.

## Usage

Once you run the application, you'll see a menu like this:

```
1. Add a new task
2. View all tasks
3. Update a task
4. Delete a task
5. Exit
```

You can select an option by entering the corresponding number.

- **Add a new task**: You will be prompted to input the task description.
- **View all tasks**: Lists all your tasks, with their status (completed/not completed).
- **Update a task**: Mark a task as completed or update its description.
- **Delete a task**: Remove a task by its index number.

## Example

```
1. Add a new task
2. View all tasks
3. Update a task
4. Delete a task
5. Exit

Enter your choice: 1
Enter task description: Buy groceries
Task added!

Enter your choice: 2
Tasks:
1. Buy groceries [Not completed]

Enter your choice: 3
Enter the task number to update: 1
Mark as completed or edit the description? (c/e): c
Task marked as completed!
```

## File Structure

The task list is saved in a text file called `tasks.txt` located in the same directory as the script. Each task is stored on a separate line with its status.

## Future Improvements

- Implement categories for tasks (e.g., Work, Personal, Shopping).
- Add due dates and reminders for tasks.
- Create a graphical user interface (GUI).
- Sync tasks with a cloud service or a database for multi-device support.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributions

Feel free to fork this repository and submit pull requests for any improvements or bug fixes!
