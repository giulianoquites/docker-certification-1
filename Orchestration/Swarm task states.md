# Swarm task states
- NEW	The task was initialized.
- PENDING	Resources for the task were allocated.
- ASSIGNED	Docker assigned the task to nodes.
- ACCEPTED	The task was accepted by a worker node. If a worker node rejects the task, the state changes to REJECTED.
- PREPARING	Docker is preparing the task.
- STARTING	Docker is starting the task.
- RUNNING	The task is executing.
- COMPLETE	The task exited without an error code.
- FAILED	The task exited with an error code.
- SHUTDOWN	Docker requested the task to shut down.
- REJECTED	The worker node rejected the task.
- ORPHANED	The node was down for too long.
- REMOVE	The task is not terminal but the associated service was removed or scaled down.