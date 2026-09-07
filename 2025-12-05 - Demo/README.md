# Project Demo Completed Features

Copy / paste the checklist from Project Specification into this section to indicate which features are complete in the demo

# Project Demo Instructions

For the project initial demo, you must record a narrated 3-5 minute video showing your project progress so far. The following features must be present in the demo:

- A functioning level editor using ImGui. Does not have to be 100% complete, but you must be able to create / load / save levels.
  - Show the ability to edit, create, save, and load a level (if possible)
- Most working gameplay mechanics
  - Record a few minutes of gameplay footage where you narrate the game mechanics being displayed
  - Do not waste any video time with re-trying things, failures, or long stumbles in speech
  - Pay more attention to any new mechanics you have implemented that are not present in the assignments
  - This is YOUR VIDEO. I don't know what's fully working or not, so cherry pick the best parts. If your project crashes sometimes, just leave that out of the video.
  - I will probably not be looking at the demo code unless something is a) horribly broken, or b) suspiciously overdone

***

This folder contains the following 3 directories:

```
bin/ 
  - must contain your compiled game executable
  - must contain any additional files you need in your bin dir such as assets / fonts
  - do not include any visualstudio output debugging files such as .pdb files

src/ 
  - must contain all of your project source code

visualstudio/
  - must contain your visual studio project files
  - delete all temporary output directories, they contain massive files
    - visualstudio/x64
    - visualstudio/.vs
```

Notes:
- This setup is exactly the same as your course assignments. You may start the project by copying an assignment into this directory and editing it. 
- This entire submission should be no more than a few megabytes at most without the temporary vs files
- Upon submission of the demo, please remove everything from this README besides the Completed Features section above
