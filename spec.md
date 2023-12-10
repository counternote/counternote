***

# Counternote Specification version 0.8.1

This is a terse description of Counternote with minimal definitions and examples. Musical ideas not expressed here are likely already done, at least aspirationally, just not written here.

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
* [__round__][round]: a block of repeated music
* [__bar__][bar]: details on how and what to play
  * [__voice__][voice]: a monophonic instrument and the sequence of [sounds][sound] to be played
  * [__stack__][stack]: multiple [voices][voice] in the same [bar][bar]
  * [__jump__][jump]: a directive on what to play next
  * [__lap__][lap]: a variation on a [bar][bar]

### [BEATS][beats]

Rhythmic elements

* [__hold__][hold]: the duration of a [note][notes]
* [__groove__][groove]: the arrangement of [beats][beats] in a [bar][bar]
* [__click__][click]: the tempo
* [__cut__][cut]: a tuplet
* [__shift__][shift]: a section of polymeter
* [__rift__][rift]: a section of polyrhythm

### [NOTES][notes]

Acoustic vibrations held in time

* [__sound__][sound]: any acoustic vibration
  * [__pitch__][pitch]: the number of vibrations per second, the frequency
  * [__rank__][rank]: the set of [pitches][pitch] separated by powers of two, the pitch-class
  * [__file__][file]: the octave range that contains a [pitch][pitch]
  * [__band__][band]: any range of [pitches][pitch]
  * [__notch__][notch]: the range of a single *semitone* or *half-step*
* [__root__][root]: the centerpoint for a [span][span] and the like
* [__key__][key]: the centerpoint for [tones][tone] and [spans][span]
* [__break__][break]: the [rank][rank] where the [file][file] changes for a given [key][key]
* [__tone__][tone]: a [word][word] indicating the absolute [rank][rank] and [file][file] of a [sound][sound]
  * [__tone start__][tone start]: the [start][start] that denotes absolute [rank][rank]
  * [__tone rhyme__][tone rhyme]: the [rhyme][rhyme] that denotes [file][file]
* [__span__][span]: a [word][word] indicating the relative [rank][rank] and [file][file] of a [sound][sound]
  * [__span start__][span start]: the [start][start] that denotes [file][file]
  * [__span rhyme__][span rhyme]: the [rhyme][rhyme] that denotes relative [rank][rank]
* [__rap__][rap]: a [word][word] indicating a [sound][sound] where [pitch][pitch] is indeterminate or incidental
* [__tie__][tie]: a [sound][sound] from a previous [bar][bar] is still being held
* [__breath__][breath]: a breath of fresh quiet
* [__stop__][stop]: two [sounds][sound] occuring at the same time

### [KNITS][knits]

Manifold acoustic vibrations

* [__thread__][thread]: a single [voice][voice] within a [knit][knits]
* [__chord__][chord]: a [knit][knits] constructed using [tones][tone] as a starting point
* [__braid__][braid]: a [knit][knits] constucted using [spans][span] as a starting point to make “metachords”
* [__weave__][weave]: a [chord][chord] or [braid][braid] with the exact voicing

### [CUES][cues]

Composer directives

* [__art__][art]: an inline cue
  * [__smooth__][smooth]: a legato line
  * [__ring__][ring]: a sustained line
  * [__vibe__][vibe]: a repeated fluctuation in [pitch][pitch] of a [sound][sound]
  * [__grace__][grace]: a quick [sound][sound] before another
  * [__trill__][trill]: a quick alternating between [sounds][sound]

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
* [__tap__][tap]: [words][word] for vocalizing rhythms and [grooves][groove]

### [NIBS][nibs]

Odds and ends

  * [__head__][head]: the start of a [score][score] term `++*`
  * [__mid__][mid]: the [track][track] and [stage][stage] separator term `+++`
  * [__tail__][tail]: the end of a [score][score] term `*++`
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
[round]: #round
[bar]: #bar
  [voice]: #voice
  [stack]: #stack
  [lap]: #lap
[jump]: #jump

[beats]: #beats

[hold]: #hold
[groove]: #groove
[click]: #click
[cut]: #cut
[shift]: #shift
[rift]: #rift

[notes]: #notes

[sound]: #sound
  [pitch]: #pitch
  [rank]: #rank
  [file]: #file
  [band]: #band
  [notch]: #notch
[root]: #root
[key]: #key
[break]: #break
[tone]: #tone
  [tone start]: #tone-start
  [tone rhyme]: #tone-rhyme
  [tie]: #tie
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

[art]: #art
  [smooth]: #smooth
  [ring]: #ring
  [vibe]: #vibe
  [grace]: #grace
  [trill]: #trill

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

  [head]: #head
  [mid]: #mid
  [tail]: #tail
  [mark]: #mark

***

# Bases

[Bases][bases] are a foundational element for learning and understanding Counternote.

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

A [sign][sign] is connected sequence of [glyphs][glyph] do not make a [word][word] like the head `++*`.

## Phone

A [phone][phone] is an indivisible articulation of spoken Counternote represented by one or two [glyphs][glyph] and up to three phonemes.

### Start

A [start][start] is the first [phone][phone] or *linguistic onset* of a [word][word]. All of these sounds are found in American English, but the letters 

The standard starting consonants with their points of articulation are as follows:

    ——————————————————————————————————
      GLYPH    IPA    PRONUNCIATION
      ~~~~~~ BILABIAL ~~~~~~~~~~~~~
       M,m      m     'm' in 'muse'
       B,b      b     'b' in 'bow'
       P,p      p     'p' in 'pick'
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
      ~~~~~~ PALATAL ~~~~~~~~~~~~~~
       X,x      ʃ    'sh' in 'ship'
       Y,y      j     'y' in 'yes'
       R,r     ɹ,r    'r' in 'run'
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

[Forms][forms] are structural elements of a composition and how such elements connect together. Here is the A-section of Bourrée by Bach:

    ++*
    SCORE: Lute Suite in E Minor BWV 996
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
        t| yu.     ju.     zo.     ju,     |
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

## Score

A [score][score] is an entire composition in Counternote. It is enclosed in the [head][head] `++*` and the [tail][tail] `*++` signs. When detailed in the [stage][stage], it is the title of work.

## Stage

A [stage][stage] holds compositional and instrumental details on entire [scores] and individual [tracks] such as title, author, instrument voices and tunings, and the like. The [score][score] [stage][stage] is between the [head][head] `++*` and the [mid][mid] `+++` signs. The [track][track] [stage][stage] is between [mid][mid] `+++` signs.

### Scribe

A [scribe][scribe] is a composer of a [score][score] or [track][track].

## Track

A [track][track] is an individual piece that may or may not occur simultaneously within a score. The are separated with mid `+++` signs.

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

A [cut][cut] is a subdivision of the [beat][beats].

## Shift

A [shift][shift] is a section of polymeter.

## Rift

A [rift][rift] is a section of polyrhythm.

***

# Notes

[Notes][notes] are [sounds][sound] for a [hold][hold].

## Sound

A [sound][sound] is any acoustic vibration fit to be notated. They come in three varieties: [tones][tone], [spans][span], and [raps][rap]. The first two deal with those of definite [pitch][pitch], [tones][tone] in an absolute way and [spans][span] in a relative way, whereas [raps][rap] deal with those of indefinite or incidental [pitch][pitch].

### Pitch

A [pitch][pitch] is the number of vibrations per second, the frequency.

### Rank

A [rank][rank] is like all traditional *notes* regardless of octave, also known as the pitch-class, the set of pitches separated by powers of two. These are written as [tones][tone] with the `-a` [rhyme][rhyme] such as `da` for *C* or [spans][span] with the `h-` [start][start] such as `ha` for *C* in the [key][key] of `da`.

### File

A [file][file] is analogous to the octave number, for instance the [band][band] from 256Hz to 512Hz.

### Band

A [band][band] is a defined range of frequencies with the lower bound inclusive and the upper bound exclusive.

### Notch

A [notch][notch] is a [band][band] a twelth root of two wide, a traditional *semitone* or *half-step*.

## Root

A [root][root] is the [tone][tone] or [span][span] that serves as the centerpoint for harmony within [spans][span] and [chords][chord].

## Key

A [key][key] is the centerpoint for [tones][tone] and [spans][span] of a [track][track]. It is like a [root][root] but for an entire composition denoted by a [tone][tone]. By default it’s `da` which does not imply a particular tonality. If a [chord][chord] is used, it will imply the following:

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

## Break

A [break][break] is the point where the [file][file] changes based on the [key][key] of a composition. It is always at seven [notches][notch] above and six [notches][notch] below. A [break][break] changes only when the [key][key] explicitly changes.

## Tone

A [tone][tone] is closest to a *note* in a traditional sense, like the [rank][rank] of *C* or a specific C note. Any [pitch][pitch] that when multiplied or divided by powers of two falls in the [notch][notch] starting from 256Hz is described by the [rank][rank] `da`. That means any [pitch][pitch] that falls in the [notch][notch] from about 430.5Hz to just over 456Hz is `ja` including *A440*, *A444*, and *A432*, which does not include the baroque tuning *A415*, falling into the [rank][rank] just below called `xa`.

### Tone Start

The [start][start] of a [tone][tone] will always be a consonant represented by a single [glyph][glyph]. Each is identified with a single [rank][rank]. The traditional “naturals” are voiced consonants and the “accidentals” voiceless. The points of articulation move from the back of the mouth up through to the lips (labiovelar —> velar —> palatal —> postalveolar —> alveolar —> labiodental —> bilabial).

    —————————————————————
      START  VALUE  IPA
    —————————————————————
        p-   D♯/E♭   p
        b-     D     b
        f-   C♯/D♭   f
        d-     C     d
        z-     B     z
        c-   A♯/B♭   tʃ
        j-     A     dʒ
        x-   G♯/A♭   ʃ
        y-     G     j
        k-   F♯/G♭   k
        g-     F     g
        w-     E     w
    —————————————————————

### Tone Rhyme

The [rhyme][rhyme] of a [tone][tone] is all but the [start][start], also known as the rhyming part (linguistic coda). It represents the [file][file] of the [tone][tone]. The exact [pitch][pitch] a [file][file] lines up with is flexible, but by default, `da` is middle C in all [keys][key]. `-a` can also refer to all [files][file] of a [rank][rank].

    ————————————————————
      RHYME  FILE  IPA
    ————————————————————
       -il    +5    il
       -al    +4    al
       -l     +3    ɛl
       -i     +2    i
       -e     +1    e
    ————————————————————
       -a     ±0    ɑ
    ————————————————————
       -o     -1    o
       -u     -2    u
       -r     -3    ɚ
       -ar    -4    ɑ˞
       -or    -5    ɔ˞
    ————————————————————

## Span

A [span][span] is an interval *and* a distinct [tone][tone] relative to some [root][root] or [key][key]. For instance, `ta` is both an octave interval *and* whatever [tone][tone] is one octave above the [root][root]. The [span start][span start] stretches for one octave with the [break][break] in the same place as the [tone rhyme][tone rhyme].

### Span Start

The [start][start] of a [span][span] indicates the [file][file] above or below the [root][root] or [key][key].

    ————————————————————
      START  FILE  IPA
    ————————————————————
       my-    +5    mʲ  
       mw-    +4    mʷ
       m-     +3    n
       v-     +2    v
       l-     +1    l
    ————————————————————
       h-     ±0    h
    ————————————————————
       t-     -1    t
       s-     -2    s
       n-     -3    n
       ny-    -4    nʲ
       nw-    -5    nʷ
    ————————————————————


### Span Rhyme

The [rhyme][rhyme] of a [span][span] tells the interval from a [root][root] or [key][key]. The quality of the vowel tells the distance from the its starting point while a terminating consonant (excluding `-r` which is treated as a vowel in this case) means it’s an interval closest to the [root][root] from below. For brevity and symmetry, only the final [glyph][glyph] of the [rhyme][rhyme] is written.


    ————————————————————————————————————————
      RHYME   VALUE    IPA   PRONUNCIATION
    ————————————————————————————————————————
        -s      7     ɚs,r̩s      'ers'
        -n     ♭7       un       'oon'
        -m      6       om       'ohm'
        -l     ♭6     ɛl,el      'ehl'
        -v      5       iv       'eev'
        -t    ♯4/♭5  ɑ˞t,art     'art'
        -i      4       i        'ee'
        -e      3      ɛ,e       'eh'
        -o     ♭3       o        'oh'
        -u      2       u        'oo'
        -r     ♭2      ɚ,r̩       'er'
        -a      1       ɑ        'ah'
    ————————————————————————————————————————

## Rap

A [rap][rap] is any sound where [pitch][pitch] is indeterminate or incidental. Rather than having some algorithmic way of bulding these, [raps][rap] are just a simple, user-definable lookup table with the caveat that they cannot conflict with [tones][tone] or [spans][span]. These are some of the proposed [raps][rap]:

    ————————————————————————
      `aa` tie
      `hh` breath (rest)
      `hx` hush, silence
      `nh` inhale
      `xh` exhale
      `xs` blue noise
      `xx` white noise
      `xw` pink noise
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
      `rk` rake
      `dp` deep tap
      `tp` light tap
      `dk` dark tick
      `tk` bright tick
      `dt` bright clave
      `dd` dark clave
      `rf` ref whistle
      `ws` Wilhelm scream
      `ck` shook
      `cp` chirp, cheep
      `jz` the licc
      `hd` handmute
      `sd` strum mute
    ————————————————————————

## Tie

A [tie][tie] is a [rap][rap] used to show a [sound][sound] from a previous [bar][bar] is still being held. It is notated with the [word][word] `aa` and not pronounced separately from the [sound][sound] being held.

## Breath

A [breath][breath] is a [rap][rap] that gives the player room to breathe. It is notated with the [word][word] `hh` and not explicitly pronounced.

## Stop

A [stop][stop] is two [voices][voice] sounding simultaneously. They can be written by concatenating a [span] onto a [tone][tone] or [span][span] [root][root].

    ————————————————————————————————
      WORD      VALUE        IPA
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

[Cues][cues] are composer directives, denoted by [glyph][glyph] `#`. Above, it is followed by the [word][word] for the [key][key] of E minor `Wov`, the [groove][groove] for four [beats][beats] `|4.|`, all at an allegretto [click][click].

## Art

An [art][art] is an inline [cue][cue] each of which are denoted by special [glyphs][glyph] and rules.

### Smooth

A [smooth][smooth] line is legato, which is to be determined by each instrument. Such lines are bracketed by parentheses `(` `)`.

### Ring

A [ring][ring] line shows [sounds][sound] sustaining over other [sounds][sound]. Such lines begin with the [sound][sound] with or without any [hold][hold] followed by curly brackets `{` `}` with the simultaneous [sounds][sound] notated bewteen them. The [hold][hold] lasts as long as the combined [holds][hold] within the curly brackets. [Bar][bar] 7 above can be notated both of the following ways:

      7
        f| za.     ja, ya, ka^^y.  ,   ya, |
        t| yu.     do.     bo.     bo.     |

      7
        | yu{za.} do{ja, ya,} bo{ka^^y.} bo{aa, ya,} |

For [sounds][sound] meant to sustain freely as they are played like when lifting the dampers on a piano, double curly brackets `{{` `}}` are used.

### Vibe

A [vibe][vibe] is a repeated fluctuation in the [pitch][pitch] of a [sound][sound]. It is an [art][art] denoted by the [vibe][vibe] [glyph][glyph] `~`.

### Grace

A [grace][grace] is the quick articulation of one [sound][sound] before another. It is an [art][art] denoted with the starting [tone][tone] or [spans’s][span] [start][start] followed by the [grace][grace] [glyph][glyph] `^` and the [tone][tone] or [span][span] to land on.

### Trill

A [trill][trill] is the quick alternating between two [sounds][sound] used as ornamentation. It is an [art][art] denoted with the starting [tone][tone] or [span][span] a double [grace][grace] [glyph][glyph] `^^` followed by the [start][start] of the [tone][tone] or [span][span] to be alternated with.

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
                      ♯4/♭5
             BREAK ↑ 
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

### Head

A [head][head] is the term `++*` that opens a Counternote document.

### Mid

A [mid][mid] is the term `+++` that separates [tracks][track] and [stages][stage].

### Tail

A [tail][tail] is the term `*++` that closes a Counternote document. All other input will be ignored.

### Mark

A [mark][mark] is a single straight quote `'`. It serves as a separator.
