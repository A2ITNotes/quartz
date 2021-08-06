---
title: "Loops in Javascript"
---

![loop](/Images/javascript.png)
- Code is embedded within the body HTML code
- (global) variable (tableout) is declared
- The HTML table values are placed within the variable
- First/outer loop (on 4th line of JS code) executes 10 times«
- «to create 10 rows using global variable and HTML <tr> code each row
- Second/inner loop is executed each time outer loop executes
  - «to create 10 columns/cells
- First time inner loop executes, the cell contains 1*1=1...
  - «second time inner loop executes, the cell contains 1*2=2
  - «third time inner loop executes, the cell contains 1*3=3
  - «up to cell that contains 1*10=10
- When inner loop reaches 10, first row of cells is complete«
  - «next row is started with 2*1=2, 2*4 etc.
  - «up to 2*10=
- The process continues until outer loop reaches 10 and all 10 rows have been created and filled. 
	