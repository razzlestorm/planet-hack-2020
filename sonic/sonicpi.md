# Sonic Pi goodness
Alex's plan is to:
* Pull raw data points (generated by MY FRIENDS) at a specified time interval
* Map data points from expected data range to audio frequency range
* Quantize data points to notes of a chord, across the entire frequency range
* Play the note
* Additional notes for one-off events, in different voices?
* Change the chord periodically (4-chord sequence?)
* Write a song over it! :3 (depending on the type of data we feed in)

I've decided to go with Sonic Pi for this, since it has timing and sound generation built in! Plus, it can easily be embedded into a standalone device (Raspberry Pi), but I can also develop it right on my Mac.

## Code
* [Sonic Pi arpeggiation gist](https://gist.github.com/alexglow/f2d3c74731f1f608d29b71cee3db79cd)

## Reference
* [Alex's thread on Sonic Pi forum](https://in-thread.sonic-pi.net/t/data-sonification-quantizing-data-to-notes-in-switchable-chords/4505)
* [Previous thread with info on quantizing notes](https://in-thread.sonic-pi.net/t/force-random-notes-into-a-scale-after-transposing/4493/2)