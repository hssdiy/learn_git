# learn_git

changed by user A

changed by user B

changed by user B as well

test upstream (my understanding: upstream is the alias of the base repository)


create some conflicts here

is my understanding correct? 

yes, my understanding is correct. upstream is the alias of the source repository (https://github.com/stephenchenxj/learn_git) where the current remote repository (https://github.com/hssdiy/learn_git) is forked from.
either upstream, or the full url address could be used to tell git where to pull the code.

updated in branch_test.

test user stephenchenxj on the raspberry pi system (hssdiy SSH key is stored on raspberry pi)
test conclusion: if the hssdiy account setting does not give others Push Access, then they can't push their changes into this repository

created a branch_local_remote_test branch locally. can't see this branch in remote yet 

can't push local branch branch_local_remote_test to the remote master branch using 'git push origin/master branch_local_remote_test'

the correct command is 'git push origin branch_local_remote_test'. 

after this, a branch: branch_local_remote_test is created in the remote repository.

  
