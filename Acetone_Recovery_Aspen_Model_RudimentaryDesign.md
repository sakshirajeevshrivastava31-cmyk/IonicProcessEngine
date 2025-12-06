🧪 Acetone Recovery – Aspen Plus Distillation Model (Rudimentary Design)
1. Problem I Took On

Our feed stream was a mix of IPA, water, and acetone — a tricky combo.
The goal was to Recover acetone at usable purity and not waste solvent.
Data from the plant was sparse, and the separation behaviour was a little stubborn.
I wanted to see if a basic simulation could give me a feel of how this could work.

 2. I Learned
Build a rudimentary distillation model and see acetone separation in action.

Understand:
How feed composition affects the column
How reflux and stages change purity
Rough energy needs (condenser & reboiler)

Basically, play engineer with Aspen Plus and learn without breaking anything.

3. How did it go (Professor's helped obviooously)
Chose NRTL thermodynamics (because non-ideal systems are tricky).
Set up a RadFrac column:
Number of stages
Feed stage
Reflux ratio
Condenser & reboiler type
Tweaked and iterated:
Number of trays
Reflux ratio
Feed stage location
Pressure adjustments

Learned a TON just by playing with numbers and seeing the output.

 4. What was Discovered / Solved
Could get phase behaviour and acetone purity trends.
Rough estimate of condenser & reboiler duties.
Saw how small feed changes mess with output — very sensitive stuff!
Made a clean PFD with major streams and equipment tags.
Got a first-cut idea for design direction.

   5. Tweaks  Made During the Simulation

Added a few more trays to improve separation.
Adjusted reflux to balance purity vs energy.
Moved feed stage after seeing some weird results.
Played with pressure to make acetone a bit more volatile.

Tinkered with distillate flow until it “looked stable.”

 6. My Results (First Impressions)
Achieved acetone purity that looked promising for a first try.
Energy estimates for condenser & reboiler were not crazy.
Stream summaries for material balance created.

Gave me confidence to take this further with more refined design.

 7. Status of Design
This is a rudimentary / first-cut design — not the final plant-ready version.
Gives a feel for:

Feasibility
Separation behaviour
Rough energy loads
Basis for more detailed work

Needs refinement: plant data, tray/packing design, safety checks, and dynamic analysis.
