# ModularKAOS
Modular KAOS plugin for Eclipse

This project was developed by Patricia Espada as part of her MSc dissertation, conducted at the Informatics Department of FCT/UNL.
The zip archive contains the sources and Eclipse plugins of the Modular KAOS editor.

The tool and its usage are described in the paper:

Espada, P., Goulão, M., & Araújo, J. (2013, June). A framework to evaluate complexity and completeness of KAOS goal models. In Advanced Information Systems Engineering (pp. 562-577). Springer Berlin Heidelberg.

```bibtex
@inproceedings{espada2013framework,
  title={A framework to evaluate complexity and completeness of KAOS goal models},
  author={Espada, Patr{\'\i}cia and Goul{\~a}o, Miguel and Ara{\'u}jo, Jo{\~a}o},
  booktitle={Advanced Information Systems Engineering},
  pages={562--577},
  year={2013},
  organization={Springer}
}
```

******************************************
*** modularKAOS - Setup guide ***
******************************************
1- Install Eclipse Modeling Tools, Juno version.

2- Make sure that your eclipse have the following plugins: 
- Eclipse Modeling Tools, version 1.5.0 
- Emfatic (Incubation), version 0.3.0 
- Epsilon Concordance (Incubation), version 0.9.1 
- Epsilon Core (Incubation), version 0.9.1 
- Epsilon EMF/GMF Life Validation (Incubation), version 0.9.1 
- Epsilon EMF/GMF Scripting (Incubation), version 0.9.1 
- Epsilon Eugenia (Incubation), version 0.9.1 
- Graphical Modeling Framework, version 2.4.0 
- Humanos Usable Textual Notation, version 0.8.1 
- OCL Examples and Editors, version 3.2.0

3- These plugins can be found in Help -> Install Modeling Components inside the eclipse environment, or in their respective website.

4- See if the Java compiler version is set to 6.0. You can find that in Eclipse -> Preferences -> Java -> Compiler -> Compiler compliance level.

5- To finish the installation just drop the modularKAOS jar plugins into the plugins or the dropins folder of the Eclipse installation. 
- Kaos.jar
- Kaos_diagram.jar
- Kaos_edit.jar
- Kaos_editor.jar


Please refer to Patricia's MSc Dissertation, also available in the zip file, for detailed setup instructions (in Portuguese).
