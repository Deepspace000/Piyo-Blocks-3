# Piyo Blocks 3 - Nus Version (fan prototype)

A single-player, touch-first homage to Big Pixel Studios' *Piyo Blocks* (iOS, 2009), rebuilt as one HTML file.

- Open `index.html` (or serve the folder) and tap PLAY.
- Modes: Piyo, Hyaku, Time Attack, 3 Second, Disco, Endless.
- Swap adjacent Piyos to line up 3+. You can keep swapping while blocks are still falling. Cascades build COMBOs.
- Points depend on how many Piyos go in one hit (3 = 30, 4 = 80, 5 = 150 ...) times the combo. The counters under the board stay blank until you capture that colour.
- Items: a glowing Piyo is a BOMB - match it and every Piyo of that colour explodes. A 4-match grows a WATERMELON in the cleared cell; tap it to blow up its 8 neighbours. DONUTS pop when a neighbour is captured (+5 s, +250). NINJAS (black) pop when a neighbour is captured (+500).
- BLOCKS: FOOD on the mode screen swaps the Piyos for strawberry, orange, lime, sushi, sapphire, diamond and amethyst. Same rules.
- Runs on iPhone and iPad: the canvas renders at native pixel density and the checkerboard fills the margins on wide screens.
- Installable on iOS/Android: open the hosted page in Safari/Chrome and choose "Add to Home Screen".
- `shots/` and the `?shot=` URL parameter are only for automated screenshots during development.
- Reference screenshots of the original are the `images*.jpg` files (not used by the game).
