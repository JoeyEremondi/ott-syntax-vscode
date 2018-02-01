# ott-syntax-vscode

Provides syntax highlighting for the [Ott semantics tool](http://www.cl.cam.ac.uk/~pes20/ott/).

## Features

Right now, only syntax highlighting.
The emphasis is on visually distinguishing the meta-language from the language being modeled.
As a result, the files end up quite colorful.

I've optimized this for the One Dark Pro theme, but it should look okay with any theme. Some
classes might not get distinguished if your theme doesn't define colors for enough scopes, though.

I'm no expert when it comes to visual design, so pull-requests are welcome with regards
to the color choices.

## Requirements

Syntax highlighting recognize some languages within the `hom` blocks,
if you have a language pack installed for that language.
Reccomended packages to allow this are:

* [VSCoq](https://marketplace.visualstudio.com/items?itemName=siegebell.vscoq) or [Coq](https://marketplace.visualstudio.com/items?itemName=ruoz.coq)
* [Isabelle](https://marketplace.visualstudio.com/items?itemName=makarius.isabelle)
* [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) or [LaTeX Language Support](https://marketplace.visualstudio.com/items?itemName=torn4dom4n.latex-support)

## Extension Settings

None so far.

## Known Issues

None so far, though I expect the highlighting to be buggy.

## Release Notes

Users appreciate release notes as you update your extension.

### 0.0.1

Initial release
