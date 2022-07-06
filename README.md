# sveltemeacoffee
Fully Configurable Buy Me A Coffee button in svelte


## Options:
There are SVG images in the BMAC creator kit, so I used those to create a SVG image of the button and used the svg `transform="scale()"` for scaling.


### Defaults:

<div align="center">
<a href="https://www.buymeacoffee.com/skamansamV" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
  <h1>Svelte Me A Coffee</h1>
  
  <p>
    A Svelte SVG component for a buymeacoffee.com button. 
  </p>
  
  
<!-- Badges -->
<p>
  <a href="https://github.com/skamansam/sveltemeacoffee/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/skamansam/sveltemeacoffee" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/skamansam/sveltemeacoffee" alt="last update" />
  </a>
  <a href="https://github.com/skamansam/sveltemeacoffee/network/members">
    <img src="https://img.shields.io/github/forks/skamansam/sveltemeacoffee" alt="forks" />
  </a>
  <a href="https://github.com/skamansam/sveltemeacoffee/stargazers">
    <img src="https://img.shields.io/github/stars/skamansam/sveltemeacoffee" alt="stars" />
  </a>
  <a href="https://github.com/skamansam/sveltemeacoffee/issues/">
    <img src="https://img.shields.io/github/issues/skamansam/sveltemeacoffee" alt="open issues" />
  </a>
  <a href="https://github.com/skamansam/sveltemeacoffee/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/skamansam/sveltemeacoffee.svg" alt="license" />
  </a>
<a href="https://github.com/skamansam/sveltemeacoffee/blob/master/LICENSE">
    <img src="https://img.shields.io/website?url=https%3A%2F%2F" alt="license" />
  </a></p>
   
<h4>
    <a href="https://github.com/skamansam/sveltemeacoffee/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/skamansam/sveltemeacoffee">Documentation</a>
  <span> · </span>
    <a href="https://github.com/skamansam/sveltemeacoffee/issues/new?template=bug_report.md">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/skamansam/sveltemeacoffee/issues/new?template=feature_request.md">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [sveltemeacoffee](#sveltemeacoffee)
  - [Options:](#options)
    - [Defaults:](#defaults)
- [:notebook_with_decorative_cover: Table of Contents](#notebook_with_decorative_cover-table-of-contents)
  - [:star2: About the Project](#star2-about-the-project)
    - [:camera: Screenshots](#camera-screenshots)
    - [:space_invader: Tech Stack](#space_invader-tech-stack)
    - [:dart: Features](#dart-features)
  - [:toolbox: Getting Started](#toolbox-getting-started)
    - [:bangbang: Prerequisites](#bangbang-prerequisites)
    - [:gear: Installation](#gear-installation)
      - [with pnpm or yarn](#with-pnpm-or-yarn)
      - [with npm](#with-npm)
    - [:test_tube: Running Tests](#test_tube-running-tests)
    - [:running: Run Locally](#running-run-locally)
    - [:triangular_flag_on_post: Deployment](#triangular_flag_on_post-deployment)
  - [:eyes: Usage](#eyes-usage)
  - [:compass: Roadmap](#compass-roadmap)
  - [:wave: Contributing](#wave-contributing)
    - [:scroll: Code of Conduct](#scroll-code-of-conduct)
  - [:grey_question: FAQ](#grey_question-faq)
  - [:warning: License](#warning-license)
  - [:handshake: Contact](#handshake-contact)
  - [:gem: Acknowledgements](#gem-acknowledgements)

  

<!-- About the Project -->
## :star2: About the Project


<!-- Screenshots -->
### :camera: Screenshots

> As soon as I get a demo page up and running, I will add a screenshot.

<div align="center"> 
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div>


<!-- TechStack -->
### :space_invader: Tech Stack

<ul>
  <li><a href="https://svelte.org/">Svelte</a></li>
  <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
</ul>


<!-- Features -->
### :dart: Features

- SVG Output
- Configure Color for:
  - background
  - text
  - coffee cup
  - coffee
- Configure text
- Use any font from https://fonts.google.com (and any variant)
- adjust size, as a multiplicitave (sorry, not adjustable for exact pixel size yet)
- adjust width, to accomodate longer text (sorry, no automatic width yet)


<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

This project uses pnpm as package manager, but any node package manager will do.

```bash
 npm install --global pnpm
```

<!-- Installation -->
### :gear: Installation

#### with pnpm or yarn

```bash
  pnpm add sveltemeacoffee
```

<div style="text-align: center">OR</div>

```bash
  yarn add sveltemeacoffee
```
#### with npm

```bash
  npm install sveltemeacoffee
```   
<!-- Running Tests -->
### :test_tube: Running Tests

To run tests, run the following command

```bash
  yarn test test
```

<!-- Run Locally -->
### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/skamansam/sveltemeacoffee.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  yarn install
```

Start the server

```bash
  yarn start
```


<!-- Deployment -->
### :triangular_flag_on_post: Deployment

To deploy this project run

```bash
  yarn deploy
```


<!-- Usage -->
## :eyes: Usage

Use this space to tell a little more about your project and how it can be used. Show additional screenshots, code samples, demos or link to other resources.


```javascript
<script>
import BuyMeACoffee from 'sveltemeacoffee';
</script>

<BuyMeACoffee/>
```

<!-- Roadmap -->
## :compass: Roadmap

* [x] Initial Release
* [ ] Add size adjustment in pixels
* [ ] [Add automatic width adjustment to accommodate text](https://stackoverflow.com/questions/118241/calculate-text-width-with-javascript)
* [ ] Optional output in HTML/CSS instead of SVG.
* [ ] Create a customElement for use anywhere

<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/skamansam/sveltemeacoffee/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=skamansam/sveltemeacoffee" />
</a>


Contributions are always welcome!

See `contributing.md` for ways to get started.


<!-- Code of Conduct -->
### :scroll: Code of Conduct

Please read the [Code of Conduct](https://github.com/skamansam/sveltemeacoffee/blob/master/CODE_OF_CONDUCT.md)

<!-- FAQ -->
## :grey_question: FAQ

- Can you implement feature X,Y, or Z?

  + If you create a feature request, I will be happy to see if it is within the scope of this project. TBH, this is just a kind of one-off project I created to get a button in my blog, but I will try to respond within a reasonable amount of time. If, however, you would like to get your hands wet and fix something or add a feature, feel free to fork this repo and submit a pull request.

-  Why does this exist?

  + When trying to use the [Buy Me A Coffee](https://www.buymeacoffee.com/) button, I noticed there are a few things wrong with the buttons you can create:

     1. There are only a handful of colored images to choose from.
     2. If you try to use a custom color or text, you can't get an image link for that custom value.
     3. If you try to use the script code they give you, it fails in Svelte/Kit (and maybe Nuxt, etc, as well) with the following error:

        >  Failed to execute 'write' on 'Document': It isn't possible to write into a document from an asynchronously-loaded external script unless it is explicitly opened.

<!-- License -->
## :warning: License

Distributed under the Unlicense. See LICENSE.txt for more information.


<!-- Contact -->
## :handshake: Contact

Your Name - [@skamansam](https://twitter.com/skamansam) - skamansam@gmail.com

Project Link: [https://github.com/skamansam/sveltemeacoffee](https://github.com/skamansam/sveltemeacoffee)


<!-- Acknowledgments -->
## :gem: Acknowledgements

I would like to say, "Thank You" to all the amazing developers who have chosen to share their talents with the world! A special shout-out goes to the following:

 - [Shields.io](https://shields.io/)
   - for making a great API for created badges for READMEs
 - [Readme Template](https://github.com/othneildrew/Best-README-Template)
   - For creating the template I used for this README
 - [@svelte-web-fonts/google](https://github.com/svelte-web-fonts/google)
   - For creating the only 3rd party library used in this project
