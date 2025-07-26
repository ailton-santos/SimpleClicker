# SimpleClicker

**Game Developed in Unreal Engine 5.6 using Blueprints Visual Scripting**

![SimpleClickerl Engine](https://img.shields.io/badge/Unreal%20Engine-5.6+-blue?style=flat-square&logo=unrealengine)


## 📋 Project Overview

SimpleClicker is a basic clicker game developed as a learning project in Unreal Engine 5. The main objective was to understand the fundamentals of game development using the Blueprints visual scripting system without writing any C++ code.

**Current Status**: ✅ **FULLY FUNCTIONAL** - Players can interact with glass cubes that have fire effects on top and destroy them by pressing the spacebar.

### 🎯 Game Mechanics
- **Interactive glass cubes** with realistic shattered glass material
- **Fire particle effects** positioned on top of each cube
- **Keyboard input system** (Spacebar to destroy cubes)
- **Visual feedback** with on-screen messages
- **Urban environment** with modular building assets
- **Object destruction** with immediate response

## 🛠️ Technologies Used

- **Engine**: Unreal Engine 5.6
- **Programming**: Blueprints Visual Scripting (100% visual, no C++)
- **Rendering**: Nanite & Lumen (UE5 next-gen features)
- **Assets**: Advanced Glass Material Pack, Urban Buildings Pack, Starter Content
- **Particles**: Cascade Particle System (P_Fire)
- **Version Control**: Git & GitHub

## 🏗️ Technical Architecture

### Blueprint Components Created

#### 🎮 BP_SimpleCube
- **Function**: Main interactive cube object
- **Components**:
  - Static Mesh (Cube geometry)
  - Advanced Glass Material (Shattered glass effect)
  - Cascade Particle System (Fire effect)
  - Box Collision (Input detection)
- **Features**:
  - Auto Receive Input: Player 0
  - Spacebar input detection
  - Print String feedback system
  - Self-destruction on interaction
  - Fire effect scaling and positioning

#### 🎯 BP_ClickerGameMode
- **Function**: Game state manager
- **Responsibilities**:
  - Define game rules and flow
  - Configure default Player Controller
  - Manage initial game state
  - Player spawn point configuration

#### 🖱️ BP_ClickerPlayerController
- **Function**: Player input handler
- **Features**:
  - Mouse cursor enablement
  - Click event configuration
  - Input priority management
  - Interface between player and game world

## 📚 Lessons Learned

### Technical Skills Acquired
- ✅ **Blueprint Visual Scripting**: Mastered node-based programming without traditional coding
- ✅ **Component-Based Architecture**: Understanding of UE5's component system (Static Mesh, Collision, Particles)
- ✅ **Event-Driven Programming**: Input handling, event dispatching, and response systems
- ✅ **Game Framework Understanding**: Game Mode, Player Controller, and Pawn relationships
- ✅ **Material System**: Advanced material application and asset integration
- ✅ **Particle Effects**: Cascade particle system implementation and configuration
- ✅ **Asset Pipeline**: Importing and integrating external content packs
- ✅ **Project Organization**: Professional folder structure and asset management


## 📖 Learning Resources

### Official Documentation
- [Unreal Engine 5 Documentation](https://docs.unrealengine.com/5.0/en-US/)
- [Blueprint Visual Scripting Guide](https://docs.unrealengine.com/5.0/en-US/blueprints-visual-scripting-in-unreal-engine/)
- [Game Framework Documentation](https://docs.unrealengine.com/5.0/en-US/game-framework-classes-in-unreal-engine/)

### Community Resources
- [Unreal Engine YouTube Channel](https://www.youtube.com/UnrealEngine)
- [Epic Games Developer Community](https://dev.epicgames.com/community/)
- [Unreal Engine AnswerHub](https://answers.unrealengine.com/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙋‍♂️ Author

**Ailton Santos**
- GitHub: [@ailton-santos](https://github.com/ailton-santos)
- Project: [SimpleClicker](https://github.com/ailton-santos/SimpleClicker)

---

*Developed with ❤️, persistence, and lots of Blueprint debugging in Unreal Engine 5.6*

**Project Status**: 🎉 **Successfully Completed Learning Objectives** 🎉
