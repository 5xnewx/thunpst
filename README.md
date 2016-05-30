# thunpst
Convert readpst multidirectory output into Thunderbird local folders structure.

Instructions for a sample "file.pst" :

Close Thunderbird
Run "readpst -r file.pst" to convert pst files to a directory structure in a directory called as the pst: "file"
Make thunpst.sh executable with "chmod +ux thunpst.sh"
Run "./thunpst.sh file"
Copy all the contents in "file" directory to the "Mail/Local Folders" directory in the user profile directory.
