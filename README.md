# Mod is still in Development!


# Plants vs. Zombies (HTML, CSS, JavaScript)

A lightweight, browser-based implementation of the classic lane defense game, Plants vs. Zombies, built entirely with HTML, CSS, and vanilla JavaScript. No frameworks or external dependencies required — just open in your browser and protect your brains!

## 🌱 Features

*   Classic lane-based tower defense strategy
*   Waves of unique zombies with different abilities 🧟
*   Sun collection and resource management ☀️
*   An arsenal of plants with special powers 💥
*   Responsive design for desktop and mobile 📱
*   Iconic cartoon graphics 🎨

Of course. Here is the complete feature list for the mod in a single markdown document.

***

## 🏡 What This Mod Adds

### New Gameplay Elements Added

1.  **New Plants**
    *   **Garlic (🧄):** Costs 50 sun. A defensive plant that doesn't attack but diverts zombies into adjacent lanes when they try to eat it.
    *   **Cherry Bomb (💣):** Costs 150 sun. An instant-use plant that explodes, dealing massive damage (90) to all zombies in a 3x3 area. It is consumed on use.
    *   **Jalapeno (🌶️):** Costs 125 sun. An instant-use plant that creates a wall of fire, destroying all zombies in an entire lane. It is consumed on use.
    *   **Tall-nut (🌰):** Costs 125 sun. A heavy-duty defensive plant with significantly more health (48) than a Wall-nut.
    *   **Torchwood (🪔):** Costs 175 sun. A supportive plant that turns regular peas passing through it into fire peas, doubling their damage. It also extinguishes freezing projectiles.
    *   **Marigold (🌼):** Costs 50 sun. An economic plant that produces coins instead of sun (though the game describes this feature as "useless").
2.  **New Zombie Types**
    *   **Gargantuar (🗿):** A massive zombie with 180 health that deals devastating damage (99). It is so large that it cannot be eaten by the Chomper.
    *   **Giga-Gargantuar (👺):** An even stronger version of the Gargantuar with 600 health, capable of instantly destroying most plants. It is also uneatable.
3.  **Shovel Functionality (⛏️)**
    *   A **Shovel Card** has been added to the plant selection bar.
    *   Selecting the shovel allows the player to click on any planted plant on the lawn to remove it instantly.
    *   The game board's cells get a red highlight when hovering over them in shovel mode.
4.  **Lawnmower Last-Line Defense (🚜)**
    *   Each of the five lanes is now protected by a one-time-use lawnmower.
    *   If a zombie gets past all plants and reaches the house, the lawnmower in that lane will activate, destroying every zombie in its path.
5.  **Plant Upgrade System (🌟)**
    *   Certain basic plants can now be upgraded into more powerful versions by planting the special upgrade plant directly on top of its base.
    *   **Twin Sunflower (🌻🌻):** Costs 150 sun. An upgrade for the Sunflower that produces double the amount of sun (100) at once.
    *   **Gatling Pea (🔫):** Costs 250 sun. An upgrade for the Repeater that fires a burst of four peas at a time.

### Changes to Existing Elements & Mechanics

1.  **Plant Rebalancing and Reworks**
    *   **Chomper (🌿):**
        *   **No Longer Shoots:** The Chomper's ranged attack has been removed.
        *   **New "Chewing" Mechanic:** After eating a zombie, the Chomper is vulnerable and must "chew" for 42 seconds before it can eat again. Its animation now changes to show when it's chewing.
        *   **Anti-Boss Attack:** It cannot eat Gargantuars, but it will bite them for heavy damage (40) at a regular interval.
    *   **Sunflower (🌻):**
        *   **Sun Production Buff:** Sun production has been increased from 40 back to the original **50 sun**.
2.  **Zombie Rebalancing**
    *   The health and speed of all original zombies have been significantly increased to make the game more challenging.
    *   **Conehead Zombie (🧟‍♂️):** Health increased from 20 to 32. Speed increased.
    *   **Buckethead Zombie (🧟‍♀️):** Health increased from 40 to 68. Speed increased.
    *   **Fast Zombie (💀):** Health increased from 6 to 25. Speed increased.
    *   **Strong Zombie (👹):** Health increased from 60 to 99. Speed increased.
3.  **Core Gameplay Mechanic Changes**
    *   **Plant Cooldowns:** Every plant now has a cooldown period after being planted. You cannot select that plant again until the timer is up, preventing players from spamming powerful units and requiring more forward planning.
    *   **Wave Progression Rework:** The wave system has been fundamentally changed. The primary way to advance is by **defeating all zombies** from the current wave. Once the lawn is clear, the next wave will begin shortly after. This rewards fast and efficient play. A 30-second timer also exists as a backup to ensure the game progresses.
    *   **Advanced Game Engine:** The underlying code for game events, timers, and animations has been completely rewritten. This results in much more stable and reliable performance, especially when pausing the game or changing its speed.
    *   **Sun Collection:** Fixed a bug where you could collect sun many times from one Sunflower.
4.  **UI and UX Enhancements**
    *   **Wave Counter Position:** The wave counter has been moved from the top-right corner to the bottom-right for better visibility.
    *   **Sun Collection Animation:** When sun is clicked, it no longer vanishes instantly. It now visually flies across the screen and into the sun counter, providing better feedback.
    *   **Cooldown Visuals:** Plant cards in the selection bar now have a dark overlay that visibly drains to show the remaining cooldown time before they can be used again.
	
## 💻 Technologies Used

*   **HTML5** for structure
*   **CSS3** for layout & design
*   **JavaScript (ES6)** for game logic

## 📄 License

This project is released under the MIT License. Feel free to use, modify, and distribute.

## 🙏 Acknowledgments

Inspired by the beloved tower defense game *Plants vs. Zombies* by PopCap Games and the [original HTML game](https://github.com/plantsvszombiesjs/plantsvszombiesjs.github.io).
