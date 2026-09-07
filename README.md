# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="1600" height="899" alt="dfd 1" src="https://github.com/user-attachments/assets/4f2a44db-038a-452b-a0e9-38bcf39ed1e9" />
<img width="1600" height="899" alt="dfd 2" src="https://github.com/user-attachments/assets/c278f260-c299-472f-ae5f-a00282bef515" />
<img width="1600" height="899" alt="dfd 3" src="https://github.com/user-attachments/assets/523a07c2-639a-4935-b2d5-d6121a8f97d4" />
<img width="1600" height="899" alt="dfd 4" src="https://github.com/user-attachments/assets/81827e0f-a6a6-4f58-9122-824c5483e044" />
<img width="1600" height="899" alt="dfd 5" src="https://github.com/user-attachments/assets/c541e560-0426-4e6f-b2e8-bb61c083c8ad" />
<img width="1600" height="899" alt="dfd 6" src="https://github.com/user-attachments/assets/231207ce-9d60-4379-a9b3-59451a71400a" />
<img width="1600" height="899" alt="dfd 7" src="https://github.com/user-attachments/assets/8c28581f-efff-4632-8984-2c92e93bfa32" />




















## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
