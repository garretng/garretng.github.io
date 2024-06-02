---
layout: post
title:  "Day 8 - Daily Changelog Update"
date:   2024-05-31 12:00:00 -0700
categories: Coding
---
Below is the Changelog from yesterdays work:

	# Spy-Run Back to Basics  Development Changelog

	All notable changes to this project will be documented in this file.

	## [As of 5/30/2024]

	### Added

	-UI
		
		-added tablet (display area for all menus and UI elements) + functionality
	
			-added tablet application "alfred" (display area for basic player and game stats are displayed) + functionality
	
				-added "alfred power monitor" (display player's stored power level) + button functionality for generating power

				-added "alfred bitcoin monitor" (display player's store bitcoin level) + button functionality for toggle bitcoin mining
	
		-added tablet application "ncrypt" (display area for messages are displayed) + functionality
	
	
	### Changed

	-

	### Removed

	-

	## [0.0.2] - 2024-30-05

	### Added

	-UI
		-ncrypt
			-added pnl_inbox (display area for inboxed messages)
			-added prfb_inbox_message_prefab (object for a single inboxed message)

	### Fixed
	
	- 

	### Changed

	- 	

	### Removed
	
	-

	## [0.0.3] - 2024-30-05
	
	### Added
	
	-UI
		-ncrypt
			-added pnl_table_off (tablet screen when the table is off)
			-added pnl_ncrypt_popup_message (popup window to diplay body of message when inbox listing is clicked.

	### Changed

	-UI
		-ncrypt
			-changed pnl_inbox -> pnl_ncrypt_inbox
			-changed prfb_inbox_message_prefab -> prfb_pnl_inbox_listing (message object in the form of a line listing in the inbox)

	### Removed
	
	-
	
	## [0.0.0] - 2024-00-00

	### Added

	- ADDED HERE

	### Fixed
	
	- FIXED HERE

	### Changed

	- CHANGED HERE	

	### Removed
	
	- REMOVED HERE
	
Okay! Good morning! Back at it again for Day 8!

When I woke up this morning I was thinking about the 30-Day Challenge idea. The original thought was to just program at lease once a day for 30-Days. I think that
I want to add to that by setting a more specific goals:

1.code/design/develop/test everyday for 30-days starting from 5/23/2024 -> 06/22/2024

2.learn about Game Design Documents by creating and maintaining one:
	
### Spy Run Game Design Document

---

**Game Title:** Spy Run

**Genre:** Incremental / Idle Game

**Platform:** PC / Mobile

**Developer:** GNG

---

#### Table of Contents

1. **Game Overview**
2. **Gameplay Mechanics**
3. **Story and Setting**
4. **Characters**
5. **User Interface (UI) Design**
6. **Art and Animation**
7. **Sound and Music**
8. **Technical Requirements**
9. **Marketing and Monetization Strategy**
10. **Development Timeline**

---

### 1. Game Overview

**Spy Run** is an incremental/idle game where players assume the role of a spy managing resources and missions. The core gameplay revolves around generating power, completing missions, and upgrading equipment. The game features a unique blend of strategy and idle mechanics, allowing players to progress even when they are not actively playing.

---

### 2. Gameplay Mechanics

**Core Mechanics:**

- **Resource Generation:**
  - **Power:** Players generate power by clicking a button with a hand-powered generator icon. Each click accumulates power, which is displayed on the GUI.
  - **Other Resources:** Additional resources (e.g., Intel, Money) can be unlocked and generated as the game progresses.

- **Missions:**
  - Players can send their spy on various missions that consume resources but provide rewards such as upgrades and new abilities.

- **Upgrades:**
  - Upgrades can be purchased to increase resource generation efficiency, unlock new abilities, and enhance mission success rates.

- **Email System (Ncrypt):**
  - The fictional computer program 'ncrypt' allows players to send and receive messages. The system will display messages stored in the player's inbox, using a GUI similar to an email client.

**Controls:**

- **Mouse Input:**
  - Clicking to generate power and interact with the UI elements.
- **Keyboard Input:**
  - Shortcuts to open specific panels or perform actions (e.g., "a" and "n" keys to open panels).

---

### 3. Story and Setting

**Setting:**
- The game is set in a modern, high-tech world where espionage and covert operations are key to maintaining global balance.

**Story:**
- Players take on the role of a spy working for an elite agency. Their mission is to gather resources, complete dangerous missions, and upgrade their capabilities to stay ahead of rival spies and organizations.

---

### 4. Characters

**Main Character:**
- **The Spy:** A highly skilled agent with a mysterious background, capable of undertaking various missions and managing resources effectively.

**Supporting Characters:**
- **The Handler:** Provides mission details and guidance through the ncrypt system.
- **The Rival Spy:** Occasionally appears as an antagonist, complicating missions and adding challenges.

---

### 5. User Interface (UI) Design

**Main Screen:**
- **Power Meter:** Displays the current power level.
- **Resource Panel:** Shows the amounts of other resources (e.g., Intel, Money).
- **Mission Button:** Allows access to the mission selection screen.
- **Upgrade Button:** Opens the upgrade shop.

**Ncrypt System:**
- **Inbox Panel (pnl_inbox):** Displays received messages.
- **Message Prefab (prfb_message):** Individual messages with sender, subject, and body text fields.

**Tablet Controller:**
- Allows switching between different panels using keyboard shortcuts.

---

### 6. Art and Animation

**Art Style:**
- Modern and sleek with a high-tech, spy-themed aesthetic.
- Consistent color scheme to convey a professional and covert atmosphere.

**Animations:**
- Smooth transitions between UI panels.
- Animations for resource generation and mission completion.

---

### 7. Sound and Music

**Sound Effects:**
- Clicking sounds for generating power.
- Notification sounds for new messages.
- Mission success/failure sounds.

**Music:**
- Background music with a stealthy, espionage vibe.

---

### 8. Technical Requirements

**Engine:**
- Unity

**Platform:**
- PC and Mobile

**Minimum System Requirements:**
- PC: Windows 7 or later, 4GB RAM, 2GHz processor
- Mobile: Android 5.0/iOS 10 or later, 2GB RAM

---

### 9. Marketing and Monetization Strategy

**Target Audience:**
- Fans of incremental and idle games.
- Players interested in espionage and strategy.

**Monetization:**
- Free-to-play with optional in-game purchases (e.g., speed boosts, cosmetic upgrades).

**Marketing:**
- Social media campaigns.
- Influencer partnerships.
- Gameplay trailers and teasers.

---

### 10. Development Timeline

**Phase 1: Pre-Production (1 month)**
- Finalize game design document.
- Create initial art assets and prototypes.

**Phase 2: Alpha Development (2 months)**
- Develop core gameplay mechanics.
- Implement resource generation and mission systems.
- Basic UI setup.

**Phase 3: Beta Development (3 months)**
- Expand on UI and UX.
- Integrate ncrypt email system.
- Add sound and music.

**Phase 4: Testing and Polish (2 months)**
- Conduct playtesting and gather feedback.
- Optimize performance.
- Finalize art and animations.

**Phase 5: Launch (1 month)**
- Prepare marketing materials.
- Release the game on selected platforms.
- Post-launch support and updates.

---

This game design document provides a comprehensive overview of "Spy Run" and outlines the key elements needed to bring the game to life. If you need further details or adjustments, feel free to ask!	





	
	


