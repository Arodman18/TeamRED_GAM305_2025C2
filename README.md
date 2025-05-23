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
✅ Introduce character model and develop animations.  
✅ Implement functional character movement and controls.  
✅ Develop one working enemy AI.  
✅ Design modular static meshes for environments.  
✅ Implement interactable objects.  

### **Week 4 - Alpha Stage Goals (First Playable Build)**
## Alpha Download Link ## **https://we.tl/t-ozHATrzKH3**
✅ Implement core movement mechanics (running, jumping, dashing, ledge grabbing).  
✅ Implement basic combat system (shooting, hit detection, enemy reactions).  
✅ Develop AI behavior (patrolling, shooting, taking damage).  
✅ Create one **fully playable level** with obstacles, hazards, and interactive elements.  
✅ Add placeholder UI for health & power-ups.  
✅ Ensure the game is **playable on PC**.  

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

# TeamRED 4-2 Project Log: Team Reflection and Alpha Release
The testing process went well with many bugs identified and reported using methods the team intended to use internally. Once reported, the team was able to replicate and resolve the bugs in a timely manner. Using multiple methods to test and retest the bugs ensured a desirable outcome.

Bugs were identified by developers during the testing process by playing and testing specific mechanics. Bugs were categorized based on which development area they were in, which were then resolved via extensive research, where multiple people would go throughout the project and problem-solve the different bugs, going between each area that were categorized, based on most problematic to least problematic for the development process.

As an example, some of the coding ended up not working out, which the coder/lead designer would have to go in and correct to fix and ensure the character would work properly based on the level. Or how some of the level would make the player character go off the level, which would be on the level designer to ensure that doesn’t happen.

We could have improved the testing process by developing a more specific checklist for mechanics to be tested. For example, instead of testing “character movement,” we could list out elements of the character movement system to be tested. Having a clear goal would have improved the approach our QA testers took and increased the feedback provided.

Our team utilized GitHub Desktop and Hack-n-plan which both came in very helpful and contributed to our success. A common roadblock for many teams and this course in general has been using Git and source control, but using the visual aspects of GitHub Desktop has helped our team stay organized and on track without any major issues.

Using Hack-n-plan, we have been able to assign and report progress very easily, with visibility from each team member being accessible. This has helped to identify specific tasks, improving session efficiency and ensuring scope management.

We have used Discord as the primary form of communication and have been able to maintain contact.
Our game is a 2.5D sidescroller and many of the Unreal Engine 5 provided templates that we planned to use were not helpful. In fact, we scrapped many of them to create our own custom blueprints with functionality that met our intentions.

Our approach using tools and techniques outlined in the game design document was greatly affected by how we as a team would work together to develop the project. As a team geographically separated, we needed a way to communicate while actively working on the project, and GitHub and Hack-n-plan made that possible.

The chosen game type also affected our decision to use specific game assets and design techniques that encouraged our workflow. Each of our inputs are critical to the outcome of level design, functionality, and the game environment, which forced us to work closely and modularly.

# TeamRED 5-2 Project Log: Team Reflection and Beta Release

## BETA RELEASE LINK
https://we.tl/t-vVLGpYdRoe

## What parts of the plan did the team perceive to go well in relation to the last stage evaluation?
The team was able to fix many of the bugs identified in the last stage evaluation, as well as take feedback from play testers to improve the gameplay. We perceived this as a success due to the positive feedback we received on the changes and overall game development progress. Our familiarity with GitHub has increased, and we've experienced far fewer issues with pull requests and merging.

## What parts of the plan did the team perceive to go wrong in relation to the last stage evaluation?
While we feel most of our progress since Alpha went well, we identified a few issues that would require gameplay changes to properly address.
Another area that didn’t go well was AI implementation. The AI pathing and decision tree did not integrate well with the 2.5D side scroller template. While it could have been fixed, it wasn’t worth the time investment compared to other simpler, more effective options.

## How were the previous evaluations integrated into this latest stage?
Previous evaluations helped guide our goals for completing the Beta stage, especially with feedback from play testers. We used this feedback to assign specific tasks to team members that would address key issues and improve the game overall.

## What would you do differently to improve the collaboration or development process?
If we could change anything, we would further combine responsibilities to increase output. For example, collaborating across each other's task lists could help changes get made faster. It also would have helped if each of us had more skills in different areas, and if we had more time to work together in person or as a full-time team. We've all been busy with outside work, which has made it difficult to meet regularly.

## Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
We found it unhelpful to rely too heavily on one person for a single role. While it got the job done by the end of the term, it wasn’t ideal and felt suboptimal, especially as things got busier outside of school. As for tools, some ideas and tools we wanted to implement never made it into the final Beta because they either didn’t work as intended or were too complex to build with the time we had.

## Identify the completed stage of development of the intended Beta and address the project schedule to meet Final Release development deadline.
The intended Beta stage is a fully playable gameplay loop across two levels. This gives us the opportunity to focus on polish and fine-tuning in preparation for the final release next week at the end of Module 6.

## Repository:
Arodman18/TeamRED_GAM305_2025C2: Game Development project TeamRED, GAM-305 C-2 SNHU

# TeamRED 6-2 Project Log: Team Reflection and Final Release

## GitHub Repo:
Arodman18/TeamRED_GAM305_2025C2: Game Development project TeamRED, GAM-305 C-2 SNHU

## Final Release DL Link:
https://we.tl/t-kVjOhJFHxh

As a team, you will routinely conduct reviews based on your progression towards the plans that you created. Evaluate the plan that your team created in Module Three from an artist’s standpoint.

## After completing your plan analysis, conduct a team reflection and consider the following:
## What parts of the plan did the team perceive to go well in relation to the last stage evaluation?
The team successfully shifted focus from new feature implementation to polishing existing mechanics and improving visual and audio elements based on play tester feedback. The decision to prioritize quality over quantity resulted in a more stable and enjoyable experience. Communication between team members also improved as we became more familiar with each other's workflows, which helped us stay organized and on track for the final release deadline.

## What parts of the plan did the team perceive to go wrong in relation to the last stage evaluation?
While we managed to polish a lot of the game, we underestimated the amount of time needed for final testing and bug-fixing before release. Some small but noticeable glitches slipped through during internal testing, and late-stage changes created new bugs that could have been avoided with more time allocated for testing. Even though the bugs and issues were fixed before the deadline, it was still a hassle with the amount of time given

## How were the previous evaluations integrated into this latest stage?
The feedback from earlier evaluations continued to guide our priorities, especially around bug fixes, balance, and usability improvements. Specific issues pointed out by both the team and play testers were converted into task lists and completed in order of priority. Our process of assigning focused roles and smaller goals based on prior evaluations helped streamline the final sprint toward the release.

## What would you do differently to improve the collaboration or development process?
For future projects, we would start final testing earlier and schedule more structured check-ins to ensure consistent progress and early detection of last-minute issues. It would also help to rotate roles slightly more, so everyone gains broader experience in all areas, especially when someone is unavailable. More frequent in-person or real-time collaboration sessions could have reduced the number of misunderstandings and delays as well.

## Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
No specific tools stood out as unhelpful this time, but we did encounter some challenges when using placeholder assets and prototype scripts for too long without replacing them. Leaving these in place until the later stages slowed down final integration and polish. Going forward, swapping out temporary assets earlier would prevent last-minute scrambles and make final playtesting more accurate.




