# UnrealProgrammerTask

The System consist in a Skateboarding Simulator Game inspired on Tony Hawk Pro Skater 3. The BP_SkaterController (PlayerController) process the inputs and set different variables in the BP_Skater (Character) [such as Pushing, PreparingJump] and his MovementComponent [such as Velocity and jump functions]. The ABP_Skater is in charge of animating the player depending it's state, it has it's own logic for that. The simple score system is just a triggerbox that auments the score in the BP_Skater.

I focused on making the movement feel nice and the animation to look as natural as possible with little to none assets. Added details such as jump charge (to match the Tony Hawk Pro Skater 3 feeling), simple steering that increases on air so you can do 180 tricks and so, when I was constructing it I was already thinking on what would I add later if I had more time such as falling from the skateboard when landing 90° and so.

I would evaluate my performance as an 8/10 given the context, I think is a good outcome, it's not to hard to extend, and using the controllers should be compatible with multiplayer usage (not tested in this case).
