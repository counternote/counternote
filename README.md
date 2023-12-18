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

For readability, the notes are simple and unambiguous — a note never has more than one name and is descriptive enough to make some intuitive and logical sense. The same goes for intervals and chords. They are organized in a way that can be sightread rather easily while still allowing for durations and articulations to appear in the same line like punctuation while dynamics, accompaniments, and other details appear in parallel above or below the line to avoid clutter. 

For typeability, everything is written in the printable characters of 7-bit ASCII which are easily typed by humans. The notes require as few keystrokes as possible, both to make typing faster and to take up less space on the line. In the process of compressing the written length of the notes, some characters have had their pronunciation reassigned and common digraphs have been eliminated, limiting them to just one consonant, vowel, or vowel-consonant pair per character.

For singability, each note is one syllable, as are each interval distinct from the notes. The simple idea here is that music is not an abstract notion, it’s something that we can mimic concretely. So these elements are onomatopoeic and autological — that is, imitative and self-descriptive. The closer a symbol is to its actual pronounciation and meaning, the easier it is to remember. But notes are more than just hitting a correct pitch — they’re about any kind of vocalization, so the percussive sounds like those from beatboxing to click languages find representation here.

For codeability, everything is written in ASCII which is easily interpretted by computers and backed up with git. However, great care has been taken to make notational aspects not feel like code. Raw numbers for duration and pitch have been eliminated — the few numbers that exist in the notation are ordinal numerals to mark the bars. No function invocations are necessary to make a sound. And the control flow of the notation is at least as simple as staff notation.

For shareability, everything is just a string of plaintext, easily shared via text message and read in monospace. There is no need to translate it into a human consummable format and back to a computer-readable one, no heavy filetype to send and store, no binary blobs to contend with. What you see it what you get.

***

# Quick Start

Don’t let the idea that Counternote is a musical language trouble you. The way to learn Counternote is by practicing music, and practicing Counternote will help you learn music. If you are reading this, you are probably motivated to do one of those things.

## Sounds

Sounds in Counternote come in three varieties — those where pitch is the defining characteristic, *tones* and *spans*, and those where pitch is indeterminate or incidental, *raps*.

### Tones

First up to practice are the twelve tones. These refer to absolute pitch, each named uniquely. They’re kind of like the letter names, but more precise. Starting from a traditional E and ending on D♯/E♭, we have:

    ——————————————————————————————————————————————————
      E   F   F♯  G   G♯  A   A♯  B   C   C♯  D   D♯
      wa  ga  ka  ya  xa  ja  ca  za  da  fa  ba  pa
    ——————————————————————————————————————————————————

You’ll notice `ka` and `ca` and maybe `za` and `xa` seem like they might sound the same, but they don’t — `c` is a 'ch' sound and `x` is a 'sh' sound in Counternote, always.

With those two tweaks in mind, speak each tone aloud paying attention to where your tongue touches (or comes close to touching) the roof of your mouth all the way until `fa` where you need to think about your lips. Now say `wa` again, this time also thinking about your lips.

The tones in Counternote are ordered by points of articulation — which is just a fancy way of saying where the sound of a consonant is coming from — and come back around with `wa` which has two points of articulation: the lips and the back of the tongue. 

Now you are ready pick up a guitar or sit at a piano (or open a music app on your phone, anything that does not use your mouth) and in a range that is somewhat comfortable for your voice, play each note and sing the tone by its name. If you don’t yet know where the traditional notes are — look them up, it’s great practice.

Try it singing the tones chromatically, then try just the naturals (white keys on the piano) or just the accidentals (black keys on the piano), maybe some major scales starting at different roots, some triads, whatever you like. Give it ten minutes at least, but no more than twenty.

### Starts and Rhymes

Maybe you’ll have noticed during that first exercise that while all of those tones start with different consonants, they all rhyme with `-a`. So that’s what it’s called, a *rhyme*. Might as well call the start of the tones the *start* while we are being Captain Obvious.

The tone starts tell you the “pitch class” which is music jargon for all the notes that we label a specific letter, like C — not just middle C but any and all C. In Counternote, this is the *rank* of a sound.

The tone rhyme, on the other hand, tells which specific octave a note is in. For `-a`, it could be any octave, but more specifically it’s the center octave. `da` is likely to be middle C. `-e` will be an octave up from there; `-o`, an octave down. In Counternote, this is the *file* of a sound.

Tone starts and rhymes go rank and file.

There are eleven rhymes for eleven files but we only really care about seven:

    —————————————————————————————————
      RHYME  FILE  IPA  ENGLISH-ISH
    —————————————————————————————————
       -l     +3    ɛl     'el'
       -i     +2    i      'ee'
       -e     +1    e      'eh'
       -a      0    ɑ      'ah'
       -o     -1    o      'oh'
       -u     -2    u      'oo'
       -r     -3    ɚ      'er'
    —————————————————————————————————

In the key of `ja`, the note directly below `wa` is `po` and directly above `pa` is `we`. This is called the *break*. If we place the tones around a clockface with the key center at 12, the break is bewteen 6 and 7:

    ——————————————————————————————————————————
                        12
              11        ja         1
                 xa  ===||===  ca
         10             ||              2
            ya  ========||========  za
                        ||
                        ||
      9   ka  ==========||==========  da   3
                        ||
                        ||
            ga  ========||========  fa
         8              ||              4
                 wa  ===||===  ba
              7         pa         5
             BREAK ↑    6
    ——————————————————————————————————————————

Now this may seem somewhat arbitrary — why not just always have the break between `wa` and `pa`? First of all, the break is informative, giving some sense of the range of a piece. But most importantly, it makes the tones and spans symmetrical.

Before we get to those spans, try taking out a piece of paper and drawing clockfaces, but instead of writing the numbers, place the tones in chromatic order. (It’s okay if you are really bad at drawing circles — you can always trace a glass — but it is important to place the tones right, so here’s a tip: put a mark at the 12, 3, 6, and 9 o’clock positions — north, east, south, west — and then put every third tone at those marks as you write them around the circle.)

Hopefully that wasn’t so tedious that you never want to look at a clockface again, because this next section might just go all-in on clocks.

### Spans

While tones let us talk about pitch in an absolute way, *spans* let us talk about pitch in a relative way. Musicians train their relative pitch sensibilities more than anything else — the basis of which is interval training. A span is just the Counternote term for interval.

Instead of the academic names of minor third and major sixth, spans give a sense of interval by vowel quality. `ho` 'hoe' (but without an ending 'w' sound) and `hn` 'hone' are a minor third (♭3, m3) and a major sixth (6, M6) with no apparent relationship bewteen them. But notice that they share the same vowel 'oh' in Counternote. That’s because a major sixth is the mirror version of a minor third and vice versa. A major sixth up is the same as a minor third down. A minor third up is the same as a major sixth down.

(The hack for traditional interval names is that minor become major, diminished becomes augmented, perfect stays perfect, and the interval numbers always add up to 9, for instance M2 —> m7, M3 —> m6, A4 —> d5, P5 —> P4, and so on. In Counternote, we just look at the quality of the vowel.)

### Hue Clock

A great way of seeing these relationships is on the *hue clock* with intervals labeled in chromatic order, presented here with the “English-ish” pronunciation along the sides:

    ————————————————————————————————————————————————————————
      HUE CLOCK
    ————————————————————————————————————————————————————————
                                1                    
      'hah'         -♭2        ha        ♭2
      'hearse'          hs  ===||===  hr             'her'
                -2             ||              2
      'whom'       hm  ========||========  hu        'who'
                               ||
                               ||
      'hone' -♭3 hn  ==========||==========  ho  ♭3  'hoe'
                               ||
                               ||
      'hell'       hl  ========||========  he        'heh'
                -3             ||              3
      'heave'           hv  ===||===  hi             'hee'
                     -4        ht        4         'heart'
                    BREAK ↑  ♯4/♭5
    ————————————————————————————————————————————————————————

We see the *break* is in the same place that the one for tones was:

    ——————————————————————————————————————————
                         12
              11        ja/ha        1
                 xa/hs ==||== ca/hr
         10              ||               2
            ya/hm =======||======= za/hu
                         ||
                         ||
      9   ka/hn =========||========= da/ho   3
                         ||
                         ||
            ga/hl =======||======= fa/he
         8               ||               4
                 wa/hv ==||== ba/hi
              7         pa/ht        5
              BREAK ↑    6
    ——————————————————————————————————————————

Notice that the span start is always `h-` and the tone rhyme is always `-a`. That’s because spans starts and rhymes go *file then rank*, the opposite of the tones.

We can see all the spans starts here:

    ————————————————————
      START  FILE  IPA
    ————————————————————
        m-    +3    m
        v-    +2    v
        l-    +1    l
        h-     0    h
        t-    -1    t
        s-    -2    s
        n-    -3    n
    ————————————————————

And the rhymes contain more than meets the eye — you can think of them as abbreviations, you know, for brevity’s sake:

    —————————————————————————————————————
      RHYME  INTERVAL  IPA  ENGLISH-ISH
    —————————————————————————————————————
        -s      7     ɚs,r̩s    'ers'
        -m     ♭7       un     'oom'
        -n      6       om     'ohn'
        -l     ♭6     ɛl,el    'ehl'
        -v      5       iv     'eev'
        -t    ♯4/♭5  ɑ˞t,art   'art'
        -i      4       i       'ee'
        -e      3      ɛ,e      'eh'
        -o     ♭3       o       'oh'
        -u      2       u       'oo'
        -r     ♭2      ɚ,r̩      'er'
        -a      1       ɑ       'ah'
    —————————————————————————————————————

Now it’s time to practice. Using the same instrument you used before, play the key center and then sing the interval up to an octave above as shown on this clock:

    ————————————————————————————————————————————————————————
      HUE CLOCK: ASCENDING CLOCKWISE
    ————————————————————————————————————————————————————————
                                8   ↓ BREAK                  
      'hah'           7        la        ♭2
      'lerse?'          ls  ===||===  hr             'her'
                ♭7             ||              2
      'loom'       lm  ========||========  hu        'who'
                               ||
                               ||
      'lone'  6  ln  ==========||==========  ho  ♭3  'hoe'
                               ||
                               ||
      'lell?'      ll  ========||========  he        'heh'
                ♭6             ||              3
      'leave'           lv  ===||===  hi             'hee'
                      5        ht        4         'heart'
                             ♯4/♭5
    ————————————————————————————————————————————————————————

Do this for no more than ten minutes, maybe changing the key center to get a feel for the relative nature of spans. Then repeat for the interval up to an octave below:

    ————————————————————————————————————————————————————————
      HUE CLOCK: DESCENDING COUNTERCLOCKWISE
    ————————————————————————————————————————————————————————
                     BREAK ↓   -8                    
      'hah'         -♭2        ta        -7
      'hearse'          hs  ===||===  tr            'ter?'
                -2             ||             -♭7
      'whom'       hm  ========||========  tu        'too'
                               ||
                               ||
      'hone' -♭3 hn  ==========||==========  to  -6  'toe'
                               ||
                               ||
      'hell'       hl  ========||========  te       'teh?'
                -3             ||             -♭6
      'heave'           hv  ===||===  ti             'tee'
                     -4        tt        -5         'tart'
                            -♯4/♭5
    ————————————————————————————————————————————————————————

### Absolutely Relative

Now is a good time to address the elephant in the room: Why there are two ways of talking about musical pitch?

There is an inherent tension between absolute frequency like A440 and relative frequency like the 3:2 ratio of a perfect fifth. The first is more about physics and less about music. The second, though, is what music is based on, particularly the 3:2 ratio of most western music. In a very real sense, relative pitch is closer to the musical metal.

This distinction is so important that there are no less than four ways of conveying relative pitch in standard western notation, none of which are standard:

* as intervals like __m3__ and __M6__
* as scale degrees like __♭3__ and __6__
* as movable-do Solfège like __me__ or __ma__ and __la__
* as integer notation __3__ and __9__

Each of those has problems, chief among them is that the only one that doesn’t use numbers is readily confused with a fixed-do Solfège used in half the world.

By representing pitch in these two different ways up front, Counternote can unambiguously handle stops and chords and *transposing instruments* without muddying the absolute pitch meaning of the tones.

If you play one of these transposing instruments, you’ll want to spend some extra time learning these spans. Tones should never be transposed with transposing instruments the way they are with standard notation — B♭ written as C for instance — it’s as close to *wrong* as Counternote allows. Instead, B♭ instruments should use spans centered on B♭, A instruments should use spans centered on A, and so on. The guitar can also act as a transposing instrument when tuned to a different standard such as E♭ or D, or when capoed up so it’s a good idea to practice them as well. But no matter your instrument, learning the tones and the spans will strengthen your ear in complementary ways.

### Lux Clock

There is one additional way of arranging tones and spans around a clock — instead of chromatic order like the hue clock, we can try the harmonic order of the *lux clock*. There is a simple way of turning the hue clock into the lux clock: Just replace every odd numeral on the clock with its opposite (1 <—> 7, 3 <—> 9, 5 <—> 11). This is in the key `ja` again:

    ——————————————————————————————————————————
      LUX CLOCK: TONES/SPANS
    ——————————————————————————————————————————
                         12
              11        ja/ha        1
                 ba/hi ==||== wa/hv
         10              ||               2
            ya/hm =======||======= za/hu
                         ||
                         ||
      9   da/ho =========||========= ka/hn   3
                         ||
                         ||
            ga/hl =======||======= fa/he
         8               ||               4
                 ca/hr ==||== xa/hs
              7         pa/ht        5
                          6
    ——————————————————————————————————————————

If you were to say the tones aloud without pausing between them with your hand on your throat, you might notice that your larynx vibrates continuously from the tones from 8–12–2 and stops vibrating at the start of the tones from 3–7. This mirrors the “natural” notes (the white keys on a typical piano) with *voiced* consonants and the “accidental” notes (the black keys on a typical piano) with *voiceless* consonants. Note that while the accidentals start out voiceless, they still end with a voice and are indispensable for harmony in our modern culture.

This clumping of the white keys is an artifact of the origin of western harmony — the seven stacked 3:2 ratios popularized by Pythagoras that are known as the major scale. But just about every culture has something very close to the five stacked 3:2 ratios of the black keys known as the pentatonic scale. In order to put the naturals and accidentals on equal footing around the clock to avoid so-called wolf intervals, we have fudged the 3:2 interval flat by 1/50th of a semitone, barely perceptible even to the trained ear.

The more seasoned musicians will have already recognized the arrangement of tones and spans on the lux clock — it’s the circle of fifths, which places notes in perfect fifths clockwise and perfect fourths counterclockwise.

Let’s take a look at the clock with just the span rhymes and scale degrees written around it. You can do this with your regular circle of fifths as well:

    ——————————————————————————————————————————
      LUX CLOCK: SPAN RHYMES & SCALE DEGREES
    ——————————————————————————————————————————
                         1
                4       -a        5
                  -i  ==||==  -v
          ♭7            ||             2
             -m  =======||=======  -u
                        ||
                        ||
       ♭3  -o  =========||=========  -n   6
                        ||
                        ||
             -l  =======||=======  -e
          ♭6            ||             3
                  -r  ==||==  -s
               ♭2       -t        7
                      ♭5/♯4
    ——————————————————————————————————————————

Notice how the flattened degrees line up on the left side along with the smaller of the (non-root) perfect intervals? This is the minor (smaller) side. It evokes a sense of settling down and turning inward, a darkening. The right side is the major (larger) side that evokes a sense of opening up and turning outward, a brightening. This brightening/darkening is *lux* in Counternote:

    —————————————————————————————————————————————————
      LUX CLOCK: SPAN RHYMES & SCALE DEGREES
    —————————————————————————————————————————————————
       |-----DARK-----| LUX |----BRIGHT----|  
                         1                 |-FEEL-|
                4       -a        5         BLENDS
                  -i  ==||==  -v               |
          ♭7            ||             2       |
             -m  =======||=======  -u        —————
                        ||
                        ||
       ♭3  -o  =========||=========  -n   6  MOODS
                        ||                     |
                        ||                     |
             -l  =======||=======  -e        —————
          ♭6            ||             3
                  -r  ==||==  -s              RUBS
               ♭2       -t        7            |
                      ♭5/♯4                  —————
    —————————————————————————————————————————————————

But there is an additional bit beyond the lux — the *feel* of a span. Counternote breaks these up into 3 sections:

* the *blends*: low open and high close vowels, some with labial consonants, which are smooth spans that do not impart much tonality
* the *moods* mid close vowels, some with alveolar consonants, which are mostly smooth but impart a lot of tonality
* the *rubs* rhoticized vowels, some with alveolar consonants, which can be rather rough, imparting mostly dissonance and some tonality.

Associating these articulations with the emotional tenor of a span will help solidify the feeling of these intervals. Practice the *blends* for five minutes or so, then the *moods*, and then the *rubs*. Separating them into these groups helps narrow the scope of what needs to be practiced in a systematic way. If you use an ear training app or are trying to transcribe a song, you can use these feels to winnow down the possibilities.

### Raps

The last kind of sound in Counternote is whatever doesn’t fit in the tones/spans. These include noise, drums, non-standard ways of producing sound on an instrument, and even memes.

Compared to tones and spans, raps are easier to demonstrate because they’re just a list of mostly user-defined sounds. They are also harder to learn because thy’re just a list of mostly user-defined sounds. There are two basic rules for creating raps, only the first of which must be followed:

* they cannot overlap with tones, spans, or reserved raps
* they should sound like what they stand for

These are some proposed raps, only the first three of which cannot be defined on a piece by piece basis:

    ————————————————————————
      RESERVED
    ————————————————————————
      `aa` tie
      `hh` breath (rest)
      `sp` speech, spoken
    ————————————————————————
      USER-DEFINABLE
    ————————————————————————
      NOISE
      `hx` hush, silence
      `nh` inhale
      `eh` exhale
      `xs` blue noise
      `xx` white noise
      `xh` pink noise
    ————————————————————————
      DRUM
      `pf` pf snare
      `ks` k snare
      `bm` bass drum
      `kk` kick drum
      `dn` high tom
      `dm` mid tom
      `gn` low tom
      `gm` floor tom
      `px` opening hi-hat
      `tx` open hi-hat
      `xp` closing hi-hat
      `xt` closed hi-hat
      `kt` rim shot
      `cx` crash
      `cs` ride
      `kl` clap
      `dt` bright clave
      `dd` dark clave
    ————————————————————————
      GUITAR
      `rk` rake
      `dp` deep tap
      `tp` light tap
      `dk` dark tick
      `tk` bright tick
      `hd` handmute
      `sd` strum mute
    ————————————————————————
      OTHER
      `rf` ref whistle
      `ws` Wilhelm scream
      `rn` siren
      `xk` shook
      `ck` crickets
      `cp` chirp, cheep
      `jz` the licc
      `lk` laugh track
    ————————————————————————

Practice beatboxing with these if you like.

## Notes

Notes in Counternote refer specifically to sounds held for some duration. That duration is denoted by a *hold*.

### Holds

Holds are basic punctuation characters that are roughly equal to a whole note to a thirty-second note that must come immediately after the sound they hold out. These can be extended by trailing holds in the same bar or by adding the rap `aa` with a new hold at the beginning of the next bar.

The six holds ordered by powers of two are as follows:

    ———————————————————————————
      HOLD  VALUE  WORD   IPA
    ———————————————————————————
      `;`    1/32   ql    kʷɛl
      `:`    1/16   qi    kʷi
      `,`    1/8    qe    kʷe
      `.`    1/4    qa    kʷɑ
      `-`    1/2    qo    kʷo
      `=`    1/1    qu    kʷu
    ———————————————————————————

The wider the character, the longer the duration, the narrower and taller the character, the shorter the duration.

### Grooves

Grooves tell the duration of a bar. They are written between `|` characters with the number of holds like `|4.|` or `|....|`, both of which are identical and equivalent to the 4/4 time signature. However, one could specify 4/4 as `|4,|` or `|,,,,|` for upbeat numbers or `|4-|` or `|----|` for more languid tunes.

Here are four rather boring bars of Counternote:

    —————————————————————————————————————————
      # |4.|
      1
        | da=                             |
      2
        | da-             da-             |
      3
        | da.     da.     da.     da.     |
      4
        | da, da, da, da, da, da, da, da, |
    —————————————————————————————————————————

You’ll notice that each of those notes takes up at least four spaces. There is a short cut that makes each note only take up three spaces and cuts down on visual noise. You’ll never guess what it’s called.

### Cuts

In Counternote, cuts are groups of notes that *cut* up some duration into equal parts. There are two kinds of cuts, long and short. It’s the short cuts that should be used most of the time. A triplet that takes up two beats in `|2.|` is notated like `| da.da.da |` with no spaces between the notes and the holds being added together. That works decently well for small prime numbers: duplets (two notes where one fits), triplets, quintuplets, but for quadruplets and sextuplets, duplets and triplets are connected with `'`:

    —————————————————————————————————————————————
      # |4.|
      1
        | da=                                 |
      2 # duplets
        | da-da             da-da             |
      3 # triplets
        | da.da.da          da.da.da          |
      4 # quadruplets
        | da.da'da.da       da.da'da.da       |
      5 # quintuplets
        | da,da,da,da,da    da,da,da,da,da    |
      6 # sextuplets
        | da,da,da'da,da,da da,da,da'da,da,da |
    —————————————————————————————————————————————

Notice how duplets can be used to simplify the bar:

    —————————————————————————————————————————
      # |4.|
      1 # like eight notes
        | da, da, da, da, da, da, da, da, |
      2 # like quarter note duplets
        | da.da   da.da   da.da   da.da   |
    —————————————————————————————————————————

That is easier for the eye to parse and, as mentioned before, can save on horizontal space:

    ——————————————————————————————————
      # |4.|
      1 # space saving
        | da.da da.da da.da da.da  |
    ——————————————————————————————————

## Score

There are obviously other details to go over, but it’s time to see some real music. This is the A-section of the track Bourrée from Bach’s Lute Suite in E Minor written using tones:

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
    # Wov |4.| @allegretto

    A
      0
        f| -           .     we.ke  |
        t| -           .     yo.ko  |
      1
        f| ye.   ke.we pe.   we.ke  |
        t| wo.   jo.   za.   jo.    |
      2
        f| ze.   fe.pe we.   be.de  |
        t| yo.   ko.   wo.   ko.    |
      3
        f| ze.   ja.ya ka.   ya.ja  |
        t| yo.   jo.   za.   jo.    |
      4
        f| ze.ja ya.ka wa.   we.ke  |
        t| yo.   za.   wo.ko yo.ko  |
      5
        f| ye.   ke.we pe.   we.ke  |
        t| wo.   jo.   za.   jo.    |
      6
        f| ze.   fe.pe we.   be.de  |
        t| yo.   ko.   wo.   ko.    |
      7
        f| ze.   je.ye ke^^y.  ,ye, |
        t| yo.   da.   ba.   ba.    |
      8
        f| hYeva-      .      _     |
        t| yo-         .      @A @B |

    *++

And here it is written using spans:

    ++*
    SCORE: Lute Suite in E Minor
    WORK: BWV 996
    SCRIBE: Bach
    KEY: wa
    +++
    TRACK: Bourrée
    VOICES:
      f: fingers
      t: thumb 
    +++
    # Aov |4.| @allegretto

    A
      0
        f| -           .     la.lu  |
        t| -           .     to.tu  |
      1
        f| lo.   lu.la ls.   la.lu  |
        t| ta.   ti.   hv.   ti.    |
      2
        f| lv.   ln.ls la.   lm.ll  |
        t| to.   tu.   ta.   tu.    |
      3
        f| lv.   hi.ho hu.   ho.hi  |
        t| to.   ti.   hv.   ti.    |
      4
        f| lv.hi ho.hu ha.   la.lu  |
        t| to.   hv.   ta.tu to.tu  |
      5
        f| lo.   lu.la ls.   la.lu  |
        t| ta.   ti.   hv.   ti.    |
      6
        f| lv.   ln.ls la.   lm.ll  |
        t| to.   tu.   ta.   tu.    |
      7
        f| lv.   li.lo lu^^o.  ,lo, |
        t| to.   hl.   hm.   hm.    |
      8
        f| hOeva-      .     _      |
        t| to-         .     @A @B  |

    *++

***
