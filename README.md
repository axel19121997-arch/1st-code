Mini-RPG Project - Le Donjon de Naheulbeuk

Welcome to the repository of my very first video game project! This is a text-based mini-RPG with a graphical user interface (GUI), developed in Python and inspired by the crazy and humorous universe of the famous French audio saga *Le Donjon de Naheulbeuk*.

This project is part of my self-taught learning journey into programming, Python development, and Graphical User Interface (GUI) management.

---

# Current Features

* **Complete Character Creation:** Customize or randomly generate your character's gender, race (Human, Elf, Ogre, Dwarf, etc.), and class (Warrior, Mage, Minstrel, Shaman...).
* **Dynamic Stats System:** Core attributes (Courage, Strength, Intelligence, Agility) are directly influenced by your chosen class and equipped gear.
* **Procedural Exploration:** Progress through 20 randomly generated rooms featuring traps to dodge, wandering merchants, and magical fountains.
* **The Dungeon Tavern:** A rest event where you can spend your gold to restore your HP (Health Points) or Mana.
* **Turn-Based Combat:** Fight a diverse bestiary (from Smelly Rats to Cave Trolls) leading up to the mythical final boss battle against Zangdar.
* **Unique Skills & Spells:** Two special abilities per class, including a devastating ultimate skill that unlocks automatically upon reaching Level 2.
* **Loot & Inventory Management:** Open treasure chests containing weapons of varying rarities (Common, Rare, Legendary) that instantly modify your stats.
* **Text-Based RP Events:** Integrated humor and situational choices when encountering Orc patrols (featuring iconic battle cries).

---

# Visuals & Media

The game features dynamic image displays to mark the end of a playthrough. *Note: I am aware of a minor display bug regarding images and am currently working on a fix!*

* **`victoire.png`**: Proudly displayed when you defeat Zangdar and recover the twelfth Statuette of Gladeulfeurha.
* **`gameover.png`**: Displayed to honor the tragic demise of your party if your HP drops to zero.

>  **Important Note:** For images to render correctly within the interface, `victoire.png` and `gameover.png` must be placed in the exact same directory as the main Python script.

---

# Tech Stack

* **Language:** Python 3
* **Standard Libraries:** `tkinter` (GUI), `random`, `os`
* **Third-Party Library:** `Pillow` (PIL) for smooth PNG image processing and resizing.
* **Tools:** Git & GitHub for version control.

---

# How to Run the Project

To test the game on your local machine, follow these steps:

# Clone the repository
```bash
git clone [https://github.com/axel19121997-arch/1st-code.git](https://github.com/axel19121997-arch/1st-code.git)
cd 1st-code
2. Install dependencies
Rendering the end-game illustrations requires the Pillow library. Install it via your terminal:

Bash
pip install Pillow
3. Run the game
Launch the main script using Python:

Bash
python "Jeu final.py"
