# MusicDoc

MusicDoc is a simple but powerful markup format for musical scores and partitures.
It is inspired by [AsciiDoc](https://asciidoc.org/) and [ChordPro](https://www.chordpro.org/).

The key principle of MusicDoc is simplicity!
Just write your lyrics and add some simple notation markup for chords, notes, bars, breaks, etc.

This makes MusicDoc different from musical formats such as [MusicXML](https://www.musicxml.com/) and even [ABC notation](https://en.wikipedia.org/wiki/ABC_notation).

## Chords

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

## Staves

Now if we want to add a stave with the melody we can additionally annotate the notes in curly braces:

```
{A}A|{c2}l[Am]as {d}my |{e.}l[C]ov-e {f/2}yo-{e}u |{d2}d[G]o {B}me |{G.}w[Em]rong {A/2}to {B]cast|
```

The result may be rendered as following:

![Greensleeves stave](img/greensleeves.png)
