🏛️ University Brick Breaker
Developed by: Imad Albekai
Project Type: 2D Arcade Game (Unity)
📝 Overview
This is a custom-built Brick Breaker game featuring a personalized theme based on ULFG (my university). The game challenges players to clear rows of bricks while managing lives and aiming for the high score, all set against a stylized backdrop of the campus.
🚀 Key Features
Persistent Scoring: High scores are saved locally using JSON serialization, so your records stay even after you close the game.
Dynamic Level Loading: Features multiple levels with increasing difficulty and unique brick layouts.
Custom Graphics: Includes a cartoon-stylized version of the university campus and specialized game assets.
Audio System: Background music and sound effects integrated via Unity's AudioSource system.
🎮 How to Play
Launch: Open exe file.
Controls: Use your Arrows to move the paddle left and right.
Objective: Bounce the ball to destroy all bricks on the screen.
Lives: You start with 5 lives. If the ball falls past the paddle, you lose a life.
Winning: Clear all bricks to progress to the next level!
📸 Gameplay


🛠️ Technical Details (For Evaluators)
Engine: Unity 2022.x+
Data Path: Uses Application.persistentDataPath to store highscore.json.
Architecture: Implements a Singleton GameManager pattern for cross-scene data persistence.
UI System: Responsive UI using the Canvas Scaler and Anchors to support various screen resolutions.
