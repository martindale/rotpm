# Rime of the Product Manager

A short film about a failed startup and the co-founder who killed it, based loosely on Samuel Taylor Coleridge's _The Rime of the Ancient Mariner_.

## Synopsis

The film opens at a technology conference, with a haggard middle-aged man accosting a young conference-goer about to enter a session. The older man tells a cautionary tale of his failed startup.

The startup had found early success and funding, and its fast growth and fun lifestyle ended up producing a less-focused team than the company started with. To fix the problem, the startup added a layer of product management, with one of the co-founders deciding to become a Product Manager himself. This began a downhill slide of market success and team morale. Eventually the B-round failed to close and the startup shut its doors, and the now-chastened PM spends his days wandering from technology conference to technology conference telling his story to unsuspecting developers.

The film ends back at the conference, as the quiet time between sessions ends and the hallway fills back up. The PM disappears, and the young developer walks off in stunned enlightenment.


## Runtime
Approx. 9 minutes

## Sets
* A coffee shop
* An office
* A tech conference

## Characters
* Two startup co-founders (approx 20-25 years of age)
* The male co-founder in middle age (the Product Manager)
* The conference-goer
* Extras
  * Coffee shop customers
  * Engineers hired by the post-funding startup
  * Conference attendees

## Using this repo

* Have Ruby installed (tested with 2.0.x).
* Run `script/bootstrap` to install the [asciidoctor](https://github.com/asciidoctor/asciidoctor) gem.
* Run `script/render` to convert the `screenplay/rotpm.asciidoc` into HTML. This will create a file called `screenplay/rotpm.html`. The generated file will be ignored by Git, and shouldn't be committed to the repo.
* Open `screenplay/rotpm.html` in a browser. Printing to a PDF creates a screenplay document fairly close to the standard form used by filmmakers.
* Collaborate on the Asciidoc screenplay source as you would any text file.
