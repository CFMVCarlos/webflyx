<div align="center">

# 📼 WebFlyx

**The Future of Online Entertainment & Content Distribution... on Floppy Disk!** 💾

[![Git](https://img.shields.io/badge/VCS-Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![Markdown](https://img.shields.io/badge/Format-Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://daringfireball.net/projects/markdown/)
[![Boot.dev](https://img.shields.io/badge/Curriculum-Boot.dev-orange?style=for-the-badge&logo=gnubash&logoColor=white)](https://www.boot.dev/)
[![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)](https://github.com/CFMVCarlos/webflyx)
[![Platform](https://img.shields.io/badge/Platform-Floppy%20Disk%203.5%22-blue?style=for-the-badge)](https://github.com/CFMVCarlos/webflyx)

<p align="center">
  <em>"You thought you knew what the web was capable of. You were <b>wrong</b>. Grab your copy at your local electronics store today!"</em>
</p>

</div>

---

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Repository Architecture](#repository-architecture)
- [Movie Catalog & Content](#movie-catalog--content)
  - [Classic Cinema Catalog](#classic-cinema-catalog)
  - [Featured Movie Titles](#featured-movie-titles)
  - [Iconic Quotes Archive](#iconic-quotes-archive)
- [Getting Started](#getting-started)
- [Author & Credits](#author--credits)

---

## Overview

**WebFlyx** is a retro-futuristic movie catalog repository developed as part of the **[Boot.dev](https://www.boot.dev/)** Git and Version Control curriculum. 

It combines the humorous lore of a 1980s/90s floppy-disk content distributor with real-world Git workflows—including multi-branch development, pull request merging, conflict management, structured tabular data (`classics.csv`), and strict file exclusion patterns via `.gitignore`.

---

## Key Features

- **📼 Retro Floppy Media Hub:** Curated catalog of vintage cinema favorites, cult classics, and drama masterpieces.
- **💬 Iconic Cinema Quotes:** Structured markdown collections capturing memorable lines from legendary Sci-Fi sagas (*Star Wars*, *Dune*).
- **🌿 Git Workflow Laboratory:** Practical demonstration of branch creation, pull request workflows, merge strategies, and clean commit history.
- **🛡️ Secure Hygiene & Privacy:** Strict `.gitignore` configurations preventing leakage of sensitive files (`secure/passwords.txt`), build artifacts (`advert.html`), and private data (`guilty_pleasures.md`).

---

## Repository Architecture

```text
webflyx/
├── .gitignore             # Exclusion rules for secrets, builds, and private files
├── README.md              # Project showcase and documentation
├── advert.md              # Marketing flyer for floppy disk distribution
├── classics.csv           # Structured database of 80s classic cinema
├── contents.md            # Master index of repository files
├── titles.md              # Curated list of acclaimed movie titles
├── quotes/                # Directory of cinematic dialogue archives
│   ├── dune.md            # Memorable quotes from the Dune universe
│   └── starwars.md        # Famous quotes from the Star Wars franchise
├── advert.html            # [Ignored] Compiled HTML flyer
├── guilty_pleasures.md    # [Ignored] Confidential guilty pleasure watchlist
└── secure/                # [Ignored] Encrypted / private credential storage
    └── passwords.txt      # [Ignored] Simulated sensitive password file
```

---

## Movie Catalog & Content

### Classic Cinema Catalog

Structured film dataset from [`classics.csv`](classics.csv):

| Title | Director | Year |
| :--- | :--- | :---: |
| **One Crazy Summer** | Savage Steve Holland | 1986 |
| **The Princess Bride** | Rob Reiner | 1987 |
| **The Goonies** | Richard Donner | 1985 |
| **The Breakfast Club** | John Hughes | 1985 |
| **Monty Python and the Holy Grail** | Terry Gilliam | 1975 |
| **Willow** | Ron Howard | 1988 |
| **Psycho** | Alfred Hitchcock | 1960 |

### Featured Movie Titles

Curated filmography from [`titles.md`](titles.md):

- 🎣 *A River Runs Through It*
- 🥊 *Fight Club*
- ⛓️ *12 Years a Slave*
- 📉 *The Big Short*
- 🐒 *12 Monkeys*
- ⏳ *The Curious Case of Benjamin Button*

### Iconic Quotes Archive

Cinematic dialogue archives located in [`quotes/`](quotes/):

#### 🌌 *Star Wars* ([`quotes/starwars.md`](quotes/starwars.md))
> *"May the Force be with you"*  
> *"I find your lack of faith disturbing"*  
> *"I am your father"*  
> *"Do or do not. There is no try"*  
> *"I've got a bad feeling about this"*

#### 🏜️ *Dune* ([`quotes/dune.md`](quotes/dune.md))
> *"May thy knife chip and shatter"*  
> *"A Great Man Doesn't Seek To Lead. He's Called To It."*  
> *"An Animal Caught In A Trap Will Gnaw Off Its Own Leg To Escape. What Will You Do?"*  
> *"When Is A Gift Not A Gift?"*  
> *"The spice must flow."*  
> *"Fear is the mind-killer."*

---

## Getting Started

### Clone & Explore

```bash
# Clone the repository
git clone https://github.com/CFMVCarlos/webflyx.git

# Navigate into the project directory
cd webflyx

# Check the branch history and commit log
git log --oneline --graph --all
```

---

## Author & Credits

- **Author:** Carlos Valente ([@CFMVCarlos](https://github.com/CFMVCarlos))
- **Learning Platform:** [Boot.dev](https://www.boot.dev/) — *Learn Git Course*
