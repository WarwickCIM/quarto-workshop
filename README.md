# Workshop "Quarto: A library to run them all?"
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-12-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Materials for the [RSE Conf 2022](https://rsecon2022.society-rse.org/) workshop: _"Quarto: a Library to run them all?"_, led by Carlos Cámara-Menoyo, James Tripp and Cagatay Turkay.


## Overview

Using literate programming is a widespread practice amongst data scientists. Chances are that you may have come across, or even used, one of the two more mature projects, Rmarkdown or jupyter notebooks, to present results, do exploratory analysis, author academic articles or complete books or even perform complete analyses. While both solutions can be used with multiple programming languages, the decision of whether to use one or the other is almost certain to be exclusively based on that: the vast majority of R users will opt for Rmarkdown while python users will favour jupyter notebooks.  At least until now, with Quarto being mature enough to become a game-changer.
Quarto is a language-agnostic software that it's based on pandoc to render files combining markdown and code into multiple ranges of formats and outputs. This means it can be used with either R, Phython, Julia or Observable without any other dependencies.
This collaborative workshop will be organised around 3 stages: 

1. a brief theoretical introduction and instructions; 
2. a task that participants may chose from the different use cases provided (i.e. generating a single document, migrating from Rmarkdown or jupyter, creating a book or generating interactive content); and 
3. discussion and conclusions.

Participants in this workshop will have enough depth of breath and practice to evaluate how feasible is to use Quarto in different scenarios and, ultimately, if it can become the one-tool for reproducible scientific publishing, regardless of your language of choice. 


## Pre-requisites

In order to take part in this workshop you will need to have the following software in your laptop:

1. Quarto installed (see [instructions here](https://quarto.org/docs/get-started/))
2. Git
3. Editor of your choice, preferably RStudio and/or Visual Studio Code (or its FLOSS version, VSCodium)


All the software used in this workshop is available for GNU/Linux, Windows and MacOS.

## Installation instructions

1. Clone repo: `git clone git@github.com:WarwickCIM/quarto-workshop.git`
2. Install quarto's binaries: https://quarto.org/docs/get-started/
3. Recreate virtual environment (not implemented yet)

## File structure

To be done later.

```
slides/       <-- Slides for the workshop.
cases/        <-- Quarto use cases, each case in a folder.
|-- <case_n>  <-- Each case should reside in a folder.
|-- template  <-- Template for documenting the process.

```

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="http://carloscamara.es/en"><img src="https://avatars.githubusercontent.com/u/706549?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Carlos Cámara</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=ccamara" title="Code">💻</a> <a href="#ideas-ccamara" title="Ideas, Planning, & Feedback">🤔</a> <a href="#talk-ccamara" title="Talks">📢</a> <a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=ccamara" title="Documentation">📖</a></td>
      <td align="center"><a href="https://warwick.ac.uk/fac/cross_fac/cim/people/cagatay-turkay"><img src="https://avatars.githubusercontent.com/u/4129319?v=4?s=100" width="100px;" alt=""/><br /><sub><b>cagatayTurkay</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=cagatayTurkay" title="Code">💻</a> <a href="#ideas-cagatayTurkay" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center"><a href="https://github.com/brian-maher"><img src="https://avatars.githubusercontent.com/u/6905100?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Brian Maher</b></sub></a><br /><a href="#mentoring-brian-maher" title="Mentoring">🧑‍🏫</a></td>
      <td align="center"><a href="https://warwick.ac.uk/fac/arts/research/digitalhumanities/team/"><img src="https://avatars.githubusercontent.com/u/5781056?v=4?s=100" width="100px;" alt=""/><br /><sub><b>James Tripp</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=jamestripp" title="Code">💻</a> <a href="#ideas-jamestripp" title="Ideas, Planning, & Feedback">🤔</a> <a href="#talk-jamestripp" title="Talks">📢</a></td>
      <td align="center"><a href="https://github.com/eirini-zormpa"><img src="https://avatars.githubusercontent.com/u/30151074?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Eirini Zormpa</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=eirini-zormpa" title="Code">💻</a></td>
      <td align="center"><a href="https://www.heatherturner.net/"><img src="https://avatars.githubusercontent.com/u/3343008?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Heather Turner</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=hturner" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/alessandrofelder"><img src="https://avatars.githubusercontent.com/u/10500965?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alessandro Felder</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=alessandrofelder" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/CamillaBressan"><img src="https://avatars.githubusercontent.com/u/18901431?v=4?s=100" width="100px;" alt=""/><br /><sub><b>CBress</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=CamillaBressan" title="Code">💻</a></td>
      <td align="center"><a href="https://vbn.aau.dk/en/persons/104579"><img src="https://avatars.githubusercontent.com/u/971307?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Thomas Arildsen</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=ThomasA" title="Code">💻</a></td>
      <td align="center"><a href="https://paddyroddy.github.io/"><img src="https://avatars.githubusercontent.com/u/15052188?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Patrick Roddy</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=paddyroddy" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/ItIsJordan"><img src="https://avatars.githubusercontent.com/u/21129425?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jordan Byers</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=ItIsJordan" title="Code">💻</a></td>
      <td align="center"><a href="https://iaanimashaun.herokuapp.com"><img src="https://avatars.githubusercontent.com/u/62275818?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ibrahim Animashaun</b></sub></a><br /><a href="https://github.com/WarwickCIM/quarto-workshop/commits?author=iaanimashaun" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

It is a collaborative project, this means that: A) Contributions of any kind are welcome!; and B) following the [all-contributors specification](https://allcontributors.org/) and being grateful is a requirement.

If you believe you must be credited, please do it in [this issue](https://github.com/WarwickCIM/quarto-workshop/issues/1).

## Attendees

Please, introduce yourselves in [this issue](https://github.com/WarwickCIM/quarto-workshop/issues/17)
