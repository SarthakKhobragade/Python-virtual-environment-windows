# Python-virtual-environment-windows
Commands for venv 


Step 1: Create

  To create a virtual environment, decide upon a directory where you want to place it, and run the venv module as a script with the directory path:
  Note: If you are using Python 3, then you should already have the venv module from the standard library installed.
  From here on out, we’ll assume you’re using the newer venv tool, since there are few differences between it and virtualenv with regard to the actual commands. In reality, though, they are very different tools.
      
      > python3 -m venv [Virtual Environment Name]
  
  Example,
			  
        > python3 -m venv sample_venv
  
  Note: By default, this will not include any of your existing site-packages.
  Here python -m flag stands for the module, i.e. some modules have main entry points and in order to run this has to be used.
  This will create the sample_venv directory if it doesn’t exist, and also create directories inside it containing a copy of the Python interpreter, the standard library, and various supporting files.

Step 2: Activate

  Before we can start installing our packages in our virtual environment, we need to activate the environment. Remember to activate the relevant virtual environment every time you work on the project. This can be done using the following command:
  On Windows :
  
    > .\[Virtual Environment Folder Name]\Scripts\activate
  
  Example,
  
    > .\sample_venv\Scripts\activate
  
  On Unix or Mac :
    
    > source [Virtual Environment Name]/bin/activate
  
  Example,
    
    > source sample_venv/bin/activate
  
  Once the virtual environment is activated, the name of your virtual environment will appear on the left side of the terminal. This will let you know that the virtual environment is currently active.

Step 3: Deactivating the virtual environment
    
    (sample_venv) C:\Users\username\Python_venv> deactivate
