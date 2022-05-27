| Score |     |
|---|---|
| **0** | *Project fails to meet the minimum requirements for this item.* |
| **1** | *Project meets the minimum requirements for this item, but falls significantly short of portfolio-ready expectations.* |
| **2** | *Project exceeds the minimum requirements for this item, but falls short of portfolio-ready expectations.* |
| **3** | *Project meets or exceeds portfolio-ready expectations; demonstrates a thorough understanding of every outlined consideration.* |

Section	|	Score	|	Notes
------	|	------	|	--------
**Problem Statement**	|	**2**	|
Is it clear what the student plans to do? 	|	3	|	Yes.
What type of model will be developed? 	|	0	|	Unstated.
How will success be evaluated? 	|	1	|	Implied to be RMSE.
Is the scope of the project appropriate? 	|	2	|	It is the minimum required of the student, but why it matters is articulated.
Is it clear who cares about this or why this is important to investigate?	|	2	|	Yes, if somewhat vaguely.
 Does the student consider the audience and the primary and secondary stakeholders?	|	3	|	Yes.
**Data Cleaning and EDA**	|	**3**	|
Are missing values imputed appropriately? 	|	3	|	Yes.
Are distributions examined and described? 	|	3	|	Yes.
Are outliers identified and addressed? 	|	3	|	Yes.
Are appropriate summary statistics provided? 	|	3	|	Yes.
Are steps taken during data cleaning and EDA framed appropriately? 	|	3	|	Yes.
Does the student address whether or not they are likely to be able to answer their problem statement with the provided data given what they've discovered during EDA?	|	1.5	|	Implicitly, yes.
**Preprocessing and Modeling**	|	**3**	|
Are categorical variables one-hot encoded? 	|	3	|	Yes.
Does the student investigate or manufacture features with linear relationships to the target? 	|	3	|	Yes.
Have the data been scaled appropriately? 	|	3	|	Yes.
Does the student properly split and/or sample the data for validation/training purposes? 	|	3	|	Yes.
Does the student utilize feature selection to remove noisy or multi-collinear features? 	|	3	|	Extensively.
Does the student test and evaluate a variety of models to identify a production algorithm (AT MINIMUM: linear regression, lasso, and ridge)? 	|	3	|	Yes.
Does the student defend their choice of production model relevant to the data at hand and the problem? 	|	3	|	Linear regression chosen based on lack of improvement by regularization.
Does the student explain how the model works and evaluate its performance successes/downfalls?	|	0	|	No.
**Evaluation and Conceptual Understanding**	|	**3**	|
Does the student accurately identify and explain the baseline score? 	|	0	|	The baseline of a 1 variable linear regression rather than the mean of the data is chosen.
Does the student select and use metrics relevant to the problem objective?	|	3	|	Yes.
Is more than one metric utilized in order to better assess performance? 	|	3	|	Yes.
Does the student interpret the results of their model for purposes of inference? 	|	3	|	Yes.
Is domain knowledge demonstrated when interpreting results? 	|	3	|	Yes.
Does the student provide appropriate interpretation with regards to descriptive and inferential statistics?	|	3	|	Yes.
**Conclusion and Recommendations**	|	**2**	|
Does the student provide appropriate context to connect individual steps back to the overall project?	|	3	|	Very much so.
 Is it clear how the final recommendations were reached? 	|	3	|	Yes.
Are the conclusions/recommendations clearly stated? 	|	2	|	Conclusion yes, recommendation is somewhat vague.
Does the conclusion answer the original problem statement? 	|	3	|	Yes.
Does the student address how findings of this research can be applied for the benefit of stakeholders? 	|	2	|	By pinpointing features for housing price assessment.
Are future steps to move the project forward identified?	|	0	|	No.
**Project Organization**	|	**3**	|
Are modules imported correctly (using appropriate aliases)? 	|	3	|	Yes.
Are data imported/saved using relative paths? 	|	3	|	Yes.
Does the README provide a good executive summary of the project? 	|	2	|	Somewhat lacking in terms of describing the process.
Is markdown formatting used appropriately to structure notebooks? 	|	3	|	Yes.
Are there an appropriate amount of comments to support the code? 	|	3	|	Yes.
Are files & directories organized correctly? 	|	2	|	Code notebooks must be in their own directory, and the main notebook is so large it should be split into smaller notebooks.
Are there unnecessary files included? 	|	2	|	Yes, ipynb_checkpoints.
Do files and directories have well-structured, appropriate, consistent names?	|	3	|	Mostly, though not consistent in terms of letter case usage.
**Visualizations**	|	**3**	|
Are sufficient visualizations provided? 	|	3	|	Well beyond sufficient.
Do plots accurately demonstrate valid relationships? 	|	3	|	Yes.
Are plots labeled properly? 	|	2	|	Some issues with overlapping xticks, which can be solved by rotating them.
Are plots interpreted appropriately? 	|	3	|	Yes.
Are plots formatted and scaled appropriately for inclusion in a notebook-based technical report?	|	3	|	Yes.
**Python Syntax and Control Flow**	|	**3**	|
Is care taken to write human readable code?	|	3	|	Yes.
Is the code syntactically correct (no runtime errors)? 	|	3	|	Yes.
Does the code generate desired results (logically correct)?	|	3	|	Yes.
 Does the code follows general best practices and style guidelines? 	|	3	|	Yes.
Are Pandas functions used appropriately? 	|	3	|	Yes.
Are sklearn methods used appropriately?	|	3	|	Yes.
