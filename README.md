# Devopstest

Scripts and configuration for Devops class
:)What does this line in shell scripts means?: #!/bin/bash
#!/bin/bash is She-bang
/bin/bash is the most common shell used as default shell for user login of the linux system. The shell’s name is an acronym for Bourne-again shell. Bash can execute the vast majority of scripts and thus is widely used because it has more features, is well developed and better syntax.

# Shell scripting command to extract column data from text file

 ● Awk : Awk is a scripting language used for manipulating data and generating reports.  Awk is mostly used for pattern scanning and processing. 
   Command : $ awk '{print $1,$4}' bankemployee.txt
    This command extract data from column 1 and column 4 and disply it.
![Capture](https://github.com/chintan2812/Devopstest/assets/142546141/a056f3b0-a6bf-4905-8bfe-28561c53d0d1)

    
 ● grep : The grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern.
    Command : grep -E "manager" filename.txt>newfile.txt
   This command extract all name with manager designation and create new file(newfile.txt)
   -E : Treats pattern as an extended regular expression (ERE)
![Capture2](https://github.com/chintan2812/Devopstest/assets/142546141/2605909a-d3f5-46ba-8b73-ebd63f8ecc7c)

   
