#SwitchMap vs MergeMap

SwitchMap and MergeMap are smiliar operators, they're your go-to when you need to combine streams. Knowing the who, what, and why between these two operators will help you pick the right one for the job. Let's start with their similarites:

####SwitchMap
SwitchMap is an operator that maps the values emitted from an observable to a different observable.

####MergeMap
MergeMap is an operator that maps the values emitted from an observable to a different observable.

___
Pretty ~~similar~~ identical so far, right? There _are_ differences, but I'll save them for later.  Let's first pick appart this definition and then move to the differences. 

####SwitchMap & MergMap
SwitchMap _and_ MergeMap are operators that maps the values emitted from an observable to a different observable.

To start, let's break apart SwitchMap and MergeMap into the indiviuals **verbs** that make them up: 


| Verb     | What it does  |
| -------- |:-------------:| 
| Map      | ? | $1600 |
| Merge    | ?      | 
| Switch   | ?      | 

####Map
When you see **map** you can read it as: `Use the value of something to change it to something else`.

To expand on this, consider this tragic hypothetical. Imagine a world where there are no dogs. Only cats. At one point there _where_ dogs, but somewhere intime CatConverter was created