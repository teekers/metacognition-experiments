_____________________________

Program:	Passage Study
Author:  	Tamar Kornblum / ta***m@gmail.com
Date:   	Fall 2015
Prepared for:	Amie Wolf / a***f@gmail.com
_____________________________

IDE:		Xojo 2015 Release 3.1 *see note
Built for: 	Mac OSX (current: 10.10.5)
Input file: 	none
Output file: 	one combined data file to desktop
_____________________________

*** Description ***

Subjects rank, study, and are tested on material related to 8 short passages. Independent variable is length of study time. Program uses Controller Module to switch between windows and control flow. 


*** Phases ***
At any time, skip to next phase with keystroke ⌘ > (command + shift + period).

0. Params 
- enter Subject ID, choose Group A/B (controls preset study time)
- Show hidden controls via menu (or ⌘S).  
- Activate Debug Mode in hidden controls (or ⌘D). 

1. Rank
- Subjects see passage previews and rate based on 2 criteria.
- Ties, if any, are resolved using ForceRank.

2. Study
- Passage titles arranged in a circle, clicking one displays full passage text in center.
- Records amount of time each passage is visible (by press, and as summary). 
- Countdown timer visible during study session.

3. Demographics
- User must answer all fields EXCEPT SAT scores.

4. Test
- Each passage has 6 questions, shown in order. The order of passages is randomized.

5. End Session
- Data file writes to Desktop. 
- If file already exists, appends new data at end of file. 
- If file is open (and cannot write to it), shows error message and copies data to clipboard.
- If program is quit before EndSession, attempts to write any collected data. 


*** Debug Mode ***

Adds shortcuts to debug sessions more quickly. Activate in parameter setup. Changes the following:
- Rank fields prepopulate 
- Study time set to 0.6 minutes
- Test answers - correct answers show as "CORRECT". Delay between questions changes from 1s to .001s.


*** Software version note ***

Most coding was done in RealBasic 2011r4.1. A few bugs (related to HTMLviewer) would not resolve until updating to current version of Xojo. Code is not optimized for Xojo, but all deprecated RB classes have been resolved. 