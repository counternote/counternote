***

# Counternote Specification version 0.8.1

This is a terse description of Counternote with minimal definitions and examples.

***

# Gloss

This [gloss][gloss] serves as a glossary and table of contents for all things Counternote.

### [BASES][bases]

Foundational elements

* [__term__][term]: a precise concept in music and Counternote, linked here in the [gloss][gloss]
* [__glyph__][glyph]: any typed character
* [__word__][word]: a connected sequence of [phones][phone]
* [__sign__][sign]: a connected sequence of [glyphs][glyph] that do not make a [word][word]
* [__phone__][phone]: the pronunciation of a speakable [glyph][glyph] or cluster of [glyphs][glyph]
  * [__start__][start]: the first [phone][phone] or *linguistic onset* of a [word][word]
  * [__rhyme__][rhyme]: the rhyming part or *linguistic coda* of a [word][word]

### [FORMS][forms]

Structural elements

* [__score__][score]: an entire composition
* [__stage__][stage]: a place for compositional and instrumental details
  * [__scribe__][scribe]: a composer of the [score][score]
* [__track__][track]: an individual piece within a [score][score]
  * [__key__][key]: the home base for a [track][track]
* [__round__][round]: a block of repeated music
* [__bar__][bar]: details on how and what to play
  * [__voice__][voice]: a monophonic instrument and the sequence of [sounds][sounds] to be played
  * [__stack__][stack]: multiple [voices][voice] in the same [bar][bar]
  * [__rep__][rep]: a directive to repeat a [bar][bar] or [round][round]
  * [__jump__][jump]: a directive on what to play next
  * [__lap__][lap]: a variation on a [bar][bar]
* [__pit__][pit]: a place suitable for code

### [SOUNDS][sounds]

Any acoustic vibration

* [__pitch__][pitch]: the number of vibrations per second, the frequency
* [__rank__][rank]: the set of [pitches][pitch] separated by powers of two, the pitch-class
* [__file__][file]: the octave range that contains a [pitch][pitch]
* [__band__][band]: any range of [pitches][pitch]
* [__notch__][notch]: the range of a single *semitone* or *half-step*
* [__break__][break]: the [rank][rank] where the [file][file] changes for a given [key][key]

### [BEATS][beats]

Rhythmic elements

* [__hold__][hold]: the duration of a [note][notes]
* [__groove__][groove]: the arrangement of [beats][beats] in a [bar][bar]
* [__click__][click]: the tempo
* [__cut__][cut]: a tuplet
  * [__short cut__][short cut]: a quick [cut][cut] notation
  * [__long cut__][long cut]: a robust [cut][cut] notation
* [__shift__][shift]: a section of polymeter
* [__rift__][rift]: a section of polyrhythm

### [NOTES][notes]

Acoustic vibrations held in time

* [__tone__][tone]: a [word][word] indicating the absolute [rank][rank] and [file][file] of a [sound][sounds]
  * [__tone start__][tone start]: the [start][start] that denotes absolute [rank][rank]
  * [__tone rhyme__][tone rhyme]: the [rhyme][rhyme] that denotes [file][file]
* [__root__][root]: the home base for [spans][span] and [knits][knits]
* [__span__][span]: a [word][word] indicating the relative [rank][rank] and [file][file] of a [sound][sounds]
  * [__span start__][span start]: the [start][start] that denotes [file][file]
  * [__span rhyme__][span rhyme]: the [rhyme][rhyme] that denotes relative [rank][rank]
* [__rap__][rap]: a [word][word] indicating a [sound][sounds] where [pitch][pitch] is indeterminate or incidental
* [__tie__][tie]: a [sound][sounds] from a previous [bar][bar] is still being held
* [__breath__][breath]: a breath of fresh quiet
* [__stop__][stop]: two [sounds][sounds] occuring at the same time

### [KNITS][knits]

Manifold acoustic vibrations

* [__thread__][thread]: a single [voice][voice] within a [knit][knits]
* [__chord__][chord]: a [knit][knits] constructed using [tones][tone] as a starting point
* [__braid__][braid]: a [knit][knits] constucted using [spans][span] as a starting point to make “metachords”
* [__weave__][weave]: a [chord][chord] or [braid][braid] with the exact voicing

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
  * [__vibe__][vibe]: a repeated fluctuation in [pitch][pitch] of a [sound][sounds]
  * [__grace__][grace]: a quick [sound][sounds] before another
  * [__lick__][lick]: a quick run of [sounds][sounds]
  * [__trill__][trill]: a quick alternating between [sounds][sounds]
* [__line__][line]: lyrics beneath the [voices][voice]
* [__drift__][drift]: lyrics beneath the [voices][voice]

### [SCHEMES][schemes]

Toward a deeper understanding

* [__clock__][clock]: a [scheme][schemes] for visualization the relationships between [tones][tone] or [spans][span]
  * [__hue clock__][hue clock]: [tones][tone] and [spans][span] arranged in chromatic order
  * [__lux clock__][lux clock]: [tones][tone] and [spans][span] arranged in harmonic order
  * [__lux__][lux]: a measure of relative brightness or darkness
  * [__bright lux__][bright lux]: a harmonic relationship evoking a sense of opening up
  * [__dark lux__][dark lux]: a harmonic relationship evoking a sense of settling down
  * [__blend__][blend]: a consonant sounding interval
  * [__mood__][mood]: a major/minor sounding interval
  * [__rub__][rub]: a dissonant sounding interval
* [__tap__][tap]: a system for vocalizing rhythms and [grooves][groove] as [words][word]

### [NIBS][nibs]

Odds and ends

  * [__mark__][mark]: the term `'`

[gloss]: #gloss

[bases]: #bases

[term]: #term
[glyph]: #glyph
[word]: #word
[sign]: #sign
[phone]: #phone
  [start]: #start
  [rhyme]: #rhyme

[forms]: #forms

[score]: #score
[stage]: #stage
  [scribe]: #scribe
[track]: #track
  [key]: #key
[round]: #round
[bar]: #bar
  [voice]: #voice
  [stack]: #stack
  [rep]: #rep
  [jump]: #jump
  [lap]: #lap
[pit]: #pit

[sounds]: #sounds

[pitch]: #pitch
[rank]: #rank
[file]: #file
[band]: #band
[notch]: #notch
[break]: #break

[beats]: #beats

[hold]: #hold
[groove]: #groove
[click]: #click
[cut]: #cut
  [short cut]: #short-cut
  [long cut]: #long-cut
[shift]: #shift
[rift]: #rift

[notes]: #notes

[tone]: #tone
  [tone start]: #tone-start
  [tone rhyme]: #tone-rhyme
[root]: #root
[span]: #span
  [span start]: #span-start
  [span rhyme]: #span-rhyme
[rap]: #rap
[tie]: #tie
[breath]: #breath
[stop]: #stop

[knits]: #knits

[thread]: #thread
[chord]: #chord
[braid]: #braid
[weave]: #weave

[cues]: #cues

[comp]: #comp
  [vamp]: #vamp
[tweak]: #tweak
[art]: #art
  [smooth]: #smooth
  [ring]: #ring
  [glide]: #glide
  [slide]: #slide
  [vibe]: #vibe
  [grace]: #grace
  [lick]: #lick
  [trill]: #trill
[drift]: #drift
[line]: #line

[schemes]: #schemes

[clock]: #clock
  [hue clock]: #hue-clock
  [lux clock]: #lux-clock
  [lux]: #lux
  [bright lux]: #bright-lux
  [dark lux]: #dark-lux
  [blend]: #blend
  [mood]: #mood
  [rub]: #rub
[tap]: #tap

[nibs]: #nibs

  [mark]: #mark

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

## Word

A [word][word] is connected sequence of [phones][phone] that can be spoken like the [tone][tone] `da` or the [hold][hold] `qo` (`.`).

## Sign

A [sign][sign] is connected sequence of [glyphs][glyph] do not make a [word][word] like the starting sequence `++*`.

## Phone

A [phone][phone] is an indivisible articulation of spoken Counternote represented by one or two [glyphs][glyph] and up to three phonemes.

### Start

A [start][start] is the first [phone][phone] or *linguistic onset* of a [word][word]. All of these sounds are found in American English, but the letters 

The standard starting consonants with their points of articulation are as follows:

    ——————————————————————————————————
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
    ——————————————————————————————————

Capital vowels and vowels at the beginning of a [word][word] are preceeded by an unwritten [ʔ]. A unwritten [j] ('soft y' like the 'y' in 'yes') is sometimes used to break up consecutive vowels.

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

All [rhymes][rhyme] include vowels as part of their [phone][phone]. Vowels are pure spanish vowels plus the rhoticized mid vowel [ɚ]:

    ————————————————————————————————
      GLYPH    IPA   PRONUNCIATION
        a       ɑ        'ah'
        r      ɚ,r̩       'er'
        u       u        'oo'
        o       o        'oh'
        e       e        'eh'
        i       i        'ee'
        h       ə        'uh'
    ————————————————————————————————

The schwa [ə] is inserted between consonants in some instances, but there is no corresponding [glyph][glyph] in that case.

Like with [starts][start], some [glyphs][glyph] can cluster:

    ————————————————————————————————
      GLYPHS   IPA   PRONUNCIATION
        -il     il       'eel'
        -al   al,æl      'al'
        -ar   ɑ˞,ar      'ar'
        -or   ɔ˞,or      'or'
    ————————————————————————————————

As well as some clustered [phones][phone] as [rhymes][rhyme]:

    ————————————————————————————————
      RHYME    IPA   PRONUNCIATION
       -s     ɚs,r̩s      'ers'
       -n       un       'oon'
       -m       om       'ohm'
       -l     ɛl,el      'ehl'
       -v       iv       'eev'
       -t    ɑ˞t,art     'art'
    ————————————————————————————————

***

# Forms

[Forms][forms] are structural elements of a composition and how such elements connect together. Here is the A-section of Bourrée by Bach using [tones][tone]:


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
        f| -           .     wa.ka  |
        t| -           .     yu.ku  |
      1
        f| ya.   ka.wa pa.   wa.ka  |
        t| wu.   ju.   zo.   ju.    |
      2
        f| za.   fa.pa wa.   ba.da  |
        t| yu.   ku.   wu.   ku.    |
      3
        f| za.   jo.yo ko.   yo.jo  |
        t| yu.   ju.   zo.   ju.    |
      4
        f| za.jo yo.ko wo.   wa.ka  |
        t| yu.   zo.   wu.ku yu.ku  |
      5
        f| ya.   ka.wa pa.   wa.ka  |
        t| wu.   ju.   zo.   ju.    |
      6
        f| za.   fa.pa wa.   ba.da  |
        t| yu.   ku.   wu.   ku.    |
      7
        f| za.   ja.ya ka^^y.  ,ya, |
        t| yu.   do.   bo.   bo.    |
      8
        f| tYeva-      .      __    |
        t| yu-         .      %A @B |

    *++

## Score

A [score][score] is an entire composition in Counternote. It is enclosed in `++*` and `*++` [signs][sign]. When detailed in the [stage][stage], it is the title of work.

## Stage

A [stage][stage] holds compositional and instrumental details on entire [scores][score] and individual [tracks][track] such as title, author, instrument voices and tunings, and the like. The [score][score] [stage][stage] is between the `++*` and `+++` [signs][sign]. The [track][track] [stage][stage] is between `+++` [signs][sign].

### Scribe

A [scribe][scribe] is a composer of a [score][score] or [track][track].

## Track

A [track][track] is an individual piece that may or may not occur simultaneously within a score. The are separated with `+++` [signs][sign].

### Key

A [key][key] is the home base for [tones][tone] and [spans][span] of a [track][track] denoted by a [tone][tone]. By default it’s `da` which does not imply a particular tonality. If a [chord][chord] is used, it will imply the following:

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

## Round

A [round][round] is a block of repeated music marked with an unindented letter or string on its own line for legibility, denoted above with `A`.

## Bar

A [bar][bar] contains all of the details of what to play when and how to play it marked with a two-space indented numeral on its own line, again for legibility, denoted above with `0`, `1`, `2`, and the like. The main component of a [bar][bar] is a [voice][voice], but it may also include composer directions and accompaniments and lyrics. `0` indicates a *pick-up bar*, an incomplete bar that leads into the first [beat][beats]. A specific [bar][bar] can be accessed outside a [round][round] by referencing the [round][round] followed by the [bar][bar] with a [mark][mark] in between, for example `A'1`.

### Voice

A [voice][voice] is akin to a sequence of music performed by a monophonic instrument such as a human *voice* enclosed in pipe `|` terms. Inline harmonies such as [stops][stop] and [chords][chord] are multiple [voices][voice] even if performed by the same instrument and notated on the same line. Harmonies can alternatively be notated by a [stack][stack].

### Stack

A [stack][stack] is separate voices in the same [bar][bar]. These can be separate instruments for an ensemble, or the same instrument like the right and left hands of a piano player or even the six strings of a guitar for a more musically informative tablature. Above, “thumb” and “fingers” were chosen.

### Lap

A [lap][lap] is a variation on a [bar][bar] to be played in different iterations of a [round][round]. It is denoted by the [bar][bar] followed by the [lap][lap] with a [mark][mark] in between, much like a [bar][bar] is specified from outside a [round][round] `8'1`.

### Rep

A [rep][rep] is a directive to repeat a [bar][bar] or [round][round].

### Jump

A [jump][jump] is a directive on what part to play next.

## Pit

A [pit][pit] holds the programmery bits. 

***

# Sound

A [sound][sounds] is any acoustic vibration fit to be notated. They come in three varieties: [tones][tone], [spans][span], and [raps][rap]. The first two deal with those of definite [pitch][pitch], [tones][tone] in an absolute way and [spans][span] in a relative way, whereas [raps][rap] deal with those of indefinite or incidental [pitch][pitch].

## Pitch

A [pitch][pitch] is the number of vibrations per second, the frequency.

## Rank

A [rank][rank] is like all traditional *notes* regardless of octave, also known as the pitch-class, the set of pitches separated by powers of two. These are written as [tones][tone] with the `-a` [rhyme][rhyme] such as `da` for *C* or [spans][span] with the `h-` [start][start] such as `ha` for *C* in the [key][key] of `da`.

## File

A [file][file] is analogous to the octave number, for instance the [band][band] from 256Hz to 512Hz.

## Band

A [band][band] is a defined range of frequencies with the lower bound inclusive and the upper bound exclusive.

## Notch

A [notch][notch] is a [band][band] a twelth root of two wide, a traditional *semitone* or *half-step*.

## Break

A [break][break] is the point where the [file][file] changes based on the [key][key] of a composition. It is always at seven [notches][notch] above and six [notches][notch] below. A [break][break] changes only when the [key][key] explicitly changes.

***

# Beats

[Beats][beats] are basic rhythmic elements

## Hold

A [hold][hold] is punctuation character that represents a duration. They come in seven varieties, six ordered by powers of two and a special one for indefinite duration:

    ————————————————————————————
      HOLD  VALUE  WORD   IPA
    ————————————————————————————
      `;`    1x     qi    kʷi
      `:`    2x     qe    kʷe
      `,`    4x     qa    kʷɑ
      `.`    8x     qo    kʷo
      `-`   16x     qu    kʷu
      `=`   32x     qr    kʷɚ
    ————————————————————————————
      `?`    ?x     qh    kʷə
    ————————————————————————————

## Groove

A [groove][groove] tells the arrangement of [beats][beats] in a [bar][bar].

## Click

A [click][click] gives the tempo.

## Cut

A [cut][cut] is a subdivision of a [beat][beats], also known as a tuplet. While there are six well-defined [holds][hold] that do duple meter, many more can be achieved without redefining holds or changing the [click][click].

### Short Cut

A [short cut][short cut] is a quick and dirty way of defining a [cut][cut], pun intended. It works with small prime number tuplets: duplets, triplets, and quintuplets. The rules are as follows:

* no whitespace exists between the [sounds][sounds]
* [holds][hold] act as separators of the [sounds][sounds] in the [cut][cut]
* the last [sound][sounds] does *not* receive a [hold][hold]
* the total duration of all the [holds][hold] is the duration the [cut][cut] fills
* a [mark][mark] `'` can be used as a separator that does not add duration
* quadruplets and sextuplets should be written as two duplets/triplets connected by a [mark][mark]
* septuplets and longer just add [sounds][sounds] and [marks][mark]
* a [tie][tie] `aa` may be used to signal that one [sound][sounds] is held

Those rules add up to:

    —————————————————————————————————————————
      |4.|
      1
        # one beat for =
        | da=                             |
        # is equivalent to
        | da-aa                           |
      2
        # two beats over =
        | da=da                           |
        # is equivalent to
        | da-         da-                 |
      3
        # three beats over --
        | da-da-da                        |
      4
        # four beats over --
        | da-da'da-da                     |
        # is equivalent to
        | da.   da.   da.   da.           |
      5
        # five beats over ....
        | da.da.da.da.da                  |
      6
        # six beats over ....
        | da.da.da'da.da.da               |
        # is equivalent to
        | da.da.da    da.da.da            |
      7
        # seven beats over ....
        | da.da.da'da'da.da.da            |
      8
        # eight beats over ....
        | da.da   da.da   da.da   da.da   |
        # is equivalent to
        | da.da'da.da     da.da'da.da     |
        # is equivalent to
        | da.da.da'da'da'da.da.da         |
        # is equivalent to
        | da, da, da, da, da, da, da, da, |
    —————————————————————————————————————————

[Short cuts][short cut] can greatly cut down on visual noise. Consider what the Bourrée above looks like using [holds][hold] on every [note][notes]:

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
        f| -               .       wa, ka, |
        t| -               .       yu, ku, |
      1
        f| ya.     ka, wa, pa.     wa, ka, |
        t| wu.     ju.     zo.     ju.     |
      2
        f| za.     fa, pa, wa.     ba, da, |
        t| yu.     ku.     wu.     ku.     |
      3
        f| za.     jo, yo, ko.     yo, jo, |
        t| yu.     ju.     zo.     ju.     |
      4
        f| za, jo, yo, ko, wo.     wa, ka, |
        t| yu.     zo.     wu, ku, yu, ku, |
      5
        f| ya.     ka, wa, pa.     wa, ka, |
        t| wu.     ju.     zo.     ju.     |
      6
        f| za.     fa, pa, wa.     ba, da, |
        t| yu.     ku.     wu.     ku.     |
      7
        f| za.     ja, ya, ka^^y.  ,   ya, |
        t| yu.     do.     bo.     bo.     |
      8
        f| tYeva-          .       __      |
        t| yu-             .       %A @B   |

    *++

### Long Cut

A [long cut][long cut] uses square brackets with [marks][mark] `'` between [sounds][sounds] and [holds][hold] at the end to slice up the [bar][bar].

    —————————————————————————————————
      |4.|
      1
        # one beat for =
        | da=                     |
      2
        # two beats over =
        |[da'da]=                 |
        # is equivalent to
        | da=da                   |
      3
        # three beats over =
        |[da'da'da]=              |
        # is equivalent to
        | da-da-da                |
      4
        # four beats over =
        |[da'da'da'da]=           |
        # is equivalent to
        |[da'da]-    [da'da]-     |
        # and equivalent to
        | da-da'da-da             |
        # and equivalent to
        | da-da       da-da       |
    —————————————————————————————————

[Long cuts][long cut] work in two places where [short cuts][short cut] cannot: nested tuplets and across multiple bars.

To nest a [cut][cut], just place a [short cut][short cut] or a [long cut][long cut] where a single cut would go:

    —————————————————————————————————
      |4.|
      1
        # triplet in triplet over 1
        |[da'da'[da'da'da]]=      |
    —————————————————————————————————

If a nested [cut][cut] takes up more than one element of a tuplet, `+` and the [tie][tie] `aa` are used: 

    —————————————————————————————————
      |4.|
      1
        # triplet in triplet over 2
        |[da'[da'da'da]+aa]=      |
    —————————————————————————————————

Because tuplets are treated as a block of one duration split evenly, the total duration must be present at the end even if it goes on longer than the [bar][bar] where it’s written. The `+` and [tie][tie] `aa` are used in this case as well:

    —————————————————————————————————
      |4.|
      1
        # triplet over...
        |[da'da'da]=+=            |
      2
        # ...2 bars
        | aa=                     |
    —————————————————————————————————

The `+` helps the performer see what how long the [cut][cut] is.

## Shift

A [shift][shift] is a section of polymeter.

## Rift

A [rift][rift] is a section of polyrhythm.

***

# Notes

[Notes][notes] are [sounds][sounds] for a [hold][hold].

## Tone

A [tone][tone] is closest to a *note* in a traditional sense, like the [rank][rank] of *C* or a specific C note. Any [pitch][pitch] that when multiplied or divided by powers of two falls in the [notch][notch] starting from 256Hz is described by the [rank][rank] `da`. That means any [pitch][pitch] that falls in the [notch][notch] from about 430.5Hz to just over 456Hz is `ja` including *A440*, *A444*, and *A432*, which does not include the baroque tuning *A415*, falling into the [rank][rank] just below called `xa`.

A list of all the two-[glyph][glyph] [tones][tone] moving left to right, bottom to top:

    ——————————————————————————————————————————————————————
      RANK (pitch class) →
    ——————————————————————————————————————————————————————
          E   F   F♯  G   G♯  A   A♯  B   C   C♯  D   D♯
      +3  wl  gl  kl  yl  xl  jl  cl  zl  dl  fl  bl  pl 
      +2  wi  gi  ki  yi  xi  ji  ci  zi  di  fi  bi  pi 
      +1  we  ge  ke  ye  xe  je  ce  ze  de  fe  be  pe 
       0  wa  ga  ka  ya  xa  ja  ca  za  da  fa  ba  pa 
      -1  wo  go  ko  yo  xo  jo  co  zo  do  fo  bo  po 
      -2  wu  gu  ku  yu  xu  ju  cu  zu  du  fu  bu  pu 
      -3  wr  gr  kr  yr  xr  jr  cr  zr  dr  fr  br  pr
    ——————————————————————————————————————————————————————
      ↑ FILE (octave)
    ——————————————————————————————————————————————————————

### Tone Start

The [start][start] of a [tone][tone] will always be a consonant represented by a single [glyph][glyph]. Each is identified with a single [rank][rank]. The traditional “naturals” are voiced consonants and the “accidentals” voiceless. The points of articulation move from the back of the mouth up through to the lips (labiovelar —> velar —> palatal —> postalveolar —> alveolar —> labiodental —> bilabial).

    ——————————————————————————————
      START  VALUE  IPA  ENGLISH
    ——————————————————————————————
        p-   D♯/E♭   p     'p'
        b-     D     b     'b'
        f-   C♯/D♭   f     'f'
        d-     C     d     'd'
        z-     B     z     'z'
        c-   A♯/B♭   tʃ   'ch'
        j-     A     dʒ    'j'
        x-   G♯/A♭   ʃ    'sh'
        y-     G     j     'y'
        k-   F♯/G♭   k     'k'
        g-     F     g     'g'
        w-     E     w     'w'
    ——————————————————————————————

### Tone Rhyme

The [rhyme][rhyme] of a [tone][tone] is all but the [start][start], also known as the rhyming part (linguistic coda). It represents the [file][file] of the [tone][tone]. The exact [pitch][pitch] a [file][file] lines up with is flexible, but by default, `da` is middle C in all [keys][key]. `-a` can also refer to all [files][file] of a [rank][rank].

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
       -ar    -4    ɑ˞    'ar'
       -or    -5    ɔ˞    'or'
    —————————————————————————————

## Root

A [root][root] is the [tone][tone] or [span][span] that serves as the centerpoint for harmony within [spans][span] and [chords][chord].

## Span

A [span][span] is an interval *and* a distinct [tone][tone] relative to some [root][root] or [key][key]. For instance, `la` is both an octave interval *and* whatever [tone][tone] is one octave above the [root][root] or [key][key]. The [span start][span start] stretches for one octave with the [break][break] in the same place as the [tone rhyme][tone rhyme].

In the Bourrée above, the [tones][tone] are used to express [pitch][pitch] in the [notes][notes]. However, there is another way to write it using [spans][span]:

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
        f| -           .     ha.hu  |
        t| -           .     so.su  |
      1
        f| ho.   hu.ha hs.   ha.hu  |
        t| sa.   si.   tv.   si.    |
      2
        f| hv.   hm.hs ha.   hn.hl  |
        t| so.   su.   sa.   su.    |
      3
        f| hv.   ti.to tu.   to.ti  |
        t| so.   si.   tv.   si.    |
      4
        f| hv.ti to.tu ta.   ha.hu  |
        t| so.   tv.   sa.su so.su  |
      5
        f| ho.   hu.ha hs.   ha.hu  |
        t| sa.   si.   tv.   si.    |
      6
        f| hv.   hm.hs ha.   hn.hl  |
        t| so.   su.   sa.   su.    |
      7
        f| hv.   hi.ho hu^^o.  ,ho, |
        t| so.   tl.   tn.   tn.    |
      8
        f| tOeva-      .     __     |
        t| so-         .     %A @B  |

    *++

These complementary ways of looking at music, one using absolute [pitch][pitch], one using relative [pitch][pitch], are central to the ethos of Counternote. Both should be used and learned because they teach different aspects of music. That said, some instruments will favor one style over another. The piano and various stringed instruments including guitar will favor [tones][tone] while transposing instruments including a capoed guitar will favor [spans][span] with a [key][key] center set to the lowest sounding [tone][tone] on that instrument.

A list of all the two-[glyph][glyph] [spans][span] moving left to right, bottom to top:

    ——————————————————————————————————————————————————————
      RANK (pitch class) →
    ——————————————————————————————————————————————————————
          -4  -3 -♭3  -2 -♭2   1  ♭2   2  ♭3   3   4  ♭5 
      +3  mv  ml  mm  mn  ms  ma  mr  mu  mo  me  mi  mt 
      +2  vv  vl  vm  vn  vs  va  vr  vu  vo  ve  vi  vt
      +1  lv  ll  lm  ln  ls  la  lr  lu  lo  le  li  lt
       0  hv  hl  hm  hn  hs  ha  hr  hu  ho  he  hi  ht
      -1  tv  tl  tm  tn  ts  ta  tr  tu  to  te  ti  tt
      -2  sv  sl  sm  sn  ss  sa  sr  su  so  se  si  st
      -3  nv  nl  nm  nn  ns  na  nr  nu  no  ne  ni  nt
    ——————————————————————————————————————————————————————
      ↑ FILE (octave)
    ——————————————————————————————————————————————————————

### Span Start

The [start][start] of a [span][span] indicates the [file][file] above or below the mid-range [root][root] or [key][key]. Middle C would typically be in the `h-` [file][file].

    —————————————————————————————
      START  FILE  IPA  ENGLISH
    —————————————————————————————
       my-    +5    mʲ    'my'
       mw-    +4    mʷ    'mw'
       m-     +3    n      'm'
       v-     +2    v      'v'
       l-     +1    l      'l'
    —————————————————————————————
       h-     ±0    h      'h'
    —————————————————————————————
       t-     -1    t      't'
       s-     -2    s      's'
       n-     -3    n      'n'
       ny-    -4    nʲ    'ny'
       nw-    -5    nʷ    'nw'
    —————————————————————————————


### Span Rhyme

The [rhyme][rhyme] of a [span][span] tells the interval from a [root][root] or [key][key]. The quality of the vowel tells the distance from the its starting point while a terminating consonant (excluding `-r` which is treated as a vowel in this case) means it’s an interval closest to the [root][root] from below. For brevity and symmetry, only the final [glyph][glyph] of the [rhyme][rhyme] is written.


    ———————————————————————————————————
      RHYME   VALUE    IPA    ENGLISH
    ———————————————————————————————————
        -s      7     ɚs,r̩s    'ers'
        -n     ♭7       un     'oon'
        -m      6       om     'ohm'
        -l     ♭6     ɛl,el    'ehl'
        -v      5       iv     'eev'
        -t    ♯4/♭5  ɑ˞t,art   'art'
        -i      4       i       'ee'
        -e      3      ɛ,e      'eh'
        -o     ♭3       o       'oh'
        -u      2       u       'oo'
        -r     ♭2      ɚ,r̩      'er'
        -a      1       ɑ       'ah'
    ———————————————————————————————————

## Rap

A [rap][rap] is any sound where [pitch][pitch] is indeterminate or incidental. Rather than having some algorithmic way of bulding these, [raps][rap] are just a simple, user-definable lookup table with the caveat that they cannot conflict with [tones][tone] or [spans][span]. These are some of the proposed [raps][rap]:

    ————————————————————————
      `aa` tie
      `hh` breath (rest)
    ————————————————————————
      `sp` speech
      `hx` hush, silence
      `nh` inhale
      `xh` exhale
    ————————————————————————
      `xs` blue noise
      `xx` white noise
      `xw` pink noise
    ————————————————————————
      `pf` pf snare
      `ks` k snare
      `bm` bass drum
      `kk` kick drum
      `dn` high tom
      `dm` mid tom
      `gn` low tom
      `gm` floor tom
      `tx` opening hi-hat
      `dx` open hi-hat
      `xt` closing hi-hat
      `xd` closed hi-hat
      `kt` rim shot
      `cx` crash
      `cs` ride
      `kl` clap
      `dt` bright clave
      `dd` dark clave
    ————————————————————————
      `rk` rake
      `dp` deep tap
      `tp` light tap
      `dk` dark tick
      `tk` bright tick
      `hd` handmute
      `sd` strum mute
    ————————————————————————
      `rf` ref whistle
      `ws` Wilhelm scream
      `ck` shook
      `cp` chirp, cheep
      `jz` the licc
    ————————————————————————

## Tie

A [tie][tie] is a [rap][rap] used to show a [sound][sounds] from a previous [bar][bar] is still being held. It is notated with the [word][word] `aa` and not pronounced separately from the [sound][sounds] being held.

## Breath

A [breath][breath] is a [rap][rap] that gives the player room to breathe. It is notated with the [word][word] `hh` and not explicitly pronounced.

## Stop

A [stop][stop] is two [voices][voice] sounding simultaneously. They can be written by concatenating a [span] onto a [tone][tone] or [span][span] [root][root].

    ————————————————————————————————
      WORD      VALUE        IPA
    ————————————————————————————————
      dahr    minor 2nd      dɑhɚ
      dahu    major 2nd      dɑhu
      daho    minor 3rd      dɑho
      dahe    major 3rd      dɑhe
      dahi   perfect 4th     dɑhi
      daht  diminished 5th  dɑhɑ˞t
      datv   perfect 5th    dɑtiv
      datl    minor 6th     dɑtel
      datm    major 6th     dɑtom
      datn    minor 7th     dɑtun
      dats    major 7th     dɑtɚs
    ————————————————————————————————

[Raps][rap] can also be performed at the same time, but concatenating them together without some sort of separator gets really hard to read, so a [mark][mark] `'` is placed in between them. These can be combined with [tones][tone] and [spans][span] for percussive playing.

    —————————————————————————————————————
      WORD             VALUE
    —————————————————————————————————————
      bm'xd   bass drum + closed hi-hat
      ck'kl       shook + clap
      rk'we        rake + high E
    —————————————————————————————————————

***

# Knits

[Knits][knits] are collections of notes occuring simultaneously. While such can be achieved with [stops][stop], it quickly gets unruly and hard to read. [Knits][knits] come in three varieties: [chords][chord], [braids][braid], and [weaves][weave].

## Thread

A [thread][thread] is a single [voice][voice] within a [knit][knits]. They are the [glyphs][glyph] for the [span rhymes][span rhyme] without the extra vowel content attached to the consonants. Because vowels can cluster with vowels (`VV`) and consonants with consonants (`CC`), there are some additional rules for pronunciation:

    ——————————————————————————————
      V:  a,r,u,o,e,i
      C:  t,v,l,m,n,s
      G:  any glyph
      X:  end of string
      -:  syllable break
    ——————————————————————————————
      GLYPH  BEFORE  ADDS   IPA
    ——————————————————————————————
        a      V      j     a-jV
        r      V      w     ɚ-wV
        u      V      j     u-jV
        o      V      w     o-wV
        e      V      w     e-wV
        i      V      j     i-jV
    ——————————————————————————————
        VC     CV     -    VC-CV
        VC     CC     ə    VC-CəC
        VC     CX     ə    V-CəC
    ——————————————————————————————

The [blends][blend] that are vowels always get the patalal glide [j] starting the next syllable whereas the [moods][mood] and [rubs][rub] always get labiovelar [w]. The [glyph][glyph] `r` as a thread is always its vowel [phone][phone] except when capitalized in [braids][braid] and [weaves][weave].

## Chord

A [chord][chord] is a [knit][knits] constructed using the capitalized [tone start][tone start] as the [root][root] and [threads][thread] for all other voices.

    ————————————————————————————————————————————————————————
        CHORD      WORD         IPA        TRANSLITERATION
    ————————————————————————————————————————————————————————
         B5        Zav         ˈzɑv            'ZAHV'
         Cm        Dov         ˈdov            'DOHV'
         C♯7       Fevn       ˈfe.vən        'FEH-vuhn'
         D13      Bevnuim   ˌbev.nuˈyim    'Behv-noo-YEEM'
      E♭13(♭5♯9)  Petnoim   ˌpet.noˈwim    'Peht-noh-WEEM'
    ————————————————————————————————————————————————————————


## Braid

A [braid][braid] is a “metachord”, like in Roman Numeral Analysis or the Nashville Number System. They are built exactly like [chords][chord] but use capitalized [threads][thread] as the starting [glyph][glyph].

    —————————————————————————————————————————————————————————
      KEY: da
    —————————————————————————————————————————————————————————
        CHORD      WORD         IPA        TRANSLITERATION
    —————————————————————————————————————————————————————————
         B5        Sav         ˈsɑv            'SAHV'
         Cm        Aov         ʔɑˈov          'ah-OHV'
         C♯7       Revn       ˈre.vən        'REH-vuhn'
         D13      Uevnuim  ʔuˌjev.nuˈjim  'oo-Yehv-noo-YEEM'
      E♭13(♭5♯9)  Oetnoim  ʔoˌwet.noˈwim  'oh-Weht-noh-WEEM'
    —————————————————————————————————————————————————————————

## Weave

A [weave][weave] is a specific voicing of a [chord][chord] or [braid][braid]. These get much more complicated looking, but they follow the same rules with two added details. First, no octave is specified, so the [span start][span start] of the lowest sounding voice is prefixed to the [chord][chord] or [braid][braid]. Second, no root is implied so every voice gets a thread.

    ——————————————————————————————————————————————————————————————————————————————————————
      COMMON GUITAR VOICINGS
      KEY: da
    ——————————————————————————————————————————————————————————————————————————————————————
      CHORD   TAB    THREADS    WORD            IPA             TRANSILITERATION
    ——————————————————————————————————————————————————————————————————————————————————————
        E    022100   avaeva  tWavaeva     təˌwɑ.vɑˈje.vɑ     tuh-Wah-vah-YEH-vah
                      avaeva  tEavaeva   təˌʔe.jɑ.vɑˈje.vɑ   tuh-Eh-yah-vah-YEH-vah
        A    x02220   avaev    sJavaev     səˌdʒa.vɑˈjev        suh-Jah-vah-YEHV
                      avaev    sMavaev      səˌma.vɑˈjev        suh-Mah-vah-YEHV
       A/E   002220   vavaev  sJvavaev    səˌdʒə.vɑ.vɑˈjev    suh-Juh-vah-vah-YEHV
                      vavaev  sMvavaev     səˌmə.vɑ.vɑˈjev    suh-Muh-vah-vah-YEHV
        D    xx0232    avae    sBavae       səˈbɑ.vɑˌje         suh-BAH-vah-Yeh
                       avae    sUavae      sə.ʔuˈjɑ.vɑˌje      suh-oo-YAH-vah-Yeh
       D/F♯  200232   evavae  tBevavae     tə.beˈvɑ.vɑˌje      tuh-beh-VAH-vah-Yeh
                      evavae  tUevavae   təˌʔu.jeˈvɑ.vɑˌje   tuh-Oo-yeh-VAH-vah-Yeh
        G    320033   aevava  sYaevava     səˌja.jeˈvɑ.vɑ      suh-Yah-yeh-VAH-vah
                      aevava  sVaevava     səˌvɑ.jeˈvɑ.vɑ      suh-Vah-yeh-VAH-vah
        G    320003   aevaea  sYaevaea   səˌjɑ.jeˈvɑ.jeˌjɑ   suh-Yah-yeh-VAH-yeh-Yah
                      aevaea  sVaevaea   səˌvɑ.jeˈvɑ.jeˌjɑ   suh-Vah-yeh-VAH-yeh-Yah
        C    x32010    aevae   sDaevae     sə.dɑˈje.vɑˌje      suh-dah-YEH-vah-Yeh
                       aevae   sAaevae   səˌʔɑ.jɑˈje.vɑˌje   suh-Ah-yah-YEH-vah-Yeh
       C/G   332010   vaevae  sDvaevae   səˌdə.vɑˈje.vɑˌje   suh-Duh-vah-YEH-vah-Yeh
                      vaevae  sAvaevae   səˌʔɑ.vɑˈje.vɑˌje   suh-Ah-vah-YEH-vah-Yeh
    ——————————————————————————————————————————————————————————————————————————————————————
***

# Cues

[Cues][cues] are composer directives, denoted by [glyph][glyph] `#`. In the Bourrée using [tones][tone] above, a [track][track]-level [cue][cues] is followed by the [chord][chord] E minor `Wov` to specify the [key][key], the [groove][groove] for four [beats][beats] `|4.|`, and all at an allegretto [click][click].

## Comp

A [comp][comp] is a minimally specified accompaniment and harmonic background written within the [bar][bar].

### Vamp

A [vamp][vamp] is a [comp][comp] that specifies rhythm and/or voicings.

## Tweak
 
A [tweak][tweak] is an instruction on effects that occur above the [voices][voice] they modify.

## Art

An [art][art] is an inline [cue][cues] each of which are denoted by special [glyphs][glyph] and rules.

### Smooth

A [smooth][smooth] line is legato, which is to be determined by each instrument. Such lines are bracketed by parentheses `(` `)`.

### Ring

A [ring][ring] shows [sounds][sounds] sustaining over other [sounds][sounds]. These begin with the [sound][sounds] (without any [hold][hold] if simultaneous, with if there is a delay) followed by curly brackets `{` `}` with the concurrent [sounds][sounds] notated bewteen them. The [hold][hold] for the outside [note][notes] is at least as long as the combined [holds][hold] within the curly brackets. [Bar][bar] 7 above can be notated both of the following ways:

    ————————————————————————————————————————————————
      7
        f| za.   ja.ya ka^^y.  ,ya, |
        t| yu.   do.   bo.   bo.    |      
      7
        | yu{za.} do{ja.ya} bo{ka^^y.} bo{aa.ya} |
    ————————————————————————————————————————————————

For [sounds][sounds] meant to sustain freely as they are played like when lifting the dampers on a piano, double curly brackets `{{` `}}` are used.

### Glide

A [glide][glide] is the smooth changing of a [sound][sounds] to a different [pitch][pitch], like a bend. `/` is for changing a [sound][sounds] up, `\` for changing a [sound][sounds] down.

### Slide

A [slide][slide] is the stepped changing of [sound][sounds] to a different [pitch][pitch] like a fret slide. `//` is for changing a [sound][sounds] up, `\\` for changing a [sound][sounds] down.

### Vibe

A [vibe][vibe] is a repeated fluctuation in the [pitch][pitch] of a [sound][sounds]. It is an [art][art] denoted by the [glyph][glyph] `~`.

### Grace

A [grace][grace] is the quick articulation of one [sound][sounds] before another. It is an [art][art] denoted with the starting [tone][tone] or [spans’s][span] [start][start] followed by the [glyph][glyph] `^` and the [tone][tone] or [span][span] to land on.

### Lick

A [lick][lick] is quick run of [sounds][sounds], often repeated. It is an [art][art] denoted with a starting [tone][tone] or [span][span] followed by a sequence of the [tone starts][tone start] or [span rhymes][span rhyme] separated by [grace][grace], [glide][glide], or [slide][slide] in the order they are articulated, finishing on a [tone][tone] or [span][span] or returning to the starting [tone][tone] or [span][span] if none are specified.

### Trill

A [trill][trill] is the quick alternating between two [sounds][sounds] used as ornamentation. It is an [art][art] denoted with the starting [tone][tone] or [span][span] a double [grace][grace] [glyph][glyph] `^^` followed by the [start][start] of the [tone][tone] or [span][span] to be alternated with.

## Drift

A [drift][drift] is a microtonal adjustment. These can be adjusted globally or inline. They are just like the [span rhymes][span rhyme] added to whole [spans][span] or [tones][tone].

    ————————————
      -t  +50
      -i  +42
      -e  +33
      -o  +25
      -u  +17
      -r  +8
      -a  ±0
      -x  -8
      -n  -17
      -m  -25
      -l  -33
      -v  -42
    ————————————

`da/hut` is a whole step and a quarter bend. `dat` is a C half-sharp.

Like with [weaves][weave], there are rules for pronounciation. Guide coming soon.

## Line

A [line][line] is a set of lyrics to be sung set below the [voice][voice] with its corresponding melody. It is enclosed in double straight quotes `"` with each syllable getting at least one [sound][sounds] and underscores `_` for multiple [sounds][sounds]. Speech is denoted by the [rap][rap] `sp` in the [voice][voice].

***

# Schemes

[Schemes][schemes] are informational diagrams to help learn and understand Counternote and the underlying music theory.

## Clock

A [clock][clock] is a [scheme][schemes] for visualizing the relationships between [tones][tone] or [spans][span]. Since there are twelve equal [tones][tone], only the [spans][span] as [span rhymes][span rhyme] are demonstrated here.

### Hue Clock

The [hue clock][hue clock] places [tones][tone] or [spans][span] in chromatic sequence around a clockface so that stepping clockwise goes up a [notch][notch] and counterclockwise goes down a [notch][notch].

    ————————————————————————————————————————————————
                                             NOTCH
                         1                    DIFF
               7        ha        ♭2            0
                 hs  ===||===  hr              ±1
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
               5        ht        4            +6
             BREAK ↑  ♯4/♭5
    ————————————————————————————————————————————————

### Lux Clock

Swapping every odd-numbered value with its counterpart (1 with 7, 3 with 9, 5 with 11) makes the [lux clock][lux clock] with all of the [spans][span] written in harmonic sequence around the clockface. All of the [bright luxes][bright lux] are on the right and all of the [dark luxes][dark lux] are on the left. The [blends][blend], [moods][mood], and [rubs][rub] slice the [lux clock][lux clock] horizontally into three sections. 

    —————————————————————————————————————————————————
       |-----DARK-----|    |----BRIGHT----|   LUX   
                         1
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
                  -r  ==||==  -s              RUBS
               ♭2       -t        7            |
                      ♭5/♯4                  —————
    —————————————————————————————————————————————————

### Lux

A [lux][lux] is a measure of how [bright][bright lux] or [dark][dark lux] an interval is. This lines up mostly with major (large) and minor (small) itervals but also includes the perfect fourth and fifth (dark and bright) respectively. Curiously, `-t` is both very dark and very bright at the same time.

### Bright Lux

A [bright lux][bright lux] is a harmonic relationship that evokes a sense of opening up, turning outward. It includes all major (large) intervals plus the (larger) perfect fifth.

### Dark Lux

A [dark lux][dark lux] is a harmonic relationhip that evokes a sense of settling down, turning inward. It includes all minor (small) intervals plus the (smaller) perfect fourth.

### Blend

A [blend][blend] is a more harmonious sounding interval: `-a`, `-u`, `-i`, `-v`, `-m`. They are the high vowels, some paired with labial consonants, plus the [root][root] which is an open vowel. If these were colors, they’d be neutrals that go with anything.

### Mood

A [mood][mood] is an interval that gives a major or minor quality: `-o`, `-e`, `-l`, `-n`. All are  mid vowels, some paired with alveolar consonants. If these were colors, they would be more saturated and vibrant, but not stridently so.

### Rub

A [rub][rub] is a dissonant interval that clashes with the root: `-r`, `-s`, `-t`. They are all the rhoticized vowels, some paired with alveolar consonants. If these were colors, they’d be best used as accents due to their intensity.

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

# Nibs

[Nibs][nibs] are the odd ends that fit in the odds and ends.

### Mark

A [mark][mark] is a single straight quote `'`. It serves as a separator.
