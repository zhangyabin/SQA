#Basic concepts, definitions & terminology for Input Domain partitioning & testing
Partitioning of the input domain is an activity that seeks to group those inputs that will cause certain failures to be experienced. If one can show that inputs in a partition have a higher probability of either causing the system to fail or to succeed, then the statistical reliability analysis can be performed with fewer number of tests

Software testing is an important and a costly phase of the software development lifecycle. An approach is presented that improves the effectiveness of software testing based on partitioning the input domain.

Specifically, it is shown how partitioning can decrease the number of tests needed to find defects. The improvement is based on partitioning the input domain according to how different user-level functions of software read from and write to internal state variables.

Several parameters that influence the probability of finding defects are investigated with a computer simulation: the size of a test case, the type of a defect, the number of partitions, and the ratio of reading and writing accesses to state variables.
