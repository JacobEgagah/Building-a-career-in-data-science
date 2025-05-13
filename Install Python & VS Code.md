>Here’s a clear, step-by-step guide for **downloading and installing Python and Visual Studio Code (VS Code)**, formatted for use in a `.ipynb` (Jupyter Notebook) or markdown file.

---

## 🧰 How to Download and Install Python & VS Code

---

### 🐍 1. Installing Python

1. **Go to the official Python website**:
   [https://www.python.org/downloads](https://www.python.org/downloads)

2. **Click on "Download Python 3.1.3"**
   (The website auto-detects your operating system)

3. **Run the Installer**:

   * Windows: Double-click the `.exe` file
   * macOS: Open the `.pkg` file
   * Linux: Use your package manager or install via source

4. ✅ **Important**: On Windows, check the box that says:
   `✔ Add Python to PATH`
📌 _Note_: The PATH setting is essential! It allows you to run Python from the command line.

6. Click **"Install Now"** and follow the prompts.
![Python Download Page](https://www.python.org/static/img/python-logo.png)
7. Verify installation:
   Open a terminal/command prompt and type:

   ```bash
   python --version
   ```

   You should see something like:

   ```
   Python 3.1.3
   ```

---

### 🖥️ 2. Installing Visual Studio Code (VS Code)

1. **Go to the official VS Code website**:
   [https://code.visualstudio.com](https://code.visualstudio.com)

2. **Click "Download for Windows/macOS/Linux"** (depending on your OS)

3. **Run the Installer**:

   * Follow the installation wizard
   * Optionally check:

     * ✔ Add to PATH
     * ✔ Register code as editor for supported file types

4. After installation, open **VS Code**

5. Install the **Python Extension**:

   * Open the Extensions view (left sidebar or `Ctrl+Shift+X`)
   * Search for `Python` and click **Install** on the one published by **Microsoft**

---

### 🧪 Testing Your Setup

1. Open a new file in VS Code
2. Save it as `test.py`
3. Type:

   ```python
   print("Hello, Jay!")
   ```
4. Right-click and select **Run Python File in Terminal**
   Or press `Ctrl+Alt+N` if using the **Code Runner** extension

✅ You should see:

```
Hello, Jay!
```

---

>🎉 You're now ready to start coding in Python using VS Code!
