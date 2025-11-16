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
*   Local Top 10 leaderboard with date/time badges 🏆

## 🏡 Key Features of This Mod


### Major New Features

*   **Full Save/Load System:** The game state can be saved at any time from the pause menu and loaded from the main selection screen, preserving all plants, zombies, and wave progress.
*   **Zombie Almanac:** An in-game Almanac is now available from the plant selection screen. It tracks all encountered zombies, allowing players to view their stats, descriptions, and abilities.
*   **Pre-Game Plant Selection:** Players no longer start with a fixed set of plants. A new **Plant Selection Screen** appears before the game starts, where players must choose a limited deck of plants from a larger library to use in the upcoming match. This adds a significant layer of strategy.
*   **Lawnmowers:** The iconic last line of defense has been added. Each lane is protected by a lawnmower (`🚜`) that will activate upon the first zombie reaching the house, clearing the entire lane once.
*   **Shovel Functionality:** Players can now remove misplaced or unwanted plants using a Shovel (`⛏️`). This is selectable from the plant bar in-game.
*   **Victory Condition:** There is a final wave (Wave 20), and defeating all zombies in that wave now triggers a **Victory sequence**, complete with a collectible trophy (`🏆`) and a victory screen.
*   **Debug/Sandbox Mode:** A hidden zombie spawner has been added, which can be toggled with the 'Z' key. This allows players to manually spawn any type of zombie on any tile for testing or fun.
*   **Custom Dialog System:** Replaces native browser alerts with themed, non-blocking modals for a smoother user experience.

---

### Core Gameplay & Balance Changes

1.  **Plant Rebalancing and Reworks**
    *   **Chomper (🌿):**
        *   **New "Chewing" Mechanic:** After eating a zombie, the Chomper is vulnerable and must "chew" for 42 seconds before it can eat again.
        *   **Bite Attack:** It cannot eat Gargantuars, but it will now bite them for a small amount of damage.
    *   **Sun Economy:**
        *   Sunflowers now produce **50 sun**.
        *   Twin Sunflowers produce **100 sun**.
        *   Sun falling from the sky is now worth **25**.

2.  **Wave Progression Rework**
    *   The wave system has been completely redesigned. Waves are now generated using a **point-buy system**, where the game uses a "budget" for each wave to purchase a varied and increasingly difficult group of zombies from an available pool.
    *   The primary way to advance is by **defeating all zombies** from the current wave. A backup timer also ensures the game progresses.

3. **Advanced Game Engine:** 
    *   The underlying code for game events and timers has been rewritten to be more robust, ensuring all timed events (cooldowns, spawns, etc.) are correctly paused and scaled with the game speed, fixing major bugs in the original.

4.  **UI and UX Enhancements**
    *   **Wave Counter Position:** The wave counter has been moved to the **bottom-right** for better visibility.
    *   **Sun Collection Animation:** Sun now visually **flies across the screen** into the sun counter for better feedback.

---

### New Plants Added

The arsenal of plants has more than tripled, adding significant strategic variety.

*   **Blover (🍀):** Costs 125 sun. An instant-use plant that creates a strong gust of wind, blowing away all flying Balloon Zombies from the screen instantly.
*   **Cabbage-pult (🥬):** Costs 100 sun. Lobs cabbages at zombies, dealing twice the damage of a standard pea.
*   **Cactus (🌵):** Costs 125 sun. Shoots piercing spikes that can pop a Balloon Zombie's balloon and hit multiple targets.
*   **Cherry Bomb (🍒):** Costs 150 sun. An instant-use plant that explodes, dealing massive damage (90) to all zombies in a 3x3 area. It is consumed on use.
*   **Coffee Bean (☕):** Costs 75 sun. An instant-use plant placed on top of sleeping mushrooms to wake them up for use during the day.
*   **Doom-shroom (🍄):** Costs 125 sun. A highly destructive instant-use plant that explodes in a massive 7x5 area, dealing huge damage (90) to all zombies caught in the blast. It leaves a temporary, unplantable crater at its location.
*   **Fire Pea (🔥):** Costs 250 sun. Shoots fire peas that deal splash damage in a small area and can thaw frozen zombies.
*   **Fume-shroom (⚗️):** Costs 75 sun. Shoots fumes that can penetrate shields and damage all zombies in a line. Sleeps during the day.
*   **Garlic (🧄):** Costs 50 sun. A defensive plant that doesn't attack but diverts any zombie that bites it into an adjacent lane.
*   **Gatling Pea (🔫):** Costs 250 sun. An upgrade plant that must be planted on an existing Repeater. It fires a burst of four peas at a time.
*   **Gloom-shroom (🌀):** Costs 150 sun. An upgrade for the Fume-shroom. It attacks all zombies in a 3x3 area around itself with a burst of fumes. Sleeps during the day.
*   **Grave Buster (🦇):** Costs 75 sun. A special single-use plant that can only be planted on graves. It consumes the grave over 5 seconds and rewards the player with sun.
*   **Hurrikale (🌬️):** Costs 100 sun. An instant-use plant that pushes all zombies in a single lane backward and applies a chilled effect, instantly defeating any Balloon Zombies blown off-screen.
*   **Ice-shroom (🧊):** Costs 75 sun. An instant-use plant that freezes every zombie on the entire screen, stopping them in their tracks for 4 seconds and dealing minor damage.
*   **Imitater (🎭):** Cost varies. A strategic plant that transforms into a copy of the previously selected plant card, allowing you to bring two of the same plant into a level with separate cooldowns.
*   **Jalapeno (🌶️):** Costs 125 sun. An instant-use plant that creates a wall of fire, dealing massive damage (90) to and destroying all zombies in an entire lane. It also melts any ice trails left by Zombonis.
*   **Kernel-pult (🌽):** Costs 100 sun. Has a 25% chance to launch butter instead of a kernel. Butter deals more damage and stuns zombies for 5 seconds, temporarily stopping them.
*   **Marigold (🌼):** Costs 50 sun. An economic plant that produces coins (represented as small suns).
*   **Melon-pult (🍉):** Costs 300 sun. Lobs melons that deal solid damage and splash to nearby zombies on impact.
*   **Plantern (🏮):** Costs 25 sun. A utility plant that is thematically included (in the original game, it clears fog).
*   **Potato Mine (🥔):** Costs 25 sun. A cheap, single-use plant that is initially vulnerable. After a 14-second arming time, it will explode on contact, dealing immense damage (90) to a single zombie.
*   **Puff-shroom (🐡):** Costs 0 sun. A short-range shooter that is free to plant but has a limited lifespan. Sleeps during the day.
*   **Scaredy-shroom (☂️):** Costs 25 sun. A long-range shooter that hides and stops firing when zombies get too close. Sleeps during the day.
*   **Snapdragon (🐲):** Costs 225 sun. A stationary plant that breathes fire in a 3x2 area, dealing 1.5 damage every 2 seconds and thawing any frozen or chilled zombies.
*   **Snow Pea (❄️):** Costs 175 sun. Shoots freezing peas that damage and slow down zombies.
*   **Spikerock (📍):** Costs 125 sun. An upgrade for Spikeweed. It deals more damage and can survive multiple hits from crushing zombies like the Zomboni.
*   **Spikeweed (📌):** Costs 100 sun. A ground-level plant that damages any zombie that walks over it. It cannot be eaten and can be upgraded to Spikerock.
*   **Sun-shroom (🌞):** Costs 25 sun. Initially produces small suns, but grows over time to produce full-sized suns. Sleeps during the day.
*   **Tall-nut (🌰):** Costs 125 sun. A heavy-duty defensive plant with significantly more health (48) than a Wall-nut, making it an excellent blocker.
*   **Threepeater (🎋):** Costs 325 sun. Shoots peas in three lanes simultaneously: its own, and the lanes directly above and below.
*   **Torchwood (🪔):** Costs 175 sun. A supportive plant that turns regular peas passing through it into fire peas, doubling their damage. It also extinguishes freezing projectiles, turning them into normal peas.
*   **Twin Sunflower (🌻🌻):** Costs 150 sun. An upgrade plant that must be planted on an existing Sunflower. It produces 100 sun at a time, doubling the normal rate.
*   **Wall-nut (🥥):** Costs 50 sun. A defensive plant with high health (24) that blocks zombies.
*   **Winter Melon (🥶):** Costs 200 sun. An upgrade for the Melon-pult. Its projectiles deal heavy damage and freeze all zombies in the splash zone.
---

### New Zombies Added

The horde has grown nearly five times more dangerous and unpredictable.

*   **Flag Zombie (🚩):** A faster zombie that leads the charge at the beginning of each wave.
*   **Newspaper Zombie (📰):** His newspaper acts as armor. Once destroyed, he becomes enraged, moving and eating much faster.
*   **Football Zombie (👹):** An extremely fast and durable zombie that acts as a battering ram.
*   **Jack-in-the-Box Zombie (🤡):** Moves quickly and has a chance to explode, destroying plants in a 3x3 area.
*   **Dancing Zombie (🕺):** Periodically summons four Backup Dancers in surrounding tiles.
*   **Backup Dancer (💃):** A standard zombie spawned in groups by the Dancing Zombie.
*   **Zomboni (🚚):** A vehicle that crushes any plant it drives over and leaves a temporary, unplantable ice trail.
*   **Balloon Zombie (🎈):** Floats over most plants, making it immune to many standard attacks.
*   **Gargantuar (🗿):** A massive zombie that smashes plants in a single hit. Throws an Imp when heavily damaged.
*   **Giga-Gargantuar (👺):** A stronger, red-eyed version of the Gargantuar with immense health.
*   **Peashooter Zombie (🌱):** Carries a peashooter head and will stop to fire peas at your plants.
*   **Wall-nut Zombie (🥥):** Wears a Wall-nut as a helmet, giving it high health.
*   **Gatling Zombie (🔫):** An upgraded Peashooter Zombie that fires a burst of four peas.
*   **Tall-nut Zombie (🌰):** Wears a Tall-nut as armor, giving it extremely high health.
*   **Trash Can Zombie (🗑️):** His trash can acts as a durable shield, similar to a bucket.
*   **Octo Zombie (🐙):** Throws octopuses that wrap around your plants, disabling them temporarily.
*   **Giga-Football Zombie (⛑️):** A stronger, tougher version of the Football Zombie.
*   **Rally Zombie (🏴‍☠️):** A very fast and durable version of the Flag Zombie that appears on the final wave.

---

## 💻 Technologies Used

*   **HTML5** for structure
*   **CSS3** for layout & design
*   **JavaScript (ES6)** for game logic

## 📄 License

This project is released under the MIT License. Feel free to use, modify, and distribute.

## 🙏 Acknowledgments

Inspired by the beloved tower defense game *Plants vs. Zombies* by PopCap Games and the [original HTML game](https://github.com/plantsvszombiesjs/plantsvszombiesjs.github.io).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome