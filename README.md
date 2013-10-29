loose_coupling_task_system
==========================

Idea of task pool: In ideal task pool, everyone go and pick the task that matches to his/her ability, work on the task till that is finalized and continue pick next one. There is no fixed schedule of person, thus the idea of department/company can be omitted in that environment, task based work for everyone. 

Low Coupling Software task system: 

Roles: Product manager, Project manager, UI designer (U), Architecture (A), Programmer(P), QC, QA. (QC QA  are not my area so i may mess them up, the the basic idea is the same as U/A/P) 

U, A, P - group divisions: 
a). Based on the knowledge/skill they can be divided into different groups, from top to down : G1 … Gn. Everyone can work on tasks that has been assigned belong/below his group level.

b). Based on the experience (current or previous Related project), they can be divide into different module groups (same level),   M1…Mn. Everyone can work on the modules that he owns. 

1. Task creation
Who - Project Manager (May be Product manager but not that often), QA 
What - describe the expected input and output, describe necessery corner cases,
When - expected time (optional)

2. Task Analysis
Who - Project Manager
What - describe what aspects will the task effect, define the module - Mx1 and first time define group - Gx1.
When - define a expected time T1. 

3. Task Design.  
Who - UI designer (Prior, if there are UI design requirement), Architecture
What - U/A, they will pick up the tasks after task analysis. (U) Define the UI elements and sequence for all the possible cases. (A) Define the code area, function flows, algorithm, data formats.   (A) has right to negotiated with Project Manager for new module Mx1 or new Group Gx2. 
When - (A) gives new expected time T2. (Finally call )

4. Task execution.
Who - Programmer, based on their group level and module division, they will pick up the tasks after design. 
What - Implement according to the design. Give feed back to (U) & (A) to adjust the design if necessary.  (Could return to step 2/3)
When - After finish implementation, write down the exact time cost. T3.  

5. Task verify.
Who - QA, QC, based on their group level and module division, they will pick up the tasks after execution. 
What - Verify the task implementation(execution) matches the requirements & design. (Could return to step 2/3/4)
When - verify scope depends on Mx. 

6. Task finalize: 
Who - creator of the task
What - confirm the expected has met.  (could return to 2)
When - depends. 


KEY - 
1. Each time there will only have one assigner at most. And the timing cost will count to the assigner. So it will be very clear for the time distribution. 
2. KPI - everyone can have a clear list of his tasks, depends on the task level and his level, KPI will become quantitative.   Of course you may be promoted or reduced according the task status. 
3. Ideally - one can not go and pick the task before he finishes his current task, but based on the task priority, this can be adjusted. 
4. Accuracy -  There are many estimate in this task working sequence, thus the accuracy of the estimate time compare to cost will also be a measure for the people make them.
 




