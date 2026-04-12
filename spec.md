***

# Counternote Specification version 0.10.0

This is a terse description of Counternote with definitions and examples.

***

# Gloss

This [gloss][gloss] serves as a glossary and table of contents for all things Counternote.

### [BASES][bases]

Foundational elements

* [__term__][term]: a precise concept in music and Counternote, linked here in the [gloss][gloss]
* [__glyph__][glyph]: any typed character
* [__phone__][phone]: the pronunciation of a speakable [glyph][glyph] or cluster of [glyphs][glyph]
  * [__start__][start]: the first [phone][phone] or *linguistic onset* of a [word][word]
  * [__rhyme__][rhyme]: the rhyming part or *linguistic coda* of a [word][word]
* [__word__][word]: a connected sequence of [phones][phone]
* [__sign__][sign]: a connected sequence of [glyphs][glyph] that do not make a [word][word]

### [FORMS][forms]

Structural elements

* [__score__][score]: an entire composition
* [__stage__][stage]: a place for compositional and instrumental details
  * [__scribe__][scribe]: a composer of the [score][score] or [track][track]
  * [__work__][work]: the collection a [score][score] or [track][track] belongs to
  * [__act__][act]: the performer of the [score][score] or [track][track]
* [__track__][track]: an individual piece within a [score][score]
  * [__key__][key]: the tonic of a [track][track]
  * [__mode__][mode]: the mode of a [track][track]
* [__round__][round]: a block of music
* [__bar__][bar]: details on how and what to play
  * [__voice__][voice]: a monophonic instrument and the sequence of [sounds][sounds] to be played
  * [__stack__][stack]: multiple [voices][voice] in the same [bar][bar]
  * [__rep__][rep]: a directive to repeat a [bar][bar] or [round][round]
  * [__jump__][jump]: a directive on what to play next
  * [__lap__][lap]: a variation on a [bar][bar]
* [__code__][code]: a place suitable for code

### [SOUNDS][sounds]

Any acoustic vibration

* [__pitch__][pitch]: the number of vibrations per second, the frequency
* [__rank__][rank]: the set of [pitches][pitch] separated by powers of two, the pitch-class
* [__file__][file]: the octave range that contains a [pitch][pitch]
* [__band__][band]: any range of [pitches][pitch]
* [__notch__][notch]: the range of a single *semitone* or *half-step*

### [BEATS][beats]

Rhythmic elements

* [__hold__][hold]: the duration of a [note][notes]
* [__groove__][groove]: the arrangement of [beats][beats] in a [bar][bar]
  * [__shift__][shift]: a section of polymeter
  * [__rift__][rift]: a section of polyrhythm
* [__pulse__][pulse]: the tempo
* [__click__][click]: the beat that feels the pulse
* [__cut__][cut]: a tuplet
  * [__short cut__][short cut]: a quick [cut][cut] notation
  * [__long cut__][long cut]: a robust [cut][cut] notation

### [NOTES][notes]

Acoustic vibrations held in time

* [__tone__][tone]: a [word][word] indicating the absolute [rank][rank] and [file][file] of a [sound][sounds]
  * [__tone start__][tone start]: the [start][start] that denotes absolute [rank][rank]
  * [__tone rhyme__][tone rhyme]: the [rhyme][rhyme] that denotes [file][file]
* [__root__][root]: the tonic for [spans][span] and [knits][knits]
* [__rap__][rap]: a [word][word] indicating a [sound][sounds] where [pitch][pitch] is indeterminate or incidental
* [__tie__][tie]: a [sound][sounds] from a previous [bar][bar] is still being held
* [__breath__][breath]: a breath of fresh quiet

### [KNITS][knits]

Manifold acoustic vibrations

* [__span__][span]: a [word][word] indicating the interval
  * [__span start__][span start]: the [start][start] that denotes [file][file]
  * [__span rhyme__][span rhyme]: the [rhyme][rhyme] that denotes relative [rank][rank]
* [__knit start__][knit start]: the [start][start] that denotes a [knit][knits]
* [__thread__][thread]: a single [voice][voice] within a [knit][knits]
* [__strand__][strand]: a [knit][knits] of two voices, a double stop
* [__chord__][chord]: a [knit][knits] of three voices or more
* [__braid__][braid]: a [chord][chord] of a particular voicing

### [CUES][cues]

Composer directives

* [__comp__][comp]: an accompaniment
  * [__vamp__][vamp]: a [comp][comp] with rhythm and/or voicings
* [__tweak__][tweak]: an instruction on effects
* [__art__][art]: an inline cue
  * [__smooth__][smooth]: a legato line
  * [__ring__][ring]: a sustained line
  * [__glide__][glide]: a smooth change in [pitch][pitch] of a [sound][sounds]
  * [__slide__][slide]: a stepped change in [pitch][pitch] of a [sound][sounds]
  * [__flux__][flux]: a repeated fluctuation in [pitch][pitch] of a [sound][sounds]
  * [__flam__][flam]: a quick [sound][sounds] before another
  * [__lick__][lick]: a quick run of [sounds][sounds]
  * [__trill__][trill]: a quick alternating between [sounds][sounds]
  * [__bang__][bang]: an accent or sudden ending of a [sound][sounds]
  * [__trem__][trem]: a rapid articulation of a [sound][sounds]
  * [__stay__][stay]: an indefinite sustaining of [sound][sounds]
* [__drift__][drift]: microtonal adjustments
* [__chant__][chant]: lyrics beneath the [voices][voice]

### [SCHEMES][schemes]

Toward a deeper understanding

* [__clock__][clock]: a [scheme][schemes] for visualization the relationships between [tones][tone]/[spans][span]
  * [__hue clock__][hue clock]: [tones][tone]/[spans][span] arranged in chromatic order
  * [__lux clock__][lux clock]: [tones][tone]/[spans][span] arranged in harmonic order
  * [__lux__][lux]: a measure of the relative brightness or darkness of an interval
  * [__bright lux__][bright lux]: a harmonic relationship evoking a sense of opening up
  * [__dark lux__][dark lux]: a harmonic relationship evoking a sense of settling down
  * [__vibe__][vibe]: a measure of emotional quality of an interval
  * [__blend__][blend]: a consonant [vibe][vibe]
  * [__mood__][mood]: a major/minor [vibe][vibe]
  * [__rub__][rub]: a dissonant [vibe][vibe]
* [__tap__][tap]: a system for vocalizing rhythms and [grooves][groove] as [words][word]

[gloss]: #gloss

[bases]: #bases

[term]: #term
[glyph]: #glyph
[phone]: #phone
  [start]: #start
  [rhyme]: #rhyme
[word]: #word
[sign]: #sign

[forms]: #forms

[score]: #score
[stage]: #stage
  [scribe]: #scribe
  [work]: #work
  [act]: #act
[track]: #track
  [key]: #key
  [mode]: #mode
[round]: #round
[bar]: #bar
  [voice]: #voice
  [stack]: #stack
  [rep]: #rep
  [jump]: #jump
  [lap]: #lap
[code]: #code

[sounds]: #sounds

[pitch]: #pitch
[rank]: #rank
[file]: #file
[band]: #band
[notch]: #notch

[beats]: #beats

[hold]: #hold
[groove]: #groove
  [shift]: #shift
  [rift]: #rift
[pulse]: #pulse
[click]: #click
[cut]: #cut
  [short cut]: #short-cut
  [long cut]: #long-cut

[notes]: #notes

[tone]: #tone
  [tone start]: #tone-start
  [tone rhyme]: #tone-rhyme
[root]: #root
[rap]: #rap
[tie]: #tie
[breath]: #breath
[strand]: #stop

[knits]: #knits
[span]: #span
  [span start]: #span-start
  [span rhyme]: #span-rhyme

[thread]: #thread
[strand]: #strand
[chord]: #chord
[braid]: #braid

[cues]: #cues

[comp]: #comp
  [vamp]: #vamp
[tweak]: #tweak
[art]: #art
  [smooth]: #smooth
  [ring]: #ring
  [glide]: #glide
  [slide]: #slide
  [flux]: #flux
  [flam]: #flam
  [lick]: #lick
  [trill]: #trill
  [bang]: #bang
  [trem]: #trem
  [stay]: #stay
[drift]: #drift
[chant]: #chant

[schemes]: #schemes

[clock]: #clock
  [hue clock]: #hue-clock
  [lux clock]: #lux-clock
  [lux]: #lux
  [bright lux]: #bright-lux
  [dark lux]: #dark-lux
  [vibe]: #vibe
  [blend]: #blend
  [mood]: #mood
  [rub]: #rub
[tap]: #tap

***

# Bases

[Bases][bases] are foundational elements for learning and understanding Counternote.

## Term

A [term][term] is the name for a precise concept in music and Counternote. They are monosyllablic to be easy to remember and speak about. Each [term][term] has an entry in this [gloss][gloss].

## Glyph

A [glyph][glyph] is any typed character in Counternote. They have been intentionally limited to the visible characters of 7-bit ASCII plus whitespace `␣` and newline `↵`:

    ———————————————————————————————————
      ␣ ! " # $ % & ' ( ) * + , - . /
      0 1 2 3 4 5 6 7 8 9 : ; < = > ?
      @ A B C D E F G H I J K L M N O
      P Q R S T U V W X Y Z [ \ ] ^ _
      ` a b c d e f g h i j k l m n o
      p q r s t u v w x y z ( | ) ~ ↵
    ———————————————————————————————————

All [glyphs][glyph] are presented here in `monospace`.

## Phone

A [phone][phone] is an indivisible articulation of spoken Counternote represented by one or two [glyphs][glyph] and up to three phonemes.

### Start

A [start][start] is the first [phone][phone] or *linguistic onset* of a [word][word]. All of these sounds are found in American English, but the letters `c`, `q`, and `x` have been reassigned to tʃ 'ch', kʷ 'qu', and ʃ 'sh'. Because the American English 'r' is exceptionally weird, a trilled 'r' is also correct. Curiously, most languages have a 'ch' kind of sound, but way fewer have its voiced counterpart 'j', so if you have trouble, just say the 'ch' sound while keeping your vocal cords vibrating. A ʒ 'zh' consonant can be substituted.

The standard starting consonants with their points of articulation going from “high” to “low” (to the “neutral” glottal consonants) are as follows:

    —————————————————————————————————
      GLYPH    IPA    PRONUNCIATION
      ~~~~~~ BILABIAL ~~~~~~~~~~~~~
       P,p      p     'p' in 'pick'
       B,b      b     'b' in 'bow'
       M,m      m     'm' in 'muse'
      ~~~~~ LABIODENTAL ~~~~~~~~~~~
       F,f      f     'f' in 'fun'
       V,v      v     'v' in 'vibe'
      ~~~~~~ ALVEOLAR ~~~~~~~~~~~~~
       L,l      l     'l' in 'lick'
       T,t      t     't' in 'tom'
       D,d      d     'd' in 'din'
       N,n      n     'n' in 'neck'
       S,s      s     's' in 'sine'
       Z,z      z     'z' in 'zip'
      ~~~~ POSTALVEOLAR ~~~~~~~~~~~
       C,c      tʃ   'ch' in 'chip'
       J,j      dʒ    'j' in 'jam'
       R,r     ɹ,r    'r' in 'run'
      ~~~~~~ PALATAL ~~~~~~~~~~~~~~
       X,x      ʃ    'sh' in 'ship'
       Y,y      j     'y' in 'yes'
      ~~~~~~~ VELAR ~~~~~~~~~~~~~~~
       K,k      k     'k' in 'kick'
       G,g      g     'g' in 'good'
       Q,q      kʷ    qu' in 'quit'
      ~~~~ LABIOVELAR ~~~~~~~~~~~~~
       W,w      w     'w' in 'wit'
      ~~~~~~ GLOTTAL ~~~~~~~~~~~~~~
       H,h      h     'h' in 'hit'
        -       ʔ     '-' in 'uh-oh'
    —————————————————————————————————

Capital vowels and vowels at the beginning of a [word][word] are preceeded by an unwritten [ʔ]. An unwritten [j] and an unwritten [w] are sometimes used to break up consecutive vowels.

Some [glyphs][glyph] can cluster:

    ————————————————————————————————
      GLYPHS   IPA   PRONUNCIATION
        my-     mʲ       'my'
        mw-     mʷ       'mw'
        ny-     nʲ       'ny'
        nw-     nʷ       'nw'
    ————————————————————————————————

### Rhyme

A [rhyme][rhyme] is the rhyming part or *linguistic coda* of a [word][word].

All [rhymes][rhyme] include vowels as part of their [phone][phone]. Vowels are pure spanish vowels plus the schwa [ə] and a rhoticized mid vowel [ɚ]:

    ————————————————————————————————
      GLYPH    IPA   PRONUNCIATION
        a       ɑ        'ah'
        h       ə        'uh'
        u       u        'oo'
        o       o        'oh'
        e       e        'eh'
        i       i        'ee'
        r      ɚ,r̩       'er'
    ————————————————————————————————

As well as some clustered [phones][phone] as [rhymes][rhyme]:

    ————————————————————————————————
      RHYME    IPA   PRONUNCIATION
       -m       əm       'uhm'
       -p       up       'oop'
       -n       on       'ohn'
       -f       ɛf       'ehf'
       -v       iv       'eev'
    ————————————————————————————————

## Word

A [word][word] is connected sequence of [phones][phone] that can be spoken like the [tone][tone] `la` or the [hold][hold] `qa` (`.`).

## Sign

A [sign][sign] is connected sequence of [glyphs][glyph] do not make a [word][word] like the starting sequence `++*`.

***

# Forms

[Forms][forms] are structural elements of a composition and how such elements connect together. Here is the A-section of Bourrée by Bach: __WIP__

<!-- TO BE REWRITTEN
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
    # ma Xov |4.| @allegretto

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
        f| hh-         .     %      |
        t| Bveva^-     .     %A %B  |

    *++
-->

## Score

A [score][score] is an entire composition in Counternote. It is enclosed in `++*` and `*++` [signs][sign]. When detailed in the [stage][stage], it is the title of a work.

## Stage

A [stage][stage] holds compositional and instrumental details on entire [scores][score] and individual [tracks][track] such as title, author, instrument voices and tunings, and the like. The [score][score] [stage][stage] is between the `++*` and `+++` [signs][sign]. The [track][track] [stage][stage] is between `+++` [signs][sign].

### Scribe

A [scribe][scribe] is a composer of a [score][score] or [track][track].

### Work

A [work][work] is collection of music a [score][score] or [track][track] belongs to.

### Act

An [act][act] is the performer of a [score][score] or [track][track].

## Track

A [track][track] is an individual piece that may or may not occur simultaneously within a score. The are separated with `+++` [signs][sign].

### Mode

A [mode][mode] is the home scale for a [track][track] denoted by its representative[chord][chord]: __WIP__

<!--
    ————————————————————————
      WORD    TONALITY
    ————————————————————————
      Dtv     Lydian
      Dev     Major/Ionian
      Devn    Mixolydian
      Dovm    Dorian
      Dov     Minor/Aeolian
      Drv     Phrygian
      Dot     Locrian
    ————————————————————————
-->

## Round

A [round][round] is a block of music, often repeated, marked with an unindented letter or string on its own line for legibility, denoted above with `A`.

## Bar

A [bar][bar] contains all of the details of what to play when and how to play it marked with a two-space indented numeral on its own line, again for legibility, denoted above with `0`, `1`, `2`, and the like. The main component of a [bar][bar] is a [voice][voice], but it may also include composer directions and accompaniments and lyrics. `0` indicates a *pick-up bar*, an incomplete bar that leads into the first [beat][beats]. A specific [bar][bar] can be accessed outside a [round][round] by referencing the [round][round] followed by the [bar][bar] with a `'` in between, for example `A'1`.

### Voice

A [voice][voice] is akin to a sequence of music performed by a monophonic instrument such as a human *voice* enclosed in `|`:

    —————————————————————————————————————————
      # |4.|
      1
        | la=                             |
      2
        | la-             la-             |
      3
        | la.     la.     la.     la.     |
      4
        | la, la, la, la, la, la, la, la, |
    —————————————————————————————————————————

A [voice][voice] can be extended to another line using `+` at the end of the next to last lines and at the start of the next lines:

    —————————————————————————————————————————
      # |4.|
      5
        | la: la: la: la: la: la: la: la: +
        + la: la: la: la: la: la: la: la: |
      6
        | la; la; la; la; la; la; la; la; +
        + la; la; la; la; la; la; la; la; +
        + la; la; la; la; la; la; la; la; +
        + la; la; la; la; la; la; la; la; |
    —————————————————————————————————————————

Inline harmonies such as [strands][strand] and [chords][chord] are multiple [voices][voice] even if performed by the same instrument and notated on the same line. Harmonies can alternatively be notated by a [stack][stack]. 

### Stack

A [stack][stack] is separate voices in the same [bar][bar]. These can be separate instruments for an ensemble, or the same instrument like the right and left hands of a piano player or even the six strings of a guitar for a more musically informative tablature. The individual [voices][voice] can be labeled like in the Bourrée: __WIP__

<!-- 
    ———————————————————————————————————
      1
        f| lo.   lu.la ls.   la.lu  |
        t| ta.   ti.   hv.   ti.    |
    ———————————————————————————————————
-->

### Lap

A [lap][lap] is a variation on a [bar][bar] to be played in different iterations of a [round][round]. It is denoted by the [bar][bar] followed by the [lap][lap] with a `'` in between, much like a [bar][bar] is specified from outside a [round][round] `8'1`.

### Jump

A [jump][jump] is a directive on what part to play next. [Jumps][jump] are denoted by `%` followed by the [bar][bar] or [round][round] to continue from.

### Rep

A [rep][rep] is a directive to repeat some number of [holds][hold] previous. It is denoted by `%%` to repeat the previous bar or `%%..` to repeat the previous `..`.

## Code

A [code][code] holds the programmery bits. 

***

# Sound

A [sound][sounds] is any acoustic vibration fit to be notated. They come in two monophonic varieties: [tones][tone] and [raps][rap]. The first deals with those of definite [pitch][pitch], whereas [raps][rap] deal with those of indefinite or incidental [pitch][pitch].

## Pitch

A [pitch][pitch] is the number of vibrations per second, the frequency.

## Rank

A [rank][rank] is like all traditional notes regardless of octave, also known as the pitch-class, the set of pitches separated by powers of two. These are written as [tones][tone] in all caps with the [rhyme][rhyme] for the [file][file] such as `LA` for *A* in the octave below *middle C*, usually *A3* or precisely *A220*. 

## File

A [file][file] is analogous to the octave number, for instance the [band][band] from 220Hz to 440Hz.

## Band

A [band][band] is a defined range of frequencies with the lower bound inclusive and the upper bound exclusive.

## Notch

A [notch][notch] is a [band][band] a twelth root of two wide, a traditional *semitone* or *half-step*.

# Beats

[Beats][beats] are basic rhythmic elements

## Hold

A [hold][hold] is punctuation character that represents a duration. They come in six varieties ordered by powers of two:

    ———————————————————————————
      HOLD  VALUE  WORD   IPA
    ———————————————————————————
      `:`    1/32   qi    kʷi
      `,`    1/16   qe    kʷe
      `;`    1/8    qh    kʷə
      `.`    1/4    qa    kʷɑ
      `-`    1/2    qo    kʷo
      `=`    1/1    qu    kʷu
    ———————————————————————————

Plus two others, immediate and indeterminant:

    ——————————————————————————————————
      HOLD     VALUE     WORD   IPA
    ——————————————————————————————————
      `!`    immediate    ql    kʷɛl
      `?`  indeterminant  qr    kʷɚ
    ——————————————————————————————————

## Groove

A [groove][groove] tells the arrangement of [beats][beats] in a [bar][bar]. It is notated `|4.|` with the number of [holds][hold] summing to the total length of a [bar][bar].

    —————————————————————————————————————————
      # |4.|
      1
        | la=                             |
      2
        | la-             la-             |
      3
        | la.     la.     la.     la.     |
      4
        | la, la, la, la, la, la, la, la, |
      5
        | la: la: la: la: la: la: la: la: +
        + la: la: la: la: la: la: la: la: |
      6
        | la; la; la; la; la; la; la; la; +
        + la; la; la; la; la; la; la; la; +
        + la; la; la; la; la; la; la; la; +
        + la; la; la; la; la; la; la; la; |
    —————————————————————————————————————————

 But [grooves][groove] can go beyond that — they can tell the accent pattern within a [bar][bar]. `|!,,!,,!,!,|` is the 5/4 clave. The accents are denoted with `!` and take the length of the rest of the [holds][hold] in the [groove][groove].

### Shift

A [shift][shift] is a section of polymeter with one [groove][groove] superimposed over another at the same [pulse][pulse] so the first beat shifts around because the lengths of the bars are different. It is notated `|3./2.|` *three over two* with the number of [holds][hold] in the [bar][bar] measured by the first [groove][groove]:

    ———————————————————————————
      # |3./2.|
      1
        # three over two
        | la.   la.   la.   |
    ———————————————————————————

Like with [grooves][groove], the [shift][shift] can be notated within the [voice][voice]:

    ————————————————————————————————
      # |2.|
      1
        # three over two
        |3./2. la.   la.   la.   |
    ————————————————————————————————

### Rift

A [rift][rift] is a section of polyrhythm with one [groove][groove] mashed against another at different [pulses][pulse] so the first beat and total [bar][bar] length stays the same but the [grooves][groove] drift in and out of phase. It is notated `|3.\2.|` *three against two* with the total length of the [bar][bar] measured by the second [groove][groove]:

    ———————————————————————————
      # |3.\2.|
      1
        # three against two
        | la.   la.   la.   |
    ———————————————————————————

Like with [grooves][groove], the [right][right] can be notated within the [voice][voice]:

    ————————————————————————————————
      # |2.|
      1
        # three against two
        |3.\2. la.   la.   la.   |
    ————————————————————————————————

## Pulse

A [pulse][pulse] gives the tempo. It is denoted by an `@` symbol followed by an exact bpm, a range of bpms, or a tempo descriptor. 

## Click

A [click][click] refers to the [hold][hold] that gets counted: In `|4.|`, `.` is one [click][click].

## Cut

A [cut][cut] is a subdivision of a [beat][beats], also known as a tuplet. While there are six well-defined [holds][hold] that do duple meter, many more can be achieved without redefining holds or changing the [pulse][pulse].

### Short Cut

A [short cut][short cut] is a quick and dirty way of defining a [cut][cut], pun intended. It works with small prime number tuplets: duplets, triplets, and quintuplets. The rules are as follows:

* no whitespace exists between the [sounds][sounds]
* [holds][hold] act as separators of the [sounds][sounds] in the [cut][cut]
* the last [sound][sounds] does *not* receive a [hold][hold]
* the total duration of all the [holds][hold] is the duration the [cut][cut] fills
* a `'` can be used as a separator that does not add duration
* quadruplets and sextuplets should be written as two duplets/triplets connected by a `'`
* septuplets and longer just add [sounds][sounds] and `'`
* a [tie][tie] `aa` may be used to signal that one [sound][sounds] is held

Those rules add up to:

    —————————————————————————————————————————
      # |4.|
      1
        # one beat for =
        | la=                             |
        # is equivalent to
        | la=aa                           |
      2
        # two beats over =
        | la-             la-             |
        # is equivalent to
        | la=la                           |
      3
        # three beats over --
        | la-la-la                        |
      4
        # four beats over --
        | la-la           la-la           |
        # is equivalent to
        | la-la'la-la                     |
        # is equivalent to
        | la.     la.     la.     la.     |
      5
        # five beats over ....
        | la.la.la.la.la                  |
      6
        # six beats over ....
        | la.la.la'la.la.la               |
        # is equivalent to
        | la.la.la        la.la.la        |
      7
        # seven beats over ....
        | la.la.la'la.la'la.la            |
      8
        # eight beats over ....
        | la.la   la.la   la.la   la.la   |
        # is equivalent to
        | la.la'la.la     la.la'la.la     |
        # is equivalent to
        | la.la'la.la'la.la'la.la         |
        # is equivalent to
        | la, la, la, la, la, la, la, la, |
    —————————————————————————————————————————

[Short cuts][short cut] can greatly cut down on visual noise. Consider what the Bourrée above looks like using [holds][hold] on every [note][notes]: __WIP__

<!-- 
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
    # ma Xov |4.| @allegretto

    A
      0
        f| -               .       la, lu,  |
        t| -               .       to, tu,  |
      1
        f| lo.     lu, la, ls.     la, lu,  |
        t| ta.     ti.     hv.     ti.      |
      2
        f| lv.     ln, ls, la.     lm, ll,  |
        t| to.     tu.     ta.     tu.      |
      3
        f| lv.     hi, ho, hu.     ho, hi,  |
        t| to.     ti.     hv.     ti.      |
      4
        f| lv, hi, ho, hu, ha.     la, lu,  |
        t| to.     hv.     ta, tu, to, tu,  |
      5
        f| lo.     lu, la, ls.     la, lu,  |
        t| ta.     ti.     hv.     ti.      |
      6
        f| lv.     ln, ls, la.     lm, ll,  |
        t| to.     tu.     ta.     tu.      |
      7
        f| lv.     li, lo, lu^^o.  ,   lo,  |
        t| to.     hl.     hm.     hm.      |
      8
        f| hh-             .       %        |
        t| Bveva^-         .       %A %B    |

    *++
-->

### Long Cut

A [long cut][long cut] uses square brackets with `'` between [sounds][sounds] and [holds][hold] at the end to slice up the [bar][bar].

    —————————————————————————————————
      # |4.|
      1
        # one beat for =
        | la=                     |
        # is equivalent to
        |[la'aa]=                 |
      2
        # two beats over =
        | la-la                   |
        # is equivalent to
        |[la'la]=                 |
      3
        # three beats over =
        | la-la-la                |
        # is equivalent to
        |[la'la'la]=              |
      4
        # four beats over =
        | la-la       la-la       |
        # is equivalent to
        | la-la'la-la             |
        # and equivalent to
        |[la'la]-    [la'la]-     |
        # and equivalent to
        |[la'la'la'la]=           |
    —————————————————————————————————

[Long cuts][long cut] work in two places where [short cuts][short cut] cannot: nested tuplets and across multiple bars.

To nest a [cut][cut], just place a [long cut][long cut] where a single sound would go:

    —————————————————————————————————
      # |4.|
      1
        # triplet in triplet
        |[la'la'[la'la'la]]=      |
        | la-la-[la'la'la]        |
    —————————————————————————————————

If a nested [cut][cut] takes up more than one element of a tuplet, `+` and the [tie][tie] `aa` are used: 

    —————————————————————————————————
      # |4.|
      1
        # triplet in triplet
        |[la'[la'la'la]+aa]=       |
        | la-[la'la'la]-+aa        |
    —————————————————————————————————

Because tuplets are treated as a block of one duration split evenly, the total duration must be present at the end even if it goes on longer than the [bar][bar] where it’s written. The `+` and [tie][tie] `aa` are used in this case as well:

    —————————————————————————————————
      # |4.|
      1
        # triplet over...
        |[la'la'la]=+=            |
      2
        # ...2 bars
        | aa=                     |
    —————————————————————————————————

The `+` with the extra [hold][hold] `=` helps the performer see what how long the [cut][cut] is.

***

# Notes

[Notes][notes] are [sounds][sounds] for a [hold][hold].

## Tone

A [tone][tone] capitalized as a [rank][rank] is the closest to a *note* in a traditional sense, like the pitch-class of *C* or a specific C note. Any [pitch][pitch] that when multiplied or divided by powers of two falls in the [notch][notch] starting from 256Hz is described by the [rank][rank] `LA`. That means any [pitch][pitch] that falls in the [notch][notch] from about 430.5Hz to just over 456Hz is `LA` including *A440*, *A444*, and *A432*, but not including the baroque tuning *A415*, which falls into the [rank][rank] `GA` just below.

A lowercase [tone][tone] is akin to a *scale degree* or *movable-do*, a note relative to the specified [key][key]. If no [key][key] is specified, the default is `LA`. Since music is predominantly a relative pitch phenomenon, only the setting of the [key][key] is done using the absolute pitch of the capitalized [tone][tone].

A matrix of all the [tones][tone] moving left to right, bottom to top: __WIP__

<!-- 
    ——————————————————————————————————————————————————————
      RANK (pitch class) →
    ——————————————————————————————————————————————————————
          E   F   F♯  G   G♯  A   A♯  B   C   C♯  D   D♯
      +5 mil bil fil zil sil lil til nil dil cil ril kil 
      +4 mal bal fal zal sal lal tal nal dal cal ral kal 
      +3  ml  bl  fl  zl  sl  ll  tl  nl  dl  cl  rl  kl 
      +2  mi  bi  fi  zi  si  li  ti  ni  di  ci  ri  ki 
      +1  me  be  fe  ze  se  le  te  ne  de  ce  re  ke 
       0  ma  ba  fa  za  sa  la  ta  na  da  ca  ra  ka 
      -1  mo  bo  fo  zo  so  lo  to  no  do  co  ro  ko 
      -2  mu  bu  fu  zu  su  lu  tu  nu  du  cu  ru  ku 
      -3  mr  br  fr  zr  sr  lr  tr  nr  dr  cr  rr  kr
      -4 mar bar far zar sar lar tar nar dar car rar kar
      -5 mor bor for zor sor lor tor nor dor cor ror kor
    ——————————————————————————————————————————————————————
      ↑ FILE (octave)
    ——————————————————————————————————————————————————————
-->

### Tone Start

The [start][start] of a [tone][tone] will always be a consonant represented by a single [glyph][glyph]. Their pitch will always be relative to the current [key][key] written here as a semitone or [notch][notch] offset

    ———————————————————————————————
      START  OFFSET  IPA  ENGLISH
    ———————————————————————————————
        w-     +6      w     'w'
        t-     +5      t     't'
        y-     +4      j     'y'
        c-     +3     tʃ    'ch'
        z-     +2      z     'z'
        k-     +1      k     'k'
    ———————————————————————————————
        l-     ±0      l     'l'
    ———————————————————————————————
        g-     -1      g     'g'
        s-     -2      s     's'
        j-     -3     dʒ     'j'
        x-     -4      ʃ    'sh'
        d-     -5      d     'd'
    ———————————————————————————————

### Tone Rhyme

The [rhyme][rhyme] of a [tone][tone] is all but the [start][start], also known as the rhyming part (linguistic coda). It represents the [file][file] of the [tone][tone].

    —————————————————————————————
      RHYME  FILE  IPA  ENGLISH
    —————————————————————————————
       -il    +6    il   'eel'
       -al    +5    al   'ahl'
       -l     +4    ɛl   'ehl'
       -i     +3    i     'ee'
       -e     +2    e     'eh'
       -h     +1    ə     'uh'
    —————————————————————————————
       -a     ±0    ɑ     'ah'
    —————————————————————————————
       -o     -1    o     'oh'
       -u     -2    u     'oo'
       -r     -3    ɚ     'er'
       -ar    -4    ɑ˞    'ar'
       -or    -5    ɔ˞    'or'
    —————————————————————————————

## Root

The tonic of a [span][span] or [knit][knits].


## Rap

A [rap][rap] is any sound where [pitch][pitch] is indeterminate or incidental. Rather than having some algorithmic way of bulding these, [raps][rap] are just a simple, user-definable lookup table with the caveat that they cannot conflict with [tones][tone], [spans][span], or the reserved [raps][rap]. These are some of the proposed [raps][rap]: __WIP__

<!-- 
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
-->

## Sync

[Raps][rap] can be performed at the same time by just concatenating them together with a `!` in between so it’s easy to read. These can be combined with [tones][tone] and [knits][knits] for percussive playing. __WIP__

<!-- 
    ———————————————————————————————————————
      WORD            VALUE
    ———————————————————————————————————————
      bm!xd   bass drum + closed hi-hat
      xk!kl       shook + clap
    ———————————————————————————————————————
-->

## Tie

A [tie][tie] is a [rap][rap] used to show a [sound][sounds] from a previous [bar][bar] is still being held. It is notated with the [word][word] `aa` and not pronounced separately from the [sound][sounds] being held.

## Breath

A [breath][breath] is a [rap][rap] that gives the player room to breathe. It is notated with the [word][word] `hh` and not explicitly pronounced.

***

# Knits

[Knits][knits] are collections of notes occuring simultaneously. [Knits][knits] come in three varieties: [strands][strand], [chords][chord], and [braids][braid].

## Span

A [span][span] is an interval. __WIP__

### Span Start

<!-- 
The [start][start] of a [span][span] indicates the [file][file] above or below the mid-range [root][root] or [key][key]. Middle C would typically be in the `h-` [file][file].

    —————————————————————————————
      START  FILE  IPA  ENGLISH
    —————————————————————————————
       ny-    +5    nʲ    'ny'
       nw-    +4    nʷ    'nw'
       n-     +3    n      'n'
       t-     +2    t      't'
       l-     +1    l      'l'
    —————————————————————————————
       h-     ±0    h      'h'
    —————————————————————————————
       v-     -1    v      'v'
       p-     -2    p      'p'
       m-     -3    m      'm'
       my-    -4    mʲ    'my'
       mw-    -5    mʷ    'mw'
    —————————————————————————————

-->

### Span Rhyme

<!--
The [rhyme][rhyme] of a [span][span] tells the interval from a [root][root] or [key][key]. The quality of the vowel tells the distance from the its starting point while a terminating consonant (excluding `-r` which is treated as a vowel in this case) means it’s an interval closest to the [root][root] from below. For brevity and symmetry, only the final [glyph][glyph] of the [rhyme][rhyme] is written.


    ——————————————————————————————————
      RHYME  INTERVAL  IPA   ENGLISH
    ——————————————————————————————————
        -z      7     ɚz,r̩z   'erz'
        -n     ♭7       un    'oon'
        -m      6       om    'ohm'
        -l     ♭6     ɛl,el   'ehl'
        -v      5       iv    'eev'
        -p    ♯4/♭5  ɑ˞p,arp  'arp'
        -i      4       i      'ee'
        -e      3      ɛ,e     'eh'
        -o     ♭3       o      'oh'
        -u      2       u      'oo'
        -r     ♭2      ɚ,r̩     'er'
        -a      1       ɑ      'ah'
    ——————————————————————————————————
-->


## Knit Start

All [knits][knits] begin with a capitalized consonant corresponding with a [tone rhyme][tone rhyme]. __WIP__

<!-- 
    —————————————————————————
      KNIT   RHYME   DEGREE  
    —————————————————————————
        Z      -z      7
        N      -n     ♭7
        M      -m      6
        L      -l     ♭6
        V      -v      5
        P      -p    ♯4/♭5
        Y      -i      4 
        J      -e      3     
        B      -o     ♭3
        W      -u      2
        R      -r     ♭2
        X      -a      1
    —————————————————————————
-->

## Thread

A [thread][thread] is a single [voice][voice] within a [knit][knits]. They are the [glyphs][glyph] for the [span rhymes][span rhyme] without the extra vowel content attached to the consonants. Because vowels can cluster with vowels (`VV`) and consonants with consonants (`CC`), there are some additional rules for pronunciation: __WIP__

<!-- 
    ——————————————————————————————
      V:  a,r,u,o,e,i
      C:  p,v,l,m,n,z
      G:  any glyph
      X:  end of string
      -:  syllable break
    ——————————————————————————————
      GLYPH  BEFORE  ADDS   IPA
    ——————————————————————————————
        a      V      y     a-jV
        r      V      r     ɚ-rV
        u      V      y     u-jV
        o      V      w     o-wV
        e      V      w     e-wV
        i      V      y     i-jV
    ——————————————————————————————
        VC     CV     -    VC-CV
        VC     CC     ə    VC-CəC
        VC     CX     ə    V-CəC
    ——————————————————————————————
-->

The [blends][blend] that are vowels always get the patalal glide [j] starting the next syllable whereas the [moods][mood] and [rubs][rub] always get labiovelar [w]. The [glyph][glyph] `r` as a thread is always its vowel [phone][phone].

## Twine

A [twine][twine] is two [voices][voice] sounding simultaneously. __WIP__

<!-- 
    ———————————————————————————————————
        WORD   VALUE (ABOVE)    IPA
    ———————————————————————————————————
        hLa     two octave     
        hLz     major 14th     
        hLn     minor 14th     
        hLm     major 13th     
        hLl     minor 13th     
        hLv    perfect 12th    
        hLp   augmented 11th   
        hLi    perfect 11th    
        hLe     major 10th     
        hLo     minor 10th     
        hLu     major 9th      
        hLh     minor 9th      
        hLa       octave         
        aLm      major 7th       
        aLp      minor 7th       
        aLn      major 6th       
        aLf      minor 6th       
        aLv     perfect 5th      
        aLr    diminished 5th    
        aLi     perfect 4th      
        aLe      major 3rd       
        aLo      minor 3rd       
        aLu      major 2nd       
        aLh      minor 2nd       
        aLa       unison         
    ———————————————————————————————————
-->

## Chord

A [chord][chord] is a [knit][knits] constructed using the capitalized [tone start][tone start] as the [root][root] and [threads][thread] for all other voices.

    ————————————————————————————————————————————————————————
        CHORD      WORD         IPA        TRANSLITERATION
    ————————————————————————————————————————————————————————
         A          
         B5      
         Cm      
         C♯7     
         D13     
      E♭13(♭5♯9) 
    ————————————————————————————————————————————————————————


## Braid

__WIP__

<!-- 
## Weave

A [weave][weave] is a specific voicing of a [chord][chord] or [braid][braid]. These get much more complicated looking, but they follow the same rules with three added details. First, no octave is specified, so the [span start][span start] of the lowest sounding voice is prefixed to the [chord][chord] or [braid][braid]. Second, no root is implied so every voice gets a thread. Third, if an entire octave is skipped, the [glyph][glyph] `x` is inserted.

    ——————————————————————————————————————————————————————————————————————————————————
      COMMON GUITAR VOICINGS
    ——————————————————————————————————————————————————————————————————————————————————
      CHORD   TAB    THREADS    WORD            IPA             TRANSILITERATION
    ——————————————————————————————————————————————————————————————————————————————————
        E    022100  
                    
        A    x02220  
                    
       A/E   002220  
                    
        D    xx0232  
                    
       D/F♯  200232 
                    
        G    320033 
                    
        G    320003  
                     
        C    x32010 
                    
       C/G   332010  
                    
        F    1x3211 
                    
    ——————————————————————————————————————————————————————————————————————————————————
*** 
-->

# Cues

[Cues][cues] are composer directives, denoted by [glyph][glyph] `#`. In the Bourrée above, a [track][track]-level [cue][cues] is followed by the [key][key] `ma` to specify the key center, the 1-[chord][chord] `Xov` to specify the [mode][mode], the [groove][groove] for four [beats][beats] `|4.|`, and all at an allegretto [pulse][pulse].

## Comp

A [comp][comp] is a minimally specified accompaniment and harmonic background written within the [bar][bar].

### Vamp

A [vamp][vamp] is a [comp][comp] that specifies rhythm and/or voicings.

## Tweak
 
A [tweak][tweak] is an instruction on effects that occur above the [voices][voice] they modify. They can be placed inline by being enclosed in `#[` and `]#`.

## Art

An [art][art] is an inline [cue][cues] each of which are denoted by special [glyphs][glyph] and rules.

### Smooth

A [smooth][smooth] lick is legato, which is to be determined by each instrument. Such licks are bracketed by parentheses `(` `)`.

### Ring

A [ring][ring] lick shows [sounds][sounds] sustaining over other [sounds][sounds]. These begin with the [sound][sounds] (without any [hold][hold] if simultaneous, with if there is a delay) followed by curly brackets `{` `}` with the concurrent [sounds][sounds] notated bewteen them. The [hold][hold] for the outside [note][notes] is at least as long as the combined [holds][hold] within the curly brackets. [Bar][bar] 7 above can be notated both of the following ways:

    ————————————————————————————————————————————————
      7
        f| lv.   li.lo lu^^o.  ,lo, |
        t| vo.   hl.   hm.   hm.    |   
      7
        | vo{lv.} hl{li.lo} hm{lu^^o.} hm{aa.lo} |
    ————————————————————————————————————————————————

For [sounds][sounds] meant to sustain freely as they are played like when lifting the dampers on a piano, double curly brackets `{{` `}}` are used.

### Glide

A [glide][glide] is the smooth changing of a [sound][sounds] to a different [pitch][pitch], like a bend. `/` is for changing a [sound][sounds] up, `\` for changing a [sound][sounds] down.

### Slide

A [slide][slide] is the stepped changing of [sound][sounds] to a different [pitch][pitch] like a fret slide. `//` is for changing a [sound][sounds] up, `\\` for changing a [sound][sounds] down.

### Flux

A [flux][flux] is a repeated fluctuation in the [pitch][pitch] of a [sound][sounds]. It is an [art][art] denoted by the [glyph][glyph] `~`.

### Flam

A [flam][flam] is the quick articulation of one [sound][sounds] before another. It is an [art][art] denoted with a [span start][span start] followed by the [glyph][glyph] `^` and the [span][span] to land on.

### Lick

A [lick][lick] is quick run of [sounds][sounds], often repeated. It is an [art][art] denoted with a starting [span][span] followed by a sequence of [span rhymes][span rhyme] separated by a [flam][flam], [glide][glide], or [slide][slide] in the order they are articulated, finishing on [span][span] or returning to the starting [span][span] if nothing else is specified.

### Trill

A [trill][trill] is the quick alternating between two [sounds][sounds] used as ornamentation. It is an [art][art] denoted with the starting [span][span] a double [flam][flam] [glyph][glyph] `^^` followed by the [rhyme][rhyme] of the [span][span] to be alternated with.

### Bang

A [bang][bang] is an accent and/or sudden ending of a [sound][sounds] denoted by `!`. It is written directly before the [note][notes] it modifies `!la.` for accents, directly after the the note for staccato `la!.`, or even directly after a [hold][hold] for that abrupt ending `la.!`.

### Trem

A [trem][trem] is the rapid articulation of a sustained [sound][sounds]. It is denoted by `!!` after the [sound][sounds] `la!!.`.

### Stay

A [stay][stay] is an indefinite sustaining of a [sound][sounds]. It is denoted by `?` and roughly equivalent to a fermata. By default, it will add at least one extra [click][click] without changing the [groove][groove]. A [stay][stay] affects an entire [bar][bar], but only the [sounds][sounds] notated with the [stay][stay] will be held. The duration of the sustain can be altered by adding [holds][hold] immediately after the [stay][stay]: `?..` will add at least two [clicks][click] to a [bar][bar] of `|4.|` for a total of six [clicks][click].

### Node

A [node][node] is the place where a resonating medium remains static such as at the twelfth fret with the second harmonic or an overtone accentuated in throat singing. It is denoted by `*` followed by the number for the nth harmonic: `lo*3` is the [node][node] for the third harmonic at the seventh or nineteenth fret that sounds like the first string on a guitar `me`. Rather than notating the pitch as a listener might hear it, Counternote notates the harmonic as it’s played.

## Drift

A [drift][drift] is a microtonal adjustment. These can be adjusted globally or inline. They are just like the [span rhymes][span rhyme] added to whole [spans][span].

    ————————————
      -p  +50
      -i  +42
      -e  +33
      -o  +25
      -u  +17
      -r  +8
      -a  ±0
      -z  -8
      -n  -17
      -m  -25
      -l  -33
      -v  -42
    ————————————

`la/hup` ˌdɑ.huˈjɑ˞p is a whole step and a quarter bend to D half-sharp. `lap` dɑˈjɑ˞p is a C half-sharp.

Like with [weaves][weave], there are rules for consecutive vowels, so [blends][blend] get a [j] to break up the vowels while [moods][mood] and [rubs][rub] get a [w].

## Chant

A [chant][chant] is a set of lyrics to be sung set below the [voice][voice] with its corresponding melody. It is enclosed in double straight quotes `"` with each syllable getting at least one [sound][sounds] and underscores `_` for multiple [sounds][sounds]. Speech is denoted by the [rap][rap] `sp` in the [voice][voice].

***

# Schemes

[Schemes][schemes] are informational diagrams to help learn and understand Counternote and the underlying music theory.

## Clock

A [clock][clock] is a [scheme][schemes] for visualizing the relationships between [spans][span].

### Hue Clock

The [hue clock][hue clock] places [spans][span] in chromatic sequence around a clockface so that stepping clockwise goes up a [notch][notch] and counterclockwise goes down a [notch][notch].

    ————————————————————————————————————————————————
                                             NOTCH
                         1                    DIFF
               7        ha        ♭2            0
                 hz  ===||===  hr              ±1
         ♭7             ||              2
            hn  ========||========  hu         ±2
                        ||
                        ||
       6  hm  ==========||==========  ho  ♭3   ±3
                        ||
                        ||
            hl  ========||========  he         ±4
         ♭6             ||              3
                 hv  ===||===  hi              ±5
               5        hp        4            +6
             BREAK ↑  ♯4/♭5
    ————————————————————————————————————————————————

### Lux Clock

Swapping every odd-numbered value with its counterpart (1 with 7, 3 with 9, 5 with 11) makes the [lux clock][lux clock] with all of the [spans][span] written in harmonic sequence around the clockface. All of the [bright luxes][bright lux] are on the right and all of the [dark luxes][dark lux] are on the left. The [blends][blend], [moods][mood], and [rubs][rub] slice the [lux clock][lux clock] horizontally into three sections. 

    —————————————————————————————————————————————————
       |-----DARK-----| LUX |----BRIGHT----|  
                         1                 |-VIBE-|
                4       -a        5         BLENDS
                  -i  ==||==  -v               |
          ♭7            ||             2       |
             -n  =======||=======  -u        —————
                        ||
                        ||
       ♭3  -o  =========||=========  -m   6  MOODS
                        ||                     |
                        ||                     |
             -l  =======||=======  -e        —————
          ♭6            ||             3
                  -r  ==||==  -z              RUBS
               ♭2       -p        7            |
                      ♭5/♯4                  —————
    —————————————————————————————————————————————————

### Lux

A [lux][lux] is a measure of how [bright][bright lux] or [dark][dark lux] an interval is. This lines up mostly with major (large) and minor (small) itervals but also includes the perfect fourth and fifth (dark and bright) respectively.

### Bright Lux

A [bright lux][bright lux] is a harmonic relationship that evokes a sense of opening up, turning outward. It includes all major (large) intervals plus the (larger) perfect fifth.

### Dark Lux

A [dark lux][dark lux] is a harmonic relationhip that evokes a sense of settling down, turning inward. It includes all minor (small) intervals plus the (smaller) perfect fourth.

### Vibe

A [vibe][vibe] is the emotional quality of an interval that runs orthogonal to [lux][lux].

### Blend

A [blend][blend] is a more harmonious [vibe][vibe]: `-a`, `-u`, `-i`, `-v`, `-m`. They are the high vowels, some paired with labial consonants, plus the [root][root] which is an open vowel.

### Mood

A [mood][mood] is a [vibe][vibe] that gives a major or minor quality: `-o`, `-e`, `-l`, `-n`. All are  mid vowels, some paired with alveolar consonants.

### Rub

A [rub][rub] is a dissonant [vibe][vibe] that clashes with the root: `-r`, `-z`, `-p`. They are all the rhoticized vowels, some paired with consonants.

## Tap

A [tap][tap] is a way of vocalizing the [groove][groove] as [words][word] designed to be understandable by lipreading alone. The classic Greek rhythms are as follows:

    ——————————————————————————————————————————
      |!.|  (trochee)     PO-ge       poge
      |.!|  (iamb)        be-KO       beko
      |!..| (dactyl)      PO-ge-de    pogede
      |.!.| (amphibrach)  be-KO-de    bekode
      |..!| (anapest)     be-ge-TO    begeto
      |!!|  (spondee)     PO-KO       poko
      |..|  (pyrrhic)     be-ge       bege
    ————————————————————————————————————————

The rules for generating these [taps][tap] are rather simple:
* The first [beat][beats] is a bilabial consonant `p` `b`
* The even [beats][beats] (off [beats][beats]) are velar consonants `k` `g`
* The rest of the [beats][beats] are alveolar consonants `t` `d`
* The accent is a voiceless consonant `p` `t` `k` paired with mid rounded `o`
* The lax syllables are voiced consonants `b` `d` `g` paired mid unrounded `e`

The lips will be rounded on the accent and will close at the beginning of the sequence. This is so that the first [beat][beats] and the accent of the sequence can be seen even if not heard.

For typical four-on-the-floor rhythms, we split them into two-syllable [words][word]:

    ————————————————————————————————
      |4.|  PO-ge de-ge  poge dege
      |4.|  be-KO de-ge  beko dege
      |4.|  be-ge TO-ge  bege toge
      |4.|  be-ge de-KO  bege deko
    ————————————————————————————————

Now we can break these up into eigth notes using the `i` for unaccented even eights and `u` for the accented ones:

    ——————————————————————————————————————————————————————
      |8,|  PO-ni ge-ni de-ni ge-ni  poni geni deni geni
      |8,|  be-NU ge-ni de-ni ge-ni  benu geni deni geni
    ——————————————————————————————————————————————————————

And even further into sixteenth notes using the `a` for the unaccented even sixteenths and `o` for the accented ones:

    ———————————————————————————————————————————————————————————————————————————————
      |16:|  PO-a-ni-a ge-a-ni-a de-a-ni-a ge-a-ni-a  poania geania deania geania
      |16:|  be-O-ni-a ge-a-ni-a de-a-ni-a ge-a-ni-a  beonia geania deania geania
      |16:|  be-a-NU-a ge-a-ni-a de-a-ni-a ge-a-ni-a  beanua geania deania geania
      |16:|  be-a-ni-O ge-a-ni-a de-a-ni-a ge-a-ni-a  beanio geania deania geania
    ———————————————————————————————————————————————————————————————————————————————

For complex meter, we break things up into two- and three-syllable [taps][tap]:

    ————————————————————————————————————————————————————————————————————
      |3,3,2,2| PO-de-ge TO-ge-de KO-de KO-de  podege togede kode kode
    ————————————————————————————————————————————————————————————————————

***
