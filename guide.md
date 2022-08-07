# Anubis

Self hosted dashboard and home management system with plugin system for rewards

## Features

* JSON-based customizable dashboard
* task-list, reminders, and reward system
* satellite system for communicating to server

---

## Story

### who
* Users hosting the app on their server
* Roommates
* family members

### what
_Self hosted dashboard and home management system with plugin system for rewards_

The basis of the app will be a express/node.js api that talks to a database and manages requests. 
The dashboard and satellites will read from/send requests to the api. 
Users will be able to customize their own response workflows from queries sent to the server, and customize how data shows on their dashboard.


### where
* At home
* Dashboard on the web
* Mobile Devices

### when
* Whenever the user has a query for the server
* Whenever the server has a reminder for the end user

### how
* Dashboard on the web
* Mobile Devices

---

## MVP
> :bulb: **Minimum Viable Product** _what features are needed for it to fulfill its basic purpose_

* API
* Front-end
* Setup json parser for viewing/editing workflows

## V2
> :pencil: **Bug squashing and some cleanup** _check with users to see what can improve_

* {bug fix}
* {bug fix}
* {QoL / small feature}

---

## Design Order
1. make multiple users, and how they use the app [^1] - Store as Github issues
1. think about data and how it relates to the app and user [^2] - UML Diagram
1. create wireframes [^3]
1. browse inspiration online [^4]
1. move along in the design process to mockups and prototypes [^5]

---

**Octo's todo system**
_A kanban board, but within your todo list_

`[ ] do the thing` use in lists

`@status thing to check later` use in comments throughout your project 

```md
[ ] @todo
[?] @think
[o] @doing
[/] @block
  @block: _insert issue here_
[>] @hack
[!] @fixme
[x] @done
[-] @cancel
```

---

**Octo's recommended tools**
_these are the only ones I use when making things_

* [figma](https://figma.com) - wireframing and mockups
* [codepen](https://codepen.io) - small code and css sketches
* [vscode](https://code.visualstudio.com/) - writing code

[^1]: [10 tips for writing good user stories](https://www.romanpichler.com/blog/10-tips-writing-good-user-stories/)
[^2]: [how to make an ER diagram](https://youtu.be/QpdhBUYk7Kk)
[^3]: [12 tips for creating better wireframes](https://uxplanet.org/12-practical-tips-for-creating-better-wireframes-be0418777946)
[^4]: [learn/ux-ui](https://github.com/octoshrimpy/learn/blob/main/web/frontend/UX_UI.md#design-inspiration)
[^5]: [the stages of design process](https://medium.com/a-curious-life/wireframe-mockup-prototype-and-other-stages-of-designing-process-2a3f1c9e1dbf)

---

planning system and template made with :purple_heart: by [octoshrimpy](https://github.com/octoshrimpy)
