---
layout: post
title:  "Day 5 - Weekend Update"
date:   2024-05-28 08:29:51 -0700
categories: Coding
---

I had a great weekend designing and programming Spy Run. I spend the majority of my time
working on graphics and ui elements and it shows in how different the game looks. Compared to Day 3 when I was just using text gui elements.

Day 3 snapshot:
![start of day 3 snapshot](/images/day3-game-snapshot.png)

Day 5 snapshot:
![start of day 3 snapshot](/images/day5-game-snapshot-1.png)

On my drive to work today I was listening to the "Think Like A Game Designer" podcast and they were talking about setting
constraints on you design when starting a new game. The idea is to use these artificial design constraints to guide you toward a "game" rather than just a
set of features.

This got me thinking about what Spy Run is going to be and what progression structure I need to implement in order to realize Spy Run. This is when I started thinking about "Game Phases"
and how the phases will fit together.

I'm going to start from the top and work down through the game like the player would.

Here is where I'm at:

# Spy Run (Main Objective)
    
## ── Phase 1: Preparation and Resource Management
    
**Objective:** Equip the player with the necessary resources, upgrades, and strategies to maximize their chances of success during missions.
        
### Components:
            
#### Resource Management:
- **Information:** Collect intel on targets, enemy locations, and potential threats.
- **Gadgets:** Acquire and upgrade spy gadgets such as hacking devices, drones, and tracking tools.
- **Disguises:** Obtain various disguises to infiltrate different locations undetected.
            
#### Base Operations:
- **Upgrades:** Improve the hideout with advanced facilities like a tech lab, training room, and surveillance systems.
- **Training:** Train the player character and any allied NPCs in various skills such as combat, hacking, and stealth.
- **Crafting:** Create new gadgets, weapons, and equipment using collected resources.
            
#### Stealth and Strategy:
- **Mission Planning:** Choose missions from a mission board, each with different objectives, rewards, and difficulty levels.
- **Intel Analysis:** Analyze collected information to plan the best approach for upcoming missions.
- **Team Assembly:** Select team members and assign roles based on their skills and the mission requirements.
    
## ── Transition: Start Mission Button
    
**Action:** Once the player feels ready, they press a button to start the mission, triggering the transition to the next phase.
    
- **Confirmation:** Provide a summary of the mission plan and allow the player to confirm their readiness.
- **Loadout:** Finalize the loadout screen where the player can make last-minute changes to their equipment and team.
    
## ── Phase 2: Mission Execution
    
**Objective:** Successfully complete the mission objectives using the resources and strategies prepared in Phase 1.
    
### Components:

#### Infiltration:
- **Stealth Mechanics:** Utilize disguises, gadgets, and stealth tactics to avoid detection.
- **Environment Interaction:** Hack security systems, disable cameras, and unlock doors.

#### Objective Completion:
- **Primary Objectives:** Complete the main mission goals such as retrieving intel, sabotaging enemy operations, or rescuing hostages.
- **Secondary Objectives:** Optional tasks that provide additional rewards, such as collecting bonus intel or capturing high-value targets.

#### Challenges and Threats:
- **Enemy AI:** Encounter guards, security drones, and surveillance systems with varying difficulty.
- **Dynamic Events:** Handle unexpected challenges like sudden patrols, alarms, or environmental hazards.

#### Escape:
- **Exfiltration:** Plan and execute an escape route to safely exit the mission area.
- **Covering Tracks:** Use tactics to cover your tracks and prevent enemies from tracing your steps back to the hideout.
    
## ── Transition: Mission Debriefing

**Action:** Once the mission is complete, a debriefing screen provides a summary of the mission outcome, rewards earned, and any new intel gathered.
- **Mission Report:** Review the mission performance, including successful objectives, collected resources, and any mistakes made.
- **Rewards and Consequences:** Receive rewards based on mission performance and face any consequences for failures or detected actions.
    
## ── Phase 3: Post-Mission Management (Back to Phase 1)

**Objective:** Use the rewards and intel from the mission to further upgrade and prepare for future missions.

### Components:
#### Upgrades and Repairs:
- **Resource Allocation:** Spend earned resources on new upgrades, gadgets, and repairs.
- **Intel Utilization:** Use gathered intel to unlock new mission opportunities and uncover enemy plans.

#### Skill Development:
- **Training:** Improve skills and abilities based on mission performance and experience gained.
- **Team Building:** Recruit new team members and enhance the capabilities of existing ones.

#### Strategic Planning:
- **Future Missions:** Plan for upcoming missions based on new intel and resources.
- **Long-Term Goals:** Set and work towards long-term objectives, such as dismantling enemy organizations or uncovering conspiracies.





