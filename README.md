# CodeMaestro
**AI-powered copilot for game development.**

Transform your Unity workflow with intelligent assistance and automation. CodeMaestro understands your game development needs and helps you build better games faster.

```
"Create a player movement script with WASD controls"
"Add a health system to my player character" 
"Set up a main menu with play and quit buttons"
```

## Quick Start

**1. Download CodeMaestro**
Get the latest version for your platform:
- **macOS:** CodeMaestro-1.0.xx-mac-arm64.dmg / CodeMaestro-1.0.xx-mac-x64.dmg
- **Windows:** CodeMaestro-1.0.xx-win-x64.exe

**2. Install Unity MCP Connector**
Install our Unity MCP connector: [codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp)

**3. Connect and Build**
- Launch CodeMaestro and connect to your Unity project
- AI will analyze your entire project (scripts, assets, scenes)
- Start building your game with full project context!

## Latest Features (v1.0.15)

#  Changelog
##  🏗️ CHANGES
### ✨ New Features
Secure Local Indexing  
Added full secure local indexing.  
⚠️ Important: No files will ever be stored on the server, even temporarily.  

### Vector Search Tools  
Introduced new vector-based search tools for large repositories.  

### 🔄 Updates
Agent Logic  
Improved agent logic for better accuracy and efficiency.  

User Projects  
All user projects previously stored on the server have been permanently deleted.  
When you log in to the application, you will now be prompted to add your project again.  

### 🎨 Improvements
Agent UI  
Updated agent UI for easier reading and better usability.  

### Artifact Visualization  
Enhanced artifact visualization for improved clarity.  

### Bug Fixes  
Fixed multiple UI-related bugs to ensure a smoother experience.  

📝 Update Instructions
After updating to this version:  
- Add your project again when prompted after launching the application.  
- Enjoy secure, local-only indexing with no server storage.  
- Explore the new vector search tools for large repositories.  


## What CodeMaestro Can Do

**Unity Integration** - Seamless integration with Unity Editor for complete game development workflow

**Game Scripts Generation** - Create player controllers, game mechanics, and system scripts with AI

**Asset Management** - Intelligent handling of prefabs, materials, and game assets

**Scene Setup** - Automated scene creation and GameObject configuration

**Game Logic Assistance** - AI-powered help with game mechanics, physics, and interactions


## How It Works

CodeMaestro connects to Unity through our Advanced Unity MCP connector ([codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp)), providing deep integration with your Unity projects. The AI understands your entire project structure, including scripts, assets, scenes, and configurations.

**Full Project Context:**
- **Complete Asset Awareness** - AI can see and work with all your project assets (Scenes, prefabs, AnimationControllers, etc.)
- **Scene Understanding** - Knows about GameObjects, components, and hierarchy structure
- **Script Analysis** - Reads and understands your existing C# scripts and their relationships
- **Project Settings** - Accesses build settings, input manager, and project configurations

**Key Components:**
- **Unity MCP Connector** - Bridges CodeMaestro with Unity Editor for real-time communication
- **Game Development AI** - Specialized in Unity C# scripting and game mechanics  
- **Asset Intelligence** - Understands your project's assets and how they connect

**💡 Tip:** Use the Prompt Refine feature to get more precise responses for your specific game development needs.

## Requirements

- Modern operating system (macOS 10.15+, Windows 10+, or Linux)
- Internet connection for AI features

## Troubleshooting

### MCP Launch Errors

If you encounter errors when launching any MCP (including test echo MCP), follow these steps:

1. **Completely uninstall CodeMaestro**
   - Remove the CodeMaestro application from your system
   
2. **Delete the cache folder**
   After uninstalling, manually delete the CodeMaestro cache directory:
   - **macOS:** `~/.codemaestro`
   - **Windows:** `%USERPROFILE%\.codemaestro`
   - **Linux:** `~/.codemaestro`

3. **Reinstall CodeMaestro**
   - Download and install the latest version
   - Reconnect to your Unity project

This process clears all cached data and configurations, resolving most MCP-related launch issues.

---

**Made by [Code Maestro](https://www.code-maestro.com) • [Join our Discord](https://discord.gg/bsFRAqATXz) • [Report Issues](https://github.com/codemaestroai/codemaestro/issues) • [License](./LICENSE)**





