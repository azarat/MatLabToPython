## REQUIREMENTS

To run/execute .m file via Python on Freia we need:

1. Have the latest activated Python version 3.7 (type in terminal):

    ```
    module unload python
    module load python
    ```

2. Install all uncompleted Python packeges (user visibility only):

    ```
    pip install --user metakernel
    pip install --user octave-kernel
    ```

3. Look through the *__run_matlab_via_python.py__* file as general example.

#### WHAT FILE *__run_matlab_via_python.py__* DO
It imports an library for .m files execution.
Creates variable *__script__* with .m file content (MatLab-code) and put it to the file *__myScript.m__*
Then it execute file *__myScript.m__*

For more detailed information about .m python execution visit official web-site of *__oct2py__* Python library.
