# Computer Science and Engineering Roadmap and Checklist

> This is the complete syllabus of _Computer Science and Engineering UG_.

#### Computer Science is divided in 4 parts
 - [Computer Science 1](#computer-science---1) : Hardware and Engineering part.
 - [Computer Science 2](#computer-science---2) : Everything that is required to write Programs.
 - [Computer Science 3](#computer-science---3) : Daily Computer Science.
 - [Computer Science 4](#computer-science---4) : Real Life Applications of CS.

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
- [Artificial Intelligence](#artificial-intelligence)
 #### [Computer Science 3](#computer-science---3)
- [Operating Systems](#operating-systems)
- [Computer Networks](#computer-networks)
- [DBMS and SQL](#dbms-and-sql)
- [Software Engineering](#software-engineering-after-learning-the-above)
 #### [Computer Science 4](#computer-science---4)
- [Cryptography](#cryptography)
- [Machine Learning](#machine-learning)
- [Computer Graphics](#computer-graphics)
- [Web Dev](#web-dev)

## Computer Science - 1

## Digital Electronics

- [ ] **[Boolean Algebra](http://www.uop.edu.pk/ocontents/ELEC-DIGE-S3%20Boolean%20Algebra%20Laws%20.pdf)**
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
   - Endianness (Big, Little)
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
    
    
- [ ] **C++** (You can try ***Python** for same topics)
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
    
## Artificial Intelligence

- [ ] **Knowledge Representation** and **Reasoning**
- [ ] **State Space**
- [ ] **Search**
    - [Hill Climbing](https://www.javatpoint.com/hill-climbing-algorithm-in-ai)<sup>Must know</sup>
    - [A*](https://www.ics.uci.edu/~kkask/Fall-2016%20CS271/slides/03-InformedHeuristicSearch.pdf)<sup>Must know</sup>
    - [MinMax](http://web.mit.edu/sp.268/www/gamesearch.pdf)<sup>Easiest Algorithm in AI</sup>
- [ ] **Neural Networks**
    - Weights and Layers
    - Gradient Descent

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
[DMBS Tutorial Reference](https://www.scaler.com/topics/dbms/)
    
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

## Cryptography and Network Security

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
 - [ ] **Firewalls**


### Data Science and Machine Learning

- [ ] **[Bias and Variance](https://svivek.com/teaching/lectures/slides/loss-minimization/bias-variance.pdf)**

- [ ] **Supervised Learning**
   - [ ] [Classification](https://cogitoai.home.blog/2019/08/21/what-is-classification-in-machine-learning/)
   - [ ] [Regression](https://www.topcoder.com/thrive/articles/introduction-to-linear-regression)

- [ ] **Un-supervised Learning**
   - [ ] [Clustering](https://scikit-learn.org/stable/modules/clustering.html)
   - [ ] [k-Nearest Neighbours](https://web.iitd.ac.in/~bspanda/KNN%20presentation.pdf)

- [ ] **[Image Processing](https://homepages.inf.ed.ac.uk/rbf/HIPR2/wksheets.htm)**<sup>Worth learning</sup>
    - [Transformation](http://www.it.hiof.no/~borres/j3d/math/twod/p-twod.html) and [Translation](https://homepages.inf.ed.ac.uk/rbf/HIPR2/translte.htm)
    

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
    - [DNS and Domain Names](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name)
    - [JSON and other formats](https://www.zionandzion.com/json-vs-xml-vs-toml-vs-cson-vs-yaml/) and [YAML](https://yaml.org/)

- [ ] **BackEnd**
    - [Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)


## [Computer Graphics](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/)

> Not mandatory, just get the overview

- [ ] **Concepts and principles**
    - [Pixels](http://math.hws.edu/graphicsbook/c2/s1.html)
    - [Rendering](https://github.com/ssloy/tinyrenderer/wiki)
    - [Shading](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/LightingAndShading.html)
    - [Texturing](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/TextureMapping.html)
    - [Ray Tracing](https://raytracing.github.io/books/RayTracingInOneWeekend.html)
    - [Raycasting](http://web.cs.wpi.edu/~matt/courses/cs563/talks/powwie/p1/ray-cast.htm)


After you are done with all this and want to make projects, check out [Projects you can make](https://github.com/apeman/awesome_computer_science/blob/master/what-should-i-code.md)

## LICENSE

[Mozilla-Public-License](./LICENSE.txt)
