1. Please provide a "confidence score" for your assessment of this submission [Very high, high, low, not my area]

Low/not my area

2. Summary and Contributions: Summarize the paper and its contributions.

The paper evaluates different embedding strategies to perform the task of identifying duplicate police reports. It also studies the task on summarized sentences and original sentences. This work applies a trained Doc2Vec model to compare with others.

3. Describe the strengths of the work.

* This work compares different models with different sentence rankings.
* This work is very practical, since it applies on the real dataset from police department.

4. Explain the imitations of the work

* The evaluation is not strong enough. The evaluation is only using accuracy. Other metrics such as recall, F1 also can be applied for analysis. Analyzing false positive cases or false negative cases can gain insights to improve the current work. 
* Choosing Top 1, 5, 10 lacks a good reason. Provide a study or reference on how to choose those number will strength the study.


5. List any minor issues with the paper.

* Paper has some grammar issues, and some sentences are hard to read.
* Table 2 label is not used correctly.
* Table style is not good.
* Fig. 1 is not cited.
* It is hard to compare the results of summarized sentence with original sentence from two different tables. Putting table 1 and table 2 together makes easy comparison between with summarization and without it.


6. Please provide an "overall score" for this submission [Accept, Weak Accept, Borderline, Weak Reject, Reject]

Weak Reject
