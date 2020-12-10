---
layout: default
title: Kinectic
type: portfolio
featured: false
thumbnail-url: JamSession\Jam5.png
description: VR Rhythm Game
tag: vr
---

# Kinectic
**Team Size**: 5 Members  
**Role**: Game Designer, Co-Producer, Artist  
**Engine**: Unity  
**Platform**: VR 
**Duration**: 1 Month  

## Project Description

Kinectic was part of an ETC project called Jam Session, focused on exploring rhythm games.

In this game, players must push ball-shaped cues that appear in front of them with a corresponding hand, tracing a line through spherical targets with their movements. The cues appear and disappear with the music. When players are in the flow of the game, it should look like they’re dancing.

## Contributions
**Game Designer**
- Led my team in brainstorming sessions
- Worked with my team to develop ideas and mechanics for each of the individual prototypes
- Implemented ideas in-engine
- Playtested prototypes throughout lifespan of the game

**Co-producer**
- Led daily Scrum meetings for the team
- Worked with each member to ensure that they knew what work had to be done for the day
- Kept track of what work had already been completed.
- Wrote postmortems for the prototypes as well as keeping in touch with the many contacts important to the project.

**Artist** 
- Contributed models, textures, and particle effects for this game.


## Project Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/ODpuxHqWHis" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Prompt**: How can we innovate on full-body motion experiences in VR?

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