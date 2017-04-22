# CS533 Course Project  
**TA: Madhumeta Ganesh**  
**Email: mganesh@pdx.edu**  
**Office Hours: Tuesdays and Thursdays at 10:30AM to 11:30AM and by appointment**  

Throughout the term, you will be developing aspects of a user-level threads package, including context-switching, scheduling, and synchronization.

Because many of the mechanisms we will be using are platform-dependent, it is important that everyone is using the same environment. To that end, we ask that students work remotely on the CS department's general-purpose Linux platform, `ada.cs.pdx.edu`. Ada is a 30-core x86-64 server running Ubuntu Linux with a variety of useful software pre-installed.

To connect to Ada, you will need an SSH client (I suggest using the terminal or [iTerm2](https://iterm2.com) for macOS, [mosh](https://mosh.mit.edu/) for Linux/Cygwin and [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/) for Windows), and an MCECS resource account, which is separate from your ODIN account and is maintained by [the CAT](http://cat.pdx.edu/). If you do not have an MCECS account, please visit the [CS Tutors](http://cat.pdx.edu/tutors.html) in FAB 88.

All code will be written in the C programming language, along with a small portion in GNU Assembler for the first assignment. We assume you have some knowledge of C; if you need to brush up, we recommend [The C Programming Language](http://en.wikipedia.org/wiki/The_C_Programming_Language) by Kernighan and Ritchie. A copy of this book is available from the CS Tutors for checkout while you are in the CS lounge (FAB 88). Knowledge of GNU Assembler syntax is helpful, but not required; some tips on the assembly required are provided [here](http://web.cecs.pdx.edu/~walpole/class/cs533/spring2017/project/project/assign1/asm_hints.md).

This project also assumes some knowledge of working on the Unix/Linux command-line, especially the use of the GNU Compiler Collection (gcc). If you need a refresher, consider attending the workshops offered by the CS Tutors near the beginning of the term, and/or browsing their [tutorials page](http://cat.pdx.edu/tutors/tutorials.html). If you need additional assistance, contact [the TA](http://web.cecs.pdx.edu/~walpole/class/cs533/spring2017/project/) or the [course mailing list](https://mailhost.cecs.pdx.edu/mailman/listinfo/cs533).

## Assignments

The project is divided into five assignments, each increasing in complexity. Assignments are due every two weeks. To complete each project, it is highly recommended that you start on them as early as possible!

* [Context Switching](https://github.com/madhu-ganesh/CS533-Operating-Systems/tree/master/Assignment_1): **Due April 14**
* [Round-robin Scheduling](https://github.com/madhu-ganesh/CS533-Operating-Systems/tree/master/Assignment_2): **Due April 28**
* [Asynchronous I/O](https://github.com/madhu-ganesh/CS533-Operating-Systems/tree/master/Assignment_3): **Due May 12**
* [Synchronization](https://github.com/madhu-ganesh/CS533-Operating-Systems/tree/master/Assignment_4): **Due May 26**
* [M:N Threading](https://github.com/madhu-ganesh/CS533-Operating-Systems/tree/master/Assignment_5): **Due May 9**

## Grading

The main goal of this project is to give you hands-on experience with the implementation of some of the complex concepts we will be encountering throughout the course.

With that in mind, we will use the project primarily as an educational tool, rather than an assessment tool. Your project assignments will not be graded, hence they will not contribute directly to your overall grade. However, the midterm and final exams will contain questions that relate to the project assignments, in addition to those that test understanding of the concepts covered in the lectures and course reading material. Hence, it is important that you complete the project assignments and learn from them. They should not be considered optional!
