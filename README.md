# ASC Archive Lenses

One archive, many ways of looking. A sister site to the ASC Living Archive, by the ASC Archives Working Group.

- **Handles** set what is selected: Principle (the seven Cybernetics Literacy principles), Time, Person (with how far out: their own, one step, two steps) and Collections.
- **Lenses** show the same selection in different ways: River, Ring, Reading room and Eucrates. An About page explains the handles and lenses, and a Feedback page sends an email to the Archives Working Group with the view attached. New lenses can be added without touching the data.
- **The link is the selection.** The address bar records every handle, so a link reproduces exactly what you see.

## Data

The site reads the shared data set at the address in `config.js` (the archive-data site). If that is empty or unreachable it uses its own copy, `data.json`.

## Files

`index.html` (the site), `config.js` (data address), `data.json` (fallback copy), `vercel.json` and `robots.txt` (ask search engines not to index).

## Eucrates

Suggested by Claudia Westermann. A lens that converses, after Gordon Pask's teaching machines and the instrumentation panel believed to be from his Eucrates project (1955, with Robin McKinnon-Wood and C.E.G. Bailey), as described in Usman Haque, "The Architectural Relevance of Gordon Pask" (2007). It offers five items from the current selection. Your responses (Go on, Not this, Open) change how it chooses the next five. Its knobs set its character:

- **External awareness**: how much it attends to you
- **Internal awareness**: how much it follows the archive's own links (shared people, principles, collections)
- **Oblivescence**: how quickly it forgets
- **Reinforce memory**: how strongly each response is remembered
- **Obstinacy**: how firmly it holds its own focus
- **Novelty** (unlabeled on the original panel): how soon it grows bored of repetition and listens elsewhere, as MusiColour did

Four lamps show whether it is following you or the archive, holding its focus, or bored. Knob settings are saved in the link.
