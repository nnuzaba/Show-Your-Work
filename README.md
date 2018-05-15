# Show-Your-Work
This plugin allows users to log their coding activity.

To use the plugin, download the 'Show Your Work.jar' file, open a Pycharm Project, go to File->Settings->Plugins->Install from Disk and then select the .jar file. 

If there's an editor open, and it's a .py file, the following actions can be found under the VCS tab under the name "Show Your Plugin Tools". 
![Screenshot of IDE with plugin installed](locationOfPluginTools.png)

Once an editor tab is opened, the 'Start Logging Edits' button creates or updates a CSV file named '(filename).csv' located in the same directory as the original file.<br />

The 'Generate Zip for Submission' button creates a zip file named '(filename)_log.zip' in the current directory, which contains a text version of the original file, as well as the CSV log file.<br />

The 'Generate Original from Log' button generates a txt file that uses the CSV log file to replicate the original into a file named '(filename)_currentVersion.txt', also located in the same directory as the original.<br />



