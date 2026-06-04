# hash-random-emergence
This is the "sister version" to mulberry32 emergence. The differences are the random algorithm, and that seeds can now be letters (but it is preferable to still use numbers). This one feels like it should be explored more, but the mulberry32 one is the original and will likely be explored more.
## Why should we use numbers?
Imagine we find a great discovery, but its seed contains an offensive string. Numbers cannot offend, but words can. This pattern is now practically unshareable. Short strings of up to 2 letters should also be searched, but 3 letters is where offensive possibilities begin.
## About Hash Depth
Hash Depth should be 32 for most things, 128 is reserved for trying to discover the rarest things (such as period-10 oscilators), and we should focus on 32 instead of 128 for discovering things.
## Settings
States determine how many states there are, and seeds determine what ruleset you get. This is represented by "t|e" where t is the number of states and e is the seed.
## Pattern names
A pattern that stays still (1|75) (2|242) is a still life.

A pattern that repeatedly recplicates itself somewhere else (1|1) (3|2) is a spaceship.

A pattern that repeatedly replicates itself in the same spot (2|954) (3|5890) is an oscillator.

A pattern that repeatedly replicates itself exponentially (2|e) is a duplicator.

A pattern that grows infinitely in some way (2|55) is infinite growth.
## Interesting Patterns
### 2|55
Generates a weird infinite growth that isn't a duplicator or a Fibonacci.
### 2|954
First ever found oscillator. Found with an automated searcher.
### 2|rg
Throws upwards a weird pattern.
### 3|4
Implements a Fibonacci sequence while creating extremely interesting patterns.
### 3|5
This is an infinite growth that looks like a slice of pizza. Yum!
### 3|5890
First ever found period-3 oscillator. Found with an automated searcher.
### 4|2
This may be the simplest knightwise spaceship.
### 4|25
This is a spaceship that releases spaceships going northeast.
### 4|32
This is a gun that releases pink cells to the left.
### 4|45
This is a gun that releases guns that release spaceships going up.
### 5|5
This is a proven infinitely growing spacefiller that gets laggy very fast.
### 5|8
This appears to be an infinite growth smile. I cannot prove if it is truly infinite growth.
### 5|37
This is an infinite growth that goes up by 2 every time.
### 5|44
This is a moving gun that shoots spaceships while moving backwards.
### 5|51
This is a Fibonacci infinite growth that appears to be a spaceship.
### 5|55
This is a tower going down and creating infinite towers that go to the bottom-right corner, potentially a dupliduplicator, an exponential exponential growth.
### 5|57
This is a spaceship occupying two cells, making it appear square on my display.
### 5|60
This is a faux 3D pattern that appears isotropic, somewhat like Q*Bert.
### 5|27583
After searching tens of thousands of seeds, this is the highly coveted period-4 oscillator, first of it's kind.
### 5|a
This quickly evolves into two spaceships going in different directions, occasionally hitting each other.
### 6|11
This is a moving oblique line whose cell count goes up according to the Padovan sequence.
### 6|16
This is a flamethrower-like pattern that appears to grow at a rate of around 1.521, which means patterns as simple as 6 states can estimate strangely precise numbers.
### 6|17
This is a laser making a checkerboard, but it is very close to a duplicator.
### 6|25
A true diagonal gun which does not move.
### 6|91
Two green and two purple spaceships running into each other and going back and down, making a spaceship made of spaceships.
### 6|93
A pattern that appears to grow at a rate of around 1.695.
### 6|95
On odd generations, the population goes up by $1 + \frac{1}{\sqrt{2}}$, but on even generations, the population goes up by a constant $2$.
### 6|101
This pattern looks like a butterfly spreading its wings, but it is a boring duplicator.
### 6|104
This pattern follows the Fibonacci sequence while also looking like a rainbow cake with frosting dripping off.
### 6|108
This pattern evolves into two green spaceships heading northeast and one pink spaceship heading east.
### 6|109
This pattern is a duplicator that looks like an extremely strange flickering checkerboard staircase. Its missing corner is northeast.
### 6|1276
Two spaceships that constantly jump past each other.
### 6|2026
An infinite growth that looks like a cake.
### 6|12412
This is another Padovan pattern.
### 6|543543
This is apparently a cubic eqaution contained entirely within 6 states.
### 6|a
This is a gun that shoots 2-width spaceships.
### 7|343623 & 7|394160 (The Double Holy Grail)
7|343623 and 7|394160. Dozens of minutes of searching. After going through hundreds of thousands of potential seeds, they were found. Two period-5 oscillators in the same hundred-thousand range. This is an extremely rare occurence that would have been almost impossible to have been discovered by humans. The next goal we set our sights on is period-6.
### 8|414246 (The Few-Second Anomaly)
This is a period-6 oscillator found on complete accident while testing a search script.
### 9|168881 (The Harbinger of Browser Lag)
After 30 seconds to a minute of searching at an extremely high speed (10000 per frame) causing browser lag, this period-7 oscillator was found. A period-10 oscillator doesn't feel so far out of reach now.
### 11|132619 (105000)
The search engine found this period-7 oscillator at exactly 105000 PM, which is how it got its name.
### 11|2520505 (Duo Cinco)
I was doing my Duolingo when I found this period-7 oscillator whose seed makes heavily use of 2 and 5, in Spanish those numbers are "Duo" and "Cinco", and "Duo Cinco" sounds like Duolingo.
### 11|3840131 (Scroll Sauerkraut)
I was scrolling on my phone and this period-7 oscillator popped up at 11:22 PM. 11:22 is also the length of the song Albuquerque, in which sauerkraut is featured.
### 11|5387841 (The Hook)
This period-7 oscillator traces out the path of a hook.
### 11|6420928 (The Quantum Duet)
Among a sea of period-7 oscillators in almost an hour of searching, one stood out. A walk to the browser window revealed it.

\[🌪️ ANOMALY CAPTURED\] Ruleset: 11|6420928 -> True P-12! (Captured at 11:35:06 PM)

Featuring two color-changing cells dancing around each other, this is the most ground-breaking discovery in all of hash random emergence. No period 8, 9, 10, or 11. Just straight to period-12. The Quantum Duet makes The Harbinger of Browser Lag look like 2|954.

Truly there are no words that can properly express how extremely rare and statistically epic this is.
### 11|7413128 & 11|7543386 & 11|7794054
This trio of period-7 oscillators appeared very near to each other.
### 11|8355092 & 11|8548308
Non-notable period-7 oscillators.
### 11|8753728 & 11|8782687 & 11|8809735 (Seven Seconds of Period-7)
Within 7 seconds, these three period-7 oscillators were discovered.
### 11|9116306
This is the final period-7 oscillator I will show here that isn't special in some way.
### 25|234
This is a weird line going down.
