# SpaceEngineers_Scripts
My general depo of scripts for SE

**Drill Platform**
> As of 1.192.104

This script is for a remote mining depo.  It turns on and off drills based on cargo space availability, and makes sure that any attached refinery has "stuff" to refine.  It will also clear out the inventory of all refineries and puts them back into cargo containers.  It does not handle rotors or piston positions.

- Place down a foundataion of some sort to place blocks on.
- Place down at least one large cargo container, at least one refinery, and work out some power
- Make sure the refineries are connected to the cargo container

**Center Screens**
> As of 1.194.208

This script resets ALL STANDARD LCDs on any connected grid to 0% padding.  It does not handle blocks with multiple LCDs (Programmable block, ironically, is one type of block that is not handled by this script)

**Taledens Inventory Manager [TIM]**
> As of 1.194.208

This is NOT my script, but, a copy and update of https://github.com/luvies/TaledensInvManagerUpdated

**Thruster Rename**
> As of 1.194.209

This script is will go through your entire grids (Connection ships and all) and rename thrusters to something standard, and optionally hide them from the terminal.

I found a "temporary" ship to get me out into space, however, because the blueprint wasn't written written with the direction of the thruster, it was a real pain to figure out which thruster was which to turn on my version of "Cruise Control".

Now all you need to do is run this script, search for the thrust your ship needs push (Backward/Up/etc), create a group against what is found, then attach it to your tool bar.
