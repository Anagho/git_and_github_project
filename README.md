# Instructions

1. Create a folder called `learn_git`.
    ```sh
    mkdir learn_git
    ```
2. Change directory into the `learn_git` folder:
    ```sh
    cd learn_git
    ```
3. Create a file called `third.txt`:
    ```sh
    touch third.txt
    ```
4. Initialize an empty git repository:
    ```sh
    git init
    ```
5. Add `third.txt` to the staging area:
    ```sh
    git add third.txt
    ```
6. Commit with the message "adding third.txt":
    ```sh
    git commit -m "adding third.txt"
    ```
7. Check out your commit with `git log`:
    ```sh
    git log
    ```
8. Create another file called `fourth.txt`:
    ```sh
    touch fourth.txt
    ```
9. Add `fourth.txt` to the staging area:
    ```sh
    git add fourth.txt
    ```
10. Commit with the message "adding fourth.txt":
    ```sh
    git commit -m "adding fourth.txt"
    ```
11. Remove the `third.txt` file:
    ```sh
    rm third.txt
    ```
12. Add this change to the staging area:
    ```sh
    git add .
    ```
13. Commit with the message "removing third.txt":
    ```sh
    git commit -m "removing third.txt"
    ```
14. Check out your commits using `git log`:
    ```sh
    git log
    ```
15. Change your global settings to `core.pager=cat`:
    ```sh
    git config --global core.pager cat
    ```
16. Write the appropriate command to list all the global configurations for git on your machine:
    ```sh
    git config --global --list
    ```
    You can type `git config --global` to find out how to do this.
