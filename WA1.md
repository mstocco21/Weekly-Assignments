[mstocco@guardian.it.edu ~]$ more WA1.fasta | grep GGILKKK | cat > file  
# Command 1: more "---" = outputs the contents of the specified file 
# Command 2: grep "---" = displays every instance of the input "GGILKKK"
# Command 3: cat > "---" = places every instance of the aforementioned desired content into the marked "---"
# Desired purpose: The above pipe command will open the WA1 file and look through the contents for multiple instances of the 
# "GGILKKK" globin code. Once found, it will enter them into whatever file is marked at the end of the "cat >" command.
