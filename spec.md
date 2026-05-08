***

#### Counternote Specification version 0.10.2

This is a terse description of Counternote with definitions and examples.

***

# Gloss

This __gloss__ serves as a glossary and table of contents for all things Counternote.

### BITS [⤵︎][bits]

Foundational elements

* [__term__][term]: a precise concept in music and Counternote, linked here in the __gloss__
* [__glyph__][glyph]: any typed character
* [__phone__][phone]: the pronunciation of a speakable [glyph][glyph] or cluster of [glyphs][glyph]
  * [__start__][start]: the first [phone][phone] or *linguistic onset* of a [word][word]
  * [__rhyme__][rhyme]: the rhyming part or *linguistic coda* of a [word][word]
* [__word__][word]: a connected sequence of [phones][phone]
* [__sign__][sign]: a connected sequence of [glyphs][glyph] that do not make a [word][word]

### BLOCKS [⤵︎][blocks]

Structural elements

* [__score__][score]: an entire composition
* [__stage__][stage]: a place for compositional and instrumental details
  * [__scribe__][scribe]: a composer of the [score][score] or [track][track]
  * [__work__][work]: the collection a [score][score] or [track][track] belongs to
  * [__act__][act]: the performer of the [score][score] or [track][track]
* [__track__][track]: an individual piece within a [score][score]
  * [__key__][key]: the tonic of a [track][track]
  * [__mode__][mode]: the mode of a [track][track]
  * [__form__][form]: the song form of a [track][track]
* [__round__][round]: a block of music
* [__bar__][bar]: details on how and what to play
  * [__voice__][voice]: a monophonic instrument and the sequence of [sounds][sounds] to be played
  * [__stack__][stack]: multiple [voices][voice] in the same [bar][bar]
  * [__lap__][lap]: a variation on a [bar][bar]
  * [__jump__][jump]: a directive on what to play next
  * [__rep__][rep]: a directive to repeat a [bar][bar] or [round][round]
* [__def__][def]: definitions
* [__script__][script]: a block or snippet of code
* [__doc__][doc]: documentation for human consumption
* [__tweak__][tweak]: instruction on effects

### SOUNDS [⤵︎][sounds]

Any acoustic vibration

* [__pitch__][pitch]: the number of vibrations per second, the frequency
* [__rank__][rank]: the set of [pitches][pitch] separated by powers of two, the pitch-class
* [__file__][file]: the octave range that contains a [pitch][pitch]
* [__band__][band]: any range of [pitches][pitch]
* [__notch__][notch]: the range of a single *semitone* or *half-step*

### BEATS [⤵︎][beats]

Rhythmic elements

* [__click__][click]: the duration of a [note][notes]
* [__groove__][groove]: the arrangement of [beats][beats] in a [bar][bar]
  * [__shift__][shift]: a section of polymeter
  * [__rift__][rift]: a section of polyrhythm
* [__pulse__][pulse]: the tempo
* [__tap__][tap]: the beat that feels the pulse
* [__cut__][cut]: a tuplet
  * [__short cut__][short cut]: a quick [cut][cut] notation
  * [__long cut__][long cut]: a robust [cut][cut] notation

### NOTES [⤵︎][notes]

Acoustic vibrations held in time

* [__tone__][tone]: a [sound][sounds] where [pitch][pitch] is the defining factor
  * [__tone start__][tone start]: the [start][start] that denotes the [rank][rank]
  * [__tone rhyme__][tone rhyme]: the [rhyme][rhyme] that denotes the [file][file]
  * [__drift__][drift]: a microtonal adjustment
* [__span__][span]: a [word][word] indicating the interval
* [__rap__][rap]: a [sound][sounds] where [pitch][pitch] is indeterminate or incidental
* [__breath__][breath]: a breath of fresh quiet

### KNITS [⤵︎][knits]

Manifold acoustic vibrations

* [__root__][root]: the [tone start][tone start] that denotes the tonic for a [knit][knits]
* [__thread__][thread]: a single [voice][voice] within a [knit][knits]
* [__strand__][strand]: a [knit][knits] of two voices, a double stop
* [__chord__][chord]: a [knit][knits] of three voices or more
* [__braid__][braid]: a [chord][chord] of a particular voicing

### CUES [⤵︎][cues]

Composer directives

* [__tie__][tie]: a [sound][sounds] held out from a previous [bar][bar]
* [__comp__][comp]: an accompaniment
  * [__vamp__][vamp]: a [comp][comp] with rhythm and/or voicings
* [__tweak__][tweak]: an instruction on effects
* [__art__][art]: an inline cue
  * [__smooth__][smooth]: a legato line
  * [__ring__][ring]: a freely ringing line
  * [__hold__][hold]: a sustained line
  * [__glide__][glide]: a smooth change in [pitch][pitch] of a [sound][sounds]
  * [__slide__][slide]: a stepped change in [pitch][pitch] of a [sound][sounds]
  * [__flux__][flux]: a repeated fluctuation in [pitch][pitch] of a [sound][sounds]
  * [__flam__][flam]: a quick [sound][sounds] before another
  * [__trill__][trill]: a quick alternating between [sounds][sounds]
  * [__trem__][trem]: a rapid articulation of a [sound][sounds]
  * [__roll__][roll]: an arpeggiation of a [knit][knits]
  * [__strum__][strum]: a strum of a [knit][knits]
  * [__strong__][strong]: an accent or sudden ending of a [sound][sounds]
  * [__harm__][harm]: the nth harmonic
* [__chant__][chant]: lyrics beneath the [voices][voice]

### SCHEMES [⤵︎][schemes]

Toward a deeper understanding

* [__clock__][clock]: a [scheme][schemes] for visualizing the relationships between [tones][tone]/[spans][span]
  * [__hue clock__][hue clock]: [tones][tone]/[spans][span] arranged in chromatic order
  * [__lux clock__][lux clock]: [tones][tone]/[spans][span] arranged in harmonic order
  * [__lux__][lux]: a measure of the relative brightness or darkness of an interval
  * [__bright lux__][bright lux]: a harmonic relationship evoking a sense of opening up
  * [__dark lux__][dark lux]: a harmonic relationship evoking a sense of settling down
  * [__vibe__][vibe]: a measure of emotional quality of an interval
  * [__blend__][blend]: a consonant [vibe][vibe]
  * [__mood__][mood]: a major/minor [vibe][vibe]
  * [__rub__][rub]: a dissonant [vibe][vibe]
* [__yap__][yap]: a system for vocalizing rhythms and [grooves][groove] as [words][word]

[gloss]: #gloss

[bits]: #bits

[term]: #term
[glyph]: #glyph
[phone]: #phone
  [start]: #start
  [rhyme]: #rhyme
[word]: #word
[sign]: #sign

[blocks]: #blocks

[score]: #score
[stage]: #stage
  [scribe]: #scribe
  [work]: #work
  [act]: #act
[track]: #track
  [key]: #key
  [mode]: #mode
  [form]: #form
[round]: #round
[bar]: #bar
  [voice]: #voice
  [stack]: #stack
  [lap]: #lap
  [jump]: #jump
  [rep]: #rep
[def]: #def
[script]: #script
[doc]: #doc
[tweak]: #tweak

[sounds]: #sounds

[pitch]: #pitch
[rank]: #rank
[file]: #file
[band]: #band
[notch]: #notch

[beats]: #beats

[click]: #click
[groove]: #groove
  [shift]: #shift
  [rift]: #rift
[pulse]: #pulse
[tap]: #tap
[cut]: #cut
  [short cut]: #short-cut
  [long cut]: #long-cut

[notes]: #notes

[tone]: #tone
  [tone start]: #tone-start
  [tone rhyme]: #tone-rhyme
  [drift]: #drift
[span]: #span
[rap]: #rap
[breath]: #breath

[knits]: #knits
[root]: #root
[thread]: #thread
[strand]: #strand
[chord]: #chord
[braid]: #braid

[cues]: #cues

[tie]: #tie
[comp]: #comp
  [vamp]: #vamp
[art]: #art
  [smooth]: #smooth
  [ring]: #ring
  [hold]: #hold
  [glide]: #glide
  [slide]: #slide
  [flux]: #flux
  [flam]: #flam
  [trill]: #trill
  [trem]: #trem
  [roll]: #roll
  [strum]: #strum
  [strong]: #strong
  [harm]: #harm
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
[yap]: #yap

***

# Bits

__Bits__ are foundational elements for learning and understanding Counternote.

## Term

A __term__ is the name for a precise concept in music and Counternote. They are monosyllabic to be easy to remember and speak about. Each __term__ has an entry in this [gloss][gloss].

## Glyph

A __glyph__ is any typed character in Counternote. They have been intentionally limited to the visible characters of 7-bit ASCII plus whitespace `␣` and newline `↵`:

    ———————————————————————————————————
      ␣ ! " # $ % & ' ( ) * + , - . /
      0 1 2 3 4 5 6 7 8 9 : ; < = > ?
      @ A B C D E F G H I J K L M N O
      P Q R S T U V W X Y Z [ \ ] ^ _
      ` a b c d e f g h i j k l m n o
      p q r s t u v w x y z { | } ~ ↵
    ———————————————————————————————————

All __glyphs__ are presented here in `monospace`.

## Phone

A __phone__ is an indivisible articulation of spoken Counternote represented by one or two [glyphs][glyph] and up to three phonemes.

### Start

A __start__ is the first __phone__ or *linguistic onset* of a [word][word]. All of these sounds are found in American English, but the letters `c`, `x`, and `q` have been reassigned to `tʃ` 'ch', `ʃ` 'sh', and rhoticized open vowel `ʔ` like '-' in 'uh-oh'.

The standard starting consonants with their points of articulation going from “high” to “low” (to the “neutral” glottal consonants) are as follows:

    ——————————————————————————————————
       GLYPH   IPA    PRONUNCIATION
      ~~~~~~ BILABIAL ~~~~~~~~~~~~~~
        P,p     p     'p' in 'pick'
        B,b     b     'b' in 'bow'
        M,m     m     'm' in 'muse'
      ~~~~~ LABIODENTAL ~~~~~~~~~~~~
        F,f     f     'f' in 'fun'
        V,v     v     'v' in 'vibe'
      ~~~~~~ ALVEOLAR ~~~~~~~~~~~~~~
        L,l     l     'l' in 'lick'
        T,t     t     't' in 'tom'
        D,d     d     'd' in 'din'
        N,n     n     'n' in 'neck'
        S,s     s     's' in 'sine'
        Z,z     z     'z' in 'zip'
      ~~~~ POSTALVEOLAR ~~~~~~~~~~~~
        C,c     tʃ   'ch' in 'chip'
        J,j     dʒ    'j' in 'jam'
      ~~~~~~ PALATAL ~~~~~~~~~~~~~~~
        X,x     ʃ    'sh' in 'ship'
        Y,y     j     'y' in 'yes'
      ~~~~~~~ VELAR ~~~~~~~~~~~~~~~~
        K,k     k     'k' in 'kick'
        G,g     g     'g' in 'good'
      ~~~~ LABIOVELAR ~~~~~~~~~~~~~~
        W,w     w     'w' in 'wit'
      ~~~~~~ GLOTTAL ~~~~~~~~~~~~~~~
        H,h     h     'h' in 'hit'
        Q,q     ʔ     '-' in 'uh-oh'
    ——————————————————————————————————

### Rhyme

A __rhyme__ is the rhyming part or *linguistic coda* of a [word][word].

All __rhymes__ include vowels as part of their __phone__. Vowels are pure spanish vowels plus the rhoticized open vowel `ɑ˞` as `q`, a rhoticized mid vowel `ɚ` as `r`, a lateralized mid front vowel `ɛl` as `l`, and a lateralized high vowel `iʎ` as `y`:

    ————————————————————————————————
      GLYPH    IPA   PRONUNCIATION
        z      ʔɚz      'erz'
        n      ʔun      'oon'
        m      ʔom      'ohm'
        v      ʔiv      'eev'
        y      ʔiʎ      'eel'
        l      ʔɛl      'ehl'
        i      ʔi       'ee'
        e      ʔe       'eh'
        a      ʔɑ       'ah'
        o      ʔo       'oh'
        u      ʔu       'oo'
        r      ʔɚ       'er'
        q      ʔɑ˞      'ar'
    ————————————————————————————————

## Word

A __word__ is connected sequence of [phones][phone] that can be spoken like the [tone][tone] `ma` or the [click][click] `pa` (`.`).

## Sign

A __sign__ is connected sequence of [glyphs][glyph] do not make a [word][word].

    ———————————————————————————————
      SIGN    MEANING
    ———————————————————————————————
       ++*    start score
       *++    end score
       +++    start/end stage
       ***    start/end track
       $$$    start/end script
       ###    start/end doc
    ———————————————————————————————

***

# Blocks

__Blocks__ are structural elements of a composition and how such elements connect together. Here is the A-section of Bourrée by Bach:

    ++*
    SCORE: Lute Suite in E Minor
    WORK: BWV 996
    SCRIBE: Bach
    +++
    TRACK: Bourrée
    VOICES:
      f: fingers
      t: thumb
    FORM: AABB
    ***
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

## Score

A __score__ is an entire composition in Counternote. It is enclosed between `++*` and `*++`.

## Stage

A __stage__ contains compositional and instrumental details on entire [scores][score] and individual [tracks][track] such as title, author, instrument voices and tunings, and the like. The __stage__ for a [score][score] comes after `++*` and the optional __stage__ for the [track][track] comes after `+++`.

### Scribe

A __scribe__ is a composer of a [score][score] or [track][track].

### Work

A __work__ is the collection of music a [score][score] or [track][track] belongs to.

### Act

An __act__ is the performer of a [score][score] or [track][track].

## Track

A __track__ is an individual piece that may or may not occur simultaneously within a score. It begins after `***`.

### Key

A __key__ is the tonic of a track. It is denoted by `@` followed by the capitalized [tone][tone] which defaults to `MA`.

### Mode

A __mode__ is the home scale for a [track][track] denoted by `@` followed by the abstract [root][root] `X` and by its representative [chord][chord] quality in all caps:

    —————————————————————————
      WORD    TONALITY
    —————————————————————————
      XQV     Lydian
      XEV     Major/Ionian
      XEVN    Mixolydian
      XOVM    Dorian
      XOV     Minor/Aeolian
      XRV     Phrygian
      XOQ     Locrian
    —————————————————————————

For transposing instruments like saxophones or a baritone guitar, the __mode__ is set using a capitalized [tone start][tone start] relative to the instrument’s key instead of `X`:

    —————————————————————————
      WORD    TONALITY
    —————————————————————————
      LQV     Lydian
      LEV     Major/Ionian
      LEVN    Mixolydian
      LOVM    Dorian
      LOV     Minor/Aeolian
      LRV     Phrygian
      LOQ     Locrian
    —————————————————————————

### Form

A __form__ is an arrangement of [rounds][round] that make up a [track][track] like AABA.

## Round

A __round__ is a block of music, often repeated, marked with an unindented letter or string on its own line for legibility, denoted above with `A`.

## Bar

A __bar__ contains all of the details of what to play when and how to play it marked with a two-space indented numeral on its own line, again for legibility, denoted above with `0`, `1`, `2`, and the like. The main component of a __bar__ is a [voice][voice], but it may also include composer directions and accompaniments and lyrics. `0` indicates a *pick-up bar*, an incomplete bar that leads into the first [beat][beats]. A specific __bar__ can be accessed outside a [round][round] by referencing the [round][round] followed by the __bar__ with a `'` in between, for example `A'1`.

### Voice

A __voice__ is akin to a sequence of music performed by a monophonic instrument such as a human *voice* enclosed in `|`:

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

A __voice__ can be extended to another line using `+` at the end of the next to last lines and at the start of the next lines:

    —————————————————————————————————————————
      @ |4.|
      5
        | ma: ma: ma: ma: ma: ma: ma: ma: +
        + ma: ma: ma: ma: ma: ma: ma: ma: |
      6
        | ma; ma; ma; ma; ma; ma; ma; ma; +
        + ma; ma; ma; ma; ma; ma; ma; ma; +
        + ma; ma; ma; ma; ma; ma; ma; ma; +
        + ma; ma; ma; ma; ma; ma; ma; ma; |
    —————————————————————————————————————————

Inline harmonies, [strands][strand] and [braids][braid], are multiple __voices__ even if performed by the same instrument and notated on the same line. Harmonies can alternatively be notated by a [stack][stack]. 

### Stack

A __stack__ is separate [voices][voice] in the same __bar__. These can be separate instruments for an ensemble, or the same instrument like the right and left hands of a piano player or even the six strings of a guitar for a more musically informative tablature. The individual [voices][voice] can be labeled like in the Bourrée:

    ——————————————————————————————————
      1
        f| ce.   ze.be me.   be.ze |
        t| ma.   do.   la.   do.   |
    ——————————————————————————————————

### Lap

A __lap__ is a variation on a __bar__ to be played in different iterations of a __round__. It is denoted by the __bar__ followed by the __lap__ with a `'` in between, much like a __bar__ is specified from outside a __round__ `8'1`.

### Jump

A __jump__ is a directive on what part to play next. __Jumps__ are denoted by `%` followed by the __bar__ or __round__ to continue from.

### Rep

A __rep__ is a directive to repeat some number of [clicks][click] or [bars][bar]. It is denoted by `%%` to repeat the previous __bar__, `%%2` to repeat the previous two [bars][bar], or `%%...` to repeat the previous duration of three `po` [clicks][click].

## Def
 
A __def__ is instruction on definitions for parts of a track. It is denoted with `@` at the beginning of a line, `@@` to the end of a line, and `@@@` for multiline definitions.

## Script

A __script__ contains the programmery bits. It is denoted with `$` at the beginning of a line, `$$` to the end of a line, and `$$$` for multiline code.

## Doc

A __doc__ contains details not meant for the machine. It is denoted with `#` at the beginning of a line, `##` to the end of a line, and `###` for multiline comments.

## Tweak
 
A __tweak__ is an instruction on effects that occur. It is denoted with `&` at the beginning of a line, `&&` to the end of a line, and `&&&` for multiline instructions.

***

# Sounds

A __sound__ is any acoustic vibration fit to be notated. They come in three varieties: [tones][tone], [spans][span], and [raps][rap]. The first two deal with those of definite [pitch][pitch], whereas [raps][rap] deal with those of indefinite or incidental [pitch][pitch].

## Pitch

A __pitch__ is the number of vibrations per second, the frequency.

## Rank

A __rank__ is like all traditional notes regardless of octave, also known as the pitch-class, the set of pitches separated by powers of two. These are written as [tones][tone] in all caps with the __rhyme__[rhyme][rhyme] for the [file][file] such as `MA` for *middle C*. 

## File

A __file__ is analogous to the octave number, for instance the [band][band] from 220Hz to 440Hz.

## Band

A __band__ is a defined range of frequencies with the lower bound inclusive and the upper bound exclusive.

## Notch

A __notch__ is a [band][band] a twelth root of two wide, a traditional *semitone* or *half-step*.

***

# Beats

__Beats__ are basic rhythmic elements

## Click

A __click__ is punctuation character that represents a duration. They come in six varieties ordered by powers of two with a suggested bpm:

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

## Groove

A __groove__ tells the arrangement of [beats][beats] in a [bar][bar]. It is notated `|4.|` with the number of [clicks][click] summing to the total length of a [bar][bar].

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
      5
        | ma: ma: ma: ma: ma: ma: ma: ma: +
        + ma: ma: ma: ma: ma: ma: ma: ma: |
      6
        | ma; ma; ma; ma; ma; ma; ma; ma; +
        + ma; ma; ma; ma; ma; ma; ma; ma; +
        + ma; ma; ma; ma; ma; ma; ma; ma; +
        + ma; ma; ma; ma; ma; ma; ma; ma; |
    —————————————————————————————————————————

 But __grooves__ can go beyond that — they can tell the accent pattern within a [bar][bar]. `|!,,!,,!,!,|` is the 5/4 clave. The accents are denoted with `!` and take the length of the rest of the [clicks][click] in the __groove__.

 __Grooves__ can also be set immediately after the `|` of a voice:

    ——————————————————————————
      1   
        |4. ma. ma. ma. ma. |
    ——————————————————————————

### Shift

A __shift__ is a section of polymeter with one __groove__ superimposed over another at the same [pulse][pulse] so the first beat shifts around because the lengths of the bars are different. It is notated `|3./2.|` *three over two* with the number of [clicks][click] in the [bar][bar] measured by the first __groove__:

    ———————————————————————————
      @ |3./2.|
      1
        # three over two
        | ma.   ma.   ma.   |
    ———————————————————————————

Like with __grooves__, the [shift][shift] can be notated within the [voice][voice]:

    ————————————————————————————————
      @ |2.|
      1
        # three over two
        |3./2. ma.   ma.   ma.   |
    ————————————————————————————————

### Rift

A __rift__ is a section of polyrhythm with one __groove__ mashed against another at different [pulses][pulse] so the first beat and total [bar][bar] length stays the same but the __grooves__ go in and out of phase. It is notated `|3.\2.|` *three against two* with the total length of the [bar][bar] measured by the second __groove__:

    ———————————————————————————
      @ |3.\2.|
      1
        # three against two
        | ma.   ma.   ma.   |
    ———————————————————————————

Like with __grooves__, the [rift][rift] can be notated within the [voice][voice]:

    ————————————————————————————————
      @ |2.|
      1
        # three against two
        |3.\2. ma.   ma.   ma.   |
    ————————————————————————————————

## Pulse

A __pulse__ gives the tempo. It is denoted by an `@` symbol followed by an exact bpm, a range of bpms, or a tempo descriptor. 

## Tap

A __tap__ refers to the [click][click] that gets counted: In `|4.|`, `.` is one __tap__.

## Cut

A __cut__ is a subdivision of a [beat][beats], also known as a tuplet. While there are six well-defined [clicks][click] that do duple meter, many more can be achieved using __cuts__.

### Short Cut

A __short cut__ is a quick and dirty way of defining a __cut__, pun intended. It works with small prime number tuplets: duplets, triplets, and quintuplets. The rules are as follows:

* no whitespace exists between the [sounds][sounds]
* [clicks][click] act as separators of the [sounds][sounds] in the __cut__
* the last [sound][sounds] does *not* receive a [click][click]
* the total duration of all the [clicks][click] is the duration the __cut__ fills
* a `'` can be used as a separator that does not add duration
* quadruplets and sextuplets should be written as two duplets/triplets connected by a `'`
* the unison `aa` may be used to signal that one or more [sounds][sounds] are held

Those rules add up to:

    —————————————————————————————————————————
      @ |4.|
      1
        # one beat for =
        | ma=                             |
        # is equivalent to
        | ma=__                           |
      2
        # two beats over =
        | ma-             ma-             |
        # is equivalent to
        | ma=ma                           |
      3
        # three beats over --
        | ma-ma-ma                        |
      4
        # four beats over --
        | ma-ma           ma-ma           |
        # is equivalent to
        | ma-ma'ma-ma                     |
        # is equivalent to
        | ma.     ma.     ma.     ma.     |
      5
        # five beats over ....
        | ma.ma.ma.ma.ma                  |
      6
        # six beats over ....
        | ma.ma.ma'ma.ma.ma               |
        # is equivalent to
        | ma.ma.ma        ma.ma.ma        |
      7
        # seven beats over ....
        | ma.ma.ma'ma.ma'ma.ma            |
      8
        # eight beats over ....
        | ma.ma   ma.ma   ma.ma   ma.ma   |
        # is equivalent to
        | ma.ma'ma.ma     ma.ma'ma.ma     |
        # is equivalent to
        | ma.ma'ma.ma'ma.ma'ma.ma         |
        # is equivalent to
        | ma, ma, ma, ma, ma, ma, ma, ma, |
    —————————————————————————————————————————

__Short cuts__ can greatly reduce visual noise. Consider what the Bourrée above looks like using [clicks][click] on every [note][notes]:

    ++*
    SCORE: Lute Suite in E Minor
    WORK: BWV 996
    SCRIBE: Bach
    +++
    TRACK: Bourrée
    VOICES:
      f: fingers
      t: thumb
    FORM: AABB
    ***
    @ JA XOV |4.| allegretto

    A
      0
        f| -               .       me, de,|
        t| -               .       so, do,|
      1
        f| se.     de, me, ge.     me. de |
        t| mo.     lo.     na.     lo.    |
      2
        f| ne.     ze, ge, me.     te, ce,|
        t| so.     do.     mo.     do.    |
      3
        f| ne.     la, sa, da.     sa, la,|
        t| so.     lo.     na.     lo.    |
      4
        f| ne. la  sa, da, ma.     me, de,|
        t| so.     na.     mo, do, so, do,|
      5
        f| se.     de, me, ge.     me, de,|
        t| mo.     lo.     na.     lo.    |
      6
        f| ne.     ze, ge, me.     te, ce,|
        t| so.     do.     mo.     do.    |
      7
        f| ne.     le, se, de^^s.  ,   se,|
        t| so.     ca.     ta.     ta.    |
      8
        f| hh-             .       %A %B  |
        t| &soSeva-        .       %A %B  |

    *++

### Long Cut

A __long cut__ uses square brackets with `'` between [sounds][sounds] and [clicks][click] at the end to slice up the [bar][bar].

    —————————————————————————————————
      @ |4.|
      1
        # one beat for =
        | ma=                     |
        # is equivalent to
        |[ma'__]=                 |
      2
        # two beats over =
        | ma-ma                   |
        # is equivalent to
        |[ma'ma]=                 |
      3
        # three beats over =
        | ma-ma-ma                |
        # is equivalent to
        |[ma'ma'ma]=              |
      4
        # four beats over =
        | ma-ma       ma-ma       |
        # is equivalent to
        | ma-ma'ma-ma             |
        # and equivalent to
        |[ma'ma]-    [ma'ma]-     |
        # and equivalent to
        |[ma'ma'ma'ma]=           |
    —————————————————————————————————

__Long cuts__ work in two places where __short cuts__ cannot: nested tuplets and across multiple bars.

To nest a __cut__, just place a __Long cuts__ where a single sound would go:

    —————————————————————————————————
      @ |4.|
      1
        # triplet in triplet
        |[ma'ma'[ma'ma'ma]]=      |
        | ma-ma-[ma'ma'ma]        |
    —————————————————————————————————

If a nested __cut__ takes up more than one element of a tuplet, the [tie][tie] `__` is used: 

    —————————————————————————————————
      @ |4.|
      1
        # triplet in triplet
        |[ma'[ma'ma'ma]'__]=      |
        | ma-[ma'ma'ma]-__        |
    —————————————————————————————————

Because tuplets are treated as a block of one duration split evenly, the total duration must be present at the end even if it goes on longer than the [bar][bar] where it’s written. The `++` adds the duration beyond the current [bar][bar] and the unison `aa` takes the duration on the next one:

    —————————————————————————————————
      @ |4.|
      1
        # triplet over...
        |[ma'ma'ma]++=            |
      2
        # ...2 bars
        | aa=                     |
    —————————————————————————————————

The extra [click][click] `=` helps the performer see what how long the __cut__ is.

***

# Notes

__Notes__ are [sounds][sounds] for a [click][click].

## Tone

A __tone__ capitalized as a [rank][rank] is the closest to a *note* in a traditional sense, like the pitch-class of *C* or a specific C note. Any [pitch][pitch] that when multiplied or divided by powers of two falls in the [notch][notch] starting from 256Hz is described by the [rank][rank] `MA`. That means any [pitch][pitch] that falls in the [notch][notch] from about 430.5Hz to just over 456Hz is `ZA` including *A440*, *A444*, and *A432*, but not including the baroque tuning *A415*, which falls into the [rank][rank] `CA` just below.

    ——————————————————————————————————————————————————
      UPPERCASE for setting the KEY
    ——————————————————————————————————————————————————
      C   C♯  D   D♯  E   F   F♯  G   G♯  A   A♯  B
      MA  KA  DA  SA  JA  LA  HA  NA  CA  ZA  TA  GA  
    ——————————————————————————————————————————————————

A lowercase __tone__ is akin to a *scale degree* or *movable-do*, a note relative to the specified [key][key]. If no [key][key] is specified, the default is `MA`. Since music is predominantly a relative pitch phenomenon, only the setting of the [key][key] is done using the absolute pitch of the capitalized __tone__.

    ——————————————————————————————————————————————————
      LOWERCASE for playing notes
    ——————————————————————————————————————————————————
       1  ♭2   2  ♭3   3   4  ♭5   5  ♭6   6  ♭7   7
      ma  ka  da  sa  ja  la  ha  na  ca  za  ta  ga  
    ——————————————————————————————————————————————————

There are reasons to the sequence being in that specific order, but it is difficult to quickly memorize twelve abstract words, so to solidify the order in your head, picture a microphone, two pills, the slammer, a chicken, a block of parmesan, and clothing label and say 'mike', 'dose', 'jail', 'hen', 'cheese', 'tag', then:

    ————————————————————————————————————————————
      ma-ka  da-sa  ja-la  ha-na  ca-za  ta-ga
    ————————————————————————————————————————————

### Tone Start

The __tone start__ will always be a consonant represented by a single [glyph][glyph]. Their pitch will always be relative to the current [key][key] written here with a [notch][notch] offset.

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

### Tone Rhyme

The __tone rhyme__ is the second letter, also known as the linguistic coda or rhyming part. It represents the [file][file] of the __tone__.

    —————————————————————————————
      RHYME  FILE  IPA  ENGLISH
    —————————————————————————————
       -y     +4   ʔiʎ   'eel'
       -l     +3   ʔɛl   'ehl'
       -i     +2   ʔi     'ee'
       -e     +1   ʔe     'eh'
    —————————————————————————————
       -a     ±0   ʔɑ     'ah'
    —————————————————————————————
       -o     -1   ʔo     'oh'
       -u     -2   ʔu     'oo'
       -r     -3   ʔɚ     'er'
       -q     -4   ʔɑ˞    'ar'
    —————————————————————————————

The [file][file] and thus __tone rhyme__ always change lower below `n-` and higher above `h-`.

### Drift

A __drift__ is a microtonal adjustment. These can be adjusted inline or globally for the likes of just intonation. They are lowercase [spans][span] appended to [tones][tone]. The default values are as given:

    ————————————
      -q  +50¢
      -i  +42¢
      -e  +33¢
      -o  +25¢
      -u  +17¢
      -r  +8¢
      -a  ±0¢
      -z  -8¢
      -n  -17¢
      -m  -25¢
      -l  -33¢
      -v  -42¢
    ————————————

`ma/daq` is a whole step and a quarter bend to D half-sharp. `maq` is an C half-sharp.

The __drifts__ are not sticky, but [tones][tone] can be redefined to make them so. In such a case where `ma` was set to `mah`, `maa` would be the 12tet value unless `-a` itself were redefined to be different. To redefine a __drift__, simply set `-a` to the number of cents to offset, positive or negative: `$ -a = +2`

Pronunciation follows that of the [knits][knits].

## Span

A __span__ is an interval. It consists of a single letter capitalized when speaking of an interval such a V, a perfect fifth. Even though they are written with a single letter, the consonants on their own have a particular vowel quality attached.

    ——————————————————————————————————
      SPAN   INTERVAL  IPA   ENGLISH
    ——————————————————————————————————
        X       8      ʔaʃ    'ahsh'
        Z       7      ʔɚz    'erz'
        N      ♭7      ʔun    'oon'
        M       6      ʔom    'ohm'
        L      ♭6      ʔɛl    'ehl'
        V       5      ʔiv    'eev'
        Q     ♯4/♭5    ʔɑ˞    'ar'
        I       4      ʔi     'ee'
        E       3      ʔɛ     'eh'
        O      ♭3      ʔo     'oh'
        U       2      ʔu     'oo'
        R      ♭2      ʔɚ     'er'
        A       1      ʔa     'ah'
    ——————————————————————————————————

Sometimes the direction of movement by an interval is need to be talked about, in which case `Y` or `F` can be prefixed to the uppercase __span__ for ascending movement, and `W` or `B` for descending movement.

    ———————————————————————————————————
      SPAN   INTERVAL   IPA   ENGLISH
    ———————————————————————————————————
       FA      15↑      fa     'fah'
       FZ      14↑      fɚz    'ferz'
       FN     ♭14↑      fun    'foon'
       FM      13↑      fom    'fohm'
       FL     ♭13↑      fɛl    'felh'
       FV      12↑      fiv    'feev'
       FQ   ♯11/♭12↑    fɑ˞    'far'
       FI      11↑      fi     'fee'
       FE      10↑      fɛ     'feh'
       FO     ♭10↑      fo     'foh'
       FU       9↑      fu     'foo'
       FR      ♭9↑      fɚ     'fer'
       YA       8↑      ja     'yah'
       YZ       7↑      jɚz    'yerz'
       YN      ♭7↑      jun    'yoon'
       YM       6↑      jom    'yohm'
       YL      ♭6↑      jɛl    'yelh'
       YV       5↑      jiv    'yeev'
       YQ     ♯4/♭5↑    jɑ˞    'yar'
       YI       4↑      ji     'yee'
       YE       3↑      jɛ     'yeh'
       YO      ♭3↑      jo     'yoh'
       YU       2↑      ju     'yoo'
       YR      ♭2↑      jɚ     'yer'
       AA       1       ʔa     'ʔah'
       WZ      ♭2↓      wɚz    'werz'
       WN       2↓      wun    'woon'
       WM      ♭3↓      wom    'wohm'
       WL       3↓      wɛl    'wehl'
       WV       4↓      wiv    'weev'
       WQ     ♯4/♭5↓    wɑ˞    'war'
       WI       5↓      wi     'wee'
       WE      ♭6↓      wɛ     'weh'
       WO       6↓      wo     'woh'
       WU      ♭7↓      wu     'woo'
       WR       7↓      wɚ     'wer'
       WA       8↓      wa     'wah'
       BZ      ♭9↓      bɚz    'berz'
       BN       9↓      bun    'boon'
       BM     ♭10↓      bom    'bohm'
       BL      10↓      bɛl    'behl'
       BV      11↓      biv    'beev'
       BQ   ♯11/♭12↓    bɑ˞    'bar'
       BI      12↓      bi     'bee'
       BE     ♭13↓      bɛ     'beh'
       BO      13↓      bo     'boh'
       BU     ♭14↓      bu     'boo'
       BR      14↓      bɚ     'ber'
       BA      15↓      ba     'bah'
    ——————————————————————————————————

__Spans__ of both varieties are used in [ties][tie], [strands][strand], and [knits][knits] as [threads][thread] when lowercas.e

## Rap

A __rap__ is any [sound][sound] where [pitch][pitch] is indeterminate or incidental. Rather than having some algorithmic way of bulding these, __raps__ are just a simple, user-definable lookup table with the caveat that they cannot conflict with [tones][tone], [spans][span], or the reserved __raps__. This is the current list of proposed __raps__:

    ———————————————————————————————
      RESERVED
    ———————————————————————————————
      `hh` breath (rest)
      `sw` spoken word
      `rp` rap
    ———————————————————————————————
      USER-DEFINABLE
    ———————————————————————————————
      NOISE
      `hx` hush
      `nh` inhale
      `xh` exhale
      `ss` blue noise
      `xs` white noise
      `xx` pink noise
    ———————————————————————————————
      DRUM KIT
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
      `px` crash
      `xp` crash mute
      `ps` ride
      `sp` ride mute
    ———————————————————————————————
      PERCUSSION
      `pm` timpani 32
      `pn` timpani 29
      `pb` timpani 26
      `pd` timpani 23
      `pp` timpani 20
      `qm` conga bass
      `qn` conga open tone
      `qp` conga mute
      `qh` conga open slap
      `qg` conga closed slap
      `qd` conga tap
      `kn` low bongo tone
      `kp` low bongo mute
      `kh` low bongo open slap
      `kg` low bongo closed slap
      `tn` high bongo tone
      `tp` high bongo mute
      `th` high bongo open slap
      `tg` high bongo closed slap
      `cm` cajon bass
      `cn` cajon open tone
      `cp` cajon mute
      `ch` cajon open slap
      `cg` cajon closed slap
      `cd` cajon tap
      `jm` djembe bass
      `jn` djembe tone
      `jp` djembe mute
      `jh` djembe open slap
      `jg` djembe closed slap
      `jd` djembe tap
      `xk` shook
      `cc` clap
      `td` clave
      `sx` rainstick
    ———————————————————————————————
      GUITAR
      `rk` rake
      `dt` deep tap
      `lt` light tap
      `dk` dark tick
      `tk` bright tick
      `hk` handmute
      `sk` strum mute
    ———————————————————————————————
      OTHER
      `rf` ref whistle
      `ah` scream
      `ws` Wilhelm scream
      `rn` siren
      `ck` crickets
      `tw` tweet, chirp
      `lc` the licc
      `lf` laugh track
      `cx` shattering glass
      `wx` whoosh
      `hs` hiss
    ———————————————————————————————

Simultaneous sounding __raps__ are placed together using `'`

## Sync

[Tones][tone] and [raps][rap] and even [knits][knits] can be performed at the same time by just concatenating them together with a `!` in between so it’s easy to read.

    ———————————————————————————————————————
      WORD            VALUE
    ———————————————————————————————————————
      bm!xd   bass drum + closed hi-hat
      xk!kl       shook + clap
      rk!le        rake + high G
    ———————————————————————————————————————

## Breath

A __breath__ is a [rap][rap] that gives the player room to breathe. It is notated with the [word][word] `hh` and not explicitly pronounced.

***

# Knits

__Knits__ are collections of notes occuring simultaneously. They come in three varieties: [spans][span], [chords][chord], and [braids][braid].

## Root

A __root__ is the tonic of a [knit][knits].

## Strand

A __strand__ is a two-voice harmony created by combining a [tone][tone] with a lowercase, two-character [span][span] representing the interval from the [tone][tone]. A perfect fifth ascending from `ma` is `mayv` 'mah-YEEV' whereas a perfect fifth descending is `mawi` 'MAH-wee'. A __strand__ is only every two voices.

## Knit Root

All __knits__ other than [strands][strand] have a capitalized [tone start][tone start] to signify the [root][root].

    —————————————————
      START  OFFSET  
    —————————————————
        H      +6
        L      +5
        J      +4
        S      +3
        D      +2
        K      +1
    —————————————————
        M      ±0
    —————————————————
        G      -1
        T      -2
        Z      -3
        C      -4
        N      -5
    —————————————————

`X` can be used as a [start][start] for speaking about chord qualities without a specified [root][root].

## Thread

A __thread__ is a single [voice][voice] within a __knit__, using the lowercase [spans][span].

    ———————————————————————————————————————————————————————————
      LOWERCASE for THREADS
    ———————————————————————————————————————————————————————————
       1  ♭2   2  ♭3   3   4  ♭5   5  ♭6   6  ♭7   7   8   X
      -a- -r- -u- -o- -e- -i- -q- -v- -l- -m- -n- -z- -x- -h-
    ———————————————————————————————————————————————————————————

An `h` is added for octave spans without a voice. Here are the rules for pronouncing the *threads*:

+ For any three consonants in a row, a schwa `ə` is inserted between the second and third
+ For any two vowels in a row, if the first is `u`, `o`, or `r`, a `w` is inserted after it
+ For any two vowels in a row, if the first is `a`, `e`, or `i`, a `y` is inserted after it
+ An `x` immediately after the [root][root] is an octave
+ An `x` anywhere else is one missing octave and gets no voice
+ The `r` is always a rhoticized mid vowel
+ The `q` is always a glottal stop

## Chord

A __chord__ is a [knit][knits] constructed using the capitalized [tone start][tone start] as the [root][root] and [threads][thread] for all other voices to convey a quality but not a specific voicing — how most people think of *chords*. Prefixing a [thread][thread] with [span][span] pronunciation yields a *slash chord*.

    ————————————————————————————————————————————————————————————
            NAME   CHORD                 IPA   TRANSLITERATION
    ————————————————————————————————————————————————————————————
               A   Zev                  ˈzev   ZEHV
              B5   Gav                  ˈgav   GAHV
            Cm/G   vMov               viˈmov   vee-MOHV
             F♯7   Hevn              ˈhe.vən   HEH-vuhn
             D13   Devnuim       ˈdev.nuˌwim   DEHV-noo-WEEM
      E♭13(♭5♯9)   Seqnoim       ˈseʔ.noˌwim   SEHʔ-noh-WEEM
    ————————————————————————————————————————————————————————————

## Braid

A __braid__ is a specific voicing of a [chord][chord]. These can get much more complicated looking, but they follow the same rules with three added details. First, no octave is specified, so the lowest sounding [tone][tone] is prefixed to the [chord][chord]. Second, every [voice][voice] above the prefix gets a [thread][thread]. Third, if more than an entire octave is skipped, the [glyph][glyph] `x` is inserted for each octave+ skipped.

    ——————————————————————————————————————————————————————————————
            NAME   BRAID                 IPA   TRANSLITERATION
    ——————————————————————————————————————————————————————————————
               A   zaZvaev      zaˈzə.vaˌjev   zah-ZUH-vah-YEHV
              B5   gaGv               gaˈgəv   gah-GUHV
            Cm/G   naMaov          naˈma.wov   nah-MAH-wohv
             F♯7   haHevn          haˈhe.vən   hah-HEH-vuhn
             D13   daDevnuim   daˈdev.nuˌwim   dah-DEHV-noo-WEEM
      E♭13(♭5♯9)   saSeqnoim   saˈseʔ.noˌwim   sah-SEHʔ-noh-WEEM
    ——————————————————————————————————————————————————————————————

Note that the __braid__ `gaGv` is identical to the [strand][strand] `gayv`, but they do convey different things — `gaGv` is the powerchord; `gayv` means the interval as a stop. The root-fifth-octave voicing of a powerchord can never be achieved using [strands][strand].

    —————————————————————————————————————————————————————————————————————————————
      COMMON GUITAR VOICINGS
    —————————————————————————————————————————————————————————————————————————————
      NAME   TAB    THREADS   BRAID                   IPA   TRANSLITERATION
    —————————————————————————————————————————————————————————————————————————————
         E   022100   vaeva   joJvaeva   dʒoˈdʒə.vaˌje.va   joh-JUH-vah-YEH-vah
        Em   022000   vaova   joJvaova   dʒoˈdʒə.vaˌjo.va   joh-JUH-vah-YOH-vah

         A   x02220    vaev   zaZvaev        zaˈzə.vaˌjev   zah-ZUH-vah-YEHV
       A/E   002220   avaev   joZavaev      dʒoˈzə.vaˌjev   joh-ZAH-vah-YEHV
        Am   x02210    vaov   zaZvaov        zaˈzə.vaˌjov   zah-ZUH-vah-YOHV
      Am/E   002210   avaov   joZavaov      dʒoˈzə.vaˌjov   joh-ZAH-vah-YOHV

         D   xx0232     vae   daDvae          daˈdə.vaˌje   dah-DUH-vah-YEH
       D/A   x00232    avae   zaDavae         zaˈza.vaˌje   zah-DAH-vah-YEH
      D/F♯   200232   vavae   hoDvavae     hoˈdə.vaˌva.je   hoh-DUH-vah-VAH-yeh
        Dm   xx0231     vao   daDvao          daˈdə.vaˌjo   dah-DUH-vah-YOH
      Dm/A   x00231    avao   zaDavao         zaˈza.vaˌjo   zah-DAH-vah-YOH
      Dm/F   100231   vavao   loDvavao     hoˈdə.vaˌva.jo   hoh-DUH-vah-VAH-yoh

         G   320033   evava   naNevava        naˈne.vaˌva   nah-NEH-vah-VAH
         G   320003   evaea   naNevaea     naˈnə.vaˌje.ja   nah-NEH-vah-YEH-yah

         C   x32010    evae   maMevae        maˈmə.vaˌjev   mah-MEH-vah-YEH
       C/G   332010   aevae   naMaevae     naˈma.jəˌva.je   nah-MAH-yeh-VAH-yeh

         F   1x3211    aeva   loLaeva         loˈla.jeˌva   loh-LAH-yeh-VAH
    —————————————————————————————————————————————————————————————————————————————

***

# Cues

__Cues__ are composer directives, denoted by [glyph][glyph] `#`. In the Bourrée above, a [track][track]-level [cue][cues] is followed by the [key][key] `ma` to specify the key center, the 1-[chord][chord] `Xov` to specify the [mode][mode], the [groove][groove] for four [beats][beats] `|4.|`, and all at an allegretto [pulse][pulse].

## Tie

A __tie__ is used to show a [sound][sounds] being held into the next [bar][bar]. It is notated with `++` after the [sound][sound] and the unison [span][span] `aa` on the next bar followed by its duration.

## Comp

A __comp__ is a minimally specified accompaniment and harmonic background written within the [bar][bar].

### Vamp

A __vamp__ is a [comp][comp] that specifies rhythm and/or voicings.

## Art

An __art__ is an inline [cue][cues] each of which are denoted by special [glyphs][glyph] and rules.

### Smooth

__Smooth__ is a directive to perform legato, which is to be determined by each instrument. Such __arts__ are bracketed by parentheses `(` `)`.

### Ring

__Ring__ is a directive to let ring, that is not to stop a [sound][sounds] when others start. These begin with the [sound][sounds] (without any [click][click] if simultaneous, with if there is a delay) followed by curly brackets `{` `}` with the concurrent [sounds][sounds] notated between them. The [click][click] for the outside [note][notes] is at least as long as the combined [clicks][click] within the curly brackets. [Bar][bar] 7 from the Bach Bourrée in E Minor can be notated both of the following ways:

    ——————————————————————————————————————————————————
      7
        f| le.   de.ce ze^^c.  ,ce,|
        t| co.   ja.   ga.   ga.   |
      7
        | co{le.} ja{de.ce} ga{ze^^c.++} ga{aa.ce} | 
    ——————————————————————————————————————————————————


### Hold

__Hold__ is a directive to sustain [sounds][sounds] freely as they are played like when lifting the dampers on a piano. It is denoted by double curly brackets `{{` `}}`.

### Glide

__Glide__ is a directive to smoothly change the [pitch][pitch], like a bend. `/` is for changing a [pitch][pitch] up, `\` for changing a [pitch][pitch] down.

### Slide

__Slide__ is a directive to change the [pitch][pitch] in a stepwise manner, like a fret slide. `//` is for changing a [pitch][pitch] up, `\\` for changing a [pitch][pitch] down.

### Flux

__Flux__ is a directive to fluctuate the [pitch][pitch] around a [tone][tone], known as vibrato. It is denoted by the [glyph][glyph] `~`.

### Flam

__Flam__ is a directive to quickly articulate one [sound][sounds] before another. If less than a perfect fourth between consecutive [tones][tone], it is denoted by a [tone start][tone start] followed by the [glyph][glyph] `^` and the [tone][tone] to land on, otherwise, a complete [tone][tone] is also for the starting [sound][sounds].

### Trill

__Trill__ is a directive to quickly alternate between two [sounds][sounds], often used as ornamentation. It is denoted by the starting [tone][tone] followed by `^^` and then the [tone start][tone start] of the [tone][tone] to be alternated with.

### Trem

__Trem__ is a directive for the rapid articulation of a sustained [sound][sounds]. It is denoted by `!!` just after the [sound][sounds] `ma!!=` it applies to.

### Roll

__Roll__ is a directive to arpeggiate a [knit][knits]. It is denoted by `&` preceding the [knit][knits] for ascending arpeggiations and after for descending ones.

### Strum

__Strum__ is a directive to strum a [knit][knits]. It is denoted by `$` preceding the [knit][knits] for up-strums and after for down-strums.

### Strong

__Strong__ is a directive to accent and/or suddenly end a [sound][sounds] denoted by `*`. It is written directly before the [note][notes] it modifies for accents, `*ma.`, directly after the the note for staccato, `ma*.`, or even directly after a [click][click] for that abrupt ending `ma.*`.

### Harm

__Harm__ is a directive to play the nth harmonic. It is denoted by `*` followed by the number for said nth harmonic: `lo*3` is for performing the third harmonic. Rather than notating the pitch as a listener might hear it, Counternote notates the harmonic as it’s played.

### Rush

__Rush__ is a directive to play ahead of the beat. It is denoted by `<` before the note `<ma.`.

### Drag

__Drag__ is a directive to play behind the beat. It is denoted by `>` before the note `>ma.`.

## Chant

A __Chant__ is a set of lyrics to be sung set below the [voice][voice] with its corresponding melody. It is enclosed in double straight quotes `"` with each syllable getting at least one [sound][sounds] and underscores `_` for multiple [sounds][sounds]. Speech is denoted by the [rap][rap] `sw` in the [voice][voice].

***
 
# Schemes

[Schemes][schemes] are informational systems to help learn and understand Counternote and the underlying music theory.

## Clock

A [clock][clock] is a [scheme][schemes] for visualizing the relationships between [tones][tone].

### Hue Clock

The [hue clock][hue clock] places [tones][tone] in chromatic order around a clockface so that stepping clockwise goes up a [notch][notch] and counterclockwise goes down a [notch][notch].

    ————————————————————————————————————————————————
                                             NOTCH
                         1                    DIFF
               7        ma        ♭2            0
                 ga  ===||===  ka              ±1
         ♭7             ||              2
            ta  ========||========  da         ±2
                        ||
                        ||
       6  za  ==========||==========  sa  ♭3   ±3
                        ||
                        ||
            ca  ========||========  ja         ±4
         ♭6             ||              3
                 na  ===||===  la              ±5
               5        ha        4            +6
        FILE CHANGE ↑ ♯4/♭5
    ————————————————————————————————————————————————

### Lux Clock

Swapping every odd-numbered value with its counterpart (1 with 7, 3 with 9, 5 with 11) makes the [lux clock][lux clock] with all of the [tones][tone] written in harmonic order around the clockface. All of the [bright luxes][bright lux] are on the right and all of the [dark luxes][dark lux] are on the left. The [blends][blend], [moods][mood], and [rubs][rub] slice the [lux clock][lux clock] horizontally into three sections. 

    ——————————————————————————————————————————————————————————————
                   |——— DARK ———|    LUX   |—— BRIGHT ——|
      |ARTICULATION|                  1                 | VIBE |
          LABIAL            4        ma         5        BLENDS
          DENTAL              la  ===||===  na              |
                      ♭7             ||              2      |
         ALVEOLAR        ta  ========||========  da       —————
                                     ||
                                     ||
         ALVEOLAR  ♭3  sa  ==========||==========  za  6  MOODS
                                     ||                     |
                                     ||                     |
          PALATAL        ca  ========||========  ja       —————
                      ♭6             ||              3
           VELAR              ka  ===||===  ga             RUBS
          GLOTTAL          ♭2        ha        7            |
                                   ♯4/♭5                  —————
    ——————————————————————————————————————————————————————————————

### Lux

A [lux][lux] is a measure of how [bright][bright lux] or [dark][dark lux] an interval is. This lines up mostly with major (large) and minor (small) intervals but also includes the perfect fourth and fifth which are dark and bright, respectively.

### Bright Lux

A [bright lux][bright lux] is a harmonic relationship that evokes a sense of opening up, turning outward. It includes all major (large) intervals plus the (larger) perfect fifth.

### Dark Lux

A [dark lux][dark lux] is a harmonic relationship that evokes a sense of settling down, turning inward. It includes all minor (small) intervals plus the (smaller) perfect fourth.

### Vibe

A [vibe][vibe] is the emotional quality of an interval that runs orthogonal to [lux][lux].

### Blend

A [blend][blend] is a more harmonious [vibe][vibe]: `-a`, `-u`, `-i`, `-v`, `-n`. They are the high vowels, some paired with labial consonants, plus the [root][root] which is an open vowel.

### Mood

A [mood][mood] is a [vibe][vibe] that gives a major or minor quality: `-o`, `-e`, `-m`, `-l`. All are  mid vowels, some paired with alveolar consonants.

### Rub

A [rub][rub] is a dissonant [vibe][vibe] that clashes with the root: `-r`, `-q`, `-z`. They are all the rhoticized vowels, some paired with consonants.

## Yap

A [yap][yap] is a way of vocalizing the [groove][groove] as [words][word] designed to be understandable by lipreading alone. The classic Greek rhythms are as follows:

    ——————————————————————————————————————————
      |!.|  (trochee)     PO-de       pode
      |.!|  (iamb)        be-TO       beto
      |!..| (dactyl)      PO-de-ge    podege
      |.!.| (amphibrach)  be-TO-ge    betoge
      |..!| (anapest)     be-de-KO    bedeko
      |!!|  (spondee)     PO-TO       poto
      |..|  (pyrrhic)     be-de       bede
    ————————————————————————————————————————

The rules for generating these __yaps__ are rather simple:
* The first [beat][beats] is a bilabial consonant `p` `b`
* The rest of the odd [beats][beats] are velar consonants `k` `g`
* The rest of the [beats][beats] are alveolar consonants `t` `d`
* The accent is a voiceless consonant `p` `t` `k` paired with mid rounded `o`
* The lax syllables are voiced consonants `b` `d` `g` paired mid unrounded `e`

The lips will be rounded on the accent and will close at the beginning of the sequence. This is so that the first [beat][beats] and the accent of the sequence can be seen even if not heard.

For typical four-on-the-floor rhythms, we split them into two-syllable [words][word]:

    ————————————————————————————————
      |4.|  PO-de ge-de  pode gede
      |4.|  be-TO ge-de  beto gede
      |4.|  be-de KO-de  bede kode
      |4.|  be-de ge-TO  bede geto
    ————————————————————————————————

Now we can break these up into eigth notes using the `i` for unaccented even eights and `u` for the accented ones:

    ——————————————————————————————————————————————————————
      |8,|  PO-ni de-ni ge-ni de-ni  poni deni geni deni
      |8,|  be-NU de-ni ge-ni de-ni  benu deni geni deni
    ——————————————————————————————————————————————————————

And even further into sixteenth notes using the `a` for the unaccented even sixteenths and `o` for the accented ones:

    ———————————————————————————————————————————————————————————————————————————————
      |16:|  PO-a-ni-a de-a-ni-a ge-a-ni-a de-a-ni-a  poania deania geania deania
      |16:|  be-O-ni-a de-a-ni-a ge-a-ni-a de-a-ni-a  beonia deania geania deania
      |16:|  be-a-NU-a de-a-ni-a ge-a-ni-a de-a-ni-a  beanua deania geania deania
      |16:|  be-a-ni-O de-a-ni-a ge-a-ni-a de-a-ni-a  beanio deania geania deania
    ———————————————————————————————————————————————————————————————————————————————

For complex meter, we break things up into two- and three-syllable __yaps__:

    ————————————————————————————————————————————————————————————————————
      |3,3,2,2| PO-de-ge TO-ge-de KO-de KO-de  podege togede kode kode
    ————————————————————————————————————————————————————————————————————
