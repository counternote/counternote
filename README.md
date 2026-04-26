***

Counternote is a chromatic musical language meant to be typed and sung. It is a work in progress so there may be errors.

### Jump to [QUICK START][quick start]

[quick start]: #quick-start

# Drive

Counternote is an answer to a question that a lot of people have asked despite a solid solution already existing — namely, is there a [Markdown][md] for music, by which they mean a human readable plaintext music notation? The answer is yes: it’s called [ABC notation][abc], and it’s great. If that’s all you are looking for, you do not need to read more. Go support it!

However, ABC notation is not a music notation directly. It’s a music notation *notation* with another layer of translation (music —> staff —> ABC). Counternote is a different kind of abstraction from western music notation, a linguistic one, not a visual one, so it can be written in plaintext directly (music —> Counternote).

Counternote has been created as a complementary foil to the venerable staff notation, not a replacement. Even the most seasoned of musicians is likely to gain another perspective on music by learning it.

But this is not a one way street. Counternote is not yet set in stone and is still being tweaked, so any relevant feedback or constructive criticism will be considered and appreciated. You can join the [Discord][dc] and suggest away.

[md]:https://daringfireball.net/projects/markdown/ "John Gruber’s Markdown Spectacular"
[abc]:https://abcnotation.com/ "ABC notation"
[dc]:https://discord.gg/SvWfPwpxEv "Counternote server invite"

***

# Design

There are five design principles that guide Counternote’s take on a musical notation: It must be readable, typeable, singable, codeable, and shareable. Unfortunately, satisfying all five of these constraints perfectly is impossible. Design is compromise just as life is pain — *anyone who tells you differently is selling something*.

For readability, the notes are simple and unambiguous — a note never has more than one name and is descriptive enough to make some intuitive and logical sense. The same goes for intervals and chords. They are organized in a way that can be sightread rather easily while still allowing for durations and articulations to appear in the same line like punctuation and dynamics, accompaniments, and other details appear in parallel above or below the line to avoid clutter. 

For typeability, everything is written in the printable characters of 7-bit ASCII which are easily typed by humans. The notes require as few keystrokes as possible, both to make typing faster and to take up less space on the line. In the process of compressing the written length of the notes, some characters have had their pronunciation reassigned and common digraphs have been eliminated, limiting them to just one consonant, vowel, or vowel-consonant pair per character.

For singability, each note is one syllable, as are each interval distinct from the notes. The simple idea here is that music is not an abstract notion, it’s something that we can mimic concretely. So these elements are onomatopoeic and autological — that is, imitative and self-descriptive. The closer a symbol is to its actual pronounciation and meaning, the easier it is to remember. But notes are more than just hitting a correct pitch — they’re about any kind of vocalization, so the percussive sounds like those from beatboxing to click languages find representation here.

For codeability, everything is written in ASCII which is easily interpretted by computers and backed up with git. However, great care has been taken to make notational aspects not feel like code. Raw numbers for duration and pitch have been eliminated — the few numbers that exist in the notation are ordinal numerals to mark the bars. No function invocations are necessary to make a sound. And the control flow of the notation is at least as simple as staff notation.

For shareability, everything is just a string of plaintext, easily shared via text message and read in monospace. There is no need to translate it into a human consummable format and back to a computer-readable one, no heavy filetype to send and store, no binary blobs to contend with. What you see it what you get.

***

# Quick Start

Don’t let the idea that Counternote is a musical language trouble you. The way to learn Counternote is by practicing music, and practicing Counternote will help you learn music. If you are reading this, you are probably motivated to do one of those things.

Because every field tends toward jargon with big and important words the deeper you get into it, and occasionally those words conflict with common usage, all terms in Counternote are simple and precise, each limited to one syllable and an easy definition.

# Sounds

Sounds in Counternote come in two varieties — those where pitch is the defining characteristic, *tones*, and those where pitch is indeterminate or incidental, *raps*.

## Tones

First up to introduce are the twelve *tones*. These refer to absolute pitch when capitalized, but are otherwise movable within a piece like scale degrees. You may think of them as fixed-do solfège when capitalized and movable-do tonic solfa when lowercase:

    ——————————————————————————————————————————————————
      C   C♯  D   D♯  E   F   F♯  G   G♯  A   A♯  B
      MA  KA  DA  SA  JA  LA  HA  NA  CA  ZA  TA  GA  
    ——————————————————————————————————————————————————

You’ll notice `ka` and `ca` seem like they might sound the same, but they don’t — `c` is a 'ch' sound in Counternote, always. 

*Tones* that are capitalized are used almost exclusively for setting the tonal center of a piece, known as the *key*. Uppercase or lowercase, they consist of a *start*, the first letter:

    ———————————————————————————————
      START  OFFSET  IPA  ENGLISH
    ———————————————————————————————
        h-     +6      h     'h'
        l-     +5      t     't'
        j-     +4     dʒ     'j'
        s-     +3      s     's'
        d-     +2      d     'd'
        k-     +1      k     'k'
    ———————————————————————————————
        m-     ±0      m     'm'
    ———————————————————————————————
        g-     -1      g     'g'
        t-     -2      t     't'
        z-     -3      z     'z'
        c-     -4     tʃ    'ch' 
        n-     -5      n     'n'
    ———————————————————————————————

And a *rhyme*, the second (and third) letter:

    —————————————————————————————
      RHYME  FILE  IPA  ENGLISH
    —————————————————————————————
       -il    +5    il   'eel'
       -al    +4    al   'ahl'
       -l     +3    ɛl   'ehl'
       -i     +2    i     'ee'
       -e     +1    e     'eh'
    —————————————————————————————
       -a     ±0    ɑ     'ah'
    —————————————————————————————
       -o     -1    o     'oh'
       -u     -2    u     'oo'
       -r     -3    ɚ     'er'
       -q     -4    ɑ˞    'ar'
       -or    -5    ɔ˞    'or'
    —————————————————————————————

In Counternote, when we want to talk about the pitch-class of a note, like every traditional note labeled C, we are talking about the *rank*. And when we want to talk about a specific octave, we are talking about the *file*. The *starts* and *rhymes* go *rank* and *file*.

By default, `ze` is *A440*, so `za` sounds an octave below it.

### Absolutely Relative

There is an inherent tension between an absolute frequency like *A440* and a relative frequency like the 5 in the key of D. The first is more about physics and less about music. The second, though, is what music is based on. In a very real sense, relative pitch is closer to the musical metal.

In fact, relative pitch is so important that there are no less than four ways to express it beyond the staff:

* as intervals like __m3__ and __M6__
* as scale degrees like __♭3__ and __6__
* as movable-do solfège (tonic solfa) like __me__ or __ma__ and __la__
* as integer notation __3__ and __9__

Each of those has problems, chief among them is that the only one that doesn’t use numbers is readily confused with a fixed-do solfège used in half the world.

By relegating the absolute pitch terms to simply setting the tonal center, we can avoid the kind of confusion that transposing instruments have, or the confusion that fixed-do and movable-do has. For transposing instruments, the *key* is set to key of the instrument, so B♭ instruments should use the *key* `TA` and alter the *mode* using chords. `TA` remains `TA`, its pitch always well-defined, while `ma` becomes B♭ and every lowercase *tone* is relative to it.

## Raps

The last kind of sound in Counternote is whatever doesn’t fit in the tones. These include noise, drums, non-standard ways of producing sound on an instrument, and even memes.

Compared to tones, raps are easier to demonstrate because they’re just a list of mostly user-defined sounds. They are also harder to learn because they’re just a list of mostly user-defined sounds. There are two basic rules for creating raps, only the first of which must be followed:

* they cannot overlap with tones or reserved raps
* they should sound like what they stand for

These are some proposed raps, only the first three of which cannot be defined on a piece by piece basis:

    ————————————————————————
      RESERVED
    ————————————————————————
      `aa` tie
      `hh` breath (rest)
      `sw` spoken word
    ————————————————————————
      USER-DEFINABLE
    ————————————————————————
      NOISE
      `hx` hush, silence
      `nh` inhale
      `xh` exhale
      `ss` blue noise
      `xs` white noise
      `xx` pink noise
    ————————————————————————
      DRUM
      `pf` pf snare
      `ks` k snare
      `kk` kick drum
      `bn` small bass drum
      `bm` large bass drum
      `dn` high tom
      `dm` mid tom
      `gn` low tom
      `gm` floor tom
      `tx` opening hi-hat
      `ts` open hi-hat
      `xt` closing hi-hat
      `st` closed hi-hat
      `kt` rim shot
      `cx` crash
      `xp` crash mute
      `cs` ride
      `sp` ride mute
      `xk` shook
      `kl` clap
      `td` bright clave
      `dd` dark clave
    ————————————————————————
      GUITAR
      `rk` rake
      `dt` deep tap
      `tt` light tap
      `dk` dark tick
      `tk` bright tick
      `hd` handmute
      `sk` strum mute
    ————————————————————————
      OTHER
      `rf` ref whistle
      `ws` Wilhelm scream
      `rn` siren
      `ck` crickets
      `cp` chirp, cheep
      `jz` the licc
      `lk` laugh track
    ————————————————————————

Practice beatboxing with these if you like.

# Notes

Notes in Counternote refer specifically to *sounds* held for some duration. That duration is denoted by a *click*.

## Clicks

Clicks are basic punctuation characters that are roughly equal to a whole note to a thirty-second note that must come immediately after the sound they sustain. These can be extended by trailing *clicks* in the same bar or by adding the rap `aa` with a new click at the beginning of the next bar.

The six *clicks* ordered by powers of two are as follows:

    ————————————————————————————
      CLICK  VALUE  WORD   IPA
    ————————————————————————————
       `;`    1/32   pi    pi
       `:`    1/16   pe    pe
       `,`    1/8    pa    pa
       `.`    1/4    po    po
       `-`    1/2    pu    pu
       `=`    1/1    pq    pɑ˞
    ————————————————————————————

Plus two others, immediate and indeterminant:

    ——————————————————————————————————
      CLICK     VALUE     WORD   IPA
    ——————————————————————————————————
       `!`    immediate    pl    pɛl
       `?`  indeterminant  pr    pɚ
    ——————————————————————————————————

The wider the character, the longer the duration, the narrower and taller the character, the shorter the duration.

## Grooves and Pulses and Snaps

*Grooves* tell the duration of a bar. They are written between `|` characters with the number of *clicks* like `|4.|` or `|....|`, both of which are identical and equivalent to the 4/4 time signature. However, one could specify 4/4 as `|4,|` or `|,,,,|` for upbeat numbers or `|4-|` or `|----|` for more languid tunes.

Here are four rather boring bars of Counternote:

    —————————————————————————————————————————
      # |4.|
      1
        | ma=                             |
      2
        | ma-             ma-             |
      3
        | ma.     ma.     ma.     ma.     |
      4
        | ma, ma, ma, ma, ma, ma, ma, ma, |
    —————————————————————————————————————————

You’ll notice that each of those notes takes up at least four spaces. There is a short cut that makes each note only take up three spaces and cuts down on visual noise. You’ll never guess what it’s called.

*Pulses* tell the tempo of a piece. They are written after a `@`, like `@80` being 80bpm.

*Snaps* refer to the *click* in the *groove* that feels the *pulse*, like what you might snap your fingers to.

## Cuts

In Counternote, *cuts* are groups of notes that *cut* up some duration into equal parts. There are two kinds of *cuts*, long and short. It’s the short *cuts* that should be used most of the time. A triplet that takes up two beats in `|2.|` is notated like `| ma.ma.ma |` with no spaces between the notes and the clicks being added together. That works decently well for small prime numbers: duplets (two notes where one fits), triplets, quintuplets, but for quadruplets and sextuplets, duplets and triplets are connected with `'`:

    —————————————————————————————————————————————
      # |4.|
      1
        | ma=                                 |
      2 # duplets
        | ma-ma             ma-ma             |
      3 # triplets
        | ma.ma.ma          ma.ma.ma          |
      4 # quadruplets
        | ma.ma'ma.ma       ma.ma'ma.ma       |
      5 # quintuplets
        | ma,ma,ma,ma,ma    ma,ma,ma,ma,ma    |
      6 # sextuplets
        | ma,ma,ma'ma,ma,ma ma,ma,ma'ma,ma,ma |
    —————————————————————————————————————————————

Notice how duplets can be used to simplify the bar:

    —————————————————————————————————————————
      # |4.|
      1 # like eight notes
        | ma, ma, ma, ma, ma, ma, ma, ma, |
      2 # like quarter note duplets
        | ma.ma   ma.ma   ma.ma   ma.ma   |
    —————————————————————————————————————————

That is easier for the eye to parse and, as mentioned before, can save on horizontal space:

    —————————————————————————————————
      # |4.|
      1 # space saving
        | ma.ma ma.ma ma.ma ma.ma |
    —————————————————————————————————

# Stacks and Knits

That’s nice and all for monophonic instruments, but what about things like the piano and guitar? There are a few ways of dealing with many voices. One is by using *stacks* — multiple lines of notes in the same *bar*.

A four-part harmony might be written:

    ——————————————————————————————————
      VOICES:
        s: soprano
        a: alto
        t: tenor
        b: bass

      # |4.|
      1
        s| mi.mi mi.mi mi.mi mi.mi |
        a| me.me me.me me.me me.me |
        t| ma.ma ma.ma ma.ma ma.ma |
        b| mo.mo mo.mo mo.mo mo.mo |
      
    ——————————————————————————————————

But what about double stops and chords and voicings where you might not need to dedicate vertical space?

This is where we introduce *knits*. Instead of each voice taking up an entire line, each voice in a *knit* is just a single letter called a *thread*.

__WIP__

# Score

There are obviously other details to go over, but it’s time to see some real music. This is the A-section of the track Bourrée from Bach’s Lute Suite in E Minor:

    ++*
    SCORE: Lute Suite in E Minor
    WORK: BWV 996
    SCRIBE: Bach
    +++
    TRACK: Bourrée
    VOICES:
      f: fingers
      t: thumb 
    +++
    @YOV |4.| @allegretto

    A
      0
        f|                   me.de |
        t|                   so.do |
      1
        f| se.   de.me ge.   me.de |
        t| mo.   lo.   na.   lo.   |
      2
        f| ne.   ze.ge me.   te.ce |
        t| so.   do.   mo.   do.   |
      3
        f| ne.   la.sa da.   sa.la |
        t| so.   lo.   na.   lo.   |
      4
        f| ne.la sa.da ma.   me.de |
        t| so.   na.   mo.do so.do |
      5
        f| se.   de.me ge.   me.de |
        t| mo.   lo.   na.   lo.   |
      6
        f| ne.   ze.ge me.   te.ce |
        t| so.   do.   mo.   do.   |
      7
        f| ne.   le.se de^^3.  ,se,|
        t| so.   ca.   ta.   ta.   |
      8
        f| hh-         .     %A %B |
        t| &soSeva-    .     %A %B |

    *++

***

Version 0.10.1