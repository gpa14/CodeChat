.. Copyright (C) 2012-2016 Bryan A. Jones.

   This file is part of CodeChat.

   CodeChat is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

   CodeChat is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

   You should have received a copy of the GNU General Public License along with CodeChat.  If not, see <http://www.gnu.org/licenses/>.

*************************
History of recent changes
*************************
- Development version:

   - Ported to Python 3.
   - Added NSIS, Spec file support.
   - Tests now reside in a separate ``test/`` subdirectory.

- 1.2.1, 12-Nov-2015:
   - Fixed broken hyperlinks in the :ref:`tutorial-examples`.
   - Provide correct Linux installation instructions.

- 1.2.0, 12-Nov-2015:
   - Prevent errors when an indented comment follows code.
   - Display the correct line number of errors/warnings.
   - Document brokenness when headings are indented.

- 1.1.1, 11-Nov-2015:
   - Fix to actually support ``SConscript`` and ``Makefiles``.

- 1.1.0, 10-Nov-2015:

   - Dropped support for pre-v1.3 Sphinx.
   - The extension of source files is now preserved, rather than being stripped. This makes for a simpler ``conf.py``, since ``source_suffix`` is no longer modified.
   - The corret HTML extension is now written to ``sphinx-enki-info.txt``.
   - A link to install instructions is now provided in :doc:`../README`.
   - The ``.ini`` file format is now supported.
   - ``SConscript`` and ``Makefiles`` are now supported.

- 1.0.1, 21-Aug-2015:

   - Support MATLAB (``.m``) files.
   - Provide a tutorial in the docs.

- 1.0.0, 20-Jul-2015:

   - Update ``setup.py`` based on modern usage.
   - Update docs.
   - Add support for Sphinx v1.3. Process source files in memory, instead of creating ``.rst`` files. This allows source links to refer to the source code, not the intermediate ``.rst`` files.
   - Creation of a tutorial.
   - Support for all Sphinx themes.
   - Use of fenced code blocks to more cleanly include code in reST.
   - Support for Sphinx's conf.py ``highlight_language = 'python'``.
   - Improved CSS for better layout of paragraphs following code.
   - Support for block comments with or without indents.
   - Support for many more languages.
   - Simpler integration of CodeChat into a Sphinx ``conf.py``.
   - Support for user-specified extensions.
   - Support for indented headings; note that they won't be indented in the resulting HTML.
   - Whitespace is removed in auto-save and build mode.
   - Errors and warnings are now displayed in the Preview dock's status bar, which replaces the useless progress bar.
   - Avoid double builds when in auto-save and build mode.
   - Template project now include ``conf.py`` and ``CodeChat.css``.

- 0.0.18, 11-Feb-2015:

   - Remove unused PyQt dependencies.
   - Modernize documentation style in ``CodeChat/LanguageSpecificOptions``.

- 0.0.17, 17-Nov-2014:

   - Support Sphinx versions before 1.2.
   - Move non-CodeChat templates to Enki.

- 0.0.16 - 0.0.13, 11-Nov-2014:

   - Improved Sphinx template: doesn't replace default.css.
   - Updated CSS to work better with docutils.

- 0.0.12, released 1-Sep-2014:

   - Fixes so that CodeChat's Sphinx extension now works.
   - File encoding can now be specified.
   - Installaiton instructions added and docs reworked.

- 0.0.11, released 1-May-2014:

   - Fixed Unicode errors.
   - Removed incorrect extra spacing between code and comments.
   - Fixed unit tests and added a few more.
   - Removed unused CodeLink directive.

- 0.0.10, released 17-Apr-2014:

   - Revamped packaging.
   - Updated docs.
   - Used ``..`` instead of marker to indent comments, producing cleaner ReST.
   - Split ``CodeToRest`` into ``CodeToRest``, ``CodeToRestSphinx`` modules.
