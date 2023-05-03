Download Link: https://assignmentchef.com/product/solved-cs352-assignment-project-3-network-programming-in-python
<br>
<h1>Objective</h1>

The objective of this project is to become familiar with Network programming.  This will be done using the following assessments:

<ul>

 <li>Explore Python programming for networking</li>

 <li>Learn to write a simple server-client program</li>

</ul>

<h1>Software Installation</h1>

Make sure to clear your web browser’s cache. We recommend running everything from the virtual machine. However, you are free to use your personal computer if it is easier for this project.

<h1>Submission Instructions</h1>

<table>

 <tbody>

  <tr>

   <td width="143"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

Please work through each of the tasks discussed below. Each task will specify the material you are required to hand in. You will need to cut several snapshots and put them into a document and convert that document (if possible) to a PDF file. For submission please submit the PDF file (with your NetID as its name) via Sakai.

For presenting your answers

<ul>

 <li>You will submit <strong>TWO </strong>items in this project

  <ol>

   <li>Submit <strong>one PDF </strong>document with a summary of all your answers including the images that you have captured.

    <ol>

     <li>This should be at the top level of your submission</li>

     <li>Exclusion of this PDF Summary will result in a reduction in your grade.</li>

    </ol></li>

  </ol></li>

</ul>

<ul>

 <li>Convert word or google docs to a PDF file</li>

</ul>

<strong>AND</strong>

<ol>

 <li>Submit a zipped file with your code and any additional files.</li>

</ol>

<ul>

 <li>Be sure to include your name and NetID in your submission</li>

 <li>Label or number the answer for each question. For example, the answer for 3a should be labeled <strong>3a </strong>or <strong>Question 3 Part a.</strong></li>

 <li>Be sure to answer all questions</li>

 <li>Provide citations for any references used</li>

 <li><strong>Due date: </strong>August, 15th @ 11:55 PM</li>

</ul>

<h1>Assignment Details</h1>

<strong>Note: </strong>Please refer to the slides entitled “network programming” for Python and Server-Client Basics.

<h2>UDP Programming</h2>

Please download and view the UDP server and Client, hence the zipped file entitled “server_client”. These files were included in Sakai with the project description.  However, the files can also be downloaded here:

<a href="https://drive.google.com/file/d/1R_-XJ0v8Y6DPXWXn5Lebdw7_AgV59DwZ/view?usp=sharing">https://drive.google.com/file/d/1R_-XJ0v8Y6DPXWXn5Lebdw7_AgV59DwZ/view?usp=sharing </a>1) Run the UDP server-client code and screenshot your results.

<strong>Note: </strong>The server must be started before the client. For more details please refer to the recitation.

<h2>TCP Programming</h2>

In this section, you will write a TCP service program that provides connection-oriented services which are essential for reliable transport.

<ul>

 <li><u>The Binary Encoding Server: </u>Write a server program for TCP using Python to write client code. The server should return the binary value of the text sent by the client. Print this binary value to the screen.</li>

</ul>

<u>Example: </u>for a text string “CS352-2021”, the client should receive “01000011 01010011 00110011 00110101 00110010 00101101 00110010 00110000 00110010 00110001”

<strong>Note: </strong>The server should be running at the localhost interface. You are free to choose any port. Include a screenshot of the results.

<ol>

 <li>Run the server and client program from the following text string: “CS352-2021”. Screenshot the results. <strong>Note: </strong>The binary value should be displayed or printed to the screen.</li>

 <li>Run the server and client program from the following text string: “mynetwork”. Screenshot the results. <strong>Note: </strong>The binary value should be displayed or printed to the screen.</li>

 <li>Write down the port and host address that you used.</li>

 <li>Save your server python code as <em>py</em>. Include this file in the zip file of your assignment submission on Sakai.</li>

 <li>Save your client python code as <em>py</em>. Include this file in the zip file of your assignment submission on Sakai.</li>

</ol>

<ul>

 <li><u>The Binary Decoding Server: </u>Write another server running on an <strong>ethernet </strong>interface to do the following:</li>

</ul>

<em><u>Example</u></em><u>: </u>the binary string “01000011 01010011 00110011 00110101 00110010 00101101

00110010 00110000 00110010 00110001” sent from the client should return “CS352-2021”.

<ol start="1110010">

 <li>Run the server program from the following binary value: 01010000 01111001 01110100 01101000 01101111 01101110 00100000 01110011 01100101 01110010 01110110 01100101 01110010. Screenshot the results.</li>

</ol>

<strong>Note: </strong>The string value should be displayed or printed to the screen. Include a screenshot of your results.

<ol>

 <li>Run the program from the following binary string: “01101000 01101100 01101111”. Screenshot the results. <strong>Note: </strong>The string value should be displayed or printed to the screen. Include a screenshot of your results.</li>

 <li>Write down the port and host address that you used.</li>

 <li>Save your server python code as <em>py</em>. Include this file in the zip file of your assignment submission on Sakai.</li>

 <li>Save your client python code as <em>py</em>. Include this file in the zip file of your assignment submission on Sakai.</li>

</ol>

<h1>Sources</h1>

This assignment was created and modified with permission from the sources below:

<ul>

 <li>Network Programming in Python <a href="http://www.winlab.rutgers.edu/comnet2/Projects/documents/network_programming.pdf">http://www.winlab.rutgers.edu/comnet2/Projects/documents/network_programming.p </a><a href="http://www.winlab.rutgers.edu/comnet2/Projects/documents/network_programming.pdf">df</a></li>

 <li>Communication Networks II: Assignment 2: Network Programming in Python <a href="http://www.winlab.rutgers.edu/comnet2/Projects/documents/assignment2_comnets2_2020.pdf">http://www.winlab.rutgers.edu/comnet2/Projects/documents/assignment2_comnets2_ </a><a href="http://www.winlab.rutgers.edu/comnet2/Projects/documents/assignment2_comnets2_2020.pdf">pdf</a></li>

</ul>