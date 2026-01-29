# 🕉️ Ashoka's Path - Act 1: The Great Empire

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![GameJam](https://img.shields.io/badge/University%20of%20Aberdeen-GameJam%202026-orange)

**An interactive historical adventure game exploring the rise of Emperor Ashoka**

Created for the **University of Aberdeen GameJam 2026** | Theme: *"Traces of the Past"*

---

## 📖 About

**Ashoka's Path** is an educational text-based adventure game that brings ancient Indian history to life. Play as young Prince Ashoka in 272 BCE as he competes for succession to the Mauryan throne through a series of virtue-testing quests.

Based on authentic historical sources including the *Ashokavadana*, rock edicts, and accounts by Greek ambassador Megasthenes, the game combines engaging gameplay with real historical education.

###  What Makes This Special

- **Historically Accurate**: Every location includes real historical facts from ancient texts
- **Educational**: Learn about the Mauryan Empire, ancient India, and Emperor Ashoka's transformation
- **Complete Experience**: 5 quests, turn-based combat, music system, and tutorial
- **Accessible**: Comprehensive tutorial and help system for all skill levels

---

##  Features

### 🎮 Gameplay
- **5 Quest System**: Each quest tests a different virtue (compassion, wisdom, humility, strength, courage)
- **Turn-Based Combat**: Strategic battle system with training mode and boss fight
- **8 Unique Locations**: Explore Pataliputra Palace and surrounding areas
- **Dynamic NPCs**: Interact with historical characters and common people
- **Multiple Endings**: Success through virtue or death by hubris

###  Educational Content
- **Historical Lore**: Detailed historical information at every location
- **Authentic Sources**: Based on Ashokavadana, rock edicts, and Greek accounts
- **Cultural Context**: Learn about ancient Indian society, religion, and governance
- **Sanskrit Terms**: Introduced naturally (Jambudvipa, dharma, etc.)

###  Presentation
- **Visual Images**: Location artwork displayed in-game
- **Background Music**: 4 atmospheric tracks (menu, exploration, battle, victory)
- **Color-Coded Interface**: Easy-to-read terminal with syntax highlighting
- **Map System**: Visual palace map showing your location

###  User Experience
- **Complete Tutorial**: In-game guide explaining every command
- **Quest Tracking**: Monitor progress on all active quests
- **Dynamic Hints**: Mother provides context-aware guidance
- **Help System**: Quick reference available anytime

---

##  Historical Context

### Emperor Ashoka (304-232 BCE)

Ashoka the Great was the third emperor of the Mauryan Dynasty who ruled nearly all of the Indian subcontinent from 268-232 BCE. His transformation from a violent conqueror to a compassionate Buddhist ruler makes him one of history's most remarkable figures.

**Key Historical Elements in the Game:**

- **The Ashokavadana** (2nd century CE Buddhist text chronicling Ashoka's life)
- **Rock Edicts** (Ashoka's inscribed declarations, still visible today)
- **Pataliputra** (Capital city, modern-day Patna, one of the largest ancient cities)
- **Mauryan Empire** (322-185 BCE, controlled most of South Asia)
- **Kalinga War** (Referenced in Act 1, central to Act 2)

---

##  Installation

### Prerequisites

```bash
Python 3.8 or higher
pip (Python package manager)
```

### Required Packages

```bash
pip install pillow pygame
```

Or using the requirements file:

```bash
pip install -r requirements.txt
```

### Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/ashokas-path.git
cd ashokas-path

# Install dependencies
pip install -r requirements.txt

# Run the game
python ASHOKA_ACT1_COMPLETE.py
```

---

##  How to Play

### Starting the Game

1. Run the game: `python ASHOKA_ACT1_COMPLETE.py`
2. Answer the opening riddle (hint: think about power)
3. Type `tutorial` for complete instructions
4. Type `help` for quick command reference

### Basic Commands

```
Movement:        north (n), south (s), east (e), west (w)
Information:     look (l), inventory (i), quest (q), map (m)
Interaction:     talk to <npc>, lore, tutorial
Combat:          train combat (at stables)
Audio:           music (toggle), volume <0-100>
```

### The Five Sacred Items

Collect these items to prove your worth:

1. **Golden Bowl** - Earn through compassion (Marketplace)
2. **Imperial Elephant** - Earn through understanding (Royal Stables)
3. **Sacred Soma** - Earn through wisdom (Temple District)
4. **Honey Cakes** - Earn through humility (Palace Kitchen)
5. **Royal Cushion** - Earn through courage (Throne Room)

 **Warning**: Entering the Throne Room with fewer than 4 items results in death!

---

## 🗺️ Game Map

```
                    [Throne Room]
                          |
    [Garden]------[Palace Courtyard]------[Stables]
                          |                    |
                    [Mother's]            [Marketplace]
                          |                    |
                     [Kitchen]             [Temple]
```

---

##  Combat System

### Turn-Based Battles

**Actions:**
- **[1] Attack** - Standard attack (15-25 damage)
- **[2] Defend** - Guard next attack (50% reduction)
- **[3] Power Attack** - Heavy strike (25-35 damage, 30% miss)
- **[4] Heal** - Restore 25 HP (3 uses per battle)

**Battles:**
- **Training Battle** (Optional) - Practice safely at Royal Stables
- **Boss Battle** (Required) - Defeat Brother Susima for final item

---

##  Music & Audio

### Music Tracks

The game includes 3 atmospheric music tracks:

- **Menu Music** - Opening riddle scene
- **Exploration Music** - Palace wandering (loops)
- **Battle Music** - Combat encounters (loops)


### Audio Setup

1. Create a `music` folder in the game directory
2. Add these MP3 files:
   - `menu.mp3`
   - `exploration.mp3`
   - `battle.mp3`
   - `victory.mp3`

**Controls:**
- `music` - Toggle music on/off
- `volume <0-100>` - Adjust volume

**Note**: Game works perfectly without music files!

---

## 📁 Project Structure

```
ashokas-path/
├── ASHOKA_ACT1_COMPLETE.py    # Main game file
├── requirements.txt            # Python dependencies
├── README.md                   # This file
│
├── images/                     # Location artwork (optional)
│   ├── palace_courtyard.png
│   ├── mothers_chambers.png
│   ├── palace_kitchen.png
│   ├── garden_pavilion.png
│   ├── royal_stables.png
│   ├── marketplace.png
│   ├── temple_district.png
│   ├── fathers_chambers.png
│   ├── coronation.png
│   └── map.png
│
└── music/                      # Background music (optional)
    ├── menu.mp3
    ├── exploration.mp3
    ├── battle.mp3
    └── victory.mp3
```

---

##  Quest Walkthroughs

### Quest 1: Golden Bowl (Beggar)
```
Location: Marketplace
1. talk to beggar
2. talk to vikram
3. help vikram
4. talk to beggar
✓ Reward: Golden Bowl
```

### Quest 2: Imperial Elephant (Airavata)
```
Location: Royal Stables
1. talk to radhagupta
2. test elephant
3. feed hay
4. remove thorn
5. comfort elephant
✓ Reward: Imperial Elephant
```

### Quest 3: Sacred Soma (Ritual)
```
Location: Temple District
Requirement: Must have Golden Bowl first!
1. talk to priest
2. ritual
3. Answer truth questions (any answer works)
✓ Reward: Soma
```

### Quest 4: Honey Cakes (Cooking)
```
Location: Palace Kitchen
1. talk to amma
2. learn cooking
3. Type: 1 2 3 4 5
4. make cakes
✓ Reward: Honey Cakes
```

### Quest 5: Royal Cushion (Susima)
```
Location: Throne Room
Requirement: Must have 4+ items first!
1. Collect 4 items
2. Navigate north to Throne Room
3. Defeat Brother Susima in combat
4. pick cushion
✓ Reward: Royal Cushion
```

### Final Victory
```
1. Collect all 5 items
2. Go to Garden of Golden Pavilion
3. talk to ascetic
✓ Victory! Act 1 Complete!
```

---

##  GameJam Information

**Event**: University of Aberdeen GameJam 2026  
**Theme**: "Traces of the Past"  
**Duration**: 1 week (50-60 hours development)  
**Category**: Solo Developer  
**Focus**: Historical accuracy + engaging gameplay

---

##  Technical Details

### Built With

- **Python 3.8+** - Core game logic
- **Tkinter** - GUI framework (included with Python)
- **Pillow (PIL)** - Image processing and display
- **Pygame** - Audio/music system

### Architecture

- **Object-Oriented Design**: GameState class manages all game state
- **Event-Driven**: Command processing with dynamic responses
- **Modular System**: Quests, combat, music, and UI separated
- **Data-Driven**: Locations and NPCs defined in dictionaries

---

##  Educational Resources

### Historical Sources Referenced

1. **Ashokavadana** (2nd century CE) - Buddhist text on Ashoka's life
2. **Rock Edicts** - Ashoka's inscribed declarations (still exist!)
3. **Megasthenes' Indica** - Greek ambassador's account of Mauryan India
4. **Arthashastra** - Ancient Indian treatise on statecraft by Chanakya
5. **Archaeological Evidence** - From Pataliputra excavations

### Further Reading

- *Ashoka: The Search for India's Lost Emperor* by Charles Allen
- *The Edicts of King Ashoka* (translations available online)
- *Ancient India: From the Earliest Times to the First Century AD* by Romila Thapar
- UNESCO World Heritage Sites: Sanchi Stupa (Ashoka's monuments)

---

##  Credits

### Development

**Solo Developer**: Aryan Batheja  
**Role**: Programming, Game Design, Narrative, Historical Research

### Special Thanks

- University of Aberdeen GameJam 2026
- Ancient Indian historians and archaeologists
- Buddhist scholars who preserved the Ashokavadana
- Archaeological Survey of India

---

##  Future Development

### Act 2: The Sword That Shaped the Continent (Planned)

- Ashoka's military campaigns
- The Kalinga War (bloodiest battle in ancient India)
- Moral crisis and transformation
- Introduction to Buddhism

### Act 3: The Dharma That Changed the World (Planned)

- Ashoka's conversion to Buddhism
- Peaceful governance and reforms
- Spreading dharma across Asia
- Legacy and rock edicts

---

##  Contributing

This is a GameJam project, but suggestions and feedback are welcome!

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

##  License

This project is licensed under the MIT License.

```
MIT License

Copyright (c) 2026 Aryan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

##  Contact

**Developer**: Aryan  
**University**: University of Aberdeen  
**Event**: GameJam 2026

**Project Link**: [https://github.com/yourusername/ashokas-path](https://github.com/yourusername/ashokas-path)

---



## 💬 FAQ

**Q: Do I need images to play?**  
A: No! The game displays text placeholders if images are missing.

**Q: Do I need music files?**  
A: No! The game works perfectly without music.

**Q: How historically accurate is this?**  
A: The game is based on authentic ancient sources. Some dramatization for gameplay, but core facts are accurate.

**Q: Will there be Act 2 and Act 3?**  
A: Planned! Act 2 will cover the Kalinga War and Ashoka's transformation.

**Q: Can I use this for my school project?**  
A: Absolutely! Just credit the source.

---

<div align="center">

## 🕉️ Thank You for Playing!

**May dharma guide your path.**

*"All men are my children. Just as I seek the welfare and happiness of my own children,  
I seek the same for all men." - Emperor Ashoka, Rock Edict XIII*

---

⭐ **Star this repo** if you enjoyed the game!  
📚 **Share** to spread knowledge of ancient Indian history!  
🎮 **Play** and experience the rise of one of history's greatest emperors!

</div>

---

**Made with ❤️ for the University of Aberdeen GameJam 2026**

*Bringing ancient history to life through interactive storytelling* 🎸🕉️
