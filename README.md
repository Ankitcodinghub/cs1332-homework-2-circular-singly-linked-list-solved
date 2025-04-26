# cs1332-homework-2-circular-singly-linked-list-solved
**TO GET THIS SOLUTION VISIT:** [CS1332 Homework 2-Circular Singly-Linked List Solved](https://www.ankitcodinghub.com/product/cs1332-homework-2-circular-singly-linked-list-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;58000&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1332 Homework 2-Circular Singly-Linked List Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
You are to code a circular singly-linked list with a head reference. A linked list is a collection of nodes, each having a data item and a reference pointing to the next node. Since it must be circular, the next reference for the last node in this list will point to the head node. As a special case, this means that in a one node list, the head node will point to itself.

Do <strong>not </strong>use a phantom node to represent the start or end of your list. A phantom or sentinel node is a node that does not store data held by the list and is used solely to indicate the start or end of a linked list. If your list contains <em>n </em>elements, then it should contain exactly <em>n </em>nodes.

It will use the default constructor (the one with no parameter) which is automatically provided by Java. Since instance variables are automatically assigned default values, it is not necessary to explicitly set them, so do not write your own constructor.

As an additional note, your circular implementation doesn’t have a tail reference, but it is still possible to efficiently add and remove from the head as well as add to the back in <em>O</em>(1) time. However, it is still not possible to remove from the back in <em>O</em>(1) time unless the linked list is doubly-linked.

<h2>Nodes</h2>
The linked list consists of nodes. A class LinkedListNode is provided to you. LinkedListNode has setter and getter methods to access and mutate the structure of the nodes.

<h2>Adding</h2>
You will implement three add() methods. One will add to the front, one will add to the back, and one will add to anywhere in the list. See the javadocs for more details.

<h2>Removing</h2>
Removing, just like adding, can be done from the front, the back, or anywhere in your linked list. In addition, you will also be coding a method to remove the last instance of a piece of data. When removing from the front, the first node should be removed in such a way that the last node points to the new front of the list (mind the efficiency!). When removing from the back, the last node should be removed and have the new last node point to the head. When removing from the middle, the node before the removed node should point to the next node of the removed node. See the javadocs for more details.

<h2>Garbage Collection</h2>
Java will automatically mark objects for Garbage Collection based on whether there is any means of accessing the object. In other words, if we want to remove a node from the list, we must remove all references <strong>to that node</strong>. What the next reference of that node points to doesn’t particularly matter since the node will be Garbage Collected eventually.

<h2>Differences between Java API and This Assignment</h2>
Some of the methods in this assignment are called different things or don’t exist in Java’s LinkedList class. Additionally, Java’s built in LinkedList is a Doubly-Linked List, so the efficiency of some operations will differ. This won’t matter until you tackle coding questions on the first exam, but it’s something to be aware of. The list below shows all methods with a different name and their Java API equivalent if it exists. The format is assignment method name ⇒ Java API name.

<ul>
<li>addAtIndex(int index, T data)⇒add(int index, T data)</li>
<li>addToFront(T data)⇒addFirst(T data)</li>
<li>addToBack(T data)⇒add(T data) or addLast(T data)</li>
<li>removeAtIndex(int index)⇒remove(int index)</li>
<li>removeFromFront()⇒poll() or pollFirst()</li>
<li>removeFromBack()⇒pollLast()</li>
<li>T removeLastOccurrence(T data)⇒boolean removeLastOccurrence(Object data)</li>
</ul>
