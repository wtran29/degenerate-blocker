# degenerate-blocker

## Description
A website blocking script to help be more productive by blocking the sites you most frequent for a certain amount of hours.
After the hours are up, the script updates and removes the sites from being blocked. Great for degenerates.

## How it Works
* Runs in the background and script checks every 5 seconds when your computer starts up.
* While within the hours you're working, the script adds the websites you listed to your hosts file in your computer.
* If it's not within the parameters when you're working, the script checks each line of the hosts file and looks for any lines that match the websites.
* Then it rewrites those lines at the top of the file excluding the websites listed at working hours.
* After that, the rest of the lines are deleted and the file defaults to its current position.
 
