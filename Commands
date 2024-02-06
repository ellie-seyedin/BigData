ls: Lists a directory’s content
Example) ls
C:\Users\elahe\Documents\Source

pwd:	Shows the current working directory’s path
Example) C:\Users\elaheh


cd:	Changes the working directory
Example) cd /directory/folder/path

mkdir:	Creates a new directory
Example) mkdir [option] [directory_name]
-p – creates a directory between two existing folders. For example, mkdir -p Music/2024/Songs creates a new 2024 directory.
-m – sets the folder permissions. For instance, enter mkdir -m777 directory to create a directory with read, write, and execute permissions for all users.
-v – prints a message for each created directory.

rm:	Deletes a file
Example)rmdir [option] directory_name


cp:	Copies files and directories, including their content
Example)cp filename.txt /home/username/Documents


mv:	Moves or renames files and directories
Example)mv filename.txt /home/username/Documents


touch:	Creates a new empty file
Example)touch [option] /home/directory/path/file.txt


file:	Checks a file’s type
Example)file filename.txt


zip: and unzip	Creates and extracts a ZIP archive
Example)zip [options] zipfile file1 file2….


tar:	Archives files without compression in a TAR format
Example)tar [options] [archive_file] [target file or directory]


nano, vi, and jed:	Edits a file with a text editor
Example)nano filename
vi filename
jed filename


cat:	Lists, combines, and writes a file’s content as a standard output
Example)cat filename.txt


grep:	Searches a string within a file
Example)grep blue notepad.txt


sed:	Finds, replaces, or deletes patterns in a file
Example)sed [option] 'script' input_file


head:	Displays a file’s first ten lines
Example)head note.txt
-n – changes the number of lines printed. For example, head -n 5 shows the first five lines.


tail:	Prints a file’s last ten lines
Example)tail -n colors.txt


awk:	Finds and manipulates patterns in a file
Example)awk '/regex pattern/{action}' input_file.txt


sort:	Reorders a file’s content
Example)sort file.txt


cut:	Sections and prints lines from a file
Example)cut [option] [file]
cut -d',' -f3-5 list.txt
-f – selects a specific field.
-b – cuts the line by a specified byte size.
-c – sections the line using a specified character.
-d – separates lines based on delimiters.

diff:	Compares two files’ content and their differences
diff [option] file1 file2
-c – displays the difference between two files in a context form.
-u – shows the output without redundant information.
-i – makes the diff command case insensitive.

tee:	Prints command outputs in Terminal and a file
Example)command | tee [option] file1
ping google.com | tee ping_result.txt 19092024.txt


locate:	Finds files in a system’s database
Example)locate -i school*note


find:	Outputs a file or folder’s location
Example)find [option] [path] [expression]


sudo:	Runs a command as a superuser
Example)sudo (command)
-k – invalidates the timestamp file.
-g – executes commands as a specified group name or ID.
-h – runs commands on the host.

su:	Runs programs in the current shell as another user
Example)su [options] [username [argument]]
-p – keeps the same shell environment, consisting of HOME, SHELL, USER, and LOGNAME.
-s – lets you specify another shell environment to run.
-l – runs a login script to switch users. It requires you to enter the user’s password.

chmod:	Modifies a file’s read, write, and execute permissions
Example)chmod -rwxrwxrwx note.txt


chown:	Changes a file, directory, or symbolic link’s ownership
Example)chown linuxuser2 filename.txt


useradd and userdel:	Creates and removes a user account
Example)useradd [option] username
passwd username
userdel username


df:	Displays the system’s overall disk space usage
Example)df [options] [file]
-m – displays information on the file system usage in MBs.
-k – prints file system usage in KBs.
-T – shows the file system type in a new column.

du:	Checks a file or directory’s storage consumption
Example)du /home/user/Documents
-s – shows the specified folder’s total size.
-m – provides folder and file information in MB.
-k – displays information in KB.
-h – informs the displayed folders and files’ last modification date.

top: Displays running processes and the system’s resource usage
Example)

htop:	Works like top but with an interactive user interface
Example)htop [options]
-d – shows the delay between updates in tenths of seconds.
-C – enables monochrome mode.
-h – displays the help message and exits.

ps:	Creates a snapshot of all running processes
Example)ps cms
Unique process ID (PID).
Type of the terminal (TTY).
Running time (TIME).
Command that launches the process (CMD).
The ps command accepts several options, including:

-T – displays all processes associated with the current shell session.
-u username – lists processes associated with a specific user.
-A – shows all the running processes.

uname:	Prints information about your machine’s kernel, name, and hardware
Example)uname [option]
-a – prints all the system information.
-s – outputs the kernel name.
-n – shows the system’s node hostname.

hostname:	Shows your system’s hostname
Example)hostname [option]
-a – displays the hostname’s alias.
-A – shows the machine’s Fully Qualified Domain Name (FQDN).
-i – outputs the machine’s IP address.

time:	Calculates commands’ execution time
Example)time [commandname]
time cd /home/directory/path; touch bashscript.sh; chmod +x bashscript.sh


systemctl: Manages system services
Example)systemctl [commandname] [service_name]


watch: Runs another command continuously
Example)watch [option] command
-d – displays the differences between command executions.
-n – changes the default two-second interval.
-t – disables the header containing the time interval, command, timestamp, and hostname.

jobs:	Displays a shell’s running processes with their statuses
Example)jobs [options] jobID
-l – lists process IDs and their information.
-n – shows jobs whose statuses have changed since the last notification.
-p – displays process IDs only.

kill:	Terminates a running process
Example)ps ux
kill [signal_option] pid


shutdown:	Turns off or restarts the system
Example)shutdown [option] [time] "message"


ping:	Checks the system’s network connectivity
Example)ping google.com


wget:	Downloads files from a URL
Example)wget https://wordpress.org/latest.zip


curl:	Transmits data between servers using URLs
Example)curl [option] URL
-o or -O – downloads files from a URL.
-X – changes the default HTTP GET method.
-H – sends a custom header to the URL.
-F – uploads a file to the specified destination.

scp:	Securely copies files or directories to another system
Example)scp [option] [source username@IP]:/[directory and file name] [destination username@IP]:/[destination directory]
-P – changes the port for copying. The default is 22.
-l – limits the scp command’s bandwidth.
-C – compresses transferred data to make it smaller.

rsync:	Synchronizes content between directories or machines
Example)rsync [options] source destination
-a – enables archive mode to preserve file permissions, dates, and other attributes.
-v – shows visual information about the transferred file.
-z – compresses the transferred file data to reduce their size.

lfconfig:	Displays the system’s network interfaces and their configurations
Example)ifconfig [interface] [option]
-s summarizes the network interfaces and their configuration. This option goes before the interface name.
up and down – enables and disables a network interface.
inet and inet6 – assigns an IPv4 and IPv6 address to a network interface.
netmask – specifies the subnet mask to use with an IPv4 address.

netstat:	Shows the system’s network information, like routing and sockets
Example)netstat [option]
-a – displays listening and closed sockets.
-t – shows TCP connections.
-u – lists UDP connections.
-r – displays routing tables.
-i – shows information about network interfaces.
-p – lists programs’ names and process IDs.
-c – continuously outputs network information for real-time monitoring.


traceroute:	Tracks a packet’s hops to its destination
Example)traceroute [option] destination
-m – sets each packet’s maximum hops.
-n – prevents the command from resolving IP addresses to hostnames for quicker tracing.
-I – changes the default UDP packets to UCMP.
-w – adds a timeout in seconds.


nslookup:	Queries a domain’s IP address and vice versa
Example)nslookup [options] domain-or-ip [server]
-type= – queries specific information, like the IP address type or MX record.
-port= – sets the DNS server’s port number for the query.
-retry= – repeats the query a specific number of times upon failure.
-debug – enables the debug mode to provide more information about the query.

dig:	Displays DNS information, including record types
Example)dig [option] target [query_type]


history: Lists previously run commands
Example)history [option]
-c – clears the history list.
-d offset – deletes the history entry at the OFFSET position.
-a – appends history lines.

man:	Shows a command’s manual
Example)man [option] [section_number] command_name


echo:	Prints a message as a standard output
Example)echo "Hostinger Tutorials"
n – displays the output without the trailing newline.
-e – enables the interpretation of the following backslash escapes:
\b – removes spaces in between a text.
\c – produces no further output.

ln:	Links files or directories
Example)ln [option] [source] [destination]


alias and unalias:	Sets and removes an alias for a file or command
Example)alias name=string
alias k='kill'
unalias [alias_name]


cal:	Displays a calendar in Terminal
Example)cal [option] [month] [year]
  

apt-get:	Manages Debian-based distros package libraries
Example)apt-get [options] (command)
update – synchronizes the package files from their sources.
upgrade – installs the latest version of all installed packages.
check – updates the package cache and checks broken dependencies.
