---
title: Template Blog
layout: default
---

## Welcome to Michael Dardour's Personal Production Journal

### Week 2
Michael Dardour, PPJ 1

Week 2 mainly consisted of getting my one and other group members git repositories and Unity versions in sync. (1hr)
Additionally I made comments about movement systems in other games such as Titanfall and how they could potentially be used as a basis of how Momentums system could perform.  (1.5hr)
Worked with Yash and Kendall mocking up the tech demo to show the player moving through a hexagonal grid with a basic environment. (2hr)


Positive: Got to brainstorm and bring up ideas 

Negative: Unity is finicky and had to spend way too much time trying to download the correct version

Total Hours: 4.5

Tags: Design, Programming, Week 2

### Week 3
Michael Dardour, PPJ 2

Spent time going over various ways of creating an easily accessible and scalable base character script which all enemies should derive from. Player character also derives from this script  (2hrs)

Took example sprites to show basic sprite interactions (2hr)

Discussions with other team members as to what characters should have certain attributes such as momentum. Eventually decided that the player is the only person with a Momentum Mechanic, however ideas of having a boss with momentum is still on the table (1hr)


Positive: Made a solid foundation for every character piece that will be implemented in the game. 
Negative: Unities method of doing sprite animations are tricky, and requires some workarounds to do basic things.

Total Hours: 5

Tags: Design, Programming, Animation, Week 3


### Week 4
Michael Dardour, PPJ 3

Created the BattleController which signals the rounds for the player and enemies. Additionally altered the characters to work with the BattleController. (2h)

Worked on finalizing the new Momentum System and updating the GDD. (4.5h)

Total Hours: 6.5

Positive: Got everyone on the same page for the general game flow and got good examples on the GDD.

Negative: Need to find better times to meet about design because I sleep early.

Tags: Design, Programming, Week 4

### Week 5
Michael Dardour, PPJ 4

Created method to find appropriate tiles for player movement in a certain direction (3hr)

Used the above method to handle player movement (2hr)

Worked on GDD and updated concept (2hr)

Helped art team to bring assets into Unity (30 min)

Total Hours: 7.5

Positives: Got a robust method of movement for the player.

Negatives: Was very swamped on work.

Tags: Design, Programming, Week 5

### Week 6
Michael Dardour, PPJ 5

Made methods to determine which way is forward, left, and right of the players current direction on a hex (.5hr)

Created appropriate movement cones & momentum logic for momentums 1 and 2. (2hr)

Attached logic for changing of direction dependant on certain tiles (2.5hr)

Implemented Sliding mechanic for after the players turn ends (1hr)

Remade the HexClicker script to be more readable and add various useful functions for the future. (1hr)

Total Hours: 7

Positives: Redid some old code to make things easier for the future

Negatives: None really, things were pretty smooth id say

Tags, Programming, Week 6

### Week 7

Michael Dardour, PPJ 6

Updated method in which player damages enemy (3h)

Created appropriate framework to house future abilities (1hr)

Various small updates to other code while implementing new methods/changes (0.5h)

Began but did not finish a method for Bounce (2hr)

Total Hours: 6.5

Positives: Made a lot of headway in getting Abilities to be easily created for the future

Negatives: Found some bugs that I havent gotten the chance to squish since I've been working

### Week 8

Michael Dardour, PPJ 7

Created proper Bounce Ability (As well as framework for abilities with targeting hex) (4hr)

Created Boost Ability (As well as framework for ability that fires outside of your turn) (.5h)

Created Whirlwind Blade Ability (Simplest ability targets and attacks all enemies around player) (.5h)

Gained a better understanding for how best to target tiles and implemented methods to do so (1hr)

Total Hours: 6

Positives: Abilities are now extremely easy to make and change now that the framework is in place

Negatives: Bounce Ability still needs tweaking

Tags: Programming

### Week 9

Made it so that the player now attacks enemies they slide into rather than crash (3hr)

Made it so that the player crashes if they have no available move options (ie stuck in corner) (1hr)

Prevented a bug that allowed the player to damage an enemy they are not targeting (.5hr)

Positives: Fixed bugs and made the game smoother for slides

Negatives: Multi-attacks are a little bit strange, may need to work on them.

### Week 10

Michael Dardour Individual Post-Mortem

"Momentum is a turn based game with movement as its core mechanic." Thats what I envisioned when I saw the pitch of this game, a time traveling swordsman gaining speed to completely slice through all that stand in his way. I really loved to envision that and wanted to design a system that could really capture that feeling for people, which is why I joined the team. The road was very bumpy, but still rewarding nontheless I'd say. If I was to describe my role in the team I would say I was the Player Logic Programmer, as well as game designer. For this post mortem Im going to describe things in a "Good -> Bad -> Good" order

Good - More than one programmer with independant capabilities
I have dealt with many game projects where I was the "main programmer". Sometimes I was the only programmer, othertimes the other programmers would always ask me for help since they didnt understand unity. But Momentum was the first game project I've worked on where I was able to depend on other programmers to handle larger tasks while I could concentrate on my own. We all had clear goals to work on, and were able to plug in everything once finished. It was very effective and very alleviating.

Bad - Only one animator
Since we only had one person animating, it was a bit of a struggle for him to get all the enemy types moving and integrated. Our project lead sometimes had to do art portions along with programming to help him out.

Good - Scalability
From the start we made the game with scalability in mind. It is simple to add and adjust just about everything. This applies to Levels, Player Abilities, Enemy types, and more.

Bad - Starting game ideas
I feel like this is mainly my fault, but I found out a little bit into development that my idea of what the game should be was different than what the creator thought it should be. I brought up my ideas and we had discussions as a group about it. My ideas were rougher and more experiemental that the group leads were, where as his would have made it simpler to implement and more easily polishable. In the end we put it up to a vote and my idea won by one vote. At the time I felt like it would make the game have more depth and potential, however I feel like it may have instead caused us more work for a less polished game. Examples include the Hex grid taking a large portion of our time to implement and fully understand. The momentum system is also something that was discussed as being too complex for players. I should have realized how complex the system that I was making when I was having trouble describing it to my own teammates.

Good - Weekly meetings
We had weekly meetings that allowed us to reflect on what our current situation was, who would do what, and how to handle everything. The weekly meetings proved to be incredibly effective in refocusing ourselves.

Bad - Low Moral during the end
Im not exactly sure why, but for some reason a few members of the team felt like the professor didnt like how our game turned out and that it was getting scrapped for the other teams idea. While I cant say whether this is true because I am not the professor, but I felt like the claims were unfounded since the professor showed no favoritism to either game. Though I feel like the idea impacted some members of the team poorly.

Generally if I were to say whether Momentum was a success or not I would say that it has, and still has potential. We spent more time then we should have implementing certain features, however those features having now been implemented just needs some more time to make a more interesting game out of them. Things we were missing was levels and AI, which was in the works for very long, but just about never seemed to see the light of day unfortunatley. I feel like Momentum is a similar story of Icarus, we started out very far then people and things started to burn out unfortunatley.





### Week 1

Had a long discussion with the rest of the team on where we should head design wise. (3hr)

Attempted to implement a possible large scale gameplay change to our existing built (3hr)

Total Hours: 6

Positives - got a good start with checking in with the new members and onboarding, some have really great ideas for the game.

Negatives - The code seems different and more complex then what I remember making, likely due to many people working on it at once last quarter. 
[back](Blogs.html)
