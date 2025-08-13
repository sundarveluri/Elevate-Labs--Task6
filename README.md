# Elevate-Labs--Task6
Features:

Add Task: Enter a task in the text field and click "Add Task" to include it in the list.

Delete Task: Select a task from the list and click "Delete Selected Task" to remove it.

Input Validation: Displays error messages if the user tries to add an empty task or delete without selecting a task.

Scrollable Task List: Tasks are displayed in a scrollable list for easy viewing.

Code Explanation:

JFrame: The main window of the application, titled "To-Do List Application".

JTextField: Used for inputting new tasks.

JButton: Two buttons for adding and deleting tasks.

JList with DefaultListModel: Displays the list of tasks and allows dynamic updates.

JScrollPane: Wraps the JList to provide scrolling for long task lists.

Event Listeners:

addButton: Adds non-empty tasks to the DefaultListModel and clears the input field.

deleteButton: Removes the selected task from the DefaultListModel if a task is selected.

Notes:

The application includes basic error handling to prevent adding empty tasks or deleting without selection.

The GUI is simple and can be extended with additional features like task editing or persistence.




SwingUtilities.invokeLater: Ensures the GUI is created on the Event Dispatch Thread for thread safety.

