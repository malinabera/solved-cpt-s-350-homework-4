Download Link: https://assignmentchef.com/product/solved-cpt-s-350-homework-4
<br>






<ol>

 <li>(very hard) Let A be a set of n points in the two-dimension plane. We would like to find the distance of a closest pair in A, using the following badffoéestpair algorithm. We first randomly split A into two subsets Al and .42, in linear time. Then, we run badClosestpair on Al and on 142. As a result, we obtain the distance (51 of a closest pair in Al and the distance (52 of a closest pair in .42. Finally, for each point in Al and each point in A2, we calculate the distance between the two points and pick the smallest ö among all these distances. The result of badClosestpair running over A returns as min(öl, (52, ö). Compute the average-case complexity of badClosestpair.</li>

 <li>We know that, using Karatsuba algorithm, it takes worst time complexity to multiply two bit strings with length n. Suppose that I want to multiply n bit strings al, • • • , a n, each of which is with length n. I do this by the following naiveKaratsuba algorithm: al ;</li>

</ol>

For i 2 to n

<ul>

 <li>ai (using Karatsuba); return p.</li>

</ul>

Compute the worst-case complexity of naiveKaratsuba.

<ol start="3">

 <li>(Be very careful — this problem involve a lot of math) We know that, using Karatsuba algorithm, it takes worst time complexity to multiply two bit strings with length n. Suppose that I want to multiply n bit strings an, each of which is with length n. I do this by the following betterKaratsuba algorithm. I first divide the n bit strings into two groups, each of which has roughly bit strings. Then run betterKaratsuba on each group (when the group has only one bit string, betterKaratsuba simply returns the bit string). Then, we use Karatsuba on the results of betterKaratsuba for the two groups. Compute the worst-case complexity of betterKaratsuba.</li>

 <li>At some moment, there are n<sup>3 </sup>airplanes in the air and we know the x-, y-, and z- coordinates for each airplane. It is also known that all the airplanes are contained in a cube of size n and the distance between any two airplanes is at least 1. Design an algorithm that runs in time O(n<sup>3 </sup>) and finds the closest pair of airplanes (the pair has the shortest distance between all the n<sup>3 </sup> Notice that it is essentially a linear time algorithm since the input’ size is n3).</li>

</ol>

<table width="756">

 <tbody>

  <tr>

   <td width="202">5. Let E</td>

   <td width="353">{a, b}. For a string a over the alphabet E, we use</td>

   <td width="201">(resp.</td>

  </tr>

 </tbody>

</table>

to denote the number of a’s (resp. b’s) in a. Given a pair of two strings a,ß, we use d(a, D) to denote the difference of the pair, which is defined as

Now, we are given an array A of n strings over E; the length of each string in A is bounded by m. A distinct pair in A is defined by (A[i], A[j]) with i j. Design an algorithm that runs in time O(nrn) and that finds the smallest difference of all the distinct pairs in A.

2