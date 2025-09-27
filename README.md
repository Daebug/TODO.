# TODO. - Advanced Task Management Application

A modern, feature-rich todo application built with React that gamifies productivity through an MMR (Match Making Rating) system, level progression, and comprehensive task management capabilities.

## ✨ Features

### 🎮 Gamification System
- **Level Progression**: Earn points by completing tasks and advance through 10 unique levels
- **MMR Rating System**: Dynamic rating system that tracks your task completion performance
- **Point System**: Earn points based on task priority (High: 15pts, Medium: 10pts, Low: 5pts)
- **Subtask Rewards**: Additional 2 points per completed subtask

### 📋 Advanced Task Management
- **Priority Levels**: Color-coded priority system (High/Medium/Low)
- **Due Dates & Times**: Set specific deadlines with time tracking
- **Subtasks**: Break down complex tasks into manageable sub-items
- **Notes System**: Add detailed notes to any task
- **Task Filtering**: View All, Active, Completed, Overdue, or Deleted tasks

### 🎯 Smart Features
- **Overdue Detection**: Automatic tracking and penalty system for missed deadlines
- **Task Recovery**: Restore accidentally deleted tasks
- **Keyboard Shortcuts**: Full keyboard navigation support
- **Responsive Design**: Adaptive layout for different screen sizes
- **Data Persistence**: Local storage ensures your progress is never lost

### 🎨 User Experience
- **Smooth Animations**: Framer Motion powered transitions
- **Dark Theme**: Eye-friendly dark interface
- **Visual Feedback**: Real-time progress indicators and status updates
- **Grid/List Views**: Toggle between different viewing modes
- **Expandable Tasks**: Click to view detailed task information

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd todo
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to see the application

### Build for Production
```bash
npm run build
npm run preview
```

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `N` | Create new task |
| `G` | Toggle grid/list view |
| `A` | Show all tasks |
| `V` | Show active tasks |
| `C` | Show completed tasks |
| `O` | Show overdue tasks |
| `D` | Show deleted tasks |
| `R` | Toggle rewards panel |
| `I` | Show help information |
| `M` | Show MMR details |
| `X` | Clear completed tasks |
| `L` | Return to list view |
| `Esc` | Close modals/forms |

## 🏆 Level System

Progress through 10 distinct levels by completing tasks:

1. **Novice** - Getting started
2. **Apprentice** - Building habits
3. **Journeyman** - Developing skills
4. **Expert** - Mastering basics
5. **Specialist** - Advanced user
6. **Master** - Exceptional performance
7. **Grandmaster** - Elite status
8. **Champion** - Outstanding achievement
9. **Legend** - Legendary performance
10. **Mythic** - Ultimate mastery (with MMR system)

### MMR System (Level 10)
At the highest level, your performance is tracked with an MMR system:
- **Positive MMR**: Maintained through consistent task completion
- **Negative MMR**: Risk of demotion for poor performance
- **Overdue Penalties**: -30 MMR for each overdue task
- **Deletion Penalties**: -15 MMR for deleted incomplete tasks

## 🛠️ Technology Stack

- **Frontend**: React 19 with modern hooks
- **Styling**: Tailwind CSS 4.0 with custom configurations
- **Animations**: Framer Motion for smooth transitions
- **Icons**: Lucide React for consistent iconography
- **Build Tool**: Vite for fast development and building
- **Code Quality**: ESLint for code standards

## 📱 Responsive Design

The application adapts to different screen sizes:
- **Compact Mode**: < 640px (mobile)
- **Default Mode**: 640px - 1024px (tablet)
- **Expanded Mode**: > 1024px (desktop)

## 🔧 Project Structure

```
src/
├── components/
│   ├── layout/           # Header and Footer components
│   ├── fragments/        # Reusable UI fragments
│   ├── TaskForm.jsx      # Task creation/editing form
│   ├── TodoItem.jsx      # Individual task component
│   ├── TodoList.jsx      # Task list container
│   ├── TodoGrid.jsx      # Grid view layout
│   ├── Modal.jsx         # Modal wrapper component
│   └── SubTaskList.jsx   # Subtask management
├── hooks/
│   └── index.js          # Custom React hooks
├── App.jsx               # Main application component
├── main.jsx              # Application entry point
└── index.css             # Global styles
```

## 🎯 Core Hooks

The application uses several custom hooks for state management:

- `useLocalStorage`: Persistent data storage
- `useOverdueTasks`: Automatic overdue task detection
- `useLayoutMode`: Responsive layout management
- `useKeyboardShortcuts`: Keyboard navigation
- `useLevelSystem`: Level progression logic
- `useTodoManagement`: CRUD operations for tasks
- `useViewMode`: View state management
- `useFilteredTodos`: Task filtering logic

## 📊 Data Persistence

All data is stored locally in your browser:
- **Tasks**: Complete task data with metadata
- **User Progress**: Points, MMR, and level information
- **Deleted Tasks**: Recoverable task history
- **Overdue Tasks**: Tracking for penalty system

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Built with React and modern web technologies
- Inspired by gamification principles in productivity
- Uses Framer Motion for beautiful animations
- Tailwind CSS for responsive design

---

**Start your productive journey today! Create your first task and begin climbing the ranks.** 🚀