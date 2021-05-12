1.
merge test1 into master
2.
merge test2 into master, there is a conflict, and it's normal
3.
merge test1-1 into master, there is a conflict, and it's abnormal. 
As we supposed to develop upon the merge commit in step2 SHA-1: f5f696536dfd851fd1103aefcd30201b468d5b9d
And we will get a merge commit in this step, SHA-1: 05b8a32484cb77c40ec634a35af0156d69009103
4.
merge test-1-1-1 into master, and test-1-1-1 is based on test1-1, there is another conflict, also abnormal
The purpose is to verify how the conflict looks like

Conclusion:
We should not keep two long branches, it will be hard to maintain the conflict code 


