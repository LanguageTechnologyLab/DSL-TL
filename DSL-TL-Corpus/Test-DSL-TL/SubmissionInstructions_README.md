<h1>Submission Instructions</h1>


== Data Format ==

The test data contains the following file:

	test.tsv - testing set

Each line in the test.tsv file is in the format:

	text-sample-1

	text-sample-2

	...

	text-sample-N


<h2>Submission</h2>

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


<h2>Task Description</h2>

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

<h2>Evaluation</h2>

The macro-averaged F1 score will be used to rank the participants.
