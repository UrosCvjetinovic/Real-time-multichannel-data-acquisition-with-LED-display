# Real-time-multichannel-data-acquisition-with-LED-display

Implemented acquisition started by a task timer and displayed on a LED display. Software timers for debouncing and updating LED display. Task 2 notifies Task 1 if a button is pressed, what channel is selected, with direct-to-task notifications. Task 1 reads acquired data queue and sends to task 3 through a mailbox. Task 3 displays the difference of the two last values.

<br><br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/59072921/95519050-a1ef8100-09c4-11eb-9984-a1f823102767.png">
</p>
