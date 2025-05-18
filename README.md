# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img  (sleuth-kit)
sudo fdisk -l ~/disk.img (GNU)

```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/675bd73a-9c43-45a3-bf62-ff59e333f70e)


![image](https://github.com/user-attachments/assets/b01bb820-3241-40c5-adbb-36c789b2ebbc)

![image](https://github.com/user-attachments/assets/727dadea-d82b-4166-9f48-cd9604b8f84b)

![image](https://github.com/user-attachments/assets/095f9b08-a4eb-49d8-ae01-df1ee80dbd04)


![image](https://github.com/user-attachments/assets/3f4b280d-74d6-4b15-9fd5-76033458c1e5)


![image](https://github.com/user-attachments/assets/9dda405a-393f-45c2-80ab-a4691831fc1e)



## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
