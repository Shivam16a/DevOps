# Linux Administration and Bash Scripting Portfolio

Welcome to my DevOps repository! This documentation outlines various Linux administration tasks, file permission controls, user management, and Bash scripting exercises.

## 1. User and Group Management

Managing users, groups, and permissions to control access within the Linux system.

![User and Group Management](userandgroup_management.png)

### Key Commands:
```bash
sudo adduser shivam
sudo addgroup devops
sudo usermod -aG devops shivam
sudo gpasswd -d shivam devops
```

---

## 2. Advanced User Operations

Further verification of group permissions and user switching.

![User Management 2](User_management_2.png)

### Key Commands:
```bash
su - shivam
sudo gpasswd -a shivam devops
getent group
```

---

## 3. File Management and Permissions

Creating files, directories, and modifying access permissions using `chmod`.

![File Management](File_Management.png)

### Key Commands:
```bash
mkdir project
touch a.txt
chmod u+rw a.txt
ls -l
```

---

## 4. Directory & File Access Control

Modifying permissions for users, groups, and others on files and directories.

![File Management 2](File_management_2.png)

### Key Commands:
```bash
cd project/
chmod u+rwx g+rwx o+rwx a.txt
chmod u+x project/
```

---

## 5. Shell Scripting Basics

Writing, granting permissions, and executing custom shell scripts.

![Shell Script](Shell_script.png)

### Key Commands:
```bash
nano simple.sh
chmod u+x simple.sh
./simple.sh
```

---

## 6. Variables and Operations

Working with variables, operational logic, and executing scripts from different paths.

![Variable Operations](Var_Op.png)

### Key Commands:
```bash
nano var.sh
chmod u+x var.sh
./var.sh
```

## Author

**Shivam Kumar**  
GitHub: [@Shivam16a](https://github.com/Shivam16a)