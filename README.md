#What is it?

Practise naming the compounds specified in *exercise.json*. Draws molecular structures using HTML5 Canvas and turns practising into a quiz game.

Live demo at <https://niklaslindblad.se/orgo>

#License

All code licensed under the GPL (any version) <http://www.gnu.org/licenses/gpl.html>

Uses ChemDoodle Web Components <http://web.chemdoodle.com/installation/license>

#Screenshots

<img src="https://dl.dropbox.com/u/1236795/orgo.png" />

# Configuration

*exercise.json* contains the compounds that will be used.

The default file contains Swedish trivial names used in an organic chemistry course at LTH <http://www.chem.lu.se/people/strandgroup/Teaching/KOKA05/2012.html>

# Data Format

ChemDoodle supports a wide variety of file formats, but the one used for the examples is MOL (.mol)

MIME type: *chemical/x-mdl-molfile*

MDL molecule model files.

Used in cheminformatics applications and on the web for storing and exchanging 3D molecule models.
Plain text tabular format.
Represents a single chemical compound.
Stores atomic coordinates, chemical bond information, and metadata.

Maintained by Elsevier Molecular Design Limited (MDL).

# Adding New Compounds

Use <http://cactus.nci.nih.gov/translate/> to translate from SMILE (the format used on Wikipedia entries for a chemical) to generate .MOL files.