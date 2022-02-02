# MilitarySpaceTraining

This is my first game made in Unreal Engine 4. The game is an isometric shooter in which you have a simple goal - get the best kill streak you can against the opponent AI. The work for this project included:
- modeling a level using Brush Geometry
- using Blueprints to define world objects, e.g. health packs, switch covers using timelines, sequence-animated shapes
- creating player's Character Blueprint containing controls, weapon-firing, damage-taking, reloading logic
- creating enemy's Character Blueprint with weapon-firing, damage-taking logic and assignment to its AI controller
- defining AI Controller, AI Behavior Trees, AI Blackboard to control enemy's behavior
- utilizing EQS (Environment Query System) to allow AI to search for cover
- creating EQS to allow AI to search for the best peek location before shooting at the player
- configuring Animation Bluprint, Animation Blend Space and Animation Montages to add more realistic look to pawns' movements
- utilizing Widget Blueprints to create main menu and HUD
- adding sound effects

# Demo

The demo video can be viewed through the link: https://youtu.be/95Mx8vNwVuo

# Credits

- FPS Weapon Bundle: https://www.unrealengine.com/marketplace/en-US/product/fps-weapon-bundle
- Basic Shooter Pack animations from Mixamo: https://www.mixamo.com/#/?page=1&type=Motion%2CMotionPack