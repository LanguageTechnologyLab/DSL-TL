<h1>Discriminating Between Similar Languages - True Labels (DSL-TL)</h1>

Discriminating between similar languages (e.g., Croatian and Serbian) and language varieties (e.g., Brazilian and European Portuguese) has been a popular topic at VarDial since its first edition. The DSL shared tasks organized in 2014, 2015, 2016, and 2017 have addressed this issue by providing participants with the DSL Corpus Collection (DSLCC), a collection of journalistic texts containing texts written in multiple similar languages and language varieties. The DSLCC was compiled under the assumption that each instance's gold label is determined by where the text is retrieved from. While this is a straightforward (and mostly accurate) practical assumption, previous research has shown the limitations of this problem formulation as some texts may present no linguistic marker that allows systems or native speakers to discriminate between two very similar languages or language varieties.

We tackle this important limitation by introducing the DSL True Labels (DSL-TL) task. DSL-TL will provide participants with a human-annotated DSL dataset. A sub-set of nearly 13,000 sentences were retrieved from the DSLCC and annotated by multiple native speakers of the included language and varieties included, namely English (American and British), Portuguese (Brazilian and European), Spanish (Argentinian and Peninsular). To the best of our knowledge this is the first dataset of its kind opening exciting new avenues for language identification research.

<ul>
  <li><b>Track 1</b> - Three-way Classification: In this track, systems will be evaluated with respect to the prediction of all three labels for each language, namely the variety-specific labels (e.g., PT-PT or PT-BR) and the common label (e.g., PT).</li>
  <li><b>Track 2</b> - Binary Classification: In this track, systems will be scored only on the variety-specific labels (e.g., EN-GB, EN-US).</li>
</ul>



<h1>Submission Instructions</h1>


== Data Format ==

The test data contains the following file:

	test.tsv - testing set

Each line in the test.tsv file is in the format:

	text-sample-1

	text-sample-2

	...

	text-sample-N


== Submission ==

Each participant is allowed to submit 3 runs for the CLOSED submission and 3 runs for the OPEN submission to:

	knorth8@gmu.edu

Your submission files must follow the following naming convention: DSLTL-[submission_type]-run-X-[team_name].tsv 

The submission files should be in the following format:

	label 1

	label 2

	...

	label N

The labels must be given in the same order as the test samples listed in test.tsv. The participants must provide labels for all the test samples. We (organizers) will score your submission in tracks 1 (three-way - all labels) and 2 (binary - six labels). 

Each submission (run) must be accompanied by a DSLTL-readme-[task_type]-run-X-[team_name].txt file containing a one-paragraph description of the respective submission, where X is the run number (1, 2 or 3). 

For example, if the team name is "Harvard", the first CLOSED submission should contain two files:

	DSLTL-closed-run-1-Harvard.txt

	DSLTL-readme-closed-run-1-Harvard.txt



== Task Description ==

COPY the DSL-TL Description

We will share a reference to the dataset paper and shared task in due time. 


== Submission Types and Tracks ==

The following two submission types are allowed:

- CLOSED: participants ARE NOT allowed to use external data to train their models. You should only the dataset provided by the competition. 

- OPEN: participants ARE allowed to use external resources such as other corpora, lexicons to train their models.

In both submission types, participants are allowed to use pre-trained embeddings (e.g., BERT).

In addition to the two submission types, each submission will be scored in two tracks:

- Track 1 - Three-way Classification: In this track, systems will be evaluated with respect to the prediction of all three labels for each language, namely the variety-specific labels (e.g., PT-PT or PT-BR) and the common label (e.g., PT).

- Track 2 - Binary Classification: In this track, systems will be scored only on the variety-specific labels (e.g., EN-GB, EN-US).


== Evaluation ==

The macro-averaged F1 score will be used to rank the participants.


<h2>Update 1/30/2023 </h2>

<ul>
  <li>Labels have been standardized across the three datasets.</li>
  <li>Several instances within the ES_train.tsv have been assigned ids that were previoulsy missing.</li>
  <li>Four duplicates have been removed across the EN_train.tsv and EN_dev.tsv.</li>
  <li>Example Annotation Prompts added.</li>
</ul>

<h2>Contact</h2>

For more details please contact knorth8@gmu.edu

Last updated Feb 3 2023
