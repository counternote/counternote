***

# Counternote Specification version 0.8.0

This is a terse description of Counternote with definitions and examples.

***

# Gloss

This [gloss][gloss] serves as a glossary and table of contents for all things Counternote.

### [BASE][base]

Foundational elements of Counternote

* [__term__][term]: a precise concept in music and Counternote, linked here in the [gloss][gloss]
* [__glyph__][glyph]: any typed character in Counternote
* [__word__][word]: a connected sequence of [phones][phone]
* [__phone__][phone]: the pronunciation of a speakable [glyph][glyph] or cluster of [glyphs][glyph]
  * [__start__][start]: the first [phone][phone] or *linguistic onset* of a [word][word]
  * [__rhyme__][rhyme]: the rhyming part or *linguistic coda* of a [word][word]


### [FORM][form]

Structural elements of Counternote

* [__score__][score]: an entire composition in Counternote
* [__track__][track]: an individual piece within a score
* [__round__][round]: a block of repeated music
* [__bar__][bar]: a sequence of lines that detail what and how to play
* [__voice__][voice]: a monophonic [sound][sound] or sequence of [sounds][sound]

### [NOTE][note]

Acoustic vibrations held in time

* [__sound__][sound]: any acoustic vibration
  * [__pitch__][pitch]: the number of vibrations per second, the frequency
  * [__rank__][rank]: the set of pitches separated by powers of two, the pitch-class
  * [__file__][file]: the octave range that contains a pitch
  * [__band__][band]: any range of pitches
  * [__notch__][notch]: the range of a single *semitone* or *half-step*
* [__root__][root]: the starting point for a [span][span] and the like
* [__key__][key]: the starting point for a [track][track]
* [__break__][break]: the [rank][rank] where the [file][file] changes for a given [key][key]
* [__hold__][hold]: the duration of a [note][note]
* [__tone__][tone]: a [word][word] indicating the absolute [rank][rank] and [file][file] of a [sound][sound]
  * [__tone start__][tone start]: the [start][start] that denotes absolute [rank][rank]
  * [__tone rhyme__][tone rhyme]: the [rhyme][rhyme] that denotes [file][file]
* [__span__][span]: a [word][word] indicating the relative [rank][rank] and [file][file] of a [sound][sound]
  * [__span start__][span start]: the [start][start] that denotes [file][file]
  * [__span rhyme__][span rhyme]: the [rhyme][rhyme] that denotes relative [rank][rank]
* [__rap__][rap]: a [word][word] indicating a [sound][sound] where [pitch][pitch] is indeterminate or incidental
* [__tie__][tie]: a [sound][sound] from a previous [bar][bar] is still being held
* [__breath__][breath]: a breath of fresh quiet
* [__stop__][stop]: two [sounds][sound] occuring at the same time.

### [KNIT][knit]

* [__thread__][thread]:
* [__chord__][chord]:
* [__braid__][braid]:
* [__weave__][weave]:

[gloss]: #gloss

[base]: #base

[term]: #term
[glyph]: #glyph
[word]: #word
[phone]: #phone
  [start]: #start
  [rhyme]: #rhyme

[form]: #form

[score]: #score
[track]: #track
[round]: #round
[bar]: #bar
[voice]: #voice

[note]: #note

[sound]: #sound
  [pitch]: #pitch
  [rank]: #rank
  [file]: #file
  [band]: #band
  [notch]: #notch
[root]: #root
[key]: #key
[break]: #break
[hold]: #hold
[tone]: #tone
  [tone start]: #tone-start
  [tone rhyme]: #tone-rhyme
  [tie]: #tie
[span]: #span
  [span start]: #span-start
  [span rhyme]: #span-rhyme
[rap]: #rap
[tie]: #tie
[stop]: #stop

[knit]: #knit

[thread]: #thread
[chord]: #chord
[braid]: #braid
[weave]: #weave

***

# Base

A [base][base] is a foundational element for learning and understanding Counternote.

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

A [word][word] is connected sequence of [phones][phone] that can be spoken like the [tone][tone] `da`.

## Phone

A [phone][phone] is an indivisible articulation of spoken Counternote represented by one or two [glyphs][glyph] and up to three phonemes.

### Start

The standard consonants with their points of articulation are as follows:

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
       Y,y      ʒ    'si' in 'vision'
        -       j     'y' in 'yes'
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
        hy-     hʲ       'hy'
        hw-     hʷ       'hw'
    ————————————————————————————————

### Rhyme

Vowels are pure spanish vowels plus the rhoticized mid vowel 'r':

    ————————————————————————————————
      GLYPH    IPA   PRONUNCIATION
        a       ɑ        'ah'
        r      ɚ,r̩       'er'
        u       u        'oo'
        o       o        'oh'
        e       e        'eh'
        i       i        'ee'
        -       ə        'uh'
    ————————————————————————————————

The schwa 'ə' is inserted between consonants in some instances, but there is no corresponding [glyph][glyph].

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

# Form

A [form][form] is a structural element of a composition and how such elements connect together.

## Score

A [score][score] is an entire composition in Counternote.

## Track

A [track][track] is an individual piece that may or may not occur simultaneously within a score.

## Round

A [round][round] is a block of repeated music marked with an unindented letter or string on its own line for legibility.

## Bar

A [bar][bar] contains all of the details of what to play when and how to play it marked with a two-space indentation on its own line, again for legibility.

## Voice

A [voice][voice] is akin to a line of music performed by a human *voice*. [Knits][knit] are multiple [voices][voice] even if performed by the same instrument.

***

# Note

A [note][note] is a [sound][sound] for a [hold][hold].

## Sound

A [sound][sound] is any acoustic vibration fit to be notated. They come in three varieties: [tones][tone], [spans][span], and [raps][rap]. The first two deal with those of definite [pitch][pitch], [tones][tone] in an absolute way and [spans][span] in a relative way, whereas [raps][rap] deal with those of indefinite or incidental [pitch][pitch].

### Pitch

A [pitch][pitch] is the number of vibrations per second, the frequency.

### Rank

A [rank][rank] is like all traditional *notes* regardless of octave, also known as the pitch-class, the set of pitches separated by powers of two. These are written as [tones][tone] with the '-a' [rhyme][rhyme] such as `da` for *C* or [spans][span] with the 'h-' [start][start] such as `ha` for *C* in the [key][key] of `da`.

### File

A [file][file] is analogous to the octave number, for instance the [band][band] from 256Hz to 512Hz.

### Band

A [band][band] is a defined range of frequencies with the lower bound inclusive and the upper bound exclusive.

### Notch

A [notch][notch] is a [band][band] a twelth root of two wide, a traditional *semitone* or *half-step*.

## Root

A [root][root] is the [tone][tone] that serves as the starting point for harmony within [spans][span] and chords.

## Key

A [key][key] is like a [root][root] but for an entire composition denoted by a [tone][tone]. By default it’s `da`. It does not imply a particular scale.

## Break

A [break][break] is the point where the [file][file] changes based on the [key][key] of a composition. It is always at seven [notches][notch] above and six [notches][notch] below. A [break][break] changes only when the [key][key] explicitly changes.

## Hold

A [hold][hold] is punctuation character that represents a duration. They come in eight varieties, six ordered by powers of two and two special ones for no duration and indefinite duration that can also have articulation properties:

    —————————————————————————————
      `!`   bang    0x duration
    —————————————————————————————
      `;`   shred   1x duration
      `:`   split   2x duration
      `,`   fast    4x duration
      `.`   short   8x duration
      `-`   long   16x duration
      `=`   slow   32x duration
    —————————————————————————————
      `?`   broad   ?x duration
    —————————————————————————————

## Tone

A [tone][tone] is closest to a *note* in a traditional sense, like the [rank][rank] of *C* or a specific C note. Any [pitch][pitch] that when multiplied or divided by powers of two falls in the [notch][notch] starting from 256Hz is described by the [rank][rank] `da`. That means any [pitch][pitch] that falls in the [notch][notch] from about 430.5Hz to just over 456Hz is `ja` including *A440*, *A444*, and *A432*, which does not include the baroque tuning *A415*, falling into the [rank][rank] just below called `xa`.

### Tone Start

The [start][start] of a [tone][tone] will always be a consonant represented by a single [glyph][glyph]. Each is identified with a single [rank][rank].

    ————————————————
      START  VALUE
    ————————————————
        p-   D♯/E♭
        b-     D
        f-   C♯/D♭
        d-     C
        z-     B
        c-   A♯/B♭
        j-     A
        x-   G♯/A♭
        y-     G
        k-   F♯/G♭
        g-     F
        w-     E
    ————————————————

### Tone Rhyme

The [rhyme][rhyme] of a [tone][tone] is all but the [start][start], also known as the rhyming part (linguistic coda). It represents the [file][file] of the [tone][tone]. The exact [pitch][pitch] a [file][file] lines up with is flexible, but by default, `da` is middle C in all [keys][key]. `-a` can also refer to all [files][file] of a [rank][rank].

    ————————————————
      RHYME   FILE
    ————————————————
       -il     +5
       -al     +4
       -l      +3
       -i      +2
       -e      +1
    ————————————————
       -a      ±0
    ————————————————
       -o      -1
       -u      -2
       -r      -3
       -ar     -4
       -or     -5
    ————————————————

## Span

A [span][span] is an interval *and* a distinct [tone][tone] relative to some [root][root] or [key][key]. For instance, `la` is both an octave interval *and* whatever [tone][tone] is one octave above the [root][root]. The [span start][span start] stretches for one octave with the [break][break] in the same place as the [tone rhyme][tone rhyme].

### Span Start

The [start][start] of a [span][span] indicates the [file][file] above or below the [root][root] or [key][key].

    ———————————————
      START  FILE
    ———————————————
       hy-    +5
       m-     +4
       v-     +3
       l-     +2
       t-     +1
    ———————————————
       h-     ±0
    ———————————————
       n-     -1
       s-     -2
       r-     -3
       q-     -4
       hw-    -5
    ———————————————


### Span Rhyme

The [rhyme][rhyme] of a [span][span] tells the interval from a [root][root] or [key][key]. The quality of the vowel tells the distance from the its starting point while a terminating consonant (excluding `-r` which is treated as a vowel in this case) means it’s an interval closest to the [root][root] from below. For brevity and symmetry, only the final [glyph][glyph] of the [rhyme][rhyme] is written.


    ——————————————————————————————————————————
      RHYME   VALUE    IPA   TRANSLITERATION
    ——————————————————————————————————————————
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
    ——————————————————————————————————————————

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

A [stop][stop] is two [voices][voices] sounding simultaneously. They can be written by concatenating a [span] onto a [tone][tone] or [span][span] [root][root].

    ————————————————————————————————
      WORD      VALUE        IPA
      dahr    minor 2nd      dɑhɚ
      dahu    major 2nd      dɑhu
      daho    minor 3rd      dɑho
      dahe    major 3rd      dɑhe
      dahi   perfect 4th     dɑhi
      daht  diminished 5th  dɑhɑ˞t
      dahv   perfect 5th    dɑhiv
      dahl    minor 6th     dɑhel
      dahm    major 6th     dɑhom
      dahn    minor 7th     dɑhun
      dahs    major 7th     dɑhɚs
    ————————————————————————————————

[Raps][rap] can also be performed at the same time, but concatenating them together without some sort of separator gets really hard to read, so a mark `'` is placed in between them. These can be combined with [tones][tone] and [spans][span] for percussive playing.

    —————————————————————————————————————
      WORD             VALUE
      bm'xd   bass drum + closed hi-hat
      ck'kl       shook + clap
      rk'we        rake + high E
    —————————————————————————————————————

***

# Knit

A [knit][knit] is a collection of notes occuring simultaneously. While such can be achieved with [stops][stop], it quickly gets unruly and hard to read. [Knits][knit] come in three varieties: [chords][chord], [braids][braid], and [weaves][weave].

## Thread

A [thread][thread] is a single [voice][voice] within a [knit][knit]. They are the [glyphs][glyph] for the [span rhymes][span rhyme] without the extra vowel content attached to the consonants. Because vowels can cluster with vowels (`VV`) and consonants with consonants (`CC`), there are some additional rules for pronunciation:

    —————————————————————————————————
      V:  a,r,u,o,e,i
      C:  t,v,l,m,n,s
      G:  any glyph
      X:  end of string
      -:  syllable break
    —————————————————————————————————
      GLYPH  BEFORE   ADDS    IPA
        a      V     soft y   a-jV
        r      V       w      a-wV
        u      V     soft y   u-jV
        o      V       w      o-wV
        e      V     soft y   e-jV
        i      V       w      i-wV
    —————————————————————————————————
        VC     CV      -     VC-CV
        VC     CC      ə     VC-CəC
        VC     CX      ə     V-CəC
    —————————————————————————————————

The [glyph][glyph] `r` as a thread is always its vowel [phone][phone] except when capitalized in [braids][braid] and [weaves][weave].

## Chord

A [chord][chord] is a [knit][knit] constructed using the capitalized [tone start][tone start] as the [root][root] and [threads][thread] for all other voices.

    ————————————————————————————————————————————————————————
        CHORD      WORD         IPA        TRANSLITERATION
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
         B5        Sav         ˈsɑv            'SAHV'
         Cm        Aov         ʔɑˈov          'ah-OHV'
         C♯7       Revn       ˈre.vən        'REH-vuhn'
         D13      Uevnuim  ʔuˌjev.nuˈjim  'oo-Yehv-noo-YEEM'
      E♭13(♭5♯9)  Oetnoim  ʔoˌwet.noˈwim  'oh-Weht-noh-WEEM'
    —————————————————————————————————————————————————————————

## Weave

A [weave][weave] is a specific voicing of a [chord][chord] or [braid][braid]. These get much more complicated looking, but they follow the same rules with two added details. First, no octave is specified, so the [span start][span start] of the lowest played sounding voice is prefixed to the [chord][chord] or [braid][braid]. Second, no root is implied so every voice gets a thread.

    ——————————————————————————————————————————————————————————————————————————————————————
      COMMON GUITAR VOICINGS
      KEY: da
    ——————————————————————————————————————————————————————————————————————————————————————
      CHORD   TAB    THREADS    WORD            IPA             TRANSILITERATION
        E    022100   avaeva  sWavaeva     səˌwa.vaˈje.va     suh-Wah-vah-YEH-vah
                      avaeva  sEavaeva   səˌʔe.ja.vaˈje.va   suh-Eh-yah-vah-YEH-vah
        A    x02220   avaev    nJavaev     nəˌdʒa.vaˈjev        nuh-Jah-vah-YEHV
                      avaev    nMavaev      nəˌma.vaˈjev        nuh-Mah-vah-YEHV
       A/E   002220   vavaev  nJvavaev    nəˌdʒə.va.vaˈjev    nuh-Juh-vah-vah-YEHV
                      vavaev  nMvavaev     nəˌmə.va.vaˈjev    nuh-Muh-vah-vah-YEHV
        D    xx0232    avae    nBavae       nəˈba.vaˌje         nuh-BAH-vah-Yeh
                       avae    nUavae      nə.ʔuˈja.vaˌje      nuh-oo-YAH-vah-Yeh
       D/F♯  200232   evavae  sBevavae     sə.beˈva.vaˌje      suh-beh-VAH-vah-Yeh
                      evavae  sUevavae   səˌʔu.jeˈva.vaˌje   suh-Oo-yeh-VAH-vah-Yeh
        G    320033   aevava  nYaevava     nəˌʒa.jeˈva.va     nuh-Zhah-yeh-VAH-vah
                      aevava  nVaevava     nəˌva.jeˈva.va      nuh-Vah-yeh-VAH-vah
        G    320003   aevaea  nYaevaea   nəˌʒa.jeˈva.jeˌja  nuh-Zhah-yeh-VAH-yeh-Yah
                      aevaea  nVaevaea   nəˌva.jeˈva.jeˌja   nuh-Vah-yeh-VAH-yeh-Yah
        C    x32010    aevae   nDaevae     nə.daˈje.vaˌje      nuh-dah-YEH-vah-Yeh
                       aevae   nAaevae   nəˌʔa.jaˈje.vaˌje   nuh-Ah-yah-YEH-vah-Yeh
       C/G   332010   vaevae  nDvaevae   nəˌdə.vaˈje.vaˌje   nuh-Duh-vah-YEH-vah-Yeh
                      vaevae  nAvaevae   nəˌʔa.vaˈje.vaˌje   nuh-Ah-vah-YEH-vah-Yeh
    ——————————————————————————————————————————————————————————————————————————————————————

***
