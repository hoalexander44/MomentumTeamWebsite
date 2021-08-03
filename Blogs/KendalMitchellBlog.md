---
title: Template Blog
layout: default
---

## Welcome to Kendal Mitchell's Personal Production Journal

### Week 2
Kendal Mitchell, PPJ 1

Tasks Done: 

This week I worked on testing a variety of solutions to 

* Create our 5x5 hex gridboard
* Allow player movement. 

Initially, I was working with Unity's hexagonal grid and tile palette, 
we eventually shifted over to displaying hexagonal models made with ProBuilder to ease our efforts later down the road for procedurally generating maps.
I researched the A* algorithm for pathfinding and assisted in paired programming for our technical demo. Additionally, I also

* Created a main menu for the game

Overall, I spent about 4 hours researching and 2 in development.

Positive:

We were able to nicely divide our team into roles of designers, programmers, and artists. The team was also eager to coordinate and share ideas with one other.

Negative: 

We ran into some issues getting everyone access to files with SourceTree, but found alternatives with GitHub Desktop and GitKraken.

Upcoming:

We'll be further delegating tasks as we go deeper into development.

### Week 3

Kendal Mitchell, PPJ 2

Tasks Done: 

This week I worked with the others creating our HexMap (grid) and tile scripts. 

* Setup a system to generate Hexagonal grids with adjustable rows, columns, and spacing
* Built public interfaces for the HexMap and Tile GameObjects.
* Designers can now input HexType variants through the Unity Editor rather than through scripts.

Our generated HexMaps utilize an "odd-r" horizontal layout. This orientation isn't set in stone at this point but I ended up learning how to adjust it as I learned how to generate it.

Overall, I spent about 6 to 7 hours in development.

Positive:

Core components! Map creation has been automated and we can now track information not only for the Hex Tiles, but the HexMap itself too. Our artists are pumping out enemy designs and it's exciting to see so much progress over a short amount of time.

Negative: 

I was having some trouble line drawing and calculating distances for hexes but with some research found that Bresenham's algorithm may be a potential solution. It is possible that it may be hampered by our use of offsets, but this is still TBD. If necessary, our HexMap will likely need to change from a square offset tile grid to one using axial coordinates. 

Upcoming:

We're hopefully getting to the point now where we can start integrating pathfinding and player/enemy units types. I also had time to start prepping utility functions for pathfinding as well.

### Week 4

Kendal Mitchell, PPJ 3

Tasks Done: 

This week I worked with the others in setting up pathfinding and hex distance calculation. 

* Refactored HexGrid generation to produce a hexagonally shaped grid
* Setup functions for hex grid calculations and path recognition
* Converted from our offset coordinates to axial/cube for hex calculations

Just as planned, our conversion from offset coordinates to axial went smoothly, saving us a lot of time and allowing us to focus on hex coordinate math.

Overall, I spent about 7 to 8 hours in development.

Positive:

We saw a lot of growth in creating enemy assets and even got started on UI elements. We had a great design meeting in which we got to flesh out a lot of how we wanted the game to work too.

Negative: 

We ran into some issues with our previous data structure utilized for storing the Hex game objects but were able to find an improvement and get things working smoothly. 

Upcoming:

We should be getting to focus on intensely on enemy AI and creating player abilities.

### Week 5

Kendal Mitchell, PPJ 4

Tasks Done: 

This week I worked with the others in integrating our new hexmap with our player, enemy, and game controllers. 

* Constructed HexMap and refined coordinate system 
* Adjusted LevelGeneration script for a HexMap
* Pair programmed with other team members to translate HexBattleController and movement scripts to utilize cubic coordinates


Overall, I spent about 8 hours in development.

Positive:

Implementation of UI, hexgrid, and player movement together.  

Negative: 

We ran into setbacks getting highlighting and the momentum movement components working but were ultimately able to get it implemented. 

Upcoming:

Refactoring codebase for organization and brevity. Implementing EnemyAI and hex/enemy variants.

### Week 6

Kendal Mitchell, PPJ 5

This week, my time was spent with changing our process for generating visuals on the map.

* Refactoring HexGrid Map Visual HexPrefab Placement
* Utilizing Unity's Scriptable Objects for HexSettings
* Setting up a LevelCreator for the designers

Overall, I spent about 7 hours in development.

Positive:
Unity's Scriptable Object system was very easy to work with and the process of adding the objects onto our current Hexes is going smoothly.

Negative:
I did have to spend some time learning how to use the Scriptable Object system and had to spend additional time refactoring our older code.

Upcoming:
Fleshing out other hex variants and finishing ingame background music and a main menu theme.

### Week 7

Kendal Mitchell, PPJ 6

This week, my time was split between creating new types of status effect hexes and creating music for the game. 

* Setup a function to edit and create and assign a Hex's settings on our map.
* Created several types of hexes for the player to interact with.
* Produced several theme loops for our Main Menu and Battle Themes.

Overall, I spent five hours programming and three hours making music.

Positive:
I ended up finishing music in time for our first trailer and the new Hex variants added more depth to our gameplay loop. It's been fascinating seeing all the different components of our game come together. We're finally getting our art assets integrated in too.

Negative:
I didn't have time to make positioning hex variants on the map accessible in a non-programmatic way. Getting to finish this would help our designers to finish levels more quickly.

Upcoming:
In addition to creating more music and SFX, I need to work on creating a frontend editor for assigning different Hexes at certain positions.


### Week 8

Kendal Mitchell, PPJ 7

This week, in addition to continuing work on music/SFX, I created a frontend level editor and pair programmed on our EnemyAI.

* Setup a frontend level editor for place varying hex types and boundary hexes.
* Pair Programmed on Enemy AI with Yash
* Started making background tracks with heightened tempos 

Overall, I spent about 7 hours in development.

Positive:
I was able to get a level editor setup for our designers, make more music, and help debug enemy AI.

Negative:
Ran into an issue where many of our materials begun linking to materials that were pink. It ended up being an issue resulting from us not starting our project with a "Universal Project Template". I got this fixed, but it did take up some time.

Upcoming:
I'll be working on finalizing music/SFX and completing work on our enemy AI ability and logic variations.

### Week 9

Kendal Mitchell, PPJ 8

This week, I setup a Tooltip System and added Dynamic Audio.

* Setup a system to have tooltips pop up over UI elements when highlight.
* In-game audio will now correspond to the player's built up momentum, increasing and decreasing in pitch.
* Continuing working on tracks for our other levels.

Overall, I spent about 5 hours in development.

Positive:
The tooltip system was fully implemented and the dynamic audio work went smoothly.

Negative:
There was still some trouble getting the EnemyAI fully integrated.

Upcoming:
I'll be working on creating more music for an updated trailer and tutorial levels for our game.

### Week 10
Postmortem:
Overall, I had a blast working on this project. It was one of my first experiences working with a team this size on a game. I also never felt as if I couldn't get help from my teammates if I needed it. Not only was everyone willing to contribute, but they were always looking for the next thing to help out with. Throughout development, I found that our communication went very well. Everyone on the team was very responsive and vocal in regards to their tasks and what they needed from each other. Additionally, we were able to build out features quickly, with short turnover times. We were all also able to get playtest data from our peers and incorporate player feedback into our game.

Areas that we could be stronger in, were organizing our design decisions, verbalizing ideas to each other efficiently, and delegating art tasks more quickly. This presented a problem for our team towards the earlier half of our development time. As we only had one artist, Mathew was limited in his time to create art and animations. Had we come to design decisions earlier, we likely could have managed the time we spent on art more efficiently. 


Personally,

This week, I worked on setting up the beginning of what will be our in game tutorial levels.

* Created a new type of hex for exiting an area
* Begun work on an objective system to track in game progress markers
* Integrated more art assets into our title screen and UI

Positive:
The integration of the new hex went smoothly. It worked well with our current layering system.

Negative: 
The objective system was too big in scale for our game within our timeline, so it wasn't able to be included.

Upcoming:
There's plenty of work to be done for including new features and more audio!

### Week 2 - Week 3
Kendal Mitchell, PPJ 1

This week was a return from a short break, alongside a bigger and better team.

* Heavy preplanning for asset creation, programming tasks, and game narrative.
* We met as a full team for about three hours and then within the art team for two the following day.

I spent about 5 hours of work with the team.

Positive:
Everyone on the team seems more than willing to contribute and was upfront about their availability over this term. I'm also looking forward to additional backup on tasks that I was alone on before, such as music creation. 
Negative:
Although we covered a lot of content, we continued an ongoing habit of overly lengthy meetings. It'll be important for us not to eat up everyone's time especially in the upcoming weeks.
Upcoming:
We'll be delegating tasks within our team and creating a level editor for our game.


### Week 3 - Week 4
Kendal Mitchell, PPJ 2

![image](https://user-images.githubusercontent.com/40584756/124524932-2132a980-ddcb-11eb-9452-d70a390ffa0b.png)
![image](https://user-images.githubusercontent.com/40584756/124524936-27c12100-ddcb-11eb-95f3-d70745194a62.png)

This week I focused on getting a level editor started to work on with Cyn. I made progress but also found some hurdles in the process.

* Setup an in-editor level generator
* Setup editor windows and a simple GUI for our designers
* Cleaned up old and redundant code

I spent about 6-7 hours of development work this week.

Positive:
I was able to integrate a lot of the pre-existing logic I wrote for generating levels into a custom level editor for our team to use later on. This is great since it'll allow us to avoid the grunt work of preplanning tile locations with coordinates and testing success through running our game. 
Negative:
Both Cyn and I ended up being pressed for time this week and didn't get to spent as much time working together as we'd like. Additionally, I ran into some issues with our HexManager's layer reconfiguration that'll need to be rectified. 
Upcoming:
We ran into some issues with our reconfigure layers function clashing with the new Editor windows. I'll be taking a look at this and working on music. 

### Week 4 - Week 5
Kendal Mitchell, PPJ 3

![image](https://user-images.githubusercontent.com/40584756/125369704-d1b02880-e34a-11eb-8237-b74d076c07d7.png)


I spent about 6 hours of development work this week.

Positive:
This week I got to add more changes to our Level Builder Tool (now accessible through window/LevelBuilder). Users may now include level hex prefabs, boundary hex prefabs, and hex map column/radius sizing. Additionally, there's also a new prefab replacement tool (accessible under the Tools menu).

Negative:
We're still running into issues with running a level created by the LevelBuilder. The issue doesn't seem to be the reconfigure layers as was theoried last week.    

Upcoming:
I'm looking to utilize the new prefab replacement tool to help with Hex assignment later on. The LevelBuilder bugs are to be handled and I'll also start working on music again.


### Week 5 - Week 6
Kendal Mitchell, PPJ 4

Fixed a bug with the level editor that would cause misassignment of hex game objects to the hex grid. I also continued working on improvements to our level builder and refactored editor instantiation before adding individual hex, player, and enemy assignments.

I spent about 6 hours of development work this week. 

Positive:
I was finally able to figure out several bugs with the level editor that had been evading me for the past few weeks. 

Negative:
I wasn't able to get all of my level editor changes in time, but should be able to get my changes in within the next sprint.  

Upcoming:
Once the level editor is on a readied state, I'll be able to move back into music production and story work.

### Week 6 - Week 7
Kendal Mitchell, PPJ 5

I spent about 7 hours of development work this week.

Positive:
This week I got to add more changes to our Level Builder Tool and fixed some lingering bugs. Users may now include player spawn positioning and update tiles and character spawns. I've finally traced down the source of a NullReferenceException error and will be fixing it this week.

We also found an alternative for updating tile variants that works well for our designers. 

Negative:
I didn't have time to finish refactoring the NullReferenceException singleton instance errors, but will be able to get them in this week.     

Upcoming:
Once I finish up with the level builder, our designers can finally start mass producing their designed levels. It'll give us more content to get in the hands of our players and help us get better feedback. 

### Week 7 - Week 8
Kendal Mitchell, PPJ 6

I spent around 8 hours of development work this week. 

Positive:
This week was spent debugging and pair programming with Cyn and Yash on our Level Builder. Although, it's not entirely fixed, we got valuable information out of attempting solutions, discovering that our Singleton was dealing with serialization issues between Edit and Runtime. 

Negative:
The continued NullReferenceException and singleton issues are starting to impede our generation of levels. We'll need to get this fixed so a more accessible tool is ready for our designers.

Upcoming:
I'll definitely need to finish up with the level builder this week and start music production, as well as any other tasks I'm assigned. 

### Week 8 - Week 9
Kendal Mitchell, PPJ 7


### Week 9 - Week 10
Kendal Mitchell, PPJ 8


### Week 10 - Finals Week
Kendal Mitchell, PPJ 9

[back](Blogs.html)
