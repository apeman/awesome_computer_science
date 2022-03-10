# Computer Science and Engineering Roadmap and Checklist

> This is the complete syllabus of _Computer Science and Engineering UG_.

#### Computer Science is divided in 4 parts
 - [Computer Science 1](#computer-science---1) : Hardware and Engineering part.
 - [Computer Science 2](#computer-science---2) : Everything that is required to write Programs.
 - [Computer Science 3](#computer-science---3) : Trinity of Computer Science.
 - [Computer Science 4](#computer-science---4) : Real Life Applications of CS. **This is optional**


**Mathematics is not mandatory but will be of good help while programming**

[**Discrete Mathematics**](http://home.iitk.ac.in/~arlal/book/mth202.pdf) is necessary for understanding Graphs.

 - [Mathematics Syllabus can be found here](https://github.com/apeman/awesome_computer_science/blob/master/Mathematics.md)

## Table of Contents

 #### [Computer Science 1](#computer-science---1)
- [Digital Electronics](#digital-electronics)
- [Computer Organization and Architecture](#computer-organization-and-architecture)
- [Theory of Computation and Automata](#theory-of-computation-and-automata)
 #### [Computer Science 2](#computer-science---2)
- [Compiler Design](#compiler-design)
- [Programming](#programming)
- [Data Structures](#data-structures)
- [Algorithms](#algorithms)
 #### [Computer Science 3](#computer-science---3)
- [DBMS and SQL](#dbms-and-sql)
- [Operating Systems](#operating-systems)
- [Computer Networks](#computer-networks)
- [Software Engineering](#software-engineering-after-learning-the-above)
 #### [Computer Science 4](#computer-science---4)
- [Cryptography](#cryptography)
- [Artificial Intelligence](#artificial-intelligence)
- [Machine Learning](#machine-learning)
- [Computer Graphics](#computer-graphics)
- [Web Dev](#web-dev)

## Computer Science - 1

## Digital Electronics

- [ ] **Boolean Algebra**
   - Number System
   - Addition, Subtraction
   - Multiplication, Division
   - 1's, 2's compliments
   - k-maps

- [ ] **Hardware**
   - Logic Gates
   - Flip-Flops and Latches
   - Adder - Subtractor
   - Encoder - Decoder
   - Multiplexer - Demultiplexer
   - Integrated Circuits
   - [Printed Circuit Boards](https://www.youtube.com/watch?v=ljOoGyCso8s)

## Computer Organization and Architecture

- [ ] **Computer Organization**
   - Address Bus, Data Bus
   - ROM, EPROM, RAM
   - Memory Hierarchy, Cache Memory, Virtual Memory
   - Secondary Storage
   - Programmable Logic Devices and Controllers
   - Input - Output Devices

- [ ] **Computer Architecture**
   - Stack
   - Registers
   - Endian_ness
   - Floating Point Numbers
   - Addressing Modes
   - Pipelining
   - Interrupts
   - RISC - CISC
   - aarch64, Intel_x86 / AMD64, MIPS / RISC-V (learn the differences)
   - [Assembly Language](https://stackoverflow.com/questions/1933801/x86-assembly-reference-sheet) (basic instructions)

## Theory of Computation and Automata

- [ ] **Automata and Languages**
   - NFA - DFA - NDFA
   - Regular Expressions
   - Context-Free Languages and Grammers
   - Pushdown Automata
   - Turing Machines
   - Decidability of Languages
   - Reducibility of Languages
   - Complexity Theory : P vs NP

## Computer Science - 2

## Compiler Design

- [ ] **Compiler Design**
    > Also used in NLP
   - Lexical analysis
   - Syntax analysis
   - Type Checking
   - Intermediate code generation
   - Machine code generation
   - Assembly and linking
   - Analysis and optimisation
   - Memory management
   - Interpreters

## Programming

- [ ] **Learn C**
    > The language almost every computer knows
    - Character constants, escape sequences, string constants
    - Data types and Type conversion
    - Precedence and associativity of operators
    - Functions
    - storage class and variable scope
    - if, for, while, switch_case
    - break, continue, goto
    - Arrays, Strings, Pointers
    - Structs, Union, enum, typedef
    - Header files, #MACROS
    - malloc, calloc, realloc, argc argv
    - file iO, streams
    - <Math.h>
    
    
- [ ] **C++**
    > Used in almost everything from Games to Browsers to Machine learning and beyond
    - Everything mentioned in C
    - Classes and Objects
    - Member Functions
    - Function Overloading
    - Constructor and Destructors
    - Inheritence, Polymorphism
    - Access Controls

## Data Structures

- **[Linked Lists](https://www.cs.cmu.edu/~adamchik/15-121/lectures/Linked%20Lists/linked%20lists.html)**
- **[Skip Lists](https://www.cs.cmu.edu/~ckingsf/bioinfo-lectures/skiplists.pdf)**<sup>PDF</sup>
  - [Skip-Lists done right](http://ticki.github.io/blog/skip-lists-done-right/)<sup>Suggested Reading</sup>
- **Hash Tables**
- **stack** and **queues** and **sets**
- [ ] **Trees** and **Tries**
    - [ ] Self Balancing Trees
    - [ ] n-ary Trees
    - [ ] 2-3 Trees
- [ ] **Graphs**
    - [ ] Adjacency matrix vs Adjacency list

## [Algorithms](https://xlinux.nist.gov/dads/)

- [ ] **Searching**
    - [ ] Breadth First Search
    - [ ] Depth First Search
- [ ] **[Sorting](https://en.wikipedia.org/wiki/Sorting_algorithm)**
    - [ ] Merge Sort
    - [ ] Quick Sort
    - [ ] Insertion Sort
    - [ ] Selection Sort
- [ ] **Graph Traversal**
    - [ ] Minimum Spanning Trees
    - [ ] Shortest Paths
- [ ] **space-time Complexity** 

## Computer Science - 3

## DBMS and SQL

- [ ] **[SQL](https://www.javatpoint.com/sql-tutorial)**
    - [ ] **Data Definition Language**
     - CREATE
     - DROP
     - ALTER
     - TRUNCATE
    - [ ] **Data Query Language**
     - SELECT
    - [ ] **Data Manipulation Language**
     - INSERT
     - UPDATE
     - DELETE
    - [ ] **Data Control Language**
     - GRANT
     - REVOKE
    - [ ] **Transction Control Language**
     - COMMIT
     - ROLLBACK
     - SAVEPOINT
    - [ ] **JOINS**
     - FULL OUTER JOIN
     - LEFT JOIN
     - RIGHT JOIN
     - NATURAL JOIN
     - LEFT OUTER JOIN
     - RIGHT OUTER JOIN

- **[DataBase Management Systems](https://www.javatpoint.com/dbms-tutorial)**
    - Entity-Relationship model.
    - [ ] **Integrity Constraints**
     - Primary Key and Foreign key
     - Composite keys
     - All other types of keys
    - [ ] Normal Forms : 1NF to 4 NF
    - [ ] File Organization.
    - [ ] Indexing (B- Trees and B+ Trees)
    - [ ] **Transactions and Concurrency Control**
    - Conflict Serializability
    - Locking
    - ACID | BASE
    
    
## [Operating Systems](http://pages.cs.wisc.edu/~remzi/OSTEP/)
   - The Boot Process
- [ ] **Processes and Threads**
  - Process Control Block
  - Dispatcher and Scheduler
- [ ] **Inter Process Communication**
  - Mesage Passing
  - Shared Memory 
- [ ] **Scheduling Algorithms**
  - Round Robin.
  - Shortest Remaining Time First.
  - Least Recently Used.  
- [ ] **Deadlocks**
  - MutEx and Locks
  - Semaphores
  - Banker's Algorithm
- [ ] **Memory Management**
  - Paging and Page tables
  - Segmentation
  - First Fit, Next Fit, Best Fit
  - Non-continuous Allocation
- [ ] **Virtual memory**
  - Page Faults
  - Page Replacement Algorithms
  - Belady’s Anomaly
- [ ] **File Systems**
  - File Allocation Tables.
  - Disk Scheduling Algorithms

## Computer Networks

- [ ] **Layers of TCP and OSI**
    - Application.
    - Presentation.
    - Session.
    - Transport.
    - Network.
    - Data.
    - Physical.

- [ ] **Flow Control**
    - Flow Control
    - Congestion Control
    - Error Control
    
- [ ] **Routers and Routing Algorithms**
    - DHCP and static routing
    - Round Robin and others
    - DHCP | ICMP
    
- [ ] **UDP and Sockets**

- [ ] **IPv4 | IPv6**
    
- [ ] **Application Layer Protocols**
    - HTTP | FTP
    - DNS | SMTP
    - Email MIME Types | POP | IMAP

## Software Engineering <sup>After learning the above</sup>

- [ ] **Software development models**
    - Waterfall
    - Spiral
    - Iterative
    - Agile

- [ ] **Software Cost Estimation**

- [ ] **COCOMO Model**

- [ ] **Risk Management**

- [ ] **Personnel Planning**

- [ ] **Software Requirement**
    - Software Requirement Specifications
    - Data Flow Diagrams

- [ ] **Software Quality**
    - ISO standards 9001, 14001
    - SEICMM
    - Six Sigma

- [ ] **Software Design**
    - Software Design Principles
    - Coupling and Cohesion
    - Object-Oriented Design
    - User Interface Design

- [ ] **Testing**

## Computer Science - 4 
_You will need these when you make projects_

## Cryptography

- [ ] **Encryption Algorithms**
    - DES, AES, Whirlpool, One Time Pad
- [ ] **Hashing Algorithms**
    - SHA family
- [ ] **Key Distribution**
    - RSA, Kerberos
- [ ] **Digital Signatures**
    - Message Digest    
 - [ ] **Compression**
    - [History](https://www.hanshq.net/zip.html#huffman).
    
## Artificial Intelligence

- [ ] **Knowledge Representation** and **Reasoning**
- [ ] **State Space**
- [ ] **Search**
    - Hill Climbing.
    - A*.
    - MinMax.
- [ ] **Neural Networks**
    - Weights and Layers
    - Gradient Descent


### Data Science and Machine Learning

- [ ] **Bias and Variance**

- [ ] **Supervised Learning**
   - [ ] Classification
   - [ ] Regression

- [ ] **Un-supervised Learning**
   - [ ] Clustering
   - [ ] k-Nearest Neighbours

- [ ] **Image Processing**<sup>Worth learning</sup>
    - [Transformation](http://www.it.hiof.no/~borres/j3d/math/twod/p-twod.html) and [Translation]
    

## Web Development
> You can study Web Development from [Mozilla Developer Network Website](https://developer.mozilla.org/en-US/docs/Web/Tutorials).

- [MDN Getting Started Guide](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
- [ ] **Front-End**
    - [HTML5](https://developer.mozilla.org/en-US/docs/Learn/HTML)
    - [CSS3](https://developer.mozilla.org/en-US/docs/Learn/CSS)
    - [JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
    - [Web Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms) 
    - [Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility) 
    - [Tools and Testing](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing)
    - DNS and Domain Names
    - JSON and YAML


## [Computer Graphics](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/)

> Not mandatory, just get the overview

- [ ] **Concepts and principles**
    - [Pixels](http://math.hws.edu/graphicsbook/c2/s1.html)
    - [Rendering](https://github.com/ssloy/tinyrenderer/wiki)
    - [Shading](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/LightingAndShading.html)
    - [Texturing](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/TextureMapping.html)
    - [Ray Tracing](https://raytracing.github.io/books/RayTracingInOneWeekend.html)
    - [Raycasting](http://web.cs.wpi.edu/~matt/courses/cs563/talks/powwie/p1/ray-cast.htm)


## LICENSE

[Mozilla-Public-License](./LICENSE.txt)
