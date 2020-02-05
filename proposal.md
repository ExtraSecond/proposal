# Fuzzing ext file system

Fuzzing is a popular technique for finding software bugs. 
Yet kernel level programs like file systems are hard to fuzz as they involve user input(system call) and internal state at the same time.
In this work, we would focus on vulnerabilities in ext file system family.
We would use [JANUS](https://taesoo.kim/pubs/2019/xu:janus.pdf) as our primary tool to do an extensive research in finding the bugs in ext 3 and ext 4.

The major goal of this research is to give us more insight on how the file systems are designed and how can we fuzz them.
Along the way We would also try to improve JANUS to help us better understanding file system designs and find better ways to do fuzzing.
We hope this work can be extended to kernel fuzzing to improve kernel reliability.

# IoT OS in Rust