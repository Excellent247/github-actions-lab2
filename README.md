# lab2

Fork the Repository - https://github.com/kodekloudhub/github-actions-lab2
Notice the Repository name is - github-actions-lab2
Go through the repository, there is a workflow file named python-installation.yml
There is one job named - build
The Job includes one step named Set up Python to install python of version 3.10
Go to Actions Tab click on I understand my workflows, go ahead and enable them
Do the following:
Configure matrix strategy to set up a build matrix for this job/step using the below spec:

This job should execute on these operating systems - ubuntu-latest, macos-14, windows-latest
Use os as the key to define these operating systems within the matrix.
The Set up Python step should install python-version 3.10, 3.11, 3.12
Use py-version as the key to define these python-version within the matrix.
Modify the job and step to make use of these matrix values.
Push and trigger the workflow.


Continue work on the Repository named - github-actions-lab2
Configure matrix strategy to exclude below combinations:

os: macos-14
py-version: 3.12
