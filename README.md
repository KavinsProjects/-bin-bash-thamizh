

# Software Installation Guide for Ubuntu

This guide provides steps to install the software on Ubuntu.

---

## 1. Google Chrome Browser

Steps to install the stable version of Google Chrome.

1.  Open your terminal (`Ctrl+Alt+T`).
2.  Update your package lists:
    ```bash
    sudo apt update
    ```
3.  Navigate to your Downloads folder:
    ```bash
    cd ~/Downloads
    ```
4.  Download the latest stable Chrome package (`.deb` file):
    ```bash
    wget [https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb](https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb)
    ```
5.  Install the package. **Method A** (recommended, handles dependencies) is generally preferred:

    **Method A:**
    ```bash
    sudo apt install ./google-chrome-stable_current_amd64.deb
    ```
    *If you use this method, you can skip step 6.*

    **Method B:**
    ```bash
    sudo dpkg -i google-chrome-stable_current_amd64.deb
    ```

6.  (Only if you used Method B) If you encounter any dependency errors, run the following command to fix them:
    ```bash
    sudo apt install -f
    ```
7.  Launch Chrome from your application menu or by typing:
    ```bash
    google-chrome
    ```

---

## 2. Visual Studio Code (VS Code)

Steps to install VS Code.

1.  Open your terminal (`Ctrl+Alt+T`) and update your package lists:
    ```bash
    sudo apt update
    ```
2.  Go to the official download page and download the **.deb (Debian/Ubuntu)** packages:
    > https://code.visualstudio.com/download
    
    Your browser will save it to your `~/Downloads` folder.

3.  Navigate to your Downloads folder in the terminal:
    ```bash
    cd ~/Downloads
    ```
4.  Install the package using `dpkg`. Make sure to replace `<filename>.deb` with the **exact name** of the file you just downloaded (e.g., `code_1.85.1-1702460838_amd64.deb`):
    
    ```bash
    # Replace <filename>.deb with the actual downloaded file name
    sudo dpkg -i <filename>.deb
    ```
    *Alternatively, you can use `apt` which also handles dependencies:*
    ```bash
    # Replace <filename>.deb with the actual downloaded file name
    sudo apt install ./<filename>.deb
    ```
5.  If you used `dpkg` and have any dependency issues, run:
    ```bash
    sudo apt install -f
    ```
6.  You're done! You can launch VS Code from your application menu or by typing `code` in the terminal.

   ---

## 3. installing notepad++ 

steps to install notepad++

1.  Open your terminal (`Ctrl+Alt+T`) and update your package lists:
    ```bash
    sudo apt update
    ```

2. install snap 
```bash
sudo snap  install snapd
```
3. install snap core
```bash
sudo snap install core
```
4. notepad++
```bash
sudo snap install notepad-plus-plus
```
