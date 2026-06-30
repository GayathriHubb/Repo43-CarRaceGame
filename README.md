# 🏎️ Car Race Game

A fast-paced, interactive Windows desktop game built with C# and Windows Forms. Race against obstacles, collect coins, and enjoy immersive sound effects in this exciting car racing experience!

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation & Setup](#installation--setup)
- [How to Play](#how-to-play)
- [Controls](#controls)
- [Game Features](#game-features)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [License](#license)

## 🎮 Overview

**Car Race Game** is a dynamic racing game where players navigate a car through traffic, collect coins for points, and avoid collisions. The game features real-time gameplay mechanics, engaging sound effects, and a responsive user interface built with Windows Forms.

## ✨ Features

- 🎯 **Dynamic Gameplay**: Navigate your car through moving obstacles and traffic
- 💰 **Coin Collection System**: Collect coins scattered throughout the game to increase your score
- 🔊 **Sound Effects**: Immersive audio experience with alert sounds during gameplay
- 🚗 **Smooth Graphics**: Rendered game environment with visual car representation
- 📊 **Score Tracking**: Real-time scoring system based on coins collected and distance traveled
- 🎨 **Professional UI**: Intuitive Windows Forms interface with game controls
- ⚡ **Responsive Controls**: Smooth and immediate response to player input

## 🛠️ Tech Stack

- **Language**: C# (.NET 8.0)
- **Framework**: Windows Forms
- **Target Platform**: Windows (AnyCPU)
- **IDE**: Visual Studio / Visual Studio Code
- **Audio**: WAV format sound files
- **Resources**: Custom icons and embedded resources

## 📦 Installation & Setup

### Prerequisites

- Windows 10 or later
- .NET 8.0 Runtime or SDK installed
- Visual Studio 2022 or compatible IDE

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/GayathriHubb/Repo43-CarRaceGame.git
   cd Repo43-CarRaceGame
   ```

2. **Open the project**
   ```bash
   # Open in Visual Studio
   open CarRacing.csproj
   ```

3. **Build the solution**
   - In Visual Studio: `Build` → `Build Solution` (Ctrl+Shift+B)
   - Or via command line:
     ```bash
     dotnet build
     ```

4. **Run the application**
   - In Visual Studio: `Debug` → `Start Debugging` (F5)
   - Or via command line:
     ```bash
     dotnet run
     ```

## 🎮 How to Play

1. Launch the application
2. Click the **Start Game** button to begin
3. Navigate your car to avoid obstacles and traffic
4. Collect coins to earn points
5. Don't collide with other vehicles!
6. Try to achieve the highest score possible

## 🎮 Controls

| Control | Action |
|---------|--------|
| **Arrow Keys** (← →) | Move car left/right |
| **Up Arrow** | Accelerate |
| **Down Arrow** | Brake/Reverse |
| **ESC** | Pause/Resume Game |
| **Space** | Start Game / Reset |

## 🎯 Game Features

### Scoring System
- **Coins**: Each coin collected = +10 points
- **Distance**: Bonus points for distance traveled
- **Multiplier**: Increase multiplier by collecting consecutive coins without collisions

### Obstacles
- Traffic vehicles with varied speeds
- Random obstacle placement for unpredictability
- Collision detection with instant feedback

### Audio
- **Alert Sound**: Plays when collecting coins or near danger
- **Background Music**: Ambient gameplay soundtrack
- **Collision Sound**: Feedback on impact events

### Difficulty Levels
- Progressive difficulty as score increases
- Faster obstacles and more traffic at higher levels
- Dynamic gameplay adjustments

## 📁 Project Structure

```
Repo43-CarRaceGame/
├── CarRacing.csproj           # Project configuration file
├── RaceCarRed.ico             # Application icon
├── EchoAlert.wav              # Sound effect file
├── Images/                    # Game graphics and sprites
├── Properties/
│   ├── Resources.resx         # Embedded resources
│   └── Resources.Designer.cs  # Auto-generated resources
├── README.md                  # This file
└── LICENSE                    # MIT License
```

## 📋 Requirements

- **Runtime**: .NET 8.0 Windows Runtime
- **Memory**: Minimum 256 MB RAM
- **Display**: 1024x768 minimum resolution (1920x1080 recommended)
- **Audio**: Sound card for audio effects (optional)

### Dependencies

All dependencies are managed through the .NET SDK and are automatically restored during build:
- Windows Forms Framework
- System libraries for Windows-specific features

## 🚀 Development

### Building from Source

```bash
# Restore dependencies
dotnet restore

# Build the project
dotnet build -c Release

# Run with debugging
dotnet run -c Debug

# Publish as standalone executable
dotnet publish -c Release -f net8.0-windows --self-contained
```

### Project Configuration

- **Target Framework**: .NET 8.0 (Windows)
- **Nullable Reference Types**: Enabled
- **Overflow Checking**: Enabled in Debug and Release builds
- **Application Icon**: RaceCarRed.ico
- **Company**: Gayathri
- **Product**: CarRace

## 🎨 Customization

### Modifying Game Parameters

You can customize game settings by modifying configuration values in the source code:
- Game speed and difficulty
- Coin spawn rates
- Obstacle frequency
- Score multipliers

### Adding New Assets

- Place new image files in the `Images/` folder
- Add sound files as WAV format to the project root
- Update `CarRacing.csproj` to include new resources

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Audio not playing | Verify `EchoAlert.wav` is in the output directory |
| Game window won't open | Ensure Windows Forms components are installed |
| Slow performance | Reduce graphics complexity or close background applications |
| Controls unresponsive | Verify keyboard drivers are up to date |

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

MIT License © 2026 Gayathri

Permission is hereby granted to use, modify, and distribute this software freely, provided the original license and copyright notice are included.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support & Contact

For issues, questions, or suggestions:
- Open an issue on [GitHub Issues](https://github.com/GayathriHubb/Repo43-CarRaceGame/issues)
- Contact: [GitHub Profile](https://github.com/GayathriHubb)

## 🎓 Learning Resources

This project demonstrates:
- Windows Forms GUI development in C#
- Game loop and event-driven programming
- Collision detection algorithms
- Audio integration in .NET applications
- Resource management and embedding
- Object-oriented design principles

## 🌟 Features Roadmap

- [ ] Mobile version (Xamarin/MAUI)
- [ ] Leaderboard system
- [ ] Multiple difficulty levels
- [ ] Power-up system
- [ ] Level progression
- [ ] Multiplayer support
- [ ] Custom car skins
- [ ] Advanced AI opponents

---

**Happy Racing! 🏁**

*Built with ❤️ using C# and .NET*
