---
layout: default
title: Gang Beats
type: portfolio
featured: false
thumbnail-url: JamSession\Jam3.png
description: Rhythm Game
tag: pc
---

# Gang Beats
**Team Size**: 5 Members  
**Role**: Game Designer, Co-Producer, Artist  
**Engine**: Unity  
**Platform**: PC 
**Duration**: 1 Month  

## Project Description

Gang Beats was part of an ETC project called Jam Session, focused on exploring rhythm games.

Gang Beats is a 2-4 player fighting game where players hit each other on the beat in order to be the last one standing.

## Contributions
As a **game designer**, I led my team in brainstorming sessions throughout the semester. Many of our ideas for game prototypes came from these sessions. I also worked with my team to develop ideas and mechanics for each of the individual prototypes, and implemented some of those ideas in-engine.

As **co-producer**, I led daily Scrum meetings for the team. I worked with each member to ensure that they knew what work had to be done for the day, as well as keeping track of what work had already been completed. On top of this, my responsibilities as co-producer led me to writing many postmortems for the prototypes as well as keeping in touch with the many contacts important to the project.

As an **artist** for the project, I contributed models, textures, and particle effects for this game.


## Project Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/aKE_fROf7No" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Prompt**: Can we make a multiplayer game where a player’s rhythmic action directly affects other players?

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

---