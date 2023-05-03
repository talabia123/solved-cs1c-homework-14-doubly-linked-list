Download Link: https://assignmentchef.com/product/solved-cs_1c-homework-14-doubly-linked-list
<br>
<ol>

 <li>Create a <em>doubly</em> <em>linked list</em> with at least five nodes using a class template with template methods

  <ol>

   <li>Print the linked list</li>

  </ol></li>

 <li>Add a copy constructor and overloaded assignment operator to the linked list

  <ol>

   <li>Test the copy constructor and the copy assignment</li>

  </ol></li>

</ol>

operator

<ol start="3">

 <li>Read the linked list from part 1 and create another linked list reversing the logical order of the first linked list

  <ol>

   <li>Print the linked list</li>

  </ol></li>

 <li>Delete the third node of each list. (Also try to (1) delete a non-existent node and (2) delete from an empty list)

  <ol>

   <li>Print both linked lists</li>

  </ol></li>

 <li>Add a node in the middle of each linked list

  <ol>

   <li>Print both linked lists</li>

  </ol></li>

 <li>Repeat steps 1-4 using doubles</li>

 <li>Run <em>valgrind</em> to test for memory leaks Sample printout (similar output for doubles):</li>

</ol>

Part 1:

Linked list 1:  88 78 62 143 60

Part 2:

Linked list 1 copy constructor:  88 78 62 143 60 Linked list 1 copy assignment:  88 78 62 143 60

Part 3:

Linked list 2:  60 143 62 78 88

Part 4 (after deleting the third node):

Linked list 1:  88 78 143 60

Linked list 2:  60 143 78 88

Part 5 (after adding a node in the middle of the list):

Linked list 1:  88 78 70 143 60

Linked list 2:  60 143 70 78 88

Part 6 – Repeat Part 1 thru 5 using doubles

Part 7 – Run valgrind memory leak check

Extra Credit [+10 pts]

Implement an <em>ordered singly (or doubly) linked list</em> class (suggested name <em>listOrdered</em>). This time linked nodes are stored internally in <em>ascending</em> order. Perform operations 1 thru 5 as outlined above using <em>listOrdered</em>.

Run <em>valgrind</em> to test for memory leaks.

Use the command script to capture your interaction compiling and running the program, including all operations, as shown below:

CS1C Fall 2018 TTH HW14 100pts <strong>Due: Tu 11/27/2018</strong>

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="1d7e6e2c7e5d7e6e2c7e304b746f69687c715f7265">[email protected]</a> ~/cs1c/hw/14 $ script hw14.scr Script started, file is hw14.scr <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="eb8898da88ab8898da88c6bd82999f9e8a87a98493">[email protected]</a> ~/cs1c/hw/14 $ date

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="ee8d9ddf8dae8d9ddf8dc3b8879c9a9b8f82ac8196">[email protected]</a> ~/cs1c/hw/14 $ ls -l

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="593a2a683a193a2a683a740f302b2d2c38351b3621">[email protected]</a> ~/cs1c/hw/14 $ make all

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="7a19094b193a19094b19572c13080e0f1b16381502">[email protected]</a> ~/cs1c/hw/14 $ ls -l

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="167565277556756527753b407f646263777a54796e">[email protected]</a> ~/cs1c/hw/14 $ ./hw14

… // print queue output after each addition, deletion operation above

… // print output from linked list steps 1 thru 5 above … // print output from valgrind memory leak check

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="fb9888ca98bb9888ca98d6ad92898f8e9a97b99483">[email protected]</a> ~/cs1c/hw/14 $ exit

Script done, file is hw14.scr

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="b8dbcb89dbf8dbcb89db95eed1cacccdd9d4fad7c0">[email protected]</a> ~/cs1c/hw/14 $ make tar