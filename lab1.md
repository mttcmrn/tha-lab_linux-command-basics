#### NAVIGATING TO THE THA LAB INSTRUCTIONS FOLDER

All THA labs contain a local copy of the lab instructions. These instructions are downloaded when you run the git clone command during the lab setup. 

Begin at a new terminal window.

1. Use the LS command to list the subfolders at your current location.
2. Using the commands shown in the module video naviagte to the assets folder at  /THA/setup/assets. The correct commands are shown below.
3. 

3. Open the PDF file “launch.pdf” in your favorite text editor and locate the object number 108. This is where we define what application is executed within the PDF file. Take note of the syntax for this object:

  ```bash
  /Type /Action
  /S /Launch
  /Win
  <<
  /F (calc.exe)
  >>
  ```

4. Modify the /F Byte string to (cmd.exe) and reopen the PDF file with Adobe Reader which should result in the Windows Command Shell being launched.

5. This concludes the lab exercise, continue to exercise 2.
