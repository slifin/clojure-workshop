

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

`clj -m core` on the terminal should execute the program on the terminal


## Session 2

Install clj-kondo for static analysis here: https://github.com/borkdude/clj-kondo/blob/master/doc/install.md

Integerate it inside Intellij by following these instructions: https://github.com/borkdude/clj-kondo/blob/master/doc/editor-integration.md#intellij-idea (it should work by copying the image), just make sure it's enabled globally afterwards

Sign up to clojurian slack via: http://clojurians.net/ for getting quick help

Sign up to 4clojure problems via: http://www.4clojure.com/

Complete the first three problems on 4clojure

Other community links:
https://www.clojuriststogether.org/
https://www.meetup.com/Bristol-Clojurians/

## Session 3

Catch up for new comers via pairing and learning language sensibilities:

https://www.youtube.com/playlist?list=PLXsqD83He-e5oUh_DFrHbO3MoNj3tG8Vh
