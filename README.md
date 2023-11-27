# F-4E Manual

[![license](https://img.shields.io/badge/license-CC--BY--NC--ND_4.0-blue)](https://github.com/Heatblur-Simulations/f-4e-manual/blob/master/LICENSE)

![Spook - My Other Ride Is Your Mom](https://i.imgur.com/KBOIocl.png)

Manual of the F-4E Phantom by Heatblur Simulations.

This is a [mdBook](https://rust-lang.github.io/mdBook/) project, content is
written in the language **Markdown** (`.md`).

The manual is automatically exported as HTML version, hosted at:
https://heatblur-simulations.github.io/f-4e-manual/.

## Setup

Markdown is supported widely by most IDEs and text editors. We recommend
[VSC](https://code.visualstudio.com/) and any JetBrains IDE, such as
[Fleet](https://www.jetbrains.com/fleet/),
[IntelliJ](https://www.jetbrains.com/idea/) or
[CLion](https://www.jetbrains.com/clion/).

You can also simply press `.` (dot) while on GitHub and it will open an instance
of Visual Studio Code right in your browser, allowing you to contribute directly
and conveniently.

Please read
[CONTRIBUTING.md](https://github.com/Heatblur-Simulations/f-4e-manual/blob/master/CONTRIBUTING.md)
before your first contribution.

### Building locally

To build the website locally, you have to install **mdbook**, see
[here](https://rust-lang.github.io/mdBook/guide/installation.html).

Then run the command `mdbook build` from this folder; the website can be found
in the folder `book`. Use `mdbook serve` to make the contents available in your
browser at [localhost:3000](http://localhost:3000/), it automatically updates
whenever the contents change.

## GH Pages

The project is automatically configured via a CI/CD to build and publish any
change to `master` to a GH-Pages branch called `html`. GitHub will automatically
publish the website on https://heatblur-simulations.github.io/f-4e-manual/.
