# 🚀 Space Explorer Quiz

An interactive web-based quiz application about space exploration, planets, and astronomy. Test your cosmic knowledge with 10 engaging questions and get instant feedback!

## ✨ Features

- **10 Space Trivia Questions** - Questions covering planets, space missions, astronomy, and cosmic phenomena
- **Interactive UI** - Beautiful, modern design with smooth animations and transitions
- **Real-time Feedback** - Instant visual feedback for correct and incorrect answers
- **Progress Tracking** - See your progress with a visual progress bar and score counter
- **Dark Mode Support** - Automatic light/dark mode based on system preferences
- **Responsive Design** - Works perfectly on mobile, tablet, and desktop devices
- **No Dependencies** - Single HTML file with no external libraries required
- **Offline Capable** - Runs completely offline, no internet connection needed
- **Fully Accessible** - Keyboard navigation support and semantic HTML for screen readers

## 🎮 How to Play

### Running Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/SlowWanderer/space-quiz.git
   cd space-quiz
   ```

2. **Open in Browser**
   - Simply open `index.html` in your web browser
   - No build tools or server setup required!
   
   **Option A: Direct File Opening**
   ```bash
   # On Windows
   start index.html
   
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   ```
   
   **Option B: Using a Local Server** (recommended for consistency)
   ```bash
   # Using Python 3
   python -m http.server 8000
   # Then visit http://localhost:8000
   
   # Or using Node.js http-server
   npx http-server
   ```

### Playing the Quiz

1. **Read the Question** - Each question is clearly displayed with 4 multiple-choice options
2. **Select Your Answer** - Click on any option to submit your answer
3. **Get Instant Feedback** - See if you were correct with visual animations and feedback text
4. **Navigate** - Use "Previous" and "Next" buttons to move between questions
5. **View Results** - After all 10 questions, see your final score and personalized message

## 📊 Scoring

- Each correct answer = 1 point
- Maximum score = 10 points
- Scoring is based on percentage:

| Score | Message |
|-------|---------|
| 100% (10/10) | 🌟 Perfect! You're a true space expert! |
| 80-99% (8-9/10) | 🚀 Excellent work! You know your cosmos! |
| 60-79% (6-7/10) | 🌙 Good job! You're becoming a space explorer! |
| 40-59% (4-5/10) | 🪐 Not bad! Keep learning about space! |
| 0-39% (0-3/10) | 🌍 Keep exploring! Space has much to teach! |

## 🎨 Design Highlights

- **Gradient Backgrounds** - Beautiful purple to blue gradients
- **Smooth Animations** - Slide-in effects, pulse animations for correct answers, shake for incorrect ones
- **Color Coding** - Green for correct, red for incorrect, purple for primary actions
- **Accessibility** - High contrast ratios and semantic HTML structure
- **Keyboard Navigation** - Full keyboard support with Tab navigation and Enter/Space activation

## 🌐 Deploy to GitHub Pages

This repository is automatically deployed to GitHub Pages on every push to the main branch using GitHub Actions.

**Live Site**: [https://slowwanderer.github.io/space-quiz/](https://slowwanderer.github.io/space-quiz/)

### Automatic Deployment

The repository includes a GitHub Actions workflow that:
- Builds and deploys the site on every push to `master` branch
- Deploys to GitHub Pages automatically
- No manual deployment steps needed!

### Manual Deployment

If you want to deploy to GitHub Pages manually:

1. Go to your repository settings
2. Navigate to **Settings > Pages**
3. Select **Deploy from a branch** or **GitHub Actions**
4. Choose your source branch (usually `master` or `main`)
5. Save and wait for deployment to complete

## 🔧 Technical Details

### Stack
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with gradients, animations, and media queries
- **Vanilla JavaScript** - No frameworks or dependencies required

### Browser Support
- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Any modern browser with ES6+ support

### Performance
- Single file: ~15KB
- Load time: < 100ms
- Zero external requests
- Memory efficient

### File Structure
```
.
├── index.html          # Main quiz application
├── README.md           # This file
├── 지침서.md           # Korean guidance document
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions deployment workflow
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs or suggest features via GitHub Issues
- Submit pull requests with improvements
- Add new questions or features
- Improve documentation

### Areas for Contribution
- Adding more quiz questions
- Translating to additional languages
- Improving accessibility features
- Adding new themes or color schemes
- Performance optimizations

## 📝 License

This project is open source and available under the MIT License.

## 🌟 Questions?

Check the included **지침서.md** (Korean guidance document) for detailed usage instructions in Korean.

---

**Made with ❤️ for space enthusiasts**

*Last updated: October 24, 2026*
