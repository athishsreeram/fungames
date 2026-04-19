# 🎮 Game World! — Fun Zone for Toddlers, Kids & Trendy Gamers

Welcome to **Game World!** — a colorful, interactive web-based game portal packed with 7 original mini-games plus external links to classic learning activities. Designed with care for toddlers (1–4), kids (5+), and fast‑paced “trending” games, the portal features a playful UI, category filters, modal popups, and parent tips.

![Game World Preview](https://via.placeholder.com/800x400?text=Game+World+Demo)  
*(Replace with a screenshot of your live project)*

https://athishsreeram.github.io/fungames/index.html

---

## ✨ Features

- **Three age‑appropriate categories**  
  👶 Toddler (1–4) – simple, gentle, no timers  
  🧒 Kids (5+) – phonics, drawing, numbers, tic‑tac‑toe  
  🔥 Trending – reaction, stacking, typing challenges

- **Interactive Filter Bar** – instantly show/hide games by category.

- **Modal Game Player** – embedded games open in a smooth modal; external links open in the same tab.

- **Parent Tips** – for toddler games, a helpful tip appears inside the modal, inspired by real‑world play and early learning methods.

- **Engaging Sound Feedback** – gentle tones for correct/wrong actions (Web Audio API).

- **Fully Responsive** – works on desktop, tablet, and mobile devices.

---

## 🕹️ Included Games

| Game | Category | Description |
|------|----------|-------------|
| **Color Hunt** | Toddler | Tap all dots that match the target color. No timers, just fun! |
| **Quiet Box** | Toddler | Pop floating bubbles and falling stars. Calming & gentle. |
| **Animal Match Up** | Toddler | Tap the animal that matches the picture. Great for learning. |
| **Shape Sorter** | Toddler | Drag each shape into its matching slot. Simple & satisfying. |
| **Tap to Stack** | Trending | Tap at the perfect moment to stack blocks. How high can you go? |
| **Reaction Click** | Trending | Click the moment the screen turns green. Test your reaction speed. |
| **Speed Typing** | Trending | Type the word before time runs out. Great for older kids. |
| ABC Phonics | Kids (external) | Learn letters and sounds through phonics play. |
| Drawing Time | Kids (external) | A virtual canvas to draw anything you imagine. |
| Number Fun | Kids (external) | Count, learn numbers, and practice maths. |
| Tic Tac Toe! | Kids (external) | Two‑player X’s and O’s on a classic grid. |


🎮 Complete 82 Game Specifications
--------------------------------------------------------------------------------
🧩 Game #1: Cuddle Zoo (Kids version of Sudoku)
File name: cuddle-zoo.html
Category: Kids (5+)
Description: Drag the baby animals into the empty pens. Each row and column must have one of each animal – no repeats!
Mapping to original: Replaces numbers 1-4 with 4 animal emojis (🐘, 🦒, 🐧, 🐨) on a 4×4 grid; preserves row and column uniqueness rule.
--------------------------------------------------------------------------------
🐛 Game #2: Wiggly Worm Home (Toddler version of Mazes)
File name: wiggly-worm-home.html
Category: Toddler (1-4)
Description: Help the hungry worm wiggle through the dirt to reach the juicy apple! Drag your finger to draw the path.
Parent Tip: "Say: Where is the apple? Can you help the worm find its snack? Let's follow the path together!"
Mapping to original: Replaces complex maze navigation with simple single-path tracing; large touch targets; no time pressure.
--------------------------------------------------------------------------------
🐰 Game #3: Sleeping Bunnies (Toddler version of Two Not Touch / Star Battle)
File name: sleeping-bunnies.html
Category: Toddler (1-4)
Description: Help the sleepy bunnies find their cozy beds! No two bunnies can touch each other - even sideways!
Parent Tip: "Say: Each bunny needs its own space! Tap a square to give a bunny a bed. Make sure bunnies aren't next to each other - they need their beauty sleep!"
Mapping to original: Replaces Star Battle (2 stars per row/col/region) with simple 4x4 grid where each row/column can have only 1 bunny, and no two bunnies can touch (including diagonally).
--------------------------------------------------------------------------------
🍋 Game #4: Hide and Squeak (Toddler version of Lime Sudoku / Minesweeper + Sudoku)
File name: hide-and-squeak.html
Category: Toddler (1-4)
Description: Little mice are hiding under the flowers! Tap a flower to see if a mouse is hiding there. The numbers tell you how many mice are nearby!
Parent Tip: "Say: The number 2 means two mice are hiding next to this flower! Can you find them without poking the wrong flowers?"
Mapping to original: Replaces Minesweeper numbers with simple 1-3 counts on a 4x4 grid; numbers indicate adjacent hidden mice; no flags needed.
--------------------------------------------------------------------------------
🌉 Game #5: Frog Leap Logs (Toddler version of Bridges / Hashiwokakero)
File name: frog-leap-logs.html
Category: Toddler (1-4)
Description: Help the frogs cross the pond! Draw bridges between lily pads so every frog can visit its friend. No jumping over other bridges!
Parent Tip: "Say: Each lily pad has a number - that's how many bridges it needs! Draw lines to connect them. Frogs love bridges!"
Mapping to original: Replaces numbered islands with 2x2 or 3x3 lily pads (numbers 1-3); bridges are simple straight lines; no diagonal or crossing bridges.
--------------------------------------------------------------------------------
🐼 Game #6: Panda Pairs (Kids version of Binox / Binairo)
File name: panda-pairs.html
Category: Kids (5+)
Description: Fill the grid with black and white pandas! No more than two same pandas in a row, and each row/column has the same number of each color.
Mapping to original: Replaces 0/1 binary with panda emojis (🐼⚪) on 6x6 grid; preserves no-three-in-a-row and equal counts rules.
--------------------------------------------------------------------------------
🐍 Game #7: Snake Snacks (Toddler version of Slitherlink)
File name: snake-snacks.html
Category: Toddler (1-4)
Description: Draw one long, wiggly snake that loops around! The numbers tell you how many snake pieces are next to each apple.
Parent Tip: "Say: The snake is hungry! Each number tells you how many apple pieces are touching that square. Draw one big loop!"
Mapping to original: Replaces numbers 0-3 with simple 1-2 clues on 4x4 grid; snake is a single continuous loop; no branches.
--------------------------------------------------------------------------------
🚂 Game #8: Choo-Choo Path (Toddler version of Train Tracks)
File name: choo-choo-path.html
Category: Toddler (1-4)
Description: Build a train track from the station to the toy store! Drag the tracks to make a path. The numbers tell you how many tracks go in each row!
Parent Tip: "Say: Choo choo! Can you connect the train station to the toy store? The numbers help you know where to put the tracks!"
Mapping to original: Replaces complex track puzzles with simple 4x4 grid; start and end points fixed; numbers indicate track count per row/col.
--------------------------------------------------------------------------------
🍝 Game #9: Spaghetti Wiggles (Toddler version of Vermicelli / Simple Loop)
File name: spaghetti-wiggles.html
Category: Toddler (1-4)
Description: Draw one long spaghetti noodle that visits every plate! The noodle can't cross itself or make branches.
Parent Tip: "Say: One long noodle, no breaks! Draw a line that touches every plate and comes back to the start. No crossing!"
Mapping to original: Replaces complex loop puzzles with simple 4x4 grid; single continuous loop visiting all cells; no intersections.
--------------------------------------------------------------------------------
🍈 Game #10: Tickle the Limes (Toddler version of Limesweeper)
File name: tickle-the-limes.html
Category: Toddler (1-4)
Description: Some limes are hiding under leaves! Tap a leaf to tickle a lime. The numbers tell you how many limes are hiding nearby.
Parent Tip: "Say: The number 3 means three limes are hiding next to this leaf! Can you find them all? No need to rush!"
Mapping to original: Replaces Minesweeper with 4x4 grid; numbers 1-3 indicate adjacent hidden limes; no flags, just tapping.
--------------------------------------------------------------------------------
🥟 Game #11: Soup Dumpling Match (Kids version of Dumplings)
File name: soup-dumpling-match.html
Category: Kids (5+)
Description: Fill the steamer basket with all the flavors of soup dumplings! Each row, column, and colored shape must have one of each flavor.
Mapping to original: Replaces numbers with dumpling flavors (pork, chicken, shrimp, veggie) on 4x4 grid with colored regions; each region must have all flavors.
--------------------------------------------------------------------------------
🦁 Game #12: Friendly Sum Forest (Kids version of Killer Sudoku)
File name: friendly-sum-forest.html
Category: Kids (5+)
Description: The animals in each fenced area add up to a special number! Fill the grid so each row and column has one of each animal.
Mapping to original: Replaces Killer Sudoku cages with colored animal families; numbers 1-4 in 4x4 grid; cage sums shown as target numbers.
--------------------------------------------------------------------------------
🍪 Game #13: Number Bakery (Kids version of Inkies / Calcudoku)
File name: number-bakery.html
Category: Kids (5+)
Description: Bake cookies in the number bakery! Each row and column has numbers 1-4. The math clues tell you how to combine the cookies in each shape!
Mapping to original: Replaces Calcudoku cages with simple addition/subtraction clues on 4x4 grid; numbers 1-4 each row/col.
--------------------------------------------------------------------------------
🧩 Game #14: Block Buddies (Kids version of Suguru / Tectonics)
File name: block-buddies.html
Category: Kids (5+)
Description: Fill each shape with numbers 1 to (size of shape). Same numbers can't touch each other - even diagonally!
Mapping to original: Replaces Suguru with 4x4 grid divided into 4-5 regions; numbers 1-4 in each region; no touching same numbers.
--------------------------------------------------------------------------------
👑 Game #15: Castle Queens (Kids version of 7 Queens)
File name: castle-queens.html
Category: Kids (5+)
Description: Place 4 queens on the chessboard so no two queens can see each other! Queens can move up, down, sideways, and diagonally.
Mapping to original: Replaces 7-queens with simpler 4x4 board; 4 queens; no two share row, column, or diagonal.
--------------------------------------------------------------------------------
🔢 Game #16: Number Crossword Jr (Kids version of Kakuro / Cross Sums)
File name: number-crossword-jr.html
Category: Kids (5+)
Description: Fill the empty squares with numbers that add up to the clues! Like a crossword puzzle, but with numbers instead of letters.
Mapping to original: Replaces Kakuro with 4x4 grid; simple addition clues; numbers 1-4 only.
--------------------------------------------------------------------------------
🔬 Game #17: Mystery Lab (Kids version of Krazydad Labs)
File name: mystery-lab.html
Category: Kids (5+)
Description: Mix and match strange ingredients in the mystery lab! Follow the secret rules to complete each experiment.
Mapping to original: Replaces experimental puzzles with rotating set of 4 simple mini-games (pattern matching, color mixing, shape sorting).
--------------------------------------------------------------------------------
🐍 Game #18: Wiggly Snakes (Kids version of Variety Slitherlink)
File name: wiggly-snakes.html
Category: Kids (5+)
Description: Draw loops around the garden for the wiggly snakes! Different colored snakes have different rules.
Mapping to original: Replaces variety slitherlink with 6x6 grid; includes loop, path, and multiple-snake variations.
--------------------------------------------------------------------------------
🦒 Game #19: Tiny Zoo (Toddler version of Kidoku)
File name: tiny-zoo.html
Category: Toddler (1-4)
Description: Help the baby animals find their homes in the tiny zoo! Each row and column has one of each animal.
Parent Tip: "Say: The elephant, giraffe, penguin, and koala all need a home. Can you put one in each row and column?"
Mapping to original: Replaces 4x4 Sudoku with 2x2 or 3x3 grid for youngest children; only 4 animals; visual matching.
--------------------------------------------------------------------------------
🥧 Game #20: Easy Number Bakery (Toddler version of Beginner Inkies)
File name: easy-number-bakery.html
Category: Toddler (1-4)
Description: Bake cookies with addition and subtraction! Each row and column has numbers 1-3. The clues help you add or subtract.
Parent Tip: "Say: The clue '2+' means two cookies add up to that number! Let's find the right numbers together."
Mapping to original: Replaces Beginner Inkies with 3x3 grid; only addition and subtraction; numbers 1-3.
--------------------------------------------------------------------------------
🐍 Game #21: Baby Snake (Toddler version of Easy Slitherlinks)
File name: baby-snake.html
Category: Toddler (1-4)
Description: Draw a tiny snake that loops around the garden! The numbers tell you how many snake pieces are nearby.
Parent Tip: "Say: The snake is very small! Just draw a circle that touches the numbered apples."
Mapping to original: Replaces Easy Slitherlink with 3x3 grid; numbers 0-2 only; single simple loop.
--------------------------------------------------------------------------------
💇 Game #22: Hair Salon (Kids version of Split Ends)
File name: hair-salon.html
Category: Kids (5+)
Description: Don't let the hair colors line up! Color each strand so no two matching colors touch in a straight line.
Mapping to original: Replaces Split Ends with 4x4 grid; 3 colors; no three in a row horizontally, vertically, or diagonally.
--------------------------------------------------------------------------------
🧩 Game #23: Puzzle Zoo (Kids version of Jigsaw Sudoku)
File name: puzzle-zoo.html
Category: Kids (5+)
Description: Each puzzle piece shape must have one of each animal! Plus each row and column too.
Mapping to original: Replaces Jigsaw Sudoku with 4x4 grid; irregular shaped regions (jigsaw pieces); animals instead of numbers.
--------------------------------------------------------------------------------
⭐ Game #24: Star Sudoku (Kids version of X Sudoku)
File name: star-sudoku.html
Category: Kids (5+)
Description: Fill the grid so each row, column, AND both long diagonals have one of each animal!
Mapping to original: Replaces X Sudoku with 4x4 grid; adds diagonal constraints; animals instead of numbers.
--------------------------------------------------------------------------------
🔴⚪ Game #25: Dot Friends (Kids version of Kropki Sudoku)
File name: dot-friends.html
Category: Kids (5+)
Description: White dots mean numbers are neighbors (like 2 and 3). Black dots mean one number is double the other!
Mapping to original: Replaces Kropki dots with simple rules on 4x4 grid; white dot = consecutive numbers; black dot = double.
--------------------------------------------------------------------------------
👫 Game #26: Number Neighbors (Kids version of Consecutive Sudoku)
File name: number-neighbors.html
Category: Kids (5+)
Description: Little bars between cells mean the numbers are neighbors (like 2 and 3)! Fill the grid with animals 1-4.
Mapping to original: Replaces Consecutive Sudoku with 4x4 grid; bars indicate consecutive numbers; animals instead of numbers.
--------------------------------------------------------------------------------
🥪 Game #27: Sandwich Shop (Kids version of Sandwich Sudoku)
File name: sandwich-shop.html
Category: Kids (5+)
Description: The numbers outside tell you how many toppings are between the 1 and 4 in that row! Make perfect sandwiches.
Mapping to original: Replaces Sandwich Sudoku with 4x4 grid; clues indicate count of numbers between 1 and 4.
--------------------------------------------------------------------------------
🏙️ Game #28: Building Blocks (Kids version of Skyscraper Sudoku)
File name: building-blocks.html
Category: Kids (5+)
Description: Build skyscrapers of different heights! The numbers outside tell you how many buildings you can see from that side.
Mapping to original: Replaces Skyscraper Sudoku with 4x4 grid; numbers 1-4 as building heights; clues from edges.
--------------------------------------------------------------------------------
⚓ Game #29: Pirate Ships (Kids version of BattleShips)
File name: pirate-ships.html
Category: Kids (5+)
Description: Find the hidden pirate ships! The numbers tell you how many ship pieces are in each row and column.
Mapping to original: Replaces BattleShips with 5x5 grid; ships of sizes 1,2,3; simple clues.
--------------------------------------------------------------------------------
💡 Game #30: Light the Way (Toddler version of Akari / Light-up)
File name: light-the-way.html
Category: Toddler (1-4)
Description: Place lanterns to light up all the dark squares! The numbers tell you how many lanterns are next to each stone.
Parent Tip: "Say: The number 2 means two lanterns go next to this rock! Lanterns shine up, down, left, and right."
Mapping to original: Replaces Akari with 4x4 grid; numbers 0-3; lanterns can't see each other.
--------------------------------------------------------------------------------
🐊 Game #31: Hungry Alligator (Kids version of Futoshiki)
File name: hungry-alligator.html
Category: Kids (5+)
Description: The alligator's mouth always eats the bigger number! Fill the grid with numbers 1-4. The arrows tell you which number is bigger.
Mapping to original: Replaces Futoshiki with 4x4 grid; inequality signs between cells; numbers 1-4 each row/col.
--------------------------------------------------------------------------------
⚔️ Game #32: Super Zoo (Kids version of Samurai Sudoku)
File name: super-zoo.html
Category: Kids (5+)
Description: Five zoos connected together! Fill all five grids so each row, column, and 2x2 box has one of each animal.
Mapping to original: Replaces Samurai Sudoku with 3 overlapping 4x4 grids; animals instead of numbers.
--------------------------------------------------------------------------------
🐮 Game #33: Corral Chaos (Kids version of Cow & Cactus)
File name: corral-chaos.html
Category: Kids (5+)
Description: Build a fence to keep the cows away from the poisonous cactus! The fence must touch every cow.
Mapping to original: Replaces Cow & Cactus with 4x4 grid; fence is a single loop; cows inside, cactus outside.
--------------------------------------------------------------------------------
👽 Game #34: Alien Rescue (Kids version of Area 51)
File name: alien-rescue.html
Category: Kids (5+)
Description: Protect the friendly aliens from the mutant cacti! Draw a fence that keeps aliens safe but cacti out.
Mapping to original: Replaces Area 51 with 5x5 grid; combines loop drawing with object placement.
--------------------------------------------------------------------------------
🍯 Game #35: Honeycomb Zoo (Kids version of Hex Sudoku)
File name: honeycomb-zoo.html
Category: Kids (5+)
Description: Fill the honeycomb with baby animals! Each row (the wiggly way) and each colored shape has one of each animal.
Mapping to original: Replaces 16x16 Hex Sudoku with simple 6-cell honeycomb; animals instead of numbers.
--------------------------------------------------------------------------------
💧 Game #36: Pond Pals (Kids version of Ripple Effect)
File name: pond-pals.html
Category: Kids (5+)
Description: Fill each pond with numbers. Same numbers can't be too close - they cause ripples!
Mapping to original: Replaces Ripple Effect with 4x4 grid; numbers 1-3; distance rule between same numbers.
--------------------------------------------------------------------------------
🖼️ Game #37: Picture Tiles (Toddler version of Pixidoku)
File name: picture-tiles.html
Category: Toddler (1-4)
Description: Match the picture tiles to complete the puzzle! Drag each tile to its matching spot.
Parent Tip: "Say: Can you find the elephant tile? Where does it go? Great matching!"
Mapping to original: Replaces Pixidoku with 2x2 or 3x3 grid; picture matching instead of numbers; no reading required.
--------------------------------------------------------------------------------
⚪ Game #38: Pearl Path (Kids version of Masyu)
File name: pearl-path.html
Category: Kids (5+)
Description: Draw a loop through all the pearls! White pearls mean go straight through; black pearls mean make a turn.
Mapping to original: Replaces Masyu with 5x5 grid; white/black pearl rules simplified; single loop.
--------------------------------------------------------------------------------
👻 Game #39: Ghost Hugs (Toddler version of Haunted)
File name: ghost-hugs.html
Category: Toddler (1-4)
Description: The friendly ghosts want to hug each other! Draw lines through the mirror maze to connect matching ghosts.
Parent Tip: "Say: Each ghost needs a hug from its twin! Can you draw a line to connect them without crossing other lines?"
Mapping to original: Replaces Haunted mirror mazes with simple path-drawing; matching ghost pairs; no time limit.
--------------------------------------------------------------------------------
🔐 Game #40: Secret Numbers (Kids version of Krypto Inkies)
File name: secret-numbers.html
Category: Kids (5+)
Description: The numbers are hidden in secret code! Solve the math clues to find which number is which.
Mapping to original: Replaces Krypto Inkies with 4x4 grid; simple letter-to-number cipher; addition/subtraction clues.
--------------------------------------------------------------------------------
📅 Game #41: Daily Zoo (Kids version of Daily Sudoku)
File name: daily-zoo.html
Category: Kids (5+)
Description: A new zoo puzzle every day! Come back tomorrow for a fresh challenge.
Mapping to original: Replaces Daily Sudoku with 4x4 grid that changes daily; uses date as random seed.
--------------------------------------------------------------------------------
⚖️ Game #42: Bigger Smaller Zoo (Kids version of Comparison Sudoku)
File name: bigger-smaller-zoo.html
Category: Kids (5+)
Description: The alligator mouth always eats the bigger animal! Use > and < signs to figure out where each animal goes.
Mapping to original: Replaces Comparison Sudoku with 4x4 grid; inequality signs between adjacent cells; animals instead of numbers.
--------------------------------------------------------------------------------
🐉 Game #43: Dragon Sudoku (Kids version of Jigoku)
File name: dragon-sudoku.html
Category: Kids (5+)
Description: The dragon's puzzle has no numbers to start! Only > and < signs. Can you figure out where all the animals go?
Mapping to original: Replaces Jigoku with 4x4 grid; no given numbers; only inequality signs between all adjacent cells.
--------------------------------------------------------------------------------
➕ Game #44: Number Crossword (Kids version of Cross Figures)
File name: number-crossword.html
Category: Kids (5+)
Description: A crossword puzzle with numbers! The clues are math problems. Fill in the grid with the correct numbers.
Mapping to original: Replaces Cross Figures with 4x4 crossword grid; simple addition/subtraction clues.
--------------------------------------------------------------------------------
🖼️ Game #45: Picture Frame Zoo (Kids version of Frame Sudoku)
File name: picture-frame-zoo.html
Category: Kids (5+)
Description: The numbers outside the grid tell you the sum of the first three animals in that row! Frame the perfect zoo.
Mapping to original: Replaces Frame Sudoku with 4x4 grid; frame clues show sums of outer numbers.
--------------------------------------------------------------------------------
🤫 Game #46: Secret Sums (Kids version of Krypto Kakuro)
File name: secret-sums.html
Category: Kids (5+)
Description: Each letter stands for a secret number! Solve the crossword sums to crack the code.
Mapping to original: Replaces Krypto Kakuro with 4x4 grid; letter-to-number cipher; addition clues.
--------------------------------------------------------------------------------
🔺 Game #47: Triangle Numbers (Kids version of TripleCross)
File name: triangle-numbers.html
Category: Kids (5+)
Description: A crossword in a honeycomb shape! Fill every hexagon with numbers that fit the math clues.
Mapping to original: Replaces TripleCross with simple hexagonal grid; 3 directions; addition clues.
--------------------------------------------------------------------------------
⭕ Game #48: Ring the Numbers (Kids version of Circle 9)
File name: ring-the-numbers.html
Category: Kids (5+)
Description: Circle the numbers 1-4 in the grid! Each row and column must have exactly one of each number circled.
Mapping to original: Replaces Circle 9 with 4x4 grid; circle exactly one of each number per row/col.
--------------------------------------------------------------------------------
🌌 Game #49: Space Spin (Kids version of Galaxies)
File name: space-spin.html
Category: Kids (5+)
Description: Each galaxy has a center star. Draw lines to divide space so each galaxy is perfectly symmetric!
Mapping to original: Replaces Galaxies with 4x4 grid; each region must be symmetric around its center dot.
--------------------------------------------------------------------------------
⭐ Game #50: Diagonal Zoo (Kids version of X Sudoku)
File name: diagonal-zoo.html
Category: Kids (5+)
Description: Both long diagonals must also have one of each animal! Can you fill the grid?
Mapping to original: Replaces X Sudoku with 4x4 grid; diagonal constraints; animals instead of numbers.
--------------------------------------------------------------------------------
🎯 Game #51: Middle Star (Kids version of Center Dot Sudoku)
File name: middle-star.html
Category: Kids (5+)
Description: The four center squares must have one of each animal! Plus regular Sudoku rules.
Mapping to original: Replaces Center Dot Sudoku with 4x4 grid; extra constraint on 2x2 center block.
--------------------------------------------------------------------------------
🌈 Game #52: Rainbow Zoo (Kids version of Rainbow Sudoku)
File name: rainbow-zoo.html
Category: Kids (5+)
Description: Each colored rainbow stripe must have one of each animal! Plus rows and columns too.
Mapping to original: Replaces Rainbow Sudoku with 4x4 grid; colored regions; animals instead of numbers.
--------------------------------------------------------------------------------
🧵 Game #53: Quilt Puzzle (Kids version of Patchwork Sudoku)
File name: quilt-puzzle.html
Category: Kids (5+)
Description: Each patch in the quilt must have different animals! No touching patches can have the same animal.
Mapping to original: Replaces Patchwork Sudoku with 4x4 grid; adjacent regions constraint.
--------------------------------------------------------------------------------
🐊 Game #54: Alligator Zoo (Kids version of Greater-than Sudoku)
File name: alligator-zoo.html
Category: Kids (5+)
Description: The alligator mouths tell you which animal is bigger! Use the signs to solve the puzzle.
Mapping to original: Replaces Greater-than Sudoku with 4x4 grid; inequality signs between cells; animals instead of numbers.
--------------------------------------------------------------------------------
🧩 Game #55: Puzzle Mix (Kids version of Jiggy)
File name: puzzle-mix.html
Category: Kids (5+)
Description: Comparison signs AND jigsaw shapes! A double challenge for puzzle masters.
Mapping to original: Replaces Jiggy with 4x4 grid; combines inequality signs with irregular regions.
--------------------------------------------------------------------------------
🪟 Game #56: Window Pane (Kids version of Jones)
File name: window-pane.html
Category: Kids (5+)
Description: Comparison signs AND window panes (extra regions)! Fill the grid carefully.
Mapping to original: Replaces Jones with 4x4 grid; inequalities plus 2x2 window regions.
--------------------------------------------------------------------------------
🏃 Game #57: Escape Plan (Kids version of Prisoner X)
File name: escape-plan.html
Category: Kids (5+)
Description: Center dot AND diagonal constraints! Help the prisoner find the escape path.
Mapping to original: Replaces Prisoner X with 4x4 grid; both center-dot and diagonal rules.
--------------------------------------------------------------------------------
🔲 Game #58: Cellblock X (Kids version of Cellblock X)
File name: cellblock-x.html
Category: Kids (5+)
Description: Diagonals AND window panes! A challenging mix for expert solvers.
Mapping to original: Replaces Cellblock X with 4x4 grid; both diagonal and window constraints.
--------------------------------------------------------------------------------
🧩 Game #59: Consecutive Jigsaw (Kids version of Consecutive Jigsaw)
File name: consecutive-jigsaw.html
Category: Kids (5+)
Description: Consecutive bars AND jigsaw shapes! Numbers next to bars must be neighbors.
Mapping to original: Replaces Consecutive Jigsaw with 4x4 grid; combines consecutive clues with irregular regions.
--------------------------------------------------------------------------------
⭐ Game #60: Jigsaw X Sudoku (Kids version of Jigsaw X Sudoku)
File name: jigsaw-x-sudoku.html
Category: Kids (5+)
Description: Jigsaw shapes AND diagonal lines! Two special rules in one puzzle.
Mapping to original: Replaces Jigsaw X Sudoku with 4x4 grid; irregular regions plus diagonal constraints.
--------------------------------------------------------------------------------
🥪 Game #61: BLT Sandwich (Kids version of BLT Sandwich)
File name: blt-sandwich.html
Category: Kids (5+)
Description: Diagonals AND sandwich clues! Make the perfect BLT sandwich with extra toppings.
Mapping to original: Replaces BLT Sandwich with 4x4 grid; diagonal constraints plus sandwich sums.
--------------------------------------------------------------------------------
🪟 Game #62: Kravitz (Kids version of Kravitz)
File name: kravitz.html
Category: Kids (5+)
Description: Consecutive bars AND window panes! Numbers next to bars must be neighbors.
Mapping to original: Replaces Kravitz with 4x4 grid; consecutive clues plus 2x2 window regions.
--------------------------------------------------------------------------------
🏙️ Game #63: Krazytown (Kids version of Krazytown)
File name: krazytown.html
Category: Kids (5+)
Description: Jigsaw shapes AND skyscraper clues! Build the craziest town ever.
Mapping to original: Replaces Krazytown with 4x4 grid; irregular regions plus skyscraper visibility clues.
--------------------------------------------------------------------------------
🌈 Game #64: Rainbow Jigsaw (Kids version of Rainbow Jigsaw)
File name: rainbow-jigsaw.html
Category: Kids (5+)
Description: Jigsaw shapes AND rainbow colors! Each colored region needs all animals too.
Mapping to original: Replaces Rainbow Jigsaw with 4x4 grid; irregular regions plus colored constraints.
--------------------------------------------------------------------------------
🏗️ Game #65: Skyscraper 4x (Kids version of Skyscraper 4x Latin square)
File name: skyscraper-4x.html
Category: Kids (5+)
Description: A smaller skyscraper puzzle! Just rows and columns, no extra regions. Build 4 buildings.
Mapping to original: Replaces Skyscraper 4x with 4x4 Latin square; only row/col uniqueness; skyscraper clues.
--------------------------------------------------------------------------------
🏗️ Game #66: Skyscraper 5x (Kids version of Skyscraper 5x Latin square)
File name: skyscraper-5x.html
Category: Kids (5+)
Description: A medium skyscraper puzzle! Build 5 buildings in each row and column.
Mapping to original: Replaces Skyscraper 5x with 5x5 Latin square; numbers 1-5; skyscraper visibility clues.
--------------------------------------------------------------------------------
🏗️ Game #67: Skyscraper 6x (Kids version of Skyscraper 6x Latin square)
File name: skyscraper-6x.html
Category: Kids (5+)
Description: A big skyscraper puzzle! Build 6 buildings in each row and column.
Mapping to original: Replaces Skyscraper 6x with 6x6 Latin square; numbers 1-6; skyscraper visibility clues.
--------------------------------------------------------------------------------
⛅ Game #68: Skycon Sudoku (Kids version of Skycon Sudoku)
File name: skycon-sudoku.html
Category: Kids (5+)
Description: Consecutive bars AND skyscraper clues! A double challenge in the sky.
Mapping to original: Replaces Skycon Sudoku with 4x4 grid; consecutive neighbor clues plus skyscraper clues.
--------------------------------------------------------------------------------
🏔️ Game #69: Flatiron Sudoku (Kids version of Flatiron Sudoku)
File name: flatiron-sudoku.html
Category: Kids (5+)
Description: Consecutive bars, jigsaw shapes, AND skyscraper clues! The ultimate triple challenge.
Mapping to original: Replaces Flatiron Sudoku with 4x4 grid; three special rules combined.
--------------------------------------------------------------------------------
📏 Game #70: Sliders (Kids version of Sliders)
File name: sliders.html
Category: Kids (5+)
Description: Consecutive bars AND sandwich clues! Numbers slide into place perfectly.
Mapping to original: Replaces Sliders with 4x4 grid; consecutive neighbor rules plus sandwich sums.
--------------------------------------------------------------------------------
🌈 Game #71: Stitchwork Sudoku (Kids version of Stitchwork Sudoku)
File name: stitchwork-sudoku.html
Category: Kids (5+)
Description: Diagonals AND rainbow colors! Stitch together the perfect puzzle.
Mapping to original: Replaces Stitchwork Sudoku with 4x4 grid; diagonal constraints plus colored regions.
--------------------------------------------------------------------------------
💨 Game #72: Windsaw Sudoku (Kids version of Windsaw Sudoku)
File name: windsaw-sudoku.html
Category: Kids (5+)
Description: Jigsaw shapes AND window panes! The wind blows through this puzzle.
Mapping to original: Replaces Windsaw Sudoku with 4x4 grid; irregular regions plus 2x2 window regions.
--------------------------------------------------------------------------------
💨 Game #73: Windconsaw Sudoku (Kids version of Windconsaw Sudoku)
File name: windconsaw-sudoku.html
Category: Kids (5+)
Description: Consecutive bars, jigsaw shapes, AND window panes! Three windy rules together.
Mapping to original: Replaces Windconsaw Sudoku with 4x4 grid; triple combination of consecutive, jigsaw, and window.
--------------------------------------------------------------------------------
🖼️ Game #74: Frame Sudoku (Kids version of Frame Sudoku)
File name: frame-sudoku.html
Category: Kids (5+)
Description: The numbers outside tell you the sum of the first three animals! Frame the picture.
Mapping to original: Replaces Frame Sudoku with 4x4 grid; frame clues show sums of outer numbers.
--------------------------------------------------------------------------------
🎨 Game #75: Kandinsky Sudoku (Kids version of Kandinsky Sudoku)
File name: kandinsky-sudoku.html
Category: Kids (5+)
Description: Frame sums AND jigsaw shapes! Like a Kandinsky painting, colorful and abstract.
Mapping to original: Replaces Kandinsky Sudoku with 4x4 grid; frame clues plus irregular regions.
--------------------------------------------------------------------------------
🟦 Game #76: Mondrian Sudoku (Kids version of Mondrian Sudoku)
File name: mondrian-sudoku.html
Category: Kids (5+)
Description: Frame sums AND window panes! Like a Mondrian painting with bold rectangles.
Mapping to original: Replaces Mondrian Sudoku with 4x4 grid; frame clues plus 2x2 window regions.
--------------------------------------------------------------------------------
🎨 Game #77: Kahlo Sudoku (Kids version of Kahlo Sudoku)
File name: kahlo-sudoku.html
Category: Kids (5+)
Description: Frame sums, jigsaw shapes, AND window panes! A masterpiece puzzle.
Mapping to original: Replaces Kahlo Sudoku with 4x4 grid; triple combination of frame, jigsaw, and window.
--------------------------------------------------------------------------------
🎨 Game #78: Klee Sudoku (Kids version of Klee Sudoku)
File name: klee-sudoku.html
Category: Kids (5+)
Description: Consecutive bars, frame sums, AND jigsaw shapes! Like a Klee painting, playful and complex.
Mapping to original: Replaces Klee Sudoku with 4x4 grid; triple combination of consecutive, frame, and jigsaw.
--------------------------------------------------------------------------------
⚫⚪ Game #79: Kropki Plain (Kids version of Kropki Latin square)
File name: kropki-plain.html
Category: Kids (5+)
Description: White dots mean numbers are neighbors. Black dots mean one is double. No extra regions!
Mapping to original: Replaces Kropki Plain with 4x4 Latin square; dot rules between adjacent cells.
--------------------------------------------------------------------------------
⚫⚪ Game #80: Kropki Sudoku (Kids version of Kropki Sudoku)
File name: kropki-sudoku.html
Category: Kids (5+)
Description: White and black dots between cells! Fill the grid so each row, column, and box has numbers 1-4.
Mapping to original: Replaces Kropki Sudoku with 4x4 grid; dot rules plus standard Sudoku constraints.
--------------------------------------------------------------------------------
🧩 Game #81: Korbut Sudoku (Kids version of Korbut Sudoku)
File name: korbut-sudoku.html
Category: Kids (5+)
Description: Jigsaw shapes AND Kropki dots! A challenging combination for puzzle experts.
Mapping to original: Replaces Korbut Sudoku with 4x4 grid; irregular regions plus dot rules.
--------------------------------------------------------------------------------
🪟 Game #82: Chagall Sudoku (Kids version of Chagall Sudoku)
File name: chagall-sudoku.html
Category: Kids (5+)
Description: An art-inspired puzzle combining colorful regions and gentle numeric/frame clues. Fill the grid so each row and column has one of each animal while respecting the artistic region constraints.
Mapping to original: Replaces Chagall Sudoku with a simplified 4x4 grid; combines jigsaw regions and frame-sum style clues for an approachable kids' variant.
--------------------------------------------------------------------------------


> **Note:** External games are hosted at `athishsreeram.github.io/fungames/`. They require an active internet connection.

---

## 🚀 How to Run

1. **Download** the `index.html` file (the complete code you have).
2. **Double‑click** the file – it will open in your default web browser.
3. No build steps, no server needed. Everything runs locally.

Alternatively, serve it with any static server:
```bash
npx serve .
# or python -m http.server
```

---

## 🧩 How to Use

- **Filter games** by clicking the buttons at the top: *All Games*, *Toddler*, *Kids*, or *Trending*.
- **Play an embedded game** (Color Hunt, Quiet Box, Animal Match Up, Shape Sorter, Tap to Stack, Reaction Click, Speed Typing) – click the card. A modal opens with the game inside.
- **Play an external game** (ABC Phonics, Drawing Time, Number Fun, Tic Tac Toe) – the card directly navigates to that URL.
- **Close a modal** by clicking the ✕ button or tapping the overlay background.

> For toddler games, a **Parent Tip** is displayed inside the modal – read it aloud for extra learning fun!

---

## 🛠️ Technology Stack

- **HTML5** – semantic structure, modal, canvas elements.
- **CSS3** – custom properties, grid/flex layouts, keyframe animations, responsive design.
- **JavaScript (ES6)** – dynamic filtering, game logic, canvas drawing, event handling.
- **Web Audio API** – simple sound effects for game feedback.
- **Google Fonts** – *Fredoka One* (headings) and *Nunito* (body).

---

## 📁 File Structure

```
project-folder/
└── index.html          # Complete game portal (styles, markup, scripts)
```

All styles and scripts are embedded in a single file – no external dependencies (except Google Fonts and the optional external game links).

---

## ⚠️ Known Issues & Improvements

### 🐞 Known Issues

- **Tap to Stack game uses `ctx.roundRect()`** – this method is not a standard Canvas API. The game currently throws an error and will not work.  
  **Fix:** Add a polyfill at the beginning of the script:
  ```js
  if (!CanvasRenderingContext2D.prototype.roundRect) {
    CanvasRenderingContext2D.prototype.roundRect = function(x, y, w, h, r) {
      if (w < 2 * r) r = w / 2;
      if (h < 2 * r) r = h / 2;
      this.moveTo(x+r, y);
      this.lineTo(x+w-r, y);
      this.quadraticCurveTo(x+w, y, x+w, y+r);
      this.lineTo(x+w, y+h-r);
      this.quadraticCurveTo(x+w, y+h, x+w-r, y+h);
      this.lineTo(x+r, y+h);
      this.quadraticCurveTo(x, y+h, x, y+h-r);
      this.lineTo(x, y+r);
      this.quadraticCurveTo(x, y, x+r, y);
      return this;
    };
  }
  ```
- **AudioContext requires user interaction** – on some browsers, sound only works after the first user click (this is a browser security policy). The first click inside any game will enable audio.

### 💡 Possible Improvements

- Add a **high score** system for trending games (localStorage).
- Include a **mute button** for sounds.
- Extend “Kids” section with more educational games (math puzzles, memory match).
- Provide **offline fallback** for external links.
- Add **loading spinners** for external iframes (if embedded later).

---

## 📄 License

This project is open‑source and available under the **MIT License**.  
You are free to use, modify, and distribute it – attribution is appreciated but not required.

---

## 🙏 Acknowledgements

- Inspired by classic early‑learning concepts from *Concept Kids Animals*, *My First Castle Panic*, and *quiet time activities*.
- Icons and emojis used for visual delight.
- Built with ☕ and 🎨 by a game‑loving developer.

