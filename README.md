proportional-font-terminal
==========================

## Proportional Font Terminal: A Better Linux / Unix / Mac Terminal (Archaic Build)

*This project works with archaic browsers, like FireFox 3 or (shudder)
Internet Explorer 6. It does not seem to work well with current browser
versions, and it is being left partly as a historical detail, with a clear
reference implementation of how one would do this with today's browser.*

*The basic enhancement of allowing this for e.g. Gnome Terminal appears to be
in the Gnome Terminal bug tracker, and so this functionality may be available
someday in standard terminal programs by setting one's font to Verdana.*

### Design, typography, and terminals: *Not-so-good, better, best*

Those of us involved in web design and usability know that fonts are not
created equal. The first incarnation of http://JonathansCorner.com used
fixed-width fonts for almost everything, because I didn't know what I was
doing. Since then, I've joined the rest of the web in recognizing the benefits
of using a font optimized for on-screen reading.

<p>In the spirit of the sort of makeover done by Tufte in books like 
[Envisioning Information] (http://www.powells.com/partner/24934/biblio/9780961392116)
, I would like to look at three different terms; the last one is
the one offered here.

#### Not-so-good

This is a (cropped) screenshot of the default term (xterm) that shipped with
my EeePC. It has a black background, like ancient VT100's:

![A Screenshot of some code in a default xterm from an
EeePC](screenshot-xterm.png)

What this is optimized for is densely packing information into a tight
space, and for serious coding this is seriously answering the wrong
question.

#### Better

Let's look at a terminal that shows much better typography and design:

![A screenshot of the same code in a
gnome-terminal.](screenshot-gnome-terminal.png)

This has a more readable font, and it makes productive use of space: more
specifically, it uses space to enhance usability and readability, not cram in
as many bits per pixel as can still technically be read. The font, unlike even
the Mac Terminal, is deftly anti-aliased, and to a designer the font appears to
have been clearly designed for usability.

#### Best

But we can do better by breaking out of the grid and using web-based
typography as a starting point, and tweak the spacing for reading code:

![A screenshot in the enhanced terminal provided in this
package.](screenshot-enhanced.png)
<img src="screenshot-enhanced.png" height="431" width="605" border="0"
alt="A screenshot of the same code in the enhanced terminal served from this page."
style="margin-left: 50px; border: 20px solid white;" />

I've looked at a lot of code this way, and the difference is remarkable.
If your code is formatted well, it is easier to read and you can tell more at a
glance and then zero in on what you need. It has just a little of the magic of
of [moving from find/grep/xargs to *ack*](http://beyondgrep.com), or
[discovering Python](http://www.linuxjournal.com/article/3882). Having
tried it, I *really* don't want to go back.

How did I do that? By standing on Antoine Lesuisse's shoulders with Ajaxterm
([homepage](http://antony.lesuisse.org/software/ajaxterm/), [download](
Ajaxterm-0.10.tar.gz). A few CSS tweaks, and there is a terminal that takes
advantage of the web's advances in typography and usability.
