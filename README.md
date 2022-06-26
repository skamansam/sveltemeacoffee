# sveltemeacoffee
Fully Configurable Buy Me A Coffee button in svelte

## Why does this exist?

When trying to use the [Buy Me A Coffee](https://www.buymeacoffee.com/) button, I noticed there are a few things wrong with the buttons you can create:

1. There are only a handful of colored images to choose from.
1. If you try to use a custom color or text, you can't get an image link for that custom value.
1. If you try to use the script code they give you, it fails in Svelte/Kit (and maybe Nuxt, etc, as well)with the following error:

  >  Failed to execute 'write' on 'Document': It isn't possible to write into a document from an asynchronously-loaded external script unless it is explicitly opened. 

## Options:
There are SVG images in the BMAC creator kit, so I used those to create a SVG image of the button and used the svg `transform="scale()"` for scaling.

<dl>
<dt></dt>
<dd></dd>
</dl>

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
</p>
   
<h4>
    <a href="https://github.com/skamansam/sveltemeacoffee/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/skamansam/sveltemeacoffee">Documentation</a>
  <span> · </span>
    <a href="https://github.com/skamansam/sveltemeacoffee/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/skamansam/sveltemeacoffee/issues/">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Screenshots](#camera-screenshots)
  * [Tech Stack](#space_invader-tech-stack)
  * [Features](#dart-features)
  * [Color Reference](#art-color-reference)
  * [Environment Variables](#key-environment-variables)
- [Getting Started](#toolbox-getting-started)
  * [Prerequisites](#bangbang-prerequisites)
  * [Installation](#gear-installation)
  * [Running Tests](#test_tube-running-tests)
  * [Run Locally](#running-run-locally)
  * [Deployment](#triangular_flag_on_post-deployment)
- [Usage](#eyes-usage)
- [Roadmap](#compass-roadmap)
- [Contributing](#wave-contributing)
  * [Code of Conduct](#scroll-code-of-conduct)
- [FAQ](#grey_question-faq)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)

  

<!-- About the Project -->
## :star2: About the Project


<!-- Screenshots -->
### :camera: Screenshots

<div align="center"> 
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div>


<!-- TechStack -->
### :space_invader: Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
    <li><a href="https://nextjs.org/">Next.js</a></li>
    <li><a href="https://reactjs.org/">React.js</a></li>
    <li><a href="https://tailwindcss.com/">TailwindCSS</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
    <li><a href="https://expressjs.com/">Express.js</a></li>
    <li><a href="https://go.dev/">Golang</a></li>
    <li><a href="https://nestjs.com/">Nest.js</a></li>
    <li><a href="https://socket.io/">SocketIO</a></li>
    <li><a href="https://www.prisma.io/">Prisma</a></li>    
    <li><a href="https://www.apollographql.com/">Apollo</a></li>
    <li><a href="https://graphql.org/">GraphQL</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mysql.com/">MySQL</a></li>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
    <li><a href="https://redis.io/">Redis</a></li>
    <li><a href="https://neo4j.com/">Neo4j</a></li>
    <li><a href="https://www.mongodb.com/">MongoDB</a></li>
  </ul>
</details>

<details>
<summary>DevOps</summary>
  <ul>
    <li><a href="https://www.docker.com/">Docker</a></li>
    <li><a href="https://www.jenkins.io/">Jenkins</a></li>
    <li><a href="https://circleci.com/">CircleCLI</a></li>
  </ul>
</details>

<!-- Features -->
### :dart: Features

- Feature 1
- Feature 2
- Feature 3

<!-- Color Reference -->
### :art: Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Primary Color | ![#222831](https://via.placeholder.com/10/222831?text=+) #222831 |
| Secondary Color | ![#393E46](https://via.placeholder.com/10/393E46?text=+) #393E46 |
| Accent Color | ![#00ADB5](https://via.placeholder.com/10/00ADB5?text=+) #00ADB5 |
| Text Color | ![#EEEEEE](https://via.placeholder.com/10/EEEEEE?text=+) #EEEEEE |


<!-- Env Variables -->
### :key: Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`ANOTHER_API_KEY`

<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

This project uses Yarn as package manager

```bash
 npm install --global yarn
```

<!-- Installation -->
### :gear: Installation

Install my-project with npm

```bash
  yarn install my-project
  cd my-project
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
import Component from 'my-project'

function App() {
  return <Component />
}
```

<!-- Roadmap -->
## :compass: Roadmap

* [x] Todo 1
* [ ] Todo 2


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

- Question 1

  + Answer 1

- Question 2

  + Answer 2


<!-- License -->
## :warning: License

Distributed under the no License. See LICENSE.txt for more information.


<!-- Contact -->
## :handshake: Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/skamansam/sveltemeacoffee](https://github.com/skamansam/sveltemeacoffee)


<!-- Acknowledgments -->
## :gem: Acknowledgements

Use this section to mention useful resources and libraries that you have used in your projects.

 - [Shields.io](https://shields.io/)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#travel--places)
 - [Readme Template](https://github.com/othneildrew/Best-README-Template)