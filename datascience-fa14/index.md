---
title: CS194-16 Introduction to Data Science
layout: default
---

# CS 194-16 Introduction to Data Science, UC Berkeley - Fall 2014

Organizations use their data for decision support and to build data-intensive
products and services. The collection of skills required by organizations to
support these functions has been grouped under the term Data Science. This
course will attempt to articulate the expected output of Data Scientists and
then equip the students with the ability to deliver against these expectations.
The assignments will involve web programming, statistics, and the ability to
manipulate data sets with code.

## Logistics

* Course Number: CS 194-16, CS 294-16 Fall 2014, UC Berkeley
* Instructor: [John Canny](http://cs.berkeley.edu/~jfc)
* Time: MW 5pm - 6:30pm
* Location: 145 Moffit
* Teaching Assistants: [Charles Reiss](https://www.eecs.berkeley.edu/~charles) [Biye Jiang]
* Discussion: Join [Piazza](https://piazza.com/class/) for
  announcements and to ask questions about the course
* Office hours:
  - John Canny - ? at 637 Soda
  - GSIs - ? at ? Soda

## Pre-requisites
Pre-requisites for this course include 61A, 61B, 61C and basic programming skills. Knowledge of Python will be useful for the assignments, and a few will also use the Scala language. Students will also be expected to run [VirtualBox](https://www.virtualbox.org/) on their laptops for the assignments.

Please take the class survey [here](https://docs.google.com/a/berkeley.edu/forms/d/1LWuhIdR8_y7FX2WeI5wAlwX2vDeaPo1E5ghAeUHUEBs/viewform).

Plese set up your machine according to [these instuctions](setup.html).

## Grading

* Class Participation and in-class labs: 20%
* Midterm: 20%
* Final Project (in groups): 25%  Final Project Information is [Here](finalproject.html)
* Homeworks : 30%  (3 @ 10% each: <a href="http://goo.gl/Pkku0e">Homework 1</a>; 
                                  <a href="http://goo.gl/Jpneux">Homework 2</a>; Homework 3)  
* "Bunnies" : 5%

## Schedule (warning - very early draft!)

<table class="table table-striped">
  <thead>
    <tr>
      <td><b>Lecture Date</b></td>
      <td><b>Lecture Material</b></td>
      <td><b>Weds Lab</b></td>
      <td><b>Reading</b></td>
      <td><b>Assignments</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>W 9/3</td>
      <td>L1: Introduction/Data Science Process
      <a href="https://drive.google.com/a/berkeley.edu/file/d/0B5q5EyRrPiIfWi1XNTBpVXh5Vms/edit?usp=sharing">[PPTX]</a>
        
      <a href="https://drive.google.com/a/berkeley.edu/file/d/0B5q5EyRrPiIfajJPcURYcTJHekk/edit?usp=sharing">[PDF]</a>
      </td>
      <td>No Lab</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>M 9/8</td>
      <td>L2: Data Preparation 
      <a href="https://drive.google.com/a/berkeley.edu/file/d/0B5q5EyRrPiIfYjQ5d0pzTDRFR0k/edit?usp=sharing">[PPTX]</a>
        
      <a href="https://drive.google.com/a/berkeley.edu/file/d/0B5q5EyRrPiIfN24xejYyc1JCMkk/edit?usp=sharing">[PDF]</a>
      </td>
      <td>
        <a href="https://github.com/biddata/datascience-fa14/tree/master/lab1">Lab 1</a>
      Unix
      </td>
      <td><a href="http://vis.stanford.edu/files/2012-EnterpriseAnalysisInterviews-VAST.pdf">Enterprise Data Analysis and Visualization: An Interview Study</a></td>
      <td>
        <a href="http://goo.gl/SqDnW6">Bunny 1</a> by 5pm on 9/8
        <!-- | <a href="http://goo.gl/VPhVGW">Responses</a> -->
      </td>
    </tr>
    <tr>
      <td>M 9/15</td>
      <td>L3: Tabular Data 
      <a href="https://drive.google.com/a/berkeley.edu/file/d/0B5q5EyRrPiIfOHRmTkxQYmhWdHM/edit?usp=sharing">[PPTX]</a>
      <a href="https://drive.google.com/a/berkeley.edu/file/d/0B5q5EyRrPiIfR1BPeFlETndrLXc/edit?usp=sharing">[PDF]</a>
      </td>
      <td>
        <a href="https://github.com/biddata/datascience-fa14/tree/master/lab2">Lab 2</a>
      Pandas 
      </td>
      <td><a href="http://www.eecs.berkeley.edu/~franklin/Papers/dataspaceSR.pdf">From Databases to Dataspaces: A New Abstraction for Information Management</a>
        <br>
        <a href="http://hadapt.com/schemaless-sql-overview/">Schemaless SQL</a> and <a href="http://www.youtube.com/watch?v=cfEYEah1XMg">Schema on Write vs. Schema on Read</a>
      </td>
      <td>
        <a href="http://goo.gl/X6ASom">Bunny 2</a> by 5pm on 9/15
        <!-- | <a href="http://goo.gl/FdlCwM">Responses</a> -->
        <br/><a href="http://goo.gl/Pkku0e">Homework 1</a> out. Due by 10/2
      </td>
    </tr>
    <tr>
      <td>M 9/22</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>M 9/29</td>
      <td>L4: Data Cleaning
      <a href="https://drive.google.com/a/berkeley.edu/file/d/0B5q5EyRrPiIfR1RrSWwwbDNrVkk/edit?usp=sharing">[PPTX]</a>
      <a href="https://drive.google.com/a/berkeley.edu/file/d/0B5q5EyRrPiIfcENuLWE2UTlPMEk/edit?usp=sharing">[PDF]</a>
      </td>
      <td>
              <a href="https://github.com/biddata/datascience-fa14/tree/master/lab3">Lab 3</a>
      OpenRefine
      </td>
      <td>
      </td>
      <td>
        <!-- | <a href="http://goo.gl/fyzN4G">Responses</a> -->
      </td>
    </tr>
    <tr>
      <td>Th 10/2</td>
      <td></td>
      <td></td>
      <td></td>
      <td><a href="http://goo.gl/Pkku0e">Homework 1</a> Due! Submit using glookup</td>
    </tr>
        <tr>
      <td>M 10/6</td>
      <td>L5- Data Integration
       <a href="http://goo.gl/Ytri9e">[PPTX]</a>
       <a href="http://goo.gl/p6SGyA">[PDF]</a>
       </td>
       <td>
       <a href="http://nbviewer.ipython.org/github/biddata/datascience-fa14/blob/master/lab4/joins.ipynb">Lab 4</a>
       Pandas
       </td>
      <td><a href="http://yz.mit.edu/papers/webtables-vldb08.pdf">WebTables: Exploring the Power of Tables on the Web (Sections 1,2 and 4; others optional)</a>
        <br>
        and <a href="http://www.youtube.com/watch?v=5tsyz3ibYzk">OpenRefine Data Augmentation (video)</a>
      </td>
      <td>
      <a href="https://docs.google.com/a/berkeley.edu/forms/d/1iJNN8LVeqJl2fAZhdKuhbQWWWS31Sz18GlocQozOXSQ/viewform">Bunny 3</a> by 5pm;
      <!-- | <a href="http://goo.gl/ZgfzAN">Responses</a> -->
      <br> <a href="http://goo.gl/YFnAmH">Final Project Group Lists</a> Due Midnight 
      </td>
    </tr>
    <tr>
      <td>M 10/13</td>
      <td>L6: Exploratory Data Analysis 
       <a href="http://goo.gl/8w8Mkb">[PPTX]</a>
       <a href="http://goo.gl/rikI8i">[PDF]</a>
      </td>
      <td>
    <a href="http://nbviewer.ipython.org/github/biddata/datascience-fa14/blob/master/lab5/lab5.ipynb">Lab 5</a>
      Python 
      </td>
      <td><a href="http://proquest.safaribooksonline.com/9781449363871/_statistical_thinking_in_the_age_of_big_data_html">Statistical Thinking in the Age of Big Data</a>
      <br><a href="http://proquest.safaribooksonline.com/9781449363871/_exploratory_data_analysis_html">Exploratory Data Analysis</a><br>
      From the O'Reilly Book "Doing Data Science" - available on campus or via the library VPN.<br><br>
      <a href="http://www.sagepub.com/upm-data/40007_Chapter8.pdf">Introduction to Hypothesis Testing</a>
      </td>
      <td><a href="http://goo.gl/tiHqU2">Bunny 4</a> by 5pm;
      <!-- | <a href="http://goo.gl/ZDS8Rb">Responses</a> -->
      <br>Final Project Proposals due Thurs 10/16 Midnight.
      <br><a href="http://goo.gl/Jpneux">Homework 2</a> out. Due by 11/6</td>
    </tr>
    <tr>
      <td>M 10/20</td>
      <td>L7: Regression, Classification, intro to Supervised Learning<br>
        Part 1:<a href="http://goo.gl/WKx4jz">[PPTX]</a> <a href="http://goo.gl/8EFuWI">[PDF]</a>
        Part 2:<a href="http://goo.gl/GNnU8i">[PPTX]</a> <a href="http://goo.gl/CGgRY7">[PDF]</a><br>
        <a href="http://goo.gl/Hh6CwR">Homework Tips</a>
      </td>
      <td>
                <a href="https://github.com/biddata/datascience-fa14/tree/master/lab6">Lab 6</a>
      R
      </td>
      <td><a href="http://proquest.safaribooksonline.com/book/databases/9781449363871/3dot-algorithms/_three_basic_algorithms_html"> Three Basic Algorithms</a>
      From the O'Reilly Book "Doing Data Science" - available on campus or via the library VPN.<br>
      </td>
      <td><a href="http://goo.gl/y4IvKu">Bunny 5</a> by 5pm <br>
          <!-- | <a href="http://goo.gl/7kUpAb">Responses</a> --> 
      </td>
    </tr> 
    <tr>
      <td>M 10/27</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr> 
    <tr>
      <td>M 11/3</td>
      <td>L8: Data Products, Slides: <a href="http://goo.gl/NbQxvE">[PDF](29MB)</a>; followed by:
      <br>
        Part2 - <a href="http://goo.gl/e50eqQ">Unsupervised Learning and K-Means Clustering </a> (in Python)
      </td>
      <td>
                <a href="http://goo.gl/nzDvVk">Lab 7</a> Python
      </td>
      <td>K-Nearest Neighbors and K-Means clustering from <a href="http://proquest.safaribooksonline.com/book/databases/9781449363871/3dot-algorithms/_three_basic_algorithms_html"> Three Basic Algorithms</a>.
      Part of the O'Reilly Book "Doing Data Science" - available on campus or via the library VPN.<br>
      </td>
      <td>No Bunny ! <br> 
          <!--| <a href="http://goo.gl/PKUQio">Responses</a> -->
      </td>
    </tr> 
    <tr>
      <td>Th 11/6</td>
      <td></td>
      <td></td>
      <td></td>
      <td><a href="http://goo.gl/Jpneux">Homework 2</a> Due. Submit using glookup</td>
    </tr>
    <tr>
      <td>M 11/10</td>
      <td>L9: Scaling Up Analytics; <a href="http://goo.gl/l4Stce">[PDF]</a> <a href="http://goo.gl/M23eAE">[PPTX]</a></td>
      <td><a href="http://goo.gl/Y1Bom6"> Lab 8 </a>Spark/EC2</td>
      <td>"MapReduce," "Word Frequency Problem", and "Other Examples of MapReduce" sections from O'Reilly "Doing Data Science" book (available <a href="http://proquest.safaribooksonline.com/book/databases/9781449363871/14dot-data-engineering-mapreduce-pregel-and-hadoop/_mapreduce_html"> online</a> or from the library) and <a href="http://people.csail.mit.edu/matei/papers/2010/hotcloud_spark.pdf">Spark Short paper</a></td>
      <td><a href="http://goo.gl/Q4S856">Bunny 9</a> by 5pm <br> 
          <a href="http://goo.gl/gYtoVf">Homework 3, Part 1</a> Due 4/14</td>
    </tr> 
    <tr>
      <td>F 4/11</td>
      <td></td>
      <td></td>
      <td></td>
      <td>Final Project update due on glookup</td>
    </tr> 
    <tr>
      <td>M 11/17</td>
      <td>
          L10: Visualization (D3 lab)<a href="http://goo.gl/LWNBKw">[PPTX]</a> <a href="http://goo.gl/RKEsCP">[PDF]</a><br>
          
      </td>
      <td>           <a href="http://nbviewer.ipython.org/github/biddata/datascience-fa14/blob/master/lab9/lab9.ipynb">Lab 9</a> Visualization <a href="https://speakerdeck.com/alignedleft/learning-d3">Lab Slides</a>
      </td>
      <td>
        <a href="http://proquest.safaribooksonline.com/book/databases/9781449363871/9dot-data-visualization-and-fraud-detection/ch09_html">Chapter 9 on Data Visualization</a> from "Doing Data Science" available online or from the library.<br>
        <a href="http://vis.stanford.edu/files/2011-D3-InfoVis.pdf">D3: Data Driven Documents</a> by Bostock et. al.<br>
        Optional: <a href="http://goo.gl/Dx43fc">Reading about how the challenger disaster may have been prevented with data visualization</a> by Edward Tufte<br>
      </td>
      <td>
          <a href="http://goo.gl/FPYhKm">Bunny 10</a> by 5pm<br>
          <a href="http://goo.gl/gYtoVf">Homework 3, Part 1</a> due<br>
          <a href="http://nbviewer.ipython.org/github/biddata/datascience-fa14/blob/master/hw3/hw3-part2.ipynb">Homework 3, Part 2</a> out.  Due by 11/25.
      </td>
    </tr> 
    <tr>
      <td>TBD</td>
      <td></td>
      <td></td>
      <td></td>
      <td>Midterm - 5.00 to 6.30 pm</td>
    </tr> 
    <tr>
      <td>M 11/24</td>
      <td>L11: Graph Processing; 
      <a href="http://goo.gl/J1MeuJ">[PPTX]</a>(19MB) <a href="http://goo.gl/Xb87gO">[PDF]</a>(19MB)<br>
      </td>
      <td>
              <a href="http://goo.gl/MNC56V">Lab 10</a> <!-- | <a href="http://goo.gl/VzFGkH">Responses<a/> --> Graphx
      </td>
      <td><a href="https://www.cs.cornell.edu/home/kleinber/networks-book/networks-book-ch02.pdf">Chapter 2</a> from "Networks, Crowds, and Markets: Reasoning About a Highly Connected World"
      </td>
      <td>
        <a href="http://goo.gl/WnPMZG">Bunny 11</a> by 5pm
      </td>
    </tr>
    <tr>
      <td>Tu 11/25</td>
      <td></td>
      <td></td>
      <td></td>
      <td><a href="http://nbviewer.ipython.org/github/biddata/datascience-fa14/blob/master/hw3/hw3-part2.ipynb">Homework 3, Part 2</a> due</td>
    </tr> 
    <tr>
      <td>M 12/1</td>
      <td>L12: Putting it All Together</td>
      <td></td>
      <td></td>
      <td><a href="http://goo.gl/PoLg6p">Bunny 12</a> by 5pm</td>
    </tr> 
  </tbody>
  </tbody>
</table>
