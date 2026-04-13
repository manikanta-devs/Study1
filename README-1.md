# 👉 DecisionOS – Smart Student Decision Assistant

A professional, mobile-first web application that helps students make better decisions through guided conversations and structured planning tools.

## 🎯 Features

### Core Decision Flows
- **💼 Career Guidance** - Get personalized career suggestions with roadmaps
- **📚 Study Strategy** - Custom study plans based on your situation
- **😴 Focus Improvement** - Personalized focus routines and productivity tips
- **💰 Money Making** - Freelancing and earning opportunities
- **🧠 Mental Wellness** - Stress management and support resources
- **🧑‍💻 Learn Coding** - Programming learning paths

### Productivity Tools
- **📋 Smart Planner** - Task management with priorities and scheduling
- **⏱️ Focus Timer** - Pomodoro timer with session tracking
- **📝 Notes System** - Quick note-taking and organization
- **📊 Progress Dashboard** - Visual tracking of your productivity
- **🎯 Goal Tracker** - Set and monitor your goals
- **📄 Resume Builder** - Create and download professional resumes

### Additional Features
- 🔥 Daily streak tracking
- 🏆 Achievement system
- 🌙 Dark/Light mode
- 📱 Mobile-first responsive design
- 💾 Offline support
- 🔔 Browser notifications (Pomodoro timer)
- ⌨️ Keyboard shortcuts

## 📁 Project Structure

```
decisionos/
├── index.html              # Main HTML structure
├── style.css              # Complete styling
├── script.js              # Main application logic
├── sw.js                  # Service Worker (offline support)
├── data/
│   └── knowledge.js       # Decision tree data & knowledge base
└── modules/
    ├── storage.js         # LocalStorage management
    ├── chat.js            # Decision chat engine
    ├── planner.js         # Task management
    ├── timer.js           # Pomodoro timer
    ├── notes.js           # Notes system
    ├── progress.js        # Progress tracking
    ├── goals.js           # Goal tracker
    └── resume.js          # Resume builder
```

## 🚀 Quick Start

### Option 1: Local Development

1. **Download all files** and maintain the folder structure
2. **Open index.html** in a modern web browser
3. **That's it!** No build process or dependencies required

### Option 2: Deploy to GitHub Pages

1. **Create a new repository** on GitHub
2. **Upload all files** maintaining the folder structure
3. **Go to Settings → Pages**
4. **Select branch** (usually `main`) and root folder
5. **Save** - Your site will be live at `https://yourusername.github.io/decisionos`

### Option 3: Deploy to Netlify

1. **Sign up** at netlify.com
2. **Drag and drop** the entire folder into Netlify
3. **Your site is live!** Netlify will provide a URL

### Option 4: Deploy to Vercel

1. **Sign up** at vercel.com
2. **Import your repository** or upload files
3. **Deploy** - Site will be live instantly

## 💡 How to Use

### Getting Started
1. Choose a decision flow from the home screen
2. Answer the questions step by step
3. Get personalized recommendations and roadmaps

### Using Productivity Tools
- **Tasks**: Add tasks with priorities and times
- **Timer**: Use Pomodoro technique (25min focus, 5min break)
- **Notes**: Quick capture ideas and information
- **Goals**: Set goals and track progress
- **Resume**: Build and download your resume

### Keyboard Shortcuts
- `Ctrl/Cmd + K` - Add task
- `Ctrl/Cmd + N` - Add note
- `Ctrl/Cmd + T` - Open timer
- `Esc` - Close modals

## 🎨 Design Philosophy

- **Mobile-First**: Optimized for phone screens
- **Button-Based UX**: Minimal typing required
- **Warm Color Palette**: Encouraging and energetic
- **Distinctive Typography**: Fraunces + Outfit fonts
- **Smooth Animations**: Polished micro-interactions
- **Card-Based Layout**: Clean and organized

## 🔧 Technical Details

### Technologies Used
- Pure HTML5, CSS3, JavaScript (ES6+)
- No frameworks or libraries required
- LocalStorage for data persistence
- Service Worker for offline support
- Canvas API for charts
- Web Notifications API

### Browser Support
- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Data Storage
All data is stored locally in your browser using LocalStorage:
- Tasks, notes, and goals
- Progress and statistics
- Resume information
- Theme preferences
- Streak data

**Note**: Data is per-browser and not synced across devices.

## 🔒 Privacy & Security

- **No Backend**: All processing happens locally
- **No Data Collection**: Your data never leaves your device
- **No Analytics**: Complete privacy
- **No Account Required**: Start using immediately

## 📱 PWA Support

The app can be installed as a Progressive Web App:
1. Open in Chrome/Edge/Safari
2. Look for "Install App" prompt
3. Add to home screen
4. Works offline after installation

## 🎯 Use Cases

### For Students
- Career planning and exploration
- Study schedule optimization
- Focus improvement
- Learning new skills
- Managing assignments

### For Freelancers
- Goal tracking
- Time management
- Resume building
- Skill development planning

### For Anyone
- Productivity improvement
- Mental wellness support
- Personal organization
- Self-improvement tracking

## 🐛 Troubleshooting

### Data Not Saving
- Check if cookies/localStorage are enabled
- Try a different browser
- Clear cache and reload

### Timer Not Working
- Allow notifications when prompted
- Check browser notification settings
- Ensure tab is active

### Charts Not Showing
- Ensure JavaScript is enabled
- Try refreshing the page
- Check browser console for errors

## 🔄 Future Enhancements

Potential features for future versions:
- Cloud sync across devices
- Export data to PDF/CSV
- Integration with calendar apps
- AI-powered suggestions
- Community features
- Mobile app versions

## 📄 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Share feedback

## 📞 Support

For questions or issues:
- Check the troubleshooting section
- Review browser console for errors
- Ensure all files are properly uploaded
- Verify folder structure is correct

## 🎉 Credits

Created with ❤️ for students everywhere.

**Design Principles**: Mobile-first, accessibility-focused, minimal yet powerful.
**Fonts**: Google Fonts (Fraunces, Outfit)
**Icons**: Native emoji (universal support)

---

## 📝 Quick Deployment Checklist

- [ ] All files uploaded with correct folder structure
- [ ] Index.html is in root directory
- [ ] Modules folder contains all 8 JavaScript files
- [ ] Data folder contains knowledge.js
- [ ] Test on mobile device
- [ ] Verify offline functionality
- [ ] Check all features work
- [ ] Share your deployed URL!

---

**Made for students, by Claude** 🚀

Start making better decisions today with DecisionOS!
