A Mahjong Package for XeLaTeX
=============================

This project is a simple and idiosyncratic XeLaTeX package called `mj`
for using Mahjong tile fonts.

This project is more-or-less discontinued. The package has most the
features I set out to implement, and I think it works well enough to
actually be used. However, it is badly written and hard to extend
(except in the trivial way of adding orthogonal commands).

A New Version?
--------------

I am planning a follow up project to create a new (Xe)LaTeX package
for using Mahjong fonts. This time I plan to code it in a structured
manner and do away with most of the limitations of the current package.

I have set up a
[project web page](http://sites.eidenvall.se/mahjong-latex-package/)
that contains a project intent; information and discussion on mahjong
fonts; and a tentative project roadmap.

__Please contact me if you are interested in participating in this project!__

Contact me via e-mail ([Johan Eidenvall](mailto:johan@eidenvall.se),
mention in the subject that it is mahjong related) or via the project
page (I’m not checking that regularly, so e-mailing is better...)

Usage
=====

See the file `example.tex`. It contains example usage of most package
commands. (Or rather, it _will_ contain most commands, once finished.)

Also, at your own discression, you could read the package itself
(`mj.sty`), but I must issue a warning that it is _not_, by any means,
well written...

The Fonts
=========

In the `fonts/` directory there are four fonts to be used with this
package. These are:

  1. `MANGANPL.TTF`: _Mangan_, by ???
      * available at [`http://www.garethjmsaunders.co.uk/mahjong/fonts.html`](http://www.garethjmsaunders.co.uk/mahjong/fonts.html)
      * Licence: Listed as “Freeware” at above site.

  2. `Mahjong Bridge.ttf`: _Mahjong_, by BRIDGEco
      * Homepage: [`http://bridgeco.jp/`](http://bridgeco.jp/)
      * Licence: Free for non-comercial use.
        [From what I can tell from Google-Translate-ing the homepage... I think...]
      * I will call this font “Bridge” to distinguish it from Yoshiki
        (the next one) and from the concept of a “mahjong font”.

  3. `ma______.ttf`: _Mahjong_, by Yoshiki Kita, Yosh’s Laboratory
      * Homepage:
        [`http://www.asahi-net.or.jp/~mn8y-kt/font/font.html`]( http://www.asahi-net.or.jp/~mn8y-kt/font/font.html ). (Click
        “Mahjong” link)
      * Licence: Shareware. (Last paragraph in font description
        [**シェアウェアです。] translates to “It is shareware”. And
        the readme.txt says the fee is 1000¥.)
      * I will call this font “Yoshiki”.

  4. `Symbola613.ttf`: _Symbola_ (version 6.13), by George Douros
      * Homepage: [`http://users.teilar.gr/~g1951d/`](http://users.teilar.gr/~g1951d/)
      * Licence: “free for any use”  (see bottom of homepage).

  * Fonts 1, 2 and 3 are _symbol fonts_, where the symbols are placed
    in the ASCII range.
  * Font 4 is a generic Unicode font that includes the Unicode block
    _Mahjong Tiles (U+1F000–U+1F02F)_ (see, for example,
    [Unicode.org PDF chart](http://www.unicode.org/charts/PDF/U1F000.pdf)
    or
    [Wikibooks](http://en.wikibooks.org/wiki/Unicode/Character_reference/1F000-1FFFF))


Boring legal stuff
==================

Regarding the Font Files
------------------------

(This section regards only the files in the `fonts/` directory.)

The font files are _not_ created by me. I believe that they are free
to distribute, but please consult the above given sources for more
information.

I AM DISTRIBUTING THESE FILES IN GOOD FAITH AND WITH NO INTENTION TO
VIOLATE COPYRIGHT OR LICENSING.

Copyright Notice for Non-Font Files
-----------------------------------

(This section regards all files in this project __except__ those in the `fonts/` directory.)

Copyright (c) 2011-2013 Johan Eidenvall

* Use of these files is unrestricted.
* Modification of these files is unrestricted.
* Distribution of these files is unrestricted.
* The right to change the copyright for later versions is explicitly
  reserved by the copyright holder.

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---
