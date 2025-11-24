# Quizzler - Christian Quiz Platform

## Project Overview
**Quizzler** is a single-file static web application featuring Christian quizzes including spiritual assessments and church history trivia. Originally designed for GitHub Pages deployment, it's been configured to run on Replit.

## Current Architecture
- **Type**: Static HTML/CSS/JavaScript application
- **Main File**: `index.html` - Contains all HTML, CSS, and JavaScript in one file
- **Server**: Python 3.11 HTTP server with cache-control headers
- **Port**: 5000 (frontend)
- **Host**: 0.0.0.0 for Replit compatibility

## Features
- Spiritual Assessment Quiz (40/70/100 questions)
- Christian History Trivia (30/50/70 questions)
- Netflix/Instagram-inspired modern UI
- Responsive mobile-first design
- Animated backgrounds with gradient orbs
- Personalized results with Bible verses

## Technology Stack
- Pure HTML5/CSS3/JavaScript (no frameworks)
- Python 3.11 (for simple HTTP server)
- Single-file architecture for easy deployment

## Setup on Replit (Completed)
1. ✅ Installed Python 3.11
2. ✅ Created Python HTTP server with cache-control headers
3. ✅ Configured workflow to run on port 5000
4. ✅ Added .gitignore for Python files

## File Structure
```
quizzler/
├── index.html          # Main application (all-in-one file)
├── server.py           # Python HTTP server with cache headers
├── .gitignore          # Python and IDE ignores
├── README.md           # Developer documentation
└── replit.md           # This file
```

## Running the Project
The workflow "Web Server" runs `python3 server.py` which serves the static files on port 5000.

## Future Expansion Ideas (from README)
- Bible Knowledge Quiz
- Spiritual Gifts Assessment
- Prayer Life Evaluation
- Fruit of the Spirit Check
- Worship Style Personality
- Progress tracking with LocalStorage
- Share results feature
- Dark/light theme toggle

## Original Purpose
Built for GitHub Pages deployment with zero dependencies, making it perfect for static hosting anywhere.

## Recent Changes
- **Nov 24, 2025**: Initial Replit setup with Python HTTP server
