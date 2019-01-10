# CSC 335 - Software Setup

Please follow the instructions in the following order to get things set up for the projects. If you already have the software (with the correct version) you can skip to the next step.

1. Install JDK 8 – If you have a newer version of Java, that’s fine, just stick to the Java 8 subset of the language for the course. The following instructions are for Windows and Mac; if you use Linux, use your distro's package manager to install OpenJDK 8.

    1.1 Go to the [Java 8 download page](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) and download JDK8.

    1.2 Accept the license agreement by selecting the radio button

    1.3 Download the appropriate link for your platform

    1.4 Run the installer

2. Install Eclipse 2018-12

    2.1 Go to the [Eclipse downloads page](http://www.eclipse.org/downloads/)

    2.2 It should have a download button that picks the right version for your system

    2.3 Install and run

3. Install EGit

    3.1 In Eclipse, go to `Help > Install New Software... >`

    3.2 Copy `http://download.eclipse.org/egit/updates/1` into Eclipse, and hit <kbd>Enter</kbd>

    3.3 When it loads, click the Select All button

    3.4 To properly resolve alld ependencies, check [x] Contact all update sites during install to find required software

    3.5 Click Next, agree to the license terms, and install

    3.6 Restart Eclipse as directed

4. Go to your assignment repository on GitHub, and click the clone button and copy the URL provided in the text field.

5. Clone the repository and open it in Eclipse

    5.1 Switch back to Eclipse, and then go to `File > Import`

    5.2 Open the folder "Git" and select "Projects from Git", then click "Next"

    5.3 Click "Clone URI", and then "Next"

    5.4 The next window should automatically be populated, based on the URI in your clipboard from step 4.5. If it is not, paste the URI in "URI", `github.com` in "Host", and your username and password in the authentication box. Then, click "Next", and then "Next" again in the next window.

    5.5 If you want, change the destination directory, and then click "Next".

    5.6 Select the radio button for "Import existing Eclipse projects", and then click "Next".

    5.7 Select the project to import (if it is not selected already), and then click "Finish".

    5.8 The new project should now be visible in the left panel under "Project Explorer".

6. Editing .java files

    6.1 In the Project Explorer tab, expand the `src` folder until you see Lab1.java. Double click it to open.

7. Edit the file as per the comments, and save when you are done. Make sure to test that the program compiles and runs by using the green play button in the toolbar.

8. Commit and push your changes

    8.1 Go to `Window > Show View > Other`

    8.2 Expand "Git", and select "Git Staging"

    8.3 In the window that appears, click the green double-plus icon above the "Unstaged Changes" box to stage all modified files (which is one, in this case) for committing.

    8.4 Write a commit message in the box on the right, indicating what you have done.

    8.5 Click "Commit and Push". If you are prompted for your GitHub credentials, type them in.

9. If there are no error messages in the resulting dialog box, you are done!