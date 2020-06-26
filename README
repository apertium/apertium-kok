Konkani

                            apertium-kok
===============================================================================

This is an Apertium monolingual language package for Konkani. What
you can use this language package for:

* Morphological analysis of Konkani
* Morphological generation of Konkani

Requirements
===============================================================================

You will need the following software installed:

* lttoolbox (>= 3.3.0)
* apertium (>= 3.3.0)
* vislcg3 (>= 0.9.9.10297)

If this does not make any sense, we recommend you look at: www.apertium.org

Compiling
===============================================================================

Given the requirements being installed, you should be able to just run:

$ ./configure
$ make

You can use ./autogen.sh instead of ./configure if you're compiling
from SVN.

If you're doing development, you don't have to install the data, you
can use it directly from this directory.

If you are installing this language package as a prerequisite for an
Apertium translation pair, then do (typically as root / with sudo):

# make install

You can give a --prefix to ./configure to install as a non-root user,
but make sure to use the same prefix when installing the translation
pair and any other language packages.

Testing
===============================================================================

If you are in the source directory after running make, the following
command should work:

$  echo "TODO: test sentence" | apertium -d . kok-morph
TODO: test analysis result

Files and data
===============================================================================

* apertium-kok.kok.dix            - Monolingual dictionary
* kok.prob                        - Tagger model
* apertium-kok.kok.rlx            - Constraint Grammar disambiguation rules
* apertium-kok.post-kok.dix       - Post-generator
* modes.xml                       - Translation modes


For more information
===============================================================================

* http://wiki.apertium.org/wiki/Installation
* http://wiki.apertium.org/wiki/Using_an_lttoolbox_dictionary

Help and support
===============================================================================

If you need help using this language pair or data, you can contact:

* Mailing list: apertium-stuff@lists.sourceforge.net
* IRC: #apertium on irc.freenode.net

License
=======

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

See also the file AUTHORS included in this distribution.
