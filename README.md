# TicraGerberExport
Gerber export information from TICRA to Altium to Fabricator Compatible Format

TICRA Setup: Commands > Add > Export Gerber Files > Target: [Select Surface] > Submit Job
Locate the output folder, where two files will be generated as follows: [File Name]_GP.gbr and [File Name]_elements.gbr, Verify the design is valid with Altium Designer Cam Viewer. The common file format is MLA4.4, but the file format from TICRA is a MTI6.6 Format which may not work with some fabricators. In this case, use a gerber viewer (Gerbv.exe/GerberEditorExe) to check that it can be loaded.

Python Script File Conversion: GerberTicraConvert.ipynb
