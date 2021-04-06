## How to Open a Jupyter Notebook

In this section, we will run through how to open a **Jupyter notebook** on Windows 10.  **Jupyter notebooks** are one way engineers can write and execute **Python** code. **Jupyter notebooks** contain **Python** code, the output of that code produces when it is run and markdown cells to explain what the code means. A **Jupyter notebook** can be started from the **Anaconda Prompt**, the **Windows Start Menu** or by using the **Anaconda Navigator**.

### 3 ways to open a Jupyter notebook:

1. **Anaconda Prompt**

2. Windows Start Menu

3. Anaconda Navigator

### 1. Anaconda Prompt

The first way to start a new **Jupyter notebook** is to use the **Anaconda Prompt**.

Go to the Windows start menu and select **[Anaconda Prompt]** under **[Anaconda3]**.

![anaconda in start menu](images/anaconda_start_menu.png)

If you don't see the **Anaconda Prompt** in the Windows Start Menu, then you need to install **Anaconda**. Download **Anaconda** at the following link: [Anaconda.com/distribution](https://www.anaconda.com/distribution/)

The **Anaconda Prompt** window should look something like the image below:

![anaconda prompt](images/jupyter_notebook_anaconda_prompt.png)

At the **Anaconda Prompt** type:

```text
> jupyter notebook
```

This command starts a **Jupyter notebook**. The output in the terminal will look something like the output shown below:

```text
Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=6bdef677d3503fbb23e1b4fa0c802ee7c20bdcfd4d9b9951
[I 16:14:12.661 NotebookApp] Accepting one-time-token-authenticated connection from ::1
```

A web browser should open and you should be able to see the **Jupyter file browser**:

![jupyter file browswer](images/new_notebook_from_browser.png)

In the upper right select **[New]** --> **[Python 3]**

You will see a new tab open in your web browser. This new browser tab is a **Jupyter notebook**.

![jupyter file browswer](images/new_notebook.png)

To rename the **Jupyter notebook**, click the file name at the top of the page to the right of the Jupyter icon.

![jupyter file browswer](images/click_change_name.png)

This opens a dialog box where the new name can be typed.

![jupyter file browswer](images/rename_window.png)

Try typing the code below into the first cell in the **Jupyter notebook** to the right of the ```In [ ]:``` prompt

```text
import  this
```

Then click the run button in the middle of the menu at the top of the notebook.

![jupyter file browswer](images/run_import_this.png)

### 2. Windows Start Menu

Another way to open a **Jupyter notebook** is to use the Windows start menu. 

Open the Windows start menu and select **[Anaconda3(64 bit)]** --> **[Jupyter Notebook]**

![jupyter file browswer](images/windows_start_jupyter_notebook.png)

This will open the **Jupyter file browser** in a web browser tab. 

In the upper right select **[New]** --> **[Python 3]**

![jupyter file browswer](images/new_notebook_from_browser.png)

A new **notebook** will open as a new tab in your web browser

![jupyter file browswer](images/new_notebook.png)

### 3. Anaconda Navigator

The last way to open a **Jupyter notebook** is by using the **Anaconda Navigator**. You can open the **Anaconda Navigator** using the Windows Start Menu and selecting **[Anaconda3(64-bit)]** --> **[Anaconda Navigator]**.

![jupyter file browswer](images/windows_start_anaconda_navigator.png)

This opens the **Anaconda Navigator** application.  In the middle of the page, in the **Jupyter notebook** tile, click **[Launch]**

![jupyter file browswer](images/anaconda_navigator_jupyter_notebook_launch.png)

This will open the **Jupyter file browser** in a web browser tab. 

In the upper right select **[New]** --> **[Python 3]**

![jupyter file browswer](images/new_notebook_from_browser.png)

A new **notebook** will open as a new tab in your web browser.

![jupyter file browswer](images/new_notebook.png)

**Congratulations!**

You know how to open a **Jupyter notebook** on your Windows 10. Now go write some Python code to solve some problems!
