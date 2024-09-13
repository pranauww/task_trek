# Task Trek

**Task Trek** is a simple and efficient task management web application built using React. It helps users organize their tasks by category, track their progress, and tag tasks with relevant technologies. Tasks can be categorized into "To Do," "Doing," and "Done" columns, allowing users to manage their workload effectively.

## Features
- **Task Creation**: Add new tasks with a title, status (To Do, Doing, Done), and tags.
- **Task Categorization**: Organize tasks into columns based on their current status.
- **Tagging**: Assign tags (e.g., HTML, CSS, JavaScript, React) to each task for easier identification.
- **Task Deletion**: Easily remove tasks that are no longer needed.
- **Persistent Storage**: Tasks are saved to `localStorage` so they remain available even after refreshing the page.

## Future Enhancements
- **Drag-and-Drop**: A planned feature to allow users to rearrange tasks within and between columns via drag-and-drop functionality.

## Installation and Setup

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/task-trek.git
   cd task-trek
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Open in browser**:
   Visit `http://localhost:3000` to see the app in action.

## Technologies Used
- **React**: For building the UI components and managing state.
- **CSS**: For styling the application.
- **LocalStorage**: For persisting task data across browser sessions.

## Usage

1. **Adding a Task**:
   - Enter a task description in the input field.
   - Choose a status from the dropdown menu (To Do, Doing, or Done).
   - Select relevant tags (HTML, CSS, JavaScript, React) by clicking on the tags.
   - Click the **+ Add Task** button to save the task.

2. **Viewing Tasks**:
   - Tasks will be displayed under their respective columns based on their status.
   - Each task will have the tags you selected, making it easy to identify them.

3. **Deleting Tasks**:
   - Click the delete icon on any task to remove it from the list.
  
## Screenshot

Here is a screenshot of the application:
src/assets/Screenshot.png

## Contributions
Feel free to submit issues or pull requests. Contributions are welcome!
