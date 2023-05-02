Download Link: https://assignmentchef.com/product/solved-comp202-data-structures-and-algorithms-assignment-6
<br>
<h1> This programming assignment will test your knowledge and your implementation abilities of what you have learned in the Graph parts of the class.</h1>

This homework must be completed individually. Discussion about algorithms and data structures are allowed but group work is not. <strong>Coming up with the same algorithm and talking about the ways of implementation leads to very similar code which is treated as plagiarism! </strong>If you are unsure, you should not discuss. Any academic dishonesty, which includes taking someone else’s code or having another person doing the assignment for you will not be tolerated. <strong>By submitting your assignment, you agree to abide by the Ko¸c University codes of conduct.</strong>

<h2>Description</h2>

This assignment requires you to implement:

<ul>

 <li>A given graph ADT</li>

 <li>Graph search algorithms</li>

 <li>Graph traversal on an implicit graph (an image)</li>

</ul>

The files provided to you have comments that will help you with implementation. In addition, keep the slides handy as they include the pseudo-codes for the algorithms. The file descriptions are below. Bold ones are the ones you need to modify and they are placed under the <em>code </em>folder, with the rest under <em>given</em>. The homework consists of three parts:

<h3>Graph Implementation</h3>

This part of the homework requires you to implement a given graph ADT for four different types of graphs. There is no explicit Edge class or an explicit Vertex class. This is done to give you total freedom. If you need extra classes such as these, feel free to put them as nested classes but do not provide extra files.

<ul>

 <li><em>java</em>: The interface that defines the graph ADT. Make sure you pay attention to all the comments!</li>

 <li><em>java</em>: The abstract base class for the graphs that you should implement. You can put the common functions here or ignore this file all together.</li>

 <li><em>java</em>: Implement an undirected-unweighted graph in this file.</li>

 <li><em>java</em>: Implement a directed-unweighted graph in this file.</li>

 <li><em>java</em>: Implement an undirected-weighted graph in this file.</li>

 <li><em>java</em>: Implement an directed-weighted graph in this file.</li>

 <li><em>java</em>: The file that includes the autograder implementation for this part. Can be run by itself.</li>

</ul>

<h3>Graph Algorithms</h3>

This part of the homework requires you to implement depth first search (DFS), breadth first search (BFS), Dijkstra’s single-source all-destinations shortest path (or actually smallest cost) algorithm and cycle finding algorithms (for both directed and undirected graphs).

<ul>

 <li><em>java</em>: Implement the algorithms. You can (and probably should) add more methods and fields.</li>

 <li><em>java</em>: The file that includes the autograder implementation this part. Can be run by itself.</li>

</ul>

<h3>Implicit Graphs: Image Segmentation</h3>

This part of the homework requires you to work on an implicit graph formed by the pixels of an image. Think of a gray-scale image as a 2D array of numbers, e.g., as in Fig. 1. These individual numbers are called pixels. Pixels are indexed by their rows and columns. Pixel values are between a range. In this homework, the pixel values are double-precision floating point numbers between 0.0 and 1.0.

Figure 1: A grayscale image is very similar to a 2D array.

The task is to segment a given image by applying graph algorithms. The goal of image segmentation is to cluster pixels into image regions. In our segmentation approach, we want to group together pixels that have similar values. We can pose this as a problem of finding connected components in a graph where each pixel is a vertex and pixel value similarity decides whether there is an edge between neighboring vertices. Each pixel has 4 possible neighbors as shown in Fig.2:

Figure 2: The pixel in the middle(red color) has 4 possible neighbors labeled 0, 1, 2, 3.

Look at the images under the <em>images/input </em>and <em>images/reference </em>folders to get an idea.

<ul>

 <li><em>java</em>: The file where you need to implement the segmentation approach. There is a dummyIteration method to help you get around the image.</li>

 <li><em>java</em>: This files defines a wrapper for an image class. You need to go over it to be able to handle this part of the assignment.</li>

 <li><em>java</em>: This file includes the autograder for the image segmentation part. Can be run by itself.</li>

</ul>