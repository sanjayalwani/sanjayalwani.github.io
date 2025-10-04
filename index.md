---
layout: page
title: Welcome
---

I am a generalist software developer with experience in *Full Stack* Development.

That experiences spans:
- Compiler development in Clojure.
- Web application feature development in React, Node.js and Postgres.
- Embedded device testing using a proprietary framework in Python, orchestrated with Jenkins.
- Warehouse storage optimization with Python using Pandas, Numpy and OR-Tools.

## Projects

### mySoundJourney

A React Single Page Application I made to visualize the numbers behind the music I listen to on Spotify, for use by anyone with an account.

![Picture of mysoundjourney]({{ site.baseurl }}public/img/mysoundjourney.png "Picture of mySoundJourney")

You can look at the energy, positivity and danceability of recently listened to music or your playlists. My design focuses on privacy first, which was enabled by using React and a client-side OAuth authentication flow that only communicates between your browser and Spotify's servers.

Check out the [<i class="fa fa-fw fa-github"></i>source code](https://github.com/sanjayalwani/mySoundJourney).

### NonoGame

A [nonogram](https://wikipedia.org/wiki/Nonogram) game built with plain old javascript.

[Play now]({{ site.baseurl }}nonogame/game.html)

![Picture of NonoGame]({{ site.baseurl }}public/img/nonogame.png "Picture of NonoGame")

[<i class="fa fa-fw fa-github"></i>source code](https://github.com/sanjayalwani/nonogame)

### Pedestrian crossing simulator

A cellular automata simulation model for a pedestrian crossing at a two lane road, written in MATLAB.

![Animation of Pedestrian crossing simulator]({{ site.baseurl }}public/img/ped_crossing.gif "Animation of Pedestrian crossing simulator")

This model was used to run multiple experiments, to investigate the effect of various parameters on pedestrian and vehicle wait times and other metrics.

Below you can see how changes to the Vehicle Arrival Period (VAP), Pedestrian Arrival Period (PAP) and Pedestrian Waiting Time (PWT), all measured in seconds, affect the percentage of stagnant vehicles in the road.

![Graph from Pedestrian crossing simulation]({{ site.baseurl }}public/img/ped_crossing_graph.png "Graph of average vehicle stagnation ratio under different arrival rates in Pedestrian crossing simulator")

[<i class="fa fa-fw fa-github"></i>source code](https://github.com/sanjayalwani/pedcrossingsim)

### CLI Wordle

Wordle in your CLI, written in C++.

Source code and execution instructions are in [<i class="fa fa-fw fa-github"></i>this repository](https://github.com/sanjayalwani/cli_wordle).

![CLI Wordle Picture]({{ site.baseurl }}public/img/cli_wordle.png "Picture of the game running in terminal")


### This website

Forked from the [<i class="fa fa-fw fa-github"></i>Hyde theme](https://github.com/poole/hyde) for Jekyll, and updated to be compatible with Ruby 3.

Hosted with GitHub Pages.
