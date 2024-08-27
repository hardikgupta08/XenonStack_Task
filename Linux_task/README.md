Command Name: sysopctl
	Version: v0.1.0
	Purpose: Manage system services, processes, and system health.
	Main Features:
		List running services.
		View system load.
		Manage system services (start/stop).
		Check disk usage.
		Monitor system processes.
		Analyze system logs.
		Backup system files.


Implementation Steps

Step 1: Create a Bash script named sysopctl.
Step 2: Implement basic command-line options (--help, --version).
Step 3: Implement the easy-level features.
Step 4: Implement intermediate-level features.
Step 5: Implement advanced-level features.
Step 6: Create a manual page for sysopctl.
Step 7: Test the command in different scenarios.
Step 8: Document the command usage and examples.


After creation of Bash script, make the script executable by using 
      chmod +x ssysopctl1


To create a manual page, we first create a directory if not present:
      mkdir -p /usr/local/share/man/man1


After Manual Page Creation, we move the manual page to an appropriate directory:
      sudo cp sysopctl.1 /usr/local/share/man/man1/
      sudo mandb

To Test the command, the followiung statement could be run:
      ./sysopctl --help
      ./sysopctl service list
      ./sysopctl system load
