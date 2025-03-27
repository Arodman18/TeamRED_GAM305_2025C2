# TeamRED_GAM305_2025C2
**Game Development Project - TeamRED, GAM-305 C-2 SNHU**

## Module Two Team Project Plan - Game Design Document

## Project Overview
- **Project Title:** Neon Nine Lives  
- **Game Type:** 3D Side-Scroller (2.5D)  
- **Genre:** Sci-Fi Platformer  
- **Date:** March 16, 2025  
- **Target Platform:** PC  
- **Target Audience:** Casual solo players  
- **Course:** GAM-305  
- **Source Control:** [GitHub Repository](https://github.com/Arodman18/TeamRED_GAM305_2025C2.git)  

## Team Members & Roles
- **Andrew Rodman** - Game Programmer  
- **Deon Knighton** - Game Design Artist  
- **Alex Strata** - Game Level Designer  
- **UI/UX Designer** - *TBD*  

## Team Communication
- **Primary Method:** Discord  
- **Meeting Frequency:**  
  - **Friday:** 5:00 PM PST (Saturday 11:00 AM JST)  
  - **Saturday:** 5:00 PM PST (Sunday 11:00 AM JST)  
- **Task Management:** Hack-n-Plan  

---

## Game Overview
Neon Nine Lives is a **2.5D side-scrolling action-adventure platformer** that emphasizes **fluid movement, engaging combat, and visually appealing level design**. Players will navigate various levels filled with enemies, platforming challenges, and puzzles.

### **Core Gameplay Features**
- **Character Movement:** Running, jumping, double-jumping, crouching, wall-hanging, ledge grabbing.  
- **Combat System:** Basic weapon shooting with enemy hit reactions.  
- **Level Design:** Multi-layered environments with interactive elements such as moving platforms, hazards, and secret areas.  
- **Enemy AI:** Basic patrol, chase, and attack patterns. Enemies include sci-fi robots and flying drones.  
- **Puzzle Elements:** Lever-activated doors, weight-sensitive platforms, and simple physics-based puzzles.  
- **Collectibles & Progression:** Power-ups, unlockable abilities, and hidden items.  

### **Art & Visual Style**
- Stylized **3D models** with hand-painted textures.  
- Smooth animations for **characters and environmental interactions**.  
- **Parallax backgrounds** to enhance the 2.5D depth perception.  
- **Vibrant lighting and atmospheric effects** for immersive visuals.  

### **Assets Used**
- **Synty Sci-Fi Character Pack**  
- **Cubes**  
- **Niagara VFX**  

---

## Technical Considerations
- Developed in **Unreal Engine**.  
- **Physics-based movement system** for smooth platforming mechanics.  
- Optimized **animation system** for fluid character movement.  
- **Modular level design** for scalable content expansion.  

## Sound & Music
- **Background music**  
- **Unique sound effects** for movement, combat, and interactions.

---

## **Development Roadmap**
### **Week 3**
🔹 Introduce character model and develop animations.  
🔹 Implement functional character movement and controls.  
🔹 Develop one working enemy AI.  
🔹 Design modular static meshes for environments.  
🔹 Implement interactable objects.  

### **Week 4 - Alpha Stage Goals (First Playable Build)**
🔹 Implement core movement mechanics (running, jumping, dashing, ledge grabbing).  
🔹 Implement basic combat system (shooting, hit detection, enemy reactions).  
🔹 Develop AI behavior (patrolling, shooting, taking damage).  
🔹 Create one **fully playable level** with obstacles, hazards, and interactive elements.  
🔹 Add placeholder UI for health & power-ups.  
🔹 Ensure the game is **playable on PC**.  

### **Week 5**
🔹 Add a second enemy type (flying enemy).  
🔹 Implement additional playable levels.  
🔹 Implement working **health bar** UI.  
🔹 Implement obtainable and functional power-ups.  

### **Week 6**
🔹 Integrate **basic sound effects and background music**.  
🔹 Develop and implement a **functional main menu**.  
🔹 Finetune gameplay mechanics and balance.  

### **Week 7 - Beta Stage Goals (Near-Complete Build)**
🔹 Complete **multiple playable levels** with refined gameplay elements.  
🔹 Polish **combat mechanics** (combos, parries, special attacks).  
🔹 Expand **AI behavior** with advanced attack patterns.  
🔹 Implement **full collectibles, upgrades, and progression**.  
🔹 Refine UI with animations and responsive elements.  
🔹 Finalize **sound design** with adaptive music and environmental effects.  
🔹 Conduct **playtesting and debugging** for stability.  

---

## **How to Run the Project**
1. **Clone the repository:**
   ```sh
   git clone https://github.com/Arodman18/TeamRED_GAM305_2025C2.git




# Module Three Project Log - Team Development: QA and Testing Plan

## Testing Process
The testing process will be completed in three steps:

- **First**, the gameplay loop must successfully be completed in editor build.  
  - This includes launching the level, completing the level, and returning to the main menu.
- **Second**, no open bug reports in editor build.
- **Then**, play testing will be completed by QA team members in editor build.
- If no game-breaking bugs are found, the game will be packaged for demo shipping.
- QA team members will collaboratively play test, specifically testing each checklist item to ensure functionality.

---

## Schedule: Play Test
The play test will be completed internally, identifying that the core gameplay features are working as intended and the gameplay loop is engaging.

---

## Schedule: Demo Test
The demo test will ensure that a packaged build is ready for launch, ensuring gameplay features are functional and the gameplay loop can be completed.

---

## Schedule: Code Release
Code release schedule will be the end of **Week 4 (30 Mar 25)** and will include a playable build that is ready for more rigorous testing by players outside of the development team.

---

## Checklist

### Play Test
- Character movement

### Demo Test
- Launch level from main menu.
- Checkpoint respawn on death.
- Return to main menu on level complete.
- Return to main menu on game over.

---

## Test Plan Updates
The QA team lead will revise and expand the test plan after each development phase to reflect newly added features, recently fixed issues, and unresolved bugs. Each update will include clearly defined test cases along with target completion dates to ensure timely and thorough quality assurance throughout the development cycle.

---

## Reporting Bugs
Bugs will be reported using **Hack-n-plan** by QA team members.  
During Alpha phase, the team will have a dedicated bug reporting solution available to players participating that they can submit bug reports to.

---

## Tracking Bugs
- Bugs will be tracked in **Hack-n-plan**.
- All bugs reported in Alpha phase by players will be validated by a QA member and added to the bug tracker in Hack-n-plan if repeatable.
- All bugs will be tracked and categorized to show similar occurrences in case not originally repeatable.

---

## Engagement and Collaboration
Team meetings to finalize the test build, play test, and then package the demo.  
A team meeting will be scheduled to test the demo build prior to Alpha release.

---

## Repository URL
[https://github.com/Arodman18/TeamRED_GAM305_2025C2](https://github.com/Arodman18/TeamRED_GAM305_2025C2)
