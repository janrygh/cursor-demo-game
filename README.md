# 🎮 Cursor Demo Game - Blazor Adventure

A simple turn-based adventure game built with C# Blazor Server as part of a Cursor AI coding exercise.

## 🎯 Game Features

### ✅ Base Game (Complete)
- **5x5 Grid Map** - Interactive top-down game board
- **Player Character** - Wizard 🧙‍♂️ with animated effects
- **WASD/Arrow Key Controls** - Smooth keyboard movement
- **Turn-based Movement** - One cell at a time
- **Position Tracking** - Real-time coordinate display
- **Reset Functionality** - R key or button to restart

### 🚀 Planned Features
- **Exit Goal** - Win condition when reaching specific cell
- **Hazards/Bombs** - Avoid dangerous cells 💣
- **Moving Monster** - AI enemy that follows player 👹
- **Enhanced UI** - Better styling and animations
- **Real-time Movement** - Smooth transitions

## 🛠️ Tech Stack

- **C# .NET 9.0** - Latest .NET framework
- **Blazor Server** - Server-side rendering with SignalR
- **HTML5/CSS3** - Modern web standards
- **Interactive Components** - Real-time UI updates

## 🚀 Getting Started

### Prerequisites
- .NET 9.0 SDK or later
- Modern web browser

### Running the Game

1. **Clone the repository:**
   ```bash
   git clone https://github.com/larsnoma/cursor-demo-game.git
   cd cursor-demo-game
   ```

2. **Navigate to the Blazor app:**
   ```bash
   cd BlazorApp
   ```

3. **Run the application:**
   ```bash
   dotnet run --launch-profile http
   ```

4. **Open your browser:**
   - Navigate to: http://localhost:5000
   - Click on "Adventure Game" in the navigation menu
   - Or go directly to: http://localhost:5000/game

## 🎮 How to Play

1. **Focus the Game:** Click on the game grid to enable keyboard input
2. **Move Your Wizard:** Use WASD or Arrow Keys
   - **W** or **↑** - Move Up
   - **S** or **↓** - Move Down
   - **A** or **←** - Move Left
   - **D** or **→** - Move Right
3. **Reset Game:** Press **R** key or click the "Reset Game" button
4. **Watch the Status:** Green indicator means the game is ready for input

## 🏗️ Project Structure

```
cursor-demo-game/
├── BlazorApp/                      # Main Blazor application
│   ├── Components/
│   │   ├── Pages/
│   │   │   └── Game.razor         # Main game component
│   │   └── Layout/
│   │       └── NavMenu.razor      # Navigation with game link
│   ├── Properties/
│   │   └── launchSettings.json    # HTTP configuration
│   ├── Program.cs                 # App configuration
│   └── BlazorApp.csproj          # Project file
├── CommandLineApp/                # Initial console app (demo)
├── .gitignore                     # Git ignore rules
└── README.md                      # This file
```

## 🎨 Game Design

The game uses a simple coordinate system where:
- **Origin (0,0)** is at the top-left corner
- **X-axis** increases moving right
- **Y-axis** increases moving down
- **Grid size** is 5x5 cells
- **Player** starts at position (0,0)

## 🔧 Development

### Key Components
- **Game.razor** - Main game logic and UI
- **Interactive keyboard handling** - Real-time input processing
- **Blazor Server** - Enables real-time updates without page refreshes
- **CSS animations** - Player character pulse effect

### Development Commands
```bash
# Build the project
dotnet build

# Run with hot reload (recommended for development)
dotnet watch

# Run tests (when available)
dotnet test

# Publish for deployment
dotnet publish
```

## 🤝 Contributing

This project was created as a coding exercise with Cursor AI. Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Fork and create your own version

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🎯 Exercise Goal

Built as part of a team exercise to create a simple adventure game using Cursor AI assistance. The goal was to implement:

> "A simple turn-based adventure game on a 5x5 grid with WASD/arrow key movement, then progressively add features like exits, hazards, monsters, and quality-of-life improvements."

## 🙏 Acknowledgments

- Built with [Cursor AI](https://cursor.sh/) assistance
- Powered by [.NET Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
- Inspired by classic grid-based adventure games

---

**🎮 Ready to play? Start the app and navigate to the Adventure Game!** 