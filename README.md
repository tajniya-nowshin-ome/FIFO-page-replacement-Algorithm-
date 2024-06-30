# FIFO-page-replacement-Algorithm-

Experiment name : Implementation of FIFO-page-replacement-Algorithm

Description:

The FIFO algorithm is a straightforward method used in memory management within an operating system. 
Here’s how it works:

Queue-Based Approach:
The operating system maintains a queue (or list) of all pages currently in memory.
When a page needs to be replaced due to a page fault, the oldest page in the queue (the one that has been in memory the longest) is selected for replacement.

Replacement Process:
When a new page must be loaded into physical memory (due to a page fault), the FIFO algorithm identifies the oldest page in memory.
The newly needed page replaces the oldest page at the front of the queue.

Advantages and Limitations:
Advantage: Simplicity – FIFO is easy to implement.
Limitation: It doesn’t consider the actual usage patterns of pages, which can lead to suboptimal replacements.
