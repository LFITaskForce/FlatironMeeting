---
layout: default
title: Hackathon
order: 3
---

##### What to expect during the hack days ?
Rapid progress on proposed projects, bursts of ideas from interactions between
participants, and speed-learning via "breakout" tutorial sessions on specific topics spontaneously put together by participants.

Here is the timeline for a standard hack day:
 - 8:30am, *Breakfast*
 - 9:30am, **Morning Tag Up**: Hack projects are briefly introduced, if you propose a hack, it's the opportunity to explain what your goals are and what kind of help you are looking for. After announcement, teams assemble and hacking begins!
 - 10:30am, *Coffee*
 - 12:30pm, *Lunch Break*
 - 1:30pm, **Afternoon announcements and breakout sessions**: Groups are given the opportunity to make announcements/request help if they are stuck/ask for a tutorial breakout session. Soon after, breakout sessions begin.
 - 3pm, *Coffee*
 - 5pm, **Evening wrap up**: Each groups report on the progress of the day, with some ***tangible results*** (e.g. a plot, pull request, or just of drawing of a schema). Second opportunity to ask for help/expertise/specific breakout session for the next day
 - 5:30pm, day is over but participants are
  welcome to continue their hacks.

For more details about food and coffee, please have a look at the [Logistics]({{"/logistics" | relative_url }}) page, and for a detailed schedule for each day, please  check the [Schedule]({{"/schedule" | relative_url }}) page.

##### How to edit this page ?
We strongly encourage participants to make use of this page to register themselves
and their hack ideas, this will help ensure a successful hackathon. **To edit this
page, click the button below**, edit the markdown file on the GitHub website,
and commit your changes in a new Pull Request.
<p align="center">
<a href="https://github.com/LFITaskForce/FlatironMeeting/edit/master/docs/hackathon.md" class="btn btn-info">Edit this page on GitHub</a> </p>

 Should you have any questions, don't hesitate to ask on Gitter or
directly one of the organizers.

## Proposed projects

In order to track the proposed projects, we are using [GitHub issues in the meeting repository](https://github.com/LFITaskForce/FlatironMeeting/issues?q=is%3Aissue+is%3Aopen+label%3A%22hack+project%22) and we
maintain a summary table below for convenience.

 We encourage participants to:
 - Have a look at the list, see if you might be interested in any project
 - Contact through the GitHub issue the people involved in the projects you are interested in. Help them refine the project ahead of time.
 - Come up with new project ideas, and don't hesitate to reach out to fellow hackers based on their listed interests and skills.


To **add a new project**, start by clicking the button below and filling out the hack template:

<p align="center">
<a href="https://github.com/LFITaskForce/FlatironMeeting/issues/new?assignees=&labels=help+wanted%2C+hack+project&template=new-hack.md&title=%5BHACK%5D+your+hack+title+" class="btn btn-info">Propose a new hack </a></p>

Once you have created a new hack issue, be sure to list in the table below.

| Project title | Suggested by | Looking for ? | Likely Participants | Day/Days |
|---------------|--------------|---------------|---------------------|----------|
| [Likelihood-Free Inference Toolbox](https://github.com/LFITaskForce/FlatironMeeting/issues/10) | @EiffL | People with experience in (and strong feelings about ;-) ) open source software, probabilistic programming language, and practical LFI |                     | W-F      |
| [NDEs for discrete (count) data](https://github.com/LFITaskForce/FlatironMeeting/issues/14) | @junstinalsing | People with background knowledge of conditional density estimation + general enthusiasm! | | W-F |
| [Living review for likelihood-free inference](https://github.com/LFITaskForce/FlatironMeeting/issues/15) | @justinalsing | People with knowledge of some corner(s) of the LFI method space, and/or the practicalities of implementation in different scenarios. Energy for writing. |   | W-F |
| [Bayesian optimization for delfi](https://github.com/LFITaskForce/FlatironMeeting/issues/16) | @justinalsing | People with Bayesian optimization knowhow |   | W-F |
| [ELFI](https://github.com/LFITaskForce/FlatironMeeting/issues/20) | @hpesonen | People wanting to contribute to ELFI | | W-F


## Breakout tutorial sessions

At various times during the hackdays, impromptu (or at most, minimally planned for) "breakout" sessions will be announced. Breakouts will typically be ~30-45 mins in length, open to (and advertised to) the whole group but only attended by some fraction of the group. The goal of breakout sessions is to bring groups of people up to speed quickly on various specialized topics through active participation and discussion. Generally these sessions are not research talks, but rather tutorials given by one of the members of the group who has expertise that others can benefit from: a breakout is a very efficient way to learn from your peers.

Feel free to propose, or ask for sessions on particular topics in the table below.

| Breakout Topic | Leader(s) | Suggested by | Interested in attending | When and Where   |
|----------------|-----------|--------------|-------------------------|------------------|
| GitHub Primer  |  @EiffL   | @EiffL       |                         | Wed 1:30, in TBD |
| Pyro (or pyprob) crash course |           | @johannbrehmer | @johannbrehmer, @EiffL, @MilesCranmer, @Linc-tw  | |
| BOLFI |           | @changhoonhahn | @changhoonhahn | | 
| pydelfi tutorial |           | @changhoonhahn | @changhoonhahn, @johannbrehmer | | 
| summary of available software packages |           | @dfm | @dfm, @johannbrehmer | | 



## Hackers

Use the following table to register your interests as well as your skills and
any resources you might have that may be of interests to other participants
(e.g. a dataset, a simulator, a density estimator code).


| Name     |   Interests |  Skills/Resources | GitHub/Gitter Handle |
|----------|-------------|-----------|------------------|---------------|
| Francois | LFI for Cosmology and beyond | Python,TensorFlow, Deep Learning, Weak Lensing | @EiffL |
| Johann   | LFI with more data from simulationis, particle physics, non-physics applications | Python, PyTorch, particle physics | @johannbrehmer |
| Jan-Matthis | LFI, computational neuroscience | Python, PyTorch, TensorFlow, neuroscience | @jan-matthis |
| Danley | LFI, computational astrophysics, astrostatistics, exoplanets | Python, Julia, Approximate Bayesian Computation code (Julia), astronomy, physics | @dch216 |
| Chang | LFI for Cosmology and Galaxy Evolution | Python, ABC, Galaxy Clustering, Galaxy Evolution | @changhoonhahn |
| Justin | LFI, cosmology, epidemiology, climate | pydelfi, python, tensorflow, deep learning, astrostats | @justinalsing |
| Pablo (remote) | LFI, LHC analyses, non-physics applications | Python, TensorFlow, Probablistic Programming, Particle Physics | @pablodecm |
| Tom | LFI for cosmology and novel statistical neural network method building | TensorFlow, Python, Julia, machine learning, ABC, PMC | @tomcharnock |
| Miles | Interpreting deep NNs, neural density estimation, dark matter, exoplanets, stellar dynamics | distributed training in PyTorch, Graph nets, Variational NNs  | @MilesCranmer |



