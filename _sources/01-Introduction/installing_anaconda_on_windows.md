## Installing Anaconda

In this section, we will run through how to install the [Anaconda distribution](https://www.anaconda.com/what-is-anaconda/) of Python on Windows 10. I think the Anaconda distribution of Python is the the best option for undergraduate engineers who want to use Python. Anaconda is free (although the download is large which can take time) and can be installed on school or work computers where you don't have administrator access or the ability to install new programs.

#### Steps:

1. Visit [Anaconda.com/distribution](https://www.anaconda.com/distribution/)

2. Select Windows

3. Download the **_.exe_** installer

4. Open and run the **_.exe_** installer

5. Open the **Anaconda Prompt** and run some Python code

#### 1. Visit the Anaconda downloads page

Go to the following link: [Anaconda.com/distribution](https://www.anaconda.com/distribution/)

The Anaconda Downloads Page will look something like this:

![anaconda download page](images/anaconda_download_page.png)

#### 2. Select the Windows

Select Windows where the three operating systems are listed.

![anaconda select Windows](images/anaconda_select_windows.png)

#### 3. Download

Download the Python 3.8 version. Python 2.7 is legacy Python. For undergraduate engineers, select the Python 3.8 version. If you are unsure about installing the 32-bit version vs the 64-bit version, most Windows installations are 64-bit. 

![anaconda select python 3.8](images/anaconda_python3_or_python2.png)

You may be prompted to enter your email. You can still download Anaconda if you click **[No Thanks]** and don't enter your Work Email address.

![anaconda](images/anaconda_enter_email.png)

The download is quite large (over 500 MB) so it may take a while for the download to complete.

![anaconda downloading](images/anaconda_downloading.png)


#### 4. Open and run the installer

Once the download completes, open and run the **_.exe_** installer

![anaconda installer](images/anaconda_run_installer.png)

At the beginning of the install, you will need to click **[Next]** to confirm the installation,

![anaconda installer click next](images/anaconda_installer_click_next.png)

and agree to the license.

![anaconda license](images/anaconda_agree_to_license.png)

At the Advanced Installation Options screen, I recommend:

 * **do not check** "Add Anaconda to my PATH environment variable"

 * Keep "Register Anaconda as my default Python" 3.7 checked

![anaconda path variable](images/anaconda_path2.png)

#### 5. Open the Anaconda Prompt from the Windows start menu

After the Anaconda install is complete, you can go to the Windows start menu and select the Anaconda Prompt.

![anaconda in start menu](images/anaconda_from_start_menu.png)

This will open up the Anaconda Prompt. Anaconda is the Python distribution and the Anaconda Prompt is a command line tool (a program where you type in your commands instead of using a mouse). It doesn't look like much, but it is really helpful for an undergraduate engineer using Python.

![anaconda prompt](images/anaconda_window.png)

At the Anaconda Prompt, type ```python```. The ```python``` command starts the Python interpreter. 

![conda prompt type python](images/conda_prompt_type_python.png)

Note the Python version. You should see something like ```Python 3.7.0```.  With the interperter running, you will see a set of greater-than symbols ```>>>``` before the cursor. 

![anaconda prompt](images/conda_type_python.png)

Now you can type Python commands. Try typing ```import this```. You should see the **_Zen of Python_** by Tim Peters

![anaconda_import_this](images/conda_import_this_output.png)

To close the Python interpreter, type ```exit()``` at the interpreter prompt ```>>>```.  Note the double parenthesis at the end of the command. The ```()``` is needed to stop the Python interpreter and get back out to the Anaconda Prompt.

To close the Anaconda Prompt, you can either close the window with the mouse, or type ```exit```.
 
#### Congratulations! You installed the Anaconda distribution on your Windows computer!

When you want to use the Python interpreter again, just click the Windows Start button and select the **Anaconda Prompt** and type ```python```.
