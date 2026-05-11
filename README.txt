ICS32 Assignment 2: Journal

This assignment includes the following starter files:

a2.py : Use this file as the main module for your program.
input_processor.py : Use this file for your user interface module.
Profile.py : Use this file to manage saving and loading of user data. Do not edit.

Please visit the course Canvas for a detailed overview of the assignment.

Name: Bozhang Zhou
Email: bozhangz@uci.edu
Student ID: 93213406

This program extends the functions from assignment1 which allows users to create, open, edit, print, and read DSU files.

Supported Commands:

C: Creating a new dsu journal file in the specified directory. If the file already exists, the program loads the existing profile.

O: Opening an existing dsu file and loads the profile.

E -usr: Updating the username. The username cannot be empty or contain spaces.

E -pwd: Updating the password. The password cannot be empty or contain spaces.

E -bio: Updating the profile bio.

E -addpost: Adding a new post to the profile.

E -delpost: Deleteing a post by index.

P -usr: Printing the username.

P -pwd: Printing the password.

P -bio: Printing the bio.

R [file_path]
Reads and prints the raw contents of a .dsu file. If the file is empty, it prints EMPTY.

Q
Quits the program.

P -posts:
Prints all posts.

P -post [index]:
Prints one specific post by index.

P -all:
Prints the username, password, bio, and all posts.