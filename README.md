QA-Engineer-Test
================

I created this test to gauge the aptitude of potential QA Engineer applicants. The intent is to find out whether the applicant is more than just bright and creative and whether they have a knack for testing. I was looking for an innate curiousity about how things are built and what combinations of variables and configurations are interesting to test. I was looking for a strong sense of how things should work and the ability to articulate it. The question: Come up with a list of input strings you would want to test. 

1) An actual word like "banana"   
2) "A" vs "a" - case shouldn't matter   
3) A simple legal case with no results "!@#@!$#@!#@"    
4) null     
5) "AA" vs "aa" - a case where the count is greater than 1 and all characters entered are the target character     
6) "b" - a non-blank, legal case with a negative result      
7) "aba" - target character at the beginning and end to look for an off-by-one loop      
8) "bab" - target character in the middle of a string      
9) spaces/tabs/etc - how are white spaces taken into account      
10) ABABABABABABABABABABABABABABABABABABABAB - enter in a long string with A's (is anything being truncated?)      
11) XNXNXNXNXXNXNXNXNXNXNXNXNXNXNXNXNXNXNXNX - enter in a long string without any A's      
12) What happens if the user enters in an A in a foreign language?       
13) Is this field susceptible to a SQL injection?        
14) will entering in HTML or Javascript cause the page not to render correctly?      

Dave Boudreau      
dboudreau@gmail.com       
@xoxodave      



This work is licensed under a Creative Commons Attribution 3.0 Unported License.
