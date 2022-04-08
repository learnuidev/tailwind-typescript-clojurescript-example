# Getting started with ClojureScript, TypeScript and TailwindCSS

In this video you will learn how to build SPA using TypeScript, ClojureScript, tailwindcss and headless


Learning Objects

- Create basic shadow-cljs react project
- Add typescript into our project.
- Learn how to configure a typescript project + understand all the required dependencies
- Learn what is babel and how to configure + use to compile typescript into es2015 code
- Use babel to compile typescript to javascript
- Learn how to use custom TypeScript component in ClojureScript codebase
- Learn how to use custom hooks in Reagent based application


So here is the strategy

1. we will use typescript to write all of our custom javascript interop logic such as react components that uses headless ui + tailwind ui
2. we will use clojurescript to write only the core business logic

This strategy has many benefits
- JavaScript interop code can evolve independently from core business logic
- Clear separation from interop code and business logic code
- ClojureScript code becomes smaller since it is only using interfaces


Steps:

1. Create a new shadow-cljs project
2. Configure typescript
3. Configure tailwind

_To Run Locally:_
Clone the repository and perform the following command line actions:
```bash
$ cd wordle
$ yarn
$ yarn dev
```


open http://localhost:3000 in browser.
