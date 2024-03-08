# Installing Poetry on Windows OS

1. [Download Python from officail Site](https://www.python.org/downloads/)
2. Install Python.

    On the first screen, make sure you select `Add Python.exe to Path`

![Python_setup](https://raw.githubusercontent.com/mkdeveloper/Installing_Poetry_in_windows_OS/main/Python_setup.PNG)


3.  Install **PIPX**

    `py -m pip install --user pipx`

4.  It is possible (and even most likely) that the above finishes with a WARNING looking similar to this:

![pipx_path](https://raw.githubusercontent.com/mkdeveloper/Installing_Poetry_in_windows_OS/main/pipx_path.png)

5.  Select the path as circled in the image and copy it.

6.  Type `cd` and paste the path, then press enter.

7.  Now enter the following command to ensure the path:

    `.\pipx.exe ensurepath`

8. Reload the Command Prompt or Terminal.

9. To install Poetry, run:

    `pipx install poetry`


## Tip:
Try running these commands to ensure the packages and scripts are installed correctly:

`python --version`

`pipx --version`

`poetry --version`
