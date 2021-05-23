# 2021 may videos

Help us edit videos!
- Find the link to the video archive (in zulip)
- Look below to see what is unfinished
- Watch the video, and use the examples to fill out new segments
- Make sure the input file is what you expect
- Using the Twitch input file is in principle better right now
- **Make sure audience video is not in stream (anything besides (CR) people**.  Voice is OK.  **If people are visible and you can't cut it out, make a clear note of it.**
- Special cases
  - Need to combine muliple different files into one?  Ask for the syntax
  - Does the syntax not express something you need?  Make it up and we will adjust syntax to match what you need.
- If you can record key points for the table of contents, e.g. "45:10: 02 Basics", write it down somehow and we can turn it into a table of contents.
- Related Git issue: https://github.com/coderefinery/2021-05-10-workshop/issues/45

## Permission to post
Add your name here if you give permission for any video including your **name**, **profile picture**, **voice**, or **video** to be posted on YouTube CC-BY:
* Richard
* Sabry
* Naoe Tatara
* Patric Holmvall
* Thor Wikfeldt
* Johan Hellsvik
* Juho Lehtonen
* Samantha Wittke
* Stefan Negru
* Max Roald Eckardt
* Radovan
* Anne Fouilloux

## General footer for all video descriptions

This will be added to the bottom of every video description:

```yaml
- workshop_description: >
    This is part of the CodeRefinery May 2021 workshop.  The videos are available to everyone, but may be most useful to the people who attended the workshop and want to review later.


    Playlist: https://www.youtube.com/playlist?list=PLpLblYHCzJACm0Nz8ZxmdC6F8UuSYwWGQ

    Workshop webpage: https://coderefinery.github.io/2021-05-10-workshop/

    CodeRefinery: https://coderefinery.org/
```

## Day 1

```yaml

# This input will be used for all segments until redefined
- input: cr-2021may-day1-obs.mov

# welcome
- output: day1-welcome.mp4
  title: Intro - CodeRefinery May 2021
  description: >
    The introduction to this workshop, explaining general mechanics and what CodeRefinery is.
  time:
    - 12:20, 31:14

# Git-intro day 1
- output: day1-git-intro-1.mp4
  title: Git Intro day 1 - CodeRefinery May 2021
  description: >
    Here, we go over the basics of git from first principles, though
    this is not the most basic course you can find.  We cover basics,
    motivation, making commits, undoing things, staging.  The part 2
    video goes into branching and merging, conflict resolution,
    inspecting history, basics of
    sharing repositories online, and some practical advice.  However, this does not cover
    multi-user work or remotes (that is the next lesson, git-collaborative).

    There are two external videos which are excluded from this
    recording.  You can find the link to them in the table of contents
    below.

    https://coderefinery.github.io/git-intro/

  time:
    - start: 31:14      # Lesson (Sabry)
    - 31:14: Overview of the day
    - 33:25: Motivation to version control
    - 38:12: '"The Life of a Document", watch at https://www.youtube.com/watch?v=CvbLVVRzJF8'
    - end: 38:51
    # cut to remove YouTube video
    - start: 40:55    # Lesson (Sabry)
    - 40:55: Lesson continues
    - end: 1:04:45
    # 1:06:14-1:09:33, gallery view including some audience
    # going to breakout rooms
    - 1:18:22, 1:28:27  # Exercise for breakout room (Sabry)
    # 1:29:29-1:31:23
    # break
    - start: 1:41:40   # Lesson (Sabry and Diana)
    - 1:46:30: External video, Linux Torvalds on git, https://youtu.be/4XpnKHJAok8?t=2625 (43:45 to 44:26)
    - end: 1:46:48
    - start: 1:47:44
    - end: 2:24:07
    # going to breakout rooms
    - 2:28:44, 2:36:38  # Exercise for breakout room (Diana)
    # break
    - 2:53:20, 3:20:53  # Lesson (Sabry)

    - 41:28: Real-life repository examples
    - 48:35: Basics of version control
    - 1:18:22: "Exercise: record changes"
    - 1:51:13: "Summary so far: basic git commands"
    - 1:52:02: Using the staging area
    - 1:58:45: Interactive committing
    - 2:28:44: "Exercise: Using the staging area"
    - 2:53:56: Ignoring things with .gitignore
    - 2:57:54: Undoing things
    - 3:13:32: Summary of the day
    - 3:20:01: What to expect in the next lesson
```


## Day 2

TODO: all, note the new format

```yaml

# Use Twitch for day 2
- input: cr-2021may-day2-twitch.mp4

- output: day2-intro.mp4
  title: Day 2 introduction - CodeRefinery May 2021
  description: >
    The quick introduction to Day 2.  This is mainly icebreaker discussion.
  time:
    - start: 11:33
    - end: 24:40

# Git-intro day 2
- output: day2-git-intro-2.mp4
  title: Git Intro day 2 - CodeRefinery May 2021
  description: >
    Part 2 of the previous video: 
  
    Here, we go over the basics of git from first principles, though
    this is not the most basic course you can find.  Previous video: We covered basics,
    motivation, making commits, undoing things, staging.  This part 2
    video goes into branching and merging, conflict resolution,
    inspecting history, basics of
    sharing repositories online, and some practical advice.  However, this does not cover
    multi-user work or remotes (that is the next lesson, git-collaborative).

    https://coderefinery.github.io/git-intro/
  
    The other conflict resolution video which was referred to in the video: https://www.youtube.com/watch?v=p03ebpjuRgA&list=PLpLblYHCzJAB6blBBa0O2BEYadVZV3JYf
  time:
    - start: 25:16      # Lesson (Sabry)
    - 25:16: Preparation
    - end: 29:05
    - start: 29:26
    - 29:26: Branching and merging
    - 35:50: "Demo: branching and merging"
    - 48:25: "Exercise: branching and merging"
    - end: 52:21
    - start: 53:30
    - 53:10: "Aside: What is the working tree?"
    - 53:38: "Exercise demo: branching and merging"
    - end: 1:04:55
    - start: 1:05:54
    - --: Q&A
    - end: 1:06:40
    - start: 1:08:18
    - end: 1:26:51
    - start: 1:38:30
    - -: Conflict resolution
    - end: 1:55:11
    - start: 1:56:13
    - -: Sharing repositiories online
    - 2:05:40: "Type-along: sharing repositories on Github"
    - end: 2:20:32
    - start: 2:33:04
    - -: Inspecting history
    - 2:35:32: "Inspecting history: the Git History browser"
    - 2:37:00: "Inspecting history: git grep"
    - 2:39:35: "Inspecting history: git log -S"
    - 2:41:19: "Inspecting history: git show"
    - 2:43:33: "Inspecting history: git annotate"
    - 2:46:59: "Inspecting history: git checkout -b"
    - 2:52:47: "Exercise: basic archaeology commands"
    - end: 2:57:45
    - start: 3:02:18
    - -: "Exercise as a demo"
    - end: 3:18:35
    - start: 3:20:08
    - -: Q&A about the exercise
    - 3:23:19: Quick summary of git-bisect
    - 3:32:18: Practical advice
    - end: 3:33:35
#    - 1:45: Title of section
#    - 5:45: Title of Section
#    - ??: Branching and Merging
#    - ??: Conflict resolution
#    - ??: Sharing repositories online
#    - ??: Inspecting history
#    - end: XX:??
```

## Day 3
All done

```yaml

- input: cr-2021may-day3-git-collab-twitch.mp4

- output: day3-intro.mp4
  title: Day 3 intro - CodeRefinery May 2021
  description: >
    The quick introduction to day 3.
  time:
    #Remove part before the start
    # soft start
    #- start: 12:35
    #- end: 21:38
    #wellcome
    - start: 21:39
    - end: 23:44

- output: day3-git-collab.mp4
  title: Git collaborative - CodeRefinery May 2021
  description: >
      Today, we expand from using git by yourself to using it in a team.  We use Github, centralized workflows, pull requests, and more.
  time:
        #intro, Centralized workflow (Sabry)
    - start: 23:45
    - end: 1:13:20
    #Remove discussion about break 
    #Explain excersise(Sabry)
    - start: 1:27:48
    - end: 1:31:08
    #People moving to BRO
    #Excersise for twitch viewers(Sabry)
    - start: 1:33:25
    - end: 1:34:06
    #small pose
    #Excersise for twitch viewers 2 (juho)
    - start: 1:37:08
    - end: 1:51:02
    # **Remove video of partticipant poping up**
    #- cover: {begin: "1:15:29", end: "1:51:34", w: 840, h: 300, x: 360}
    # This is already not in the segment
    - start: 1:57:25
    - end: 2:22:35
    #Break
    - start: 2:33:29
    - end: 2:47:20
    #BO room at 02:50:31 videos appear and should be removed
    #- start: 2:50:51
    - start: 2:49:40
    - cover: {begin: "2:50:30", end: "2:50:52", w: 840, h: 300, x: 360}
    - end: 3:02:21
    #Waiting for Bo people to return, remove username on video
    - start: 3:08:00
    - cover: {begin: "3:23:15", end: "3:23:20", w: 840, h: 300, x: 360}
    - end: 3:28:37
    #Remove a video flash
    - start: 3:34:45
    - end: 3:51:12

    #End 3:51:12

    #intro : 21:39 Diana
    - 23:45: Intro  #Juho
    - 28:58: Concepts arround collaboration #Juho
    - 41:41: Centralized workflow   #Sabry
    - 1:27:48: Exercise intro  #sabry
    - 1:33:25: Exercise demo  #Sabry
    - 2:15:09: Collaborative distribute VC   #(Juho)
    - 3:50:00: Daily wrap-up

```

## Day 4

TODO: intro
TODO: reproducible research

* Social coding
  * Presenter approved: YES

```yaml
- input: cr-2021may-day4-obs.mkv

- output: day4-intro.mp4
  title: Second week introduction - CodeRefinery May 2021
  description: >
    The introduction to the second week, where we go into slightly more detail about what we will cover this week and how it fits together.
  time:
    - start: 10:15
    - end: 15:20
    #- ????: Intro

- output: day4-reproducible-research.mp4
  title: Reproducible Research - CodeRefinery May 2021
  description: >
    If you can't get your code to do the same thing again, is it
    really science?  Or more practically, are you able to do your
    work?  Reproducibilty is a big deal, but we don't always learn how
    to do it.  In this lesson, we cover the basics, how to organize
    projects, record computational steps with Snakemake or other
    workflow managers, how to record environments with conda (and docker
    a bit), and sharing code and data (FAIR).

    https://coderefinery.github.io/reproducible-research/

  time:
    - start: 15:28   # first session before break, exclude meta
    - end: 1:05:10
    - 15:28: "Introduction"
    - 17:00: "Motivation"
    - 23:20: "Organizing your projects"
    - 31:25: "Begin the word-count example"
    - 39:15: "Dependencies"
    - 51:40: "Type-along: Conda environment"
    - end: 1:04:50
    - start: 1:16:20
    - 1:17:48: "Containers"
    - 1:22:58: "Recording computational steps"
    - 1:25:00: "Exercise preparation: Snakemake"
    - end: 1:33:30

    - start: 1:38:45
    - 1:38:45: "Snakemake exercise demo"
    - end: 1:45:35

    - start: 1:55:20
    - 1:55:25: "Sharing research data"
    - end:   2:00:40

    - start: 2:05:25
    - 2:05:25: Instructor discussion
    - end:   2:08:08

    - start: 2:12:41
    - 2:13:00: Fair principles
    - end: 2:15:34

- output: day4-social-coding.mp4
  title: Social coding - CodeRefinery May 2021
  description: >
    We don't just program for ourselves: we are part of a community.  As scientists, we want to get citations, so how can our software support this?  Our work is a constant balance between using the work of others and hoping that others will use our work.  In this lesson, we talk about the advantages and disadvantages of others building on our work, and how to support that.

    We cover best practices for software/data projects, requirements for sharing, copyright, licensing, citation, and more.

    https://coderefinery.github.io/social-coding/
  time:
    - 2:26:55, 2:31:15
    - 2:26:55: Intro
    - 2:27:50: Social Coding
    # Break for answering questions
    - 2:34:55, 3:01:00
    - 2:58:10: "Exercise: how to make a repository more reusable?"
    - 3:07:45, 3:12:20
    #- 3:16:14-17??  Learner in video
    - cover: {begin: "3:16:14", end: "3:16:17", w: 840, h: 300, x: 360}
    - 3:14:25, 3:17:20
    - 3:22:05, 3:38:30
    - 3:22:05: Licensing
    - 3:35:30: Practical recommendations
    - 3:37:05: Software citation

- output: day4-outro.mp4
  title: Day 4 final remarks - CodeRefinery May 2021
  description: >
    ...
  time:
    - 3:38:30, 3:39:42
```

## Day 5

All done!

* Intro
  * Presenter approved: no
* Jupyter
  * Presenter approved: pending
* Documentation
  * Presenter approved: YES

```yaml

- input: cr-2021may-day5-obs.mkv

- output: day5-intro.mp4
  title: Day 5 introduction - CodeRefinery May 2021
  description: >
    The quick introduction to Day 5.
  time:
    - 5:00, 6:10 # talking about icebreaker
    - 8:25, 9:05
    - 13:15, 20:50     #
    - 15:00: Jupyter getting started


- output: day5-jupyter.mp4
  title: Jupyter - CodeRefinery May 2021
  description: >
    The goal of this lesson is to teach learners the user interface of JupyterLab, how Jupyter notebooks work, and what some common and powerful usecases are. Our focus is to demonstrate and discuss and guide towards good practices for reproducibility, collaboration, and reusability. The emphasis of this lesson is to demonstrate how to use notebooks in combination with version control and how to share reproducible notebooks via Binder.

    This lesson demonstrates the use of JupyterLab, nbdime, jupyterlab-git, and Binder.

    https://coderefinery.github.io/jupyter/
  time:
    - cover: {begin: "41:29", end: "41:35", w: 840, h: 300, x: 360}
    - 20:50, 1:00:30   # episode, Exercise as a demo
    - 1:01:20, 1:18:24         # After exercise
    - 1:32:50, 1:49:50
                          # 1:15:45 Thor in video
    - 1:53:25, 1:55:20
    - 20:50: Motivation, pitfalls, best practices
    # 32:50 Sabry appears
    - 37:41: Interface
    # Diana name at 44:30
    - 42:10: "Exercise: Darts and the interface"
    - 50:00: "Demo: Darts exercise plus explanation"
    - 1:01:20: Post-exercise discussion
    - 1:11:20: Git and notebooks
    - 1:32:50: Binder and sharing notebooks

- output: day5-documentation.mp4
  title: Documentation - CodeRefinery May 2021
  description: >
    In this lesson we discuss different solutions for implementing and deploying code documentation. We start by creating a wishlist for how we would code documentation like to be. Then after a tour of available tools, we discuss how to write useful and accessible READMEs, and then we progress by demonstrating and practicing the Sphinx documentation generator and demonstrate how to deploy documentation to Read the Docs service.

    Topics and tools discussed: Markdown, reStructured text, README documentation, table of contents generation, Sphinx, Read the Docs, GitHub/GitLab pages.

    https://coderefinery.github.io/documentation/
  time:
    - 1:59:55, 2:26:25
    - 2:27:00, 2:40:05
    - 2:40:55, 2:44:00
    # 2:30:00 Stefan in video
    # 2:38:00 - 29:31 Johan in stream
    - 2:53:50, 3:21:15
    - 3:22:25, 3:45:00
    - 3:47:13, 4:02:54

    - 2:00:00: Intro
    - 2:01:00: Motivation
    - 2:14:20: Popular tools
    - 2:21:20: Readme files
    - 2:23:55: "Exercise: Readme files"
    - 2:53:50: Sphinx documentation
    - 2:57:30: Sphinx type-along
    - 3:19:40: Sphinx exercise
    - 3:22:25: Sphinx exercise demo
    - 3:36:45: What comes next
    - 3:39:00: ReadTheDocs summary
    - 3:40:50: Github Pages summary
    - 3:42:40: Summary, eend of day
    - 3:47:13: ReadTheDocs demo

```

## Day 6

Approvals for youtube:
* Intro
* Testing
  * Thor, Diana, Iusan
* Modular
  * Max, Radovan, Anne

```yaml=

- input: cr-2021may-day6-obs.mkv

- output: day6-intro.mp4
  title: Day 6 intro - CodeRefinery May 2021
  description: >
    The quick introduction to Day 6.
  time:
    - start: 15:47
    - end: 19:10

- output: day6-testing.mp4
  title: Software Testing - CodeRefinery May 2021
  description: >
    Software testing is a fundamental part of modern software development, and especially important for science since results should be correct.  Luckily, it's not so hard to get started, and anyone can do it. This is a crash course for scientists to get started testing their software.

    Tools covered include concepts of testing for science, unit testing, pytest, continuous integration, GitHub actions .  We make demos in Python, but have examples in other languages and this will apply to every language in some form.

    https://coderefinery.github.io/testing/

  time:
    - start: 19:10
    - 19:10: Intro
    - 22:05: Motivation
    - 32:20: Concepts
    - 41:10: Q&A
    - 45:00: "Exercise: testing locally"
    - cover: {begin: "45:48", end: "46:04", w: 840, h: 300, x: 360}
    - end: 47:27
    - start: 48:25
    - 48:25: Exercise as a demo
    - end: 54:00 # ???
    #- start: 1:03:00  # ???, Small discussion but said again once people are back
    #- end:
    - start: 1:06:50
    - 1:06:50: Q&A
    - 1:08:10: Automated testing with CI
    #- 1:11:25: CI step 1-2
    #- 1:29:50: Step 7: Fix the broken test
    #- 1:34:00 Step 8: Open a pull request
    - 1:36:30: Q&A, summary of automated testing
    - 1:37:55: Test design, exercise prepration
    - end: 1:43:00
    - start: 2:16:45
    - end: 2:17:08

- output: day6-modular-code-development.mp4
  title: Modular Code Development - CodeRefinery May 2021
  description: >
    In this live-coding demo session we take a Python script as starting point which reads data, computes simple statistics, and generates a plot. Together we then improve this code based on suggestions from the audience to arrive at a more reusable code with reusable components. We start in the Jupyter notebook, later move to a Python script/module, introduce testing, and finally introduce and motivate a command line interface to our code.

    In this demonstration we use JupyterLab, Python, Pandas,
    Matplotlib, pytest, and Click.  It is also a great demonstration
    of pair programming.

    https://coderefinery.github.io/modular-type-along/
  time:
    - start: 2:17:50
    - 2:17:50: Intro and questions to the audience
    - cover: {begin: "2:22:20", end: "2:22:26", w: 840, h: 100, x: 600}
    # Max at 2:26:30
    - 2:36:15: "Modular type-along"
    - 2:38:10: Starting with Jupyter
    - 2:44:00: Functions
    - end: 3:04:40
    - start: 3:10:50
    - 3:10:50: Some questions
    - 3:14:10: Moving out of the notebook
    - cover: {begin: "3:15:03", end: "3:15:09", w: 840, h: 165, x: 540}
    - 3:24:05: Adding a command line interface
    - 3:32:20: Wrap-up
    - end: 3:33:30e

- output: day6-outro.mp4
  title: Workshop outro - CodeRefinery May 2021
  description: >
      The concluding remarks of the workshop.
  time:
    - start: 3:35:10
    - end: 3:47:17

```
