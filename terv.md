# AI in Videogames — Website Plan

## Overview

A one-page informational website about artificial intelligence in videogames, built with HTML5 and Bootstrap 5. The site covers the history, techniques, examples, and future of game AI in a clean, responsive layout.

---

## Content Sections

1. **Hero** — Full-width header with title, tagline, and call-to-action button.
2. **History** — Brief timeline of AI milestones in gaming (Pac-Man, GoldenEye, FEAR, etc.).
3. **Core Techniques** — Cards explaining FSM, Behavior Trees, A* Pathfinding, Utility AI, GOAP.
4. **Notable Examples** — NPC behavior, enemy tactics, procedural generation, dynamic difficulty adjustment.
5. **Modern Trends** — Machine learning, reinforcement learning, LLM-driven dialogue, procedural content generation.
6. **Future Outlook** — Speculative look at where game AI is heading.

---

## Wireframe

```
┌──────────────────────────────────────────────────────┐
│                     Navbar                           │
│  Brand  |  Home  |  History  |  Techniques  |  ...  │
├──────────────────────────────────────────────────────┤
│                                                       │
│                  Hero Section                         │
│          "AI in Videogames"                           │
│      subtitle  +  [Explore] button                    │
│                                                       │
├──────────────────────────────────────────────────────┤
│ ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────┐ │
│ │ History  │  │Techniques│  │ Examples │  │Future│ │
│ │  card    │  │   card   │  │   card   │  │ card │ │
│ └──────────┘  └──────────┘  └──────────┘  └──────┘ │
├──────────────────────────────────────────────────────┤
│   ┌──────┐  ┌───────────────────────────────┐       │
│   │ img  │  │ Deep-dive section (text)      │       │
│   └──────┘  └───────────────────────────────┘       │
│   ┌───────────────────────────────┐  ┌──────┐       │
│   │ Deep-dive section (text)      │  │ img  │       │
│   └───────────────────────────────┘  └──────┘       │
├──────────────────────────────────────────────────────┤
│                Footer                                │
│          links  |  credit  |  © 2026                 │
└──────────────────────────────────────────────────────┘
```

---

## File Structure

```
projekt/
├── index.html           Main website page
├── style.css            Custom CSS overrides
├── ai-in-videogames.md  This plan document
└── assets/
    └── images/          Images used on the site
```

---

## Tech Stack

| Layer    | Choice       |
| -------- | ------------ |
| Markup   | HTML5        |
| Styling  | Bootstrap 5 (CDN) + custom CSS |
| Layout   | Bootstrap Grid (container, row, col) |
| Icons    | Bootstrap Icons (CDN) |
| Font     | System font stack |
| Hosting  | Static (any)  |

---

## Responsive Breakpoints

- **Mobile** (< 768px): stacked cards, single-column layout.
- **Tablet** (768px–992px): two-column card grid.
- **Desktop** (> 992px): four-column card grid, side-by-side deep-dive sections.
