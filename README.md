# Set up automation environment

##1. Install java 8
*Download java from internet, for example - https://www.java.com/en/download/
*Double click install java on windows
*Type advanced system settings in the search box (beside the Windows start button), clicks View advanced system settings.
*Add JAVA_HOME - In System variables, clicks New... button to add a new JAVA_HOME variable and point it to the JDK installed folder.
*•	Update PATH ：In System variables, find PATH, clicks edit... button :
In old version of Windows, it will prompt you below dialog box to edit the values directly, append this %JAVA_HOME%\bin; to the end of the line.
In latest Windows 10, it will prompt you below dialog box, clicks on New button, and add this %JAVA_HOME%\bin
*Test - Open a command prompt, type: java –version/echo %JAVA_HOME%

##2. Download Automation build from GitHub
*Go to Git hub  and open https://github.com/FujitsuUscan/UscanEnterpriseAutomation
Press “Code” button and copy https://github.com/FujitsuUscan/UscanEnterpriseAutomation.git
* Go to your local machine and create a new folder name which you like and from there open command line: type : “git clone https://github.com/FujitsuUscan/UscanEnterpriseAutomation.git”

##3. Download Eclipse latest version from - https://www.eclipse.org/downloads/
*Install eclipse on your window
*Open eclipse and go to File -> import -> Maven -> Existing Maven Projects
*Press “Browse…” -> select your git project(UsanEnterpriseAutomation) -> Finish