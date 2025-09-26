# Dungeon Generator

A procedural dungeon generator web application built with React that creates intricate maze-like dungeon layouts perfect for tabletop RPGs, game development, or just for fun!

![Dungeon Generator Demo](https://github.com/user-attachments/assets/2962f265-1bd9-4b39-ad09-a2467ba502a1)

## 🚀 Live Demo

Visit the live application: **[wastrilith2k.github.io](https://wastrilith2k.github.io)**

## ✨ Features

- **Procedural Generation**: Creates unique dungeon layouts every time using advanced maze generation algorithms
- **Visual Rendering**: Real-time visualization of the generated dungeon with different colors for:
  - 🟫 **Walls** (brown/red areas) - Impassable barriers
  - ⬛ **Corridors** (black paths) - Walkable passages  
  - 🟦 **Special Rooms** (blue areas) - Important chambers or features
  - 🟣 **Connections** (purple) - Doorways and transitions
- **Optimized Generation**: Efficient algorithms that complete generation in hundreds of iterations
- **Dead End Removal**: Post-processing to clean up unnecessary dead ends for better dungeon flow
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Instant Results**: Fast generation with real-time progress logging

## 🛠️ Technology Stack

- **Frontend**: React.js
- **Styling**: CSS3 with responsive design
- **Build Tool**: Create React App (CRA)
- **Deployment**: GitHub Pages
- **Languages**: JavaScript, HTML5, CSS3

## 🎮 How It Works

The dungeon generator uses sophisticated algorithms to:

1. **Initialize Grid**: Creates a base grid structure
2. **Generate Maze**: Uses recursive algorithms to carve out corridors and rooms
3. **Remove Dead Ends**: Post-processes the maze to eliminate unnecessary dead ends
4. **Add Features**: Places special rooms, doors, and connections
5. **Render**: Displays the final dungeon with color-coded elements

The console output shows the generation progress:
- Iteration count during maze generation
- Dead end removal iterations
- Completion status

## 📁 Project Structure

```
wastrilith2k.github.io/
├── index.html              # Main HTML file
├── manifest.json            # PWA manifest
├── favicon.ico             # Site favicon
├── logo192.png             # App icon (192x192)
├── logo512.png             # App icon (512x512)
├── robots.txt              # Search engine instructions
├── asset-manifest.json     # Build asset mappings
└── static/                 # Built React application assets
    ├── css/
    │   ├── main.1ec7c1cf.chunk.css     # Compiled styles
    │   └── main.1ec7c1cf.chunk.css.map # Source map
    └── js/
        ├── main.4c2c1a99.chunk.js      # Main application logic
        ├── 2.884b725a.chunk.js         # React/vendor libraries
        ├── 3.b1a9b25e.chunk.js         # Additional chunks
        ├── runtime-main.2916099a.js    # Webpack runtime
        └── *.map files                 # Source maps
```

## 🚀 Local Development

To run this project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/wastrilith2k/wastrilith2k.github.io.git
   cd wastrilith2k.github.io
   ```

2. **Serve the files**
   Since this is a built React app, you can serve it with any static file server:
   
   **Using Python 3:**
   ```bash
   python3 -m http.server 8000
   ```
   
   **Using Node.js (http-server):**
   ```bash
   npx http-server . -p 8000
   ```
   
   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

3. **Open your browser**
   Navigate to `http://localhost:8000`

## 🎨 Customization

The dungeon appearance can be customized by modifying the CSS classes in the built files:

- `.wall` - Wall appearance (currently black)
- `.corridor, .room` - Corridor and room styling (grey borders)
- `.connection` - Connection styling (purple background)
- `.door` - Door styling (blue background)
- `#dungeon` - Main container positioning

## 🎯 Use Cases

- **Tabletop RPGs**: Generate unique dungeons for D&D, Pathfinder, or other RPG sessions
- **Game Development**: Use as inspiration or base for procedural dungeon generation in games
- **Educational**: Study maze generation algorithms and their implementations
- **Creative Writing**: Generate layouts for stories or world-building
- **Art & Design**: Create abstract geometric patterns and layouts

## 🤝 Contributing

Contributions are welcome! Since this is a built React application, here are some ways to contribute:

1. **Report Issues**: Found a bug or have a feature request? Open an issue!
2. **Documentation**: Help improve this README or add code comments
3. **Testing**: Test the application on different devices and browsers
4. **Feature Ideas**: Suggest new dungeon generation features or algorithms

### Development Setup

If you want to contribute to the source code:

1. This appears to be a built React app - you may need access to the original source code
2. The build artifacts suggest this was created with Create React App
3. Consider reaching out to the repository owner for access to the source files

## 📄 License

This project is open source. Please check with the repository owner for specific licensing terms.

## 👥 About

Created by [wastrilith2k](https://github.com/wastrilith2k)

---

**Enjoy generating awesome dungeons! 🏰**

*Feel free to star ⭐ this repository if you find it useful!*