Step 1: Create a Virtual Machine [VM]

Step 2: Make sure everything is updated on the VMs through the command 'sude apt-get update' 

Step 3: Install python onto the VMs through the command 'sudo apt install python3-pip'

Step 4: Install Flask onto the VMs through the command 'pip3 install flask' 

Step 5: Clone the repo on GitHub through the command 'git clone [Repo URL]' 

Step 6: Go inside the cloned repo folder 

Step 7: Use command 'sudo python3 app.py' to make sure it is working

Step 8: Ctrl + C to exit and then use 'sudo nohup python3 app.py > log.txt 2>&1 &' to keep the flask app running in the background when you exit out of the remote terminal.

*On Azure if it keeps on saying "Module not found" use command 'sudo pip install flask' or 'sudo apt install python3-flask'