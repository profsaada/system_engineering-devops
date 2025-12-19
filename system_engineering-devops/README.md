# system_engineering-devops

## 0x03-shell_variables_expansions

### Task 0: Aliases (0-alias)
- **Objective:** Understand what aliases are and how to create them.
- **Script:** 0-alias
- **Alias Created:** ls → rm *
- **Example Usage:**
```bash
julien@ubuntu:/tmp/0x03$ ls
0-alias  file1  file2
julien@ubuntu:/tmp/0x03$ source ./0-alias
julien@ubuntu:/tmp/0x03$ ls
julien@ubuntu:/tmp/0x03$ \ls
julien@ubuntu:/tmp/0x03$
```
- **Notes:** After executing the script, ls removes all files in the directory.

### Task 1: Hello You (1-hello_you)
- **Objective:** Create a bash script that prints a greeting to the current Linux user.
- **Script:** 1-hello_you
- **How it works:** Uses the $USER environment variable.
- **Example Usage:**
```bash
julien@ubuntu:/tmp/0x03$ chmod +x ./1-hello_you
julien@ubuntu:/tmp/0x03$ ./1-hello_you
hello julien
```
- **Notes:** Make sure the script is executable (chmod +x 1-hello_you) before running.

---

### General Notes
- All scripts are located inside 0x03-shell_variables_expansions/.
- Both root README.md and the folder README.md are non-empty to satisfy automated checks.
