# 15213-Introduction-to-Computer-Systems

The following contains work from the course 15-213 Introduction to Computer Systems. This course contained 8 assignments including:

__1. L0 - C Programming Lab__

  > This lab consisted of implementing a deque as a singly-linked list with additional features to support efficient operations.
  
__2. L1 - Data Lab__

  > This lab involved solving several puzzles that required bit manipulations of integers and floating point numbers.

__3. L2 - Bomb Lab__

  > This lab involved "defusing" a personalized binary executable bomb that required reading the assembly code of the bomb and using GDB to determine which inputs would result in the correct output.

__4. L3 - Attack Lab__

  > This lab consisted of exploiting security vulnerabilities through injections, ROP attacks, and buffer overflows. I used GDB and read the assembly code to learn about the system stack, registers, and other parameter-passing mechanisms of x86-64 machine code and used that knowledge to exploit the personalized code.

__5. L4 - Cache Lab__

  > In this lab, I first wrote a C program that simulates the hit, miss, and evict behavior of a cache memory with a least-recently used replacement policy. After reading all the lines of the trace, it will output the total number of hits, misses, and evictions. In addition, it will output the number of dirty bytes that have been evicted and the number of dirty bytes still in the cache. Then, I optimized a matrix transpose function, with the goal of minimizing the number of cache misses.

__6. L5 - Malloc Lab__

  > This lab consisted of writing a A 64-bit struct-based segregated free list dynamic memory allocator that supported the malloc, free, realloc, and calloc functions with first-find fit algorithm, no footers, and minimum block size of 16 bytes. My implementation uses segregated circularly doubly-linked lists to hold free blocks and a singly linked list to hold free blocks that are the minimum block size (16 bytes). It uses a first find algorithm to find a free block whenever malloc is called. This code performed above the utilization and throughput thresholds set by the course.

__7. L6 - Shell Lab__

__8. L7 - Proxy Lab__
