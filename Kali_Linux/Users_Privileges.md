# Linux File Permissions and User Management

### File and Directory Indicators
- **`-`** at the start indicates it's a **file**.

    ![image](https://github.com/user-attachments/assets/1afea39f-8028-4620-9af2-3a01d7f96771)

- **`d`** at the start indicates it's a **directory**.

  ![image](https://github.com/user-attachments/assets/a55d881e-1e6b-431f-94c6-3996db64afad)



  ![image](https://github.com/user-attachments/assets/2d035399-49e3-453b-9198-14a859129bb8)


### `rwx`
- **`rwx`** stands for **read**, **write**, and **execute** permissions. It's divided into three parts:
  - The **first** bit represents the **owner** of the file.
  - The **second** bit represents **members** who own the file or have access.
  - The **third** bit represents **all users** on the system.

### `chmod`
- **`chmod`** is used to **change the permissions** of a file or directory.
  - Example: `chmod rw hello.txt` to set read and write permissions.
  - You can use **numeric permissions** like `777` to grant **read, write, and execute access** to everyone: `chmod 777 hello.txt`.
 
    ![image](https://github.com/user-attachments/assets/32f9033d-d0a7-4736-8859-6f72b3b70d7b)


### `adduser`
- **`adduser`** is used to **add a new user** to the system.
  - Syntax: `adduser <username>`

### `su`
- **`su`** means **switch user**.
  - Syntax: `su <username>` to switch to a specific user.

### Important Directories and Files
- **`cat /etc/passwd`**: Displays **all current users** on the machine.
- **`cat /etc/shadow`**: Displays **hashed passwords** of the current users.
