# Mafia / Werewolf Game Roles Assignment

Welcome to the ** Mafia / Werewolf Game Roles Assignment Assistant**, a simple yet fun web-based tool designed for group activities or games where players need randomized roles! Perfect for party games, team-building exercises, or any scenario requiring quick, fair role distribution. Built with HTML, CSS, and JavaScript, this app runs entirely in your browser—locally or hosted on GitHub Pages—and is optimized for mobile use.

## Purpose

This game helps you assign roles to up to N players in a random, interactive way. Define your roles, customize them, and let players reveal their fates by tapping circles on the screen. Whether it’s "City," "Mafia,".

## Features

- **Role Customization**: Edit a list of roles with duplicates allowed (e.g., 3 Mafia, 7 Cities).
- **Random Assignment**: Hit "Start" to shuffle roles into 10 tappable circles.
- **Interactive Reveal**: Players tap a circle to see their assigned role—each circle is single-use.
- **Mobile-Friendly**: Designed for your iPhone (or any device) with responsive styling.
- **Persistent Roles**: Uses `localStorage` to save your edits between sessions.
- **Reset Option**: Revert to default roles with a single tap.
- **Offline Capable**: Runs locally from a single `index.html` file—no server needed.

## How to Play

1. **Open the Game**:
   - Locally: Save `index.html` to your iPhone’s Files app and open it in Chrome.
   - Online: Visit `https://pay632006.github.io/game/` (if deployed).

2. **Set Up Roles**:
   - View the role definitions (e.g., "Leader: Commands the team").
   - Edit the 10 roles in the input fields to match your game.

3. **Start the Game**:
   - Tap "Start" to hide the setup and display 10 circles.
   - Pass the phone around—each player taps a circle to reveal their role.

4. **Reset (Optional)**:
   - Tap "Reset to Defaults" to clear changes and revert to the original role list.

## Installation

### Local Use
1. Download `index.html` from this repository.
2. Transfer it to your iPhone (e.g., via email or AirDrop) and save to Files.
3. Open Files, tap `index.html`, and select "Copy to Chrome" from the Share menu.

### GitHub Pages
Deployed automatically via GitHub Actions:
- Repository: `<username>/<repository-name>`
- URL: `https://pay632006.github.io/game/`
- Workflow: See `.github/workflows/static.yml` for details.

## Requirements

- A modern browser (e.g., Chrome on iOS).
- No external dependencies—all CSS and JS are inline in `index.html`.

## Development

Built with:
- **HTML**: Structure and layout.
- **CSS**: Responsive styling for mobile screens.
- **JavaScript**: Role management, randomization, and interactivity.

To modify:
1. Clone the repo: `git clone https://github.com/pay632006/game.git`
2. Edit `index.html` in a text editor or IDE (e.g., VS Code with Cursor AI).
3. Push changes to `main` for auto-deployment.

## License

Feel free to use, modify, and share this game under the [MIT License](LICENSE) (or specify your preferred license).

---

Enjoy assigning roles and let the games begin!
