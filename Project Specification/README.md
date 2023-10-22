# COMP 4300 Project Specification

## Project GitHub URL Submission

As soon as you have formed a group for the project and created a GitHub repo, please submit your group GitHub repo URL to the `Group GitHub Repo URL` assignment folder on D2L. This must be done before the due date of the Project Proposal.

## Project Proposal (5%)

Your group must submit a project proposal by 11:59pm on the date listed on the proposal folder. 

## Required Game Features / Gameplay Functionality (75%)

### Game Overview
  - Must be implemented using ECS architecture in C++ using only the SFML / ImGui libraries
  - You may use any course code already written for assignments as the bases for your project game
  - Game Types Allowed: 2D Platformer, Top-Down Shooter, Action RPG, etc
    - If 2D platformer is chosen, it must be significantly different from Assignment 3
    - No assets or levels may be re-used from the class assignments
  - Must contain at least 3 pre-built levels, and have a separate 'final boss' battle level
  -	Must contain a custom menu that allows the player to play the game, edit levels, or select options
  - Must contain some sort of in-game menu (item selection, inventory, options, etc)
  - Must contain a level editor that allows for loading, editing, and saving of game levels (see relevant section)
  - Must contain a ‘game over’ screen indicating when the game has been finished
  - All levels, player, and game configuration options must be defined in external text files
  - All assets should be gathered or created by the project group members


- [x] Chosen speciality is: _____
  - [ ] Specialty implemented successfully and demonstrated in video
- [ ] Resource Gathering Basics
  - [ ] All idle workers sent to gather minerals
  - [ ] 3 workers placed in each gas refinery
  - [ ] Max 2.5 workers per mineral patch in base
- [ ] BuildOrder Production
  - [ ] BuildOrder class parses text file
  - [ ] BuildOrder queue works properly
    - [ ] Loop monitors queue for next item to be built
    - [ ] If resources available, check for builder unit
    - [ ] If builder unit found, check build location (if required)
    - [ ] If build location found, built unit and remove from queue
    - [ ] Be sure to 'reserve' resources so items don't get skipped while building
- [ ] Scouting
  - [ ] All enemy units and their last positions recorded / drawn
  - [ ] If enemy base is not known:
    - [ ] Move toward next possible enemy location
  - [ ] If enemy base is known:
    - [ ] If outside enemy base, go toward it with scout
    - [ ] If inside enemy base, attack enemy worker
    - [ ] If worker attacks back or has defenses, retreat scout
- [ ] Defense
  - [ ] Enemy units in base detected, circle drawn around them
  - [ ] Static defense structure constructed
- [ ] Attack Timings
  - [ ] Army units rallied after production
  - [ ] Condition for attack calculated successfully
  - [ ] Attack sent toward known enemy location
  - [ ] Final enemy buildings found and destroyed
- [ ] Expanding
  - [ ] Natural Expansion location calculated and drawn to map
  - [ ] Expansion built and demonstrated at least once for video
- [ ] Succesfully default built-in AI sometimes
