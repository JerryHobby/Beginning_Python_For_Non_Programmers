# Writing and Running Your First Python Program

Now that you have Python and Visual Studio Code installed, it’s time to write and run your first Python program. Writing code may seem intimidating at first, but don’t worry—Python is designed to be beginner-friendly. In this section, you’ll create a simple program that prints a message to the screen, commonly known as the "Hello, World!" program.

#### Step 1: Create a New Python File

1. Open Visual Studio Code.
2. From the menu at the top, select **File > New File** to create a new file.
3. Save the file by selecting **File > Save As**. Name the file `hello.py` and make sure to save it with the `.py` extension, which indicates that it is a Python file.

#### Step 2: Write the "Hello, World!" Program

In the `hello.py` file, type the following code:

```python
print("Hello, World!")
```

#### Step 3: Run the Python Program

1. Once you’ve written the code, you can run the program directly from within VS Code.
2. First, make sure that the Python interpreter is selected. If it’s not already selected, press **Ctrl+Shift+P** (or **Cmd+Shift+P** on macOS), type `Python: Select Interpreter`, and choose your installed version of Python.
3. Now, you can run the program by opening the integrated terminal. Go to **Terminal > New Terminal** from the top menu.
4.  In the terminal window that opens at the bottom of VS Code, navigate to the folder where you saved `hello.py`. If the file is saved on your Desktop, you can type:



    ```bash
       cd Desktop
    ```
5.  Finally, run your Python program by typing the following command in the terminal:

    ```bash
       python hello.py
    ```
6. You should see the message `Hello, World!` displayed in the terminal. Congratulations! You’ve just written and executed your first Python program.

#### Step 4: Understanding the Output

When you run the program, Python executes the `print()` function, which outputs whatever is inside the parentheses. In this case, it prints the text "Hello, World!". This simple example demonstrates how Python interprets and runs code.

#### Step 5: Experimenting with Python

Now that you’ve successfully run your first program, feel free to experiment! Change the message inside the `print()` function to something different, like:

```python
print("Welcome to Python!")
```

Save the file, and run the program again using the same steps as before. You should now see the new message displayed in the terminal. By modifying small parts of the code and running it, you’ll start to understand how Python works and how to make the computer perform different tasks. This is just the beginning of what you can create with Python, and as you continue, you’ll learn to build more complex and interesting programs.



