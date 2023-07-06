# Assignments

This Repo will act as the template for Assignment uploads.

# Steps

1. Create a public repo with README and add each assignments in separate folder
2. Create a YAML file (in detail below)
3. Add the Tests folder to corresponding assignments
4. Add your system as a self-hosted runner

# Prerequisites

1. Caraya Unit Test Framework
2. Drona
3. G- CLI

Install them from VIPM if not available.

## NOTE: Kindly follow the steps below in creating files

# STEP1: Creating YAML File

![image](https://github.com/Sadh26/Assignments/blob/master/README%20Images/image.png)

Click SETUP A WORKFLOW YOURSELF and paste the code from the YAML file of this repository.
(After commiting in GitHub pull the updates to your local)

# STEP2: Details of YAML File

![YAML_Image](https://github.com/Sadh26/Assignments/blob/master/README%20Images/YAML.png)

1. This will trigger the test to run (only if connected to GitHub through Windows Powershell) once there is a PR or push to the master/main branch. [Press ctrl+/ to uncomment it from the YAML template]
2. Follow this https://solitontech-my.sharepoint.com/:w:/p/sadhana_suresh/EUg5HBnxLrpCqPJ7OgUee3IBjahCa6hl3Jtg0OSPKQXD-Q?e=hvmr8B to set up a Self-hosted system

![Github_Workspace_Image](https://github.com/Sadh26/Assignments/blob/master/README%20Images/GH%20Workspace.png)

3. ${{ github.workspace }} --> To see the directory you can echo this and check. Call the Test vi in the run command.

# STEP3: Assignment File Hierachy

![Files_Image](https://github.com/Sadh26/Assignments/blob/master/README%20Images/Files.png)

Have the Project files, Main.vi and Tests folder

![Tests_Image](https://github.com/Sadh26/Assignments/blob/master/README%20Images/Tests.png)

The Tests Folder will contain the Test vi, Test library and Drona ini file.
