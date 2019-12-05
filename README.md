

## Session 1 

Install Clojure https://clojure.org/guides/getting_started

Download & install https://www.jetbrains.com/idea/download/ Intellij Community

Install the Cursive plugin, instructions are here: https://cursive-ide.com/userguide/index.html

Create a new clojure -> deps project under file -> new in Intellij

Right click your project in the side bar and click new clojure namespace type src/core

That will generate a folder called src with a .clj file in called "core.clj" 
open it and edit it to be:
```clj
(ns core)
```

Then add a hello world code by adding this:
```clj
(defn -main []
  (println "Hello world"))
```

Run the code by right clicking your project and clicking REPL and then run that should open a REPL
Learn how to run your hello world by reading: https://cursive-ide.com/userguide/repl.html

`clj -m core` on the terminal, in your project dir, should execute the program on the terminal

Enable parinfer (important)

## Session 2

Install clj-kondo for static analysis here: https://github.com/borkdude/clj-kondo/blob/master/doc/install.md

Integerate it inside Intellij by following these instructions: https://github.com/borkdude/clj-kondo/blob/master/doc/editor-integration.md#intellij-idea Use the LSP instructions (these were improved recently)

Sign up to clojurian slack via: http://clojurians.net/ for getting quick help

Sign up to 4clojure problems via: http://www.4clojure.com/

Complete the first three problems on 4clojure

Other community links:
- https://www.clojuriststogether.org/
- https://borkdude.github.io/re-find.web
- https://www.meetup.com/Bristol-Clojurians/

## Session 3

Catch up for new comers via pairing and learning language sensibilities:

- https://youtu.be/GtkouFS-GSQ
- https://youtu.be/-6BsiVyC1kM

## Session 4 
Dissecting ShadowCLJS, Reagent and Reframe templates, goal is to show the qualities of CLJS as a compile to JavaScript language

https://github.com/lambrospetrou/create-shadow-cljs-app
- `npx create-shadow-cljs-app ...; cd ...; (npm run start:browser and npm run watch:browser) `

https://github.com/filipesilva/create-cljs-app
- `npx create-cljs-app ...; cd ...; npm run start`

https://github.com/day8/re-frame-template
- `lein new re-frame` 

### Challenge 
Transact something to the reframe database

<details>
  <summary>More advanced templates</summary>
  
  http://www.luminusweb.net/docs/profiles.html#clojurescript
  - `lein new luminus ... +cljs`

  https://github.com/fulcrologic/fulcro-template
  - `git clone ...`

  https://github.com/fulcrologic/fulcro-native-template
  - `git clone ...`
</details>

### Homework
- What is the "elephant in the room" at every stand up?
- What is a complexity budget?
- What does it mean to complect something?

Answers found in session 3

