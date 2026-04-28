# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name: Preethi J
### Reg No: 212223220080
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.




### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version


## OUTPUT:
### i) VIRTUAL BOX:**
#### Virtual Box Official website.
<img width="1920" height="1080" alt="Screenshot (216)" src="https://github.com/user-attachments/assets/308ceb73-c65e-4391-b9e0-b03f384bebed" />

#### Downloaded .exe file
<img width="1920" height="456" alt="Screenshot (219)" src="https://github.com/user-attachments/assets/a65df7ca-170f-4c1e-97a1-df3cc7a3a488" />

#### Installer wizard
<img width="1920" height="1080" alt="Screenshot (221)" src="https://github.com/user-attachments/assets/21d2be4d-9dab-43bf-8f55-76bf7dd76449" />

#### Network Interfce warning
<img width="1920" height="1080" alt="Screenshot (222)" src="https://github.com/user-attachments/assets/67c31757-a2fc-4390-88bd-72eca6a2d96c" />

#### Installation Begins
<img width="1920" height="1080" alt="Screenshot (223)" src="https://github.com/user-attachments/assets/bc435a95-1977-4102-944a-9a1c04f52021" />

#### VirtualBox after launch
<img width="1920" height="1080" alt="Screenshot (224)" src="https://github.com/user-attachments/assets/5cd4dc67-42cb-45ee-874c-f9ad4ff50c39" />




### ii) KALI LINUX:

#### Installed Kali Linux 

<img width="1920" height="1080" alt="Screenshot (234)" src="https://github.com/user-attachments/assets/1d6ac4a8-74ee-4d18-bec4-295ebf49ceb0" />
<img width="1920" height="1080" alt="Screenshot (235)" src="https://github.com/user-attachments/assets/34a0ba64-373d-4e91-b50a-f4a9f1bb252d" />

#### kali linux terminal
<img width="1916" height="548" alt="image" src="https://github.com/user-attachments/assets/60eb2284-ef3d-4840-a304-1691d27491fa" />






### iii) SLEUTH-KIT:
<img width="1920" height="1080" alt="Screenshot (226)" src="https://github.com/user-attachments/assets/c55859bd-814f-4cdb-8000-7f7ca7be8f37" />
<img width="1920" height="1080" alt="Screenshot (227)" src="https://github.com/user-attachments/assets/3c85645e-ea6d-42c3-8a22-3d448824b0e5" />
<img width="1920" height="1080" alt="Screenshot (228)" src="https://github.com/user-attachments/assets/1d8c4a66-8e85-42bd-b2c9-4b231c313f61" />
<img width="1920" height="1080" alt="Screenshot (229)" src="https://github.com/user-attachments/assets/be906df8-9ac0-411c-ba43-8cad232a0e76" />
<img width="1920" height="1080" alt="Screenshot (230)" src="https://github.com/user-attachments/assets/b5300f35-9a79-42b9-be30-f7b6ee996353" />
<img width="1920" height="1080" alt="Screenshot (231)" src="https://github.com/user-attachments/assets/45e1fdef-0bbc-48f9-ac4a-05119277fda4" />
<img width="1920" height="1080" alt="Screenshot (232)" src="https://github.com/user-attachments/assets/8c56cbf9-0dfa-47ee-a7b4-175df9bde897" />
<img width="1920" height="1080" alt="Screenshot (233)" src="https://github.com/user-attachments/assets/98f29f03-b895-4a31-b460-d7c2f7af274d" />











## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
