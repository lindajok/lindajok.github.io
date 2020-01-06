---
layout: default
---
## Course overview  
An introduction course to command-line tools aimed for linguists. Among other things the course included the understanding of Unix systems, corpora processing, installing programs and creating GitHub pages.

### 1. Introduction 
Getting familiar with command-line environment with basic commands and creating files
 * creating, renaming, copying and moving files    
 * viewing text files  
 * basic operations on _emacs_   

### 2. Getting to Understand UNIX System  
Navigating in Unix system and learning more basic commands, in addition working in remote services
 * creating, renaming, copying and moving directories  
 * display information about commands/programs    
 * compressing files  
 * running processes from programs and running them in the background   
 * creating links  
 * changing file modes or access control lists with `chmod`  
 * Working in remote services (SHH)  

### 3. Basic Corpus Processing  
Learning about different character encondings and how to convert between them. Using this information to analyze files from a linguistic point of view. Also learning about different structured text files
 * sort lines into alphabetical order
 * ignore case
 * controlling streams with redirect and pipe
 * `iconv`, `dos2unix`
 * transform characters into other characters with `tr`
 * standard input, output and error

### 4. More in Depth Corpus Processing
Using stream editor to edit files without opening them, making frequency lists and understanding N-grams
 * `sed`
  * substitution, deletion, finding patterns, replication 
 * text files to one-word-per-line format and finally arranging them into numerical order
 * searching differencies within files with `diff` 
 * _regex_ 

### 5. Creating Scripts and Configuration files
Making scripts with commands and understanding that commands are programs too. Learning about shell and environmental variables
 * set, change and view new variables
 * setting environmental variables permanently in configuration files 

### 6. Installing and running programs
Software installation with package managers and using `make` 
 * switching between users, running commands as root from your other users
 * learning that _libraries_ are a collection of pre-written software
 * learning that _dependencies_ are specific code needed for specific programs
 * using ``pip`, a standard package manager for python, to allow the installation and management of libraries and dependencies

### 7. Version Control and building webpages with GitHub
Undersanding why it is useful to have multiple versions of your work and also beeing able to go back to previous versions. Tracking changes and being aware what has been commited
 * adding and commiting changes
 * traking these changes
 * creating new braches and stwitching between them 
 * using _markdown_ files, which can for example have tables to portray collected data:
&nbsp; &nbsp; &nbsp;|Word  |Frequency  
&nbsp; &nbsp; &nbsp;| ---  | --- 
&nbsp; &nbsp; &nbsp;| the  | 5009     
&nbsp; &nbsp; &nbsp;| of   | 2701     
&nbsp; &nbsp; &nbsp;| and  | 2041        
&nbsp; &nbsp; &nbsp;| to   | 1733     	
&nbsp; &nbsp; &nbsp;| that | 1182     
&nbsp; &nbsp; &nbsp;| in   | 1161     
