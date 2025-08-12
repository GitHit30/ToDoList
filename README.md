# ToDoList
# 🌊 Daily Flow - Modern To-Do Application

A beautiful, responsive to-do application built with React and styled with Tailwind CSS. Transform your daily productivity with an elegant glassmorphism design and smooth animations.

<img width="1270" height="822" alt="image" src="https://github.com/user-attachments/assets/f24818b2-0027-4dd2-9cf5-b954d14bcbd0" />


## ✨ Features

- 🎨 **Modern Glassmorphism UI** - Beautiful frosted glass effect with gradient backgrounds
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Real-time Updates** - Instant task management with smooth animations
- 🎯 **Task Filtering** - View All, Active, or Completed tasks
- ⭐ **Priority System** - Mark important tasks with star ratings
- 📊 **Progress Tracking** - Visual progress bar and statistics dashboard
- 🕐 **Timestamps** - Track when tasks were created
- ⌨️ **Keyboard Support** - Press Enter to quickly add tasks
- 🎭 **Smooth Animations** - Delightful micro-interactions and hover effects
- 💾 **Session Persistence** - Tasks persist during your browser session

## 🚀 Demo

> **🔗 Add your live demo link here once deployed**  
> **📱 Screenshots coming soon - take them from your running app!**

## 🛠️ Tech Stack

- **Frontend:** React 18, JavaScript (ES6+)
- **Styling:** Tailwind CSS
- **Icons:** Lucide React
- **Build Tool:** Create React App / Vanilla HTML
- **Deployment:** GitHub Pages / Netlify / Vercel

## 📦 Installation

### Quick Start (HTML Version)

1. Clone the repository:
```bash
git clone https://github.com/your-username/daily-flow-todo.git
cd daily-flow-todo
```

2. Open `index.html` in your browser or serve it locally:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

3. Visit `http://localhost:8000` in your browser

### React Development Setup

1. Clone and install dependencies:
```bash
git clone https://github.com/your-username/daily-flow-todo.git
cd daily-flow-todo
npm install
```

2. Start the development server:
```bash
npm start
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🎯 Usage

### Adding Tasks
- Type your task in the input field
- Press **Enter** or click the **Add** button
- Tasks appear instantly with creation timestamp

### Managing Tasks
- **Complete:** Click the circle checkbox to mark as done
- **Priority:** Click the star icon to mark as high priority
- **Delete:** Click the trash icon to remove tasks

### Filtering
- **All:** View all tasks
- **Active:** View only incomplete tasks  
- **Completed:** View only finished tasks

### Progress Tracking
- Monitor completion percentage
- View total, completed, and remaining task counts
- Visual progress bar updates in real-time

## 🎨 Design Features

### Color Palette
- **Primary:** Deep purple to pink gradient (`from-indigo-900 via-purple-900 to-pink-800`)
- **Accent:** Emerald green for completed tasks
- **Glass Effect:** White overlays with backdrop blur
- **Text:** White with purple tints for secondary text

### Typography
- **Primary Font:** System font stack for optimal performance
- **Weights:** Light (300) to Bold (700)
- **Sizes:** Responsive scaling from mobile to desktop

### Animations
- Smooth hover transitions (300ms)
- Task completion animations
- Background particle effects
- Scale transforms on interaction

## 📁 Project Structure

```
daily-flow-todo/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   └── TodoApp.js
│   ├── styles/
│   │   └── index.css
│   ├── App.js
│   └── index.js
├── README.md
├── package.json
└── tailwind.config.js
```

## 🔧 Configuration

### Tailwind CSS Setup

```javascript
// tailwind.config.js
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {
      animation: {
        'pulse': 'pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite',
      }
    },
  },
  plugins: [],
}
```

### Environment Variables

Create a `.env` file for customization:

```env
REACT_APP_TITLE="Daily Flow"
REACT_APP_SUBTITLE="Transform your day, one task at a time"
```

## 🚀 Deployment

### GitHub Pages

1. Install gh-pages:
```bash
npm install --save-dev gh-pages
```

2. Add to package.json:
```json
{
  "homepage": "https://your-username.github.io/daily-flow-todo",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }
}
```

3. Deploy:
```bash
npm run deploy
```

### Netlify

1. Build the project:
```bash
npm run build
```

2. Drag the `build` folder to [Netlify Drop](https://app.netlify.com/drop)

### Vercel

```bash
npx vercel --prod
```

## 📸 Screenshots

<img width="1270" height="822" alt="image" src="https://github.com/user-attachments/assets/28f39aeb-3d50-48f8-87ed-22cc233afc6e" />


```markdown
### Desktop View
![Desktop Screenshot](./screenshots/desktop-view.png)

### Mobile View  
![Mobile Screenshot](./screenshots/mobile-view.png)

### Task Management
![Task Management](./screenshots/task-management.png)
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Guidelines

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

### Code Style

- Use ES6+ features
- Follow React best practices
- Maintain consistent indentation (2 spaces)
- Add comments for complex logic
- Use semantic commit messages

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎉 Acknowledgments

- **Design Inspiration:** Modern glassmorphism trends
- **Icons:** [Lucide Icons](https://lucide.dev/)
- **Colors:** Tailwind CSS color palette
- **Fonts:** System font stack for performance

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)  
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🔮 Future Enhancements

- [ ] Local storage persistence
- [ ] Dark/Light theme toggle
- [ ] Task categories and tags
- [ ] Due dates and reminders
- [ ] Export to CSV/JSON
- [ ] Drag and drop reordering
- [ ] Task search functionality
- [ ] Keyboard shortcuts
- [ ] Voice input support
- [ ] PWA capabilities



---

<div align="center">

**Made with ❤️ by [Harshit Srivastav](https://github.com/GitHit30)**



</div>
