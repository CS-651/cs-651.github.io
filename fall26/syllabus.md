## [<< back](./index.html)

# CAS CS 651 -  Course Syllabus Fall 2026

**Instructors**: John Liagouris  
**Teaching Assistants**: Danesh Kohina

**Lectures**: Mon/Wed 2.30-3.45pm, PSY B53   
**Discussions**: Fri 2.30-3.20pm, CDS 364

**Instructor Office Hours**: Mon 4-5.30pm and Wed 4-5.30pm, CDS 721   
**TF Office Hours**: Wed 10-11.30am and Thursday 4-5.30pm, Grey lounge next to CDS 612

> **IMPORTANT**: Refrain from using email to reach the course staff. Use [Piazza](https://piazza.com/bu/fall2026/cs651) for all class communication.


## Learning Objectives
The goal of this course is to get you excited about the key ideas that have shaped modern distributed systems. By the end of the semester, you will:

- Have a solid understanding of fundamental concepts in distributed systems, such as asynchrony, concurrency,
parallelism, replication, fault tolerance, consensus, atomicity, and data consistency

- Be able to synthesize ideas and system design principles from the literature

- Be aware of problems you might face when developing distributed applications, trade-offs you need to consider, and tricky bits of distributed computing

- Feel comfortable about building distributed systems and applications

## Course Overview
CS 651 provides a programming-centric introduction to distributed systems. The course discusses computation and communication primitives, concurrency control, parallelism, replication, fault tolerance, distributed consensus, data consistency, sharding and consistent hashing, distributed transactions, cluster computing, distributed tracing, peer-to-peer systems, serverless, and systems for decentralized trust. Most lectures are centered on real case studies from industry. CS 651 is a graduate-level course that includes graded paper reading and requires independent exploration of the material. 

### Topics

- Computation and Communication Primitives (threads; remote procedure call)
- Concurrency Control (optimistic vs pessimistic)
- Replication and Faul Tolerance
- Data Consistency Models (linearizability; sequential consistency; causal consistency; eventual consistency)
- Distributed Consensus (OmniPaxos)
- Distributed Transactions (ACID; serializability; snapshot isolation; two-phase commit)
- Peer-to-peer Systems (DHTs; consistent hashing)
- Distributed Shared Memory 
- Publish/Subscribe Systems
- Distributed Computing (MapReduce; dataflow model)
- Cluster Management (resource consolidation; job scheduling)
- Serverless Computing
- Distributed Training (ML)
- Distributed Tracing (microservices)
- Decentralized Trust (blockchain; secure multiparty computation)


## Prerequisites
**CAS CS 350, CS 351, or equivalent (will be enforced!)**

CS 651 requires basic knowledge of computer systems. Students must also have good programming skills, otherwise it will be difficult to keep up with the load. Prior experience with parallel programming is a plus but not required to succeed in the course.

## Instructional Format and Course Materials

### 2.1 Courseware

We will use:

- The [course website](https://cs-651.github.io/fall26/index.html ) to maintain an up-to-date class schedule
- [Piazza](https://piazza.com/bu/fall2026/cs651) for announcements, questions, discussions, and all other communication
- [Github Classroom](https://github.com/CS-651/) for the discussions and assignments
- [Gradescope](https://www.gradescope.com/courses/1382855) for assignment submissions

### 2.2 Lectures
Lectures will be held during the assigned time slots. 
The [detailed lecture schedule](./lectures.html) provides the topic for each lecture. 
Lecture and lab slides will be made available on Piazza. Some lectures have pointers to assigned readings, which you should complete prior to the lecture.

#### Textbook
The course does not have a required textbook. The best material to study from are the lecture and lab slides, as well as the notes you take in class. If you are looking for additional resources, below are some good books on distributed systems:
 
- [Distributed Systems](https://www.distributed-systems.net/index.php/books/ds4/) 4th Edition (by Maarten van Steen, Andrew S. Tanenbaum). You can request a free pdf version of the book in the provided link.
- Distributed Systems: Concepts and Design (by G. Coulouris, J. Dollimore, T. Kindberg, Gordon Blair).
- Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems (by Martin Kleppmann).

### 2.3 Lab Discussions
Labs (Fri 2.30-3.20pm, CDS 364) are a core component of the course. Lab discsussions will be focusing on the following topics: 

- [Golang](https://go.dev) (basic syntax and data structures; goroutines; channels; mutexes; logging; race detector, etc.)
- Good (and bad) coding practices 
- Common mistakes (with concrete examples from previous iterations of the course)
- Programming assignments

Some labs may turn into OHs, depending on the progress we make. The TF will post information on Piazza as necessary. 

### 2.4 Programming Language and Software Tools
All programming assignments will be in [Golang](https://cacm.acm.org/research/the-go-programming-language-and-environment/), and we recommend using [VSCode](https://code.visualstudio.com/) for development. _No prior knowledge of Go is required to succeed in the course_; the lab sections will introduce you to the language features and the Go runtime.  

For code management, we will be using Git. You are expected to regularly push your code to your Github repository. 
We will provide instructions on how to set up your programming environment on [Piazza](https://piazza.com/bu/fall2026/cs651). Make sure your code is well-documented and _always use meaningful commit messages_. 
We will be using your Git commit history to track your progress and give you feedback.

### 2.5 Office Hours
We will be holding office hours four days a week to further discuss lecture material (with the instructor) and hands-on assignments (with the instructor or the TF). We may also have extra OHs before some assignment deadlines. The instructor and TF will be giving you advice on good coding practices but they are not supposed to debug your code. 
_Debugging is your responsibility_.

#### OH Schedule

- **Monday 4-5.30pm**: Instructor OH (CDS 721)
- **Wednesday 10-11.30am**: TF OH (grey lounge next to CDS 612)
- **Wednesday 4-5.30pm**: Instructor OH (CDS 721)
- **Thursday 4-5.30pm**: TF OH (grey lounge next to CDS 612)

## 3. Assignments, Quizes, Exams, and Grading Criteria

### 3.1 Grading Scheme

The course includes reading assignments, programming assignments, a midterm exam, and a final exam. 
Your final grade will be determined as follows:

- In-class Quizzes and Reading assignments: 20%
- Midterm exam: 30%
- Final exam: 30%
- Programming assignments: 20% (weights: A1: 10%,  A2: 10%, A3: 20%, A4: 30%, A5: 10% A6: 20%)

### 3.2 Midterm and Final Exams

The midterm will take place during lecture time (date TBD) and the final exam is scheduled on **December 14**.
Please plan your work and travel plans accordingly. Both exams are open-book; however, the use of electronic devices during the exams is strictly prohibited. You are only allowed to bring hard copies of the lecture and lab slides, your notes, and any papers we have covered in class.

### 3.3 Reading Assignments

Most lectures will have assigned readings with graded QA that you must submit to [Gradescope](https://www.gradescope.com/courses/1382855) _prior to_ the lecture. All questions and due dates will be posted on [Piazza](https://piazza.com/bu/fall2026/cs651). We will not accept late submissions for reading assignments. Please take a moment to review the guidelines on how to read research papers by [M. Mitzenmacher](https://www.eecs.harvard.edu/~michaelm/postscripts/ReadPaper.pdf) and [S. Keshav](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf) (also available on [Piazza](https://piazza.com/bu/fall2026/cs651)).

### 3.4 Programming Assignments

We will release 6 programming assignments during the semester:

| Assignment | Release Date | Due Date | Duration | 
|----------|----------|----------|----------|
| A1: Futures        |  9/4    |  9/11  |  1 week  |
| A2: MapReduce  |  9/14   |  9/25  |  2 weeks |
| A3: OmniPaxos A          |  9/28   |  10/9 | 2 weeks  |
| A4: OmniPaxos B           |  10/12  |  10/30 | 3 weeks |
| A5: PubSub A           |  11/2  |  11/13 | 2 weeks |
| A6: PubSub B              |  11/16  |  12/10 | 3 weeks |



**Deadlines are strict. There will be no extensions.** If you are unable to meet a deadline, you should contact the instructor in advance. Some assignments depend on previous ones and will be challenging. Remember: We are here to help!

## 4. Class and University Policies

### 4.1 Attendance
We will not be taking attendance in lectures and labs. All course material will be posted on Piazza. Ultimately, you are responsible for your own learning and for keeping up with the homework. Lectures and labs will not be recorded. If you are unable to attend a lecture or a lab discussion, please come to our OHs to catch up.

### 4.2 Academic Conduct

All hands-on assignments must be completed individually. Discussion with fellow students via Piazza or in person are encouraged, but presenting the work of another person as your own is strictly forbidden. This includes "borrowing", "stealing", copying programs/solutions (or parts of them) from others or public repositories. **We will be using automated plagiarism checkers**. If your submission has more than 50% similarity with another submission or a publicly available solution we have crawled from the Web, you will automatically receive 0 points. 

Please take the time to review the [CAS Academic Conduct Code](http://www.bu.edu/academics/resources/academic-conduct-code/). 

### 4.3 On the use of GenAI tools

You are free to use AI tools to help you with the assignments, e.g., for debugging, troubleshooting, and understanding the assignment skeletons. However, **asking an AI tool to generate an entire solution for you undermines the educational purpose of this course** and will most likely get you flagged for plagiarism. AI should amplify your understanding of the material, not replace it. Be aware that AI-generated content oftentimes contains errors, omissions, bugs, and misinterpretations that may impact your score. Do not trust anything that an LLM says before cross-checking with another source. 

## 5. Accommodations
If you are a student with a disability or believe you might have a disability that requires accommodations, please contact the Office for Disability Services (ODS) at (617) 353-3658 or access@bu.edu to coordinate any reasonable accommodation requests. ODS is located at 25 Buick Street on the 3rd floor.
