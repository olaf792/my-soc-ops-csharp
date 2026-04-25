# 🎮 Welcome to Soc Ops!

Your development environment is now ready! Here's a quick tour to help you navigate this project.

## 🚀 What is Soc Ops?

**Soc Ops** is a Social Bingo game designed for in-person mixers. Players find people who match various social prompts and mark off their bingo card to get 5 in a row — it's a fun way to break the ice at events!

- 🎮 **Live Demo:** https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/
- 📚 **Local Workshop:** See `workshop/` for interactive guides

---

## 📁 Project Structure at a Glance

```
SocOps/                    # Main Blazor WebAssembly application
├── Components/            # Reusable UI components
│   ├── GameScreen.razor   # Main game interface
│   ├── BingoBoard.razor   # Bingo card display
│   └── StartScreen.razor  # Game start screen
├── Services/              # Business logic
│   ├── BingoGameService.cs      # Game state management
│   └── BingoLogicService.cs     # Game rules & validation
├── Data/                  # Static data
│   └── Questions.cs       # Bingo card questions/prompts
└── wwwroot/               # Static assets (CSS, bootstrap)
```

---

## 🛠️ Development Commands

Everything is set up and running! Here's what you need to know:

### Build the Project
```bash
cd SocOps
dotnet build
```

### Run the Development Server
```bash
cd SocOps
dotnet run
```
Server runs on: **http://localhost:5166**

### Install Dependencies
```bash
cd SocOps
dotnet restore
```

---

## 🎯 Quick Start Checklist

- ✅ **Environment verified:** .NET 10.0.202 SDK installed
- ✅ **Dependencies restored:** All NuGet packages ready
- ✅ **Project built:** Blazor WebAssembly compiled
- ✅ **Dev server running:** http://localhost:5166
- ✅ **Browser opened:** App is accessible!

---

## 📚 Next Steps – Choose Your Path

### 🎓 **New to the Project?**
1. **Play the game** at http://localhost:5166 to understand the UX
2. Read the **Overview** in `workshop/00-overview.md`
3. Follow the **Setup & Context Engineering** guide in `workshop/01-setup.md`

### 💡 **Ready to Start Coding?**
1. **Generate Agent Instructions:** In VS Code Chat, run `/github.copilot-instructions generate`
2. **Design-First Frontend:** Check `workshop/02-design.md` for UI/UX improvements
3. **Build Features:** Use GitHub Copilot Chat (`Ctrl+I` or `Cmd+I`) for intelligent code suggestions

### 🤖 **Want to Build with AI?**
1. **Quiz Master Agent:** `workshop/03-quiz-master.md` — Create custom question sets
2. **Multi-Agent Development:** `workshop/04-multi-agent.md` — Work with parallel AI assistants
3. **Complete Challenge:** `workshop/05-complete.md` — Full integration exercise

---

## 🔧 Key Files to Know

| File | Purpose |
|------|---------|
| **SocOps/Program.cs** | Bootstrap Blazor app, DI container setup |
| **SocOps/App.razor** | Root component & router |
| **SocOps/Components/GameScreen.razor** | Main game UI |
| **SocOps/Services/BingoGameService.cs** | Game state, score tracking |
| **SocOps/Services/BingoLogicService.cs** | Win detection, game rules |
| **SocOps/Data/Questions.cs** | Bingo card prompts |

---

## 💬 Using GitHub Copilot

This workspace is optimized for AI-assisted development:

- **Chat:** Press `Ctrl+I` (Cmd+I on Mac) to ask questions about the code
- **Inline Edit:** Use `Copilot: Edit` to refactor or generate code
- **Context:** Additional `.instructions.md` files guide Copilot for better suggestions

**Tip:** Ask Copilot to "explain the bingo logic" or "add a new question category" — it understands your codebase!

---

## 📖 Workshop Modules

| Module | Duration | Topics |
|--------|----------|--------|
| [00-overview](workshop/00-overview.md) | 5 min | Project walkthrough & setup |
| [01-setup](workshop/01-setup.md) | 15 min | **← You are here!** Context engineering |
| [02-design](workshop/02-design.md) | 20 min | Frontend design with Copilot |
| [03-quiz-master](workshop/03-quiz-master.md) | 25 min | Custom Quiz Master agent |
| [04-multi-agent](workshop/04-multi-agent.md) | 30 min | Parallel AI development |
| [05-complete](workshop/05-complete.md) | 45 min | Full integration challenge |

---

## 🐛 Troubleshooting

**Dev server won't start?**
```bash
# Kill any existing processes and try again
pkill -f "dotnet run"
cd SocOps && dotnet run
```

**Build failing?**
```bash
# Clean and rebuild
cd SocOps
dotnet clean
dotnet restore
dotnet build
```

**Port 5166 already in use?**
- The app will pick an alternate port — check the console output for the correct URL

---

## 🌟 Have Fun!

This is a learning project. Experiment, ask Copilot questions, and enjoy the process of building with AI!

**Questions?** Check the [main README](README.md) or the [workshop guide](workshop/GUIDE.md).

---

**Happy coding! 🚀**
