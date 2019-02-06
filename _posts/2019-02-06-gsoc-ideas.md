---
layout: post
title: Ideas list for GSoC 2019
tagline: Fragments.
visible: 1
category: blog
tags: [intro]
---

## About MDG

Mobile Development Group, IIT Roorkee, founded in 2010, is an active student group directing its efforts towards creating useful mobile applications and promoting tech-based learning for the same. We have people who are in various fields related to tech (primarily related to computer science and tech). These fields include Android/iOS/cross-platform App Development, Web Development, Machine Learning and Artificial Intelligence, we also have people who are into Computer Systems and Security.

## How to start
There are many open source projects in our GitHub organisation (http://github.com/mdg-iitr/), anyone can start contributing by solving current issues or by working on the ideas in the Project Section.
- First, introduce yourself at our [chat](http://mdg.iitr.ac.in/chat).
- Do not start working on any issues anonymously, always ask before starting, through our chat/ email.
- our chat/ email (mdg@iitr.ac.in).

## Our Projects

### MusicDNA
MusicDNA is a full featured Music Player that combines the usefulness of a clean traditional music player with ···amazing visualizations or DNAs generated based on the currently playing music. The Player allows users to play both local music as well as Stream Music directly from SoundCloud. The Player also packs a Powerful Equalizer with BassBoost and Reverb effects.
<b>Github</b>
https://github.com/mdg-iitr/MusicDNA
#### Ideas:
- Add support for online music streaming from many free music sites, for example ReverbNation, SoundCloud, NoiseTrade, etc. This is one of the awesome feature demanded by users.
- Support for multiple languages.
- Instead of a single DNA image of song, generate a video for more visual appeal.
- There are many more small features request which can be found [here](https://github.com/harjot-oberai/MusicDNA/issues).

### EmojiReactionView
An Android library to make Emoji Reactions on ImageViews ( without changing/modifying the image ) in a manner Instagram does in Instagram stories. Users can customize the look to a great extent easily and reliably. This library can be easily used in recycler view. For further details visit this GitHub repo.
<b>Github</b>
https://github.com/mdg-iitr/EmojiReactionView
#### Ideas:
- Better implementation so that it works more effectively in Recycler views.
- Adding more animations.
- Using cubic bezier instead of arc for the panel.

### Rotating Text
Rotating text is an Android library that can be used to make text switching painless and beautiful, with the use of interpolators, typefaces and more customisations.
<b>Github</b>
https://github.com/mdg-iitr/RotatingText
#### Ideas:
- Adding more control over the rotatable.
- Adding curve rotation animation.
- Improving performance.

### VectorMaster
This library introduces dynamic control over vector drawables. Each and every aspect of a vector drawable can be controlled dynamically (via Java instances), using this library.
<b>Github</b>
https://github.com/mdg-iitr/VectorMaster
#### Ideas:
- Adding functionality to dynamically add groups, paths etc. to the Vector.
- Implementing another scale method which takes pivot points as arguments along with the scale factor.
- Support for dynamically changing the vector source.

### Graph Kit
This library allows you to plot different kinds of graphs from data points. The currently supported graphs are Line Graph, Bar Graph and Pie Chart. This library also includes an EditGraphView which you can edit by dragging points and also get normalized points from the curve. To know more, visit our GitHub repo
<b>Github</b>
https://github.com/mdg-iitr/Graph-Kit
#### Ideas:
- Line graph can be plotted for all 4 quadrants.
- Zoom-in and zoom-out features can be added to graphs.
- Number of curves can be plotted in a single line graph to compare between the plots or to find the intersections.
- The Graphs can be made to plot in real-time.
- Snapping feature can be added in EditGraphView.
- Undo and Redo feature can be added in Edit graph.
- Polar Coordinate system can be added.
- Graphs can be plotted from functions and their roots, stationary points, integrals, etc. can be obtained from the graphs.
- A database can be integrated to store the graphs locally in the app.

### Animated Text Kit
Animated Text Kit is a Flutter package that contains a collection of some cool and awesome text animations for the developers to incorporate animated texts almost seamlessly and effortlessly in their apps. To know more, visit our GitHub repo.
<b>Github</b>
https://github.com/mdg-iitr/Animated-Text-Kit
#### Ideas:
- Add some more animated texts in the library.
- Provide the ability to randomize the "text".
- Accept List of Widgets instead of List of String for more flexibility.
- Implement AutoSizeText.
- Prevent creation of so many widgets and animation variables. {optimization}

### Attachable-floating-menu
AttachableFloatingMenu (AFM) is an Android Library written in Kotlin that provides you with a Floating Action Button (FAB)which when triggered opens up a Menu. The menu itself comprises of other FABs. The AFM attaches itself to an Android View and only appears when that View is long pressed. The AFM renders more FABs around itself in a circular fashion. The user then slides the finger near the desired FAB to select that option. It is majorly inspired by Pinterest’s menu. To know more, visit our GitHub repo.
<b>Github</b>
https://github.com/mdg-iitr/attachable-floating-menu
#### Ideas:
- Make AFM compatible with a recycler view. Currently, when AFM is triggered, then any attempt to move the finger across the screen triggers scrolling in the recycler view in the background.
- Handle boundary cases when rendering AFM. For example, the Menu should not go out of the screen when triggered near edges or corners.
- Think of more types of animations [(see this for examples)](https://github.com/rjsvieira/floatingMenu?utm_source=android-arsenal.com&utm_medium=referral&utm_campaign=5697) and implement them.

## Splitter
It is a simple mobile platform (currently only Android) 2D game, where aim is to just avoid the spikes and climb higher to reach out of tunnel. 
<b>Github</b>
https://github.com/mdg-iitr/Splitter
#### Ideas:
- Adding more levels with increasing difficulty.
- Add more costume as demanded by users.
- Creating virtual accessories like speed boost, obstacle-destructor,  Coins, etc.
- New theme design with dark colours.   