I have tried to build a tree-structure of the spice files, following the '.include' statements from the top level file. 
For simplicity, 'cells' directory is moved under the 'models' directory. 
And all the files in 'cells' directory are  shown in a single 'cells' diretory. 

- tree_for_sky130_fd_pr_tt_1103.txt
   
   is when only 'tt' corner is used for fet devices. 
   
- tree_for_sky130_fd_pr_1103.txt
   
   is when all the corners are included. 
   
   
 The motivation for doing this is that there are so many files. And it is very hard to understand the include hierarchy. 
A text representation seems better than a graph representation, since there are so many files and the filenames are not short. 
The 'Dot' files can be used to generate graphs with graphviz tool. Until now, the graphs are not satisfactory for me.


