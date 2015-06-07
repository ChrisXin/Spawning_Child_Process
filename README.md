# Spawning_Child_Process


When a process spawns a child, the child will need resources from the parent.
e.g. user clicks an Email link on Email Client, and Email client spawns the web browser with the specific address.


The workflow in UNIX is as follows:
1. the parent spawns the child process with the fork system call.
2. fork creates a new process
3. one of the processes may use the exec system call, to replace its memory space with a new program.
     
