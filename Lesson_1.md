# Introduction
### Matching specific string
### Matching anything but a newline
 Dot(.) matches anything except the newline.
> **Problem**: Regex that matches strings exactly of the form _abc.def.ghi.jkx_

*Solution* :
         ``` "^.{3}\\.((.{3}\\.){2}).{3}$" ```
          **OR**
         ```  "^(.{3}\\.){3}.{3}$" ```
### Matching digits & non digit character
### Matching Whitespace & Non-Whitespace Character
### Matching Word & Non-Word Character
### Matching Start & End

Credits: Hackerrank problems
https://www.hackerrank.com/domains/regex