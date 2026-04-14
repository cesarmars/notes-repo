# Motivation

Cache is high speed memory storage that stores a subset of data in a transiet way, memory that
can be obtain fast.

Caches allow us to 

- fetch memory/information faster because it is closer to the CPU (locality)
- get more power efficiency compared to RAM
- scale to multiple CPU'S

# Memory analogy, The Library

Consider a large library like Main Stacks. You are a student tyring
to find a book, where we ,

- search a large card catalog
- check out the book

Large library = search longer/slower. 

Having such an expansive library can 
cause very slow searches, very similar to technology we use like
in terms of accessing memory:

- DRAM = Dynamic random access memory
- SRAM = Static random access memory

DRAM and SRAM refers to RAM inside our computers. DRAM is the most
common/standard. Whenever, someone says DDR(Double data rate), they 
refer to the underlying technology DRAM. DDR is just the interface 
on top of the DRAM that transfers data.

But the goal here is to have large memory yet fast memory access 
(impossible in theory).


Still using the library analogy, in order to have that illusion, of
large memory fast memory access, we can think of the term locality, 
remember what you used and storing it. 

- searching up a book through a catlog
- checkout the book
- place book in desk
- repeat if needed

Where 

- Desk = memory cache
- Main Stacks = main memory
- Books = data blocks
- Student = cpu

Here, the student(cpu) goes to the library(main memory), looks for
books(data), then the student saves his books to his 
desk(memory cache), in which the desk remembers his books
(data).


The locality here is the pattern in which the student(cpu) keeps 
grabbing.

If 

- student(cpu) keeps coming back for the same book(data) 
= temporal locality
- student(cpu) keeps grabbing books(data) that are in a 
sequential order = spaital locality.








  



