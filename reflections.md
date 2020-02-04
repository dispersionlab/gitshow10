># Score:

>1. Unmute the first two channels to start.

>2. Learn the pace, find the duration that suits you.

>3. Unmute the next two channels.

>4. Adjust the timing, learn the connections.

>5. Make a mess.

>6. Cut down to the start.

>Lean back and enjoy when you've found your sequence, or your chaos.

>Be gentle though, unwelcome appearances can occur.


## First Thoughts

The track begins with a slightly low bassline that quickly transforms with additional layers.  These layers, like the catalyst bassline before it, seem expected, slightly distorted at times, but well within recognizable patterns.  One minute in (~60s) and chaotic sounds appear, although in an orderly fashion (such as their time scale), but seemingly more random in their play.

### VCV Rack

![Imgur](https://i.imgur.com/KJp0kVZ.png)

As shown in the image above, the recording was achieved with a 17 module setup that looks pretty clean and organized.  Patching cable amount seems large yet really easy to follow.  Notable modules for me at first glance was the Quantizer. Seeing how that works in this rack makes me want to work with this module in my first edit.

### Score

Having been playing with the idea of using the dot language for notation in this exercise, so I tried to imagine what the score would look like for this recording (sketch below).


![](https://i.imgur.com/2icic2r.png)


#### Analysis

The score sample image above suggests the following 4 events:

00:00 - Pattern begins with BPM set to 139
00:11 - An echo effect begins to emerge
00:13 - Slow rising pitch w/reverb
00:20 - Glitchy high pitched digital sound w/reverb

This glitchy sound continues to repeats at a medium pace, then cuts off that particular pattern at around 00:50.

---

## Performance

Here is the state of the amended modules seleted:

![](https://i.imgur.com/0eFzkGQ.png)

The changes can roughly be defined as follows:

1. `BPM` changed to `101` in `GNOME` module.
2. Patch cable added between `GNOME WIDTH` and `LFO-1 TRI` waveform.
3. Created 3rd channel in `8VERT` connecting a patch cable from `VCO-1 SAW` waveform to its input and a patch cable from `8VERT` output of 3rd channel to `Quantizer (QNT) IN`.
4. Create 4th channel in `8VERT` connecting a patch cable from `VCF LPF` to its input and a patch cable from `8VERT` output of 4th channel to `Mixer8 IN 5`.  Dial on `8VERT` 4th channel turned to 9-o'clock.
5. Muted channels 1 through 4 of `Mixer8`.

### Deep Bass Telegraph

![](https://i.imgur.com/oF1kA3u.png)

Deep Bass Telegraph is a newer version of Birdy Telegraph, using the same modules and a few patch cable reroutes to give a deep bass sound.
