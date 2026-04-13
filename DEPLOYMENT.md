# 📁 DecisionOS - File Structure & Deployment Guide

## Complete File Structure

```
decisionos/
│
├── 📄 index.html              (Main HTML - Entry Point)
├── 🎨 style.css               (Complete Styling - 2000+ lines)
├── ⚙️ script.js                (Main App Logic - Initialization & Navigation)
├── 🔧 sw.js                   (Service Worker - Offline Support)
├── 📖 README.md               (Documentation)
│
├── 📂 data/
│   └── 📊 knowledge.js        (Decision Tree Data - All flows & knowledge)
│
└── 📂 modules/
    ├── 💾 storage.js          (LocalStorage Management)
    ├── 💬 chat.js             (Decision Chat Engine)
    ├── 📋 planner.js          (Task & Schedule Management)
    ├── ⏱️ timer.js            (Pomodoro Timer)
    ├── 📝 notes.js            (Notes System)
    ├── 📊 progress.js         (Progress Dashboard & Charts)
    ├── 🎯 goals.js            (Goal Tracker)
    └── 📄 resume.js           (Resume Builder)
```

## 📝 File Descriptions

### Core Files (Root Directory)

**index.html** (14KB)
- Complete HTML structure
- All views and modals
- No external dependencies
- Ready to run

**style.css** (25KB)
- Mobile-first responsive design
- Dark/Light theme support
- Smooth animations
- Professional styling
- Custom properties (CSS variables)

**script.js** (8KB)
- App initialization
- View navigation
- Theme management
- Event handling
- Keyboard shortcuts

**sw.js** (1KB)
- Service Worker for offline support
- Caches all files
- Works without internet

**README.md** (5KB)
- Complete documentation
- Deployment instructions
- Usage guide
- Troubleshooting

### Data Directory

**data/knowledge.js** (15KB)
- All decision flow logic
- Career paths database
- Study strategies
- Focus solutions
- Money-making opportunities
- Coding learning paths
- Mental wellness support

### Modules Directory

**modules/storage.js** (6KB)
- LocalStorage wrapper
- CRUD operations for all data types
- Progress tracking
- Streak management
- Daily reset logic

**modules/chat.js** (7KB)
- Decision flow engine
- Question handling
- Answer processing
- Result generation
- Dynamic UI rendering

**modules/planner.js** (4KB)
- Task creation & management
- Schedule generation
- Priority handling
- Statistics updates

**modules/timer.js** (5KB)
- Pomodoro timer logic
- Visual progress ring
- Session tracking
- Notifications
- Statistics

**modules/notes.js** (3KB)
- Note CRUD operations
- UI rendering
- Modal management

**modules/progress.js** (5KB)
- Weekly chart drawing
- Productivity score calculation
- Achievement system
- Canvas-based visualization

**modules/goals.js** (4KB)
- Goal tracking
- Progress updates
- Achievement triggers
- Visual progress bars

**modules/resume.js** (4KB)
- Resume data management
- Live preview
- PDF generation (print-based)
- Auto-save

## 🚀 Deployment Steps

### Step 1: Prepare Files
1. Download the entire `decisionos` folder
2. Verify folder structure matches above
3. Ensure all files are present

### Step 2: Choose Deployment Method

#### Option A: GitHub Pages (Recommended)
```bash
1. Create new repository on GitHub
2. Upload all files (keep structure)
3. Go to Settings → Pages
4. Select branch and root folder
5. Save - site goes live in ~1 minute
```

#### Option B: Netlify (Easiest)
```bash
1. Go to netlify.com
2. Drag & drop the 'decisionos' folder
3. Site is live immediately
4. Get custom domain (optional)
```

#### Option C: Vercel
```bash
1. Go to vercel.com
2. Import from GitHub or upload
3. Deploy with one click
```

#### Option D: Local Testing
```bash
1. Open index.html in browser
2. Works immediately (no server needed)
3. Test all features
```

### Step 3: Verify Deployment
- [ ] Site loads without errors
- [ ] All navigation buttons work
- [ ] Decision flows complete properly
- [ ] Timer functions correctly
- [ ] Data persists after refresh
- [ ] Works on mobile devices
- [ ] Offline mode functional

## 🔍 Important Notes

### File Dependencies
- index.html MUST be in root directory
- CSS/JS files use relative paths
- All modules must be in /modules folder
- Knowledge base must be in /data folder

### Loading Order
Files load in this sequence:
1. HTML structure
2. CSS styling
3. Knowledge base (data/knowledge.js)
4. All modules (modules/*.js)
5. Main script (script.js)

### Browser Compatibility
- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Optimized

## 💡 Quick Test Checklist

After deployment, test these features:

**Home Screen**
- [ ] Stats display correctly
- [ ] Streak counter works
- [ ] Decision buttons clickable

**Decision Flows**
- [ ] Career flow completes
- [ ] Study flow shows schedule
- [ ] All flows give results

**Productivity Tools**
- [ ] Add/complete tasks
- [ ] Timer starts/stops
- [ ] Notes save
- [ ] Goals track progress
- [ ] Resume previews

**Settings & Data**
- [ ] Theme toggle works
- [ ] Data persists
- [ ] Offline mode works

## 🐛 Common Issues & Fixes

**Issue**: Blank page
**Fix**: Check browser console, ensure all files uploaded

**Issue**: Styles not loading
**Fix**: Verify style.css is in root, check file path

**Issue**: Modules not loading
**Fix**: Ensure /modules and /data folders exist

**Issue**: Data not saving
**Fix**: Check localStorage is enabled, try different browser

**Issue**: Timer notifications not working
**Fix**: Allow notifications in browser settings

## 📱 Mobile Testing

Test on:
- iPhone Safari
- Android Chrome
- Tablet landscape/portrait
- Different screen sizes

## 🎯 Performance Tips

1. **Keep it fast**: All code is optimized
2. **No dependencies**: Runs anywhere
3. **Offline first**: Works without internet
4. **Local storage**: No database needed

## 🔐 Data & Privacy

- All data stored locally in browser
- No backend or server required
- No data collection or tracking
- Complete user privacy

## 📊 File Sizes Summary

Total project size: ~95KB (uncompressed)
- HTML: ~14KB
- CSS: ~25KB
- JavaScript: ~56KB
- Total: Extremely lightweight!

## 🎉 You're Done!

Your DecisionOS is now live and ready to help students make better decisions!

**Share your deployment:**
- Test thoroughly
- Share the URL
- Get feedback
- Iterate and improve

---

**Questions?** Check README.md for detailed documentation.

**Need Help?** All code is well-commented for easy understanding.

**Want to Customize?** Start with style.css for colors and themes!
