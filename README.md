# Jezzball
 
A browser-based version of Jezzball, built with HTML, CSS, JavaScript, and jQuery.

## How to Play
 
Open `index.html` in any modern web browser. No installation or server required.
 
**Controls:**
- **Left click** — draw a barrier from the cursor position
- **Right click** — toggle the cursor between vertical and horizontal directions
- A barrier grows in both directions simultaneously until it hits a wall or an existing barrier
- If a ball touches a barrier while it's still growing, the barrier is destroyed and you lose a life
**Goal:**
- Clear 75% or more of the play area by walling off sections that don't contain any balls
- Complete the level before the timer runs out
- Progress through levels — each level adds another ball and more time
**Scoring:**
- Points are awarded for each grid space enclosed in a closed area
- Bonus points are added at level completion based on remaining time
**Lives:**
- You start with `level + 1` lives per level
- Losing all lives ends the game; press **Retry** to restart the level
