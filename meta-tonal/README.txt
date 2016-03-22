Investigates whether learning word pairs can be affected by hearing them presented with monotone vs. harmonic sequences. 

Data file written to desktop.

** PARAMETERS **
4 condition presents. Use “show/hide params” in menu to reveal details. 

- Tone Set: currently only Monotone/Harmonic
- Study Presentation order: Random, BlockAfirst, BlockBfirst
- Timing: set delay for target appear, JOL appear, hide words
- Filler task: None, Easy, Hard
- Tones during test: true/false
- Confidence judgments during test: random, 1sthalf, 2ndhalf, none
- Test Presentation order: Same as study, Random

** PHASES **

Study phase: play word pair sound bytes along with visual cue
 - ask JOL [slider]: “How confident are you that you will remember this pair?”

Test phase: show cue, user types in target.
- after response, confidence judgement [slider]: “How sure are you that your answer is correct?”



** CHANGE LOG **

12/3/2009
- add option to have ConfJudg for ALL
- sometimes words are blank… check 0-19, 1-20 again

1/13/2010
- add ConfJudg All
- fixed slider issue
- changed all sounds to Mom-Dad (temp)
- added # trials control (for easier debugging)
- made timers go by quarter seconds, not half

2/4/2010
- resolved why sometimes blank words in "Random" order condition
- create condition 1-4 presets
- put new sounds (words and tones) in
- minute count during filler

2/5/2010
- added correlate ratings, tested, recompiled, posted.