# Jer's Playground 🎮

Welcome to **Jer's Playground**, a fun collection of tiny games and silly experiments made just for enjoyment and creativity! 

Here you'll find a variety of mini-games ranging from quirky physics-based challenges to creative art tools and word puzzles. Whether you're looking for a quick distraction or something to spark your imagination, this playground has a little something for everyone.

## Features
- Lightweight, browser-based games
- Simple and playful design
- Theme toggle (light, dark, and rainbow modes)
- Tag-based game filtering for easy browsing

## How to Use
Simply browse the games, click to play, and have fun! Feel free to contribute new games or experiments by submitting a pull request.

## About
Created by Jer ([@aysail](https://github.com/aysail)) as a personal playground to experiment with web games and share joy.

---

**Enjoy your time in the playground! 🕹️**

---

## 🎨 Modding Jer's Playground Games 

_To mod Jer’s Playground games, you’ll need to know a bit of HTML, CSS, and JavaScript—just enough to understand what you’re doing, not everything in-depth._

Modding is a way of adding new stuff to Jer’s Playground games — whether it’s something totally wild, a bug fix, or just a fun improvement you want to share.

If you made something cool or fixed something broken, feel free to open a pull request!

> 📜 **License**  
> This project is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).  
> Feel free to remix, share, or mod — just **credit**, **don’t sell**, and **link back** to this repo!


### 🛠️ How to Mod a Game

1. **Fork or clone the repo**:
   ```bash
   git clone https://github.com/aysail/jers-playground.git
   ```

2. **Open the folder in VS Code** (or any code editor).

3. Go into the `/games/` folder and pick a game to mod.

4. Edit the HTML, CSS, or JavaScript:
   - Add new features 🧪  
   - Change gameplay 🎮  
   - Tweak visuals 🎨  
   - Fix bugs 🐞

5. **Test your changes**:
   - Open the game file directly in your browser  
   - Or use a Live Server extension in VS Code

6. **Add your mod to the homepage**:
   Open `index.html` and add a new block in the `.game-grid` section like this:

   ```html
   <a href="games/YourModdedGame.html" class="game-card" data-tags="mod yourtag">
     <div class="card-emoji">🧪</div>
     <h2>Your Mod Name</h2>
     <p class="tags">#mod #yourtag</p>
   </a>
   ```

7. **Make a pull request** if you want your mod included on the main site!

---

### 📁 Folder Tips

- Put your mod file in the `/games/` folder
- Make sure the filename is something unique (like `CoolMod.html`)
- You can include your own `.js` or `.css` files too

---

### 💡 Examples

#### A basic mod card in `index.html`:

```html
<a href="games/BouncyBoxMOD.html" class="game-card" data-tags="silly physics mod">
  <div class="card-emoji">🧪</div>
  <h2>Bouncy Box: Chaos Edition</h2>
  <p class="tags">#silly #mod</p>
</a>
```

---

### ✅ Ready to Share?

If your mod works and you want it added:

1. Make sure it’s fun and Family Friendly (We only allow family friendly games on the site)  
2. Credit yourself inside the file (like in a comment)  
3. Submit a **pull request** to the main repo

Let’s make this playground even weirder, sillier, and more awesome! 🎉


