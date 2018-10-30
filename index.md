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
<br>

### Course Description 

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

The main objective of the course is to highlight optimization as a vital part of contemporary research in ML/AI/SP, and draw the attention of students to open-questions in related topics. 
In particular, the aim for students is to (i) learn how to distinguish differences in research papers of related fields, (ii) understand the connection between them and how researchers advance each area, and (iii) be able to consider possible extensions of these works, as part of the final (open-ended) project of the course. 

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/akyrillidis/comp545/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
