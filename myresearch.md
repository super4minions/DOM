#super4minions 


##The Question Number 3 

---

###What is a node in the DOM? What different types of node are there?

***
According to the W3C HTML DOM standard, everything in an HTML document is a node



1. The entire document is a document node 
2. Every HTML element is an element node 
3. The text inside HTML elements are text nodes 
4. Every HTML attribute is an attribute node 
5. All comments are comment nodes 


***


![alt text](http://www.w3schools.com/js/pic_htmltree.gif "Html Tree")


##Node Types

> Documents, elements, attributes, and other aspects of an HTML or XML document has different node types.

> There are 12 different node types, which may have children of various node types:
-----------------------------------------------------------------------------
|Node type 					| nodeName returns 		  | nodeValue returns 	|
|---------------------------|:-----------------------:|--------------------:|
|1 	| Element 				| 	element name 		  |	null 				|
|2 	| Attr 	  			 	|attribute name 		  |	attribute value 	|
|3 	| Text 	  				| #text 	content 	  |	of node 			|
|4 	| CDATASection 			| 	#cdata-section 		  | content of node 	|
|5 	| EntityReference 		|	entity reference name |	null 				|
|6 	| Entity 				|entity name 	      	  | null 	  			|
|7 	| ProcessingInstruction |	target                | content of node 	|
|8 	| Comment 	            | #comment                |	comment text 		|
|9 	| Document 				| #document 			  |	null 				|
|10 |	DocumentType 		|	doctype name          |	null 				|
|11 | 	DocumentFragment 	| 	#document fragment    | null 				|
|12 |	Notation 			|notation name 			  | null 				|