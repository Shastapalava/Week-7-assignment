# Week-7-assignment
Time spent: 7.5 hours spent in total


1.
Vulnerability type: XSS 
Tested in version: 4.2
Fixed in vertion: 4.2.3

This vulnerability allows users with special privileges(ex: author,aditor) to run XSS on a WordPress. The action can be done by incorporating cross site scripting inside a post. (In this example the script is: "<a href="[caption code=">]</a><a title=" onmouseover=alert('XSS') ">link</a>"). If user with higher privileges(ex: admin) viewed the page the XSS would be executed.

<a href="https://imgflip.com/gif/281ud5"><img src="https://i.imgflip.com/281ud5.gif" title="made at imgflip.com"/></a>

2.
Vulnerability type: User Enumeration 
Tested in version: 4.2
Fixed in vertion: 4.7.5

This vulnerability allows to find out user names list. As a result this can be used in a brute forth atack in order to gain or modify private data.

<a href="https://imgflip.com/gif/281vw2"><img src="https://i.imgflip.com/281vw2.gif" title="made at imgflip.com"/></a>

