# Assignment: Building a Test Developement Server
You have been hired as a junior DevOps Engineer at `Kwe4Africa`. The Kwe4Africa's infrastructure is based on the Linux Operating System. Your manager has tasked you with the responsibility of setting up a development serverr for one of their clients using vagrant tool and version control tool.

![image](https://github.com/user-attachments/assets/e1d1d470-389b-41ef-b745-147d2d1214da)

Prerequisites:
* Familiarity with Linux, Apache, and bash scripting
* Vagrant installed on your local machine
* Git and GitHub account for submission


1.  **Create and Start Linux VM**
   Your manager has assigned you the task to create a Linux virtual machine and install a web server inside it, all using automation.
    -  Create a new directory for your project.
    -  Inside the directory, initialize a Vagrant project.
    -  Configure the `Vagrantfile` to provision a Linux virtual machine (Ubuntu 20.04 or similar).
    -  Configure the VM name, network ip etc.
    -  Ensure the VM has at least `512MB` of RAM and `1 CPU`.

2.  **Install Apache Server and Deploy the Static Website:**
    - Write a Bash script to install Apache on the VM.
    - Ensure Apache is set to start on boot.
    - Your script should check if there is directory `website`, Copy the provided static website files from your local machine to the Apache web root directory on the VM `(/var/www/html)`.
    - Ensure the website is accessible via the VM’s IP address.
    - Display neccessary log messages and time during provisioning

3. **Prepare Website Files**
    - Download and unzip a website template [here](https://www.tooplate.com/view/2119-gymso-fitness)
    - Create a new directory website in your project directory
    - Add all content of the downloaded file to this directory

4. **Test the Deployment:**
   - Access the website from your host machine’s browser using the VM’s IP address.
   - Ensure that all website assets (images, CSS, JS) load correctly.

5. **Version Control and Submission:**
   - Initialize a Git repository in your project directory.
   - Commit all relevant files (Vagrantfile, Bash script, website files).
   - Push your project to a GitHub repository.
   - Share the GitHub repository link as your submission on the `LMS portal`.

## Evaluation Criteria:
* Correctness: The website should be correctly deployed and accessible.
* Automation: The deployment process should be fully automated by the Bash script.
* Code Quality: Proper use of Vagrant, Bash scripting, and Git version control.
* Documentation: Clear `README.md` file and `screenshot` where neccessary explaining the steps you followed, any assumptions made, and how to access the website.

