# 15213-Introduction-to-Computer-Systems

The following contains work from the course [15-213 Introduction to Computer Systems](http://www.cs.cmu.edu/afs/cs/academic/class/15213-s20/www/index.html). This course contained 8 assignments including:

__1. C Programming Lab__

  > This lab consisted of implementing a deque as a singly-linked list with additional features to support efficient operations.
  
__2. Data Lab__

  > This lab involved solving several puzzles that required bit manipulations of integers and floating point numbers.

__3. Bomb Lab__

  > This lab involved "defusing" a personalized binary executable bomb that required reading the assembly code of the bomb and using GDB to determine which inputs would result in the correct output.

__4. Attack Lab__

  > This lab consisted of exploiting security vulnerabilities through injections, ROP attacks, and buffer overflows. I used GDB and read the assembly code to learn about the system stack, registers, and other parameter-passing mechanisms of x86-64 machine code and used that knowledge to exploit the personalized code.

__5. Cache Lab__

  > In this lab, I first wrote a C program that simulates the hit, miss, and evict behavior of a cache memory with a least-recently used replacement policy. After reading all the lines of the trace, it will output the total number of hits, misses, and evictions. In addition, it will output the number of dirty bytes that have been evicted and the number of dirty bytes still in the cache. Then, I optimized a matrix transpose function, with the goal of minimizing the number of cache misses.

__6. Malloc Lab__

  > This lab consisted of writing a A 64-bit struct-based segregated free list dynamic memory allocator that supported the malloc, free, realloc, and calloc functions with first-find fit algorithm, no footers, and minimum block size of 16 bytes. My implementation uses segregated circularly doubly-linked lists to hold free blocks and a singly linked list to hold free blocks that are the minimum block size (16 bytes). It uses a first find algorithm to find a free block whenever malloc is called. This code performed above the utilization and throughput thresholds set by the course.

__7. Shell Lab__

  > This lab involved creating a shell program with job control. I created an interactive command-line interpreter that reads the prompt from the user and and executes the command of the corresponding prompt. The builtin commands for this shell include: quit, jobs, bg job, and fg job. This shell can run programs both in the foreground and background, as well as handle SIGINT and SIGSTP signals, reap all of its zombie children, and support I/O redirection.

__8. Proxy Lab__

  > In this lab, we created a web proxy server with concurrent threads and cache storage. This web proxy handles HTTP GET requests from the client and can also handle multiple concurrent requests - so, while the proxy is waiting for a response from a web server, it can begin to work on another pending request from another client. This is accomplished using threads. The proxy also uses a cache to store recently used web objects (implemented as an LRU cache with a singly-linked list). The server has a mutual exclusion lock to control access to the cache to ensure that the cache is thread-safe.
