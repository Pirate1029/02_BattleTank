This is the [Unreal Engine Developer]( http://gdev.tv/urcgithub) course – it started as a runaway success on Kickstarter and has gone on to become one of the bestselling Unreal courses on the internet! Continually updated in response to student suggestions, you will benefit from the fact we have already taught over 360,336 students game development, many shipping commercial games as a result.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: [Unreal Engine Developer]( http://gdev.tv/urcgithub)

## In This Section

### 1 Intro, Notes & Section 3 Assets ###

+ Welcome to our first Unreal editor section.
+ You’ll learn simple level building.
+ We’ll be using meshes and materials.
+ C++ events accessed from Blueprint.
+ Calling C++ code from Blueprint.
+ And much more.

### 2 S03 Game Design Document (GDD) ###

The Concept, Rules and Requirements of our simple game.

### 3 Version Control 101 ###

+ The what and why of Version Control Systems
+ Choosing your Version Control System (VCS)
+ What files to include / exclude
+ Commit = save a local snapshot
+ Reset = roll-back to a previous state
+ Branch, Push and Large File Support later.

### Landscaping

+ Creating & Deleting
+ Setup & Scaling
+ Landscape Layering
+ Flat Shading Low Poly Landscapes
+ Additional Tools

### Configuring a tank

+ Importing combined meshes
+ Making Tank_BP as pawn
+ Adding sockets to Tank_BP for body, turret, barrel and tracks

### 3rd Person Camera Control

+ Adding Camera with spring arm component on Tank_BP
+ Adding inputs as axes for Azimuth & Altitude (Elevation)
+ Setting up Camera input bindings for yaw and pitch in Tank_BP event graph

### Fixing 3rd Person Camera Rotation

+ Adding Azimuth Gimbal (Scene Component) as parent of SpringArm
+ Changing Local Rotation for Yaw target to the Azimuth Gimbal in Input Setup Graph
+ Disabling camera roll for SpringArm (Optional)

### User Interface (UI)

+ Creating User Interface Widget
+ Setting anchor to 50% Horizontal, 33.3% Vertical
+ Centering image to center of anchor+
+ Creating TankPlayerController_BP
+ Referencing PlayerUI widget to add to viewport in TankPlayerController_BP
+ Setting Player Controller Class in BattleTankGameMode_BP to be the newly create TankPlayerController_BP

### Main Menu

+ Creating a new menu widget
+ Importing image into Unreal
+ Showing Mouse Cursor at Main Menu (Target: Player Controller)
+ Creating Scale Box with Stretch set to "Scale to Fill" in MenuUI Widget
+ Importing font for texts
+ Adding Start Button and Title (Battle Tank)
