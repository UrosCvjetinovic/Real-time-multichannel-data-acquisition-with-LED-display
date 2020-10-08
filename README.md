# Real-time-multichannel-data-acquisition-with-LED-display

Implemented acquisition started by a task timer and displayed on a LED display. Software timers for debouncing and updating LED display. Task 2 notifies Task 1 if a button is pressed, what channel is selected, with direct-to-task notifications. Task 1 reads acquired data queue and sends to task 3 through a mailbox. Task 3 displays the difference of the two last values.
