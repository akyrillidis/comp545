<h2 align="center"><b> Advanced topics in optimization: From simple to complex ML systems</b> </h2>

<br>
<br>

<table style="width:100%">  
  <tr>
    <td>Email (instructor): anastasios@rice.edu</td>
    <td align="right">Web: https://akyrillidis.github.io/comp545/</td> 
  </tr>
  <tr>
    <td> </td>
    <td align="right">Email (course): RiceCOMP545@gmail.com</td> 
  </tr>
  <tr>
    <td>Office hours: XX:XXam </td>
    <td align="right">Class hours: T\TH 14:30 - 15:45</td> 
  </tr>
  <tr>
    <td>Office: DH 3119</td>
    <td align="right">Classroom: XXXX </td> 
  </tr>
</table>

<br>

<table style="width:100%">  
  <tr> 
    <td><a href="http://akyrillidis.github.io/comp545/index.md">Course description</a></td>
    <td align="center"><a href="http://akyrillidis.github.io/comp545/schedule.md">Schedule</a></td> 
    <td align="right"><a href="http://akyrillidis.github.io/comp545/grading.md>Grading policy</a></td> 
  </tr>
</table>

Classical courses on machine learning (ML), artificial intelligence (AI), and signal processing (SP) abide by the following recipe: 
first, they introduce models that well-fit a problem at hand; then, rigorously back up these models with intuition, and finally describe basic algorithms that solve such objectives for learning, inference and estimation.
And in most cases, a gradient-based algorithm is the solution to our problems that saves the day!

Nevertheless, there are many papers that might have come to your attention, but go beyond plain gradient descent: 
papers on momentum and acceleration; 
papers with weird names for algorithms such as AdaGrad, Adam and RMSProp; 
research on variance-reduced techniques and hyper-parameter tuning such as learning rate, mini batch size and regularization; 
papers on gradient-variants that promote structures such as sparsity and low-rankness; 
literature that discusses the matter of "convex vs. non-convex optimization" and how gradient descent behaves on each case; 
papers that study the objective landscapes for saddle points and local minima; 
papers that study how easy it is to distribute gradient descent computations; and so on...
You might wonder "_what is so different and significant in all these cases, since gradient descent is what is used after all in each case?_"

COMP 545 is a graduate-level course on optimization techniques and algorithms, as these are used in modern ML/AI/SP tasks.
During this course, we will learn and study the above topics (both in depth and breadth).
The course (i) will focus on different objective classes (convex vs. non-convex objectives, with constraints or not, etc.),
(ii) will cover different optimization strategies within each class, 
(iii) will study algorithmic choices based on computational resources (e.g., use of low-dimensional structures (when/why), asynchronous vs. synchronous algorithms, distributed algorithms, etc.)
and (iv) lastly, will study schemes that handle some specific, but well-spread optimization constraints (sparsity, low-rankness).

### Textbook

There is no textbook for the class. The class will be a collection of lectures, prepared by the instructor, as well as presentations of research papers available online. Links will be provided during the course.

### Prerequisites

Basics of calculus, linear algebra and basic knowledge of machine learning topics. 
Programming skills are not necessary, but might be required, depending on the project selected at the end of the course.
In the latter case, programming in Python/Matlab could be sufficient.

During the first class, a quiz will be given to the students to assess their background; this quiz is going to be used for course content assessment (edits in the syllabus will possibly occur).

### Course outcomes

The main objective of the course is to highlight optimization as a vital part of contemporary research in ML/AI/SP, and draw the attention of students to open-questions in related topics. 
In particular, the aim for students is to (i) learn how to distinguish differences in research papers of related fields, (ii) understand the connection between them and how researchers advance each area, and (iii) be able to consider possible extensions of these works, as part of the final (open-ended) project of the course. 

After successful attendance, students are expected to: 
- have a good understanding of the differences / difficulties of convex and non-convex optimization. 
- have a good comprehension how optimization plays a key role in different areas of ML/AI/SP. 
- have a first touch with various optimization-driven applications in ML/AI/SP. 
- be able to read and review advanced papers on similar subjects, as well as present the papers in front of an audience. \end{itemize}

```markdown
Course Policies

- During Class
I understand that the electronic recording of notes will be important for class and so computers will 
be allowed in class. Please refrain from using computers for anything but activities related to the 
class. Drinking (coffee, tea, water) is allowed in class. Try not to eat your lunch in class as the 
classes are typically active.

- Policies on Late Assignments
Assignments (scribing, reviews, project) should be turned on time. You receive a 10\% penalty for 
each day of delay, up to 2 days. No submissions after the 2 day grace period. Exceptions will be 
given to very extreme circumstances, with proper documentations.

- Academic Integrity and Honesty
Students are required to comply with the university policy on academic integrity found in the 
Honor System Handbook (http://honor.rice.edu/honor-system-handbook/).

- Accommodations for Disabilities
If you have a documented disability that may affect academic performance, you should: 1) make sure
this documentation is on file with Disability Resource Center (Allen Center, Room 111 / 
adarice@rice.edu / x5841) to determine the accommodations you need; and 2) meet with me to discuss 
your accommodation needs.
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/akyrillidis/comp545/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
