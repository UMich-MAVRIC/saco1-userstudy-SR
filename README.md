# saco1-userstudy-SR

## Overview

- Paper link: [Online version]() or [download PDF]()


## Data Files
The following data files are in the `data` folder.
* `data_48subjects.csv`: Data from 48 subjects analyzed in the paper. Each row of the file corresponds to data from one subject. The following are the descriptions for the header.
  * Condition: The experimental condition assigned to the subject. Condition 1 is the low SMM and low communication amount condition. Condition 2 is the low SMM and high communication amount condition. Condition 3 is the high SMM and low communication amount condition. Condition 4 is the high SMM and high communication amount condition.
  * SMM_level: Whether the SMM level was low or high.
  * Comm_level: Whether the communication amount level was low or high.
  * SMM_low: 1 if the SMM level was low, 0 if the SMM level was high.
  * SMM_high: 1 if the SMM level was high, 0 if the SMM level was low.
  * Comm_low: 1 if the communication amount level was low, 0 if the communication amount level was high.
  * Comm_high: 1 if the communication amount level was high, 0 if the communication amount level was low.
  * SMMxCommInt: 1 if both the SMM and communication amount levels were high, 0 otherwise.
  * Age: The age of the subject.
  * Gender: The gender of the subject.
  * Attention_score: The percentage of attention check questions answered correctly. There were 8 attention check questions.
  * Attention_extra_score: The percentage of additional attention check questions answered correctly by subjects in the high communication amount level. -1 means these questions were not administered to those in the low communication amount level.
  * Pre_SMM: The SMM score of the subject before the experiment began. The SMM score was summed out of 4 questions.
  * TSA_ALL: Team SA across all elements of interest and all discrete timepoints for the mission.
  * z_TSA_ALL: Standardized team SA, computed by taking the z-score of team SA.
  * Comm_2items: The average of Comm_Item2 and Comm_Item3.
  * Comm_Item2: The response to the first communication overload question on a 7-point Likert scale.
  * Comm_Item3: The response to the second communication overload question on a 7-point Likert scale.
  * TOs_required: The number of times help was provided to a UGV during a processing status for events requring help.
  * TOs_not_required: The number of times help was not provided to a UGV during a processing status for events not requiring help.
  * MEfficiency: The sum of TOs_required and TOs_not_required as a measure of mission efficiency.
  * Points: The total point score at the end of the mission.
* `spss_tests.pdf`: The output of all analyses in IBM SPSS 29.0.1.0. 
* `surveys.pdf`: The survey questions analyzed in the paper.

## Paper Source Files and Figures
The `paper` folder contains the LaTeX source files for the paper. Paper figures are in `paper/figures`.


## Citation
Please use the following citation:
