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
* [__snip__][snip]: a place suitable for code

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
* [__rap__][rap]: a [word][word] indicating a [sound][sounds] where [pitch][pitch] is indeterminate or incidental
* [__tie__][tie]: a [sound][sounds] from a previous [bar][bar] is still being held
* [__breath__][breath]: a breath of fresh quiet

### [KNITS][knits]

Manifold acoustic vibrations

* [__root__][root]: the tonic for [spans][span] and [knits][knits]
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
  * [__ring__][ring]: a freely ringing line
  * [__sust__][sust]: a sustained line
  * [__glide__][glide]: a smooth change in [pitch][pitch] of a [sound][sounds]
  * [__slide__][slide]: a stepped change in [pitch][pitch] of a [sound][sounds]
  * [__flux__][flux]: a repeated fluctuation in [pitch][pitch] of a [sound][sounds]
  * [__flam__][flam]: a quick [sound][sounds] before another
  * [__trill__][trill]: a quick alternating between [sounds][sounds]
  * [__star__][star]: an accent or sudden ending of a [sound][sounds]
  * [__trem__][trem]: a rapid articulation of a [sound][sounds]
* [__drift__][drift]: microtonal adjustments
* [__chant__][chant]: lyrics beneath the [voices][voice]

<!-- ### [SCHEMES][schemes]

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
* [__tap__][tap]: a system for vocalizing rhythms and [grooves][groove] as [words][word] -->

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
[snip]: #snip

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
[rap]: #rap
[tie]: #tie
[breath]: #breath
[strand]: #stop

[knits]: #knits
[root]: #root
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
  [sust]: #sust
  [glide]: #glide
  [slide]: #slide
  [flux]: #flux
  [flam]: #flam
  [trill]: #trill
  [star]: #star
  [trem]: #trem
[drift]: #drift
[chant]: #chant

<!-- [schemes]: #schemes

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
[tap]: #tap -->

***

# Bases

__Bases__ are foundational elements for learning and understanding Counternote.

## Term

A __term__ is the name for a precise concept in music and Counternote. They are monosyllablic to be easy to remember and speak about. Each __term__ has an entry in this [gloss][gloss].

## Glyph

A __glyph__ is any typed character in Counternote. They have been intentionally limited to the visible characters of 7-bit ASCII plus whitespace `␣` and newline `↵`:

    ———————————————————————————————————
      ␣ ! " # $ % & ' ( ) * + , - . /
      0 1 2 3 4 5 6 7 8 9 : ; < = > ?
      @ A B C D E F G H I J K L M N O
      P Q R S T U V W X Y Z [ \ ] ^ _
      ` a b c d e f g h i j k l m n o
      p q r s t u v w x y z ( | ) ~ ↵
    ———————————————————————————————————

All __glyphs__ are presented here in `monospace`.

## Phone

A __phone__ is an indivisible articulation of spoken Counternote represented by one or two [glyphs][glyph] and up to three phonemes.

### Start

A __start__ is the first __phone__ or *linguistic onset* of a [word][word]. All of these sounds are found in American English, but the letters `c`, `q`, and `x` have been reassigned to tʃ 'ch', kʷ 'qu', and ʃ 'sh'. Because the American English 'r' is exceptionally weird, a trilled 'r' is also correct. Curiously, most languages have a 'ch' kind of sound, but way fewer have its voiced counterpart 'j', so if you have trouble, just say the 'ch' sound while keeping your vocal cords vibrating. A ʒ 'zh' consonant can be substituted.

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

### Rhyme

A __rhyme__ is the rhyming part or *linguistic coda* of a [word][word].

All __rhymes__ include vowels as part of their __phone__. Vowels are pure spanish vowels plus the schwa `ə` and a rhoticized mid vowel `ɚ`:

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

## Word

A __word__ is connected sequence of [phones][phone] that can be spoken like the [tone][tone] `la` or the [hold][hold] `qa` (`.`).

## Sign

A __sign__ is connected sequence of [glyphs][glyph] do not make a [word][word] like the starting sequence `++*`.

***

# Forms

__Forms__ are structural elements of a composition and how such elements connect together. Here is the A-section of Bourrée by Bach:

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
    #DOV |4.| @allegretto

    A
      0
        f| -           .     le,ze  |
        t| -           .     co,zo  |
      1
        f| ce.   ze,le me.   le,ze  |
        t| lo.   to.   da.   to.    |
      2
        f| de.   se,me le.   ge,je  |
        t| co.   zo.   lo.   zo.    |
      3
        f| de.   ta,ca za.   ca,ta  |
        t| co.   to.   da.   to.    |
      4
        f| de,ta ca,za ha.   le,ze  |
        t| co.   da.   lo,zo co,zo  |
      5
        f| ce.   ze,le me.   le,ze  |
        t| lo.   to.   da.   to.    |
      6
        f| de.   se,me le.   ge,je  |
        t| co.   zo.   lo.   zo.    |
      7
        f| de.   li,ce ze^^c.  ,ce, |
        t| co.   ja.   ga.   ga.    |
      8
        f| hh-           .   %      |
        t| coCeva^-      .   %A %B  |
    *++

## Score

A __score__ is an entire composition in Counternote. It is enclosed in `++*` and `*++` [signs][sign]. When detailed in the [stage][stage], it is the title of a work.

## Stage

A __stage__ holds compositional and instrumental details on entire [scores][score] and individual [tracks][track] such as title, author, instrument voices and tunings, and the like. The [score][score] __stage__ is between the `++*` and `+++` [signs][sign]. The [track][track] __stage__ is between `+++` [signs][sign].

### Scribe

A __scribe__ is a composer of a [score][score] or [track][track].

### Work

A __work__ is the collection of music a [score][score] or [track][track] belongs to.

### Act

An __act__ is the performer of a [score][score] or [track][track].

## Track

A __track__ is an individual piece that may or may not occur simultaneously within a score. The are separated with `+++` [signs][sign].

### Mode

A __mode__ is the home scale for a [track][track] denoted by its representative [chord][chord]:

    —————————————————————————
      WORD    TONALITY
    —————————————————————————
      Lrv     Lydian
      Lev     Major/Ionian
      Levf    Mixolydian
      Lovm    Dorian
      Lov     Minor/Aeolian
      Lhv     Phrygian
      Lor     Locrian
    —————————————————————————

## Round

A __round__ is a block of music, often repeated, marked with an unindented letter or string on its own line for legibility, denoted above with `A`.

## Bar

A __bar__ contains all of the details of what to play when and how to play it marked with a two-space indented numeral on its own line, again for legibility, denoted above with `0`, `1`, `2`, and the like. The main component of a __bar__ is a [voice][voice], but it may also include composer directions and accompaniments and lyrics. `0` indicates a *pick-up bar*, an incomplete bar that leads into the first [beat][beats]. A specific __bar__ can be accessed outside a [round][round] by referencing the [round][round] followed by the __bar__ with a `'` in between, for example `A'1`.

### Voice

A __voice__ is akin to a sequence of music performed by a monophonic instrument such as a human *voice* enclosed in `|`:

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

A __voice__ can be extended to another line using `+` at the end of the next to last lines and at the start of the next lines:

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

Inline harmonies such as [strands][strand] and [chords][chord] are multiple __voices__ even if performed by the same instrument and notated on the same line. Harmonies can alternatively be notated by a [stack][stack]. 

### Stack

A __stack__ is separate [voices][voice] in the same __bar__. These can be separate instruments for an ensemble, or the same instrument like the right and left hands of a piano player or even the six strings of a guitar for a more musically informative tablature. The individual [voices][voice] can be labeled like in the Bourrée:

    ———————————————————————————————————
      1
        f| ce.   ze,le me.   le,ze  |
        t| lo.   to.   da.   to.    |
    ———————————————————————————————————

### Lap

A __lap__ is a variation on a __bar__ to be played in different iterations of a __round__. It is denoted by the __bar__ followed by the __lap__ with a `'` in between, much like a __bar__ is specified from outside a __round__ `8'1`.

### Jump

A __jump__ is a directive on what part to play next. __Jumps__ are denoted by `%` followed by the __bar__ or __round__ to continue from.

### Rep

A __rep__ is a directive to repeat some number of [holds][hold] previous. It is denoted by `%%` to repeat the previous __bar__ or `%%..` to repeat the previous `..`.

## Snip

A __snip__ holds the programmery bits. 

***

# Sounds

A __sound__ is any acoustic vibration fit to be notated. They come in two monophonic varieties: [tones][tone] and [raps][rap]. The first deals with those of definite [pitch][pitch], whereas [raps][rap] deal with those of indefinite or incidental [pitch][pitch].

## Pitch

A __pitch__ is the number of vibrations per second, the frequency.

## Rank

A __rank__ is like all traditional notes regardless of octave, also known as the pitch-class, the set of pitches separated by powers of two. These are written as [tones][tone] in all caps with the __rhyme__[rhyme][rhyme] for the [file][file] such as `LA` for *A* in the octave below *middle C*, usually *A3* or precisely *A220*. 

## File

A __file__ is analogous to the octave number, for instance the [band][band] from 220Hz to 440Hz.

## Band

A __band__ is a defined range of frequencies with the lower bound inclusive and the upper bound exclusive.

## Notch

A __notch__ is a [band][band] a twelth root of two wide, a traditional *semitone* or *half-step*.

# Beats

__Beats__ are basic rhythmic elements

## Hold

A __hold__ is punctuation character that represents a duration. They come in six varieties ordered by powers of two:

    ———————————————————————————
      HOLD  VALUE  WORD   IPA
    ———————————————————————————
      `;`    1/32   qh    kʷə
      `:`    1/16   qi    kʷi
      `,`    1/8    qe    kʷe
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

A __groove__ tells the arrangement of [beats][beats] in a [bar][bar]. It is notated `|4.|` with the number of [holds][hold] summing to the total length of a [bar][bar].

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

 But __grooves__ can go beyond that — they can tell the accent pattern within a [bar][bar]. `|!,,!,,!,!,|` is the 5/4 clave. The accents are denoted with `!` and take the length of the rest of the [holds][hold] in the __groove__.

### Shift

A __shift__ is a section of polymeter with one __groove__ superimposed over another at the same [pulse][pulse] so the first beat shifts around because the lengths of the bars are different. It is notated `|3./2.|` *three over two* with the number of [holds][hold] in the [bar][bar] measured by the first __groove__:

    ———————————————————————————
      # |3./2.|
      1
        # three over two
        | la.   la.   la.   |
    ———————————————————————————

Like with __grooves__, the [shift][shift] can be notated within the [voice][voice]:

    ————————————————————————————————
      # |2.|
      1
        # three over two
        |3./2. la.   la.   la.   |
    ————————————————————————————————

### Rift

A __rift__ is a section of polyrhythm with one __groove__ mashed against another at different [pulses][pulse] so the first beat and total [bar][bar] length stays the same but the __grooves__ go in and out of phase. It is notated `|3.\2.|` *three against two* with the total length of the [bar][bar] measured by the second __groove__:

    ———————————————————————————
      # |3.\2.|
      1
        # three against two
        | la.   la.   la.   |
    ———————————————————————————

Like with __grooves__, the [right][right] can be notated within the [voice][voice]:

    ————————————————————————————————
      # |2.|
      1
        # three against two
        |3.\2. la.   la.   la.   |
    ————————————————————————————————

## Pulse

A __pulse__ gives the tempo. It is denoted by an `@` symbol followed by an exact bpm, a range of bpms, or a tempo descriptor. 

## Click

A __click__ refers to the [hold][hold] that gets counted: In `|4.|`, `.` is one __click__.

## Cut

A __cut__ is a subdivision of a [beat][beats], also known as a tuplet. While there are six well-defined [holds][hold] that do duple meter, many more can be achieved without redefining holds or changing the [pulse][pulse].

### Short Cut

A __short cut__ is a quick and dirty way of defining a __cut__, pun intended. It works with small prime number tuplets: duplets, triplets, and quintuplets. The rules are as follows:

* no whitespace exists between the [sounds][sounds]
* [holds][hold] act as separators of the [sounds][sounds] in the __cut__
* the last [sound][sounds] does *not* receive a [hold][hold]
* the total duration of all the [holds][hold] is the duration the __cut__ fills
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

__Short cuts__ can greatly reduce visual noise. Consider what the Bourrée above looks like using [holds][hold] on every [note][notes]:

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
    #DOV |4.| @allegretto

    A
      0
        f| -               .       le, ze,  |
        t| -               .       co, zo,  |
      1
        f| ce.     ze, le, me.     le, ze,  |
        t| lo.     to.     da.     to.      |
      2
        f| de.     se, me, le.     ge, je,  |
        t| co.     zo.     lo.     zo.      |
      3
        f| de.     ta, ca, za.     ca, ta,  |
        t| co.     to.     da.     to.      |
      4
        f| de, ta, ca, za, ha.     le, ze,  |
        t| co.     da.     lo, zo, co, zo,  |
      5
        f| ce.     ze, le, me.     le, ze,  |
        t| lo.     to.     da.     to.      |
      6
        f| de.     se, me, le.     ge, je,  |
        t| co.     zo.     lo.     zo.      |
      7
        f| de.     li, ce, ze^^c.  ,   ce,  |
        t| co.     ja.     ga.     ga.      |
      8
        f| hh-             .       %        |
        t| coCeva^-        .       %A %B    |

    *++

### Long Cut

A __long cut__ uses square brackets with `'` between [sounds][sounds] and [holds][hold] at the end to slice up the [bar][bar].

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

__Long cuts__ work in two places where __short cuts__ cannot: nested tuplets and across multiple bars.

To nest a __cut__, just place a __Long cuts__ where a single sound would go:

    —————————————————————————————————
      # |4.|
      1
        # triplet in triplet
        |[la'la'[la'la'la]]=      |
        | la-la-[la'la'la]        |
    —————————————————————————————————

If a nested __cut__ takes up more than one element of a tuplet, `+` and the [tie][tie] `aa` are used: 

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

The `+` with the extra [hold][hold] `=` helps the performer see what how long the __cut__ is.

***

# Notes

__Notes__ are [sounds][sounds] for a [hold][hold].

## Tone

A __tone__ capitalized as a [rank][rank] is the closest to a *note* in a traditional sense, like the pitch-class of *C* or a specific C note. Any [pitch][pitch] that when multiplied or divided by powers of two falls in the [notch][notch] starting from 256Hz is described by the [rank][rank] `LA`. That means any [pitch][pitch] that falls in the [notch][notch] from about 430.5Hz to just over 456Hz is `LA` including *A440*, *A444*, and *A432*, but not including the baroque tuning *A415*, which falls into the [rank][rank] `GA` just below.

A lowercase __tone__ is akin to a *scale degree* or *movable-do*, a note relative to the specified [key][key]. If no [key][key] is specified, the default is `LA`. Since music is predominantly a relative pitch phenomenon, only the setting of the [key][key] is done using the absolute pitch of the capitalized __tone__.

### Tone Start

The __tone start__ will always be a consonant represented by a single [glyph][glyph]. Their pitch will always be relative to the current [key][key] written here as a semitone or [notch][notch] offset

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

The __tone rhyme__ is all but the [start][start], also known as the rhyming part (linguistic coda). It represents the [file][file] of the __tone__.

    —————————————————————————————
      RHYME  FILE  IPA  ENGLISH
    —————————————————————————————
       -il    +6    il   'eel'
       -al    +5    al   'ahl'
       -l     +4    ɛl   'ehl'
       -h     +3    ə     'uh'
       -i     +2    i     'ee'
       -e     +1    e     'eh'
    —————————————————————————————
       -a     ±0    ɑ     'ah'
    —————————————————————————————
       -o     -1    o     'oh'
       -u     -2    u     'oo'
       -r     -3    ɚ     'er'
       -ar    -4    ɑ˞    'ar'
       -or    -5    ɔ˞    'or'
    —————————————————————————————

## Rap

A __rap__ is any sound where [pitch][pitch] is indeterminate or incidental. Rather than having some algorithmic way of bulding these, __raps__ are just a simple, user-definable lookup table with the caveat that they cannot conflict with [tones][tone], [spans][span], or the reserved __raps__. These are some of the proposed __raps__:

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

## Sync

[Tones][tone] and [raps][rap] and even [knits][knit] can be performed at the same time by just concatenating them together with a `!` in between so it’s easy to read.

    ———————————————————————————————————————
      WORD            VALUE
    ———————————————————————————————————————
      bm!xd   bass drum + closed hi-hat
      xk!kl       shook + clap
      rk!le        rake + high A
    ———————————————————————————————————————

## Tie

A __tie__ is a [rap][rap] used to show a [sound][sounds] from a previous [bar][bar] is still being held. It is notated with the [word][word] `aa` and not pronounced separately from the [sound][sounds] being held.

## Breath

A __breath__ is a [rap][rap] that gives the player room to breathe. It is notated with the [word][word] `hh` and not explicitly pronounced.

***

# Knits

__Knits__ are collections of notes occuring simultaneously. They come in three varieties: [spans][span], [chords][chord], and [braids][braid].

## Root

The tonic of a [knit][knits].

## Span

A __span__ is an interval. It consists of a single letter capitalized when speaking of an interval such a V, a perfect fifth, but is lowercase when attached to a note. Even though they are written with a single letter, the consonants on their own have a particular vowel quality attached.

    ——————————————————————————————————
      RHYME  INTERVAL  IPA   ENGLISH
    ——————————————————————————————————
        N       7       mə    'nuh'
        F      ♭7       fu    'foo'
        M       6       no    'moh'
        P      ♭6       pɛ    'peh'
        V       5       vi    'vee'
        R     ♯4/♭5     ɚ      'er'
        I       4       i      'ee'
        E       3       ɛ      'eh'
        O      ♭3       o      'oh'
        U       2       u      'oo'
        H      ♭2       ə      'uh'
        A       1       ɑ      'ah'
    ——————————————————————————————————

This quality is dropped when used as [threads][thread] in [knits][knit].

## Knit Start

All __knits__ begin with a capitalized consonant corresponding with a [tone start][tone start]. The capitalization tells the performer and the compiler that this is a polyphonic [note][note].

    —————————————————
      START  OFFSET  
    —————————————————
        W      +6
        T      +5
        Y      +4
        C      +3
        Z      +2
        K      +1
    —————————————————
        L      ±0
    —————————————————
        G      -1
        S      -2
        J      -3
        X      -4
        D      -5
    —————————————————


## Thread

A __thread__ is a single [voice][voice] within a __knit__. They are the [glyphs][glyph] for the [spans][span].

For any three consonants in a row, a schwa `ə` is inserted between the second and third. Because that is the `h` [span’s][span] usual pronounced, `h` becomes a glottal stop `ʔ` when a __thread__. The [blends][blend] that are vowels always get the patalal glide [j] preceding them if they follow a vowel whereas the [moods][mood] and [rubs][rub] always get labiovelar [w]. The [glyph][glyph] `r` as a thread is always its vowel [phone][phone].

## Chord

A __chord__ is a [knit][knits] constructed using the capitalized [tone start][tone start] as the [root][root] and [threads][thread] for all other voices.

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

A __braid__ is a specific voicing of a [chord][chord]. These get much more complicated looking, but they follow the same rules with three added details. First, no octave is specified, so the lowest sounding [tone][tone] is prefixed to the [chord][chord]. Second, no [root][root] is implied so every [voice][voice] gets a [thread][thread]. Third, if an entire octave is skipped, the [glyph][glyph] `b` is inserted.

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

__Cues__ are composer directives, denoted by [glyph][glyph] `#`. In the Bourrée above, a [track][track]-level [cue][cues] is followed by the [key][key] `ma` to specify the key center, the 1-[chord][chord] `Xov` to specify the [mode][mode], the [groove][groove] for four [beats][beats] `|4.|`, and all at an allegretto [pulse][pulse].

## Comp

A __comp__ is a minimally specified accompaniment and harmonic background written within the [bar][bar].

### Vamp

A __vamp__ is a [comp][comp] that specifies rhythm and/or voicings.

## Tweak
 
A __tweak__ is an instruction on effects that occur above the [voices][voice] they modify. They can be placed inline by being enclosed in `#[` and `]#`.

## Art

An __art__ is an inline [cue][cues] each of which are denoted by special [glyphs][glyph] and rules.

### Smooth

__Smooth__ is a directive to perform legato, which is to be determined by each instrument. Such __arts__ are bracketed by parentheses `(` `)`.

### Ring

__Ring__ is a directive to let ring, that is not to stop a [sounds][sounds] when others start. These begin with the [sound][sounds] (without any [hold][hold] if simultaneous, with if there is a delay) followed by curly brackets `{` `}` with the concurrent [sounds][sounds] notated bewteen them. The [hold][hold] for the outside [note][notes] is at least as long as the combined [holds][hold] within the curly brackets. [Bar][bar] 7 from the Bach Bourrée in E Minor can be notated both of the following ways:

    ————————————————————————————————————————————————
      7
        f| lv.   li.lo lu^^o.  ,lo, |
        t| vo.   hl.   hm.   hm.    |   
      7
        | vo{lv.} hl{li.lo} hm{lu^^o.} hm{aa.lo} |
    ————————————————————————————————————————————————


### Sust

__Sust__ is a directive to sustain [sounds][sounds] freely as they are played like when lifting the dampers on a piano. It is denoted by double curly brackets `{{` `}}`.

### Glide

__Glide__ is a directive to smoothly change the [pitch][pitch], like a bend. `/` is for changing a [pitch][pitch] up, `\` for changing a [pitch][pitch] down.

### Slide

__Slide__ is a directive to change the [pitch][pitch] in a stepwise manner, like a fret slide. `//` is for changing a [pitch][pitch] up, `\\` for changing a [pitch][pitch] down.

### Flux

__Flux__ is a directive to fluctuate the [pitch][pitch] around a [tone][tone], known as vibrato. It is denoted by the [glyph][glyph] `~`.

### Flam

__Flam__ is a directive to quickly articulate one [sound][sounds] before another. It is denoted by a [tone start][tone start] followed by the [glyph][glyph] `^` and the [tone][tone] to land on.

### Trill

__Trill__ is a directive to quickly alternate between two [sounds][sounds], often used as ornamentation. It is denoted by the starting [tone][tone] followed by `^^` and then the [tone start][tone start] of the [tone][tone] to be alternated with.

### Star

__Star__ is a directive to accent and/or suddenly end a [sound][sounds] denoted by `*`. It is written directly before the [note][notes] it modifies `*la.` for accents, directly after the the note for staccato `la*.`, or even directly after a [hold][hold] for that abrupt ending `la.*`.

### Trem

__Trem__ is a directive for the rapid articulation of a sustained [sound][sounds]. It is denoted by `**` just before the [sound][sounds] `**la.` it applies to.

### Harm

__Harm__ is a directive to play the nth harmonic. It is denoted by `*` followed by the number for said nth harmonic: `lo*3` is for performing the third harmonic. Rather than notating the pitch as a listener might hear it, Counternote notates the harmonic as it’s played.

## Drift

__Drift__ is a directive for microtonal adjustment. These can be adjusted globally for the likes of just intonation or inline. They are [spans][span] appended to [tones][tone] with a `*`. The default values are as given:

    ————————————
      *r  +50¢
      *i  +42¢
      *e  +33¢
      *o  +25¢
      *u  +17¢
      *h  +8¢
      *a  ±0¢
      *n  -8¢
      *f  -17¢
      *m  -25¢
      *p  -33¢
      *v  -42¢
    ————————————

`la/da*r` is a whole step and a quarter bend to B half-sharp. `la*p` is an A half-sharp.

The __drifts__ are not sticky, but [tones][tones] can be redefined to make them so. In such a case where `la` was set to `la*h`, `la*a` would be the 12tet value unless `*a` itself were redefined to be different.

Like with [weaves][weave], there are rules for consecutive vowels, so [blends][blend] get a [j] to break up the vowels while [moods][mood] and [rubs][rub] get a [w].

## Chant

A __Chant__ is a set of lyrics to be sung set below the [voice][voice] with its corresponding melody. It is enclosed in double straight quotes `"` with each syllable getting at least one [sound][sounds] and underscores `_` for multiple [sounds][sounds]. Speech is denoted by the [rap][rap] `sw` in the [voice][voice].

***
<!-- 
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

*** -->
