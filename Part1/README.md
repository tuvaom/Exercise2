# Mutex and Channel basics

### What is an atomic operation?
> A operation is atomic if it is not aware of the existence of other tasks while it is running.

### What is a semaphore?
> It is a way of limiting the number of consumers for a specific resource. Ex: to limit the number of simultaneous calls to a database in an application.

### What is a mutex?
> Mutual exclusion is used to protect shared resources. It blocks the resources for all threads but one at once.

### What is the difference between a mutex and a binary semaphore?
> Only the thread that locked or acquired the mutex can unlock it, while for a semaphore, a thread waiting on it can be signaled by a different thread. A mutex is a locking mechanism, the semaphore is a signaling mechanism.

### What is a critical section?
> Sequence of statements that we need to execute indivisibly

### What is the difference between race conditions and data races?
 > Race conditions is a flaw where timing/order of events affects the correctness of the program. Data races are when there are two accesses in a program where both target the same location

### List some advantages of using message passing over lock-based synchronization primitives.
> Tillater mer tydlige grenser for ansvar. Reduserer kompleksjonen av data og utførelse. Reduserer muligheten for å få tak i ting du ikke skal ha tak i, mere oversiktelig

### List some advantages of using lock-based synchronization primitives over message passing.
> Effektivitet. Performance. 
