# Geographies of Holocaust Rescue on the Plateau Vivarais-Lignon
NLP project, using rules-based, deep learning, and AI, to understand space and place of Holocaust survivors and rescuers on the Plateau Vivarais-Lignon in France based on their personal testimonies.

The Geoparsing component of this project has the Jupyter notebooks for the three different methods used, with folders for each:  the Irchel Geoparser; LLM using GPT-4.1; and a rules-based spaCy Entity Ruler geoparsing structure.  Also included in the folders are the yaml files indicating the libraries in the respective environments, as well as additional supporting files.  

The Emotion Detection components of this project has the Jupyter notebooks for the two different methods used (Deep Learning and GPT-4.1), with the files marked "FinalCode_" being the last iterations, as well as the yaml files indicating the libraries in the respective environments, as well as additional supporting files and results.  For the GPT-based method, I included all the different iterations of code, instruction prompts, and results so that folks can see the testing that went into this.  The Deep Learning method used the Rules-Based Entity Ruler geoparser for extracting toponyms and non-named places for keywords.  Rather than duplicating that code, please see the Geoparsing/RulesBased_EntityRulers folder for those files.     

NOTE:  In no case are my data files uploaded.  My data are part of three different archives of Holocaust testimonies and will not be publically available on this site.

The information here is available as open source under the attached MIT license.  If using anything specific from my work, please attribute as appropriate:  Anderson, Christopher (2025) https://github.com/nordicgeosolutions/HolocaustRescue-PlateauVivaraisLignon/.

The Python libraries (e.g. spaCy, Irchel Geoparser, OpenAI, etc.) are utilized based on their respective licenses.  For my methodology of geoparsing using spaCy rules-based "Entity Rulers," I gratefully acknowledge that the spark of the idea for using entity rulers originates with: Mattingly, W. J. B. 2023. Introduction to Python for Digital Humanists. Boca Raton: CRC Press, Taylor & Francis Group.
