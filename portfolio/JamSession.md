---
layout: default
title: Jam Session
type: portfolio
featured: true
thumbnail-url: portfolio\JamSession.png
description: Rhythm Game Research Project
tag: research
---

# Jam Session
**Team Size**: 5 Members  
**Role**: Game Designer, Co-Producer, Artist  
**Engine**: Unity  
**Platform**: PC, VR  
**Duration**: 4 Months  

## Project Description

Jam Session was a team at Carnegie Mellon University Entertainment Technology Center focused on exploring rhythm games.

By creating a set of innovative and engaging prototypes and documenting a summary of processes and reflections through playtesting data and postmortems, we worked to answer that question. Check out our [website](http://www.etc.cmu.edu/projects/jam-session/) to see our games in action or try them for yourself!

## Contributions
As a **game designer**, I led my team in brainstorming sessions throughout the semester. Many of our ideas for game prototypes came from these sessions. I also worked with my team to develop ideas and mechanics for each of the individual prototypes. For many of the prototypes, such as Laserfade and Jelly Tracks, I implemented ideas and mechanics in-engine. This included adding new features, models, and beatmaps into the prototypes.

As **co-producer**, I led daily Scrum meetings for the team. I worked with each member to ensure that they knew what work had to be done for the day, as well as keeping track of what work had already been completed. On top of this, my responsibilities as co-producer led me to writing many postmortems for the prototypes as well as keeping in touch with the many contacts important to the project.

As an **artist** for the project, I contributed models, textures, and particle effects for many of the different game prototypes.


## Project Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/kqsnckK6rnU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Game Prototypes
### Gang Beats

<iframe width="560" height="315" src="https://www.youtube.com/embed/aKE_fROf7No" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Prompt**: Can we make a multiplayer game where a player’s rhythmic action directly affects other players?

#### Description
Gang Beats is a 2-4 player fighting game where players hit each other on the beat in order to be the last one standing.

#### Prototype Goals
- We found that most multiplayer rhythm games simply had players competing in terms of score – there wasn’t much competition, as the two players would play as if it were single-player and have their scores compared at the end. We wanted to try a game where player’s rhythmic accuracy impacts other players in the game.
- We also thought it could be very interesting to make a real-time fighting game using rhythmic accuracy as a method of combat.

#### Design Thoughts
- In one of the earlier iterations, determining which player “won” a combat (e.g. if players hit each other on the same beat) was resolved on the beat itself, which meant that players that hit early would always have an advantage over those that hit late. We later realized that the only way we could resolve conflicts fairly was to wait for the next beat to decide. This, along with the playing of a sound effect to signify a successful hit, created a pretty cool off-beat rhythm that was surprisingly pleasant to hear.
- While we designed the “clap” audio cue to be extremely prominent, it became clear during playtesting that players desired more visual feedback. We added the floor flashing effect in a later iteration, which players responded positively to.
- Stalemates became very common once people were used to the beatmap. In order to accommodate more skilled players with a good understanding of the song, more mechanics would need to be implemented.

#### Lessons Learned
- Discrete feedback is necessary for players to know how well they’re doing — accuracy had to be categorized into grades, we needed the colored rings to inform players which grade they were given
- In a game as busy as this one, audio cues alone are not enough to get players’ attention, especially first-time players. Visual feedback is incredibly important.
- Conflicts on a certain beat had to be resolved on the next beat in order to equally prioritize early and late hits
	- Should early and late hits be equally prioritized? We can investigate this in a different prototype.
- Music needs to be less dense, “soundtrack like”, and more heavily focused on the cues (and cue leadup). Extraneous information that could be interpreted as a cue (i.e., the “cooler” drumline) should be minimized.

__________

### Jelly Tracks

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ji7s97Yniks" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Prompt**: How can we create a rhythm puzzle game?

#### Description
Jelly Tracks is a co-op rhythm puzzle game where two players work together to clear a board of enemies. Each enemy is associated with a beat within the “square per beat” track, as well as a color. Guests must communicate with each other to time their actions to ultimately eliminate all of the colored obstacles.

#### Prototype Goals
- We wanted to explore an example of a rhythm puzzle game
- We found the concept of building a rhythm with a partner to be very intriguing.

#### Design Thoughts
- While we initially wanted to design a puzzle game, introducing a co-op element early on so that the game became more accessible, ended up making it less of a rhythm puzzle game and more of a coordination or communication challenge.
- We played around with multiple ways to make the puzzle element of the game more robust — with no goal or limitations, the puzzles wouldn’t have true solutions, and players could exploit gameplay mechanics (sending out a projectile on every beat) to complete the puzzles with no consequence.
	- We ended up deciding to force players to complete the puzzle within a time limit, respawning all enemies if players didn’t succeed.
	- We kept track of the number of projectiles players have sent during the course of the level. A lower number of projectiles used = better score.

#### Lessons Learned
- There is great debate about whether or not this game was an example of either a rhythm game, or a puzzle game.
- Visual feedback was important!
- This game became a stronger rhythm game AND a stronger puzzle game when we removed the co-op element. Before, players were focusing less on the music and more on coordinating their button presses with their partner. Now, players have to rely more on the music and their own hand-eye coordination when executing the solution to the puzzle.
- For timed levels: players disliked the fact that the timers started immediately on the next beat after they timed out. They wanted to use the time to plan their next move, but would often have to wait for the timer to start again from the top so they had enough time to execute the whole solution.

---

### Laserfade
<iframe width="560" height="315" src="https://www.youtube.com/embed/x6n6m4rTGgo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Prompt**: How can we create a game focused on testing players’ internal sense of rhythm?

#### Description
In this game, players are tasked with shooting targets that appear in the wireframe-styled world around them. Players must charge their shots to destroy targets; however, doing so removes the music from the world. Since shots must be charged for a certain number of beats, and targets require different numbers of beats to be destroyed, players must internalize the beat in order to succeed.

#### Prototype Goals
- The goal of this game was to explore the idea of testing players’ sense of rhythm by removing the music, while still having them perform actions to the beat.

#### Design Thoughts
- Aiming needed to be as easy as possible, so we made it so that the gun automatically locks onto to the closest target. This prevented people from having to worry about aiming and rhythm at the same time, which is a difficult concept to quickly grasp.

#### Lessons Learned
- Rhythm is already a hard concept. Manual aiming would have added unnecessary difficulty and concept to keep track of.
- Players like aspects of repetition and predictability

---

### Chopin Beats
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X7KO0b_9zE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Prompt**: How can we innovate on the presentation of a note highway in VR?

#### Description
In this game, players are placed in a VR kitchen where they must chop and push ingredients that arrive to the beat of music.

#### Prototype Goals
- The team wanted to experiment with the presentation of a note highway in VR
- Exploit the immersive, diegetic nature of VR environments by placing players with a less abstract, more physically-present location

#### Design Thoughts
- Good principles for VR design can sometimes clash with rhythm game design principles. We made the notes in our note highway physics-responsive because players in VR respond well to objects behaving as they would in real life; however, this adds an element of impreciseness to the objects that rhythm games often don’t permit.
	- In VR note highway games like Beat Saber, Audica, etc., the notes move linearly towards the player and don’t respond to outside forces.
	- In the end, we solved the problem by simulating physics for certain elements of the game, such as when the ingredients fall to the chopping board, or when players swipe the ingredients into the bins.
- Rather than force players to chop things on the beat, we chose to have the ingredients land on the chopping board to the beat instead.

#### Lessons Learned
- Real physics are very satisfying, but add complications and are not 100% conducive to accuracy when dealing with beatmap integrations.
- The realistic setting and interaction make the rhythmic action easy to understand, even to VR novices and non-gamers.
- Our explorations in innovating on the “note highway” in VR allowed us to unravel havoc on the certain key elements that the traditional note highway represents. Tradition note highways gives the game designers very complete control over the world, while allowing players a very limited area of interaction. Allowing physics (and the freedom it gives to cues) into the picture within VR relinquishes that control, which is why such a free environment for note highway/rhythm games probably isn’t the route to go.

---

### Kinectic
<iframe width="560" height="315" src="https://www.youtube.com/embed/ODpuxHqWHis" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Prompt**: How can we innovate on full-body motion experiences in VR?

#### Description
In this game, players must push ball-shaped cues that appear in front of them with a corresponding hand, tracing a line through spherical targets with their movements. The cues appear and disappear with the music. When players are in the flow of the game, it should look like they’re dancing.

#### Prototype Goals
- Can we make a rhythm game that encourages full-body movement in VR?
- Can we make a rhythm game that uses continuous input?

#### Design Thoughts
- While we originally visualized the player being surrounded by a grid of possible points for cues to spawn, we realized that raised questions about how direct the player’s attention effectively to targets that were outside of their view. In the end, we decided that this was more of a VR UI/UX design decision which wasn’t a priority for us to iterate on, so we made targets spawn on a single 3 x 6 grid in front of the player (because the grid is invisible, players should not have an overt awareness that cues are snapped to a grid).
- One iteration of the game had players touching cues with their hands to bring them to a destination point, snapping cues to players’ hands upon contact. This resulted in players using a very different motion to complete notes compared to the more deliberate pushing action we wanted to see. Instead, we snapped notes to a plane in front of the player and allowed players to push the note along the plane.
- With the limited time we had to get this prototype playable, we had to iterate on what a beatmap looked like and how best to create them. While we had a VR beatmap maker, we didn’t have the resources to include features such as real-time editing or deleting notes — only adding to and overwriting the whole beatmap at a time. We allowed for beatmaps to be mapped out using 1 hand at a time to reduce the load on our beatmap designer.
- Beatmap – while working on the beatmap maker we started to visualize what this prototype could look like by creating animatics in Maya. At first, we created one when we thought this would be 360 degrees, then we created one when cut it down to the spheres right in front of you. Using this animatic as inspiration, we then started showcasing possible movements to see how that may affect the music that was created. From there we went into VR using the beatmap maker. When beatmap making, we tried to have repetition in certain parts, as well as have the next item spawn in places near where the player would finish their last note. 

#### Lessons Learned
- We built this prototype to explore continuous player actions, which focuses on having players act according to the music’s flow and melody, rather than discrete beats or sound cues. However, programmatically speaking, we could really only evaluate the accuracy of player actions at discrete points. While we could have made players follow a really precise path with their motions, with the limitations of VR field-of-view and attention management, we decided that a more simplified input would be easier to both implement and playtest. Our final input scheme, “pushing a note along a path”, is still a continuous motion, but it would be interesting to explore more complex paths that happen around the player, instead of only in front.
- A VR rhythm game that involves choreographed movements needs a VR beatmapping system. However, it’s difficult enough to create a fully functional beatmapping system for regular PC use, let alone in VR. The basic VR beatmap maker we came up with was sufficient, but could have had more features such as a timeline, etc. What could we do with more time?

---

### Dutch Double
<iframe width="560" height="315" src="https://www.youtube.com/embed/bael20a6k-w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Prompt**: How can we gamify a familiar rhythm-based activity?

#### Description
In Dutch Double, players jump on a Dance Dance Revolution Dance Pad to emulate jumping rope. The main screen of the game shows players what buttons they should be jumping on and if they should be doing single (jumping with both feet at the same time), or double (jumping with alternating feet). An auxiliary screen provides players with a visual indicator of when to jump. The more the player continues to jump on the beat, the more layers are added to the game’s soundtrack. After three failed jumps, players lose the game.

#### Prototype Goals
- Can we make a rhythm game that simulates the real-life, rhythmic activity of jump rope/double dutch?
- Can we make a rhythm game that requires players to be active?

#### Design Thoughts
- This game was really, really hard. Many of our naive testers had a hard time getting more than a couple of correct jumps.
	- We already had a leeway system built in that ignored bad jumps after certain events, such as when changing the players’ foot positions. One idea we had was to give players a couple of jumps of leeway after making 1 bad jump — however, this made it hard for players to self-correct, because there was no feedback during the “invincibility period” that would help them fix their timing.

#### Lessons Learned
- Even though the act of jumping rope is a rhythmic activity, it seems that most people (especially novices) don’t perceive its true rhythm when doing it. Therefore, translating that true rhythm to a video game doesn’t work so well. To make it work, we have to make the game similar to other rhythm game mechanics. (Landing on the beat) 
- A/B testing the two input schemes we had (jumping on the beat and landing on the beat) proved really useful in determining which was the better choice for our game.
- Physical interfaces that use non-traditional forms of input (i.e. not just button/key presses on a keyboard or a gamepad) require a lot more work than we foresaw. There are completely different paradigms about usability and user experience when using jump- or even foot-based controls. Rhythm games are already pretty difficult, so mashing that up with a wacky control scheme makes the resulting game extremely hard.
- Testing a game that’s supposed to be more like a festival/exhibition experience is tricky, especially when you can’t bring a ton of equipment with you. This game required multiple monitors with a very specific orientation.
- Players need to be allowed to self-correct their input when they make a mistake. Rhythm games that focus on beat-matching action need to give players some sort of feedback about how far off-beat they are so they can rectify their own inputs.
