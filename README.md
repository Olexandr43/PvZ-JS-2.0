# Plants vs. Zombies (HTML, CSS, JavaScript)

A lightweight, browser-based implementation of the classic lane defense game, Plants vs. Zombies, built entirely with HTML, CSS, and vanilla JavaScript. No frameworks or external dependencies required — just open in your browser and protect your brains!

## 🌱 Features

*   Classic lane-based tower defense strategy
*   Waves of unique zombies with different abilities 🧟
*   Sun collection and resource management ☀️
*   An arsenal of plants with special powers 💥
*   Responsive design for desktop and mobile 📱
*   Iconic cartoon graphics 🎨

## 🏡 What this mod adds

### New Gameplay Elements Added

1.  **New Plants**
    *   **Garlic (🧄):** Costs 50 sun. A defensive plant that doesn't attack but diverts zombies into adjacent lanes when they try to eat it.
    *   **Cherry Bomb (💣):** Costs 150 sun. An instant-use plant that explodes, dealing massive damage (90) to all zombies in a 3x3 area. It is consumed on use.
    *   **Jalapeno (🌶️):** Costs 125 sun. An instant-use plant that creates a wall of fire, destroying all zombies in an entire lane. It is consumed on use.
    *   **Tall-nut (🌰):** Costs 125 sun. A heavy-duty defensive plant with significantly more health (48) than a Wall-nut.
    *   **Gatling Pea (🔫):** Costs 250 sun. An upgraded Repeater that fires a burst of four peas at a time.
    *   **Torchwood (🪔):** Costs 175 sun. A supportive plant that turns regular peas passing through it into fire peas, doubling their damage. It also extinguishes freezing projectiles.
    *   **Marigold (🌼):** Costs 50 sun. An economic plant that produces coins instead of sun (though the game describes this feature as "useless").
2.  **New Zombie Types**
    *   **Gargantuar (🗿):** A massive zombie with 180 health that deals devastating damage (99). It is so large that it cannot be eaten by the Chomper.
    *   **Giga-Gargantuar (👺):** An even stronger version of the Gargantuar with 600 health, capable of instantly destroying most plants. It is also uneatable.
3.  **Shovel Functionality**
    *   A **Shovel Card (⛏️)** has been added to the plant selection bar.
    *   Selecting the shovel allows the player to click on any planted plant on the lawn to remove it instantly.
    *   The game board's cells get a red highlight when hovering over them in shovel mode.

### Changes to Existing Elements & Mechanics

1.  **Plant Rebalancing and Reworks**
    *   **Chomper (🌿):**
        *   **No Longer Shoots:** The Chomper's ranged attack has been removed.
        *   **New "Chewing" Mechanic:** After eating a zombie, the Chomper is vulnerable and must "chew" for 42 seconds before it can eat again. Its animation now changes to show when it's chewing.
        *   **Anti-Boss Attack:** It cannot eat Gargantuars, but it will bite them for heavy damage (40) at a regular interval.
2.  **Zombie Rebalancing**
    *   The health, speed, and point values for all original zombies have been significantly increased to make the game more challenging.
    *   **Conehead Zombie (🧟‍♂️):** Health increased from 20 to 32. Speed increased.
    *   **Buckethead Zombie (🧟‍♀️):** Health increased from 40 to 68. Speed increased.
    *   **Fast Zombie (💀):** Health increased from 6 to 25. Speed increased.
    *   **Strong Zombie (👹):** Health increased from 60 to 99. Speed increased.
3.  **Core Gameplay Mechanic Changes**
    *   **Wave Progression:** The game advances to the next wave based on a 30-second timer. BUT, the next wave will also begin after all zombies from the current wave have been defeated.
    *   **Sun Collection:** Fixed a bug where you could collect sun many times from one Sunflower.
4.  **UI and UX Enhancements**
    *   **Wave Counter Position:** The wave counter has been moved from the top-right corner to the bottom-right for better visibility.

## 💻 Technologies Used

*   **HTML5** for structure
*   **CSS3** for layout & design
*   **JavaScript (ES6)** for game logic

## 📄 License

This project is released under the MIT License. Feel free to use, modify, and distribute.

## 🙏 Acknowledgments

Inspired by the beloved tower defense game *Plants vs. Zombies* by PopCap Games and the [original HTML game](https://github.com/plantsvszombiesjs/plantsvszombiesjs.github.io).
