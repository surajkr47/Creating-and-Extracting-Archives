# Creating-and-Extracting-Archives
This project focuses on the practical application of command-line tools for archiving and compressing files.  Participants will learn to create tarballs, compress them using gzip, and efficiently extract files from these  archives. This process is essential for effective data management, particularly in backup solution 
Steps to Perform 
Setting Up the Environment: 
Ensure tar and gzip are installed on your system (most Unix/Linux systems come with these tools pre
installed). 
 
II. Creating a Directory for Practice: 
o Create a new directory and add some sample files and subdirectories. 
mkdir my_archive 
touch my_archive/file1.txt my_archive/file2.txt 
mkdir my_archive/subdir 
touch my_archive/subdir/file3.txt 
 
III. Creating a Tarball: 
o Use the tar command to create an archive of the directory. 
tar -cvf my_archive.tar my_archive 
 
IV. Compressing the Tarball with gzip: 
o Compress the tarball using gzip. 
 
gzip my_archive.tar 
 
 
V. Extracting the Compressed Archive: 
o Extract the contents of the compressed tarball to a different location. 
mkdir extracted_files 
tar -xvzf my_archive.tar.gz -C extracted_files 
 
 
VI. Verifying the Extraction: 
o Check the extracted files and directories to ensure they match the original structure.
