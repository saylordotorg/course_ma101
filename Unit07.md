---
layout: default
title: "MA101: Single-Variable Calculus I"
course_description: "A survey of concrete applications of how calculus is used and, more importantly, why it works, through the introduction of topics including limits, derivatives, and integrals."
next: ../Unit08
previous: ../Unit06
---
**Unit 7: Integration** <span id="7"></span> 
*In the last unit of this course, you will learn about “integral
calculus,” a subfield of calculus that studies the area formed under the
curve of a function.  Although its relationship with the derivative is
not necessarily intuitive, integral calculus is closely linked to the
derivative, which you will revisit in this unit.*

**Unit 7 Time Advisory**  
This unit should take you approximately 15.25 hours to complete.  
  
 ☐    Subunit 7.1: 3 hours  
  
 ☐    Subunit 7.2: 5.5 hours
☐    Reading: 1.5 hours  
  
 ☐    Lecture: 2 hours  
  
 ☐    Assignment: 2 hours

☐    Subunit 7.3: 2.5 hours

☐    Subunit 7.4: 4.25 hours
☐    Reading: 1.5 hours  
  
 ☐    Lecture: 0.75 hours  
  
 ☐    Assignment: 2 hours

**Unit7 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Define antiderivatives and the indefinite integral.
-   State the properties of the indefinite integral.
-   Relate the definite integral to the initial value problem and the
    area problem.
-   Set up and calculate a Riemann sum.
-   State the Fundamental Theorem of Calculus and use it to calculate
    definite integrals.
-   State and apply basic properties of the definite integral.
-   Use substitution to compute definite integrals.

**7.1 Motivation** <span id="7.1"></span> 
-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 7:
    Integration: “Section 7.1: Two Examples”**
    Link: Whitman College: David Guichard’s *Calculus: *Chapter 7:
    Integration:* *[“Section 7.1: Two
    Examples”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_07_Integration.pdf) (PDF)  
        
     Instructions: Please click on the link above and read Section 7.1
    (pages 145-149) in its entirety.  This reading introduces the
    integral through two examples.  The first example addresses the
    question of how to determine the distance traveled based only on
    information about velocity.  The second example addresses the
    question of how to determine the area under the graph of a function.
     Surprisingly, these two questions are closely related to each other
    and to the derivative.  
        
     This reading should take you approximately one hour to complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  This
    text was originally written by Professor David Guichard.  It has
    since been modified to include edited material from Neal Koblitz of
    the University of Washington, H. Jerome Keisler of the University of
    Wisconsin, Albert Schueller, Barry Balof, and Mike Wills.  You can
    access the original version
    [here](http://www.whitman.edu/mathematics/calculus/).

-   **Lecture: Massachusetts Institute of Technology: David Jerison’s
    Single Variable Calculus: “Lecture 18: Definite Integrals”**
    Link: Massachusetts Institute of Technology: David Jerison’s *Single
    Variable Calculus:* [“Lecture 18: Definite
    Integrals”](http://www.youtube.com/watch?v=rmbjnTbzmX8) (YouTube)  
        
     Instructions: Please click on the link above and watch the entire
    video (47:14).  Lecture notes are available
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/lecture-notes/lec18.pdf).  
      
     Viewing this lecture and taking notes should take you approximately
    one hour to complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Jerison and MIT's
    [OpenCourseWare](http://ocw.mit.edu/index.htm).  It may be viewed in
    its original form
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-18-definite-integrals/).

-   **Assignment: Whitman College: David Guichard’s Calculus: Chapter 7:
    Integration: “Exercises 7.1: Problems 1-8”**
    Link: Whitman College: David Guichard’s *Calculus: *Chapter 7:
    Integration:* *[“Exercises 7.1: Problems
    1-8”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_07_Integration.pdf) (PDF)  
        
     Instructions: Please click on the link above and work through
    problems 1-8 for Exercises 7.1.  When you are done, check your
    answers against [“Appendix A:
    Answers”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_12_Selected_Answers.pdf).  
        
     This assignment should take you approximately one hour to
    complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  This
    text was originally written by Professor David Guichard.  It has
    since been modified to include edited material from Neal Koblitz of
    the University of Washington, H. Jerome Keisler of the University of
    Wisconsin, Albert Schueller, Barry Balof, and Mike Wills.  You can
    access the original version
    [here](http://www.whitman.edu/mathematics/calculus/).

**7.2 The Fundamental Theorem of Calculus** <span id="7.2"></span> 
*Note: The Fundamental Theorem of Calculus is the apex of our course. 
It explains the relationship between the derivative and the integral,
tying the two major facets of this course together.  In the previous
section, you learned the definition of the definite integral as a limit
of a Riemann Sum.  The computations were long and involved.  In this
subunit, you will learn about the Fundamental Theorem of Calculus, which
makes the computation of definite integrals significantly easier.*

-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 7:
    Integration: “Section 7.2: The Fundamental Theorem of Calculus”**
    Link: Whitman College: David Guichard’s *Calculus: *Chapter 7:
    Integration:* *[“Section 7.2: The Fundamental Theorem of
    Calculus”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_07_Integration.pdf) (PDF)  
        
     Instructions: Please click on the link above and read Section 7.2
    (pages 149-155) in its entirety.  Pay close attention to the
    treatment of Riemann sums, which lead to the definite integral.  The
    Fundamental Theorem of Calculus explicitly describes the
    relationship between integrals and derivatives.  
        
     This reading should take you approximately one hour and 30 minutes
    to complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  This
    text was originally written by Professor David Guichard.  It has
    since been modified to include edited material from Neal Koblitz of
    the University of Washington, H. Jerome Keisler of the University of
    Wisconsin, Albert Schueller, Barry Balof, and Mike Wills.  You can
    access the original version
    [here](http://www.whitman.edu/mathematics/calculus/).

-   **Lecture: Massachusetts Institute of Technology: David Jerison’s
    *Single Variable Calculus*: “Lecture 19: The First Fundamental
    Theorem”**
    Link: Massachusetts Institute of Technology: David Jerison’s *Single
    Variable Calculus:* [“Lecture 19: The First Fundamental
    Theorem”](https://www.youtube.com/watch?v=1RLctDS2hUQ&feature=share&list=PL590CCC2BC5AF3BC1&index=16) (YouTube)  
        
     Instructions: Watch this video lecture. Lecture notes are available
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/lecture-notes/lec19.pdf).  
      
     Watching this lecture and taking notes should take you
    approximately one hour.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to David Jerison and MIT's
    [OpenCourseWare](http://ocw.mit.edu/index.htm). It may be viewed in
    its original form
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-19-first-fundamental-theorem/).

-   **Lecture: Massachusetts Institute of Technology: David Jerison’s
    Single Variable Calculus: “Lecture 20: The Second Fundamental
    Theorem”**
    Link: Massachusetts Institute of Technology: David Jerison’s *Single
    Variable Calculus:* [“Lecture 20: The Second Fundamental
    Theorem”](http://www.youtube.com/watch?v=hKnnIVIHrFQ) (YouTube)  
        
     Instructions: Please click on the link above and watch the entire
    video (49:30).  Lecture notes are available
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/lecture-notes/lec20.pdf).  
        
     Viewing this lecture and taking notes should take you approximately
    one hour to complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Jerison and MIT's
    [OpenCourseWare](http://ocw.mit.edu/index.htm).  It may be viewed in
    its original form
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-20-second-fundamental-theorem/).

-   **Assignment: Whitman College: David Guichard’s Calculus: Chapter 7:
    Integration: “Exercises 7.2: Problems 7-22”**
    Link: Whitman College: David Guichard’s *Calculus: *Chapter 7:
    Integration:* *[“Exercises 7.2: Problems
    7-22”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_07_Integration.pdf) (PDF)  
        
     Instructions: Please click on the link above and work through
    problems 7-22 for Exercises 7.2.  When you are done, check your
    answers against [“Appendix A:
    Answers”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_12_Selected_Answers.pdf).  
      
     This assignment should take you approximately two hours to
    complete.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  This
    text was originally written by Professor David Guichard.  It has
    since been modified to include edited material from Neal Koblitz of
    the University of Washington, H. Jerome Keisler of the University of
    Wisconsin, Albert Schueller, Barry Balof, and Mike Wills.  You can
    access the original version
    [here](http://www.whitman.edu/mathematics/calculus/).

**7.3 Some Properties of Integrals** <span id="7.3"></span> 
-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 7:
    Integration: “Section 7.3: Some Properties of Integrals”**
    Link: Whitman College: David Guichard’s *Calculus: *Chapter 7:
    Integration:* *[“Section 7.3: Some Properties of
    Integrals”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_07_Integration.pdf) (PDF)  
        
     Instructions: Please click on the link above and read Section 7.3
    (pages 156-160) in its entirety.  In particular, note that the
    definite integral enjoys the same linearity properties that the
    derivative does, in addition to some others.  In its application to
    velocity functions, pay particular attention to the distinction
    between distance traveled and net distance traveled.  
        
     This reading should take you approximately one hour to complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  This
    text was originally written by Professor David Guichard.  It has
    since been modified to include edited material from Neal Koblitz of
    the University of Washington, H. Jerome Keisler of the University of
    Wisconsin, Albert Schueller, Barry Balof, and Mike Wills.  You can
    access the original version
    [here](http://www.whitman.edu/mathematics/calculus/).

-   **Lecture: Massachusetts Institute of Technology: David Jerison’s
    Single Variable Calculus: “Lecture 15: Antiderivatives”**
    Link: Massachusetts Institute of Technology: David Jerison’s *Single
    Variable Calculus:* [“Lecture 15:
    Antiderivatives”](http://www.youtube.com/watch?v=fFZ-7I8Ifno) (YouTube)  
        
     Instructions: Please click on the link above and watch the video
    from the beginning to the 30:00 minute mark.  Lecture notes are
    available
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/lecture-notes/lec15.pdf).  
        
     Viewing this lecture and taking notes should take you approximately
    45 minutes to complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Jerison and MIT's
    [OpenCourseWare](http://ocw.mit.edu/index.htm).  It may be viewed in
    its original form
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-15-antiderivatives/).

-   **Assignment: Whitman College: David Guichard’s Calculus: Chapter 7:
    Integration: “Exercises 7.3: Problems 1-6”**
    Link: Whitman College: David Guichard’s *Calculus: *Chapter 7:
    Integration:* *[“Exercises 7.3: Problems
    1-6”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_07_Integration.pdf) (PDF)  
        
     Instructions: Please click on the link above link and work through
    problems 1-6 for Exercises 7.3.  When you are done, check your
    answers against [“Appendix A:
    Answers”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_12_Selected_Answers.pdf).  
        
     This assignment should take you approximately 45 minutes to
    complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  This
    text was originally written by Professor David Guichard.  It has
    since been modified to include edited material from Neal Koblitz of
    the University of Washington, H. Jerome Keisler of the University of
    Wisconsin, Albert Schueller, Barry Balof, and Mike Wills.  You can
    access the original version
    [here](http://www.whitman.edu/mathematics/calculus/).

**7.4 Integration by Substitution** <span id="7.4"></span> 
-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 8:
    Techniques of Integration: “Section 8.1: Substitution”**
    Link: Whitman College: David Guichard’s *Calculus: *Chapter 8:
    Techniques of Integration:* *[“Section 8.1:
    Substitution”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_08_Techniques_of_Integration.pdf) (PDF)  
        
     Instructions: Please click on the link above and read Section 8.1
    (pages 161-166) in its entirety.  This section explains the process
    of taking the integral of slightly more complicated functions.  We
    do this by implementing a “change of variables,” or rewriting a
    complicated integral in terms of elementary functions that we
    already know how to integrate.  Simply put, integration by
    substitution is merely the act of taking the chain rule in
    reverse.  
        
     This reading should take approximately one hour and 30 minutes to
    complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  This
    text was originally written by Professor David Guichard.  It has
    since been modified to include edited material from Neal Koblitz of
    the University of Washington, H. Jerome Keisler of the University of
    Wisconsin, Albert Schueller, Barry Balof, and Mike Wills.  You can
    access the original version
    [here](http://www.whitman.edu/mathematics/calculus/).

-   **Lecture: Massachusetts Institute of Technology: David Jerison’s
    Single Variable Calculus: “Lecture 15: Antiderivatives”**
    Link: Massachusetts Institute of Technology: David Jerison’s *Single
    Variable Calculus:* [“Lecture 15:
    Antiderivatives”](http://www.youtube.com/watch?v=fFZ-7I8Ifno) (YouTube)  
        
     Instructions: Please click on the link above and watch the video
    from the 30:00 minute mark to the end.  Lecture notes are available
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/lecture-notes/lec15.pdf).  
      
     Viewing this lecture and taking notes should take you approximately
    45 minutes to complete.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Jerison and MIT's
    [OpenCourseWare](http://ocw.mit.edu/index.htm).  It may be viewed in
    its original form
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-15-antiderivatives/).

-   **Assignment: Whitman College: David Guichard’s Calculus: Chapter 8:
    Techniques of Integration: “Exercises 8.1: Problems 5-19”**
    Link: Whitman College: David Guichard’s *Calculus: *Chapter 8:
    Techniques of Integration: [“Exercises 8.1: Problems
    5-19”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_08_Techniques_of_Integration.pdf) (PDF)  
        
     Instructions: Please click on the link above link and work through
    problems 5-19 for Exercises 8.1.  When you are done, check your
    answers against [“Appendix A:
    Answers”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/calculus_12_Selected_Answers.pdf).  
        
     This assignment should take you approximately two hours to
    complete.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).  This
    text was originally written by Professor David Guichard.  It has
    since been modified to include edited material from Neal Koblitz of
    the University of Washington, H. Jerome Keisler of the University of
    Wisconsin, Albert Schueller, Barry Balof, and Mike Wills.  You can
    access the original version
    [here](http://www.whitman.edu/mathematics/calculus/).


