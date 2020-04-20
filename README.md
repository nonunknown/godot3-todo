![TODO logo](addons/todo/icon.png)

# TODO Plugin
This is a TODO list dock for the Godot 3 game engine. It is the successor of [the 2.1 version](https://github.com/need12648430/godot-todo).

## Features:
* Supports `TODO`, `HACK`, `BUG`, `FIXME`, and `NOTE` tags out of the box.
* Double clicking any TODO will bring you right to it; built-in script? No problem. TODO buried 200 lines deep? It'll even bring you to the line.
* Uses Godot's `EditorFileSystem`, so TODO lists are updated on file save with no (additional) background polling required. Some naive caching is also used to speed things up further.
* Searchable/filterable by TODO contents, or filenames.
* If the script editor is open, it will only show TODOs in the active script so you can focus exclusively on what you're doing.
* Tight integation with the Godot 3 ~ **a e s t h e t i c** ~. (In other words I blatantly (and lazily) abused the built-in icons.)

## How to Install
* Download the repo
* Extract the plugin folder inside your project's addon/ folder
* Enable it

## How to use
Simply Add one of the follow keywords at your script
* **#TODO :**
* **#HACK :**
* **#BUG :**
* **#FIXME :**
* **#NOTE :**

Example:
```
func great_plugin():
  #TODO :
  #Implement this awesome plugin
```

## Plugin in action:

![Preview of TODO](preview/todo.gif)

[![Shamelessly begging for tips](https://az743702.vo.msecnd.net/cdn/kofi1.png?v=0)](https://ko-fi.com/A0A4H42F)
