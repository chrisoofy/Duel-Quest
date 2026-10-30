# Duel Quest

**Duel Quest is a fan-made recreation inspired by the duel-style mode of Mario Party.** It takes the head-to-head feel of a party-game showdown and turns it into a small, browser-playable adventure with dice rolls, board spaces, recruitable allies, and turn-based battles.

> This is an unofficial fan project made for learning and recreation. It is not affiliated with, endorsed by, or sponsored by Nintendo or the creators of Mario Party. Mario Party and related names and characters are the property of their respective owners.

## How to Play

1. Open `index.html` in a modern web browser.
2. Choose **1 Player vs CPU** or **2 Local Players**.
3. Select **Start / Restart Game** to begin.
4. Take turns using **Roll Dice & Move** to travel around the board.
5. Use the board spaces to collect coins, recruit allies, or earn rewards.
6. When the two rivals meet on the same space, a duel begins. Choose **Attack** to deal damage or **Defend** to reduce the next incoming hit.
7. Allies add to your team's attack power and take incoming damage before the leader.
8. Defeat the rival leader to win. Start a new game to play again.

## Features

- Two game modes: solo versus CPU and two local players.
- A dice-driven board with coin, partner, and duel spaces.
- Recruitable allies with their own health and attack values.
- Head-to-head battles with Attack and Defend actions.
- Team Status, an Adventure Board, and an Adventure Log.
- In-game rules and quick directions.
- A Game Check Lab with six automated checks for key game data and battle behavior.

## Project Files

- `index.html` — the game, styles, board, rules, and JavaScript logic in one file.

## Testing

Open the game and try both modes. Check that the board tokens move, space rewards work, allies can be recruited, battle actions alternate, allies take damage before the leader, and the winner is announced when a leader reaches 0 HP.

The **Run 6 Game Checks** button in the Game Check Lab checks the board space count, board positions, space types, ally data, team attack calculation, and ally-first damage behavior. These checks are helpful, but they do not replace playing through a complete game manually.

## Data and Progress

The game keeps its live state in JavaScript variables while the page is open. Progress is not saved to a database or persistent browser storage, so reloading the page or starting a new game resets the match.

## Credits and Disclaimer

Duel Quest is a fan-made recreation inspired by Mario Party's duel-style gameplay. It uses original project code and simple emoji-based visuals. It is intended for educational and entertainment purposes only. No official affiliation with Nintendo is claimed.
