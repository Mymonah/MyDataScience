
I started learning Python on April 11, 2025.
For anyone with a background in programming languages like C++ or Java, Python is generally easy to learn.
It is considered a high-level programming language, meaning its syntax is more similar to human language, making it more intuitive and readable.

---

### First we started with the environment setup:
Which refers to the platform where you can write and run your code to see results.<br/><br/>
In this case, we use **Google Colab**. As someone who enjoys learning abbreviations, I found it interesting to know that Colab stands for "Colaboratory"a blend of the words "collaboration" and "laboratory."<br/><br/>
It refers to an online environment (or virtual lab) where multiple people can collaborate in real time while experimenting, coding, and analyzing data—especially in fields like machine learning and data science.<br/><br/>
So, Google Colab (Collaboratory) is essentially a collaborative coding lab in the cloud, and is particularly well-suited for machine learning, data science, and educational purposes.<br/><br/>
It is a cloud-based, "as-a-service" version of **Jupyter Notebook** that allows you to write and execute Python code directly through your browser—no installation required.

**You can access Google Colab through Google Drive. Just follow these steps (see the image below):**

1. Open your Google Drive.
2. Right-click of My Drive.
3. Go to "More" in the menu.
4. If "Google Colaboratory" is listed, click it to create a new notebook.
5. If it’s not listed, select "Connect more apps".
6. Search for "Google Colaboratory".
7. Click "Connect" to add it to your Drive.
8. Once connected, you’ll be able to create and open Colab notebooks directly from your Google Drive.

<br/><br/>

<img src="/Assets/Python1.png" width="60%" align="center" alt="Python1.png">

<br/><br/>

--- 
*"You said **"Jupyter Notebook"!** what is that?"*<br/>

Jupyter Notebook is a tool you can use in your web browser to write and run code step by step.
It lets you see the results right away, which makes it perfect for learning, testing ideas, or doing data analysis.

Think of it like a digital notebook where:

- You write small pieces of code (called cells).
- You press a button to run each cell.
- The result appears just below it.
- You can also add notes and explanations between your code.

<br/><br/>
<img src="/Assets/Python2.png" width="60%" align="center" alt="Python2.png">
<br/><br/>

As shown in the image above, here are a few key points to help clarify how Jupyter Notebooks work:

1. The file extension for a Jupyter Notebook is **".ipynb"**, which stands for Interactive Python Notebook..
2. the **"+ Code"** is used to add new cell where you can write and run Python code.
3. the **"+ Text"** is used to add new cell  for writing text, formatted using Markdown—similar to how text is styled here on GitHub.
4. the play button icon ▶️ or (shift + Enter) is used to run the code in a selected cell. Note that the first time you open a Colab notebook, it might take a few moments to connect to the runtime before code can execute.

---
### Local IDE Setup

All of the options mentioned above are used when you want to write and execute code in a cloud-based environment, like Google Colab through Google Drive.
But what if you prefer to code and run everything on your local environment, directly on your personal computer?

In that case, you can use a more traditional approach—something developers have relied on for decades: an IDE (Integrated Development Environment).
One popular example is Visual Studio (or more commonly for Python development, Visual Studio Code) or pycharm.

Here's a simple step-by-step guide to set up Visual Studio Code (VS Code) for Python development on your local machine:

#### Step 1: Download and Install VS Code:
1. Go to the official website: https://code.visualstudio.com
2. Download the version for your operating system (Windows, macOS, or Linux).
3. Install it like any standard software.

#### Step 2: Install Python:
1. Visit https://www.python.org/downloads
2. Download the latest version of Python (e.g. Python 3.12).
3. Important: During installation, make sure to check the box that says "Add Python to PATH".

#### Step 3: Install Python Extension in VS Code
1. Open VS Code.
2. Go to the Extensions tab on the left sidebar (or press Ctrl+Shift+X).
3. Search for “Python” (by Microsoft).
4. Click Install.

#### Step 4: Create and Run a Python File
1. Create a new file and save it with a .py extension, for example: hello.py.

#### Optional (Recommended): Use Jupyter in VS Code
If you’re using Visual Studio Code, you can also:

1. Install the Jupyter extension from the Extensions tab (Ctrl+Shift+X).
2. Open any .ipynb file directly in VS Code and run cells like in a notebook

--- 
### Interpreter vs Compiler:
When you write code in Python, you don’t need to compile it first like you would in languages such as C++ or Java. Instead, Python uses an interpreter.

***What does that mean?***

A compiler takes all your code at once, turns it into a machine-language file, and then runs it.<br/>
An interpreter (like in Python) reads and runs your code line by line, instantly.

***Why is this useful?***

Because you can see results immediately, which is great for learning, testing, and quick feedback.<br/>
It’s easier to catch errors in small parts of your code without compiling the whole program.

