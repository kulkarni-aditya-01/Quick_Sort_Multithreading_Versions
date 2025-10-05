Quick Sort with the Multithreading version
This is the unique project of the sorting algorithm where i have implemented the multithreaded version of Quick Sort 

Simple view of my project is : 
1. Read the 100k integers with the parsin file such as read the integer from the every line of the file as string convert it into the integer 
for this <code> strtok(NULL, line) <code> functions helps me from the c langugae
2.After the readin then flows goes like a to create the partition with the different types two faamous are : "Hoare's Partition" and "Lomatous Partition"
> for the lomatous partition it is not the cache friendly and it is hard to perfom good while using the -E core
> Hoares is good for the performance but hard for the partition to create because every time it has to run as N time for the cehcking the pivot index
> Based on this i have generated the perf data
3. Now it time to creat the thread for making the partition my idea is i have created the thread for the partiiton whi has the total integetrs >35k
> It serves me as good cache friednly also supportive for the perfomance
> Create the threads as much as how cores are there so for thta i have used the system call from the c library
4. Final part is that i have gatered the "Perf" profiling for the every algorithm that i hav tried and also creayed the flame graph for it also 
