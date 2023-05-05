Download Link: https://assignmentchef.com/product/solved-cse330-homework-assignment-4
<br>
This assignment will have you add the standard set operations, union, intersection, and set difference to class Set. Also add a member function  max_depth which is to return the length of the deepest node in a given Set&lt;T&gt; data structure objects. Consider the root to be located at depth 0.




Add the following to the public interface of class Set (5 points each) in your Set.h header file.




Set&lt;T&gt; set_union(Set&lt;T&gt; otherset) { …}

Set&lt;T&gt; set_intersection(Set&lt;T&gt; otherset) { …}

Set&lt;T&gt; set_difference(Set&lt;T&gt; otherset} {…}




int max_depth(){…}




Also write your own int main() function (e.g., in a file SetHw4.cpp) that will test your functions in the following manner:  (10 pts)




<ul>

 <li>Two Set&lt;int&gt; objects setA and setB are declared.</li>

 <li>Set setA is filled with integer values from a vector (traversed left to right) which contains a random permutation of multiples of 3 between 3 and 36.</li>

 <li>Set setB is filled with integer values from a vector which contains a random permutation of multiples of 3 between 18 and 54.</li>

 <li>With the use of a Set&lt;int&gt;::iterator the contents of sets setA and setB is printed out.</li>

 <li>After printing each set, the depth that is determined by max_depth() for each set is reported.</li>

 <li>The set_union function is tested by computing the union of setA and setB, followed by the set_interaction of setA and setB. The contents of both resulting sets is printed out.</li>

 <li>Then two difference sets are computed: the result of subtracting setB from setA, and the result of subtracting setA from setB. The contents of both difference sets is printed out.</li>

</ul>




For the vectors of integers from which the sets are to be filled, you may use the Standard Template Library &lt;vector&gt;; <strong>2 bonus points if you use our home-baked Vector.h for this assignments </strong>(to obtain the bonus, your code must be a program the compiles and runs.)







<strong>Submit on Monday, March 9, 2020, via electronic portal : </strong>(1) A copy of your file Set.h with the three set operations implemented,  a copy of your file SetHw4.cpp, (3) A  typescript or screen

shot which demonstrate the compiling and running of your program