 # COMP2150 - Level Design Document ### Name: Lukas Strohkorb ### Student number: 47910356

1. Player Experience

1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?
In the beginning of the level, the player is introduced to the core mechanics of the game. The first encounter the player has is their introduction to spikes and that they deal damage if touched. This allows the player to understand that they are a threat and to be careful around them later in the level. After this they are introduced on how to heal health through health pickups !The spikes and health pickup(DocImages/<Spikes.PNG>). Soon the player encounters an acid pool and has to navigate across it on the floating platforms, as well as discovering their first checkpoint. This teaches the player that if they fall into the acid they get spawned back at the checkpoint !The acid and checkpoint(DocImages/<Acid.PNG>). Upon advancing the player encounters their first enemy and quickly realise they don’t have a way to damage them, so they must run past them and discover the first weapon, the staff. Now they are able to fight back !The Chompers and Staff(DocImages/<Chompers and Melee.PNG>). These three encounters teach the player what to expect and how to deal with these challenges that will come up throughout the level.

1.2. Drama
Throughout the level the player will encounter various different moments of intensity. One of these encounters is the spitter elevator section on the right side of the level. As the elevator begins moving upwards, the player is quickly met by the spitters along the walls of the elevator, increasing the tension and intensity. Once they get to the top they are met with relief of having just survived the encounter !The elevator with the spitters in the walls(DocImages/<SpitterElevator.PNG>). After this encounter the player has to get across an acid pit on a moving platform, trying to jump over the spikes all while getting attacked by spitters above them. After having a moment of relief they are thrust into an extremely dangerous and intense situation that only ends after they reach the other side !An in-engine photo of the scenario(DocImages/<SpittersAndAcidPool.PNG>). A similar dramatic moment to the spitter elevator is the spike elevator, located on the opposite side of the map. In this elevator the player has to navigate around the spikes that are in their path. Tension increases as the player gets close to spikes and are met with moments of relief after passing them !Elevator with the spikes(DocImages/<SpikeElevator.PNG>). These encounters all contribute to modulating intensity throughout the experience.

1.3. Challenge
The main challenges that occur throughout the level are both halfway through and at the end of each section. The middle sections are the elevators, and they act as a health check for the final encounter. In the case of the left side of the map, the player goes up the spike elevator and possibly taking damage along the way !Elevator with the spikes(DocImages/<SpikeElevator.PNG>). After this they are met with the final encounter of this section. Here they have to first get across an acid pool while getting attacked by a spitter that may hit them into the acid, after this they have to get past the enemies in a long corridor to retrieve the key !Final Encounter(DocImages/<FinalEncounterLeftSide.PNG>). These seamlessly transitioned encounters allow the player to remain in the flow channel by modulating the difficulty. I had to balance the spitter by lowering their range as before they were too difficult and it would result in the player falling into the acid pool too often and was quite annoying. The other main challenges that the player faces is the spitter elevator, which confines the player into a small area while getting attacked from above and the sides by the spitters !The elevator with the spitters in the walls(DocImages/<SpitterElevator.PNG>). Shortly after the elevator the player takes on the final encounter of this section, which takes a bunch of what they have learnt throughout the level and puts it to the test. This section underwent many changes in difficulty and fine tuning to a point where I believe it to be a fair challenge. Changes such as adding and removing extra spitters, increasing and decreasing their range, all contributed to keeping the player in the flow channel !An in-engine photo of the scenario(DocImages/<SpittersAndAcidPool.PNG>).

1.4. Exploration
After the player completes the introductory section they are given the choice of two directions to go, if they go left they are thrown down into a cave, in this section they come across a pressure pad that moves the elevator, however the player soon discovers that they need something to weigh it down. This encourages them to go exploring a way to do so, which leads them to a wall that they can break, revealing a box above the pressure pad that the player then pushes onto it !An in-engine photo of the scenario(DocImages/<ElevatorPuzzle.PNG>). The cave design of this section makes this area distinct and memorable. As for the right side section, the player comes across a moving platform above an acid pool, and if they go on it they are taken across to a door that requires something to open it, but the player doesn’t know what or how yet. This invites them to go exploring for it, which ends up being the gun to shoot the switch !An in-engine photo of the scenario(DocImages/<GunPickupArea.PNG>). These areas of uncertainty and choice allows the player to explore the level how they want to, instead of being told where to go and what to do.

2. Core Gameplay

2.1. Spikes
!Storyboard(DocImages/<StoryboardSpikes.PNG>)
This storyboard depicts how the player should handle spikes. This is done by showing that they need to jump over them otherwise they lose a heart. I chose to put this here so the player understands that can take damage straight away.
2.2. Health Pickups
!Storyboard(DocImages/<StoryboardHealthPickup.PNG>)
This storyboard displays how if the player wishes to regain their lost health, they must find one of the brown boxed health pickups to regain a lost heart. I put this here so the player knows that they can heal from damage right after first experiencing taking it.
2.3. Checkpoints and 2.4. Acid
!Storyboard(DocImages/<StoryboardAcidAndCheckpoint.PNG>)
This storyboard shows that the player has to get across without touching the acid because if they do they will lose a heart and respawn at the checkpoint they previously walked past. I put this here so the player quickly learns that if they fall in the acid they can respawn at a checkpoint.
2.5. Moving Platforms
!Storyboard(DocImages/<StoryboardMovingPlatform.PNG>)
This storyboard explains to the player what moving platforms are and how they work. I put this here to add a challenge to the acid pool.
2.6. Chompers
!Storyboard(DocImages/<StoryboardChomper.PNG>)
This storyboard introduces the player to their first enemy, the chomper, and that currently can’t fight them so they must jump over them or risk getting attacked and losing a heart. I put this encounter before getting the weapon to show that these enemies are dangerous if not given the correct tools.
2.7. Weapon Pickup (Staff)
!Storyboard(DocImages/<StoryboardStaffPickup.PNG>)
This storyboard shows that after picking up the staff, the player is now able to kill the enemy chompers. I put this after your first encounter to show the player that they actually can kill the enemy.
2.8. Passthrough Platforms
!Storyboard(DocImages/<StoryboardPassthroughPlatform.PNG>)
This storyboard explains that the player can pass through certain platforms that look like this. I put this at the end of the introductory section as it drops them into the actual sections of the level and ends the linear part of the level, allowing the player to explore the map.
2.9. Keys
!Storyboard(DocImages/<StoryboardKeys.PNG>)
This storyboard introduces the player to the keys that they must get to open the door. I chose to put it here because it set the goal for the player to complete and cements that they are out of the tutorial section.
2.10. Weapon Pickup (Gun)
!Storyboard(DocImages/<StoryboardGunPickup.PNG>)
This storyboard displays the player discovering the gun pickup. I chose to put it here as it shows that you will be needing it for what this section is putting you against.
2.11. Spitters
!Storyboard(DocImages/<StoryboardSpitter.PNG>)
This storyboard explains to the player that spitters have a ranged attack that takes a heart, and that you can shoot them using the gun. I chose to put this here and it shows that you can shoot crouched to reach lower level enemies or switches with the gun. Which is needed in this section of the level.
3. Spatiotemporal Design

3.1. Molecule Diagram
!Molecule Diagram(DocImages/<MoleculeDiagram.PNG>)
3.2. Level Map – Section 1
!Level Map 1(DocImages/<LevelMap1.PNG>)
3.3. Level Map – Section 2
!Level Map 2(DocImages/<LevelMap2.PNG>)
3.4. Level Map – Section 3
!Level Map 3(DocImages/<LevelMap3.PNG>)

4. Iterative Design

Iterative design helped me to improve my level design by being able to create a section of the map, look back on it and test out whether or not the concept works, and if it works as intended. This led to sections being removed entirely from the final design. This allowed me to tweak enemy encounters to either be more challenging by adding more enemies, or if it was too difficult I could remove enemies or lower their attack range. Sometimes making it more balanced meant changing the environment instead. Such as adding more platforms for the player to jump on, or removing obstacles that damaged the player. An encounter from my level that could be improved through further iterative design is the final encounter on the right side of the map. Further testing needs to be conducted on it as it may be too difficult to complete. For example I could have an outside source playtest it and give feedback on what should be changed.
