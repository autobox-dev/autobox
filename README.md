## autobox - Command line interface installation guide

Download the tar file that matches your Operating System Specifications/Architecture.

### x86-64 Linux/Intel Mac/ARM Mac

1. Install the respective files. Untar the downloaded file: `tar xzvf <PATH-TO-TAR-FILE>`

2. Move autobox directory into your executable path: `sudo cp <DIRECTORY>/* /usr/local/bin`

3. Verify that the installation is valid: `autobox`

### Windows

1. Install the windows file. Unzip the downloaded file.

2. The unzipped file (which is a folder) must be added to PATH. You can do this by setting the environment variable of PATH to include the path of the unzipped folder.

To do this follow the steps: 
* Navigate to This PC.
* lick on properties on the top left of the window.
* Scroll down and click on Advanced system settings.
* You should now have the System Properties window open. Click on the Environment Variables Button.
* Under System Variables, select path and edit.
* Add an entry with the absolute path to the folder that resulted from the unzipped file.
* Restart powershell. Now you should be able to run autobox.
