# hash-random-emergence
This is the "sister version" to mulberry32 emergence. The differences are the random algorithm, and that seeds can now be letters (but it is preferable to still use numbers). This one feels like it should be explored more, but the mulberry32 one is the original and will likely be explored more.
## Why should we use numbers?
Imagine we find a great discovery, but its seed contains an offensive string. Numbers cannot offend, but words can. This pattern is now practically unshareable. Short strings of up to 2 letters should also be searched, but 3 letters is where offensive possibilities begin.
## Settings
States determine how many states there are, and seeds determine what ruleset you get. This is represented by "t|e" where t is the number of states and e is the seed.
## Pattern names
A pattern that stays still (1|75) (2|242) is a still life.

A pattern that repeatedly recplicates itself somewhere else (1|1) (3|2) is a spaceship.

A pattern that repeatedly replicates itself in the same spot (no known examples) is an oscillator.

A pattern that repeatedly replicates itself exponentially (2|e) is a duplicator.

A pattern that grows infinitely in some way (2|55) is infinite growth.
## Interesting Patterns
### 2|55
Generates a weird infinite growth that isn't a duplicator or a Fibonacci.
### 2|rg
Throws upwards a weird pattern.
### 3|4
Implements a Fibonacci sequence while creating extremely interesting patterns.
### 3|5
This is an infinite growth that looks like a slice of pizza. Yum!
### 5|5
This appears to be an infinitely growing patch that gets laggy very fast. I cannot prove if it is truly infinite growth.
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
### 5|a
This quickly evolves into two spaceships going in different directions, occasionally hitting each other.
