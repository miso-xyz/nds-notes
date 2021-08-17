# nds-notes
All of the content available here is original.
## Projects ##
- Tools
  - <a href="https://github.com/miso-xyz/DDJDS-SFR">Doodle Jump Save File Reader</a>
  - <a href="https://github.com/miso-xyz/UnlaunchEditor">Unlaunch.dsi Editor</a>
- Libraries
  - <a href="https://github.com/miso-xyz/PPMLib">PPMLib</a>
- Reverse Engineered Games
  - <a href="https://github.com/miso-xyz/TrackManiaDS-Reversed">TrackMania DS</a>
  - <a href="https://github.com/miso-xyz/Cars-2-DS-Reversed">Cars 2 DS</a>
- Other
  - <a href="https://github.com/miso-xyz/TrackManiaDS-Documentation">Trackmania DS - Documentation</a>

## Syntax Highlighting ##
Click to download `.pos` file - Requires <a href="http://www.winhex.com/winhex/">`WinHex`</a>
<hr>

- <a href="https://github.com/miso-xyz/nds-notes/raw/main/WinHex%20Syntax%20Highlighting/DDJDS%20Save%20File%20-%20WinHex%20Highlighting.pos">Doodle Jump DS Save File</a>
- <a href="https://github.com/miso-xyz/nds-notes/blob/main/WinHex%20Syntax%20Highlighting/THPDS%20Save%20File%20-%20WinHex%20Highlighting.pos">Texas Hold'em Poker DS Save File</a>
- - - -
## Custom Action Replay Codes ##
Number of Complete Codes: `45`</br>
***More Information can be found in the files, such as scrapped codes & indexed Memory Addresses***
- - - -
<details>
  <summary><a href="https://github.com/miso-xyz/nds-notes/blob/main/AR%20Codes%20ive%20made/Doodle%20Jump%20Codes.txt">Texas Hold'em Poker DS</a> (12 Codes)</summary>
  <hr>
  
  - Player - Always have $99999999
    - <pre>0226B014 05F5E0FF
      0226B03C 05F5E0FF
      0226B064 05F5E0FF
      0226B08C 05F5E0FF
      0226B0B4 05F5E0FF
      022FBC98 05F5E0FF</pre>
  - Player - Always have $0
    - <pre>0226B014 00000000
      0226B03C 00000000
      0226B064 00000000
      0226B08C 00000000
      0226B0B4 00000000
      022FBC98 00000000</pre>
  - Always Player's Turn
    - <pre>0236D1C0 00000000
      0236D408 00000000
      0236DC4C 00000000</pre>
  - Always Raise with $0
    - <pre>022FBCA0 00000000</pre>
  - $99999999 Pot
    - <pre>222D0F40 05F5E0FF
      022D0F70 05F5E0FF</pre>
  - $0 Pot
    - <pre>222D0F40 00000000
      022D0F70 00000000</pre>
  - Always Call with $0
    - <pre>0226B4F4 00000000
      0226B51C 00000000
      0226B544 00000000
      0226B56C 00000000
      0226B594 00000000</pre>
  - CPU 1 - Always have $0
    - <pre>022FD560 00000000</pre>
  - CPU 2 - Always have $0
    - <pre>022FF058 00000000</pre>
  - CPU 3 - Always have $0
    - <pre>023006D4 00000000</pre>
  - CPU 4 - Always have $0
    - <pre>02301D50 00000000</pre>
  - CPU 5 - Always have $0
    - <pre>023033CC 00000000</pre>
  <hr>
</details>

<details>
  <summary><a href="https://github.com/miso-xyz/nds-notes/blob/main/AR%20Codes%20ive%20made/Pokemon%20Link%20Codes.txt">Pokemon Link!</a> (7 Codes)</summary>
  <hr>
  
  - Always Have Max Score
    - <pre>022101C4 7FFFFFFF
      02210260 7FFFFFFF</pre>
  - Always Have 0 Pokemons Remaining
    - <pre>022101BC 00000000
      02210330 00000000</pre>
  - Always Have 1 Pokemons Remaining
    - <pre>022101BC 00000001
      02210330 00000001</pre>
  - Disable Bonus Combos
    - <pre>022101CC 00000000
      02210284 00000000</pre>
  - Always Have Max Bonus Combo
    - <pre>022101CC 7FFFFFFF
      02210284 7FFFFFFF</pre>
  - Infinite Clear Bonus
    - <pre>022103D8 7FFFFFFF
      027E382C 7FFFFFFF</pre>
  - Infinite Prize Coins
    - <pre>0210556C 7FFFFFFF</pre>
  <hr>
</details>

<details>
  <summary><a href="https://github.com/miso-xyz/nds-notes/edit/main/AR%20Codes%20ive%20made/Tetris%20Party%20Premium%20DS%20Codes.txt">Tetris Party Premium DS</a> (7 Codes)</summary>
  <hr>
  
  - Freeze Timer (00:00:00)
    - <pre>0230AE64 00000000</pre>
  - Freeze Timer (999:59:96)
    - <pre>0230AE64 001B773F</pre>
  - Always Have Max Score
    - <pre>0230AF60 7FFFFFFF</pre>
  - Always Have 0 Score
    - <pre>0230AF60 00000000</pre>
  - Always Have 0 Lines Clear
    - <pre>2230AF50 00000000</pre>
  - Always Have 150 Lines Clear (Auto-Finish)
    - <pre>2230AF50 00000096</pre>
  - Always Have 9999 Lines Clear (Auto-Finish)
    - <pre>2230AF50 7FFFFFFF</pre>
  <hr>
</details>

<details>
  <summary><a href="https://github.com/miso-xyz/nds-notes/blob/main/AR%20Codes%20ive%20made/Trackmania%20Turbo%20DS%20Codes.txt">Trackmania Turbo DS</a> (7 Codes)</summary>
  <hr>
  
  - Always Have Max Coppers
    - <pre>0227ED6C 7FFFFFFF</pre>
  - Freeze Timer (00:00:01) & No Starting Countdown - Stadium & Snow
    - <pre>021EF2D8 00000000</pre>
  - Freeze Timer (00:00:01) & No Starting Countdown - Island
    - <pre>0226A868 00000000</pre>
  - Freeze Timer (00:00:01) & No Starting Countdown - Coast
    - <pre>021EF968 00000000</pre>
  - Freeze Timer (99:59:98) - Stadium & Snow
    - <pre>021EF2D8 10000000</pre>
  - Freeze Timer (99:59:98) - Island
    - <pre>0226A868 10000000</pre>
  - Freeze Timer (99:59:98) - Coast
    - <pre>021EF968 10000000</pre>
  <hr>
</details>

<details>
  <summary><a href="https://github.com/miso-xyz/nds-notes/blob/main/AR%20Codes%20ive%20made/Doodle%20Jump%20Codes.txt">Doodle Jump DS</a> (6 Codes)</summary>
  <hr>
  
  - Max Points
    - <pre>0206CFA0 7FFFFFFF
      0206CFA8 7FFFFFFF
      0206CFB0 7FFFFFFF
      027E3664 7FFFFFFF</pre>
  - Crazy Fast Levitation (Collisions disabled)
    - <pre>0205784D 7FFFFFFF</pre>
  - Levitation (Collisions disabled)
    - <pre>0205784D 0000FFFF</pre>
  - Slowfall (Collisions disabled)
    - <pre>0205784D 00000100</pre>
  - Infinite Shield
    - <pre>320531C5 0000007F
      32057884 0000007F</pre>
  - Infinite Jetpack, Flying Hat & Rocket
    - <pre>320577CD 0000007F
      320577F9 0000007F</pre>
  <hr>
</details>

<details>
  <summary><a href="https://github.com/miso-xyz/nds-notes/blob/main/AR%20Codes%20ive%20made/Need%20For%20Speed%20-%20Undercover%20Codes.txt">Need For Speed - Undercover</a> (4 Codes)</summary>
  <hr>
  
  - Freeze Police Cars
    - <pre>022956D8 000F423F
      022956E4 000F423F</pre>
  - Always Have Nitro
    - <pre>021AD7B8 00000064</pre>
  - Always Have Nitro + Nitro Bar Extends Out of the bottle sprite
    - <pre>021AD7B8 7FFFFFFF</pre>
  - Always Have No Nitro
    - <pre>021AD7B8 00000000</pre>
  <hr>
</details>

<details>
  <summary><a href="https://github.com/miso-xyz/nds-notes/blob/main/AR%20Codes%20ive%20made/Picross%203D%20Codes.txt">Picross 3D</a> (1 Code)</summary>
  <hr>
  
  - Unlock All Extra Stages (Silver & Gold)
    - <pre>020FFD22 0000007F
      02214F26 0000007F
      022156B4 0000007F
      022156E8 0000007F</pre>
  <hr>
</details>

<details>
  <summary><a href="https://github.com/miso-xyz/nds-notes/blob/main/AR%20Codes%20ive%20made/Trackmania%20DS%20Codes.txt">Trackmania DS</a> (1 Code)</summary>
  <hr>
  
  - Freeze Timer (00:00:01) & No Starting Countdown
    - <pre>02151588 00000000</pre>
  <hr>
</details>

- - - -
