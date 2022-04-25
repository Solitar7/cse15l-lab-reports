# Report 2
## Debug MarkdownParse
**Code change 1**

First change:

First failure file [here](test-file.md)

First symptom below:
![first symptom](symptom1.png)

This is caused due to an infinite loop. Since the `indexOf` method return -1 if the required string is not found. So I change the code and check if it gets -1. And if it is -1, then break the loop. 