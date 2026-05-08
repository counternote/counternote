***

Counternote is a chromatic musical language meant to be typed and sung. It is a work in progress so there may be errors.

### Jump to [QUICK START][quick start]

[quick start]: #quick-start

# Drive

Counternote is an answer to a question that a lot of people have asked despite a solid solution already existing — namely, is there a [Markdown][md] for music, which I take to mean a human readable plaintext music notation? The answer is yes: it’s called [ABC notation][abc], and it’s great. If that’s all you are looking for, you do not need to read more. Go support it!

However, ABC notation is not a music notation directly. It’s a music notation *notation* with another layer of translation (music → staff → ABC). Counternote is a different kind of abstraction from western music notation, a linguistic one, not a visual one, so it can be written in plaintext directly (music → Counternote).

Counternote has been created as a complementary foil to the venerable staff notation, not a replacement. Even the most seasoned of musicians is likely to gain another perspective on music by learning it.

But this is not a one way street. Counternote is not yet set in stone and is still being tweaked, so any relevant feedback or constructive criticism will be considered and appreciated.

[md]:https://daringfireball.net/projects/markdown/ "John Gruber’s Markdown Spectacular"
[abc]:https://abcnotation.com/ "ABC notation"

***

# Design

There are five design principles that guide Counternote’s take on a musical notation: It must be readable, typeable, singable, codeable, and shareable. Unfortunately, satisfying all five of these constraints perfectly is impossible. Design is compromise just as life is pain — *anyone who tells you differently is selling something*.

For readability, the notes are simple and unambiguous — a note never has more than one name and is descriptive enough to make some intuitive and logical sense. The same goes for intervals and chords. They are organized in a way that can be sightread rather easily while still allowing for durations and articulations to appear in the same line like punctuation whereas dynamics, accompaniments, and other details appear in parallel above or below the line to avoid clutter. 

For typeability, everything is written in the printable characters of 7-bit ASCII which are easily typed by humans. The notes require as few keystrokes as possible, both to make typing faster and to take up less space on the line. In the process of compressing the written length of the notes, some characters have had their pronunciation reassigned and common digraphs have been eliminated, limiting them to just one consonant, vowel, or vowel-consonant pair per character.

For singability, each note is one syllable, as are each interval distinct from the notes. Music is not an abstract notion; it’s something that we can mimic concretely. So these elements are onomatopoeic and autological — that is, imitative and self-descriptive. The closer a symbol is to its actual pronunciation and meaning, the easier it is to remember. But notes are more than just hitting a correct pitch — they’re about any kind of vocalization, so the percussive sounds like those from beatboxing to click languages find representation here.

For codeability, everything is written in ASCII which is easily interpreted by computers and backed up with git. However, great care has been taken to make notational aspects not feel like code. Raw numbers for duration and pitch have been eliminated — the few numbers that exist in the notation are ordinal ones to label the bars. No function invocations are necessary to make a sound. And the control flow of the notation is at least as simple as staff notation.

For shareability, everything is just a string of plaintext, easily shared via text message. There is no need to translate it into a human consumable format and back to a computer-readable one, no heavy filetype to send and store, no binary blobs to contend with. What you see is what you get.

***

# Quick Start

Don’t let the idea that Counternote is a musical language trouble you. The way to learn Counternote is by practicing music, and practicing Counternote will help you learn music. If you are reading this, you are probably motivated to do one of those things.

Because every field tends toward jargon with big and important words the deeper you get into it, and occasionally those words conflict with common usage, all terms in Counternote are simple and precise, each limited to one syllable and an easy definition.

# Sounds

Sounds in Counternote come in two varieties — those where pitch is the defining characteristic, *tones*, and those where pitch is indeterminate or incidental, *raps*.

## Tones

First up to introduce are the twelve *tones*. These refer to absolute pitch when capitalized, used almost exclusively for setting the *key*, but are otherwise movable within a piece like scale degrees. You may think of them as fixed-do (solfège) when capitalized and movable-do (tonic solfa) when lowercase:

    ——————————————————————————————————————————————————
      UPPERCASE for setting the KEY
    ——————————————————————————————————————————————————
      C   C♯  D   D♯  E   F   F♯  G   G♯  A   A♯  B
      MA  KA  DA  SA  JA  LA  HA  NA  CA  ZA  TA  GA  
    ——————————————————————————————————————————————————
      LOWERCASE for playing notes
    ——————————————————————————————————————————————————
       1  ♭2   2  ♭3   3   4  ♭5   5  ♭6   6  ♭7   7
      ma  ka  da  sa  ja  la  ha  na  ca  za  ta  ga  
    ——————————————————————————————————————————————————

You’ll notice `ka` and `ca` seem like they might sound the same, but they don’t — `c` is a 'ch' sound in Counternote, always. 

Uppercase or lowercase, they consist of a *start*, the first letter:

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

And a *rhyme*, the rest of the letters:

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

`ZE` is *A440*, so by default `ze` sounds the same and `za` sounds an octave below it.

### Absolutely Relative

There is an inherent tension between an absolute frequency like *A440* and a relative frequency like the 5 in the key of D. The first is more about physics and less about music. The second, though, is what music is based on. In a very real sense, relative pitch is closer to the musical metal.

That is why the absolute pitch terms have been relegated to setting the tonal center, which comes with a huge benefit — transposing instruments can be read by anyone in the correct key. Simply set the *key* to that of the instrument, B♭ instruments should use `TA`, and alter the *mode* using *chords*. `TA` remains `TA`, its pitch always well-defined, while `ma` becomes B♭ and every lowercase *tone* is relative to it.

## Raps

The last kind of sound in Counternote is whatever doesn’t fit in the tones. These include noise, drums, non-standard ways of producing sound on an instrument, and even memes.

Raps are just a list of mostly user-defined sounds. There are two basic rules for creating them, only the first of which must be followed:

* they cannot overlap with tones or reserved raps
* they should sound like what they stand for

These are some proposed raps, only the first two of which cannot be defined on a piece by piece basis:

    ————————————————————————
      RESERVED
    ————————————————————————
      `hh` breath (rest)
      `sw` spoken word
      `rp` rap
    ————————————————————————
      USER-DEFINABLE
    ————————————————————————
      NOISE
      `hx` hush
      `nh` inhale
      `xh` exhale
      `hs` hiss
      `ss` blue noise
      `xs` white noise
      `xx` pink noise
    ————————————————————————
      DRUM
      `pf` pf snare
      `ks` k snare
      `kt` rim shot
      `kk` kick drum
      `bd` bass drum
      `gm` floor tom
      `gn` low tom
      `dm` mid tom
      `dn` high tom
      `tx` opening hi-hat
      `ts` open hi-hat
      `xt` closing hi-hat
      `st` closed hi-hat
      `cx` crash
      `xp` crash mute
      `cs` ride
      `sp` ride mute
    ————————————————————————
      PERCUSSION
      `pm` conga bass
      `pn` conga open tone
      `pp` conga mute
      `ph` conga open slap
      `pg` conga closed slap
      `pd` conga tap
      `kn` low bongo tone
      `kp` low bongo mute
      `kh` low bongo open slap
      `kg` low bongo closed slap
      `tn` high bongo tone
      `tp` high bongo mute
      `th` high bongo open slap
      `tg` high bongo closed slap
      `jm` djembe bass
      `jn` djembe tone
      `jp` djembe mute
      `jh` djembe open slap
      `jg` djembe closed slap
      `jd` djembe tap
      `xk` shook
      `cl` clap
      `td` clave
    ————————————————————————
      GUITAR
      `rk` rake
      `dt` deep tap
      `lt` light tap
      `dk` dark tick
      `tk` bright tick
      `hk` handmute
      `sk` strum mute
    ————————————————————————
      OTHER
      `rf` ref whistle
      `ah` scream
      `ws` Wilhelm scream
      `rn` siren
      `ck` crickets
      `cp` chirp, cheep
      `lc` the licc
      `lf` laugh track
    ————————————————————————

Practice beatboxing with these if you like.

# Notes

Notes in Counternote refer specifically to *sounds* held for some duration. That duration is denoted by a *click* or by the *tie* that carries it to the next *bar*.

## Clicks

*Clicks* are basic punctuation characters that must come immediately after the sound they sustain. They are roughly equivalent to the range of a whole note to a thirty-second note. These can be extended by trailing *clicks* in the same bar. They can also be shortened using *cuts*. More on them in a bit.

The six *clicks* ordered by powers of two with suggested bpms as follows:

    ——————————————————————————————————
      CLICK  VALUE  WORD   IPA   BPM
    ——————————————————————————————————
       `;`    1/32   pi    pi    280
       `:`    1/16   pe    pe    200
       `,`    1/8    pa    pa    140 
       `.`    1/4    po    po    100
       `-`    1/2    pu    pu    70
       `=`    1/1    pr    pɚ    50
    ——————————————————————————————————

Plus two others, immediate and indeterminate:

    ——————————————————————————————————
      CLICK     VALUE     WORD   IPA
    ——————————————————————————————————
       `!`    immediate    pl    pɛl
       `?`  indeterminate  pq    pɑ˞
    ——————————————————————————————————

The wider the character, the longer the duration, the narrower and taller the character, the shorter the duration.

## Grooves and Pulses and Taps

*Grooves* tell the duration of a bar. They are written on a line starting with `@` between `|` characters with the number of *clicks* like `|4.|` or `|....|`, both of which are identical and equivalent to the 4/4 time signature. However, one could specify 4/4 as `|4,|` or `|,,,,|` for upbeat numbers or `|4-|` or `|----|` for more languid tunes.

Here are four rather boring bars of Counternote:

    —————————————————————————————————————————
      @ |4.|
      1
        | ma=                             |
      2
        | ma-             ma-             |
      3
        | ma.     ma.     ma.     ma.     |
      4
        | ma, ma, ma, ma, ma, ma, ma, ma, |
    —————————————————————————————————————————

*Pulses* tell the tempo of a piece. `@ |4.| 100` is 4 taps at 100bpm.

*Taps* refer to the *click* in the *groove* that feels the *pulse*, like what you might tap your foot to.

## Tie

The *tie* `++` can be used with or even instead of *clicks* to extend the *note* to the next *bar*. That extension is notated with the unison `aa` in the next *bar*:

    —————————————————————————————————————————
      @ |4.|
      1
        | ma-             ma++            |
      2
        | aa++                            |
      3
        | aa, ma, ma, ma, ma, ma, ma, ma, |
    —————————————————————————————————————————

## Cuts

In Counternote, *cuts* are groups of notes that slice some duration into equal parts. There are two kinds of *cuts*, long and short. It’s the *short cuts* that should be used most of the time.

You’ll notice in the boring bars above, each of those notes takes up at least four spaces. The *short cut* makes each note only take up three spaces and cuts down on visual noise, so it’s aptly named.

A triplet that takes up two beats in `|2.|` is notated like `| ma.ma.ma |` with no spaces between the notes and the clicks being added together. That works decently well for small prime numbers: duplets (two notes where one fits), triplets, quintuplets, but for quadruplets and sextuplets, duplets and triplets are connected with `'` which acts as a separator:

    —————————————————————————————————————————————
      @ |4.|
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
      @ |4.|
      1 # like eight notes
        | ma, ma, ma, ma, ma, ma, ma, ma, |
      2 # like quarter note duplets
        | ma.ma   ma.ma   ma.ma   ma.ma   |
    —————————————————————————————————————————

That is easier for the eye to parse and, as mentioned before, can save on horizontal space:

    —————————————————————————————————
      @ |4.|
      1 # space saving
        | ma.ma ma.ma ma.ma ma.ma |
    —————————————————————————————————

# Stacks, Spans, Strands, and Knits

That’s nice and all for monophonic instruments, but what about things like the piano and guitar? There are a few ways of dealing with many voices. One is by using *stacks* — multiple lines of notes in the same *bar*.

A four-part harmony might be written:

    ——————————————————————————————————
      VOICES:
        s: soprano
        a: alto
        t: tenor
        b: bass

      |4.|
      1
        s| mi.mi mi.mi mi.mi mi.mi |
        a| me.me me.me me.me me.me |
        t| ma.ma ma.ma ma.ma ma.ma |
        b| mo.mo mo.mo mo.mo mo.mo |
      
    ——————————————————————————————————

But what about double stops and chords and voicings where you might not need or want to dedicate vertical space?

For that, we’ll learn about *knits* and *strands*, but to do so we have to introduce intervals called *spans*:

    ——————————————————————————————————
      SPAN   INTERVAL  IPA   ENGLISH
    ——————————————————————————————————
        X       8       aʃ   'ahsh'
        Z       7       ɚz    'erz'
        N      ♭7       un    'oon'
        M       6       om    'ohm'
        L      ♭6       ɛl    'ehl'
        V       5       iv    'eev'
        Q     ♯4/♭5     ʔɑ˞   'ʔar'
        I       4       ʔi    'ʔee'
        E       3       ʔɛ    'ʔeh'
        O      ♭3       ʔo    'ʔoh'
        U       2       ʔu    'ʔoo'
        R      ♭2       ʔɚ    'ʔer'
        A       1       ʔa    'ʔah'
    ——————————————————————————————————

Notice that the pronunciation of each isn’t the name of the letter but the sound of it, and the consonants include the vowel quality of the span. These single uppercase letters represent the interval in abstract terms, but sometimes you want to talk about a fifth above or a fifth below. For that, we prefix it with `Y-` for up to an octave above, `W-` for down to an octave below, and unison gets doubled `AA`. These create the *spans* used for *strands* — lowercase versions attached to tones to create double stops:

    ————————————————————————————————————
      SPAN   INTERVAL   IPA    ENGLISH
    ————————————————————————————————————
      -ya       8↑      ja     'yah'
      -yz       7↑      jɚz    'yerz'
      -yn      ♭7↑      jun    'yoon'
      -ym       6↑      jom    'yohm'
      -yl      ♭6↑      jɛl    'yelh'
      -yv       5↑      jiv    'yeev'
      -yq     ♯4/♭5↑    jɑ˞    'yar'
      -yi       4↑      ji     'yee'
      -ye       3↑      jɛ     'yeh'
      -yo      ♭3↑      jo     'yoh'
      -yu       2↑      ju     'yoo'
      -yr      ♭2↑      jɚ     'yer'
      -aa       1       ʔa     'ʔah'

Just like *strand spans* became lowercase, the single-letter *spans* become lowercase to make *threads*, individual voices within a *knit*.

    ———————————————————————————————————————————————————————————
      LOWERCASE for THREADS
    ———————————————————————————————————————————————————————————
       1  ♭2   2  ♭3   3   4  ♭5   5  ♭6   6  ♭7   7   8   X
      -a- -r- -u- -o- -e- -i- -q- -v- -l- -m- -n- -z- -x- -h-
    ———————————————————————————————————————————————————————————

An `h` is added for octave spans without a voice. Here are the rules for pronouncing the *threads*:

+ For any three consonants in a row, a schwa `ə` is inserted between the second and third.
+ For any two vowels in a row, if the first is `u`, `o`, or `r`, a `w` is inserted after it.
+ For any two vowels in a row, if the first is `a`, `e`, or `i`, a `y` is inserted after it.
+ If more than an octave is skipped between two *threads*, an `h` is inserted for each missing octave.
+ The `r` is always a rhoticized mid vowel.
+ The `q` is always a glottal stop.

*Knits* come in two varieties: *chords* which are analogous to the chords we know and love, and *braids* which are specific voicings of *chords*.

Both kinds of *knits* consist of a *root* as the capitalized *tone start*, plus the *threads*. A bass note is prefixed for all *braids*, but *chords* only prefix the *thread* of the bass note for inversions.

    ——————————————————————————————————————————————————————————————
            NAME   CHORD                 IPA   TRANSLITERATION
    ——————————————————————————————————————————————————————————————
               A   Zev                  ˈzev   ZEHV
              B5   Gav                  ˈgav   GAHV
            Cm/G   vMov               viˈmov   vee-MOHV
             F♯7   Hevn              ˈhe.vən   HEH-vuhn
             D13   Devnuim       ˈdev.nuˌwim   DEHV-noo-WEEM
      E♭13(♭5♯9)   Seqnoim       ˈseʔ.noˌwim   SEHʔ-noh-WEEM
    ——————————————————————————————————————————————————————————————
            NAME   BRAID                 IPA   TRANSILITERATION
    ——————————————————————————————————————————————————————————————
               A   zaZvaev      zaˈzə.vaˌjev   zah-ZUH-vah-YEHV
              B5   gaGv               gaˈgəv   gah-GUHV
            Cm/G   naMaov          naˈma.wov   nah-MAH-wohv
             F♯7   haHevn          haˈhe.vən   hah-HEH-vuhn
             D13   daDevnuim   daˈdev.nuˌwim   dah-DEHV-noo-WEEM
      E♭13(♭5♯9)   saSeqnoim   saˈseʔ.noˌwim   sah-SEHʔ-noh-WEEM
    ——————————————————————————————————————————————————————————————


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
    @ JA XOV |4.| allegretto

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
        f| ne.   le.se de^^s.  ,se,|
        t| so.   ca.   ta.   ta.   |
      8
        f| hh-         .     %A %B |
        t| &soSeva-    .     %A %B |

    *++

***

Version 0.10.1