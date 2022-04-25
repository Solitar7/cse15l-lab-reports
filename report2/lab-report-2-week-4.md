# Report 2
## Debug MarkdownParse
**Code Change 1**

First change:
![first change](change1.png)

First failure file [here](test-file.md)

First symptom below:
![first symptom](symptom1.png)

This is caused by an infinite loop. Since the `indexOf` method return -1 if the required string is not found. So I change the code and check if it gets -1. And if it is -1, then break the loop.

**Code Change 2**

Second change:
![second change]()

Second failure file [here](test-file3.md)

Second symptom below:
![second symptom](symptom2.png)

This is caused since bracket can be found but parenthesis cannot. So I decide to check the closeBracket, the openParen, and the closeParen. If one of them is -1, then directly go to the next loop with currentIndex go to openBracket + 1 in order to get the next openBracket.