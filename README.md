Bone Grid (Tavern Style) - MVP Prototype
This is a frontend prototype of the "Bone Grid" dice game, built to demonstrate core game mechanics, UI responsiveness, and a fallback AI logic for Telegram Mini Apps.
🎮 Play the Prototype
Click here to play the Live Demo
🚀 Features implemented in this POC:
￼ Core Mechanics: Rolling dice, placing them in columns, and the destruction mechanic (removing opponent's matching dice).
￼ Combo Scoring: Advanced scoring logic where 2 matching dice multiply their sum by 2, and 3 matching dice multiply by 3.
￼ Responsive UI: Tailored specifically for mobile screens (Telegram Mini App constraints) with strict viewport locking.
￼ Tavern Aesthetics: Custom "bone" dice styling, ambient glows, and dark fantasy color palette.
￼ Fallback AI: A basic heuristic bot that identifies optimal columns for attacking (destroying dice) or defending (building combos).
🛠 Next Steps for Production
In the final architecture, this frontend will be strictly a visualizer:
1 Server-Side RNG: All dice rolls and scoring calculations will be moved to the Python (FastAPI) backend to prevent client-side manipulation.
2 WebSockets: Real-time state synchronization for PvP matchmaking.
3 Advanced AI: Implementation of the Minimax algorithm on the server side for complex tactical bot behavior.
