# Command Line Interface Languages

Watch the [Harvard CS50 command line overview](https://www.youtube.com/watch?v=lnYKOnz9ln8)

1. Login and click the orange `START` button on [Codecademy's Learn the Command Line course][1]. Complete the first 2 modules in this course:

* Navigating the File System
* Viewing and Changing the File System

Navigating the File System has 9 lessons which can be found by clicking the menu icon in the lower left hand corner of the codecademy screen.
![Codecademy Menu][2]

In the [Navigation module][3], you'll learn about the following commands:

* `pwd` outputs the name of the current working directory.
* `ls` lists all files and directories in the working directory.
* `cd` switches you into the directory you specify.
* `mkdir` creates a new directory in the working directory.
* `touch` creates a new file inside the working directory.

After completing these 9 lessons click `Next` to move to the next module. Remember, you do **not** have to upgrade to codecademy pro.

In the [Manipulation module][4], you'll learn about:

* options that modify what `ls` and `cp` do
* how wildcards allow you to select groups of files or directories

## Introducing a new tool - Glitch

Codecademy is great for learning and practicing new concepts, but it is purposefully limiting in what you can do. When we need more flexibility you'll use a site called [Glitch][8] to apply the knowledge you've been learning.

This is especially useful when learning the command line as typing the wrong command on your personal computer can do serious damage.

1. Head to [https://glitch.com][8] and click the `Sign in` button in the upper right.

    ![Glitch signup 1][9]

2. Choose the `Sign in with Github` option and you'll be taken to the screen below. Click the green `Authorize FogCreek` button (FogCreek is the company who makes Glitch). You'll be redirected to the glitch homepage with an account ready for coding!

    ![Glitch signup 2][10]

3. Click `New Project` then `hello-webpage` in the upper right corner and you'll be taken to the Glitch coding environment.

    ![Glitch signup 3][11]

    Notice, my project is called gutsy-gym. Yours will be called something different, this allows many people to create projects on glitch and share them with each other.

4. Click the `Logs` button near the upper left to open the console at the bottom of your browser.
5. There, you will see a `Console` button. Click this and a new window or tab will open with a command line for your project

    ![Glitch console][12]

6. Practice the commands you learned. If you get stuck, head back to glitch.com and create a new project to start over.

## Extra Resources

Because Windows is not based on Unix, there are several differences in how the Windows Command Prompt works compared to what you learned above. thenewboston has [a good Youtube playlist][13] that does over the Windows Command Prompt if you're a Windows user.

djangogirls.com has [a good resource][14] that takes the topics and shows them for Mac, Linux, and Windows side-by-side.

[//]: # (References)
[1]: https://www.codecademy.com/learn/learn-the-command-line
[2]: assets/cc-cli-1.png
[3]: https://www.codecademy.com/courses/learn-the-command-line/lessons/navigation
[4]: https://www.codecademy.com/courses/learn-the-command-line/lessons/manipulation
[8]: https://glitch.com
[9]: assets/glitch-1.png
[10]: assets/glitch-2.png
[11]: assets/glitch-3.png
[12]: assets/glitch-4.png
[13]: https://www.youtube.com/playlist?list=PL6gx4Cwl9DGDV6SnbINlVUd0o2xT4JbMu
[14]: https://tutorial.djangogirls.org/en/intro_to_command_line/