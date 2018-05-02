Preface
=======

Simple file to keep track of various terms that keep coming up across readings
in systems and computer science.

Cache line Bouncing
-------------------

Cache Coherence
---------------

Cache Coherence Protocols
-------------------------


Cache Invalidation
------------------

Disk Buffer
-----------

Usually a piece of dedicated RAM/NVRAM built into a hard-disk or disk array
controller that provides hardware caching and faster throughput for bursty
writes.

Major Pagefault
---------------

Memory Fence
------------
Also known as memory barrier

MESI
----

Minor Pagefault
---------------

Mutex
-----

NVRAM
-----

Non-Volatile Random Access Memory. It is a type of memory that retains its
information when power is turned off. "Flash Storage" is quintisential
non-volatile memory. Write speed and durability are usually a concern when
compared to other forms of memory.

Page Cache
----------

AKA "Disk Cache" - not to be confused with "Disk Buffer".

A Page Cache is a cache for pages that are read from or written to secondary
storage, anything that is not RAM, such as disks, network filesystems etc. It
co-exists with regular application memory in RAM transparently, the operating
system uses unsed poritions of the main memory for the page cache. It's used to
speed up access to data/pages "on disk".

reference: ![IO Stack in the Linux Kernel](https://upload.wikimedia.org/wikipedia/commons/3/30/IO_stack_of_the_Linux_kernel.svg)


PMU (Performance Monitoring Unit)
---------------------------------

Reentrant Function
------------------

Semaphore
---------

TLB Shootdown
-------------

QSpinLock
---------

