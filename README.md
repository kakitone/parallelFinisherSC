# parallelFinisherSC
Here are example commands to run the tool:

The standard way is as before. 

    python finisherSC.py destinedFolder mummerPath
	
For parallel access with 4 threads (you can replace 4 by other numbers, default is 1), 

    python finisherSC.py -par 4 destinedFolder mummerPath
    
For parallel access with 4 threads and with large contig file,

    python finisherSC.py -par 4 -l True destinedFolder mummerPath

For parallel access with 4 threads and with large contig file and in the fast mode,

    python finisherSC.py -par 4 -l True -f True destinedFolder mummerPath


For more help, 

    python finisherSC.py -h
