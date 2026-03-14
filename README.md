# MathSt4rz
GN OS its a web os kinda a$$ but ok for school its using gn math btw so credits to them


# MathSt4rz

fake cyberpunk os interface running entirely in your browser. play store for dumping html5 games/zones. install/uninstall from library. dock, windows, blur glass, red glow. zero backend. all localstorage.

current version: **26.03** (march 2026 edition)

https://github.com/gn-math/gn-math-DONTDMCA (or wherever you host the raw html)

## features

- boot → fake account creation (username + pass, stored locally)
- desktop with animated glowing dock
- play store launcher (blur overlay)
- two tabs: **store** + **my games** (library)
- search games in both views
- install → adds to dock + localstorage
- in library: **play** button + **🗑 trash** to nuke installed games
- windows with titlebar (fullscreen, new tab, download html, close)
- internal html zones get blob-wrapped + base href fix
- external urls load straight in iframe
- glassmorphism + neon red accents
- clock in status bar
- no server, no tracking, pure client-side

## screenshots

(tba – drop some when you have them)

or just open index.html in browser and screenshot yourself.

## how to run

1. clone or download this repo
2. open `index.html` in any modern browser (chrome/edge/firefox 2025+ recommended)
3. create fake account on first load
4. click play store icon in dock → browse/install
5. go to "my games" tab → trash shit you don't want

that's it. no npm, no build step, no nothing.

## tech stack (lol)

- vanilla html/css/js
- css variables + backdrop-filter blur
- fetch + blob urls for internal games
- localstorage for account + installed list
- cdn.jsdelivr.net for zones.json / covers / html payloads

## zones format (for reference)

zones come from:
