=MusicDoc

MusicDoc is a simple but powerful markup format for musical scores and partitures.
It is inspired by https://asciidoc.org/[AsciiDoc] and https://www.chordpro.org/[ChordPro].

The key principle of MusicDoc is simplicity!
Just write your lyrics and add some simple notation markup for chords, notes, bars, breaks, etc.

This makes MusicDoc different from musical formats such as https://www.musicxml.com/[MusicXML] and even https://en.wikipedia.org/wiki/ABC_notation[ABC notation].

==Examples

With regular ChordPro you can simply annotate lyrics with chords like this:

```
A|l[Am]as my |l[C]ove you |d[G]o me |w[Em]rong to cast|
```

The result may be rendered as following:

```
 | Am    | C       | G    | Em          |
A|las my |love you |do me |wrong to cast|
```

The great benefit of this notation is its simplicity: 
You can wrap and break the line anywhere in the text whereas in the "rendered" text manual wrapping would be much more tedious.
