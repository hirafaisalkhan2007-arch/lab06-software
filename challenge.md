1. Install http, run it, write one thing it shows.
Command: sudo apt install -y httpie
Output: It shows the HTTPie usage and documentation link.

2. Which version of apache2 does Ubuntu offer?
Command: apt show apache2 | head -2
Version: 2.4.66-2ubuntu2.6

3. How many packages are installed on your server now?
Command: apt list --installed | wc -l
Number: [Type your number here]

4. Use Docker to run alpine so that it prints Hello from Alpine.
Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. What is the full path of Docker's key file, and of Docker's sources file?
Key path: /etc/apt/keyrings/docker.asc
Source path: /etc/apt/sources.list.d/docker.sources

6. Remove http and prove that it is gone.
Commands: sudo apt remove -y httpie, then hash -r, then http. It says command not found.
