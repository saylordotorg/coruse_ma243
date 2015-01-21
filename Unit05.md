**Unit 5: Integration** <span id="5"></span> 
*We earlier defined analytic or holomorphic functions as functions
differentiable in an open set.  We will now see that the derivative of
an analytic function is continuous and that in fact higher derivatives
also exist, using complex integration to prove it.  
           
 We will also discuss curves in the complex plane—that is, functions
from a closed bounded interval of real numbers into the complex
plane—before defining the integral of a complex function along a curve
in the complex plane (contour or line integrals).  
          
 We will then learn about the main theorem of complex analysis: Cauchy’s
Theorem.  As a consequence of the theorem, we will see that an analytic
function can be represented as a contour integral where the function’s
argument acts as a parameter (Cauchy’s Integral Formula). Cauchy’s
Theorem will also enable us to prove that an analytic function is
infinitely differentiable and that the sum of a power series is analytic
inside the domain of convergence.  Conversely, any analytic function can
be represented by a power series.  
            
 We will finish by proving some of the most important consequences of
Cauchy’s Theorem: the Fundamental Theorem of Algebra, Liouville’s
Theorem, and Morera’s Theorem.*

**Unit 5 Time Advisory**  
This unit will take you 20 hours to complete  
    
 ☐    Subunit 5.1: 2 hours  
  
 ☐    Subunit 5.2: 4.5 hours

☐   <span id="cke_bm_592S" style="display: none;"> </span> Subunit
5.2.1: 2 hours  
  
 ☐    Subunit 5.2.2: 1.5 hours  
  
 ☐    Subunit 5.2.3: 1 <span id="cke_bm_592E"
style="display: none;"> </span>hour

☐    Subunit 5.3: 3 hours

☐    Subunit 5.4: 2.5 hours  
  
 ☐    Subunit 5.5: 2 hours

☐    Subunit 5.5.1: 1 hour

☐    Subunit 5.5.2-5.5.3: 1 hour

☐    Subunit 5.6: 6 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Define key terms relating the curves in the complex plane,
    including: simple, closed, smooth, pathwise-smooth, positively
    oriented, etc.
-   Find the length of a smooth curve.
-   Write a parameterization of a curve that traverses a given path.
-   Define homotopy.
-   State and prove Cauchy’s Theorem. Use its corollaries.
-   State and prove Cauchy’s Integral Formula.
-   State the Jordan Curve Theorem.
-   Calculate contour integrals.
-   Bound contour integrals.
-   Define equivalent curves.
-   State the Fundamental Theorem of Algebra and Liouville’s Theorem and
    derive them as consequences of Cauchy’s Theorem.
-   Define primitive and state the First and Second Fundamental Theorems
    of Calculus in the context of contour integrals.
-   State and prove Morera’s theorem.

**5.1 Curves in the Complex Plane** <span id="5.1"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “4.1: Complex Integrals: Curves in the Complex
    Plane”**
    Link: Imperial College, London: W.W.L.Chen’s  Introduction to
    Complex Analysis: “[4.1: Complex Integrals: Curves in the Complex
    Plane](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 4:
    Complex Integrals.”  The reference will open in PDF.  Please read
    the indicated (short) section, noting in particular the
    illustrations of paths and different types of curves.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “4.1 Integration: Definition and Basic
    Properties”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[4.1 Integration: Definition and Basic
    Properties](http://www.saylor.org/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 48 (marked page 44) of the
    document and read the indicated section. Note in particular the
    calculation of arc length, which should be familiar to you from
    Calculus.  
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

-   **Lecture: Suffolk University: Professor Adam Glesser’s F09 Suffolk
    Math 481, Lecture 11: Contours and Contour Integrals**
    Link: Suffolk University: Professor Adam Glesser’s [F09 Suffolk Math
    481, Lecture 11: Contours and Contour
    Integrals](http://adamglesserf09math481.wordpress.com/page/2/)
    (Flash Video)  
        
     Instructions: Click on the link above, then scroll down to the
    indicated lecture.  Click on “click to play” to play the video
    (Time: 1 hour, 6 minutes).  
        
     Note that we have skipped Lecture 10 because it is merely a long
    preparation for this lecture, making most of the same definitions in
    the context of R<sup>2</sup>.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.2 Contour Integrals** <span id="5.2"></span> 
**5.2.1 Definitions** <span id="5.2.1"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “4.2: Complex Integrals: Contour Integrals”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[4.2: Complex Integrals: Contour
    Integrals](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 4:
    Complex Integrals.”  The reference will open in PDF.  Scroll down to
    page 3 of the document and read the indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Lecture: Suffolk University: Professor Adam Glesser’s F09 Suffolk
    Math 481, Lecture 12: Examples of Contour Integrals**
    Link: Suffolk University: Professor Adam Glesser’s [F09 Suffolk Math
    481, Lecture 12: Examples of Contour
    Integrals](http://adamglesserf09math481.wordpress.com/page/2/)
    (Flash Video)  
        
     Instructions: Click on the link above, then scroll down to the
    indicated lecture.  Click on “click to play” to play the video
    (Time: 1 hour, 3 minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.2.2 Inequalities** <span id="5.2.2"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “4.3: Complex Integrals: Inequalities for Contour
    Integrals”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[4.3: Complex Integrals: Inequalities for Contour
    Integrals](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 4:
    Complex Integrals.”  The reference will open in PDF.  Scroll down to
    page 6 of the document and read the indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Lecture: Louisiana Tech University: Professor Bernd Schröder’s
    Introduction to Complex Analysis: “Lecture 12: Upper Bounds for
    Integrals”**
    Link: Louisiana Tech University: Professor Bernd Schröder’s
    Introduction to Complex Analysis: “[Lecture 12: Upper Bounds for
    Integrals](http://www2.latech.edu/%7Eschroder/comp_var_videos.htm)”
    (Windows Media Video)  
        
     Instructions: Click on the link above and scroll down to the
    indicated video.  Click on “Video” to download the lecture in WMV
    format.  Once it has downloaded, watch it in its entirety (Time: 11
    minutes).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.2.3 Equivalent Curves** <span id="5.2.3"></span> 
-   **Reading: Imperial College, London: W.W.L.Chen’s Introduction to
    Complex Analysis: “4.4: Complex Integrals: Equivalent Curves”**
    Link: Imperial College, London: W.W.L.Chen’s Introduction to Complex
    Analysis: “[4.4: Complex Integrals: Equivalent
    Curves](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html)”
    (PDF)  
        
     Instructions: Click on the link above, then click on “Chapter 4:
    Complex Integrals.”  The reference will open in PDF.  Scroll down to
    page 7 of the document and read the indicated section.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.3 Cauchy’s Theorem** <span id="5.3"></span> 
-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “4.2: Integration: Cauchy’s Theorem”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[4.2: Integration: Cauchy’s
    Theorem](http://www.saylor.org/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 51 (marked page 47) of the
    document and read the indicated section.   
        
     This is perhaps the most important theorem that you will learn in
    this course, and you should commit it to memory.  Note that a second
    proof can be found in Professor Chen’s notes, [Chapter 5, Sections 1
    and
    2](http://rutherglen.science.mq.edu.au/wchen/lnicafolder/lnica.html).  
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

-   **Lecture: Louisiana Tech University: Professor Bernd Schröder’s
    Introduction to Complex Analysis: “Lecture 13: Cauchy-Goursat
    Theorem”**
    Link: Louisiana Tech University: Professor Bernd Schröder’s
    Introduction to Complex Analysis: “[Lecture 13: Cauchy-Goursat
    Theorem](http://www2.latech.edu/%7Eschroder/comp_var_videos.htm)”
    (Windows Media Video)  
        
     Instructions: Click on the link above and scroll down to the
    indicated video.  Click on “Video1” to download the first part of
    the lecture in WMV format.  Once it has downloaded, watch it in its
    entirety (Time: 39:03 minutes). Next, click on “Video2” to download
    the second part of the lecture, and watch it in its entirety (Time:
    12:25 minutes).  
        
     Note that this lecture covers subunits 5.2.3 and 5.3.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.4 Cauchy’s Integral Formula and the Jordan Curve Theorem** <span
id="5.4"></span> 
-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “4.3: Integration: Cauchy’s Integral Formula”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[Integration: Cauchy’s Integral
    Formula](http://www.saylor.org/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 53 (marked page 49) of the
    document and read the indicated section.   
        
     Cauchy’s Integral Formula should also be committed to memory.  
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

-   **Lecture: Louisiana Tech University: Professor Bernd Schröder’s
    Introduction to Complex Analysis: “Lecture 14: Cauchy Integral
    Formula”**
    Link: Louisiana Tech University: Professor Bernd Schröder’s
    Introduction to Complex Analysis: “[Lecture 14: Cauchy Integral
    Formula](http://www2.latech.edu/%7Eschroder/comp_var_videos.htm)”
    (Windows Media Video)  
        
     Instructions: Click on the link above and scroll down to the
    indicated video.  Click on “Video” to download the lecture in WMV
    format.  Once it has downloaded, watch it in its entirety (Time:
    35:17 minutes).  
        
     This video is intended to cover subunits 5.4 and 5.5.1.  Note,
    however, that it also covers some of the material for subunits
    5.5.2-5.5.6.  This latter material will be covered again in the
    video lecture listed in subunit 5.5.6 at a slower pace.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.5 Consequences of Cauchy’s Theorem** <span id="5.5"></span> 
**5.5.1 Derivatives** <span id="5.5.1"></span> 
-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “5.1: Consequences of Cauchy’s Theorem: Extensions
    of Cauchy’s Formula”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[5.1: Consequences of Cauchy’s Theorem:
    Extensions of Cauchy’s
    Formula](http://www.saylor.org/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 59 (marked page 55) of the
    document and read the indicated section.   
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

**5.5.2 Fundamental Theorem of Algebra** <span id="5.5.2"></span> 
*The Reading for this course is covered by 5.5.3.*

**5.5.3 Liouville’s Theorem** <span id="5.5.3"></span> 
-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “5.2: Consequences of Cauchy’s Theorem: Taking
    Cauchy’s Formula to the Limit”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[5.2: Consequences of Cauchy’s Theorem: Taking
    Cauchy’s Formula to the
    Limit](http://www.saylor.org/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 61 (marked page 57) of the
    document and read the indicated section.   
        
     Note that this reading covers subunits 5.5.2 and 5.5.3.  
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

**5.6 Antiderivatives and Morera’s Theorem** <span id="5.6"></span> 
-   **Reading: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “5.3: Consequences of Cauchy’s Theorem:
    Antiderivatives”**
    Link: San Francisco State University: Matthias Beck, Gerald
    Marchesi, Dennis Pixton, and Lucas Sabalka’s A First Course in
    Complex Analysis: “[5.3: Consequences of Cauchy’s Theorem:
    Antiderivatives](http://www.saylor.org/site/wp-content/uploads/2012/01/complex.pdf)”
    (PDF)  
        
     Instructions: Scroll down to page 64 (marked page 60) of the
    document and read the indicated section.   
        
     Terms of Use: The material above has been reposted with permission
    by Matthias Beck, Gerald Marchesi, Dennis Pixton, and Lucas Sabalka.
     It can be viewed in its original form
    [here](http://math.sfsu.edu/beck/complex.html) (PDF).  It may not be
    altered in any way.

-   **Lecture: Suffolk University: Professor Adam Glesser’s F09 Suffolk
    Math 481, Lecture 20: Some Applications**
    Link: Suffolk University: Professor Adam Glesser’s [F09 Suffolk Math
    481, Lecture 20: Some
    Applications](http://adamglesserf09math481.wordpress.com/page/1/)
    (Flash Video)  
        
     Instructions: Click on the link above, then scroll down to the
    indicated lecture.  Click on “click to play” to play the video
    (Time: 1 hour, 13 minutes).  
        
     Note that video covers subunits 5.5.2-5.6.  Also note that much of
    the material in this video was presented at a faster pace in the
    video lecture for subunit 5.4.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Washington University in St. Louis: Professor M.
    Victor Wickerhauser’s Complex Variables: “HW \# 4, Problems 2 and 3”
    and “HW \#9, Problem 4”**
    Link: Washington University in St. Louis: Professor M. Victor
    Wickerhauser’s Complex Variables: “[HW \# 4, Problems 2 and
    3](http://www.math.wustl.edu/%7Evictor/classes/ma416/)” (PDF) and
    “[HW \# 9, Problem
    4](http://www.math.wustl.edu/%7Evictor/classes/ma416/)” (PDF)  
        
     Instructions: Click on the link and scroll down to the links to
    HW\#4 and HW \#9, which will open in PDF.  Work through the
    indicated problems.  When finished, return to the first page and
    click on the “solutions” links.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: University of Illinois, Urbana-Champaign: Professor
    Robert Ash and W.P. Novinger’s Complex Variables: “Chapter 2.1,
    Problems 1-3, 2.2, Problems 5 and 13, and 2.4, Problems 13, 16-19”**
    Link: University of Illinois, Urbana-Champaign: Professor Robert Ash
    and W.P. Novinger’s Complex Variables: “[Chapter 2.1, Problems 1-3;
    2.2, Problems 5 and 13; and 2.4, Problems 13,
    16-19](http://www.math.uiuc.edu/%7Er-ash/CV.html)” (PDF)  
        
     Instructions: Click on the link and select “Chapter 2” which will
    open in PDF.  Problems for section 2.1 begin on page 9, those for
    sections 2.2 begin on page 17, and those for section 2.4 on page 26.
     When finished, return to the main page and click on the “Solutions”
    link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


