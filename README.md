<p align="center">
  <img src="https://raspi.website/img/raspi/lg.webp" width="555">
 
  <p align="center">
    <img src="https://github.com/raspberry-pi-org/raspberry-pi-org.github.io/workflows/tests/badge.svg"></img>
    <img src="https://img.shields.io/github/commit-activity/m/raspberry-pi-org/raspberry-pi-org.github.io?color=ff69b4"></img>
    <img src="https://img.shields.io/github/repo-size/raspberry-pi-org/raspberry-pi-org.github.io"></img>
    <img src="https://img.shields.io/github/license/raspberry-pi-org/raspberry-pi-org.github.io.svg"></img>
  </p>
</p>


# Intro
✨ Display all project informations of [`Raspberry Pi Organization`](https://github.com/raspberry-pi-org) by the stunning presentation on the web created by [`reveal.js`](https://revealjs.com/)


# How to run
## Full Setup - Recommended
Some reveal.js features, like external Markdown, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](https://nodejs.org/en/) (10.0.0 or later)
2. Clone this repository
```shell
$ git clone https://github.com/raspberry-pi-org/raspberry-pi-org.github.io.git
```
3. Move to the project.golanger.org folder and install dependencies
```shell
$ cd raspberry-pi-org.github.io && npm install
```
4. Serve the presentation and monitor source files for changes
```shell
$ npm start
```
5. Open http://localhost:8000 to view your presentation

### Development Server Port
The development server defaults to port 8000. You can use the the port argument to switch to a different one :
```shell
npm start -- --port=8001
```

> For more informations please refer to : *https://revealjs.com/installation/*


# Thanks
<p align="left">
  <a href="https://revealjs.com">
  <img src="https://hakim-static.s3.amazonaws.com/reveal-js/logo/v1/reveal-black-text.svg" alt="reveal.js" width="150">
  </a>
  <br><br>
  <a href="https://github.com/hakimel/reveal.js/actions"><img src="https://github.com/hakimel/reveal.js/workflows/tests/badge.svg"></a>
  <a href="https://slides.com/"><img src="https://s3.amazonaws.com/static.slid.es/images/slides-github-banner-320x40.png?1" alt="Slides" width="160" height="20"></a>
</p>

reveal.js is an open source HTML presentation framework. It enables anyone with a web browser to create fully featured and beautiful presentations for free. [Check out the live demo](https://revealjs.com/).

The framework comes with a broad range of features including [nested slides](https://revealjs.com/vertical-slides/), [Markdown support](https://revealjs.com/markdown/), [Auto-Animate](https://revealjs.com/auto-animate/), [PDF export](https://revealjs.com/pdf-export/), [speaker notes](https://revealjs.com/speaker-view/), [LaTeX support](https://revealjs.com/math/), [syntax highlighted code](https://revealjs.com/code/) and much more.

### Documentation
The full reveal.js documentation is available at [revealjs.com](https://revealjs.com).
