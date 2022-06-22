# Basic Frogger HTML and JavaScript Game

This is a basic implementation of the Konami Frogger game, but it's missing a few things intentionally and they're left as further exploration for the reader.

<img width="300" height="301" alt="" src="https://user-images.githubusercontent.com/2433219/94889236-b4077780-0438-11eb-8f0e-616f8e13fc8d.png">

## Further Exploration

- Lives
  - Frogger starts with 6 lives and should lose a life whenever it is hit by a vehicle or lands in the water
- Timer
  - The player has 30 seconds to get Frogger to the end bank. Display the timer as a reverse progress bar
  - Timer resets when player gets to the end bank or dies
- Score
  - Each time Frogger makes it to the end bank it should score points according to a few factors (see https://en.wikipedia.org/wiki/Frogger#Scoring). Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the score to the screen
  - Every 20,000 should award another life
- Mobile and touchscreen support
  - Allow the game to be scaled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
  
**Important note:** I will answer questions about the code but will not add more features or answer questions about adding more features. This series is meant to give a basic outline of the game but nothing more.
  
## License

(CC0 1.0 Universal) You're free to use this game and code in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but appreciated.

## Other Basic Games

- [Snake](https://gist.github.com/straker/ff00b4b49669ad3dec890306d348adc4)
- [Pong](https://gist.github.com/straker/81b59eecf70da93af396f963596dfdc5)
- [Breakout](https://gist.github.com/straker/98a2aed6a7686d26c04810f08bfaf66b)
- [Tetris](https://gist.github.com/straker/3c98304f8a6a9174efd8292800891ea1)
- [Bomberman](https://gist.github.com/straker/769fb461e066147ea16ac2cb9463beae)
- [Missile Command](https://gist.github.com/straker/afc4e2a30b6df772a5f9f6ef01751d41)
- [Sokoban](https://gist.github.com/straker/2fddb507d4bb6bec54ea2fdb022d020c)
- [Doodle Jump](https://gist.github.com/straker/b96a4a68bd6d79cf75a833d98a2b654f)
- [Puzzle Bobble](https://gist.github.com/straker/afc5bedc7f4b4bc65ba8b05c435f6d32)
- [Helicopter](https://gist.github.com/straker/0d25ae9d235f6a62f8287fd36a097043)

## Support

Basic HTML Games are made possible by users like you. When you become a [Patron](https://www.patreon.com/straker), you get access to behind the scenes development logs, the ability to vote on which games I work on next, and early access to the next Basic HTML Game.

### Top Patrons

- Karar Al-Remahy
- UnbrandedTech