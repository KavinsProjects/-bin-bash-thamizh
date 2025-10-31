# 💻 Basic System Commands (Basic Commands Tamil+English style)

| Command | Description (Tanglish) |
|----------|-----------------------|
| `pwd` | Current directory path kaamikkum (enga irukke nu sollum) |
| `uname -a` | OS version details ellam kaamikkum |
| `whoami` | Neenga login panna user name sollum |
| `clear` | Terminal screen ah clean pannum |
| `history` | Munnaadi use panna commands list kaamikkum |
| `sudo` | Superuser permission kuduthu command run pannum (admin maari) |

---

## ✍️ `vi` Text Editor la Work Panna

| Action | Command / Shortcut | Description (Tanglish) |
|---------|-------------------|-------------------------|
| Open a file | `vi hello.txt` | File open pannum |
| Insert mode ku poganum | Press `i` | Typing mode la pogum |
| Save & Exit | `Esc` press pannitu `:wq` type pannunga, then Enter |
| Exit without save | `Esc` press pannitu `:q!` type pannunga |
| Delete full line | Normal mode la `dd` type pannunga |

---

## 📂 Files & Directory Management

| Command | Description (Tanglish) |
|----------|----------------------|
| `mkdir foldername` | New folder create pannum |
| `touch filename` | Empty file create pannum |
| `rm filename` | File delete pannum |
| `rm *.txt` | Ella `.txt` files ah delete pannum current directory la |
| `cat filename` | File oda content kaamikkum |
| `cp source.txt destination.txt` | File copy pannum |
| `cat source.txt >> destination.txt` | One file content another file ku append pannum |
| `echo "your text"` | Terminal la text display pannum |
| `history >> commands.txt` | Command history file la save pannum |

---

# 🧰 Software Install Guide for Ubuntu.

## 1️⃣ Google Chrome Install panna

1. Terminal open pannunga (`Ctrl+Alt+T`).
2. Package list update pannunga:
    ```bash
    sudo apt update
    ```
3. Downloads folder ku poganum:
    ```bash
    cd ~/Downloads
    ```
4. Chrome `.deb` package download pannunga:
    ```bash
    wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
    ```
5. Install pannuradhu ku two methods irukku 👇

    **Method A (Recommended – easy da!):**
    ```bash
    sudo apt install ./google-chrome-stable_current_amd64.deb
    ```

    **Method B:**
    ```bash
    sudo dpkg -i google-chrome-stable_current_amd64.deb
    ```

6. Dependency error vandha fix pannunga:
    ```bash
    sudo apt install -f
    ```

7. Chrome open panna:
    ```bash
    google-chrome
    ```

---

## 2️⃣ Visual Studio Code (VS Code) Install panna

1. Terminal open pannunga (`Ctrl+Alt+T`) → update package list:
    ```bash
    sudo apt update
    ```

2. Official website ku poi `.deb` package download pannunga:  
   👉 https://code.visualstudio.com/download

3. Downloads folder ku poganum:
    ```bash
    cd ~/Downloads
    ```

4. Install pannunga (filename replace pannunga with actual name):
    ```bash
    sudo dpkg -i <filename>.deb
    ```

   or better way 👇
    ```bash
    sudo apt install ./<filename>.deb
    ```

5. Dependency problem vandha fix pannunga:
    ```bash
    sudo apt install -f
    ```

6. Done da! VS Code open panna just type pannunga:
    ```bash
    code
    ```

---

## 3️⃣ Notepad++ Install panna (snap use pannuvom)

1. Terminal open pannunga (`Ctrl+Alt+T`) → update pannunga:
    ```bash
    sudo apt update
    ```

2. Snap install panna:
    ```bash
    sudo snap install snapd
    ```

3. Snap core install panna:
    ```bash
    sudo snap install core
    ```

4. Finally Notepad++ install pannunga:
    ```bash
    sudo snap install notepad-plus-plus
    ```
## hide nothing

That's it bro 😎 — ippo notepad++ ready ah use panna mudiyum Ubuntu la!
