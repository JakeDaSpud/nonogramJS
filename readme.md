# ⏹️Nonograms but in Javascript❎
yep, i'm going to try make the japanese puzzle game ***nonogram / picross*** in javascript, i love the game and i plan to try turn them into password systems and captchas too, even though they're not very suitable for that!

---

## 🪆moscow to-do📝

### must have
- [ ] table layout (start with 3x3, dynamic later?)
- [ ] click detection on a cell
- [ ] js that changes the contents of a cell / changes its state [empty, filled (◼️), crossed (❌)]
- [ ] js that can parse correct answer matrix for puzzle
- [ ] js that will generate outer hint numbers for table, from the answer matrix

### should have
- [ ] puzzle completion message, player knows when they're done
- [ ] ability to put X in cell
- [ ] proper algo that prevents guessing? **(<- needs researching!)**
- [ ] generate new puzzle button
- [ ] restart puzzle button -> all cells emptied

### could have
- [ ] timer from first action, until final correct filled cell is placed
- [ ] pause button: pause -> timer paused + all cells are filled with either empty or crosses until unpaused
- [ ] dynamic puzzle size generation (generate table html from js? 🤔)
- [ ] give up function: press -> puzzle auto-fills

### won't have
- [ ] account system
- [ ] penalty system, you cannot lose, like some versions where you get 3 mistakes then lose 🙄 (extremely unfun mechanic, i am here to relax and PUZZLE)
- [ ] puzzle completion remembering
- [ ] leaderboards / points
- [ ] coloured puzzle ability ***(yet!! next on the list if i get this done!)***
- [ ] good styling lol, not the point rn
