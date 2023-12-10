***

Counternote is a chromatic musical language meant to be typed and sung.

# Drive

Counternote is an answer to a question that a lot of people have asked despite a solid solution already existing — namely, is there a [Markdown][md] for music, by which they mean a human readable plaintext music notation? The answer is yes: it’s called [ABC notation][abc], and it’s great. If that’s all you are looking for, you do not need to read more. Go support it!

However, ABC notation is not a music notation directly. It’s a music notation *notation* with another layer of translation (music —> staff —> ABC). Counternote is a different kind of abstraction from western music notation, a linguistic one, not a visual one, so it can be written in plaintext directly (music —> Counternote).

Counternote has been created as a complementary foil to the venerable staff notation, so that even the most seasoned of musicians is likely to gain a deeper understand of the craft of music by learning it.

[md]:https://daringfireball.net/projects/markdown/ "John Gruber’s Markdown Spectacular"
[abc]:https://abcnotation.com/ "ABC notation"

# Design

There are five design principles that guide Counternote’s take on a musical notation: It must be readable, typeable, singable, codeable, and shareable. Unfortunately, satisfying all five of these constraints perfectly is impossible. Design is compromise just as life is pain — *anyone who tells you differently is selling something*.

For readability, the notes are simple and unambiguous — a note never has more than one name and is descriptive enough to make some intuitive and logical sense. The same goes for intervals and chords. They are organized in a way that can be sightread rather easily while still allowing for durations and articulations to appear in the same line like punctuation while dynamics, accompaniments, and other details appear in parallel above or below the line to avoid clutter. 

For typeability, everything is written in the printable characters of 7-bit ASCII which are easily typed by humans. The notes require as few keystrokes as possible, both to make typing faster and to take up less space on the line. In the process of compressing the written length of the notes, some characters have had their pronunciation reassigned and common digraphs have been eliminated, limiting them to just one consonant, vowel, or vowel-consonant pair per character.

For singability, each note is one syllable, as are each interval distinct from the notes. The simple idea here is that music is not an abstract notion, it’s something that we can mimic concretely. So these elements are onomatopoeic and autological — that is, imitative and self-descriptive. The closer a symbol is to its actual pronounciation and meaning, the easier it is to remember. But notes are more than just hitting a correct pitch — they’re about any kind of vocalization, so the percussive sounds like those from beatboxing to click languages find representation here.

For codeability, everything is written in ASCII which is easily interpretted by computers and backed up with git. However, great care has been taken to make notational aspects not feel like code. Raw numbers for duration and pitch have been eliminated — the few numbers that exist in the notation are ordinal numerals and a quick way to count the notes in a tuplet. No function invocations are necessary to make a sound. The control flow is simpler than staff notation.

For shareability, everything is just a string of plaintext, easily shared via text message and read in monospace. There is no need to translate it into a human consummable format and back to a computer-readable one, no heavy filetype to send and store, no binary blobs to contend with. What you see it what you get.
