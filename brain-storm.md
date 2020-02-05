# Proj Proposals

## 2FA - Jingyuan

[paper](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-reaves_paper.pdf)

How to protect a 2FA server? 

## Sandbox - Completed

[paper](https://www.usenix.org/legacy/publications/library/proceedings/sec96/full_papers/goldberg/goldberg.pdf)  
[github](https://github.com/DataCorrupted/sandbox)

## Fuzz file system - Peter

[paper](https://taesoo.kim/pubs/2019/xu:janus.pdf)  
[video](https://www.youtube.com/watch?v=UbzZDjk2lsI)  

Ceph FS  
[exFAT](https://en.wikipedia.org/wiki/ExFAT)  
Fuzz CUDA  

## Embeded/IoT - Haitian

## BlockChain - Yubo

[paper](https://bitcoin.org/bitcoin.pdf)  
[github](https://github.com/ecs251-w19-ucdavis/Blockchain)  

# Fuzzing ext file system

Fuzzing is a popular technique for finding software bugs. 
Yet kernel level programs like file systems are hard to fuzz as they involve user input(system call) and internal state at the same time.
In this work, we would focus on vulnerabilities in ext file system family.
We would use [JANUS](https://taesoo.kim/pubs/2019/xu:janus.pdf) as our primary tool to do an extensive research in finding the bugs in ext 3 and ext 4.

The major goal of this research is to give us more insight on how the file systems are designed and how can we fuzz them.
Along the way We would also try to improve JANUS to help us better understanding file system designs and find better ways to do fuzzing.
We hope this work can be extended to kernel fuzzing to improve kernel reliability.

