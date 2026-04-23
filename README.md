# Plunder Party

**Unit Name:** Gameplay Design and Programming / Client Brief

**Student Name:** Harry Lehman

**Student ID:** 2407002

**Total Word Count:** \[XXXX]

**API Reference Link:** \[URL]

**User Guide Link:** \[URL]

**Build Link:** \[URL or Embed]

**Video Demonstration Link:** \[URL or Embed]

---

## Project Outline

My task for this project was to work in a team with game design students to create a pirate-themed party game consisting of three different minigames. For this project, the designers were responsible for coming up with the concepts and artwork for the game, whereas I was responsible for implementing the gameplay mechanics. The designers came up with the concept of the game being themed around a child's imagination, with the game scenes and pirate characters all being toys and other objects a child would normally have. The three game concepts we decided on were a game in which the players had to hold onto a peg leg item for as long as possible to win, a whack-a-mole style game where players had to hit rats in barrels with hammers, and a boat race game where you had to cross the finish line first while avoiding obstacles.


---

## Research *(Approx. 20-30% of word count)*

### What sources or references have you identified as relevant to this task?

Reflect on the **type** and **relevance** of sources explored. Justify your research direction in relation to the task brief and target outcomes.

* What types of sources did you explore and why?
* Which types of sources did you avoid and why?
* How does the research relate to the user experience, technical approach, or creative aim?

#### Sources

For each source, provide:

1. An **opening paragraph** describing the source's creator/publisher, reputation, and relevance.
2. A **bullet list** of what you analysed or learned from it.
3. A **closing paragraph** evaluating its usefulness or limitations.

You may include both **academic resources** and **industry examples** (e.g. documentation, games, developer talks). You are encouraged to include plenty of images, videos and diagrams.

> You should have at least 1 game source as inspiration, 1 documentation/tutorial source and 1 academic source at a minimum.

To create the different minigames for this project, I researched similar games for inspiration on game mechanics. The first minigame, Peg Leg, is a game where there is a peg leg object that players fight over. As inspiration for this minigame, I researched Mario Kart 8 Deluxe, specifically the Shine Thief minigame in the game's battle mode.

In Mario Kart's Shine Thief game, players fight over the shine item. When a player is holding the shine, their team's counter goes down. When a team's counter drops to zero, that team wins. If the player holding the shine is hit by an item, they drop the shine, giving the other players an opportunity to pick it up.

The mechanics of Shine Thief are very similar to what I want to achieve for Peg Leg, with the main difference being that since there's no items, the player holding the peg leg will drop it by bumping into another player. The general driving mechanics of Mario Kart also serve as great inspiration for the third minigame, Row-Mania.

The second minigame, Splat-a-Rat, is a whack-a-mole type game where each player has a hammer and gain points by hitting rats that pop out of barrels. Whichever player scores the most points before the thirty-second timer runs out will win. While many party games have made their own variations of whack-a-mole, the version I specifically researched was the Hammer Heads minigame from Wii Party.

This specific version of a standard whack-a-mole is almost exactly what I hope to achieve for my minigame, and has also given me some inspiration for game mechanics that could improve the competitive aspect of the game, such as being able to stun other players by hitting them with the hammer, or a special type of rat that awards more points.

---

## Implementation *(Approx. 30–40% of word count)*

### What was your development process and how did decisions evolve?

Describe your technical and creative approach, including:

* Planning, ideation, and iteration
* Feedback received and how it was integrated
* New tools, workflows, or systems explored

### What creative or technical methods did you try?

Were any methods unfamiliar or experimental? Did they succeed? Did they change your approach?

### Did you experience any technical challenges?

How did you address problems, bugs, or limitations?

---

## Testing

Unfortunately, due to a number of reasons including unforeseen technical issues and several personal issues, there were many bugs that rendered the minigames almost unplayable that were not fixed until very late into development, meaning there was not enough time to perform user testing and gather data on tests.

---

## Critical Reflection *(Approx. 10–15% of word count)*

### What went well?

* What strengths or successes stood out in the final piece?
* Did anything exceed expectations?

### What could be improved or done differently next time?

* Were there things that didn’t work? Why?
* What would you try differently with more time or resources?

An aspect that I felt worked very well in this project was how well I collaborated with the game designers.

However, there are many things in this project that I think did not go as well as they could have. The biggest example of this is the movement of the boats in Row-Mania. My original intention was for the boats to move forward and steer left and right, however despite trying several different methods I could not get the movement to work properly before the deadline, so I simply copied over the default player movement. If I had more time on the project, I would try other methods to get the boat's movement working as intended. Other aspects of the project I would improve upon if I had more time would be to add additional features that I considered but could not implement, such as being able to hit and stun other players in Splat-a-Rat, or adding the special rat that gives bonus points. I would also make sure to set aside enough time to conduct user testing and gather results from those tests.

---

## Bibliography

Please use [UCA's Harvard Referencing Format](https://mylibrary.uca.ac.uk/referencing) for all citations.

Example:

> Rollings, A. and Adams, E. (2003) *Andrew Rollings and Ernest Adams on Game Design*. New Riders Publishing.

---

## Declared Assets

You must declare any content that was **not entirely created by you**, or was **modified with the aid of AI tools**. This includes:

* Third-party 3D models, audio, textures, or code
* Code snippets from tutorials or forums
* AI-generated or AI-assisted assets (e.g. ChatGPT, GitHub Copilot, DALL·E)

List these clearly, with context where needed.

Example:

> The following assets were created or modified with the use of GPT-4o:
>
> * `Test.cs` – generated structure with manual revision
> * `UIAudioManager.cs` – refactored with Copilot suggestions
> * `DevelopmentJournal.html` – generated layout and headings

---