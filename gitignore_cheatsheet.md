# this is a gitignore cheatsheet
| Pattern | Explanation/Matches | Examples |
| -------- | -------- | -------- |
| name.file | All names with name.file will be ignored | /name.file /lib/name.file |
| *.txt |ignores all files that end with .txt extension or the specified extension| samp.txt, file1.txt, file2.txt, example.txt will all be ignored |
| ! | includes a file or a directory that would otherwise be ignored | if file1.txt was in modules and modules folder is in gitignore but we don't want to ignore that file, we will do !modules/file1.txt This will ignore all the everything in modules except file1.txt |
| Lines starting with a # symbol | These lines are comments and will be ignored by git | # this is a gitignore file |
| name.html | All files with name.html will be ignored | /name.html |
| .log | All files with the .log will be ignored | /id.log |