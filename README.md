# RaceConditionThread
Manage Race Condition example at multi-threaded applications c++

Racing Example
A race condition occurs when two or more threads can access shared data and they try to change it at the same time.
Because the thread scheduling algorithm can swap between threads at any time,
you don't know the order in which the threads will attempt to access the shared data.
Therefore, the result of the change in data is dependent on the thread scheduling algorithm,
i.e. both threads are "racing" to access/change the data.
