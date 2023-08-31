# Shell Permissions Project

This project is a collection of shell scripts that demonstrate various tasks related to Linux file permissions, ownership, and basic shell scripting. The tasks involve manipulating permissions, changing ownership, and performing other actions on files and directories.

## Project Structure

The project is organized into different scripts, each addressing a specific task. Each script is designed to be concise and meet the specified requirements. Here's an overview of the tasks and their corresponding scripts:

1. **0-iam_betty**: Switches the current user to the user "betty."
2. **1-who_am_i**: Prints the effective username of the current user.
3. **2-groups**: Prints all the groups the current user is a part of.
4. **3-new_owner**: Changes the owner of the file "hello" to the user "betty."
5. **4-empty**: Creates an empty file called "hello."
6. **5-execute**: Adds execute permission to the owner of the file "hello."
7. **6-multiple_permissions**: Adds execute permission to the owner and the group owner, and read permission to other users, to the file "hello."
8. **7-everybody**: Adds execution permission to the owner, the group owner, and other users, to the file "hello."
9. **8-James_Bond**: Sets specific permissions for the file "hello."
10. **9-John_Doe**: Sets the mode of the file "hello" to a specific mode.
11. **10-mirror_permissions**: Sets the mode of the file "hello" the same as the mode of another file "olleh."
12. **11-directories_permissions**: Adds execute permission to all subdirectories for owner, group owner, and other users.
13. **12-directory_permissions**: Creates a directory "my_dir" with specific permissions.
14. **13-change_group**: Changes the group owner of the file "hello."
15. **100-change_owner_and_group**: Changes the owner and group owner of all files and directories.
16. **101-symbolic_link_permissions**: Changes the owner and group owner of a symbolic link file.
17. **102-if_only**: Changes the owner of the file "hello" to "betty" only if it is owned by a specific user "guillaume."

## Usage

To run any of the scripts, follow these steps:

1. Make the script executable: `chmod +x script_name`
2. Execute the script: `./script_name`




