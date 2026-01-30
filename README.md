You cannot create an empty folder and then add files to that folder, but rather the creation of a folder must happen together with the addition of at least a single file. This is because git doesn't track empty folders.

On GitHub, you can do it this way:

    Go to the folder inside which you want to create another folder
    Click on New file
    On the text field for the file name, first write the folder name you want to create
    Then type /. This creates a folder
    You can add more folders similarly
    Finally, give the new file a name (for example, .gitkeep which is conventionally used to make Git track otherwise empty folders; it is not a Git feature though)
    Finally, click Commit new file.

