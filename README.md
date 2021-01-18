# GUI Explorations for the Rust DAW
The Rust reference DAW will need a UI. In this DAW we are gathering requirements for that UI and developing a prototype. 

## Purpose of this Repo
This repo is for the following:
+ UX requirements.
+ GUI design & wireframes.
+ Prototype code
+ Benchmarks from other DAWS. These can be:
  + Examples to Follow
  + Examples to Ignore

## Using This Repo
New user stories and benchmarks should be added using issues. 

Requirements can also be added as issues, but user stories are the preferred process.

### Adding User Stories
User stories should use the [user story template](https://github.com/RustyDAW/gui-explorations/issues/1).

### Benchmarks
Benchmarks should follow this template:
TODO

## DAW UX Priorities
If there is a conflict then primary priorities take precedence over secondary priorities.

### Primary UX Priorities
This DAW must:
+ Be Efficient To Use
+ Be Easy to Learn

### Secondary UX Priorities
This DAW should:
+ Look Good
+ Be Flexible
+ Be Intuitive

## UI Feature Priority List
The following features have been identified to work on initially:
+ [ ] Timeline _started_
+ [ ] Short CUts & Command Palette _started_
+ [ ] Media Bin
+ [ ] Transport Bar
+ [ ] Routing UI
+ [ ] Automation
+ [ ] Mixer
+ [ ] DAW Shell
+ [ ] Global Standards for UI, widgets, controls, errors
+ [ ] Color Palette

Other features will be added as the main DAW project progresses.

## Design Motivations

### Automation
Global automation, particularly when editing, is a pain in most DAWs. DAWs really do what the user thinks they should do, or it's hard to predict what they will do. We want to solve this problem.

### Keyboard Shortcuts
Keyboard shortcuts allow power users to be vastly more efficient, but they are rarely intuitive and require a lot of memorization. We would like to make keyboard shortcuts intuitive, learnable and easy to remember. We would also like to at least investigate ideas from applications such as VIM's modal editing to see if we can steal some of those ideas for power users.

### Modes
DAWs have a bunch of different modes, but don't make it clear what mode they're in. Consequently it's often easy for a user to forget which mode they're in and so do the wrong thing. Modal UIs are a well studied UX problem, but also unavoidable in a DAW.

In this DAW it should always be obvious to the user which mode they're in, and how to change modes. There should also be a way to set to an initial mode quickly (e.g. by pressing escape).

## Additional Things that Need a Place
+ time signature changes
+ tempo ramping.
+ Supporting microtonal music
+ Folders/Subgroups for tracks (like Reaper)

## Background Reading
+ https://admiralbumblebee.com/DAW-Wants.html - essential reading.
