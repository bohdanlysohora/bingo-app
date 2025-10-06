# Bingo Card App 🎯

A simple and intuitive web application for creating and managing bingo cards. Perfect for tracking tasks, organizing activities, or playing bingo games.

## Features

- ✅ **Create Cards**: Add custom cards with any name
- 🎯 **Mark as Done**: Click cards to move them to the "Done" list
- ↩️ **Move Back**: Click done cards to move them back to available
- 💾 **Auto-Save**: All cards are automatically saved to browser storage
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile devices
- 🎨 **Beautiful UI**: Modern gradient design with smooth animations

## How to Use

1. **Open the App**: Simply open `index.html` in your web browser
2. **Add a Card**: 
   - Type a name in the input field
   - Click "Add Card" or press Enter
3. **Mark as Done**:
   - Click on any card in the "Available Cards" section
   - It will move to the "Done Cards" section with a green color
4. **Move Back**:
   - Click on any card in the "Done Cards" section
   - It will move back to "Available Cards"

## Technical Details

- **Pure HTML/CSS/JavaScript**: No frameworks or dependencies required
- **LocalStorage**: Cards persist between browser sessions
- **Single File**: Everything is contained in one `index.html` file
- **Cross-Browser Compatible**: Works in all modern browsers

## Getting Started

### Option 1: Direct File Access
```bash
# Clone the repository
git clone https://github.com/bohdanlysohora/bingo-app.git
cd bingo-app

# Open index.html in your browser
open index.html  # macOS
xdg-open index.html  # Linux
start index.html  # Windows
```

### Option 2: Using a Web Server
```bash
# Using Python
python3 -m http.server 8000

# Using Node.js (npx)
npx http-server

# Then open http://localhost:8000 in your browser
```

## Screenshots

### Initial View
![Initial Page](https://github.com/user-attachments/assets/6a9a1530-fccb-4f5c-876a-326e928a6022)

### Cards Added
![Cards Added](https://github.com/user-attachments/assets/bf931740-323e-4eae-a4bd-875c182591ea)

### Cards Marked as Done
![Cards Done](https://github.com/user-attachments/assets/155ad0aa-fff6-4903-bf4a-b1c55188af5a)

## License

MIT License - Feel free to use this project for any purpose!
