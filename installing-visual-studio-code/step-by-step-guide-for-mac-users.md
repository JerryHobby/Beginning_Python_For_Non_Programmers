# Step-by-step guide for Mac Users

Visual Studio Code (VS Code) is a powerful, free code editor that's perfect for Python development. Follow these steps to install and set up VS Code on your Mac.

#### Step 1: Download Visual Studio Code

1. Open your web browser and go to the official VS Code website: [https://code.visualstudio.com](https://code.visualstudio.com).
2. On the homepage, click the **Download for macOS** button. This will download the `.zip` file containing VS Code for macOS.

#### Step 2: Install Visual Studio Code

1. Once the download is complete, open your **Downloads** folder and locate the `.zip` file.
2. Double-click the `.zip` file to extract the contents. This will create a new file named **Visual Studio Code.app**.
3. Drag the **Visual Studio Code.app** file into your **Applications** folder to install VS Code.

#### Step 3: Open Visual Studio Code

1. Go to your **Applications** folder and find **Visual Studio Code**.
2. Double-click the application to launch it. If a security message pops up (since the app was downloaded from the internet), click **Open** to proceed.

#### Step 4: Install the Python Extension

1. Once VS Code opens, you’ll need to install the Python extension to enable features like syntax highlighting, code completion, and debugging.
2. On the left side of the VS Code window, click the **Extensions** icon (or press **Cmd+Shift+X**).
3. In the Extensions search bar, type **Python**.
4. Select the extension titled **Python** (by Microsoft) and click the **Install** button.
5. After the extension is installed, VS Code will be ready for Python development.

#### Step 5: Verify Python is Installed in VS Code

1. After installing the Python extension, VS Code will try to automatically detect the Python interpreter installed on your system.
2. To manually verify this, open the **Command Palette** by pressing **Cmd+Shift+P**, then type `Python: Select Interpreter`.
3. You should see a list of Python versions available on your Mac. Select the correct version (typically the latest one).

#### Step 6: Add VS Code to PATH (Optional)

1. If you want to open VS Code from the terminal with the `code` command, you can add VS Code to your PATH.
2. Open VS Code and press **Cmd+Shift+P** to open the **Command Palette**.
3. Type `Shell Command: Install 'code' command in PATH` and select the option. This will allow you to run `code .` from the terminal to open the current directory in VS Code.

***

You’ve now successfully installed Visual Studio Code and set it up for Python development on your Mac! Next, we’ll guide you through writing and running your first Python program in VS Code.
