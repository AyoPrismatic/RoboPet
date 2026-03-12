Installation:
Download the Mediafire link here for Game files:
https://www.mediafire.com/file/drazjto1x8ab9z9/GameFiles.zip/file

Download the Mediafire link here for the Game:
https://www.mediafire.com/file/0af5nbuxvuutkhy/RoboPet.exe/file

Copyrighted materials:
Godot Game Engine - https://godotengine.org/ - Juan Linietsky

Crab Model - https://sketchfab.com/3d-models/crab-robot-a0729527a07e4ba48a99b5e5fb5dfe67 - Turkey

Inspiration for Grass Shader - https://www.youtube.com/shorts/NbF5pGo2FGY - CatchNCookGame

Inspiration for Toon Shader - https://www.youtube.com/watch?v=io2y8RgF39A - StayAtHomeDev

Stylized Water shader - https://godotshaders.com/shader/stylized-toon-water/ - ThunderGecko

Sky Shader - https://godotshaders.com/shader/simple-overcast/ - tentabrobpy

Standard font - https://www.dafont.com/vcr-osd-mono.font - Riciery leal

Thick Font - https://www.dafont.com/daydream-3.font - DoubleGum

Scenes, Handlers, Managers, etc:
LiveDataManager:
Handles data that changes during gameplay. Stores and updates values the game needs to access in real time.

SceneManager:
Controls scene loading and switching. Manages moving the player between different scenes in the game.

TransitionManager:
Handles visual and timing transitions between scenes or states. Manages things like fades, wipes, or delays during changes.

SystemManager:
Coordinates core game systems. Initializes and keeps track of global systems the game relies on.

PetStatsHandler:
Manages pet statistics such as health, hunger, or happiness. Updates and retrieves stat values when gameplay changes them.

JobTaskLoopHandler:
Runs and manages repeating job tasks. Handles loops that process ongoing work or tasks over time.

LayerCullingHandler:
Controls which layers are visible or processed. Hides or disables layers that should not render or update to improve performance.

ActionHandler:
Scans Nodes in it's parent (Descendants) and Applies UIActions
