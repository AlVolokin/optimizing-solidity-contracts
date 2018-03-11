The second pragma statement is unnecessary and wrongly written.

The contract “Member” is better as a library (no costly constructor for example), containing the data for each Member and the needed functionality. 

The variables tmp* are unnecessary, еspecially as state variables. The library functions are sufficient to fulfill the task.

