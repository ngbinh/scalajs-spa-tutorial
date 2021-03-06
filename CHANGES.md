# Change history

## 0.1.4

* Introduced [ScalaRx](https://github.com/lihaoyi/scala.rx) to propagate changes from store to views, replaced EventEmitter

## 0.1.3

* Unidirectional data flow framework *Ukko* following Facebook Flux and actor architectures
* Todo list implemented with the new data flow model
* Main menu item *Todo* now shows count of open todos
* Testing with *uTest*

## 0.1.2

* Simple jQuery integration added (Bootstrap Modal)
* Modal example with a form
* Refactored Bootstrap components a bit
* Todos are now updated on the server

## 0.1.1

* Refactored the router system to follow the intended design of the Scala.js React router (thanks to @japgolly for feedback)
* Separated MainMenu into its own component as part of the router refactoring
* Updated libraries scalajs-dom and scalajs-react to 0.8.0
* Changed all tags to use <^ prefixes (less potential for name conflicts)
* Documentation updated to reflect the changes

## 0.1.0

* Initial release
