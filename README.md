# OS-Project-1
**The parent communicates with the child using pipes.**

In this project, you should read in a file name from the terminal. The given skel.cpp runs a for loop over a set of hash programs. In each iteration of this for loop, a child process is forked. The parent sends the file name to the child. The child calls a function (popen) to compute the respective hash (as specified by the hash program) of the file name. The child sends the computed hash value back to the parent.
The parent communicates with the child using pipes.
Starter code is provided to you in skel.cpp. A lot of hints in the form of comments are also provided in skel.cpp. You should add your code to the given starter code, wherever the comments guide you to do that. Over and above that, you should remember to add code where it is important for completing any task (the comments may not always be provided for everything).
