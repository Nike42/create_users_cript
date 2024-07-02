# create_users_script
Automating User and Group Management in Linux with Bash
########

Key Features:
########

Automated User Creation: Reads user information from a text file and creates users accordingly.
########

Group Management: Ensures each user has a personal group with the same name and adds users to specified additional groups.
########

Home Directory Setup: Creates and configures home directories with secure permissions.
########

Password Generation: Generates random passwords for new users and stores them securely.
########

Logging: Logs all actions and errors for easy monitoring and troubleshooting.
########

Using the Script
To use the script, follow these steps
#######


Save the Script: Save the provided script as create_users.sh.


Make the Script Executable: chmod +x create_users.sh


Prepare Your Input File: Create a text file with usernames and groups in the required format.


Example:
_light; sudo,dev,www-data
idimma; sudo
mayowa; dev,www-data_


Run the Script: sudo ./create_users.sh input_file.txt
