The Algorithm that is used in the main PageFault.java is "Not Recently Used", it replaces the pages base on the time, the page that is not used for a while will be replaced for making space for new pages in memory .

The output files shows the page fault that we had during the runtime and the algorithm is NRU, it will replace the page that has been not used for a long time and it has a flag for it as M for Modify.

For implementing "Round Roubin" and "Least Recently Used" we need to change the part that select the page for the replacement in PageFault.java file and select the page base on the algorithm.
