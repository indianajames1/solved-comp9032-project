Download Link: https://assignmentchef.com/product/solved-comp9032-project
<br>
<u style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Description:</u>




<a href="https://www.megafungames.com/games/cup_game/">Cup and Ball</a> [1] is an online game where a ball is shuffled under three cups and you guess the position of the ball. For each guess, you gain one point if it is correct or lose one point if it is wrong. (Click the picture in Figure 1 for a fun try on this game.)




<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/02/917.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/02/917.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>                                                                              Figure 1




In this project, you will be working <strong>individually</strong> to develop a system, using the AVR Lab board, to simulate the game (with some modifications).




In this system, the push button is used to start the game; Three LEDs are used to represent the three cups, and these LEDs together with the motor are also used to indicate the ball shuffling among the three cups; the key board (replacing the mouse in the original game) is used for the player to make a guess; the player’s score is displayed on LCD, as indicated in Figure 1.




For the LED bar on the lab board, two groups of LEDs are used, as shown in Figure 2. Three LEDs, called <em>cup LED</em>s, are associated with three cups (as mentioned before) and the four LEDs of the other group work as a result indicator for a guess. When a guess is correct, the indicator will flash.




LED Bar

<table width="285">

 <tbody>

  <tr>

   <td width="30"> </td>

   <td width="25"> </td>

   <td width="25"> </td>

   <td width="25"> </td>

   <td width="46"> </td>

   <td width="25"> </td>

   <td width="25"> </td>

   <td width="25"> </td>

   <td width="25"> </td>

   <td width="30"> </td>

  </tr>

 </tbody>

</table>

Result Indicator




<h1>Figure 2</h1>

Each operation of the system and the related inputs/outputs are described below.




<ol>

 <li>After the simulation system is turned on (i.e. the lab board is powered on), the system is initialized and the ball is with an arbitrarily cup. In this case,</li>

 <li>“Ready…” is displayed on LCD;</li>

 <li>The cup LED with the ball is on, as illustrated in Figure 3 (a), where the ball is with Cup 3. Other LEDs are off.</li>

</ol>




<h1>Figure 3 (a)</h1>




<ol start="2">

 <li>When the push button is pressed, the game starts and the ball is shuffled under the three cups. In this case,</li>

 <li>“Start …” is displayed on LCD;</li>

 <li>Motor spins;</li>

 <li>Three cup LEDs are all on, but in <strong>dimmed light</strong>; other LEDs remain off, as shown in Figure (b).</li>

</ol>




<h1>Figure 3 (b)</h1>




<ol start="3">

 <li>When the player wants to make a guess for the ball position by pressing the push button again, the ball shuffle stops. In this case,</li>

 <li>The motor stops;</li>

 <li>The three cup LEDs remain dimmed, as shown in Figure (3)(b);</li>

 <li>After the player keys in the ball position on the key pad, the cups are removed, the ball position is uncovered and the score is determined. In this case,</li>

 <li>The cup LED with the ball is fully on, as illustrated in Figure 3</li>

</ol>

(c), where the ball is now with Cup 2; ii. If the player’s guess is correct, the score on the LCD is incremented by 1 and the indicator will flash a few times, as illustrated in Figure 3 (c)(i); otherwise,

iii. If the guess is incorrect, as illustrated in Figure 3 (c)(ii), the score on LCD is decremented.







<h1>Figure 3 (c)</h1>




<ol start="4">

 <li>When the player’s score becomes zero, the game will be reset to the initial start status; otherwise, the game can be continued by pressing the button for a new round of ball shuffle.</li>

</ol>










In your design, you need to decide how to shuffle the ball. You can add extra functions to make your design better (which is optional) and you are also allowed to make assumptions that you think are necessary but not given in this project specification.













<u>Reference</u>




[1] https://www.megafungames.com/games/cup_game/


































<u>Submission Information:</u>




The following items should be submitted:

<ol>

 <li>Source code. Your program should be well commented.</li>

 <li>User manual (up to 3 pages). The user manual describes how to use your simulation system, including how to wire up the AVR lab board.</li>

 <li>Design manual (up to 5 pages). The design manual describes how you design the simulation system.</li>

</ol>

Both manuals should be written well. A person with knowledge about the course and the lab board should understand how your system is designed and how to use your system after reading the given manuals.


