# Game Theory through Examples — Modern Web Applets

A collaborative project to preserve, modernise, and extend the interactive web applets from **Erich Prisner's _Game Theory through Examples_** (Mathematical Association of America, 2014).

Many of the original applets were written in the late 1990s and early 2000s. While some remain accessible, many links have disappeared or no longer provide a good user experience on modern devices.

The aim of this project is to faithfully recreate these educational games using modern web technologies while preserving the original game mechanics and educational value.

## Goals

- Preserve the original educational content.
- Modernise the interface for desktop and mobile browsers.
- Replace obsolete HTML and JavaScript with modern standards.
- Keep each applet completely self-contained (HTML/CSS/JavaScript).
- Make the games easy to read, maintain, and extend.
- Provide a shared repository for members of the University of Pretoria's SIAM Student Chapter (a.k.a. the UP Maths Club) reading group to develop and maintain the applets collaboratively.

## Project Structure

```
/
│
├── index.html              # Main page linking to all applets
│
├── Auction/
│   ├── index.html
│   └── images/
│
├── QuatroUno/
│   ├── index.html
│   └── ...
│
├── ...
│
└── README.md
```

Each game lives in its own directory and consists of a standalone HTML application together with any required images or other assets.

## Design Philosophy

The original applets were built at a time when browser capabilities were much more limited. Rather than attempting to preserve the original interface exactly, each applet is reimplemented with a modern, responsive design while remaining faithful to the original gameplay.

Modernisations typically include:

- responsive layouts
- improved typography
- keyboard accessibility
- mobile support
- cleaner animations
- simplified game state management
- modern JavaScript (ES6+)
- removal of deprecated HTML features
- improved visual feedback
- readable, well-documented source code

## Artwork

Some original artwork used by the historical applets is no longer available.

Where replacement artwork is required, this repository uses either:

- public-domain artwork,
- openly licensed resources, or
- newly created graphical elements.

No AI-generated artwork is used unless explicitly stated.

## Attribution

These applets are based on the educational games created by **Prof. Erich Prisner** and published in:

> Erich Prisner,  
> *Game Theory through Examples*,  
> Mathematical Association of America, 2014.

This repository is an independent preservation and modernisation project and is not affiliated with the Mathematical Association of America or the author.

## Contributing

This repository is intended as a collaborative workspace for members of the UP Maths Club reading group.

Members are welcome to contribute by:

- recreating missing applets
- improving accessibility
- fixing bugs
- improving responsiveness
- cleaning up code
- improving documentation
- replacing unavailable assets with suitable public-domain alternatives

When making changes, please try to preserve the original game mechanics unless there is a compelling reason to change them. If gameplay is intentionally modified or extended, please document the changes clearly.

## Development Guidelines

Each applet should ideally:

- be entirely client-side
- have no build step
- avoid external JavaScript frameworks
- work in current versions of Chrome, Firefox, Edge, and Safari
- remain readable as an educational example

## Acknowledgements

Many thanks to **Prof. Erich Prisner** for creating these elegant examples illustrating concepts from game theory. We hope this project helps preserve these educational resources for future readers and students.

## License

The code in this repository is released under the license specified in this repository.

Please note that the original games, book content, and any third-party artwork remain subject to their respective copyrights and licences.
