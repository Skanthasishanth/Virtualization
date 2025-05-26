# Virtualization
### NAME: Kantha Sishanth S
### REG NO: 212222100020

## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox

## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:

* Machine with Internet access
* Minimum 4 GB RAM
* Sufficient storage space

## Steps:
1. Download Oracle VM VirtualBox:

    * Visit Oracle VirtualBox Official Site
    * Download installer for your OS (Windows/macOS/Linux).
2. Install Oracle VM VirtualBox (Example: Windows):

    * Launch Installer → Allow Changes → Click Next.
    * Choose Installation Options → Click Next.
    * Accept Network Interface Warning → Click Yes.
    * Click Install.
    * Finish Installation and Launch VirtualBox.
3. Configure VirtualBox:

    * Open VirtualBox.
    * Click New → Name VM → Select Type (Linux/Windows) and Version.
    * Allocate:
        * Minimum 2 GB RAM
        * Create Virtual Hard Disk (20 GB recommended).
    * Start Virtual Machine and provide ISO to install OS.

## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux

## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
* Oracle VM VirtualBox Installed
* 4 GB RAM and 20 GB Storage Minimum
* Kali Linux ISO image

## Steps:
1. Download Kali Linux ISO:

    * Visit Kali Linux Official Site
    * Download 64-bit ISO (Installer version).
2. Create a New Virtual Machine:

    * Open VirtualBox → Click New.
    * Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
3. Allocate Memory:

    * Minimum 2 GB RAM (recommended 4 GB).
4. Create Virtual Hard Disk:

    * Select VDI (VirtualBox Disk Image).
    * Choose Dynamically allocated.
    * Set Disk size to 20 GB or more.
5. Configure ISO Image:

    * Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
6. Start Installation:

    * Boot Virtual Machine → Choose Graphical Install.
    * Set Language, Region, Keyboard.
    * Configure Network → Set Hostname (e.g., kali).
    * Set root password.
    * Disk Partitioning: Use entire disk → All files in one partition.
    * Install System → Install GRUB Bootloader → Finish Installation.
7. Login to Kali Linux:

    * Use root credentials.
8. (Optional) Install Guest Additions:

    * Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

## Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox

![3333a](https://github.com/user-attachments/assets/9e137d35-0af0-4eab-a64c-3bd327f2d56e)


Snapshot 2: Kali Running in Virtual

![3333b](https://github.com/user-attachments/assets/7ee10442-8f08-4229-8f57-5d3f78901b1f)


## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali

## About Linux:
* Open-source operating system.
* Kernel manages communication between hardware and software.
* Commands are case-sensitive.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 

```bash
ls
```

**Output:**

![OP_1](https://github.com/user-attachments/assets/5d344db6-ae34-4394-b4b8-12a61c2d7ed8)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**

```bash
pwd
```

**Output:**

![OP_2](https://github.com/user-attachments/assets/dffd8bd8-6d2d-46be-bc39-39e247cb678d)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**

```bash
mkdir <directory_name>
```

**Output:**

![OP_3](https://github.com/user-attachments/assets/de1c39be-2660-4aba-89b3-61fe7a2d9782)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**

```bash
rmdir <directory_name>
```

**Output:**

![OP_4](https://github.com/user-attachments/assets/1ea16844-0967-4eae-a196-77c669c027c6)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**

```bash
cd <directory_name>
```

**Output:**

![OP_5](https://github.com/user-attachments/assets/ff9bbe6f-c0ab-452e-b187-f85af69b8711)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**

```bash
cat [OPTION]... [FILE]...
```

**Output:**

![OP_6](https://github.com/user-attachments/assets/a6bfd8fa-60c5-404e-bfe8-628ab67fbdba)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**

```bash
cp <source_file> <destination_file>
```

**Output:**

![OP_7](https://github.com/user-attachments/assets/0945919a-10ee-4e9e-8ff1-1a6751f43ae6)


### 8. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**

```bash
mv <file_name> <directory_path>
```

**Output:**

![OP_9](https://github.com/user-attachments/assets/7fd6a0f7-20f9-43f3-b610-d44b13eb0b66)


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**

```bash
su <username>
```

**Output:**

![OP_8](https://github.com/user-attachments/assets/a1cf4bb5-ea25-4210-8b6e-4774ed1667d3)


### 10. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**

```bash
host <domain_name> or <ip_address>
```

**Output:**

![OP_10](https://github.com/user-attachments/assets/488b30a6-6465-430e-9c90-0ab06cd1bc7c)


## Result:
Linux commands are executed in the linux terminal successfully.
