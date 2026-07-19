# Marshmallow Puzzle

A colorful three-stage match-3 browser game built with HTML, CSS, JavaScript, ChatGPT, and Codex.

Marshmallow Puzzle began with a simple idea inspired by watching a child eat cereal with milk. That everyday moment became a soft, playful puzzle game featuring marshmallow characters, combo scoring, stage progression, cookie obstacles, and ice blocks.

## Live Demo

Add your published game URL here.

```text
https://YOUR-USERNAME.github.io/marshmallow-puzzle/
```

## Project Overview

Players select a marshmallow block and swap it with an adjacent block.

When three or more marshmallows of the same flavor are matched, they disappear, the score increases, and new blocks fall from the top to fill the empty spaces.

The game contains three stages:

- **Stage 1:** Classic marshmallow matching
- **Stage 2:** Cookie obstacles that break when a nearby match is cleared
- **Stage 3:** Ice obstacles that require two nearby hits before breaking

Each stage provides 20 moves.

## Main Features

- Three-stage match-3 gameplay
- 20 moves per stage
- Score and best-score tracking
- Combo scoring
- Falling-block animations
- Cookie and ice obstacle mechanics
- Stage-clear and final-result screens
- Play Again and Home options
- Sound on/off control
- Responsive desktop and mobile layout
- Best score saved with Local Storage
- Single-file browser game

## How to Play

1. Select a marshmallow block.
2. Select an adjacent block to swap it.
3. Match three or more marshmallows of the same flavor.
4. Create chain reactions to earn combo points.
5. Complete all three stages before the game ends.

## Stage Rules

### Stage 1: Classic Match

Match marshmallow blocks and earn as many points as possible.

### Stage 2: Cookie Challenge

Cookie blocks cannot be moved.

Clear marshmallow matches beside a cookie block to remove it.

### Stage 3: Ice Challenge

Ice blocks cannot be moved.

Each ice block must be hit twice by nearby matches before it breaks.

## Built With

- HTML5
- CSS3
- JavaScript
- Local Storage
- ChatGPT
- Codex

## AI-Assisted Development

ChatGPT and Codex were used to support the development process, including:

- Structuring the match-3 game logic
- Implementing block swapping and match detection
- Building stage transitions
- Creating cookie and ice obstacle mechanics
- Improving responsive behavior
- Adding score and combo feedback
- Testing and fixing interaction bugs
- Refining visual design and animations

AI tools helped accelerate implementation, but the project still required repeated planning, testing, visual review, and product decisions.

## Development Process

The project was created through short iterative cycles:

1. Define a feature
2. Implement it
3. Test the interaction
4. Identify logic or visual issues
5. Request a focused correction
6. Test again

This process was especially important for:

- Preventing the board from shifting when a block was selected
- Fixing stage transitions
- Keeping the completed board visible behind result popups
- Improving cookie and ice designs
- Making blocks fall naturally from the top
- Separating Play Again and Home behaviors

## Project Structure

This project is currently packaged as a single HTML file.

```text
marshmallow-puzzle/
├── index.html
└── README.md
```

The HTML file contains all styles and JavaScript logic, so no build process is required.

## Run Locally

1. Download the project.
2. Rename the final HTML file to `index.html`.
3. Open `index.html` in Chrome, Edge, or another modern browser.

No installation or server is required.

## Deploy with GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html` and `README.md`.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and `/root`.
6. Save and wait for the deployment URL.

## Challenges

Key challenges included:

- Preventing layout movement during block selection
- Managing stage completion and next-stage transitions
- Resetting the game correctly after Play Again
- Returning to the title screen with Home
- Preserving the finished board behind result overlays
- Making new blocks fall instead of appearing instantly
- Designing obstacles that felt consistent with the marshmallow theme
- Balancing the difficulty of cookie and ice stages

## What I Learned

This project showed that AI coding tools are most useful when requirements are clear and changes are requested in small, testable steps.

I also learned that successful AI-assisted development still depends on:

- Product planning
- UI/UX judgment
- Repeated browser testing
- Clear state management
- Careful visual refinement
- Player-focused feedback

## Future Improvements

- Stage mission counters
- Additional obstacle types
- Special power-up blocks
- Sound effects and background music
- Difficulty settings
- Daily challenges
- Touch gestures for mobile
- Accessibility options
- Online leaderboards
- AI-generated stage layouts

## OpenAI Build Week

This project was prepared as an entry for OpenAI Build Week.

It demonstrates how a product planner with a UI/UX background can use AI coding tools to turn a small everyday idea into a complete playable browser game.

## License

This project is for demonstration and hackathon submission purposes.

You may add an MIT License later if you want others to reuse or modify the code. 
