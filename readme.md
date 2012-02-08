# Slingin’ Hot Leading
Manually adjusting ```line-height``` for optimum readability across a bunch of media queries is kind of a pain. So I made a thing. One sets a minimum width at which the adjustment starts, a maximum element width where it stops, and a minimum and maximum line height to adjust through. This isn’t especially well-tested, but seems to check out in all the big desktop browsers (including IE).

## Notes:
* Binding to ```resize``` makes me nauseous to begin with, and in this first pass I’m going about it in a particularly gross way.
* There’s a demo <a href="http://wilto.github.com/Molten-Leading/">right hurr</a>.
* Full credit to <a href="http://twitter.com/nicewebtype">Tim Brown</a> for <a href="http://nicewebtype.com/notes/2012/02/03/molten-leading-or-fluid-line-height/">the post</a> that got my lazy ass in gear on this, and the awesome name.