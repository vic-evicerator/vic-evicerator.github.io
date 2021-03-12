---
title: "Bellum Aeternum - Technical Improvements"
date: "2007-07-09"
category: History
tags: [Rampage,Bellum]
---

The biggest improvement on *Bellum Aeternum*, musically speaking, is the greater range of gear and power of the gear used between the first incarnation and the current one. Some details are below: INSTRUMENTS

Back in 1999, I had just gotten my new Jackson Rhoads-style V (RX10D, actually), and it was an order of magnitude better than my Warlock, so I used that one guitar for all the electric guitar parts. I have a Fender acoustic I used for "The Wakening". I had two basses at the time - the P-bass and my Ibanez Destroyer. On everything I did up to that time I used the Destroyer, and so I wanted to switch up and give my P-bass a workout. However, due to other limitations detailed below the P-bass just didn't get the right sound, so I ended up redoing all the songs but one with the Destroyer.

I still have the Jackson V and the acoustic, but I also have my SG and my Strat. The extra electric guitars allowed me a wider sound palate for recording, and I used it to the max. Being metal, of course, I had to use humbuckers, so the bulk of guitars are the SG and the V, but I switched and mixed the instruments to tailor to the sounds of the songs. The V, being a standard scale length, has a good, tight, crisp sound, well-suited to crunching and faster riffs. The SG has that Les-Paul type shorter scale length, with its consequent darker, more rumbly tone, better served on doomier riffs. "Soulsword", for example, is a classic doom song, so the SG was used exclusively on the rhythms on that one. "Rainbow Skies", on the other hand, is much more thrashy and 'active', and so the V worked better there. On a couple of songs I mixed just to get contrasting sounds ("Excalibur" is one I remember offhand, though I'm sure there are others...). I did over half the solos on the V, but did make sure to use the SG for solos where a whammy bar wasn't necessary. "Rainbow Skies", despite having the V for rhythms, has the SG for the solo. For "The Wakening", since it's a lead trade-off, has both guitars, one doing each part.

Speaking of "The Wakening", that's where my Strat got used. Every other clean part on the album is my SG, which just has a better tone for that kind of thing, but with "The Wakening", which is built on an acoustic guitar strum, I wanted that unique out-of-phase Strat-type Mark Knopfler tone. It blends very well with an acoustic and makes that whole section sound, I think, quite a bit better. I even extended the intro to add a short Knopfler-like solo before the tradeoffs start.

To get that Strat, though, I had to sell my Destroyer, so I only had the P-bass for bass tracks. However, thanks to all the new outboard gear and better PC, I was able to get a much better sound, and it all worked out fine. And that leads us to...

OUTBOARD GEAR

My signal chains were very simple on the 1999 album:

Guitar->Boss Metal Zone->Boss Comp-lim->Rockman Chorus->PC

Bass->Boss Comp-lim->Rockman Chorus->PC

Direct, dry, and with a chorus unit for solos, mellow bits, 'special effects', and that's it. That's fine, really - for me, this album is about the songwriting, not the effects, but sometimes the right spice can make a dish come alive, and it's nice to have a fully stocked spice rack to call upon when you feel the need. So, this time around, I had this:

Guitar or Bass->Rocktron RepliTone->Boss Comp-lim->Rockman Chorus->Mixer->PC

Doesn't really look all that more complicated - replace the pedal with an amp and add a mixer. I still use the Comp-lim to round off gross volume variations, and the Chorus is still optional as-needed. However, the other parts are vital, and the key to making this album, I think, sound leagues better than the original.

The Mixer is another level of volume regulation before getting to the PC, as well as allowing me some basic input EQ and making it so all my plugins are on the desktop, not under the computer table. Also, I could use the mixer's input trim when micing the acoustic guitar so I actually got a decent sound, without the hassles I had to go through to record it the first time. The RepliTone is the magic ingredient, though. Notice how there's no more stompbox distortion. Even as good as you can make the Metal Zone sound (if you know what you're doing), it doesn't compare to a real amplifier. And I suppose some might quibble over whether digital emulation is 'a real amplifier', but even the most ardent tube-o-phile will admit that a digital processor built into an amplifier is a helluvalot better than a little pedal.

Furthermore, the amp has emulation for a variety of different amps - 15 total - not to mention 3-band parametric EQ, gain control, and lots of built-in effects, not to mention reverb. A touch of natural reverb really made the guitar sounds come alive, and through some variations and experiments I came up with three basic rhythm guitar sounds I liked, based on two different emulation modes. Between having two rhythm guitars and the presets I saved, I was able to really give each track its own distinct guitar sound. Also, I saved a couple of different bass sounds as well. Some of the emulation modes are for classic clean amps, so I was able to really get vibrant, alive bass sounds, rather than my former method of using the Boss Comp-lim as a preamp.

Also, the effects built into the amp allowed me to do much more than just the old Chorus unit. I love the sound of Rockman, though, and I did use it quite a bit, but there's some amp chorus as well, a bit of flange or phasing here and there, and some amp-based delay - all in addition to the amp reverb of course. I wasn't limited there with regard to effects, either; the PC had plenty more options in that regard also, and that leads us to our next section...

COMPUTER

This comparison is best suited to a table.

| Item | Old PC | New PC |
|--- |--- |--- |
|Processor |P2-166 |P3-933 |
|Memory |128MB |512MB |
|Disk Space |C: 2GB, D: 500MB |C: 120GB, D: 80GB |
|Sound Card |SoundBlaster AWE64 |Audiotrak Maya44 |
|Recording Platform |Magix Music Studio 3.0 |Sonar 2.0 XL |
|Track Capacity |8 audio, 128 MIDI |As many as the PC can handle |
|Export directly to WAV? |No |Yes |
|DirectX/DirectSound |No |Yes |


That about says it. Given the track limits, the slower old PC did well performance wise. It was just limited. The disk limit was harder to work around the first time. 2GB on my C drive was just about eaten up with the OS and other programs, so the D drive was my audio drive, and 500MB goes fast when you are eating up 5MB per minute per track and have at least six tracks per song with an average length of over five minutes. That's why I was almost forced to record the first Bellum at 22.05 instead of 44.1 - I needed to do that just for the disk space.

The bigger limits were the last two items. Mixing to tape sucks, because it's real-time, and, well, it's tape. Those old UHR albums may be the world's only DAD albums. But I digress. Even the mixing-down issue pales in comparison to DirectSound/DirectX. Back in the 'good old days', we did have sample-based synthesis for MIDI (Sound fonts, wavetable synthesis, etc.), which resulted in decent sounding programmed things - however, soundcards only had one digital audio output, so playing MIDI not only used up your computer's MIDI controller, it also used up your audio controller. Which means, if you want to have your recorded audio playing with real-live samples, you have to render them. And since the audio/mixer software on my soundcard didn't work, I couldn't just direct the 'out' stream back in for recording, so I had to physically connect my 'out' to my 'in' with a patch cable and press 'play' to dub programmed elements to wave in real-time - with resulting loss in quality by being decoded and encoded once just in recording. For songs with keys and multiple programmed parts, not just drums, you had to do that ONCE for EACH instrument or track you wanted (and do this while keeping in mind that each track you dub bumps up against that 8-track audio limit). That's why I only rendered drums on *Bellum Infinitum*, and left all the other programmed instruments in MIDI.

Now, of course, DirectSound has made everything in that regard much easier - and the synths built in to or bundled with Sonar make it even easier, AND give you much more power to manipulate the sound. All your MIDI can be rendered real-time, edited/effected non-destructively, AND you can apply effects to the output audio stream(s). So you could, for example, send your snare drum to a separate virtual output from the rest of the drumkit and give it a bigger reverb setting, or apply chorus and delay to programmed instruments, or even use an amp simulator on a keyboard patch to get that fat, dirty 'key through a marshall' distorted keyboard/Jon-Lord-type sound. And I did all that and more. (Well, maybe not EXACTLY like Jon Lord, but that's what I was going for...).

So, as you can see from all of the above, I really had a lot more options and a lot more power to record things exactly the way I wanted them and to experiment with a lot of different effects, processing options, etc., without sacrificing anything. Furthermore, I had six years more recording experience under my belt, so I wasn't flying quite so blind and could try some of these ideas ground-up instead of having to go back and redo something if I had something else I wanted to try halfway through a song. Some of the things I changed about the songs themselves, though, will have to wait for another post...

***

*(Another invaluable post. While the songwriting posts are great song-by-song, connecting each to its inspiration, the disparately-sourced songs all end up connected by intention, and it's that connection, the forging not just of ideas but of combining those ideas into a grand, unified whole that really makes making an album a gratifying act. Posts like this strike right at the heart of why I do this.*

*Also, that chart of the differences between my first and second studio PC is a jewel beyond price, and very telling. And the increase between that new one, which is now the old one, and the one I'm writing on now is similarly impressive.*

*And seeing that makes me really want to show off what it can do.)*
