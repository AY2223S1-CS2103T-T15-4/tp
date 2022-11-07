---
layout: page
title: Ervin Kin's Project Portfolio Page
---

### Project: Gim

* Gim is a **desktop app for managing gym exercises, optimized for use via a Command Line Interface** (CLI) while still having the benefits of a Graphical User Interface (GUI). If you can type fast, Gim allows you to keep track your exercises and Personal Records in a efficient way.
  Example usages:
  * as a tracking tool to keep track of completed exercises
  * as a tracking tool to keep track of your personal records
  * as a workout generator to generate exercises based on your personal records

Given below are my contributions to the project.

* **New Feature**: Saved Exercises list in bottom right of the GUI ([PR #107](https://github.com/AY2223S1-CS2103T-T15-4/tp/pull/107))
  * What it does: Provides User with an idea of what unique exercises they have inputted in the system.
  * Justification: This is especially important when the exercise list is populated/ the user has been using the app for a long time. He may accidentally misspell an exercise name when keying it in, causing the system to miss out on a potential personal record/entry. It also provides the user a guide to which exercises they can filter out. 
  * Highlights:
    * Added Exercise Keys Class which handles logic behind ExerciseHashMap keys. 
    * Used Observer Pattern design in facilitating real time interaction between ExerciseHashMap and UI.
    * Update ExerciseHashMap with relevant methods and fields to support Observer pattern.  
    * Conducted testing while designing the feature such that code coverage remained consistent (no change in coverage after push)
* **Code contributed**: [RepoSense Link](https://nus-cs2103-ay2223s1.github.io/tp-dashboard/?search=ervink123&breakdown=true&sort=groupTitle&sortWithin=title&since=2022-09-16&timeframe=commit&mergegroup=&groupSelect=groupByRepos&checkedFileTypes=docs~functional-code~test-code~other)

* **Project management**:
  * Managed issue tracker for v1.3 and v1.4 
  * Created milestones for v1.3 and 1.4  

* **Enhancements to existing features**: 
  * Redesigned Help Window ([PR #115](https://github.com/AY2223S1-CS2103T-T15-4/tp/pull/115), [#141](https://github.com/AY2223S1-CS2103T-T15-4/tp/pull/141), [#142](https://github.com/AY2223S1-CS2103T-T15-4/tp/pull/142))
    * What I did: 
      * Help window now provides a brief summary of available commands on top of a link to the user guide. 
    * Justification: 
      * Provides convenience as users can now get some basic help in the help window instead of being redirected to the user guide. This enhancement saves clicks and time in the long run.  
  * Redesigned User Interface (PR #84, #94, #116)
    * What I did:
      * Moved Result Display window to the right and added Saved Exercises List window. 
      * Separated Date as a standalone label in the Exercise Card UI. 
    * Justification: 
      * For moving the Result Display window and adding the Saved Exercises List window, the previous UI had a lot of wasted real estate as the cards were taking up a lot of space. Furthermore, the result display window was too small and needed to scroll, especially when a long error message came up, which was inconvenient. By moving it to the side, it would make messages much easier to see and tie in with the Generate and Listing PR features on top of existing system messages.
  * Added Reps as a field to the creation of an Exercise. ([Pr #67](https://github.com/AY2223S1-CS2103T-T15-4/tp/pull/100))
    * In charge of REGEX and operations relating to reps. 
  * Removing edit feature and tests relating to it ([Pr #127](https://github.com/AY2223S1-CS2103T-T15-4/tp/pull/127))

* **Documentation**:
  * User Guide:
    * Standardised pictures in User guide, included callouts for important information in each picture. ([PR #202](https://github.com/AY2223S1-CS2103T-T15-4/tp/pull/202))
    * Wrote entire section for GUI orientation 
    * Crafting of tips and format of the User Guide

  * Developer Guide:
    * Wrote section on listing of unique stored Exercises in the graphical UI 
    * Added UML diagrams (class and sequence diagrams) for recognised exercise list implementation
    * Added User stories 

* **Community**:
  * Reviewed Team Member's PRs.
  * Provided ideas and contributed in discussions during weekly team meeting. 

* **Tools**:
  * PlantUML: Creating UML diagrams. 
  * SceneBuilder: Edit FXML files which Gim UI components use.
