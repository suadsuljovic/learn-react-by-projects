# How to build React.js projects step by step

## Intro

**If it's your first time reading this. Read this to understand the thought process and the reason for writing this guide.**

Building a React app is more than using Create React App scripts to make your project and hack away coding.

You will need to think about many other things:

- What is my goal in doing this project
- How many people are going to work on this project
- How will I use versioning software
- What project structure should I use
- How will I write my CSS
- Do I need to set some naming conventions on files and coding
- Should I use Prettier or Eslint or both to manage my code formatting
- Should I use third-party component library

Depending on how you answer the question above the way and stuff you need to do will differ.

For example: If are the only one working on this project you will not care about any collaboration tools or formatting and naming guidelines. Even though this is fine on its own you should think about whether will this make you a better programmer. In the majority of cases, it will not.

The things mentioned above are not the only things that you should think about. These are only some of the things that experienced programmers think about on daily bases when starting a new project.

**So the main purpose of this document is to define important steps that you should think about when building react projects.**

**The second purpose is to identify the steps you are not familiar with and learn why are they important.**

**The third one is to also identify ways for yourself to become a better programmer.**

## Pick your poison

Depending on how difficult you want the project to be there are the following difficulty levels.

1. **I want to get it over with!** <br>
   For this, you will only choose stuff that you are familiar with and not even look at the stuff you have no idea about.

2. **I like when life throws rocks at me!** <br>
   Here you will always try to choose stuff that you are not familiar with. But you will also learn why that thing is better or worse than other stuff.

3. **I like feeling the pain of Typescript!** <br>
   For this one take all from the previous one but do it all in Typescript.

## Creating the project

For most beginners, there is the holy grail called Create React App, or CRA for short.

The CRA is a good library and is recommended by React official documentation for a good reason.

But it's not the only way and not the best way to make React projects either.

The best way depends on your project and I recommend taking following tools into consideration:

### [CRA](https://create-react-app.dev/)

- Familiar to most people
- It is quick and painless to start

### [Vite](https://vitejs.dev/)

- New and incredibly fast
- You will never care about static pages

### [Remix](https://remix.run/)

- You really love react-router
- Learn something new

### [Next.js](https://nextjs.org/)

- Want to have front-end and back-end in same app
- Your project needs to have static pages

## Choose project structure

There is no real main way of structuring your project and most people do it how they want.

But we definitely want some structure to our projects.

So I recommend reading this [article](https://www.robinwieruch.de/react-folder-structure/) that describes the evolution of React project folder structure and choosing one step.

## Add formatting and linting tools
