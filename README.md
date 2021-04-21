# Phasmophobia Helper v2
Live Link: https://desolate-river-55511.herokuapp.com/

## ✏️ Description
This is a simple companion webapp for [Phasmophobia](https://store.steampowered.com/app/739630/Phasmophobia/) that helps you and your team track the ghost name, its behaviour and the objectives. It also helps you decide what kind of ghost you're dealing with. Also works with Speech Recognition (only available in Chrome/Chromium browsers as of 2021).

![Phasmophobia Helper Screenshot](https://i.ibb.co/bdWvzgP/Screenshot-2021-04-21-at-09-49-46.png)

## 📕 Table of Contents
<table>
    <tr>
        <td align="center"><a href="#-features">✨ Features<a></td>
        <td align="center"><a href="#%EF%B8%8F-installation">⚙️ Installation<a></td>
        <td align="center"><a href="#%EF%B8%8F-concepts">🏗️ Concepts<a></td>
        <td align="center"><a href="#-todo-list">📃 Todo list<a></td>
        <td align="center"><a href="#-tech-stack">⭐ Tech Stack<a></td>
        <td align="center"><a href="#-packages">📦 Packages<a></td>
        <td align="center"><a href="#-license">🔐 License<a></td>
    </tr>
</table>

## ✨ Features
- Easy tracking of ghost name, response & objectives
- Automatically find the correct ghost
- Immersive Voice Commands as an alternative input

## ⚙️ Installation
1. Clone this Repo locally
```
git clone https://github.com/SjorsWijsman/real-time-web-2021/
```

2. With Node & NPM [download here](https://nodejs.org/en/download/) installed, run the following command to install dependencies:
```
npm install
```

3. Build & Start a local server with:
```
npm start
```
4. Or start a dev environment (with automatic local server updates on code changes) with:
```
npm dev
```

## 🏗️ Concepts
For the Real Time Web course I started with 3 concepts to develop during the course. I started with the first concept (Gameplaylists), still visible on the `old` branch of this repo. Eventually I got demotivated by this concept (not enough challenge) and switched to the Phasmophobia Helper concept.

<details open>
<summary>3 Concepts</summary>
<br>
| Gameplaylists | Phasmophobia Book | Poker |
|--|--|--|
| ![Gameplaylists](https://i.ibb.co/2jMS3tW/Gameplaylists.png) | ![Phasmophobia Helper](https://i.ibb.co/sFdS873/Phasmophobia-Book.png) | ![Poker](https://i.ibb.co/ZHW9R7r/Poker.png)
</br>

## 📃 Todo list
- [x] Reimplement old [Phasmophobia Helper Svelte code](https://github.com/SjorsWijsman/phasmophobia-helper) 
- [x] Implement static site generation with Snowpack
- [x] Setup server & Serve files wtith Express
- [x] Implement basic Socket functionalities
- [x] Add Socket rooms with ingame lobby codes
- [ ] Improve Socket stability
- [ ] Add better feedback for joining lobbies
- [ ] Prevent bottom of page from jumping around when reducing possible ghost amount

## ⭐ Tech Stack
### Svelte
Svelte Docs: https://svelte.dev/docs

TODO

### Express
Express Docs: https://expressjs.com/

TODO

### Snowpack
Snowpack Docs: https://www.snowpack.dev/

TODO

### Socket.io
Socket.io Docs: https://socket.io/

TODO

## 📦 Other Packages
### nodemon
Nodemon Docs: https://www.npmjs.com/package/nodemon

TODO

### concurrently
Concurrently Docs: https://www.npmjs.com/package/concurrently

TODO

## 🔐 License
MIT License.
