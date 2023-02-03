<h1>Submission Instructions</h1>

<h2>Test Data Format</h2>

The test data contains the following file:

	DSL-TL-test.tsv - testing set

Each line in the test.tsv file is in the format:

	text-sample-1

	text-sample-2

	...

	text-sample-N


<h2>Submission</h2>

Each participant is allowed to submit 3 runs for the CLOSED submission and 3 runs for the OPEN submission to:

	knorth8@gmu.edu

Your submission files must follow the following naming convention: <b>DSLTL-[submission_type]-run-X-[team_name].tsv</b> 

The submission files should be in the following format:

	label 1

	label 2

	...

	label N

The labels must be given in the same order as the test samples listed in test.tsv. The participants must provide labels for all the test samples. We (organizers) will score your submission in tracks 1 (three-way - all labels) and 2 (binary - six labels). 

Each submission (run) must be accompanied by a <b>DSLTL-readme-[task_type]-run-X-[team_name].txt</b> file containing a one-paragraph description of the respective submission, where X is the run number (1, 2 or 3). 

For example, if the team name is "Harvard", the first CLOSED submission should contain two files:

	DSLTL-closed-run-1-Harvard.txt

	DSLTL-readme-closed-run-1-Harvard.txt


<h2>Task Description</h2>

The DSL-TL shared-task provides participants with a human-annotated DSL dataset. A sub-set of nearly 13,000 sentences were retrieved from the DSLCC and annotated by multiple native speakers of the included languages and varieties, namely English (American and British), Portuguese (Brazilian and European), Spanish (Argentinian and Peninsular). To the best of our knowledge, this is the first dataset of its kind opening exciting new avenues for language identification research.

<ul>
  <li><b>Track 1</b> - Three-way Classification: In this track, systems will be evaluated with respect to the prediction of all three labels for each language, namely the variety-specific labels (e.g., PT-PT or PT-BR) and the common label (e.g., PT).</li>
  <li><b>Track 2</b> - Binary Classification: In this track, systems will be scored only on the variety-specific labels (e.g., EN-GB, EN-US).</li>
</ul>

We will share a reference to the dataset paper and shared task in due time. 


<h2>Submission Types and Tracks</h2>

The following two submission types are allowed:

<ul>
  <li><b>CLOSED</b> : participants ARE NOT allowed to use external data to train their models. You should only the dataset provided by the competition. 
  <li><b>OPEN</b> : participants ARE allowed to use external resources such as other corpora, lexicons to train their models.
</ul>

In both submission types, participants are allowed to use pre-trained embeddings (e.g., BERT).

In addition to the two submission types, each submission will be scored in two tracks:

<ul>
  <li><b>Track 1</b> - Three-way Classification: In this track, systems will be evaluated with respect to the prediction of all three labels for each language, namely the variety-specific labels (e.g., PT-PT or PT-BR) and the common label (e.g., PT).
 <li><b>Track 2</b> - Binary Classification: In this track, systems will be scored only on the variety-specific labels (e.g., EN-GB, EN-US).
</ul>

<h2>Evaluation</h2>

The macro-averaged F1 score will be used to rank the participants.
