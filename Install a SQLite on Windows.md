#  Install a SQLite on Windows

> This topic describes how to install a SQLite on Windows.

## Procedure

Perform the following steps to install a SQLite on Windows:

1. Go to the [download page](https://sqlite.org/download.html) of the SQLite official website.

2. Download precompiled binaries for Windows: DLL package (containing `sqlite-dll` and `sqlite-shell` files) and `sqlite-tools-win32-x86-xxxxxxx.zip`. Select the DLL package that corresponds to your computer's OS. For example, download the following two packages for 64-bit Windows as shown below.
![](https://github.com/MeantForChange/SQLite-Installation-Guide/blob/master/img-folder/downloadpage.png)

3. Unzip the downloaded packages. You will obtain a program named `sqlite3.exe`. You can run this program to use SQLite in the directory where the packages are extracted. If you want to run SQLite in any directory, continue the following steps.

4. Create a folder e.g., `c:\sqlite` in the system root directory and put the extracted files into the folder. You should see the following files in the folder as shown below:
![](https://github.com/MeantForChange/SQLite-Installation-Guide/blob/master/img-folder/sqliteforenglish.png)

5. Add `c:\sqlite` to your Path variable, as shown below:
![](https://github.com/MeantForChange/SQLite-Installation-Guide/blob/master/img-folder/setenvironmentvariable.png)

6. Open the Command Prompt, type `sqlite3`, and  press Enter. You should see the following output:
![](https://github.com/MeantForChange/SQLite-Installation-Guide/blob/master/img-folder/commandoutput.png)
