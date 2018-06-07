# CS Curriculum Textbooks and References

- [Computer Organisation and Architecture](#computer-organisation-and-architecture)
- [Algorithm Design and Analysis](#algorithm-design-and-analysis)
- [Theory of Computation](#theory-of-computation)
- [Operating Systems](#operating-systems)
- [Data Communication](#data-communication)
- [Microprocessors and Microcontrollers](#microprocessors-and-microcontrollers)
- [Discrete Mathematics](#discrete-mathematics)
- [Computer Graphics](#computer-graphics)
- [Information Theory and Coding](#information-theory-and-coding)
- [Compiler Design](#compiler-design)
- [Computer Networks](#computer-networks)
- [Software Engineering](#software-engineering)

## Computer Organisation and Architecture

### Standard Textbooks

1. **Computer Architecture: A Quantitative Approach** - David A. Patterson and John L. Hennessy [1]
2. **Computer Organisation and Design: The Hardware/Software Interface** - David A. Patterson and John L. Hennessy [2]
3. **Computer Organisation** - V. C. Hamacher, Zvonko G. Vranesic and Safwat G. Zaky [3]

### Alternative/Supplementary

1. **Computer System Architecture** - M. Morris Mano [4]
2. **Computer Organization and Architecture: Designing for Performance** - William Stallings [5]
3. **Computer Architecture and Organisation** - John. P. Hayes [6]
4. **Computer Systems Design and Architecture** - Vincent P Heuring and Harry F Jordan
5. **Fundamentals of Computer Organization and Architecture** - Mostafa Abd-El-Barr and Hesham El-Rewini
6. **Computer Systems: a Programmer’s Perspective** - Randal E. Bryant and David R. O’Hallaron [7]
7. **Introduction to Computing Systems: From Bits and Gates to C and Beyond** - Patt and Patel [8]
8. **Structured Computer Organization** - Andrew S. Tanenbaum
9. **The Principles of Computer Hardware** - A. Clements
10. **Fundamentals of Computer Architecture** - M. Burrell
11. **Computer Architecture: Pipelined and Parallel Processor
Design** - Michael J. Flynn [9]

### Notes

There are plenty more books than listed and more courses than I'd care to link.

[1] - Widely regarded as an authoritative reference for Computer Organisation and Architecture. It is written by Turing Award winning Computer Scientists David Patterson and John Hennessy, but also assumes the reader is already well versed with concepts of Computer Architecture. For the beginner, [2] is widely recommended as _the_ book to start with. Used as a reference for

- [CS146 at Harvard](http://www.eecs.harvard.edu/~dbrooks/cs146-spring2004/)

[2] - [TYCS](https://teachyourselfcs.com/#architecture) recommends this excellent book (after going through **The Elements of Computing Systems** by Nishan and Schocken), as do I, for an introduction to the fundamental ideas of Computer Organisation and Architecture. It is extremely well written, has plenty of depth, and is built upon in [1] by the same authors. Used as a reference for

- [CS 312 at UMSL](http://www.cs.umsl.edu/~sanjiv/classes/cs312/)
- [ECE 411 at UI](https://ece.illinois.edu/academics/courses/profile/ECE411)
- [B62006Y-01 at ](http://english.ucas.ac.cn/index.php/admission/undergraduate/course-syllabuses/620-school-of-computer-and-control-engineering/4471-principles-of-computer-organization) (Note: Syllabus page only)
- [18-447 at CMU](http://www.ece.cmu.edu/~ece447/s13/doku.php?id=schedule) along with [8]
- [CS 3410 at Cornell](http://www.cs.cornell.edu/courses/cs3410/2016fa/)
- [CS 61C at Berkeley](http://www-inst.eecs.berkeley.edu/%7Ecs61c/sp15/#Resources)

[4] - I didn't find this book stimulating at all.

[6] - I found this book incredibly dull and difficult to understand. Good luck.

[7] - Used as the reference for

- [CS 2505 at VT](http://courses.cs.vt.edu/~cs2505/spring2018/)
- [15-213/18-213 at CMU](http://www.cs.cmu.edu/%7E213/)
- [CS107 at Stanford](http://web.stanford.edu/class/cs107/)

[9] - Used as the reference for

- [EE382 at Stanford](https://web.stanford.edu/class/ee382/)

## Algorithm Design and Analysis

### Standard Textbooks

1. **Introduction to Algorithms** - Thomas Cormen, C. Leiserson, and R. Rivest and C. Stein (*CLRS*) [1]
2. **Algorithm Design** - Jon Kleinberg and Éva Tardos (*KT*) [2]
3. **Algorithms** - Christos Papadimitriou, Sanjoy Dasgupta, and Umesh Vazirani (*DPV*) [3]

### Alternative/Supplementary

1. **The Algorithm Design Manual** - Steven Skiena [4]
2. **Algorithms** - Robert Sedgewick and Kevin Wayne [5]
3. **Introduction to Algorithms: A Creative Approach** - Udi Manber [6]
4. **Fundamentals of Computer Algorithms** - Ellis Horowitz, Sartaj Sahni and S. Rajasekaran
5. **An Introduction to the Analysis of Algorithms** - Robert Sedgewick and Philippe Flajolet
6. **Design and Analysis of Algorithm** - P. H. Dave and H. B. Dave
7. **Design Methods and Analysis of Algorithms** - S. K. Basu
8. **Algorithms in a Nutshell: A Practical Guide** - George T. Heineman and Gary Pollice
9. **Algorithm Design: Foundations, Analysis and Internet Examples** - Michael T. Goodrich and Roberto Tamassia

### Notes

- Algorithms are a vast topic and merit their own course altogether due to there being many subtopics such as randomised, parallel, approximation and so on, each having entire textbooks on them. This particular topic is meant to serve as an introduction to each subtopic by focusing on the underlying principles used in designing the algorithm. There are many MOOCs to cater to students, again linked [here]().
- There are, again, numerous resources on the web related to the topic and if a major course related to it hasn't made it to the list, contributions are extremely welcome.
- [CSC2420 at UoT](http://www.cs.toronto.edu/~bor/2420f12/) does not use a single source. Instead it uses a combination of [1], [3] and [2].
- [5] is used as the basis for [Sedgewick and Wayne's online course on Coursera](https://www.coursera.org/teach/algorithms-part1) with a [second part](https://www.coursera.org/teach/algorithms-part2).
- [2] has a revised version of slides to accompany the textbook available [here](http://www.cs.princeton.edu/~wayne/kleinberg-tardos/).
- [Algorithms, Etc. by Jeff Erickson](http://jeffe.cs.illinois.edu/teaching/algorithms/) is a set of notes that covers the material necessary for his course at University of Illinois.
- *TAOCP* also serves as a useful reference for many algorithms typically studied as part of an undergraduate level course. It is quite mathematical so typically many students find it a hard read.

[1] - Typically used as an encyclopedic reference for most topic, rather than an introduction to algorithms. Used as the reference for

- [CS 600 A at SIT](https://www.cs.stevens.edu/~swetzel/CS600/spring11/)
- [15-451/651 at CMU](https://www.cs.cmu.edu/~15451/) which also recommends [3] but either can be used, while an [older version](http://www.cs.cmu.edu/~avrim/451f09/index.html) has it's own set of notes
- [CS 466/666 at UoW](https://cs.uwaterloo.ca/~eblais/courses/F17/CS466/) with additional material described [here](https://cs.uwaterloo.ca/~eblais/courses/F17/CS466/outline.pdf)

[2] - Used as the reference for

- [CSci 256 at WC](https://www.cs.williams.edu/~lenhart/cs256/index.html)
- [CPSC500 at UBC](http://www.cs.ubc.ca/~condon/cpsc500/) with [3] additionally recommended along with other texts
- [CS 7200 at WU](http://cecs.wright.edu/~tkprasad/courses/cs7200/cs7200.html) with [1] additionally used for reference
- [CS 161 at Stanford](http://openclassroom.stanford.edu/MainFolder/CoursePage.php?course=IntroToAlgorithms) where Tim has made his lecture videos available to all
- [CS 7820 at Cornell](http://www.cs.cornell.edu/courses/cs6820/2009fa/) taken by **Jon Kleinberg**

[3] - Used as the reference for

- [CS 157 at Brown](https://cs.brown.edu/courses/cs157/)

[4] - Recommended by *TYCS*. Used as the reference for

- [CSE 373 at SUNY](http://www3.cs.stonybrook.edu/~skiena/373/) which is taken by **Steven Skiena**

[5] - Used as the reference for

- [COS226 at Princeton](http://www.cs.princeton.edu/courses/archive/spring18/cos226/) with a [condensed version of the book](https://algs4.cs.princeton.edu/home/) available for reference

## Theory of Computation

### Standard Textbooks

1. **Introduction to Automata Theory, Languages, and Computation** - John E. Hopcroft and Jeffrey D. Ullman (_The Cinderella Book_) [1]
2. **Introduction to the Theory of Computation** - Michael Sipser [2]
3. **Elements of the Theory of Computation** - Harry R. Lewis & C. H. Papadimitriou

### Alternative/Supplementary

1. **Introduction to Formal Language and Computation** - Peter Linz [4]
2. **Theory of Computer Science: Automata, Language and Computation** - Mishra & Chandrasekharan
3. **A Text Book on Automata Theory** - Nasir & Sirmani
4. **Introduction to Languages and The Theory of Computation** - John Martin
5. **Computability, Complexity, and Languages: Fundamentals of Theoretical Computer Science** - Martin Davis, Ron Sigal, Elaine J. Weyuker
6. **An Introduction to the Theory of Computation** - Eitan Gurari
7. **Theory of Computation** - James L. Hein
8. **Models of Computation and Formal Languages** - R. Gregory Taylor
9. **Essentials of Theoretical Computer Science** - F. D. Lewis
10. **Automata and Computability** - Dexter C. Kozen

### Notes

[1] - Used a reference textbook for many courses around the world. It closely matches what Jeff Ullman [teaches online at Lagunita](https://lagunita.stanford.edu/courses/course-v1:ComputerScience+Automata+Fall2016/about). (Duh)

[2] - Used as the reference for

- [CS 3102 at UoV](http://www.cs.virginia.edu/~robins/cs3102/)
- [CS-251 at EPFL](http://theory.epfl.ch/cs251/Home.html)
- [CS 3800 at NU](https://course.ccs.neu.edu/cs3800f17wc/policies.html)
- [CS39 at Dartmouth](https://www.cs.dartmouth.edu/~ac/Teach/CS39-Spring18/)

[4] - Used as the reference for

- [UPenn's CSC 4170-50](https://www.seas.upenn.edu/~cit596/notes/dave/syllabus.html)

[5] - Used as the reference for

- [AU's COMP 674](http://www.athabascau.ca/syllabi/comp/comp674.php), a graduate level course.

## Operating Systems

### Standard Textbooks

1. **Operating System Concepts** - J. L. Peterson and A. Silberschatz (*The Dinosaur Book*) [1]
2. **Modern Operating Systems** - Andrew S. Tanenbaum
3. **Operating Systems, Internals and Design Principles** - William Stallings [2]

### Alternative/Supplementary

1. **Operating Systems: Three Easy Pieces** - Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau (*The Black Book*/*The Asteroid Book*/*The Comet Book*) [3]
2. **Schaum’s Outline of Operating Systems** - Archer J. Harris
3. **The Design of the UNIX operating system** - Maurice J. Bach
4. **Operating Systems: Principles and Practice** - Thomas Anderson and Michael Dahlin. [4]
5. **Operating Systems: A Concept-Based Approach** - D. M. Dhamdhere
6. **Operating Systems: A Modern Perspective** - Gary J. Nutt
7. **Operating Systems In Depth: Design and Programming** - Thomas W. Doeppner [5]
8. **Operating System Concepts Essentials** - Silberschatz, Galvin, Gagne [6]

### Notes

For a more historical approach, [this Wikipedia page](https://en.wikipedia.org/wiki/List_of_important_publications_in_computer_science#Operating_systems) provides a list of a series of breakthroughs in Operating System Design. [A list of research papers on Udacity](https://www.udacity.com/wiki/ud156-readings) may also be useful, and are the recommended readings for [CS 6210 at GATech](https://www.omscs.gatech.edu/cs-6210-advanced-operating-systems).

[1] - Used as the reference for

- [CS 385 at UIC](https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/)
- [CM's 15-410](https://www.cs.cmu.edu/~410/)
- [CS 347 at IITB](https://www.cse.iitb.ac.in/~mythili/teaching/cs347_autumn2016/index.html) where reading through MIT's [xv6 Operating System](https://pdos.csail.mit.edu/6.828/2012/xv6.html) is mandatory.
- [Drexel's CS 543](https://www.cs.drexel.edu/~jjohnson/2012-13/fall/cs543/) which again recommends reading **Linux Kernel Development**.
- [CS170 at UCSB](http://www.cs.ucsb.edu/~rich/class/cs170/)

[2] - Used as the reference for

- [TOM-2.1-CS at UT](https://wwwhome.ewi.utwente.nl/~pieter/CS-OS/)
- [CS 372 at UT Austin](http://www.cs.utexas.edu/users/witchel/372/) although certain readings are from [1] as well.

[3] - [**OSTEP**](http://pages.cs.wisc.edu/~remzi/OSTEP/) was made as a companion for a [course on Operating Systems at UWISC](http://pages.cs.wisc.edu/~remzi/Classes/537/Spring2018/), which is freely available. The professors also recommend reading classic texts such as **Linux Kernel Development** and **The C Programming Language** (K&R). It is also used as a reference for [WPI's CS 3013](https://web.cs.wpi.edu/~cshue/cs3013/). Apart from being my personal recommendation for an introduction to Operating Systems, it is also recommended over at [Teach Yourself Computer Science](https://teachyourselfcs.com/£oeprating-systems) (_TYCS_).

[4] - Used as the reference for

- [SU's CS140](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring18/index.php)
- [Yale's CS422/522](http://flint.cs.yale.edu/cs422/)

[5] - Used as the reference for
- [CS 161 at HU](http://www.eecs.harvard.edu/~cs161/)

[6] - Basically a cheaper version of [1] recommended as the reference textbook for [CU's COMS W4118](http://www.cs.columbia.edu/~jae/4118/).

## Data Communication
<!-- Data transmission fundamentals: historical overview; time/frequency representation of data signals; elements of a communications link; definition of key terms; factors affecting system design, Binary and multi-level signaling: information transfer rate; calculation of channel capacity; bandwidth efficiency, Baseband data transmission: the problem of inter symbol interference; achieving a Nyquist channel response; recovery of symbols from noise; bit error rate performance for baseband data systems, Bandpass digital modulation: binary modulation schemes (eg ASK, FSK, PSK); multi-level digital modulation (e.g. M-ary ASK, M-ary FSK, M-ary PSK, QAM), Coding theory and practice: source coding; channel coding; block coding; convolutional coding; combined coding and modulation, Multi-user digital modulation techniques such as frequency division multiple access (FDMA); time division multiple access (TDMA); code division multiple access (CDMA); combined multiple access systems; Error detection and correction, Digital transmission fundamental  -->
### Standard Textbooks

1. **Data Communication and Networking** - B. A. Forouzan
2. **Computer Networks** - Andrew S. Tanenbaum

### Alternative/Supplementary

1. **Data Communication, Computer Networks and Open Systems** - Fred Halsall
2. **TCP/IP Protocol Suite** - B. A. Forouzan
3. **Data and Computer Communications** - William Stallings [1]
4. **Communication Networks, Fundamental Concepts & Key Architecture** - Leon-Garcia and I. Widjaja

### Notes

- Please help. I found nothing on the web with similar syllabus, which has been commented out. See source code.

[1] - Used as the reference for

- [CS 3413 at UTSA](http://www.cs.utsa.edu/~korkmaz/teaching/cs3413/)

## Microprocessors and Microcontrollers

### Standard Textbooks

1. **The Intel Microprocessors - Architecture Programming And Interfacing** - Barry B. Brey [1]
2. **Microprocessor and Interfacing** - D. V. Hall
3. **Microprocessor Architecture, Programming, and Applications with the 8085** - Ramesh Gaonkar [5]

### Alternative/Supplementary

1. **Microcomputer Systems - The 8086/8088 Family Architecture, Programming and Design** - Liu and Gibson
2. **The 8051 Microcontroller and Embedded Systems** - M. A. Mazidi, J. G. Mazidi and R. D. McKinlay
3. **Microprocessors: Principles and Applications** - A. Pal
4. **The 8051 Microcontroller and Embedded Systems : Using Assembly and C** - Muhammad Ali Mazidi
5. **Advanced Microprocessors and Peripherals** - A. K. Ray and K. M. Bhurchandi
6. **Fundamentals of Microprocessors And Microcontrollers** - Ram B.

### Notes

Online courses about Microprocessors are rather difficult to come by.

[1] - Used as the reference for

- [a course at UCF](http://www.cs.ucf.edu/~ahossam/teaching/microp/)

[5] - Used as the reference for

- [IITK's CS43003](http://www.facweb.iitkgp.ernet.in/~apal/files/microprocessor_04.pdf) (Note: Syllabus page only)

## Discrete Mathematics

### Standard Textbooks

1. **Discrete Mathematics and Its Applications** - Kenneth H. Rosen [1]
2. **Discrete Mathematics** - Kevin Ferland [2]
3. **Mathematics for Computer Science** - Eric Lehman, F. Thomson Leighton, and Albert R. Meyer [3]

### Alternative/Supplementary

1. **Discrete and Combinatorial Mathematics: An Applied Introduction** - Ralph P. Grimaldi [4]
2. **Discrete Mathematics for Computer Science** - Kenneth Bogart and Robert L. Drysdale [5]
3. **Concrete Mathematics** - Ronald Graham, Donald E. Knuth and Oren Patashnik [6]
4. **Discrete Mathematics** - Jiří Matoušek and Jaroslav Nešetřil [7]
5. **Mathematical Structures for Computer Science** - J. L. Gersting [8]
6. **Discrete Mathematics** - Norman L. Biggs [9]
7. **Discrete Mathematics** - Kenneth A. Ross and Charles R. Wright [10]
8. **Discrete Mathematics** - Seymour Lipschutz and Mar Lars Lipson [11]
9. **Discrete Mathematics: Mathematical Reasoning and Proof with Puzzles, Patterns and Games** - Douglas E. Ensley and J. Winston Crawley [12]
10. **Elements of Discrete Mathematics: A Computer Oriented Approach** - C. L. Liu and D. P. Mohapatra
11. **Discrete Mathematical Structures with Applications, to Computer Science** - J. P. Tremblay and R. Manohar
12. **Discrete Mathematics for Computer Scientists & Mathematics** - Joe L. Mott, A. Kandel, and T. P. Baker
13. **Graph Theory with applications to Engineering & Computer Science** - N. Deo
14. **Discrete Mathematical Structures for Computer Science** - B. Kolman and R. C. Busby
15. **Discrete Mathematics with Applications** - Thomas Koshy
16. **Discrete Mathematics** - Nicodemi O.
17. **Discrete Mathematics** - R. Krishna Kumar
18. **Discrete Mathematics** - Johnsonbaugh
19. **An Introduction to Discrete Mathematics for Business & Computing** - John Dwyer
20. **Discrete Mathematics With Applications** - Susanna S. Epp
21. **The Art of Computer Programming** - Donald E. Knuth
22. **Practice Problems in Discrete Mathematics** - Bojana Obrenic
23. **Hand Book of Discrete and Combinatorial Mathematics** - Kenneth H. Rosen and John G. Michaels
24. **Discrete Mathematics by Example** - Andrew Simpson
25. **Discrete mathematics with graph theory and combinatorics** - T. Veerarajan

### Notes

- [Stanford's CS103](http://web.stanford.edu/class/cs103/) may serve as an introduction to those who are unfamiliar with the concepts.
- Yale's CPSC 202 uses a [document of notes on Discrete Math as the primary reading](http://cs.yale.edu/homes/aspnes/classes/202/notes.pdf). Additional reading can be done from [2] or [1].
- [CS20 at Harvard](https://www.seas.harvard.edu/courses/cs20/) uses [notes](https://www.seas.harvard.edu/courses/cs20/MIT6_042Notes.pdf) from [MIT's 6.042](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/).
- Cornell also hosts a useful set of [notes on Discrete Structures](https://www.cs.cornell.edu/~rafael/discmath.pdf).
- [UT Austin's CS 311](http://www.cs.utexas.edu/~vl/teaching/311/) appears to have their own set of lecture notes linked on the course page.

[1] - Used as the reference for

- [CS381 at ODU](http://www.cs.odu.edu/~cs381/index.html)
- [CSE 191 at UaB](https://cse.buffalo.edu/~rapaport/191/) with [11] additionally recommended
- [6301 at UCL](https://www.ucl.ac.uk/maths/courses/undergraduates/modules/general-ancillary/general_ancillary_syllabuses/6301) (Note: Syllabus page only)
- [14:332:312 at Rutgers](http://eceweb1.rutgers.edu/~csi/DiscMath.html)
- [CS 441 at PU](https://people.cs.pitt.edu/~milos/courses/cs441/)
- [CS 70 at Berkeley](http://eecs70.org/) although notes are recommended for primary reading
- [CS 207 at IIT Bombay](https://www.cse.iitb.ac.in/~akshayss/courses/cs207-2016.html) along with [9]

[3] - Used as the reference for

- [CS2102 at UoV](https://uvacs2102.github.io/) and has generously been made [available online](https://uvacs2102.github.io/docs/mcs.pdf) under the Creative Commons License
- [CS1010 at IITH](https://www.iith.ac.in/~aravind/cs1010.html) although it uses [slightly older notes](https://www.iith.ac.in/~aravind/Files-DM/LLM-MFCS-2012.pdf) instead with an additional guide on [**How to write Mathematics**](http://erickson.sites.truman.edu/files/2012/04/guide1.pdf) by Martin Erickson
- [CS 30 at Dartmouth](https://www.cs.dartmouth.edu/~ac/Teach/CS30-Winter18/) with [1] recommended for additional reading

[4] - Used as the reference for

- [Discrete Structures and Combinatorics at BGU](https://www.cs.bgu.ac.il/~dsc172/Main) along with some weird Israeli book? :shrug

[5] - Used as the reference for

- [CPS 102 at Duke](https://www2.cs.duke.edu/courses/spring09/cps102/) with [1], [6] and [7] also recommended

[8] - Used as the reference for

- [MAT 385 at NKU](http://ceadserv1.nku.edu/longa//classes/2002fall/mat385/)

[9] - Used as the reference for

- [Discrete Math at Cambridge](https://www.cl.cam.ac.uk/teaching/1314/DiscMath/) with additional books listed

[10] - Used as the reference for

- [Discrete Mathematics at Oxford](https://www.cs.ox.ac.uk/teaching/courses/2017-2018/discretemaths/) along with other recommendations like [4]

[12] - Used as the reference for

- [CSCI 2824 at UoC Boulder](https://www.colorado.edu/cs/csci-2824-discrete-structures)

## Computer Graphics

### Standard Textbooks

1. **Computer Graphics: Principles and Practice** - John F. Hughes, Andries van Dam, Morgan McGuire, David F. Sklar, James D. Foley, Steven K. Feiner, Kurt Akeley [1]
2. **Fundamentals of Computer Graphics** - Pete Shirley and Steve Marschner with Michael Ashikhmin, Michael Gleicher, Naty Hoffman, Garrett Johnson, Tamara Munzner, Erik Reinhard, Kelvin Sung, William B. Thompson, Peter Willemsen, and Bryan Wyvill [2]
3. **Computer Graphics, C Version** - Donald Hearn and M. Pauline Baker [3]

### Alternative/Supplementary

1. **Computer Graphics using Open GL** - Francis S. Hill [4]
2. **Multimedia Systems** - R. Steinmetz and K. Nahrstedt [5]
3. **Fundamentals of Multimedia** - Ze-Nian Li and M. S. Drew [6]
4. **Mathematical Elements for Computer Graphics** - David F. Rogers and James Alan Adams [7]
5. **Physically Based Rendering: From Theory to Implementation** - Matt Pharr and Greg Humphreys [8]
6. **Procedural Elements for Computer Graphics** - David Rogers [9]
7. **Computer Graphics for Java Programmers** - L. Ammeraal and K. Zhang [10]
8. **Computer Graphics: A Survey of Current Techniques and Applications** - John Lewell [11]
9. **Computer Graphics: Theory Into Practice** - Jeffrey J. McConnell [12]
10. **Computer Graphics: Techniques and Applications** - R. D. Parslow, R. W. Prowse, Richard Elliot Green [13]
11. **Computer graphics and virtual environments: from realism to real-time** - M. Slater, A. Steed, Y. Chrysantho [14]
12. **Interactive environments with open-source software** - Wolfgang Höhl [15]
13. **Foundations of 3D Computer Graphics** - Steven J. Gortler [16]
14. **Interactive Computer Graphics, A Top-Down Approach with WebGL** - Edward Angel and Dave Schreiner [17]

### Notes

- The first two are no doubt standard textbooks in the field, but there is simply too vast an ocean of textbooks to categorise.

- There is a reference book for OpenGL programming one may find useful called the "[Red Book](http://www.opengl.org/documentation/red_book/)". Many courses have further resources like these linked on their course or info pages.

[1] - Used as the reference for

- [CSCI 1230 at Brown](https://cs.brown.edu/courses/cs123/)
- [CS4620/CS4621 at Cornell](http://www.cs.cornell.edu/courses/cs4620/2014fa/index.shtml) along with [16]
- [CS 6360 at IITM](http://www.cse.iitm.ac.in/~vplab/computer_graphics.html) along with [3]
- [Introduction to Computer Graphics at UIC](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/index.html)
- [CS 488 at UIC](https://www.evl.uic.edu/aej/488/index.html) which seems to be an earlier version of the course above

[2] - Used as the reference for

- [CMU 15-462/662](http://15462.courses.cs.cmu.edu/fall2015/) along with [1] and [8]
- [Computer Graphics at Oxford](https://www.cs.ox.ac.uk/teaching/courses/2017-2018/graphics/) with [1] and others additionally recommended
- [CS248 at Stanford](http://graphics.stanford.edu/courses/cs248-18-spring/) with [1] also recommended

[16] - Used as the reference for

- [CS 175 at Harvard](https://sites.fas.harvard.edu/~lib175/) taught by Steven Gortler himself

[17] - Used as the reference for

- [CS 465 at Bilkent](http://www.cs.bilkent.edu.tr/~gudukbay/cs465/)
- [EDAF80 at LTH](http://cs.lth.se/edaf80/) with [The Graphics Codex](http://graphicscodex.com/) linked for additional reading
- [CS 537 at Drexel](https://www.cs.drexel.edu/~david/Classes/ICG/)
- [CS 4102 at St. Andrews](https://info.cs.st-andrews.ac.uk/student-handbook/modules/CS4102.html) (only a list of textbooks)

## Information Theory and Coding

### Standard Textbooks

1. **Elements of Information Theory** - T. M. Cover and J. A. Thomas [1]
2. **Information Theory, Inference and Learning Algorithms** - David J. C. Mackay [2]
3. **Information Theory Coding and Cryptography** - R. Bose

### Alternative/Supplementary

1. **Coding and Information Theory** - S. Roman
2. **Introduction to Data Compression** - Khalid Sayood
3. **The Theory of Information and Coding** - R. J. McEliece
4. **The Theory of Error Correcting Codes** - F. J. MacWilliams and N. J. A. Sloane
5. **Entropy and Information Theory** - Robert M. Gray [3]
6. **Information Theory and Reliable Communication** - R. G. Gallagher [4]
7. **Information Theory** - Robert B. Ash [5]

### Notes

- Wikipedia has an [extensive reference list](https://en.wikipedia.org/wiki/Information_theory#References) with many classic texts and books linked.
- A [Workshop on Complexity Information Theory in Theoretical Computer Science and Discrete Mathematics](http://sites.math.rutgers.edu/~saks/IT/) at Rutgers has an extensive reading list should one be ambitious enough.
- [CS 229r at Harvard](http://people.seas.harvard.edu/~madhusudan/courses/Spring2016/) has links to notes from other courses and multiple papers on the topic.
- Most of the courses strongly recommend reading through Claude Shannon's [A Mathematical Theory of Communication](math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf) paper from 1948. It serves as the basis for the branch of Information Theory and Coding related research.
- Most/All of the courses have relevant additional resources which are very useful

[1] - Used as the reference for

- [15-859 at CMU](http://www.cs.cmu.edu/~venkatg/teaching/ITCS-spr2013/) with many other classic papers recommended for reading
- [CSE 533 at UoW](https://catalyst.uw.edu/workspace/anuprao/15415/86593) with [a list of papers](https://catalyst.uw.edu/workspace/anuprao/15415/86644)
- [EE5581 at UMN](http://people.ece.umn.edu/~nihar/ee5581_fall05/index.html)
- [CSCI1850 at Brown](http://jwmi.github.io/IC/) with additional readings from **Information Theory, Inference, and Learning Algorithms** which is [available free of cost](http://www.inference.org.uk/mackay/itila/book.html)
- [TTIC 31200/CMSC 37220 at UC](http://ttic.uchicago.edu/%7Emadhurt/courses/infotheory2014/index.html)
- [10-704 at CMU](http://www.cs.cmu.edu/%7Eaarti/Class/10704/lecs.html) along with [2], and has elements of Machine Learning applied to it
- [CS85/CS185 at Dartmouth](http://www.cs.dartmouth.edu/%7Eac/Teach/CS85-Winter06/) with [a list of papers](http://www.cs.dartmouth.edu/%7Eac/Teach/CS85-Winter06/#papers) for primary reading
- [COS 597D at Princeton](http://www.cs.princeton.edu/courses/archive/fall11/cos597D/) which also recommends several papers
- [COMPSCI 650 at UMass](https://people.cs.umass.edu/~elm/Teaching/650_F14/) with [2] recommended additionally
- [582650 at UoH](https://www.cs.helsinki.fi/group/cosco/Teaching/Information/2014/)
- [CO 739-2 at UoW](http://www.math.uwaterloo.ca/~anayak/Site/Information_Theory.html)
- [EECS 428 at NU](https://www.mccormick.northwestern.edu/eecs/courses/descriptions/428.html) (Note: Syllabus page only)
- [ECE 563 at UoI](https://ece.illinois.edu/academics/courses/profile/ece563) (Note: Syllabus page only)

[2] - Used as a reference for

- [COMP 7404 at DU](http://web.cs.du.edu/~ramki/courses/tpcs/infoTheory/index.html)
- [CSC 310 at UoT](https://www.cs.toronto.edu/~radford/csc310.F11/) with [3] recommended for rigorous mathematical analysis
- [CS 616 at WU](https://www.westminster.edu/resources/dean/view_course_syllabus.cfm?id=769) (Note: Syllabus page only)

## Compiler Design

### Standard Textbooks

1. **Compilers: Principles, Techniques, and Tools** - A. V. Aho, Ravi Sethi & Jeffrey D. Ullman [1]
2. **Compiler Construction Principles and Practice** - K. C. Louden 
3.  **Modern compiler implementation in ML** - A. W. Appel [2]

### Alternative/Supplementary

1. **Compiler Construction: Theory and Practice** - W. A. Barrett, John D. Couch, C. Couch
2. **Engineering a Compiler** - Keith D Cooper and Linda Torczon
3. **Modern Compiler Design** - Dick Grune, Kees van Reeuwijk, Henri E. Bal, Ceriel J.H. Jacobs, Koen Langendoen 

### Notes

[1] - This is a brilliant book recommended by [pearson.com](https://www.pearson.com/us/higher-education/program/Aho-Compilers-Principles-Techniques-and-Tools-2nd-Edition/PGM167067.html). Used as the reference for

- [CS143 at Stanford University](https://web.stanford.edu/class/cs143/)
- [CS4120 at Cornell University](http://www.cs.cornell.edu/courses/cs4120/2013fa/)
- [CS5470 at university of Utah](https://courses.engr.illinois.edu/cs421/fa2014/)

[2] - Used as reference for 

- [CS421 at University of Illinois](https://courses.engr.illinois.edu/cs421/fa2014/) 

## Computer Networks

### Standard Textbooks

1. **Computer Networking: A Top-Down Approach** - James Kurose and Keith Ross [1]
2. **Computer Networks – A System Approach** - Larry L. Peterson and Bruce S. Davie [2]
3. **Computer Networks** - Andrew S. Tanenbaum [3]

### Alternative/Supplementary

1. **TCP/IP protocol Suite** - Behrouz A. Forouzan
2. **Data and Computer Communication** - William Stallings [4]
3. **Data Communication, Computer Networks and Open Systems** - F. Halsall
4. **Data Communications and Networking** - Behrouz A. Forouzan [5]
5. **Internetworking with TCP/IP, Volume 1** - Douglas Comer
6. **TCP/IP Illustrated, Volume 1: The Protocols** - W. Richard Stevens [6]
7. **Unix Network Programming, Volume 1: The Sockets Networking API** - W. Richard Stevens [7]

### Notes

[GATech's CS 6250](https://www.omscs.gatech.edu/cs-6250-computer-networks) has a list of useful papers [on Udacity](https://www.udacity.com/wiki/ud819/resources). There are also many more amazing resources on the web.

[1] - It is recommended over at [TYCS](https://teachyourselfcs.com/#networking). Also used as the reference for

- [CS60 at Dartmouth](http://www.cs.dartmouth.edu/~campbell/cs60/) where texts on Shell Scripting like **A Practical Guide to Linux Commands, Editors, and Shell Programming** by Mark G. Sobell are also recommended
- [CS 356 at UT Austin](http://www.cs.utexas.edu/users/lam/cs356/)
- [COS 461 at Princeton](https://www.cs.princeton.edu/courses/archive/spring17/cos461/) along with [2]
- [CS244A at Stanford](http://web.stanford.edu/class/cs244a/)

[2] - Used as the reference for

- [15-441 at CMU](https://www.cs.cmu.edu/~prs/15-441-F16/)
- [Computer Networks at Oxford](https://www.cs.ox.ac.uk/teaching/courses/2017-2018/networks/) along with [3]
- [CS 640 at UWISC](http://pages.cs.wisc.edu/~pb/cs640.html)

[4] - Used as the reference for
- [CS 408 at SU](http://people.sabanciuniv.edu/levi/cs408/)

[5] - It is regarded as the standard textbook in the field [according to Wikipedia](https://en.wikipedia.org/wiki/List_of_important_publications_in_computer_science#Networking).

[6], [7] - Widely recommended in many courses listed above for additional reading, especially those at Princeton, Stanford and UWISC.

## Software Engineering

### Standard Textbooks

1. **Software Engineering A Practitioner’s Approach** - Roger S. Pressman [1]
2. **Software Engineering** - Ian Sommerville [2]

### Alternative/Supplementary

1. **An Integrated Approach to Software Engineering** - Pankaj Jalote [3]
2. **Software Engineering Fundamentals** - A. Behferooz and F. J. Hudson
3. **Fundamentals of Software Engineering** - Rajib Mall
4. **Software Engineering** - Gaurav Gupta and Deepika Gupta
5. **Encyclopedia of Software Engineering** - Philip A. LaPlante
6. **Software Engineering 1st Edition** - Udit Agarwal
7. **Algebraic Methodology and Software Technology** - Grigore Rosu and Jose Meseguer
8. **Software Design Methodology: From Principles to Architectural Styles** - Hong Zhu
9. **Object-oriented Software Engineering : using UML, patterns, and Java** - Bernd Bruegge and Allen Dutoit [4]
10. **The New Software Engineering** - Sue A. Conger [5]
11. **The Pragmatic Programmer** - Dave Thomas and Andy Hunt [6]
12. **Software Engineering** - Ivan Marsic [7]
13. **Design Patterns:  Elements of Reusable Object-Oriented Software**-  E. Gamma, R. Helm, R. Johnson, and J. Vlissides [8]
14. **Object-Oriented Software Engineering: Practical Software Development using UML and Java** - Timothy C. Lethbridge and Robert Laganière [9]
15. **Fundamentals of Software Engineering** - Carlo Ghezzi [10]

### Notes

- Wikipedia has a [list of notable publications](https://en.wikipedia.org/wiki/Outline_of_software_engineering#Notable_publications) in Software Engineering.
- [CS32 at Brown](http://cs.brown.edu/courses/cs0320/) recommends **Effective Java** by Joshua Bloch for some reason. :shrug
- [EE 360F at UT Austin](http://users.ece.utexas.edu/~perry/education/SE-Intro/) has a list of papers and sections from multiple books as necessary readings for the course.

[1] - Used as the reference for

- [15-413 at CMU](https://www.cs.cmu.edu/~aldrich/courses/413/)
- [CS 501 at Cornell](http://www.cs.cornell.edu/courses/cs501/2000FA/index.html) along with other classic books like **The Mythical Man Month** by Frederick Brooks

[2] - Used as the reference for

- [Introduction to Software Engineering at PSU](http://www.csci.psu.edu/seminars/fallnotes/SWEintro.pdf) (Note: Syllabus page only)

[3] - Used as the reference for

- [CS 320 at UMass](https://people.cs.umass.edu/~brun/class/2013Spring/CS320/)

[4] - Used as the reference for

- [CS223 at Warwick](http://web.iitd.ac.in/~sumeet/sm.pdf) (Note: Syllabus and lecture pdf only)

[5] - Used as the reference for

- [CS302 at Saylor Academy](https://learn.saylor.org/mod/page/view.php?id=686)

[6] - Used as the reference for

- [CSE 403 at UoW](https://courses.cs.washington.edu/courses/cse403/)

[7] - A [free book](http://www.ece.rutgers.edu/~marsic/books/SE/book-SE_marsic.pdf) written by the instructor of [ECE 14:332:452 at Rutgers](http://www.ece.rutgers.edu/~marsic/Teaching/SE/).

[8] - Used as the reference for

- [CSE870 at MSU](http://www.cse.msu.edu/~cse870/index.php) along with many other articles from literature
- [Foundations of Software Engineering at BGU](https://www.cs.bgu.ac.il/~fsen141/Main) along with many other textbooks

[9] - Used as the reference for

- SEG 2100 at UoO which cannot be accessed. Instead the author provides supporting materials and other links [here](http://www.site.uottawa.ca/school/research/lloseng/).

[10] - Used as the reference for

- [CSE2102 at UConn](http://www.engr.uconn.edu/~steve/Cse2102/cse2102.html)

# References

## Websites

   [Teach Yourself CS](https://teachyourselfcs.coms)  
   [List of Notable Publications in Software Engineering - Wikipedia](https://en.wikipedia.org/wiki/Outline_of_software_engineering#Notable_publications)  
   [List of Important Publications in Computer Science](https://en.wikipedia.org/wiki/List_of_important_publications_in_computer_science)  
   [Is there a list of the canonical introductory textbooks covering the major branches of computer science? - /r/COMPSCI](https://np.reddit.com/r/compsci/comments/gprp0/is_there_a_list_of_the_canonical_introductory/c1pcqe5/)  
   [What are the canon books in Computer Science? - /r/COMPSCI](https://www.reddit.com/r/compsci/comments/40mq3q/what_are_the_canon_books_in_computer_science/)  
   [What Books Should Everyone Read? - Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/3253/what-books-should-everyone-read)  
   [What papers should everyone read? - Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/1168/what-papers-should-everyone-read?noredirect=1&lq=1)  
   [Theory of Computation - Further reading](https://en.wikipedia.org/wiki/Theory_of_computation#Further_reading)  
   [Automata Theory - Further reading](https://en.wikipedia.org/wiki/Automata_theory#Further_reading)  
   [Operating System - Further reading](https://en.wikipedia.org/wiki/Operating_system#Futher_reading)  
   [Computer Network - Further Reading](https://en.wikipedia.org/wiki/Computer_network#Further_reading)
   [Principles of Compiler Design -Further Reading]( https://en.wikipedia.org/wiki/Principles_of_Compiler_Design#Further_reading) 
   [List of Important Publications in Computer Science](https://en.wikipedia.org/wiki/List_of_important_publications_in_computer_science)  
   [Discrete Mathematics - Further Reading](https://en.wikipedia.org/wiki/Discrete_mathematics#Further_reading)  
   [Discrete Mathematics - Wikibooks](https://en.wikibooks.org/wiki/Discrete_Mathematics)  
   [Computer Network - Further Reading](https://en.wikipedia.org/wiki/Computer_network#Further_reading)  
   [Information Theory - References](https://en.wikipedia.org/wiki/Information_theory#References)  
   [Best Reference Books - San Foundry](https://www.sanfoundry.com/best-reference-books-computer-science-engineering/)  

## Courses

- Computer Organisation and Architecture

   [CS 312 - University of Missouri-St. Louis](http://www.cs.umsl.edu/~sanjiv/classes/cs312/)  
   [CS146 - Harvard University](http://www.eecs.harvard.edu/~dbrooks/cs146-spring2004/)  
   [ECE 411 - University of Illinois](https://ece.illinois.edu/academics/courses/profile/ECE411)  
   [18-447 - Carnegie Mellon University](http://www.ece.cmu.edu/~ece447/s13/doku.php?id=schedule)  
   [CS 3410 - Cornell University](http://www.cs.cornell.edu/courses/cs3410/2016fa/)  
   [CS 61C - University of California, Berkeley](http://www-inst.eecs.berkeley.edu/%7Ecs61c/sp15/#Resources)  
   [CS 2505 - Virginia Tech](http://courses.cs.vt.edu/~cs2505/spring2018/)  
   [15-213/18-213 - Carnegie Mellon University](http://www.cs.cmu.edu/%7E213/)  
   [CS107 - Stanford University](http://web.stanford.edu/class/cs107/)  
   [EE382 - Stanford University](https://web.stanford.edu/class/ee382/)  

- Algorithm Design and Analysis

   [CS 600 A - Stevens Institute of Technology](https://www.cs.stevens.edu/~swetzel/CS600/spring11/)  
   [CSC2420 - University of Toronto](http://www.cs.toronto.edu/~bor/2420f12/)  
   [15-451/651 - Carnegie Mellon University](https://www.cs.cmu.edu/~15451/)  
   [15-451/651 - Carnegie Mellon University](http://www.cs.cmu.edu/~avrim/451f09/index.html) (older Fall 2009 version)  
   [CS 466/666 - University of Waterloo](https://cs.uwaterloo.ca/~eblais/courses/F17/CS466/)  
   [CSci 256 - Williams College](https://www.cs.williams.edu/~lenhart/cs256/index.html)  
   [CPSC500 - University of British Columbia](http://www.cs.ubc.ca/~condon/cpsc500/)  
   [CS 7200 - Wright State University](http://cecs.wright.edu/~tkprasad/courses/cs7200/cs7200.html)  
   [CS 161 - Stanford University](http://openclassroom.stanford.edu/MainFolder/CoursePage.php?course=IntroToAlgorithms)  
   [CS 7820 - Cornell University](http://www.cs.cornell.edu/courses/cs6820/2009fa/) taken by **Jon Kleinberg**  
   [CS 157 - Brown University](https://cs.brown.edu/courses/cs157/)  
   [CSE 373 - State University of New York](http://www3.cs.stonybrook.edu/~skiena/373/) taken by **Steven Skiena**  
   [COS226 - Princeton University](http://www.cs.princeton.edu/courses/archive/spring18/cos226/)  

- Theory of Computation

   [Automata Theory - Stanford Lagunita](https://lagunita.stanford.edu/courses/course-v1:ComputerScience+Automata+Fall2016/about) (taken by **Jefferey D. Ullman** himself)  
   [CSC 4170-50 - University of Pennsylvania](https://www.seas.upenn.edu/~cit596/notes/dave/syllabus.html)  
   [CS3102 - University of Virginia](http://www.cs.virginia.edu/~robins/cs3102/)  
   [CS-251 - École Polytechnique Fédérale de Lausanne EPFL](http://theory.epfl.ch/cs251/Home.html)  
   [CS 3800 - Northeastern University](https://course.ccs.neu.edu/cs3800f17wc/policies.html)  
   [CS39 - Dartmouth University](https://www.cs.dartmouth.edu/~ac/Teach/CS39-Spring18/)  
   [COMP 674 - Athabasca University](http://www.athabascau.ca/syllabi/comp/comp674.php)  

- Operating Systems

   [CS 6210 - Georgia Tech](https://www.omscs.gatech.edu/cs-6210-advanced-operating-systems)  
   [CS 385 - University of Illinois, Chicago](https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/)  
   [CS 347 - Indian Institute of Technology, Bombay](https://www.cse.iitb.ac.in/~mythili/teaching/cs347_autumn2016/index.html)  
   [CS 543 - Drexel University](https://www.cs.drexel.edu/~jjohnson/2012-13/fall/cs543/)  
   [CS170 - University of California, Santa Barbara](http://www.cs.ucsb.edu/~rich/class/cs170/)  
   [TOM-2.1-CS - University of Twente](https://wwwhome.ewi.utwente.nl/~pieter/CS-OS/)  
   [CS 372 - University of Texas, Austin](http://www.cs.utexas.edu/users/witchel/372/)  
   [CS-537 - University of Wisconsin-Madison](http://pages.cs.wisc.edu/~remzi/Classes/537/Spring2018/)  
   [CS3013 - Worchester Polytechnic Institute](https://web.cs.wpi.edu/~cshue/cs3013/)  
   [CS140 - Stanford University](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring18/index.php)  
   [CS422/522 - Yale University](http://flint.cs.yale.edu/cs422/)  
   [CS 140 - Harvard University](http://www.eecs.harvard.edu/~cs161/)  
   [COMS W4118 - Columbia University](http://www.cs.columbia.edu/~jae/4118/)  

- Data Communications

   [CS 3413 - University of Texas at San Antonio](http://www.cs.utsa.edu/~korkmaz/teaching/cs3413/)

- Microprocessors and Microcontrollers

   [Fundamentals of Microprocessors - University of Central Florida](http://www.cs.ucf.edu/~ahossam/teaching/microp/)  
   [CS758: Building Microprocessors - University of Wisconsin](http://pages.cs.wisc.edu/~karu/courses/cs758/fall2011/wiki/index.php)  

- Discrete Mathematics

   [CS103 - Stanford University](http://web.stanford.edu/class/cs103/)  
   [CS20 - Harvard University](https://www.seas.harvard.edu/courses/cs20/)   
   [CS 311 - University of Texas, Austin](http://www.cs.utexas.edu/~vl/teaching/311/)  
   [CS381 - Old Dominion University](http://www.cs.odu.edu/~cs381/index.html)  
   [CSE 191 - University at Buffalo, New York](https://cse.buffalo.edu/~rapaport/191/)  
   [6301 - University College London](https://www.ucl.ac.uk/maths/courses/undergraduates/modules/general-ancillary/general_ancillary_syllabuses/6301)  
   [14:332:312 - Rutgers University](http://eceweb1.rutgers.edu/~csi/DiscMath.html)  
   [CS 441 - Pittsburgh University](https://people.cs.pitt.edu/~milos/courses/cs441/)  
   [CS 70 - University of California, Berkeley](http://eecs70.org/)  
   [CS 207 - Indian Institute of Technology, Bombay](https://www.cse.iitb.ac.in/~akshayss/courses/cs207-2016.html)  
   [Discrete Structures and Combinatorics - Ben-Gurion University of the Negev](https://www.cs.bgu.ac.il/~dsc172/Main)  
   [CPS 102 - Duke University](https://www2.cs.duke.edu/courses/spring09/cps102/)  
   [MAT 385 - North Kansas University](http://ceadserv1.nku.edu/longa//classes/2002fall/mat385/)  
   [Discrete Math - Cambridge University](https://www.cl.cam.ac.uk/teaching/1314/DiscMath/)  
   [Discrete Mathematics - Oxford University](https://www.cs.ox.ac.uk/teaching/courses/2017-2018/discretemaths/)  
   [CS2102 - University of Virginia](https://uvacs2102.github.io/)  
   [MIT 6.042 - Mathematics for Computer Science](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/)  
   [CS1010 - Indian Institute of Technology, Hyderabad](https://www.iith.ac.in/~aravind/cs1010.html)  
   [CS 30 - Dartmouth University](https://www.cs.dartmouth.edu/~ac/Teach/CS30-Winter18/)  
   [CSCI 2824 - University of Colorado, Boulder](https://www.colorado.edu/cs/csci-2824-discrete-structures)

- Computer Graphics

   [CSCI 1230 - Brown University](https://cs.brown.edu/courses/cs123/)  
   [CS4620/CS4621 - Cornell](http://www.cs.cornell.edu/courses/cs4620/2014fa/index.shtml)  
   [CS 6360 - Inbdian Institute of Technology, Madras](http://www.cse.iitm.ac.in/~vplab/computer_graphics.html)  
   [Introduction to Computer Graphics - University of Illinois, Chicago](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/index.html)  
   [CS 488 - University of Illinois, Chicago](https://www.evl.uic.edu/aej/488/index.html)  
   [CMU 15-462/662 - Carnegie Mellon University](http://15462.courses.cs.cmu.edu/fall2015/)  
   [Computer Graphics - Oxford University](https://www.cs.ox.ac.uk/teaching/courses/2017-2018/graphics/)  
   [CS248 - Stanford University](http://graphics.stanford.edu/courses/cs248-18-spring/)  
   [CS 175 - Harvard University](https://sites.fas.harvard.edu/~lib175/)  
   [CS 465 - Bilkent University](http://www.cs.bilkent.edu.tr/~gudukbay/cs465/)  
   [EDAF80 - Lund University](http://cs.lth.se/edaf80/)  
   [CS 537 - Drexel University](https://www.cs.drexel.edu/~david/Classes/ICG/)  
   [CS 4102 - University of St. Andrews](https://info.cs.st-andrews.ac.uk/student-handbook/modules/CS4102.html)  
   [CSCI 2240: Interactive Computer Graphics - Brown University](https://dritchie.github.io/csci2240/)  

- Information Theory and Coding

   [CS 229r - Harvard University](http://people.seas.harvard.edu/~madhusudan/courses/Spring2016/)  
   [15-859 - Carnegie Mellon University](http://www.cs.cmu.edu/~venkatg/teaching/ITCS-spr2013/)  
   [CSE 533 - University of Washington](https://catalyst.uw.edu/workspace/anuprao/15415/86593)  
   [EE5581 - University of Minnesota](http://people.ece.umn.edu/~nihar/ee5581_fall05/index.html)  
   [CSCI1850 - Brown University](http://jwmi.github.io/IC/)  
   [TTIC 31200/CMSC 37220 - University of Chicago](http://ttic.uchicago.edu/%7Emadhurt/courses/infotheory2014/index.html)  
   [10-704 - Carnegie Mellon University](http://www.cs.cmu.edu/%7Eaarti/Class/10704/lecs.html)  
   [CS85/CS185 - Dartmouth University](http://www.cs.dartmouth.edu/%7Eac/Teach/CS85-Winter06/)  
   [COS 597D - Princeton University](http://www.cs.princeton.edu/courses/archive/fall11/cos597D/)  
   [COMPSCI 650 - University of Massachussets, Amherst](https://people.cs.umass.edu/~elm/Teaching/650_F14/)  
   [582650 - University of Helsinki](https://www.cs.helsinki.fi/group/cosco/Teaching/Information/2014/)  
   [CO 739-2 - University of Waterloo](http://www.math.uwaterloo.ca/~anayak/Site/Information_Theory.html)  
   [EECS 428 - Northwestern University](https://www.mccormick.northwestern.edu/eecs/courses/descriptions/428.html)  
   [ECE 563 - University of Illinois](https://ece.illinois.edu/academics/courses/profile/ece563)  
   [COMP 7404 - University of Denver](http://web.cs.du.edu/~ramki/courses/tpcs/infoTheory/index.html)  
   [CSC 310 - University of Toronto](https://www.cs.toronto.edu/~radford/csc310.F11/)  
   [CS 616 - Westminster University](https://www.westminster.edu/resources/dean/view_course_syllabus.cfm?id=769)  
   [CS 783 - Cornell University](http://www.cs.cornell.edu/courses/cs783/2007fa/) which has not been linked in relevant section due to being a graduate-level course

- Compiler Design
   
   [CS143 at Stanford University](https://web.stanford.edu/class/cs143/)
   [CS4120 at Cornell University](http://www.cs.cornell.edu/courses/cs4120/2013fa/)
   [CS5470 at university of Utah](https://courses.engr.illinois.edu/cs421/fa2014/)

- Computer Networks

   [CS 6250 - Georgia Institute of Technology](https://www.omscs.gatech.edu/cs-6250-computer-networks)  
   [CS60 - Dartmouth University](http://www.cs.dartmouth.edu/~campbell/cs60/)  
   [CS 356 - University of Texas, Austin](http://www.cs.utexas.edu/users/lam/cs356/)  
   [COS 461 - Princeton University](https://www.cs.princeton.edu/courses/archive/spring17/cos461/)  
   [CS244A - Stanford University](http://web.stanford.edu/class/cs244a/)  
   [15-441 - Carnegie Mellon University](https://www.cs.cmu.edu/~prs/15-441-F16/)  
   [Computer Networks - Oxford University](https://www.cs.ox.ac.uk/teaching/courses/2017-2018/networks/)  
   [CS 640 - University of Wisconsin-Madison](http://pages.cs.wisc.edu/~pb/cs640.html)  
   [CS 408 - Sabancı Üniversitesi](http://people.sabanciuniv.edu/levi/cs408/)  
   [CS 527 - University of British Columbia](https://www.cs.ubc.ca/~bestchai/teaching/cs527_2015w1/index.html) is a PhD level course judging by appearance, so it has not been linked in the relevant section.
   
- Software Engineering

   [CS32 - Brown University](http://cs.brown.edu/courses/cs0320/)  
   [EE 360F - University of Texas, Austin](http://users.ece.utexas.edu/~perry/education/SE-Intro/)  
   [15-413 - Carnegie Mellon University](https://www.cs.cmu.edu/~aldrich/courses/413/)  
   [CS 501 - Cornell University](http://www.cs.cornell.edu/courses/cs501/2000FA/index.html)  
   [Introduction to Software Engineering - Pennsylvania State University](http://www.csci.psu.edu/seminars/fallnotes/SWEintro.pdf)  
   [CS 320 - University of Massachusetts Amherst](https://people.cs.umass.edu/~brun/class/2013Spring/CS320/)  
   [CS223 - University of Warwick](http://web.iitd.ac.in/~sumeet/sm.pdf)  
   [CS302 - Saylor Academy](https://learn.saylor.org/mod/page/view.php?id=686)  
   [CSE 403 - University of Washington](https://courses.cs.washington.edu/courses/cse403/)  
   [ECE 14:332:452 - Rutgers University](http://www.ece.rutgers.edu/~marsic/Teaching/SE/)  
   [CSE870 - Michigan State University](http://www.cse.msu.edu/~cse870/index.php)  
   [Foundations of Software Engineering - Ben-Gurion University of the Negev](https://www.cs.bgu.ac.il/~fsen141/Main)  
   [CSE2102 - University of Connecticut](http://www.engr.uconn.edu/~steve/Cse2102/cse2102.html)  

## Resources

   [**The Algorithm Design Manual**](https://www8.cs.umu.se/kurser/TDBAfl/VT06/algorithms/BOOK/BOOK/BOOK.HTM) by Steven Skiena (for online reading)  
   [Algorithms Part I](https://www.coursera.org/teach/algorithms-part1) and [Part II](https://www.coursera.org/teach/algorithms-part2) taught by **Sedgewick** and **Wayne** on Coursera  
   [Lecture Slides for Kleinberg-Tardos](http://www.cs.princeton.edu/~wayne/kleinberg-tardos/)  
   [Algorithms, Etc. by Jeff Erickson](http://jeffe.cs.illinois.edu/teaching/algorithms/)  
   [Algorithm Notes for CS 466 at Waterloo](https://cs.uwaterloo.ca/~eblais/courses/F17/CS466/outline.pdf)  
   [**Algorithms**](https://algs4.cs.princeton.edu/home/) by Robert Sedgewick and Kevin Wayne (condensed version for reference)  
   [CS Readings](http://www.cs.virginia.edu/~robins/CS_readings.html)
   [Xv6, a simple Unix-like teaching operating system - PDOS-MIT](https://pdos.csail.mit.edu/6.828/2012/xv6.html)  
   [**Operating Systems: Three Easy Pieces**](http://pages.cs.wisc.edu/~remzi/OSTEP/)  
   [Advanced Operating Systems Readings](https://www.udacity.com/wiki/ud156-readings)  
   [Microprocessors and their Architecture](https://www.byclb.com/TR/Tutorials/microprocessors/ch2_1.htm)  
   [Links to Intel  documentation](https://software.intel.com/en-us/forums/intel-isa-extensions/topic/285900)
   [Microprocessor Design - Wikibooks](https://en.wikibooks.org/wiki/Microprocessor_Design)  
   [**Mathematics for Computer Science**](https://uvacs2102.github.io/docs/mcs.pdf) by Eric Lehman, F. Thomson Leighton, and Albert R. Meyer  
   [Notes on Discrete Structures - Cornell University](https://www.cs.cornell.edu/~rafael/discmath.pdf)  
   [Notes - MIT 6.042 Mathematics for Computer Science](https://www.seas.harvard.edu/courses/cs20/MIT6_042Notes.pdf)  
   [A Course on Discrete Mathematics - Yale University](http://cs.yale.edu/homes/aspnes/classes/202/notes.pdf)  
   [Mathematics for Computer Science (2012)](https://www.iith.ac.in/~aravind/Files-DM/LLM-MFCS-2012.pdf)  
   [**How to Write Mathematics**](http://erickson.sites.truman.edu/files/2012/04/guide1.pdf) by Martin Erickson  
   [Red Book](http://www.opengl.org/documentation/red_book/)
   [The Graphics Codex - Web Edition](http://graphicscodex.com/)  
   [**Information Theory, Inference, and Learning Algorithms**](http://www.inference.org.uk/mackay/itila/book.html) by David J. C. Mackay  
   [2011 Workshop on Complexity Information Theory in Theoretical Computer Science and Discrete Mathematics](http://sites.math.rutgers.edu/~saks/IT/)  
   [A Mathematical Theory of Communication - Claude Shannon (1948)](math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf)  
   [Awesome Compilers - GitHub](https://github.com/aalhour/awesome-compilers)
   [Introduction to Software Engineering - Wikibooks](https://en.wikibooks.org/wiki/Introduction_to_Software_Engineering)  
   [Software Engineering book by Ivan Marsic](http://www.ece.rutgers.edu/~marsic/books/SE/book-SE_marsic.pdf)  
   [Supplementary Material for **Object-Oriented Software Engineering**](http://www.site.uottawa.ca/school/research/lloseng/) by Lethbridge and Laganière  
   [Software Engineering Notes from CS 440 at UIC](https://www.cs.uic.edu/~jbell/CourseNotes/OO_SoftwareEngineering/)  

# Miscellaneous links

   [ACM Classic Books Series](https://dl.acm.org/classics.cfm)
