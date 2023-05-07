Download Link: https://assignmentchef.com/product/solved-lab-assignment-8
<br>
Problem DescriptionThis assignment is to develop a simple grade book application. A grade book has multiple rows and multiple columns. Each column represents an assignment and each row records the grades of a student from those assignments as illustrated below.




<table class=" aligncenter" style="height: 314px;" width="367">

 <tbody>

  <tr>

   <td width="75"></td>

   <td width="75"><em>1</em></td>

   <td width="75"><em>2</em></td>

   <td width="75"><em>3</em></td>

   <td width="75"><em>…</em></td>

   <td width="75"><em>n</em></td>

  </tr>

  <tr>

   <td width="75"><em>1</em></td>

   <td width="75">89.50</td>

   <td width="75">97.00</td>

   <td width="75">75.00</td>

   <td width="75">…</td>

   <td width="75">100.00</td>

  </tr>

  <tr>

   <td width="75"><em>2</em></td>

   <td width="75">95.00</td>

   <td width="75">89.90</td>

   <td width="75">85.50</td>

   <td width="75">…</td>

   <td width="75">92.60</td>

  </tr>

  <tr>

   <td width="75">…</td>

   <td width="75">…</td>

   <td width="75">…</td>

   <td width="75">…</td>

   <td width="75">…</td>

   <td width="75">…</td>

  </tr>

  <tr>

   <td width="75"><em>k</em></td>

   <td width="75">92.50</td>

   <td width="75">99.00</td>

   <td width="75">100.00</td>

   <td width="75">…</td>

   <td width="75">93.00</td>

  </tr>

 </tbody>

</table>

<p style="text-align: left;">When the application starts, it should prompt the user to enter the number of students and the number of assignments. After receiving those numbers, the application should prompt the user to enter grades.After all grades are entered, the application should then display all the grades in the grade book. The grades of each student should be displayed in a single line. After all grades are displayed, the application should produce a report of the average grades of students. In addition, it should generate a report about the statistics of the assignments including the average score, the highest score, and the lowest score of each assignment.Here is a sample run of three students, four assignments and 12 test case grades:

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/959.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/959.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Assignment RequirementsThe following specific requirements must be met:• The grade book should be implemented as a two-dimensional array• Create a sub-method to read the grades, store the grades in a two-dimensional array (grade book), and then return the grade book to the caller.• Create a sub-method to display all grades in the grade book passed into the method as a parameter• Create a sub-method to compute and display the average grades of the students in the grade book passed into the method as a parameter• Create a sub-method to calculate and report the statistics of all assignments in the grade book passed into the method as a parameter• The main method of the program must call those methods to read the grade book and produce those reports• If either the number of students or the number of assignments or both is not positive, you program should report the error and terminate the execution as shown in the example below:<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/323.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/323.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>• Your program should pass the following test cases:a. Negative assignments inputb. Negative students inputc. 3 students, 4 assignments, grades matching the test case values above• Include a screenshot of the sample run (run through your program) along with the test cases in your screenshots.Submission RequirementsYour assignment submission should include the following items:• The Java source code file (i.e., *.java file)• The screen captures of the test cases you runSubmit all those files above into the dropbox of this assignment.Assignment AssessmentThe assessment rubric for the assignment is below:Task Items Complete &amp; Correct Incomplete/Partially Correct MissingSolution Pseudo-Code (Java comments) (10%) 100% By % 0Java Program (60%) 100% By % 0Testing Completeness (30%) 100% By % 0