# Report 3
## All Group Choice Options (1-3) from Lab 5
**Streamlining ssh Configuration**

So first I create and edit the config file in .ssh by using VSCode shown below.
![config file](config_edit.png)
Thus now I can use ssh and scp commands directly.
The ssh command results here below.
![login](ssh.png)
The scp that copy a file to the server results here below.
![copy](copy.png)
Here we can see that the top ls shows the existing files inside. Then by using the scp command and the local computer (my own computer), and then use ssh command to log into the server and use ls to check again, we can find that the copied file appears on the server.

**Setup Github Access from ieng6**

Here is public key on github.
![github pubkey](githubkey.png)
Here is keys on server
![server keys](serverkey.png)
Then I made a clone and made some changes (not shown), then commit and push it back just like shown below.
![commitpush](commitandpush.png)
The link to this commit is [here](https://github.com/Solitar7/markdown-parser/commit/c64728c4e9146cb530bdb2b6f118f7c355121539).

**Copy whole directories with scp -r**

Now I need to copy the whole directory of markdown-parser.
![copywhole](copywhole.png)
Though there are a lot of files, they are still all copied (not all shown in the graph).
Then I get on the server and compile and run the test.
![runtest](runtest.png)
We can see first some copied files on the top of this screenshot and then also test run successfully.
Now, I'm going to run all the commands in one line.




