---
title: "Sample code 3 "
---
![[Pasted image 210506112946.png]]

form action="mailto: aftersales@mycompany.com"
Tells the page that this is a form to be actioned by sending / submitting the
form to a specified URL / default URL is this page
To send an email via mailto to the specified address

method="post"
Specifies the HTTP method to be used when submitting the form
In this case post means not to display the submitted data / used for sensitive
or private / personal data / make the submitted data invisible in the field / will
not allow bookmarking / is not saved in browser history
Post can send unlimited amounts of data so no need to specify the size


enctype="text/plain"
Specifies the encoding of the data
As plain text