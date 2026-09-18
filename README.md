# Portfolio

Hi I'm Lily
- UBC '23 Combined major in CPSC and Mathematics
- 4.0 GPA. Various awards/scholarships totalling ~$11000, including the Academic Award of Excellence for the highest graduating GPA in the program
- Former exec and cryptography mentor for the UBC CTF team Maple Bacon
  - Ranked 1st in Canada 2019-2022, peaking at 7th worldwide
  - 1st place at DEFCON CTF as Maple Mallard Magistrates, together with PPP and Theori
- Previously
  - Cybersecurity engineer @ Jane Street (log infrastructure, detection, network security monitoring, lots of OCaml)
  - Swift standard library @ Apple
  - Software dev @ Canadian Centre for Cybersecurity

Feel free to contact me about opportunities to work on interesting problems at the intersection of programming languages, security, compilers, or cryptography

# Work samples
- Issue triaging and the bug fixing PR: https://github.com/apple/swift-experimental-string-processing/issues/558 https://github.com/apple/swift-experimental-string-processing/pull/560
- A feature PR: https://github.com/apple/swift-experimental-string-processing/pull/577

# Writing
- [CTF challenge writeups](https://blog.ririryn.com/archive/#:~:text=CTF,-related), writeups for some of the CTF challenges I've solved
- [Cryptography resources](https://crypto.maplebacon.org/), a resource for helping beginners get into cryptography
- [Personal blog](https://blog.ririryn.com/archive/)

# Projects

I have many many silly projects

[![Lily's top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rctcwyvrn&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

## Personal highlights
- [rlox](https://github.com/rctcwyvrn/rlox), a `rust` bytecode compiler and VM for the `Lox` language, optimized to roughly 2x faster across almost all benchmarks and fuzzed with cargo-fuzz
- A Racket to x86 compiler (CPSC 411), a full nanopass compiler written in a team of three. Macro expansion, register allocation, closure conversion, tagged data, and heap objects
- [tal-inference](https://github.com/rctcwyvrn/tal-inference), type inference on an assembly subset. It _kinda_ works.
- [rop-fk](https://github.com/rctcwyvrn/rop-fk), using return oriented programming to make a bf interpreter
- [queens](https://github.com/rctcwyvrn/queens), a whole bunch of really really dumb AI players for the Amazons board game, based on this tom7 video https://www.youtube.com/watch?v=DpXy041BIlA
- [rust-fractran](https://github.com/rctcwyvrn/rust-fractran), did you know that fractions are Turing complete? Watch me compute prime numbers using them

## LLM assisted projects
- [infernal-fpga](https://github.com/rctcwyvrn/infernal-fpga), FPGA acceleration of Infernal's RNA covariance model search, written in `Hardcaml (OCaml)` for AWS F1. A systolic array design that generates synthesizable SystemVerilog. **Incomplete**
- [momentum], a combat robot modelled in OpenSCAD by agents
- [AIRFUEL], a Godot shooter with extremely fast movement

## Cryptography projects
- [blake3](https://github.com/rctcwyvrn/blake3), an implementation of the blake3 hash function in pure java, published to Maven Central and used by Jacksum, keri-java, and riv-benchmark
- [py_hash_sigs](https://github.com/rctcwyvrn/py_hash_sigs), while on a flight I implemented some hash based signature schemes, which are very cool (see SPHINCS+, now standardized from the post quantum NIST competition!)
- [cryptopals](https://github.com/rctcwyvrn/ctf_stuff/tree/master/cryptopals), solutions for the original [Matasano Cryptopals](https://cryptopals.com/) sets. Lots of fun attacks on real cryptography

## Word game solvers
- [letter_boxed](https://github.com/rctcwyvrn/letter_boxed_solver), a solver for [https://www.nytimes.com/puzzles/letter-boxed](https://www.nytimes.com/puzzles/letter-boxed)
- [sidewords](https://github.com/rctcwyvrn/sidewords), a solver for [https://sidewords.ca/](https://sidewords.ca/)

## Other stuff
- [woodpecker](https://github.com/rctcwyvrn/woodpecker), a compiler that lowers bitwise operations and addition onto the four instruction bit tape machine from Radical Semiconductor's woodpecker challenge
- [skipper](https://github.com/rctcwyvrn/skipper), a constant-time assembly language and compiler, written at 39c3. **Work in progress**
- [gossip-glomers](https://github.com/rctcwyvrn/gossip-glomers), solutions to the Fly.io distributed systems challenges in `rust`. **Incomplete**
- [jlox](https://github.com/rctcwyvrn/jlox): A `java` tree walk interpreter for `Lox`
- [minecraft_api](https://github.com/rctcwyvrn/minecraft_api), we wanted an api to connect our minecraft server messages to a discord bot, so I wrote this little `rust` project
- [advent](https://github.com/rctcwyvrn/advent), some Advent of Code solutions, a few of these got in the daily top 100 placings!
- [sudoku](https://github.com/rctcwyvrn/sudoku), a little `haskell` project, just a simple backtracking sudoku solver
- [py_spec](https://github.com/rctcwyvrn/py_spec). You know those circular audio waveform things? I wanted a script that could generate those for me so I wrote one. It works _ok_
- [python-bees](https://github.com/rctcwyvrn/python-bees), a `python` implementation of the `Artificial Bee Colony` algoirthm, which is this weird meta-heuristic algorithm based on bee foraging patterns
