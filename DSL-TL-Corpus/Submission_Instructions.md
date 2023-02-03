<h1>DSL-TL Corpus</h1>

This is the official training, dev and test data for the Discriminating between Similar Languages - True Labels (DSL-TL) task at VarDial 2023.

<h2>Contents</h2>

This repository contains the following files:

<h3>Data for English - (:uk:/:us:)</h3>

`../EN-DSL-TL/EN_train.tsv`               - English Training set for the DSL-TL task              -  2097

`../EN-DSL-TL/EN_dev.tsv`                 - English Dev set for the DSL-TL task              -  599

<h3>Data for Spanish - (:es:/:argentina:)</h3>

`../ES-DSL-TL/ES_train.tsv` 							- Spanish Training set for the DSL-TL task              -  3467 

`../ES-DSL-TL/ES_dev.tsv` 						  	- Spanish Dev set for the DSL-TL task              -  989 

<h3>Data for Portuguese - (:portugal:/:brazil:)</h3>

`../PT-DSL-TL/PT_train.tsv` 							- Portuguese Training set for the DSL-TL task              -  3467 

`../PT-DSL-TL/PT_dev.tsv` 							  - Portuguese Dev set for the DSL-TL task              -  991 

<h3>Test Data</h3>

`../Test-DSL-TL/DSL-TL-test.tsv` 							  - Test set for both tracks. Contains instances in all language varieties without labels              -  1290 

`../Test-DSL-TL/README.md` 							  - <b>Submission Instructions</b>        

<h3>Additional Files</h3>

`README.md` 								                - This file. Brief description of the DSL-TL data. 

<h2>Format</h2>

Each line in the .tsv files are tab-delimited in the format:

`id<tab>sentence<tab>label`

<strong>Example:</strong> 

`135<tab>Hey, burger freaks: Were you planning to wait two hours-plus cooling your heels for Au Cheval’s crazypants patty? Hold your horses.<tab> EN-US`

<h2>Labels</h2>

`EN`, `ES`, and `PT` for common instances, previous labeled as `Both or neither`, `Ambas o ninguna (both or none)`, or  `Ambas ou Nenhuma (both or none)` and `Ambas or None (both or none)` respectively.

`EN-GB` and `ES-US` for British and American English respectively.

`ES-ES` and `ES-AR` for Spanish (Peninsular/European) and Argentine Spanish respectively.

`PT-PT` and `PT-BR` for Portuguese (European) and Brazilian Portuguese respectively.

<h2>Contact</h2>

For more details please contact knorth8@gmu.edu

Last updated Feb 3 2023
