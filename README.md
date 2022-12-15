My previous project, buffered_io, which worked for for single-threaded processes, now updated for multi-threaded processes.


Contains the IO61 library, which is a single-slot cache—that you will modify to:

Add support for file range locks, or “flocks” for short. A flock allows a thread to lock a specific range of bytes within a file.
Implement thread safety for all operations.
