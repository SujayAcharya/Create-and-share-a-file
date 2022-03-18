# Create-and-share-a-file
1. Create a text file

==> vi newfile

2. Ensure any user can read and write it

==> chmod a+rw newfile
    stat newfile
    
3. Compress the file using tar or zip

==> tar -czf newfile.tgz newfile

    ls -lh newfile.tgz
