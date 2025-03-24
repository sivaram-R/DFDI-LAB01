# File Recovery using Autopsy

```
Register Number : 212222040121
Name : Praveen V
```
## AIM:

This experiment aims to demonstrate:

- Create a **Disk Partition**.  

- Adding, deleting, and recovering files using Autopsy.

- Understanding the forensic recovery of deleted data.

- Removing the disk partition after the process.

## Step1: Creating a Disk Partition
## 1.Open File Manager

- Right-click This PC → Click Show More Options.
  ![Screenshot 2025-03-19 220523](https://github.com/user-attachments/assets/8a7b99d9-bd5d-4b41-ad35-6d1301b5ff82)

- Select Manage.
  ![Screenshot 2025-03-19 220537](https://github.com/user-attachments/assets/df827a18-3894-4dbd-bbd3-a1b6eb8ae0b8)


## 2.Access Disk Management

- In the new window, select Disk Management.
  ![Screenshot 2025-03-19 220639](https://github.com/user-attachments/assets/9652e198-abd8-4f45-a689-a20f248bac2d)


## 3.Shrink the C Drive to Allocate Space

- Locate C: drive → Right-click → Select Shrink Volume.

- Enter the amount of memory to allocate for the new disk.

- Click Shrink.
  ![Screenshot 2025-03-19 220808](https://github.com/user-attachments/assets/6fdef27e-c4b2-43b6-b7e7-a280e377d7e7)


## 4.Create a New Volume

- Right-click on the newly unallocated space → Select New Simple Volume.
  ![Screenshot 2025-03-19 220859](https://github.com/user-attachments/assets/f6eb66bd-7167-4091-8504-5e859e6c995a)


- Follow the wizard and assign a disk name.
  ![Screenshot 2025-03-19 220922](https://github.com/user-attachments/assets/4fddc384-c0e2-4fe4-a268-f082a6c47389)


- Click Finish to complete the process.
  ![Screenshot 2025-03-19 220935](https://github.com/user-attachments/assets/f06a24e8-e373-4271-94bc-87cac73f6e27)
  
- The new Disk Partition is created as **PRAVEEN V**.
  ![Screenshot 2025-03-19 221000](https://github.com/user-attachments/assets/9b603c47-c7da-4012-9b35-3953cfeea86c)

  
## Step2: Adding Files

## 1.Copy Files to the Partition:

- Open File Explorer → Navigate to the newly created drive (C: or D:).

- Transfer images or files into it.
![Screenshot 2025-03-19 224841](https://github.com/user-attachments/assets/b9fdc15b-f166-435b-9b0d-cd5d40da55de)
## Step3: Analysing Files using Autopsy
## 1. Install and Open Autopsy
- Download and install Autopsy from its official website.

- Open Autopsy and create a new case.

## 2. Create a Case
- Enter a case name and select a location to store the case data.
  ![image](https://github.com/user-attachments/assets/d6f37baf-7bce-4abd-9281-cdb8f265c476)

- Provide a case number and investigator details if required.

## 3. Add a Data Source
- Click "Add Data Source" and choose the type:
  ![image](https://github.com/user-attachments/assets/a7721ece-2aee-4046-926e-e7437804758e)

- Select the data source and let Autopsy process it.

## 4. File Analysis
Autopsy will extract and categorize data. Key areas to check:

File System: View all files, deleted files, and hidden files.

Keyword Search: Look for specific terms in files.

Hash Set Analysis: Compare files against known hash databases.

Metadata Extraction: View timestamps, ownership, and file paths.

File Carving: Recover deleted or corrupted files.

Email and Chat Analysis: Extract email communications and chat logs.




