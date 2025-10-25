[![Discord](https://img.shields.io/discord/1157693749841899621?label=Join%20Discord&logo=discord&style=flat&color=5865F2)](https://discord.gg/6vpe5X78w8)

# KineticGorilla

## README

Setup:
1. Make a game object called LeftPhysics and RightPhysics them drag the PhysicsHands script and also
the PhysicsGrab script onto the object (MAKE SURE YOU SET UP THE SCRIPTS)
2. Add a Box Collider onto the PhysicsHands and make sure the position is 0,0,0 and the Size 
is 1,1,1
3. Add a Rigidbody to the PhysicsHands set Interpolation to Interpolate and
set Collision Detection to Continuous Speculaitive
4. Add a Configurable Joint onto the PhysicsHands and drag in the Player Rigidbody 
in the Connected Body

Settings:
- Frequency: how fast it follows (higher = snappier)
- Damping: how smooth it feels (higher = softer)
- Rot Frequency and Rot Damping do the same for rotation.

I recommend you keep the values the same but depending 
on how you want your hands to work its up to you

If you need any extra help join the discord server
