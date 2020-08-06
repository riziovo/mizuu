# Mizu
<b>An Interactive ADT Visualizer</b>

This is a public facing repository to keep track of the project progress and announcements.


MIZU is a web app to visualize algorithms and data structure routines live on screen. The user will be able to see the transformations and data movements , real-time, as it responds to user events.


A working demo is available on youtube.

> <b> ~ Code will be live in September~ </b>

<b>Link</b> >> https://www.youtube.com/watch?v=FQ6ENe4olaE

Mizu goes live in September.


Backend hosts the Server and the Algorithms library which power the simulations on the backend. This Algorithms library houses ADTs based on structures :
> - Tree 
> - Heap
> - Trie
> - Queue
> - Stack
> - List
> - Graph



All of the ADTs in this library are my own implementations. As a function of being an interactive visualizer, the simulations on user side are real-time, not pre-rendered.


> ### ~watch this space for updates!



Todos
-----

### HIGH LEVEL PRIORITIES:

 - Write MORE Tests
 - Finish Tree section

### GRANULAR LEVEL PRIORITIES:


- HIGH PRIORITY : Fix margins so nodes do not overlap

- HIGH PRIORITY : For every user operation -> highlight, with a specific color, the node and element the Btree is acting upon, through which the end-user has a fair idea of the current flow of events.

- Remedy the issue of branches staying a step too long at dead spots

- Make transitions smoother. No cutscenes in between (Maybe add an inorganic hack with an animation step...?)

- Fix text-centering inside Nodes

- Labelling is bad... Improve it

- Brief documentation on each ADT


TECH
----

### Backend Tech

* [ZeroMQ] - Message Queues and Services Orchestration of worker threads for simulation
* [Java] - Backend in based on a Java ecosystem
* [NodeJS] - Websockets proxy relay
* [Redis] - session and caches


### Frontend Tech

* [HTML5] - UI
* [CSS3] - UI
* [Javascript ES6] - Visualisation Lib written in Vanilla JS to relay data transformations on client-side
* [Websockets] - Native WebSockets API

### And of course Internets and People! Without them I'd get nowhere.

License
----

MIT


**Free Software, Hell Yeah!**


