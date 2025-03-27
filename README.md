# Analysing the Disk Files

```
Register Number : 212222100050
Name : Sivaram R
```
## AIM:

The primary aim of this report is to demonstrate the process of creating a disk partition, adding files, and analyzing them using Autopsy, a digital forensic tool.

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
![{57884EC8-F9A5-4FE9-AA1C-C134036B8706}](https://github.com/user-attachments/assets/043ad60d-9a3e-47b6-8819-14e71236ab1c)

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
- Application 
![image](https://github.com/user-attachments/assets/031432bf-1463-4a2a-a17a-b86ad5555fe6)

- File Metadata
![image](https://github.com/user-attachments/assets/4ebf6962-582b-4f42-b826-55b8a97aadfc)
![image](https://github.com/user-attachments/assets/e7851df5-4008-4054-aad1-990d8eb16b92)
![image](https://github.com/user-attachments/assets/467db963-048a-4ea0-aef5-cb9da966e8e0)

- OS Account
![image](https://github.com/user-attachments/assets/30ee87a7-6d71-424c-9f16-0b101c78ff15)

- Generate Report
![image](https://github.com/user-attachments/assets/5381eefd-7391-4e3f-b117-7d9f58fb5dec)


## Result
The process successfully demonstrated disk partitioning, file storage, and forensic analysis using Autopsy. The analysis provided valuable insights into file metadata and system account details.







