TASK 1
1.  What do i see:
    The ls command shows the files that are in the current folder.
    
    what is it used for:
    It is used to display the current files and information about the files in the current directory.
    
2.  What do I See :
    /home/recruit
    The pwd command display the full path of the current directory im working on or im in.
       
    What is it used for:
	  The pwd command is used to display the current full path of the directory you are currently
	  in or working in.
    
3.  Commands used to make the directory workspace and cd from the ~/ (Home directory):
    ~$ ls
    ~$ mkdir workspace
    ~$ ls
    ~$ cd workspace
    ~$ ls
    
4.  What do i see:
    The new created directory is empty since no files are created in the new directory.
    
5.  command to create README.md
    ~$ touch README.md
    
6.  Command to copy the README.md file and give it a new name.
    ~$ cp README.md CHNAGELOG.md
    
    
Task 2
1.  creating exercise.md file and moving to /tmp folder using relative pathname
    ~$ touch exercise.md
    ~$ mv exercise.md ../../tmp
    
2.  delete exercise.md file using an absolute pathname    
    ~$ rm /tmp/exercise.md
    
    
Task 3
1.  creating the 3 files, to exit writing/editing is ctrl+D.
    ~$ cat > umuzi.md
    ~$ cat > recruits.md
    ~$ cat > cohort.md
    
2.  Concatenation : 
    ~$ cat > umuzi.md recruits.md cohort.md
    
3.  Creation of Summary.md with all requirements
    ~$ cat umuzi.md recruits.md cohort.md ->> summary.md
       The End
    
    viewing the summary file
    ~$ cat summary.md
    
Task 4
1. Find a file named umuzi
    ~$ locate -b umuzi
2. Save results on search_result.md
    ~$ locate -b umuzi >> search_result.md
    ~$ ~ls
    
    view the search_result.md
    ~$ cat search_result.md
    
Task 5
1.  ~$ touch ~/Documents/pad.md
2.  ~$ cd ~/Desktop
    ~/Desktop$ mkdir work
3.  ~/Desktop$ cp ~/Documents/pad.md pad_copy.md
4.  ~/Desktop$ sudo updatedb
5.  ~/Desktop$ cd -
6.  ~$ locate -b pad_copy.md    

Task 6
1.  ~$ find ~/ -name *.pdf
2.  ~$ find ~/ -name *.pdf >> ~/Desktop/find_results.md
3.  ~$ find ~/ -mtime -1 -ls


Task 7
1.  ~$ nano my_bio.md
2.  To Save = CTRL+O
    To Exit = CTRL+X   
3.  ~$ mkdir my_files
    ~$ mv my_bio my_files 
