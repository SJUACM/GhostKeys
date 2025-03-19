This guide is intended to be used alongside the live demo. It includes all the commands that will be run with brief explanations of what they each do. It also contains a very brief description of how the GhostKeys program works. 

What you need for this lab:
- A github account
- VS-Code
- A linux machine to develop on
- A windows machine to test on

For the two machines, it can be any combination of VMs or physical machines you want. For the live demo, Ill be developing on a Kali VM, and testing on a windows VM. You should be able to use any windows machine for testing. Due to the simplicity of this keylogger, it **SHOULDNT** set off anti-virus solutions (but it might. Who knows). 

Commands Used: In order (All commands are on your linux machine)
- Install VS Code
	- `sudo apt install code-oss`
- Clone the github repo
	- `cd /opt`
	- `sudo git clone https://github.com/SJUACM/GhostKeys.git`
	- `cd GhostKeys`
- Create a new branch
	- `git checkout -b <new-branch-name>`
		- Replace "`<new-branch-name>`" with whatever you want to name your branch
- Open the repo in VS Code
	- `sudo code-oss .`
- Commit Changes
	- `git add <changed files>`
		- Replace `<changed files>` with the names of any files you made changes to
	- `git commit -m "commit message"`
		- Replace `commit message` with a short message (about 1 sentance) describing your changes
- Push Changes to github
	- `git push origin <branch name>`
		- Replace `<branch name>` with the name of your branch

After youve pushed your changes, in order to submit a pull request, open the GhostKeys repo on github. 
- Go to the "Pull Requests" tab and click "New Pull Request"
- Select the branch you pushed. Here youll be able to compare it to the main branch and see all the changes you made. 
- Click "Create Pull Request"
- Add a description of what you changed. 
- Click Submit.

If all goes well and the creator likes what you did, they will approve your request and merge it into the main branch.
