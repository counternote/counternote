    /*
    Counternote Grammar 0.10.2
    Work in Progress
    */

    Score ::= '++*' Set? ( NEWLINE | ( Track '+++' ) )+ Track '*++'
    Set ::= ( NEWLINE | Prop )+ NEWLINE '+++'
    Track ::= Stage? ( NEWLINE | Round | Bar | Voice )+ '+++'?
    Stage ::= ( NEWLINE | Prop )+ NEWLINE '***'
    Round ::= NAME DENT Bar+
    Bar ::= Number DENT ( Cue NEWLINE )* ( Voice NEWLINE )* Voice
    Voice ::= name '|' SPACE+ Phrase '|'
    Phrase ::= ( ( Art | Cut | Note )+ ( Art | Click )* )+
    Prop ::= NAME ':' ( DENT? .+ )+
    Art ::= Smooth | Ring | Hold | '*' | '&' | '^' | '^^' | '/' | '//' | '\' | '\\' | '$' | '~'
    Smooth ::= '(' Phrase ')'
    Ring ::= '{' Phrase '}'
    Hold ::= '{{' Phrase '}}'
    Line ::= '[' Phrase ']'
    Cut ::= ( Note Click )+ Note
    Note ::= Art* ( Tone | Strand | Braid ) Art* Click Art*
    Tone ::= ToneStart ToneRhyme
    ToneStart ::= [mkdsjlhncztg]
    ToneRhyme ::= [qruoaeily]
    Rap ::= 'hh' | 'sw' | 'rp' 
    Click ::= [!;:,.] | '-' | [=?] | Tie
    Tie ::= '++'
    Span ::= SpanStart Thread | Same 
    Same ::= 'aa'
    SpanStart ::= [bfwyxr]
    Thread ::= [aruoeiqvlmnzx]
    Strand ::= Tone Span
    Knit ::= Chord | Braid
    Chord ::= Thread? KNITSTART Thread+
    Braid ::= Tone KNITSTART Thread+
    TONE ::= TONESTART TONERHYME
    TONESTART ::= [MKDSJLHNCATG]
    TONERHYME ::= [QRUOAEILY]
    KNITSTART ::= TONESTART | 'X'
    SPANSTART ::= [BFWYXR]
    THREAD ::= [ARUOEIQVLMNZX]
    STRAND ::= ( SPANSTART SPAN | SAME )
    SAME ::= 'AA'
    CHORD ::= ( TONESTART | 'X' ) THREAD+
    DENT ::= NEWLINE SPACE+
    NAME ::= [A-Z_][A-Z0-9_]*
    Name ::= [A-Za-z_][A-Za-z0-9_]*
    name ::= [a-z]*
    Number ::= [0-9XYZ]+
    SPACE ::= ' ' | '\t'
    NEWLINE ::= '\n'