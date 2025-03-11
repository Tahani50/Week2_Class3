# Multi-Screen Task Manager App

## Overview
The **Multi-Screen Task Manager App** is a simple and efficient task management application built using SwiftUI. It follows the **MVVM (Model-View-ViewModel)** architectural pattern and ensures accessibility compliance. The app allows users to create, view, and manage tasks across multiple screens while supporting **dark mode** and **dynamic text scaling**.

## Features
### 1. **Navigation Implementation**
- Utilizes **NavigationStack** for smooth screen transitions.
- Implements **NavigationLink** to navigate between screens.
- Passes data efficiently between screens using ViewModels.

### 2. **MVVM Architecture**
- Uses **ObservableObject** for managing the app state.
- Implements **@Published** properties to keep UI updated.
- Uses **@StateObject** for ViewModel lifecycle management.

### 3. **Accessibility Features**
- Implements **accessibilityLabel()**, **accessibilityHint()**, and **accessibilityHidden()**.
- Supports **Dynamic Type** to ensure text scales appropriately.

### 4. **Task Management Features**
- **Task List Screen**: Displays all tasks in a list.
- **Add Task Screen**: Allows users to input a new task using a **TextField** and add it to the list.
- **Task Completion**: Users can mark tasks as completed.
- **Dark Mode Support**: UI adapts to the system theme.

## Screens
1. **Task List Screen**
   - Displays all tasks.
   - Includes a toggle for **dark mode**.
   - Supports **task deletion** and **completion status**.
   
2. **Add Task Screen**
   - Allows users to enter a new task.
   - Includes a button to save the task.
   - Validates input before allowing task creation.

## Installation & Usage
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/TaskManagerApp.git
   ```
2. **Open the project in Xcode**
3. **Run the app on an iOS Simulator or a physical device**

## Technologies Used
- SwiftUI
- MVVM Architecture
- NavigationStack & NavigationLink
- Accessibility APIs

## Accessibility Considerations
- **VoiceOver support** for task interaction.
- **Dynamic Text** scaling support.
- **Dark Mode compatibility** for better visibility.
