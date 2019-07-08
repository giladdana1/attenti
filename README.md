# attenti
This exercise is written in python on an online interperter
you need to have python install on your machine
Install Python 3.6 using the MSI available in python.org download page.

Start a command prompt using the cmd.exe program and run the pip command as given below to install selenium.

C:\Python35\Scripts\pip.exe install selenium
Now you can run your test scripts using Python. For example, if you have created a Selenium based script and saved it inside C:\my_selenium_script.py, you can run it like this:

C:\Python35\python.exe C:\my_selenium_script.py
1.5. Downloading Selenium server
Note
The Selenium server is only required if you want to use the remote WebDriver. See the Using Selenium with remote WebDriver section for more details. If you are a beginner learning Selenium, you can skip this section and proceed with next chapter.

Selenium server is a Java program. Java Runtime Environment (JRE) 1.6 or newer version is recommended to run Selenium server.

You can download Selenium server 2.x from the download page of selenium website. The file name should be something like this: selenium-server-standalone-2.x.x.jar. You can always download the latest 2.x version of Selenium server.

If Java Runtime Environment (JRE) is not installed in your system, you can download the JRE from the Oracle website. If you are using a GNU/Linux system and have root access in your system, you can also use your operating system instructions to install JRE.

If java command is available in the PATH (environment variable), you can start the Selenium server using this command:

java -jar selenium-server-standalone-2.x.x.jar
Replace 2.x.x with the actual version of Selenium server you downloaded from the site.

If JRE is installed as a non-root user and/or if it is not available in the PATH (environment variable), you can type the relative or absolute path to the java command. Similarly, you can provide a relative or absolute path to Selenium server jar file. Then, the command will look something like this:

/path/to/java -jar /path/to/selenium-server-standalone-2.x.x.jar
