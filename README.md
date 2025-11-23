# Portfolio 2025 -  AstroJS base  (v5.16.0)

My new website / portfolio, version 2025, using new technologies base on JavaScript / Nodejs, using Astrojs

[Hosted on Netlify](https://ampmonteiro-2025.netlify.app/)

## Goals

- Research on new tech

- refesh the portfolio

- Release this static website on netlify

- Avoid js on final result of project.

- take advantage of image optimization offered by the framework


## Tech

- JavaScript / TypeScript

- Vanilla CSS, like previous, taking advantage of flex and css grid

- AstroJS 

## 🚀 Project Structure

Inside of your Astro project, beside recommend folders, 

was added: json folder and assets folder:

```
/
├── public/
│   └── favicon.svg

├── src/
│   ├── assets/                # images, icons, fonts
│   ├── components/
│   │   ├── AboutCourseList.astro
│   │   ├── AboutInfo.astro
│   │   ├── AboutWorkList.astro
│   │   ├── Accordion.astro
│   │   ├── Card.astro
│   │   ├── Footer.astro
│   │   ├── Menu.astro
│   │   └── SkillTable.astro
│   │
│   ├── json/
│   │   ├── cert.json
│   │   ├── edu.json
│   │   ├── frameworks.json
│   │   ├── me.json
│   │   ├── pkgs.json
│   │   ├── software.json
│   │   ├── tech.json
│   │   └── work.json
│   │
│   ├── layouts/
│   │   ├── Layout.astro
│   │   └── MdProjectLayout.astro
│   │
│   ├── styles/                # Global CSS
│   │
│   └── pages/
│       ├── index.astro
│       ├── about-me.astro
│       ├── social.astro
│       ├── skills.astro
│       │
│       └── projects/
│           ├── index.astro
│           ├── [name-of-poject].md
│
└── package.json
```

##  Structure [name-of-poject].md

this file has the follow info that it is needed to be filled:

```
---
layout: ../../layouts/MdProjectLayout.astro
title: ''
image:
  url: '/src/assets/img/
see: 'https://'
order: 1
---

Description

**The goal of this projects is**: 



**Technologies**:


**Frameworks | Libraries | API**:


```

## images

- homepage

![Homepage](/md-images/homepage.png)


- about

![About](/md-images/about.png)

- Projects

![Projects](/md-images/projects.png)


- Skills

![Skills](/md-images/skills.png)

- Social

![Social](/md-images/social.png)


# Original instructions

### Astro Starter Kit: Basics

```
npm create astro@latest -- --template basics
```
> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![basics](https://user-images.githubusercontent.com/4677417/186188965-73453154-fdec-4d6b-9c34-cb35c248ae5b.png)


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm i`                | Installs dependencies                            |
| `npm start`            | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
