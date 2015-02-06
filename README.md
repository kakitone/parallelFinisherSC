# parallelFinisherSC
Here are example commands to run the tool:

The standard way is as before. 

    python finisherSC.py destinedFolder mummerPath
	
For parallel access with 4 threads, 

    python finisherSC.py -par 4 destinedFolder mummerPath
    
For parallel access with 4 threads and with large contig file,

    python finisherSC.py -par 4 -l True destinedFolder mummerPath

For more help, 

    python finisherSC.py -h
