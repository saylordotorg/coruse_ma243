---
layout: default
title: "MA243: Complex Analysis"
course_description: "An introduction to the theory of the analytic functions of a complex variable."
next: ../Unit07
previous: ../Unit05
---
**Unit 6: Singularities and Power Series** <span id="6"></span> 
*In this unit we will consider functions that are analytic in a disk
with the center removed. (The center of the disk is called an isolated
singularity.) We will be focusing on the behavior of the function close
to the singularity and identify the three kinds of singularities:
removable singularities, poles, and essential singularities. In the case
where the singularities of the function are poles, the function is
called a meromorphic function.    
  
 Isolated singularities can be classified by using the Laurent Series
Expansion about the singularity, which will be introduced at the end of
the unit, and understanding Laurent Series is fundamental for using
Residue Theory, which will be the focus of Unit 7.*

**Unit 6 Time Advisory**  
This unit will take you 19.5 hours to complete  
    
 ☐    Subunit 6.1: 1 hour  
  
 ☐    Subunit 6.2: 2 hours  
  
 ☐    Subunit 6.3: 1.5 hours  
  
 ☐    Subunit 6.4: 1 hour  
  
 ☐    Subunit 6.5: 1 hour  
  
 ☐    Subunit 6.6: 8 hours
<span id="cke_bm_592S" style="display: none;"> </span>☐    Subunit
6.6.1: 1.5 hours  
  
 ☐    Subunit 6.6.2: 1 hour  
  
 ☐    Subunit6.6.3: 4.5 hours  
  
 ☐    Subunit 6.6.4: 1 hour<span id="cke_bm_592E"
style="display: none;"> </span>

☐    Subunit 6.7: 5 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Define analytic functions and find power series representations of
    holomorphic functions.
-   Find Laurent series for meromorphic functions.
-   Define and calculate residues.
-   State fundamental results about the zeros of analytic functions and
    use them to establish results about the uniqueness of functions and
    series representations of functions.
-   Classify singularities as removable singularities, poles, or
    essential singularities.
-   State the Maximum Modulus Theorem and use it to establish uniqueness
    results.
-   State and use Riemann’s Theorem on Removable Singularities.
-   State results about the boundedness of a function near a
    singularity.
-   State and use the Casorati-Weierstrass Theorem.
-   Classify isolated singularities at infinity.

**6.1 Power Series Representation of Analytic Functions** <span
id="6.1"></span> 
-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “8.1: Taylor and Laurent Series: Power Series and
    Holomorphic Functions”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[8.1: Taylor and Laurent Series: Power Series and
    Holomorphic
    Functions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 90 (marked page 86) of the
    document and read the indicated section.   
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

**6.2 Laurent Series and Residues Introduced** <span id="6.2"></span> 
-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “8.3: Taylor and Laurent Series: Laurent Series”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[8.3: Taylor and Laurent Series: Laurent
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 95 (marked page 91) of the
    document and read the indicated section.   
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

-   **Lecture: Suffolk University: Professor Adam Glesser’s F09 Suffolk
    Math 481, Lecture 22: Laurent Series**
    Link: Suffolk University: Professor Adam Glesser’s [F09 Suffolk Math
    481, Lecture 22: Laurent
    Series](http://adamglesserf09math481.wordpress.com/page/1/) (Flash
    Video)  
        
     Instructions: Click on the link above, then scroll down to the
    indicated lecture.  Click on “click to play” to play the video
    (Time: 1 hour, 8 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**6.3 Zeros of an Analytic Function** <span id="6.3"></span> 
-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “8.2: Taylor and Laurent Series: Classification of
    Zeros and the Identity Principle”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[8.2: Taylor and Laurent Series: Classification
    of Zeros and the Identity
    Principle](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 93 (marked page 89) of the
    document and read the indicated section.   
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

**6.4 Uniqueness of Series Representations** <span id="6.4"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “7.3: Taylor Series, Uniqueness, and the Maximum
    Principle: Uniqueness”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[7.3: Taylor Series, Uniqueness, and the Maximum
    Principle:
    Uniqueness](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 7:
    Taylor Series, Uniqueness, and the Maximum Principle.”  The
    reference will open in PDF.  Scroll down to page 5 of the document
    and read the indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**6.5 The Maximum Modulus Theorem** <span id="6.5"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “7.4: Taylor Series, Uniqueness, and the Maximum
    Principle: The Maximum Principle”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[7.3: Taylor Series, Uniqueness, and the Maximum
    Principle: The Maximum
    Principle](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 7:
    Taylor Series, Uniqueness, and the Maximum Principle.” The reference
    will open in PDF.  Scroll down to page 8 of the document and read
    the indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**6.6 Classification of Singularities** <span id="6.6"></span> 
**6.6.1 Removable Singularities** <span id="6.6.1"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “8.1: Isolated Singularities and Laurent Series:
    Removable Singularities”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[8.1: Isolated Singularities and Laurent Series:
    Removable
    Singularities](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 8:
    Isolated Singularities and Laurent Series.” The reference will open
    in PDF.  Please read the indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Lecture: Suffolk University: Professor Adam Glesser’s F09 Suffolk
    Math 481, Lecture 23: Zeros and Singularities**
    Link: Suffolk University: Professor Adam Glesser’s [Lecture 23:
    Zeros and
    Singularities](http://adamglesserf09math481.wordpress.com/page/1/)(Flash
    Video)  
        
     Instructions: Click on the link above, then scroll down to the
    indicated lecture.  Click on “click to play” to play the video
    (Time: 42 minutes).  
        
     Note that this lecture covers subunits 6.3 and 6.6.1 and introduces
    material for subunits 6.6.2 and 6.6.3.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**6.6.2 Poles** <span id="6.6.2"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “8.2: Isolated Singularities and Laurent Series:
    Poles”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[8.2: Isolated Singularities and Laurent Series:
    Poles](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 8:
    Isolated Singularities and Laurent Series.”  The reference will open
    in PDF.  Scroll down to page 4 of the document and read the
    indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**6.6.3 Essential Singularities** <span id="6.6.3"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “8.3: Isolated Singularities and Laurent Series:
    Essential Singularities”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[8.3: Isolated Singularities and Laurent Series:
    Essential
    Singularities](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 8:
    Isolated Singularities and Laurent Series.”  The reference will open
    in PDF.  Scroll down to page 4 of the document and read the
    indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Lecture: Suffolk University: Professor Adam Glesser’s F09 Suffolk
    Math 481, Lecture 24: Poles**
    Link: Suffolk University: Professor Adam Glesser’s [F09 Suffolk Math
    481, Lecture 24:
    Poles](http://adamglesserf09math481.wordpress.com/page/1/) (Flash
    Video)  
        
     Instructions: Click on the link above, then scroll down to the
    indicated lecture.  Click on “click to play” to play the video
    (Time: 1 hour, 9 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Washington University in St. Louis: Professor M.
    Victor Wickerhauser’s Complex Variables: “HW \# 5”**
    Link: Washington University in St. Louis: Professor M. Victor
    Wickerhauser’s Complex Variables: “[HW \#
    5](http://www.math.wustl.edu/~victor/classes/ma416/)” (PDF)  
        
     Instructions: Click on the link and scroll down to the link to
    HW\#5, which will open in PDF.  Work through all problems. When
    finished, return to the first page and click on the “solutions”
    link.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: University of Illinois, Urbana-Champaign: Professor
    Robert Ash and W.P. Novinger’s Complex Variables: “Chapter 2.2,
    Problem 5; Chapter 2.4, Problem 1; and Chapter 4.1, Problems 10 and
    13”**
    Link: University of Illinois, Urbana-Champaign: Professor Robert Ash
    and W.P. Novinger’s Complex Variables: “[Chapter 2.2, Problem 5;
    Chapter 2.4,  Problem 1; and Chapter 4.1, Problems 10 and
    13](http://www.math.uiuc.edu/~r-ash/CV.html)” (PDF)  
        
     Instructions: Click on the link and select “Chapter 2” which will
    open in PDF.  Problems for section 2.2 begin on page 17 and those
    for sections 2.4 begin on page 26.  
        
     Next, return to the main page and click on “Chapter 4.”  Problems
    for section 4.1 begin on page 6.   
        
     When finished, return to the main page and click on the “Solutions”
    link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**6.6.4 Isolated Singularities at Infinity** <span id="6.6.4"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “8.4: Isolated Singularities and Laurent Series:
    Isolated Singularities at Infinity”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[8.4: Isolated Singularities and Laurent Series: Isolated
    Singularities at
    Infinity](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 8:
    Isolated Singularities and Laurent Series: Removable
    Singularities.”  The reference will open in PDF.  Scroll down to
    page 5 of the document and read the indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**6.7 Laurent Series Revisited** <span id="6.7"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “8.6: Isolated Singularities and Laurent Series:
    Removable Singularities: Taylor Series, Uniqueness, and the Maximum
    Principle: Laurent Series”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[8.6: Isolated Singularities and Laurent Series: Laurent
    Series](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 8:
    Isolated Singularities and Laurent Series.”  The reference will open
    in PDF.  Scroll down to page 7 of the document and read the
    indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Washington University in St. Louis: Professor M.
    Victor Wickerhauser’s Complex Variables: “HW \#8”**
    Link: Washington University in St. Louis: Professor M. Victor
    Wickerhauser’s Complex Variables: “[HW \#
    8](http://www.math.wustl.edu/~victor/classes/ma416/)” (PDF)  
        
     Instructions: Click on the link and scroll down to the HW \#8,
    which will open in PDF.  Work through the indicated problems.  When
    finished, return to the first page and click on the “solutions”
    link.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: University of Illinois, Urbana-Champaign: Professor
    Robert Ash and W.P. Novinger’s Complex Variables: “Chapter 4.1,
    Problems 3-6”**
    Link: University of Illinois, Urbana-Champaign: Professor Robert Ash
    and W.P. Novinger’s Complex Variables: “[Chapter 4.1, Problems
    3-6](http://www.math.uiuc.edu/~r-ash/CV.html)” (PDF)  
        
     Instructions: Click on the link and select “Chapter 4” which will
    open in PDF.  Scroll down to page 5 and work through the indicated
    problems.  When finished, return to the main page and click on the
    “Solutions” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


