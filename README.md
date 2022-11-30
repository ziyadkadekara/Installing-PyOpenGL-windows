
Hello Guys,

I am here to help you with installing OpenGL for python in windows.
Along the journey I have faced some issues, so I have made this 
step by step instructions for you guys .

# **Step 1**

Install python in your system windows 10/11 preferred.
for python 3.8.0 : https://www.python.org/ftp/python/3.8.0/python-3.8.0-amd64.exe

If you have already installed then check for your python version

Open terminal and type "python --version"

it will display your python version. for example I have installed python 3.8.0.

# **Step 2**

Next open terminal and run the below command 
> python -m pip install --upgrade pip==20.3

sometimes you have higher version of pip installed but its okay to downgrade back to version 20.3

# **Step 3**


now for installing OpenGL
go to this site : https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyopengl

and download 
                                
    PyOpenGL‑3.1.6‑cp38‑cp38‑win_amd64.whl (for 64bit windows)  or
    PyOpenGL‑3.1.6‑cp38‑cp38‑win32.whl (for 32 bit)
                                        and
    PyOpenGL_accelerate‑3.1.6‑cp38‑cp38‑win_amd64.whl (for windows 64bit) or
    PyOpenGL_accelerate‑3.1.6‑cp38‑cp38‑win32.whl  (for windows 32bit)

**Note** :  I have in installed python 3.8.0. so I downloaded PyOpenGL  having cp38 word in it. If you have installed python 3.9 or other version download the above mentioned file having name cp39,cp10 etc.

after downloading both files according to your python version. put it a folder.
# **Step 4**

then open terminal from that folder. Windows 10 lets you launch Command Prompt in a folder through the File Explorer's address bar. **Type “cmd” in the address bar and then hit Enter**

after opening terminal enter the below command

`pip install PyOpenGL-3.1.5-cp38-cp38-win_amd64.whl --force-reinstall`

then after installing it run the below command

`pip install PyOpenGL_accelerate-3.1.5-cp38-cp38-win_amd64.whl --force-reinstall`

**Note** : Don't forget to change the file name ( e.g. : PyOpenGL-3.1.5-cp38-cp38-win_amd64.whl) to the file name that you have downloaded.

by Installing both if no error occurs Congratulation you have successfully Done the work.  now try to run the python code for opengl in your code editor. 
Hope your problem is solved.

Feel free to mark out the error if any ;) 
