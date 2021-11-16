# Music Box
Music Box is a tile based music creation website made with the Web Audio API. Currently at https://music.prussia.dev.

## Features
- Adjust tempo
- Enable looping
- Listen to your tune on the site
- Export the file as a txt file and import it back in
- Save the song as an mp4 file (note gap not supported, gaps in song also not supported yet)
- Has 36 notes
- Adjust length of song (adjust columns)

## Notes
Uses [Crunker](https://github.com/jackedgson/crunker), an awesome library that lets users easily merge, concatenate, play, export and download audio files with the Web Audio API.

Hosted on Repl.it. 

Looks ugly on mobile, sorry.

If you find a bug please open an issue.

It is also likely I will add support for other instruments with https://tonejs.github.io/.

You can find examples in the `examples` folder

## Known Bugs
- Saving song as mp4 file does not include note gap or gaps in song (actually gaps in song now probably included?)
- Pause sometimes broken, who knows why though