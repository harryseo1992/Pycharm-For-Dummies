---
layout: default
title: Setting up PyCharm
nav_order: 2
---

# Setting up PyCharm
{: .no_toc }


Before write actual code with PyCharm, you need to make a basic setup for PyCharm.
You will be able to make a new project in your PyCharm and Python file by successfully follow the steps below.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Check if Python is Working
If you successfully installed Python, Git, and PyCharm, the first thing you need to do is to check if your Python program is working.

In Windows 10, you can check it using Command Prompt.

1. Press ***WIN*** ( ![windows-key](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/windows_logo.png?raw=true "windows key") ) + ***R***.

2. Type **cmd** in the Run window and press *OK* as figure below shows.

    ![cmd-run](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/run_cmd.png?raw=true "Run cmd")
    
    Okay! Let's execute Python in Command Prompt next.

3. Type "python" in your Command Prompt like below.

    ![cmd-python-implementation](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/1.cmd_python_implementation.png?raw=true "Python implementation in cmd")
    
    If you succeeded, you can see the current version of your Python and after that, you will see three close angled brackets(```>>>```).
    
    The brackets indicate that you are currently using the Python interpreter.

    ![cmd-python-implementation2](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/2.cmd_python_implementation_2.png?raw=true "Python implementation in cmd")
    
    **STOP**
    {: .label .label-red }
        If you failed to execute Python program in your Command Prompt, you MUST add Python to Windows PATH.
        To add Python to Windows PATH, please see Troubleshooting - 1. Add Python to PATH.
    
    Next, let's print **Hello World** using Python.

4. Type **print("Hello World")** next to the angled brackets, and press *ENTER*.

    You will see **Hello World** is printed on your screen.

    ![cmd-hello-world](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/3.cmd_hello_world.png?raw=true "Print hello world in cmd")

    **GO**
    {: .label .label-green }
        If you successfully followed the steps all the way here, it means your Python is perfectly working.

5. Type **quit()** to terminate Python in your Command Prompt.

    ![cmd-quit](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/4.cmd_quit().png?raw=true "Quit Python from cmd")

Okay! Your Python seems perfectly working!

Next, let's create a new project in PyCharm.

## Create a New Project in PyCharm
In this stage, you will be able to create a new project in your PyCharm.

1. Open your PyCharm and click *New Project* button.

    ![PyCharm-starting-page](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/5.PyCharm_Starting_Page.png?raw=true "PyCharm starting page")

2. Click the arrow as is shown in the first red box, and click the *etc* button (```...```).
    
    **GO**
    {: .label .label-green }
        If you can see an interpreter as figure below, GO STRAIGHT TO STEP 5

    ![Creating-new-project-1](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/7.click_down_arrow.png?raw=true "Creating new project")

3. Select *System Interpreter* from the left navigation bar, and click the *etc* button (```...```).

    Then, find the path to *python.exe* file. It is usually in **C:\Users\\\[YOUR_USER_NAME\]\AppData\Local\Programs\Python\Python38\python.exe**.

    **CAUTION**
    {: .label .label-yellow }
        The number with Python (e.g., Python38) may vary depending on the Python version that you installed.

    When you find your *python.exe* file, click *OK* button.

    ![Creating-new-project-2](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/8.find_interpreter.png?raw=true "Creating new project 2")

4. Double check that you can see the interpreter correctly, and press *OK* button.

    ![Creating-new-project-3](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/9.Interpreter_found.png?raw=true "Creating new project 3")

5. Press *Create* button, then you get a new project in your PyCharm.

    ![Creating-new-project-4](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/10.create_new_project.png?raw=true "Creating new project 4")
    
After you create a new project, you will see a window like figure below.

![Creating-py-file-1](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/11.first_window_after_creating_project.png?raw=true "Createing py file 1")

Next, let's create a **.py** file in your project.

## Create .py File into the Project
1. Right-click the project directory, hover on **New** and click **Python File** sequentially.

    ![Creating-py-file-2](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/12.create_new_python_file.png?raw=true "Createing py file 2")

2. Name your new .py file (HelloWorld in this example) and press *ENTER*.

    ![Creating-py-file-3](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/13.creating_py_file.png?raw=true "Createing py file 3")
    
Great! You successfully created a .py file in your project!

You also create multiple **.py** files in a project by repeating the steps above.

Finally, let's run the **.py** file!

## Run Your .py File

1. Type your Python code like **print("Hello World")**, right-click on your screen, and click *Run \[YOUR_FILE_NAME\]*

    ![Run-your-py-file-1](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/14.run_py_file.png?raw=true "Run your py file 1")

2. Check the result of the execution.

    ![Run-your-py-file-2](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/15.after_run.png?raw=true "Run your py file 2")

Congratulations!!! You successfully finished setting up your PyCharm.

Next, try to follow [Linking to Github](https://harryseo1992.github.io/Pycharm-For-Dummies/docs/ui-components) if you want to use PyCharm more efficiently.
