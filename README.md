# Demon Dialer HACKTIC PCB
New PCB of the BlueBox Demon Dialer by HACKTIC from an idea of Don Froula

The Demon Dialer is a BlueBox featured in [Issue No.14/15 of the HACKTIC Magazine](https://archive.org/details/hacktic-14-15_202105/page/48/mode/2up) [1991].


| FRONT  | BACK  |
| ------ | ----- |
| ![PCB_PCB_Demon Dialer V2_2023-05-27_FRONT.png](https://github.com/spinoinside/Demon_Dialer_HACKTIC_PCB/blob/main/images/PCB_Demon_Dialer_V2_2023-05-27_FRONT.png) | ![PCB_Demon_Dialer_V2_2023-05-27_BACK.png](https://github.com/spinoinside/Demon_Dialer_HACKTIC_PCB/blob/main/images/PCB_Demon_Dialer_V2_2023-05-27_BACK.png) |

| SCHEMATIC |
| --------- |
| ![Schematic_Demon_Dialer_2023-05-27.png](https://github.com/spinoinside/Demon_Dialer_HACKTIC_PCB/blob/main/schematic/Schematic_Demon_Dialer_2023-05-27.png) |
| [Schematic_Demon_Dialer_2023-05-27.pdf](https://github.com/spinoinside/Demon_Dialer_HACKTIC_PCB/blob/main/schematic/Schematic_Demon_Dialer_2023-05-27.pdf) |

| FRONT  | BACK  |
| ------ | ----- |
| ![PCB_assembled_FRONT.jpg](https://github.com/spinoinside/Demon_Dialer_HACKTIC_PCB/blob/main/images/PCB_assembled_FRONT.jpg) | ![`PCB_assembled_BACK.jpg`](https://github.com/spinoinside/Demon_Dialer_HACKTIC_PCB/blob/main/images/PCB_assembled_BACK.jpg) |

| FIRST PROTO |
| --------- |
| ![All_Parts.jpg](https://github.com/spinoinside/Demon_Dialer_HACKTIC_PCB/blob/main/images/All_Parts.jpg) |

# Command List

| Command | Function |
| ------- | -------- |
| ^ 1 2 3 4 | Password |
| 2 5 ^8 7 8 ^3 7 3 ^8 2 5 |Master Password |
| ^* ^*	| Power Off |
| ^* 0 |	Mode Touch-Tone [DTMF] |
| ^* 1 |	Mode ATF1 [B-netz] |
| ^* 2 |	Mode R2-forward |
| ^* 3 |	Mode CCITT No. 3 [C3/pulse dial] |
| ^* 4 |	Mode CCITT No. 4 [C4] |
| ^* 5 |	Mode CCITT No. 5 / R1 [C5] <br> ^1 is called 'Code 11' <br> ^2 is called 'Code 12' <br> ^3 is ‘KP1’ <br> ^4 is ‘KP2’ <br> ^5 is ‘ST’ <br> ^6 lasts 500ms <br> ^7 is 120ms <br> ^8 is 120ms <br> ^9 is 240ms  <br> ^0 is a silence of 50ms <br> * is called clear forward and lasts 175ms <br> # is called seize and lasts 300ms <br> ^6 2600Hz |
| ^* 6 |	Mode RedBox |
| ^* 7 |	Mode line signaling menu |
| ^* 8 |	Mode tone slot |
| ^* 12 |	Mode R2-backeard |
| ^* 18 |	Mode user programmable (RAM-mode) |
| ^# |	Macro mode |
| ^<0-9> |	Record macro (0 to 9) <br> Press # to confirm programming <br> To end macro recording press ^# followed by # <br> To go back to normal operation just press # |
| ^* * 0 |	Initialize the device <br> Press # to confirm |
| ^* * 1 |	RAM FIN programming (0 to 11) <br> Type ^* * 1 \<FIN\> # <frequency> # |
| ^* * 2 |	Time template programming <br> Typing ^* * 2 \<time-template number\> \<time in msec\> # |
| ^* * 3 |	Guard tone programming (0, 1 or 2) <br> Press ^* * 3 \<Guard tone number\> \<FIN\> # |
| ^* * 4 |	Start guard tone <br> Pressing A* * 4 \<guard tone number\>  will turn on that guard tone. |
| ^* * 5 |	Stop guard tone <br> If a guard tone is on, ^* * 5 will stop it. |
| ^* * 6 |	Frequency stepping <br> Pressing ^* * 6 \<start frequency\> # \<step size\> # will sound the start frequency.  |
| ^* * 7 |	Sweep tone (Frequency response testing) <br> Press # to stop |
| ^* * 8 |	Password protection on |
| ^* * 9 |	Password protection off |
| ^* * *	| Number scan <br> Type ^* * * \<play macro\> \<number macro\> \<step size\> # |
| ^* ^#	| Hookswitch control |



# Links

 * [Willem GitHub](https://github.com/nlitsme/HACKTIC_demon_dialer) aka itsme, a member of HACKTIC, is the one who wrote the code
 * [Project MF](http://www.projectmf.org/) a living simulation of a blueboxable phoneline
 * [Don Froula GitHub](https://github.com/donfroula)
 * [Don Froula YouTube](https://m.youtube.com/user/df9999999999/videos)
 


