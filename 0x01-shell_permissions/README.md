File 0-iam_betty switches the current user to the user betty.

File 1-who_am_i prints the effective username of the current user.

File 2-groups prints all the groups the currennt user is a part of.

File 3-new_owner changes the owner of the file hello to the user betty.

File 4-empty creates an empty file called hello.

File 5-execute adds execute permission to the owner of the file hello.

File 6-multiple_permissions adds execute permission to the owner and group owner, and read permission to other users, to the file hello.

File 7-everybody adds execution permission to the user owner, group owner and other users of the file hello.

File 8-James_Bond sets the permission to the file hello as follows; Owner: no permission at all, Group: no permission at all, Other users: all the permissions.

File 9-John_Doe sets the mode of the file hello to 753.

File 10-mirror_permissions sets the mode of the file hello the same as olleh’s mode, the mode of olleh will not always be 664. Make sure your script works for any mode.

File 11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

File 12-directory_permissions creates a directory called my_dir with permissions 751 in the working directory.

File 13-change_group changes the group owner to school for the file hello.

File 100-change_owner_and_group changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

File 101-symbolic_link_permissions changes the owner and the group owner of _hello to vincent and staff respectively. The file _hello is a symbolic link.

File 102-if_only changes the owner of the file hello to betty only if it is owned by the user guillaume.

File 103-Star_Wars will play the StarWars IV episode in the terminal.

File gitauto is a script that automatically pushes all the files after a commit message is supplied.

File hashvi is a script that automatically creates, adds the shebang into and opens the file that has been supplied.
