# HTML5 Canvas Space Shooter Game

A classic top-down space shooter game built entirely with HTML5 Canvas and plain JavaScript. Features multiple enemy types, a multi-phase boss battle, power-ups, and visual effects.


## Features

* **Player Control:** Smooth ship movement using WASD or Arrow Keys.
* **Shooting:** Fire bullets using the Spacebar.
* **Slow Mode:** Hold Left Shift or Right Shift for precise movement and hitbox display.
* **Multiple Enemy Types:** Face three distinct enemy types with unique movement, health, and attack patterns (straight shots, spread shots, circular bursts).
* **Boss Battle:** Encounter a challenging multi-phase boss with evolving attack patterns and a dedicated HP bar.
* **Scoring System:** Earn points by destroying enemies and defeating the boss.
* **Lives System:** Start with 3 lives; lose a life upon collision.
* **Basic Power-Up:** Destroying enemies gives a chance to temporarily upgrade player shots.
* **Visual Effects:** Includes a parallax star background and explosion animations.
* **UI Elements:** Displays current score and remaining lives.
* **Game States:** Includes Start Screen, Game Over Screen, and Stage Clear Screen.
* **Image Fallbacks:** Uses colored rectangles if image assets fail to load.
* **Progressive Difficulty:** Enemy spawn rate and complexity increase over time.

## How to Play

* **Move:** Use **WASD** keys or the **Arrow Keys (↑ ← ↓ →)** to navigate your ship.
* **Shoot:** Press the **Spacebar** to fire bullets.
* **Slow Mode / Show Hitbox:** Hold down the **Left Shift** or **Right Shift** key to move slower for more precise dodging and to see your ship's hitbox (the small cyan circle).
* **Objective:** Survive waves of enemies, shoot them down to score points, and defeat the final boss.
* **Avoid:** Dodge enemy ships and their bullets. Colliding with either will cost you a life.
* **Game Over:** The game ends when you run out of lives.
* **Restart:** Use the buttons on the "Game Over" or "Stage Clear" screens to play again.

## How to Run

### Online (via GitHub Pages)

This game can be played directly in your browser using GitHub Pages (if enabled for this repository).

* **Play Here:** [https://Brook-Yohoho.github.io/simple-shooter-game2/](https://Brook-Yohoho.github.io/simple-shooter-game2/)

### Locally

1.  **Download:** Clone this repository or download the `index.html` file.
    ```bash
    git clone [https://github.com/Brook-Yohoho/simple-shooter-game2.git](https://github.com/Brook-Yohoho/simple-shooter-game2.git)
    cd simple-shooter-game2


    ```
    OR just download `index.html`.
2.  **Open:** Open the `index.html` file directly in your web browser (like Chrome, Firefox, Edge, Safari). No web server is needed.

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* HTML5 Canvas API

## Customization

Feel free to fork this repository and modify the code (`index.html`):

* Adjust game parameters (speeds, health, spawn rates, cooldowns).
* Add new enemy types or attack patterns.
* Implement different power-ups or items.
* Improve graphics or add sound effects.
* Create multiple levels or different bosses.

---

*This project serves as a demonstration of creating a browser game using HTML5 Canvas and JavaScript.*
