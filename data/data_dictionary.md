column | description
-------|---------
JOBID | The identification number of the job or job step. Regular jobs are in the form JobID and array jobs are in the form ArrayJobID_ArrayTaskID
ACCOUNT | The account under which the job was submitted
USER | The user who submitted the job
USEDMEM | Used memory in megabytes per-node
REQTIME | Requested time in d-hh:mm:ss or hh:mm:ss
USEDTIME | Used time in d-hh:mm:ss or hh:mm:ss
NODES | Number of servers used for this job
CPUS | Total number of CPU-cores allocated to the job
GPUS | Total number of GPUs allocated to the job
PARTITION | Identifies the partition on which the job ran.
EXITCODE | The exit code returned by the job script or salloc, typically as set by the exit() function. Following the colon is the signal that caused the process to terminate if it was terminated by a signal.
STATE | Job state or status (COMPLETED, CANCELLED, FAILED, TIMEOUT, PREEMPTED, etc.)