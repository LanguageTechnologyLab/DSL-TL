<h1>Discriminating Between Similar Languages - True Labels (DSL-TL)</h1>

Discriminating between similar languages (e.g., Croatian and Serbian) and language varieties (e.g., Brazilian and European Portuguese) has been a popular topic at VarDial since its first edition. The DSL shared tasks organized in 2014, 2015, 2016, and 2017 have addressed this issue by providing participants with the DSL Corpus Collection (DSLCC), a collection of journalistic texts containing texts written in multiple similar languages and language varieties. The DSLCC was compiled under the assumption that each instance's gold label is determined by where the text is retrieved from. While this is a straightforward (and mostly accurate) practical assumption, previous research has shown the limitations of this problem formulation as some texts may present no linguistic marker that allows systems or native speakers to discriminate between two very similar languages or language varieties.

We tackle this important limitation by introducing the DSL True Labels (DSL-TL) task. DSL-TL will provide participants with a human-annotated DSL dataset. A sub-set of nearly 13,000 sentences were retrieved from the DSLCC and annotated by multiple native speakers of the included language and varieties, namely English (American and British), Portuguese (Brazilian and European), Spanish (Argentinian and Peninsular). To the best of our knowledge, this is the first dataset of its kind opening exciting new avenues for language identification research.

<ul>
  <li><b>Track 1</b> - Three-way Classification: In this track, systems will be evaluated with respect to the prediction of all three labels for each language, namely the variety-specific labels (e.g., PT-PT or PT-BR) and the common label (e.g., PT).</li>
  <li><b>Track 2</b> - Binary Classification: In this track, systems will be scored only on the variety-specific labels (e.g., EN-GB, EN-US).</li>
</ul>

<h2>News</h2>


<h3>Update 2/15/2023 </h3>

<ul>
  <li>Updated submission instructions, in particular, the file naming convention. The submission instructions should now be more clear. The file is located at: <a href="https://gitfront.io/r/user-8615904/RrdNouqLYf3k/DSL-TL/tree/DSL-TL-Corpus/Test-DSL-TL/">../Test-DSL-TL/Submission_Instructions.md</a></li>

<h3>Update 2/13/2023 </h3>

<ul>
  <li>Converted four labels within the ES_train.tsv file to uppercase: es-ES to ES-ES. Updated file can be found at: <a href="https://gitfront.io/r/user-8615904/RrdNouqLYf3k/DSL-TL/blob/DSL-TL-Corpus/ES-DSL-TL/ES_train.tsv">../ES-DSL-TL/ES_Train.tsv</a></li>
</ul>

<h3>Update 2/03/2023 </h3>

<ul>
  <li>Included the test.tsv file for DSL-TL. Can be found at: <a href="https://gitfront.io/r/user-8615904/RrdNouqLYf3k/DSL-TL/blob/DSL-TL-Corpus/Test-DSL-TL/DSL-TL-test.tsv">../Test-DSL-TL/DSL-TL-test.tsv</a></li>
  <li>Added submission instructions at: <a href="https://gitfront.io/r/user-8615904/RrdNouqLYf3k/DSL-TL/tree/DSL-TL-Corpus/Test-DSL-TL/">../Test-DSL-TL/Submission_Instructions.md</a></li>
  <li>Changed directory structure. Directories previously named DSLCC-TL have been shortened to DSL-TL to conform with dataset.</li>
</ul>

<h3>Update 1/30/2023 </h3>

<ul>
  <li>Labels have been standardized across the three datasets.</li>
  <li>Several instances within the ES_train.tsv have been assigned ids that were previously missing.</li>
  <li>Four duplicates have been removed across the EN_train.tsv and EN_dev.tsv.</li>
  <li>Example Annotation Prompts added.</li>
</ul>

<h2>Contact</h2>

For more details please contact knorth8@gmu.edu

Last updated Feb 3 2023
