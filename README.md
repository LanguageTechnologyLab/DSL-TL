<h1>DSL-TL Corpus</h1>

This is the official training and dev data for the Discriminating between Similar Languages - True Labels (DSL-TL) task at VarDial 2023.

<h2>Contents</h2>

This repository contains the following files:

<h3>Data for English `r emo::ji("france")`</h3>

`../EN-DSLCC-TL/EN_train.tsv`               - English Training set for the DSL-TL task 

`../EN-DSLCC-TL/EN_dev.tsv`                 - English Dev set for the DSL-TL task 

`../EN-DSLCC-TL/EN_test.tsv`                - English Test set for the DSL-TL task 

`../ES-DSLCC-TL/ES_train.tsv` 							- Spanish Training set for the DSL-TL task 

`../ES-DSLCC-TL/ES_dev.tsv` 						  	- Spanish Dev set for the DSL-TL task 

`../ES-DSLCC-TL/ES_test.tsv`                - Spanish Test set for the DSL-TL task 

`../PT-DSLCC-TL/PT_train.tsv` 							- Portuguese Training set for the DSL-TL task 

`../PT-DSLCC-TL/PT_dev.tsv` 							  - Portuguese Dev set for the DSL-TL task 

`../PT-DSLCC-TL/PT_test.tsv`                - Portuguese Test set for the DSL-TL task 

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

<h2>Update 1/30/2023 </h2>

<ul>
  <li>Labels have been standardized across the three datasets.</li>
  <li>Several instances within the ES_train.tsv have been assigned ids that were previoulsy missing.</li>
  <li>Four duplicates have been removed across the EN_train.tsv and EN_dev.tsv.</li>
  <li>Example Annotation Prompts added.</li>
</ul>

<h2>Contact</h2>

For more details please contact knorth8@gmu.edu

Last updated Jan 23 2023
