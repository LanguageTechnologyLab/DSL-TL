<h1>Discriminating Between Similar Languages - True Labels (DSL-TL)</h1>

Discriminating between similar languages (e.g., Croatian and Serbian) and language varieties (e.g., Brazilian and European Portuguese) has been a popular topic at VarDial since its first edition. The DSL shared tasks organized in 2014, 2015, 2016, and 2017 have addressed this issue by providing participants with the DSL Corpus Collection (DSLCC), a collection of journalistic texts containing texts written in multiple similar languages and language varieties. The DSLCC was compiled under the assumption that each instance's gold label is determined by where the text is retrieved from. While this is a straightforward (and mostly accurate) practical assumption, previous research has shown the limitations of this problem formulation as some texts may present no linguistic marker that allows systems or native speakers to discriminate between two very similar languages or language varieties.

We tackle this important limitation by introducing the DSL True Labels (DSL-TL) task. DSL-TL will provide participants with a human-annotated DSL dataset. A sub-set of nearly 13,000 sentences were retrieved from the DSLCC and annotated by multiple native speakers of the included language and varieties included, namely English (American and British), Portuguese (Brazilian and European), Spanish (Argentinian and Peninsular). To the best of our knowledge this is the first dataset of its kind opening exciting new avenues for language identification research.

<ul>
  <li><b>Track 1</b> - Three-way Classification: In this track, systems will be evaluated with respect to the prediction of all three labels for each language, namely the variety-specific labels (e.g., PT-PT or PT-BR) and the common label (e.g., PT).</li>
  <li><b>Track 2</b> - Binary Classification: In this track, systems will be scored only on the variety-specific labels (e.g., EN-GB, EN-US).</li>
</ul>


<b>Evaluation</b>: Macro F1 score over the language/variety labels (9 on track 1, 6 on track 2).

<b>Submission type(s)</b>: Closed or Open

<h1>Submission Instructions</h1>





<h1>DSL-TL Corpus</h1>

This is the official training and dev data for the Discriminating between Similar Languages - True Labels (DSL-TL) task at VarDial 2023.

<h2>Contents</h2>

This repository contains the following files:

<h3>Data for English - (:uk:/:us:)</h3>

`../EN-DSLCC-TL/EN_train.tsv`               - English Training set for the DSL-TL task              -  2096

`../EN-DSLCC-TL/EN_dev.tsv`                 - English Dev set for the DSL-TL task              -  598

`../EN-DSLCC-TL/EN_test.tsv`                - English Test set for the DSL-TL task              -  299

<h3>Data for Spanish - (:es:/:argentina:)</h3>

`../ES-DSLCC-TL/ES_train.tsv` 							- Spanish Training set for the DSL-TL task              -  3466 

`../ES-DSLCC-TL/ES_dev.tsv` 						  	- Spanish Dev set for the DSL-TL task              -  988 

`../ES-DSLCC-TL/ES_test.tsv`                - Spanish Test set for the DSL-TL task              -  494 

<h3>Data for Portuguese - (:portugal:/:brazil:)</h3>

`../PT-DSLCC-TL/PT_train.tsv` 							- Portuguese Training set for the DSL-TL task              -  3466 

`../PT-DSLCC-TL/PT_dev.tsv` 							  - Portuguese Dev set for the DSL-TL task              -  990 

`../PT-DSLCC-TL/PT_test.tsv`                - Portuguese Test set for the DSL-TL task              -  494    

<h3>Additional Files</h3>

`README.md` 								                - This file. Brief description of the DSL-TL data. 

`../example_annotation_guidelines/..`  							- Example annotation prompts used on Amazon Mechanical Turk.

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
