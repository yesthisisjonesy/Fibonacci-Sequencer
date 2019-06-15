## Fibonacci's Sequencer
Jonesy Jones - ryanjones2018@u.northwestern.edu - EECS397 - Digital Music Instrument Design - Northwestern University - Professor Stephan Moore

### What is this?

Fibonacci's Sequencer is an instrument/tower defense game hybrid programmed using Max/MSP, Javascript, and Arduino. Interacting with it takes on two different meaning of the word 'play'. The user builds a song on the playing field by picking notes and beats. The notes they select then also take on the role of a defensive fortress, firing shots at incoming waves of enemies when they are triggered. Gameplay takes place in two different phases; a building phase where the player composes their song, and an active phase when enemies enter the field and the song is played.

### Okay, but why?

Incorporating music into gaming is not a new concept, but many iterations of this idea largely remove any amount of creative expression from the user. Games like Guitar Hero, Elite Beat Agents, or AudioSurf are rhythm games where the music informs the user what they should be doing and when, but do not give a player an opportunity to express themselves in any way. If the "wrong" note is played or a note is played at the "wrong" time, your score, or your health, or whatever metric the game is judging you by, goes down. These are music games, but they are not instruments.

At the same time, many games do allow for some rudimentary creative expression in the way they are played. Fighting games like Mortal Kombat or Super Smash Bros may let you pick between a sword wielder, a martial artist, or a magic user, each with extremely different play styles. Action RPGs like Diablo or Path of Exile are highly customizable in managing the way you want your character to plow through your countless foes. In many cases with games like these there is an optimal strategy or a few optimal strategies, but there is still room for a player to decide that they'd rather shoot fireballs at their enemies than smash all of their heads in with a hammer. These choices can serve as an extension of a player's personality or feelings. Some days you just want to punch a zombie, and some days you want to levitate it up into the air instead. In a way, these types of games are closer to being instruments than something like Guitar Hero, even though Guitar Hero has you literally holding a plastic replica of an instrument. By giving a player branching options or skill trees or decisions in their playstyle, they are composing their character and their play experience as they go.

### Got it. So what about this game?

Fibonacci's Sequencer is a tower defense game, a la Bloons Tower Defense or Plants vs Zombies. This is a genre about using resources in various combinations to achieve a goal. These games typically have a rhythm to them: each tower or weapon or pea-shooting plant will fire at a specific rate as enemies approach them. Excelling at these games requires a knowledge of the strengths and weaknesses of each of your tools, and finding combinations of them that work together in harmony, to fill in all the gaps in your defenses. This, to me, feels remarkably like composing a song. So, why not make a game that does that in a literal sense?

Fibonacci's Sequencer adds an additional layer to song compoosition, in that you must also decide the physical location of each of your notes on the playing field. Notes have different properties based on their place on the C scale- shots fired by lower notes move slower, but do more damage, and shots from higher notes are faster and do less damage. An optimal strategy likely calls for a mixture of notes, spread out over all eight beats in the looping measure, to help cover more ground on the play field While there is no such thing as an optimal strategy in music composition, variation in notes and beats tends to lead to more interesting compositions. 

This touches on one of the more difficult pieces of taking on a project like this: there's no subjective way to score music. This means that, for a typical game with points and objectives, there will always be a divide between gameplay and creation. It would be almost meaningless to try to completely merge the two: do you get points for making a chord? Is more notes better? Would John Cage's 4'33" award him an automatic Game Over? I have no answers.


### So this is a prototype. What's missing?

In an ideal world with unlimited time, I would have like to have built at least one other type of instrument for a user to play with. The current one is essentially based on a piano- my next intention was to build a drum machine that operated similarly. The drum beats would have acted more as area-of-effect weapons, damaging enemies that got too close, and requiring a user to think much more critically about where they were placing their notes. More choice in instrument gives another level of creativity to the user, and ideally two or more players could make music together. 

Other additions would be more variety in the types of enemies, more variation in the effect of notes on these enemies, and more completely unessescary cutscenes about Fibonacci.
